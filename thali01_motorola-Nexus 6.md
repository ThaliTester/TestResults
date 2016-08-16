#### Test 813219427e676a1_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 19:31:39.593   873  1837 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:31:40.248  3798  3798 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 19:31:40.253  3798  3798 D AndroidRuntime: CheckJNI is OFF
08-16 19:31:40.295  3798  3798 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 19:31:40.344  3798  3798 I Radio-JNI: register_android_hardware_Radio DONE
08-16 19:31:40.367  3798  3798 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 19:31:40.373   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 19:31:40.404  2002  2014 W SearchService: Abort, client detached.
08-16 19:31:40.407  3798  3798 D AndroidRuntime: Shutting down VM
08-16 19:31:40.417  2002  2311 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@f13f36b
08-16 19:31:40.417  2002  2002 I HotwordDetector: Closing mic
08-16 19:31:40.419  2002  2328 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 19:31:40.437   873  1939 I ActivityManager: Start proc 3807:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 19:31:40.469   376  2330 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 19:31:40.473   376  2330 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 19:31:40.476   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 19:31:40.477  2002  2327 I MicroRecognitionRnrImpl: Detection finished
08-16 19:31:40.478  2002  2319 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 19:31:40.523  3807  3807 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 19:31:40.545  3807  3807 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 19:31:40.551  3807  3807 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1859-1862)
08-16 19:31:40.551  3807  3807 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 19:31:40.568  3807  3807 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4cbd4ae}
08-16 19:31:40.569  3807  3807 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 19:31:40.569  3807  3807 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 19:31:40.574  3807  3807 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 19:31:40.575  3807  3807 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 19:31:40.588  3807  3807 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 19:31:40.597  3807  3807 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 19:31:40.597  3807  3807 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 19:31:40.597  3807  3807 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 19:31:40.597  3807  3807 I Adreno  : Build Date                       : 10/20/15
08-16 19:31:40.597  3807  3807 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 19:31:40.597  3807  3807 I Adreno  : Local Branch                     : M14
08-16 19:31:40.597  3807  3807 I Adreno  : Remote Branch                    : 
08-16 19:31:40.597  3807  3807 I Adreno  : Remote Branch                    : 
08-16 19:31:40.597  3807  3807 I Adreno  : Reconstruct Branch               : 
,08-16 19:31:40.631   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1b4baa:true
,08-16 19:31:40.669  3807  3807 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 19:31:40.680  3807  3807 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 19:31:40.728  3807  3848 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 19:31:40.752  3807  3834 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 19:31:40.789  3807  3848 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 19:31:40.832   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +421ms
,08-16 19:31:40.839  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-16 19:31:40.899  3807  3807 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3807
,08-16 19:31:41.006  3807  3807 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 19:31:41.226   873  1372 I ActivityManager: Killing 2960:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 19:31:41.249  3807  3850 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1680410320
,08-16 19:31:41.254   873  1372 I ActivityManager: Killing 3213:com.google.android.gm/u0a78 (adj 15): empty #18
,08-16 19:31:41.260  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 19:31:41.260  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 19:31:41.260  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 19:31:41.260  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 19:31:41.260  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 19:31:41.260  3807  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2228d2 added. We now have 1 listener(s)
08-16 19:31:41.263  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 19:31:41.264  3807  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 19:31:41.264  3807  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:31:41.264  3807  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 19:31:41.268  3807  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9af3c59 added. We now have 1 listener(s)
,08-16 19:31:41.268  3807  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:31:41.273   873  1309 D WifiService: New client listening to asynchronous messages
,08-16 19:31:41.273  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 19:31:41.273  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 19:31:41.274  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 19:31:41.274  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
08-16 19:31:41.274  3807  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 19:31:41.302  3807  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:31:41.302  3807  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 19:31:41.308  3807  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 19:31:41.309  3807  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:31:41.309  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:41.309  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:41.309  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:41.309  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:31:41.309  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:31:41.309  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:41.309  3807  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 19:31:41.309  3807  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 19:31:41.309  3807  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 19:31:41.310  3807  3850 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 19:31:41.348  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:41.350  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:41.352  3807  3807 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 19:31:41.472   873  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 19:31:42.294  3807  3859 W jxcore-log: Initializing JXcore engine
,08-16 19:31:42.295  3807  3859 W jxcore-log: JXcore engine is ready
,08-16 19:31:42.335  3859  3859 W Thread-331: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8958 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 19:31:42.335  3859  3859 W Thread-331: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11583]" dev="sockfs" ino=11583 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 19:31:42.335  3859  3859 W Thread-331: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 19:31:42.335  3859  3859 W Thread-331: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26090]" dev="sockfs" ino=26090 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 19:31:42.350  3807  3859 W jxcore-log: Starting JXcore engine
,08-16 19:31:42.465  3807  3859 W jxcore-log: Platform android
08-16 19:31:42.465  3807  3859 W jxcore-log: 
,08-16 19:31:42.465  3807  3859 W jxcore-log: Process ARCH arm
08-16 19:31:42.465  3807  3859 W jxcore-log: 
,08-16 19:31:42.688  3807  3859 I jxcore-log: JXcore Cordova bridge is ready!
08-16 19:31:42.688  3807  3859 I jxcore-log: 
08-16 19:31:42.688  3807  3859 W jxcore-log: JXcore engine is started
,08-16 19:31:42.699  3807  3850 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 19:31:42.703  3807  3807 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 19:31:46.515  3613  3866 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 19:31:46.530  3613  3867 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 19:31:46.543  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:31:46.544  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:31:46.565  1516  2251 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 19:31:46.565  1516  2251 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 19:31:46.565  1516  2251 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 19:31:46.565  1516  2251 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:31:46.590  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:31:46.593  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:31:46.617  1516  2086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 19:31:46.617  1516  2086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 19:31:46.618  1516  2086 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:31:46.618  1516  2086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:31:46.640  3613  3867 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 19:31:46.641  3613  3866 E BooksSync: Soft error
08-16 19:31:46.641  3613  3866 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:31:46.641  3613  3866 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 19:31:46.641  3613  3866 E BooksSync: Sync error
08-16 19:31:46.641  3613  3866 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:31:46.641  3613  3866 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 19:31:46.641  3613  3866 I BooksSync: Finished books sync
,08-16 19:31:46.653   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127764, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:31:49.167   873  1837 D NetlinkSocketObserver: NeighborEvent{elapsedMs=130477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 19:31:50.688  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:31:50.693  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 19:31:50.694  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:31:50.713  1516  2882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 19:31:50.713  1516  2882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 19:31:50.713  1516  2882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:31:50.713  1516  2882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:31:50.729  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 19:31:50.729  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 19:31:50.729  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-16 19:31:58.558  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 19:31:58.558  3807  3859 I jxcore-log: 
,08-16 19:31:58.560  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 19:31:58.560  3807  3859 I jxcore-log: 
,08-16 19:31:58.572  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:31:58.572  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:58.572  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:58.572  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:58.572  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:31:58.572  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:31:58.572  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:58.572  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:31:58.579  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:31:58.585  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 19:31:58.585  3807  3859 I jxcore-log: 
,08-16 19:31:58.592  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 19:31:58.592  3807  3859 I jxcore-log: 
,08-16 19:31:58.950  3807  3859 D ExecuteNativeTests: Running unit tests
,08-16 19:31:59.009  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 19:31:59.009  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf added. We now have 2 listener(s)
,08-16 19:31:59.010  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 19:31:59.011  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:31:59.011  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 19:31:59.011  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 19:31:59.011  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c added. We now have 2 listener(s)
08-16 19:31:59.011  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:31:59.011  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 19:31:59.017  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:31:59.034  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:31:59.034  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.034  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.034  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:59.034  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:31:59.034  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:31:59.034  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:59.034  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:31:59.036  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:31:59.037  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 19:31:59.039  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 19:31:59.041  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 19:31:59.041  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 19:31:59.042  3807  3859 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 19:31:59.042  3807  3859 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 19:31:59.042  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 19:31:59.042  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 19:31:59.043  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 19:31:59.043  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.043  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.043  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.044  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.044  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.044  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:31:59.044  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 19:31:59.044  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf removed from the list
08-16 19:31:59.044  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.044  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c removed from the list
08-16 19:31:59.045  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:31:59.045  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.045  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.046  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.047  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.047  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 19:31:59.048  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.048  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.048  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.049  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:31:59.050  3807  3859 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 19:31:59.050  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 19:31:59.050  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.050  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.050  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.050  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.051  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.051  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.051  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.051  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.051  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 19:31:59.051  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.051  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.051  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.051  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.052  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.052  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.052  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.052  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
,08-16 19:31:59.057  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 19:31:59.057  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 19:31:59.058  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 19:31:59.059  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 19:31:59.059  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.059  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.059  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.060  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.060  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.060  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.060  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.060  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:31:59.060  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.060  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.060  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.060  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.060  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.060  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.061  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.061  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.061  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.061  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.062  3807  3859 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 19:31:59.063  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.066  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:31:59.066  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.066  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.066  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:59.066  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:31:59.066  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:31:59.066  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:59.066  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:31:59.067  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:31:59.068  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 19:31:59.068  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 19:31:59.068  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 19:31:59.068  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 19:31:59.068  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.068  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:31:59.070  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:31:59.071  3807  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:31:59.072  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 19:31:59.072  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:59.077  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 19:31:59.079  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 19:31:59.079  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 19:31:59.082  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-16 19:31:59.086  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-16 19:31:59.086  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 19:31:59.087  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 19:31:59.089  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 19:31:59.090  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:31:59.099  2609  2621 D BtGatt.GattService: registerClient() - UUID=ecdb9380-6838-43bc-8c5e-1b68fbda548c
,08-16 19:31:59.100  2609  2645 D BtGatt.GattService: onClientRegistered() - UUID=ecdb9380-6838-43bc-8c5e-1b68fbda548c, clientIf=5
08-16 19:31:59.100  3807  3819 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 19:31:59.102  2609  2619 D BtGatt.GattService: start scan with filters
,08-16 19:31:59.104  2609  2661 D BtGatt.ScanManager: handling starting scan
,08-16 19:31:59.106  2609  2661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:31:59.106  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 19:31:59.108  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 19:31:59.109  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 19:31:59.109  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 19:31:59.115  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 19:31:59.116  2609  2645 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 19:31:59.116  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.116  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 19:31:59.117  2609  2661 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 19:31:59.117  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 19:31:59.118  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 19:31:59.120  3807  3859 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 19:31:59.133  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 19:31:59.133  3807  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 19:31:59.133  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 19:31:59.134  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 19:31:59.134  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.134  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 19:31:59.134  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 19:31:59.134  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 19:31:59.134  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 19:31:59.134  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 19:31:59.134  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 19:31:59.134  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 19:31:59.137  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:31:59.138  2609  2621 D BtGatt.GattService: stopScan() - queue size =1
,08-16 19:31:59.138  2609  2619 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 19:31:59.143  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.143  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 19:31:59.143  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 19:31:59.143  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 19:31:59.144  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 19:31:59.147  2609  2645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 19:31:59.147  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.147  2609  2661 D BtGatt.ScanManager: Starting BLE batch scan
08-16 19:31:59.147  2609  2661 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 19:31:59.148  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 19:31:59.149  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.149  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 19:31:59.150  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:31:59.151  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 19:31:59.153  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 19:31:59.153  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.153  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 19:31:59.154  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.154  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.154  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 19:31:59.155  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
,08-16 19:31:59.156  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 19:31:59.156  3807  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 19:31:59.155  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.156  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
,08-16 19:31:59.156  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.157  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:31:59.157  3807  3859 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 19:31:59.158  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.160  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 19:31:59.161  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 19:31:59.161  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 19:31:59.161  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:31:59.162  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 19:31:59.165  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:31:59.165  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.165  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.165  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:59.165  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:31:59.165  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:31:59.165  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:59.165  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:31:59.166  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 19:31:59.167  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.167  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 19:31:59.167  2609  2645 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 19:31:59.167  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.168  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:31:59.168  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 19:31:59.168  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 19:31:59.168  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 19:31:59.169  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:31:59.170  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 19:31:59.173  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 19:31:59.179  2609  2645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 19:31:59.179  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.180  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 19:31:59.180  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 19:31:59.180  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.180  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 19:31:59.183  3807  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 19:31:59.185  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:59.188  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 19:31:59.188  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 19:31:59.188  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 19:31:59.188  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:31:59.190  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:59.191  2609  2621 D BtGatt.GattService: registerClient() - UUID=313b8e37-ff73-475d-b9eb-1447e1c64e08
08-16 19:31:59.191  2609  2645 D BtGatt.GattService: onClientRegistered() - UUID=313b8e37-ff73-475d-b9eb-1447e1c64e08, clientIf=5
08-16 19:31:59.191  3807  3817 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 19:31:59.192  2609  2619 D BtGatt.GattService: start scan with filters
,08-16 19:31:59.195  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 19:31:59.195  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 19:31:59.195  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 19:31:59.195  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 19:31:59.196  2609  2645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 19:31:59.196  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:31:59.197  2609  2661 D BtGatt.ScanManager: stopping BLe Batch
,08-16 19:31:59.197  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 19:31:59.197  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 19:31:59.198  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 19:31:59.198  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 19:31:59.200  3807  3859 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 19:31:59.202  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.202  3807  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 19:31:59.202  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.202  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 19:31:59.202  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.202  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 19:31:59.202  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 19:31:59.202  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 19:31:59.203  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 19:31:59.203  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 19:31:59.203  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 19:31:59.203  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 19:31:59.204  3807  3859 D BluetoothAdapter: STATE_ON,
08-16 19:31:59.204  2609  2621 D BtGatt.GattService: stopScan() - queue size =0
08-16 19:31:59.205  2609  2645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 19:31:59.205  2609  2742 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 19:31:59.205  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:31:59.205  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 19:31:59.205  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 19:31:59.205  2609  2661 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 19:31:59.205  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 19:31:59.205  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 19:31:59.205  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 19:31:59.206  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 19:31:59.206  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 19:31:59.206  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 19:31:59.206  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:31:59.207  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 19:31:59.208  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 19:31:59.208  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:31:59.208  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 19:31:59.210  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:31:59.210  3807  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 19:31:59.211  2609  2645 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 19:31:59.211  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.211  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 19:31:59.212  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 19:31:59.213  2609  2661 D BtGatt.ScanManager: handling starting scan
08-16 19:31:59.212  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.213  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 19:31:59.213  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 19:31:59.213  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 19:31:59.213  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 19:31:59.213  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
,08-16 19:31:59.214  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:31:59.214  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:31:59.216  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.217  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 19:31:59.217  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.219  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 19:31:59.219  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-16 19:31:59.219  2609  2645 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 19:31:59.219  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:31:59.219  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:31:59.219  2609  2661 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 19:31:59.221  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:31:59.221  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 19:31:59.222  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.224  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 19:31:59.224  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.224  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.225  2609  2645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 19:31:59.225  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.225  2609  2661 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 19:31:59.225  2609  2661 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 19:31:59.226  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 19:31:59.227  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.227  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.227  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:31:59.227  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.228  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 19:31:59.228  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.228  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.228  3807  3859 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
08-16 19:31:59.230  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:31:59.233  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:31:59.233  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.233  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.233  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:59.233  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:31:59.233  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:31:59.233  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:59.233  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:31:59.235  2609  2645 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 19:31:59.235  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:31:59.235  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 19:31:59.236  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 19:31:59.236  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 19:31:59.236  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 19:31:59.236  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 19:31:59.236  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.236  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 19:31:59.237  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:59.241  2609  2645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 19:31:59.241  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.241  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:59.242  3807  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 19:31:59.247  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 19:31:59.247  2609  2645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 19:31:59.248  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:31:59.248  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 19:31:59.248  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 19:31:59.248  2609  2661 D BtGatt.ScanManager: stopping BLe Batch
,08-16 19:31:59.249  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.250  2609  2621 D BtGatt.GattService: registerClient() - UUID=7279aafe-0f79-4c07-adcf-d06621fa5656
08-16 19:31:59.251  2609  2645 D BtGatt.GattService: onClientRegistered() - UUID=7279aafe-0f79-4c07-adcf-d06621fa5656, clientIf=5
,08-16 19:31:59.251  3807  3821 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 19:31:59.251  2609  2619 D BtGatt.GattService: start scan with filters
,08-16 19:31:59.254  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 19:31:59.254  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 19:31:59.254  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 19:31:59.254  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 19:31:59.255  2609  2645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 19:31:59.255  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.255  2609  2661 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 19:31:59.256  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 19:31:59.256  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 19:31:59.256  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 19:31:59.257  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 19:31:59.259  3807  3859 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 19:31:59.259  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.259  3807  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 19:31:59.259  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.259  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 19:31:59.259  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.259  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 19:31:59.259  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 19:31:59.259  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 19:31:59.260  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 19:31:59.260  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 19:31:59.260  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 19:31:59.260  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 19:31:59.260  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:31:59.261  2609  2742 D BtGatt.GattService: stopScan() - queue size =0
08-16 19:31:59.261  2609  2645 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 19:31:59.261  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.261  2609  2752 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 19:31:59.261  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 19:31:59.261  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 19:31:59.261  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 19:31:59.261  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 19:31:59.261  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 19:31:59.262  2609  2661 D BtGatt.ScanManager: handling starting scan
08-16 19:31:59.262  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 19:31:59.262  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 19:31:59.262  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 19:31:59.262  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 19:31:59.263  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:31:59.263  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 19:31:59.263  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.263  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:31:59.265  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:31:59.265  3807  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 19:31:59.268  2609  2645 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 19:31:59.268  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:31:59.268  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 19:31:59.268  2609  2661 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 19:31:59.268  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 19:31:59.268  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 19:31:59.268  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:31:59.269  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:31:59.269  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.269  3807  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 19:31:59.269  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.269  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.269  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.269  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.270  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 19:31:59.270  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.270  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.270  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.270  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.270  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.271  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.271  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.272  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 19:31:59.272  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.272  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:31:59.274  2609  2645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 19:31:59.274  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.275  2609  2661 D BtGatt.ScanManager: Starting BLE batch scan
08-16 19:31:59.275  2609  2661 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 19:31:59.275  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 19:31:59.275  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:31:59.275  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.277  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 19:31:59.277  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.277  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.277  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.278  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.278  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.278  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 19:31:59.278  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.278  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.279  3807  3859 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 19:31:59.279  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.280  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.280  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.280  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.280  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.280  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.280  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.280  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.280  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.280  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 19:31:59.280  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.280  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.280  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.280  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.281  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 19:31:59.281  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.281  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.282  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:31:59.282  3807  3859 D BluetoothLeScanner: could not find callback wrapper
,08-16 19:31:59.282  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.282  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-16 19:31:59.282  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
,08-16 19:31:59.282  2609  2645 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 19:31:59.283  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:31:59.283  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 19:31:59.283  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 19:31:59.283  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 19:31:59.284  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 19:31:59.284  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 19:31:59.284  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.284  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-16 19:31:59.284  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
,08-16 19:31:59.284  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.284  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
,08-16 19:31:59.284  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.284  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 19:31:59.285  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.285  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.285  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.285  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.285  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.285  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:31:59.286  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.287  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.287  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.287  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:31:59.287  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.287  2609  2645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 19:31:59.287  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.287  3807  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 19:31:59.288  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.288  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 19:31:59.288  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.288  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.288  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.288  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.288  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.288  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:31:59.288  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.288  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.288  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.289  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.289  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.289  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.289  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 19:31:59.289  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.290  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:31:59.290  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.290  3807  3859 D BluetoothLeScanner: could not find callback wrapper
,08-16 19:31:59.290  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.290  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:31:59.290  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.291  3807  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 19:31:59.291  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 19:31:59.291  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 19:31:59.291  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 19:31:59.291  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 19:31:59.292  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.292  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-16 19:31:59.292  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
,08-16 19:31:59.292  2609  2645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 19:31:59.292  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.292  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:31:59.292  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.292  2609  2661 D BtGatt.ScanManager: stopping BLe Batch
,08-16 19:31:59.292  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 19:31:59.292  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.292  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.292  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.292  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-16 19:31:59.293  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 19:31:59.293  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.294  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:31:59.294  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.294  3807  3859 D BluetoothLeScanner: could not find callback wrapper
,08-16 19:31:59.294  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.294  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:31:59.294  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
,08-16 19:31:59.295  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 19:31:59.296  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 19:31:59.297  2609  2645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 19:31:59.297  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.297  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-16 19:31:59.297  2609  2661 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 19:31:59.297  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-16 19:31:59.297  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 19:31:59.297  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 19:31:59.297  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 19:31:59.298  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.298  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.298  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 19:31:59.298  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.298  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.298  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
,08-16 19:31:59.298  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.298  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.298  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 19:31:59.298  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.299  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.299  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.299  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.300  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.301  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.301  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:31:59.301  2609  2645 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 19:31:59.301  2609  2645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:31:59.301  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.302  3807  3859 D BluetoothLeScanner: could not find callback wrapper
,08-16 19:31:59.302  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.302  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.302  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.302  3807  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 19:31:59.303  3807  3859 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 19:31:59.303  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 19:31:59.306  3807  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 19:31:59.306  3807  3859 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 19:31:59.306  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-16 19:31:59.306  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 19:31:59.306  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 19:31:59.306  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 19:31:59.306  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 19:31:59.306  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-16 19:31:59.307  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 19:31:59.307  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 19:31:59.307  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 19:31:59.307  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-16 19:31:59.307  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 19:31:59.307  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 19:31:59.307  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-16 19:31:59.307  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 19:31:59.308  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 19:31:59.309  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 19:31:59.309  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 19:31:59.309  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 19:31:59.309  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 19:31:59.309  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 19:31:59.309  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 19:31:59.309  3807  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 19:31:59.310  3807  3859 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 19:31:59.310  3807  3859 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 19:31:59.310  3807  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 19:31:59.310  3807  3859 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 19:31:59.310  3807  3859 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 19:31:59.310  3807  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 19:31:59.310  3807  3859 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 19:31:59.310  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 19:31:59.313  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 19:31:59.314  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 19:31:59.314  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 19:31:59.315  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 19:31:59.315  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 19:31:59.315  3807  3859 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 19:31:59.315  3807  3859 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 19:31:59.315  3807  3859 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 19:31:59.315  3807  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 395)
08-16 19:31:59.316  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.316  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.316  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.316  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.316  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.316  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.316  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 19:31:59.317  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.317  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.317  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.317  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.317  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.317  3807  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 395
08-16 19:31:59.317  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.318  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.318  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.318  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.318  3807  3873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 19:31:59.318  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.319  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.319  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.319  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.319  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.319  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.320  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.320  3807  3859 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 19:31:59.321  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.321  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.321  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.321  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.321  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.321  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.321  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.321  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.321  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.321  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.321  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.321  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.321  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.322  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.322  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.322  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.322  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.323  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.323  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.323  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.323  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.323  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.324  3807  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 19:31:59.324  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.324  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.324  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.324  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.325  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.325  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.325  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.325  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.325  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.325  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.325  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.325  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.325  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.325  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.326  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.326  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.326  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.326  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.326  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.327  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.327  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.327  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.327  3807  3859 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 19:31:59.327  3807  3859 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 19:31:59.327  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 19:31:59.327  3807  3859 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 19:31:59.328  3807  3859 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 19:31:59.328  3807  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 19:31:59.328  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 19:31:59.328  3807  3859 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 19:31:59.328  3807  3859 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 19:31:59.328  3807  3859 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-16 19:31:59.328  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 19:31:59.328  3807  3859 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 19:31:59.328  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.328  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.328  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.328  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.329  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.329  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.329  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.329  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.329  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.329  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.329  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.329  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.329  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.329  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.330  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.330  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.330  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:31:59.330  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.330  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.330  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 19:31:59.331  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:31:59.331  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.331  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.331  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.331  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.331  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.331  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:31:59.331  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.331  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.331  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.332  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.332  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.332  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.332  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.332  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.332  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.332  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.332  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.332  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.332  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 19:31:59.333  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.333  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.333  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.333  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.333  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.333  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
,08-16 19:31:59.333  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.333  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.333  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.333  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.333  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.334  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.334  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.334  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.334  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.334  3807  3859 D BluetoothLeScanner: could not find callback wrapper
,08-16 19:31:59.334  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.335  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.335  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.336  3807  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 19:31:59.336  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:31:59.336  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 19:31:59.337  3807  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 19:31:59.337  3807  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 19:31:59.338  3807  3807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 19:31:59.338  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 19:31:59.338  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 19:31:59.338  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.338  3807  3875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 19:31:59.338  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-16 19:31:59.338  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 19:31:59.338  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 19:31:59.338  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.338  3807  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 19:31:59.339  3807  3807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 19:31:59.339  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.339  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.339  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 19:31:59.339  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 19:31:59.339  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 19:31:59.339  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 19:31:59.340  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.340  3807  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-16 19:31:59.340  3807  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 19:31:59.340  3807  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 19:31:59.340  3807  3859 D BluetoothLeScanner: could not find callback wrapper
,08-16 19:31:59.340  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.340  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.340  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 19:31:59.340  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:31:59.340  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.341  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 19:31:59.341  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 19:31:59.341  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.341  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:31:59.342  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.342  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.342  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.342  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 19:31:59.342  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.342  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.342  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:31:59.342  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.342  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.342  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
,08-16 19:31:59.342  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.342  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.343  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:31:59.343  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:31:59.343  3807  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 19:31:59.346  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 19:31:59.346  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 19:31:59.346  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 19:31:59.346  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:31:59.346  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.348  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.348  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.348  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.348  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 19:31:59.349  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.349  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.349  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.349  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.349  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.349  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 19:31:59.349  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:31:59.349  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.349  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:31:59.350  3807  3859 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 19:31:59.351  3807  3859 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 19:31:59.351  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 19:31:59.351  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:31:59.351  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:31:59.352  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.352  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 19:31:59.352  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 19:31:59.352  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.352  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.352  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.352  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.353  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.353  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.353  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.353  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.353  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.353  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.353  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.354  3807  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 19:31:59.355  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 19:31:59.355  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.355  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.355  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.355  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.355  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.356  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.356  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.356  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.356  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.356  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
,08-16 19:31:59.358  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 19:31:59.358  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.359  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.359  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 19:31:59.359  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.359  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.359  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.359  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.359  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.359  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.359  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.359  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.359  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.359  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.360  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.360  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.360  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:31:59.361  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:31:59.361  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.361  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.361  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.361  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.365  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:31:59.365  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:31:59.365  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:31:59.365  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:59.365  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.365  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.365  3807  3859 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc613bf not in the list
08-16 19:31:59.365  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.365  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.366  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:59.366  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.366  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:31:59.366  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:59.366  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:59.367  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:31:59.367  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:31:59.367  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:31:59.367  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:31:59.367  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:31:59.367  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:31:59.367  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:59.367  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214ca8c not in the list
08-16 19:31:59.368  3807  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-16 19:31:59.368  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 19:31:59.368  3807  3859 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 19:31:59.369  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 19:31:59.369  3807  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 19:31:59.369  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 19:31:59.370  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 19:31:59.370  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 19:31:59.371  3807  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 19:31:59.371  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 19:31:59.371  3807  3859 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 19:31:59.371  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 19:31:59.371  3807  3859 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-16 19:31:59.371  3807  3859 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 19:31:59.372  3807  3859 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 19:31:59.372  3807  3859 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 19:31:59.372  3807  3859 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 19:31:59.372  3807  3859 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 19:31:59.372  3807  3859 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-16 19:31:59.372  3807  3859 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 19:31:59.373  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 19:31:59.373  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de041f2 added. We now have 2 listener(s)
08-16 19:31:59.373  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 19:31:59.374  3807  3859 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 19:31:59.374   873  1939 D WifiService: setWifiEnabled: true pid=3807, uid=10000
,08-16 19:31:59.375   873  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 19:31:59.375  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:31:59.375  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc00043 added. We now have 3 listener(s)
08-16 19:31:59.375  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 19:31:59.379  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:31:59.379  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba6b6c0 added. We now have 4 listener(s)
,08-16 19:31:59.379  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 19:31:59.380  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:31:59.380  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2a7ff9 added. We now have 5 listener(s)
08-16 19:31:59.380  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:31:59.381   873  1988 D WifiService: setWifiEnabled: false pid=3807, uid=10000
08-16 19:31:59.382   873  1988 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 19:31:59.386  2609  2641 D BluetoothAdapterState: Current state: ON, message: 23
08-16 19:31:59.386  2609  2641 D BluetoothAdapterProperties: Setting state to 13
08-16 19:31:59.386  2609  2641 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 19:31:59.386  2609  2641 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 19:31:59.387  2609  2641 I BluetoothAdapterState: Entering PendingCommandState
,08-16 19:31:59.388  2609  2609 D BluetoothMapService: onReceive
08-16 19:31:59.388  2609  2609 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 19:31:59.388  2609  2609 D BluetoothMapService: STATE_TURNING_OFF
08-16 19:31:59.388  2609  2609 D BluetoothMapService: MAP Service closeService in
08-16 19:31:59.388  2609  2609 D BluetoothMapMasInstance0: MAP Service shutdown
,08-16 19:31:59.388  2609  2609 D ObexServerSockets0: shutdown(block = true)
08-16 19:31:59.389  2609  2609 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 19:31:59.389  2609  2753 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 19:31:59.389  2609  2609 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 19:31:59.389  2609  2754 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 19:31:59.389  2609  2609 I BtOppRfcommListener: stopping Accept Thread
08-16 19:31:59.390  2609  3420 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 19:31:59.390  2609  2735 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 19:31:59.390  2609  3420 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 19:31:59.392  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 19:31:59.392  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:31:59.392  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.392  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.392  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:59.392  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:31:59.392  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:31:59.392  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:59.392  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 19:31:59.393  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.393  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:31:59.401  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 19:31:59.403   873  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 19:31:59.403   873  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 19:31:59.403   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 19:31:59.403   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 19:31:59.409   873  1839 D DhcpClient: Clearing IP address
08-16 19:31:59.409   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 19:31:59.414   372   871 D CommandListener: Setting iface cfg
,08-16 19:31:59.417   873   886 I ActivityManager: Start proc 3878:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 19:31:59.418  2609  2645 D BluetoothAdapterProperties: Scan Mode:20
,08-16 19:31:59.418  2609  2641 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 19:31:59.418  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:31:59.413  1516  2079 V NativeCrypto: Read error: ssl=0xaebeae00: I/O error during system call, Connection timed out
,08-16 19:31:59.420  2609  2609 D HeadsetService: Received stop request...Stopping profile...
08-16 19:31:59.422   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 19:31:59.422   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-16 19:31:59.423  1926  1938 D BluetoothHeadset: Proxy object disconnected
08-16 19:31:59.424  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.424  1366  1384 D BluetoothHeadset: Proxy object disconnected
,08-16 19:31:59.424  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:31:59.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:59.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:31:59.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:31:59.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:59.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 19:31:59.425   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 19:31:59.425   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 19:31:59.425   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 19:31:59.425  2609  2609 V BluetoothAdapterState: isTurningOff()=true
08-16 19:31:59.425  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-16 19:31:59.425  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:31:59.425  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:31:59.425   873  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-16 19:31:59.426   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 19:31:59.427  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.427  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 19:31:59.428   395   395 E Parcel  : Reading a NULL string not supported here.
08-16 19:31:59.428   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 19:31:59.429   873  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 19:31:59.430  1516  2079 V NativeCrypto: SSL shutdown failed: ssl=0xaebeae00: I/O error during system call, Broken pipe
08-16 19:31:59.431  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.431  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:31:59.431  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.431  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.431  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:59.431  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:31:59.431  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:31:59.431  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:59.431  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:31:59.432  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.432  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 19:31:59.432   873  1841 D DhcpClient: Receive thread stopped
08-16 19:31:59.432  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 19:31:59.433  2609  2609 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 19:31:59.434  2609  2609 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 19:31:59.434  2609  2697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 19:31:59.434  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 19:31:59.434  2609  2697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 19:31:59.434  2609  2697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 19:31:59.434  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:31:59.434  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.434  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.434  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:59.434  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:31:59.434  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:31:59.434  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:31:59.434  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 19:31:59.434  2609  2645 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 19:31:59.435  2609  2645 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 19:31:59.436  2609  2609 D A2dpService: Received stop request...Stopping profile...
08-16 19:31:59.436  1366  1366 D HeadsetProfile: Bluetooth service disconnected
08-16 19:31:59.436  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.436  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:31:59.436  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.436  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.436  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:59.436  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:31:59.436  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:31:59.436  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:31:59.436  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 19:31:59.436  2609  2746 D A2dpStateMachine: Exit Disconnected: -1
08-16 19:31:59.438  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.438  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:31:59.438  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.438  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.438  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:31:59.438  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:31:59.438  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:31:59.438  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:31:59.438  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 19:31:59.439  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.439  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetwor,kChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 19:31:59.440   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 19:31:59.441   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 19:31:59.442  1366  1366 D BluetoothA2dp: Proxy object disconnected
08-16 19:31:59.443  2609  2609 D HidService: Received stop request...Stopping profile...
08-16 19:31:59.443  2609  2609 D HidService: Stopping Bluetooth HidService
08-16 19:31:59.444  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-16 19:31:59.444  1366  1366 D HidProfile: Bluetooth service disconnected
08-16 19:31:59.445  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.445  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:31:59.445  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:59.445  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:59.445  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:31:59.445  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:31:59.445  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:31:59.445  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:31:59.445  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 19:31:59.445  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:31:59.445  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 19:31:59.446  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:31:59.447  2609  2609 D HealthService: Received stop request...Stopping profile...
08-16 19:31:59.449  2609  2609 D PanService: Received stop request...Stopping profile...
08-16 19:31:59.449  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 19:31:59.449  1366  1366 D PanProfile: Bluetooth service disconnected
08-16 19:31:59.450  2609  2609 D BluetoothMapService: Received stop request...Stopping profile...
08-16 19:31:59.450  2609  2609 D BluetoothMapService: stop()
08-16 19:31:59.451   873  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 19:31:59.453  2609  2609 D BluetoothMapAppObserver: deinitObservers()
08-16 19:31:59.453  2609  2609 D BluetoothMapAppObserver: removeReceiver()
,08-16 19:31:59.453  2091  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 19:31:59.454  2609  2609 V BluetoothAdapterState: isTurningOff()=true
08-16 19:31:59.454  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-16 19:31:59.454  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:31:59.454  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:31:59.455  2609  2645 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 19:31:59.455  2609  2697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 19:31:59.455  2609  2697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 19:31:59.455  2609  2697 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 19:31:59.455  2609  2697 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 19:31:59.455  2609  2697 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 19:31:59.455  2609  2697 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 19:31:59.456  2609  2609 V BluetoothAdapterState: isTurningOff()=true
,08-16 19:31:59.456  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-16 19:31:59.456  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:31:59.456  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:31:59.457  2609  2609 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 19:31:59.457  2609  2645 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 19:31:59.457  2609  2609 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 19:31:59.457  2609  2609 V BluetoothAdapterState: isTurningOff()=true
,08-16 19:31:59.457  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-16 19:31:59.457  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:31:59.457  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:31:59.457  2609  2609 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 19:31:59.457  2609  2645 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 19:31:59.458  2609  2609 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 19:31:59.458  2609  2609 V BluetoothAdapterState: isTurningOff()=true
,08-16 19:31:59.458  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-16 19:31:59.458  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:31:59.458  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:31:59.458  2609  2609 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 19:31:59.459  2609  2609 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 19:31:59.459  2609  2609 D BluetoothMapService: MAP Service closeService in
08-16 19:31:59.459  2609  2609 V BluetoothAdapterState: isTurningOff()=true
08-16 19:31:59.459  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-16 19:31:59.459  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:31:59.459  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:31:59.460  2609  2641 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 19:31:59.460  2609  2641 D BluetoothAdapterProperties: Setting state to 15
08-16 19:31:59.460  2609  2641 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 19:31:59.460  1926  2045 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:31:59.460   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:31:59.460  1366  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 19:31:59.463  2609  2641 I BluetoothAdapterState: Entering BleOnState
,08-16 19:31:59.463  1366  2024 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 19:31:59.464  1366  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 19:31:59.465  1366  1384 D BluetoothMap: onBluetoothStateChange: up=false
08-16 19:31:59.465   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 19:31:59.465   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:31:59.465   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 19:31:59.465  1366  2024 D BluetoothPan: onBluetoothStateChange on: false
08-16 19:31:59.466  1366  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:31:59.467  2609  2641 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 19:31:59.467  2609  2641 D BluetoothAdapterProperties: Setting state to 16
08-16 19:31:59.467  2609  2641 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 19:31:59.467  2609  2641 D BluetoothAdapterProperties: onBleDisable
08-16 19:31:59.467  2609  2641 I BluetoothAdapterState: Entering PendingCommandState
08-16 19:31:59.468  2609  2642 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 19:31:59.468  2609  2697 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 19:31:59.469  2609  2697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 19:31:59.470  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:59.470  3807  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 395)
08-16 19:31:59.470  2609  2645 D BluetoothAdapterProperties: Scan Mode:20
08-16 19:31:59.471  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:31:59.472  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:31:59.474  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:31:59.474  2609  2609 D BluetoothMapService: cleanup()
08-16 19:31:59.474  2609  2609 D BluetoothMapService: MAP Service closeService in
08-16 19:31:59.482  3878  3878 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-16 19:31:59.488   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 19:31:59.494  3878  3878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 19:31:59.501  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 19:31:59.504   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-16 19:31:59.506   873  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 19:31:59.506   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 19:31:59.515   873  1982 I ActivityManager: Start proc 3894:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 19:31:59.517   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 19:31:59.520  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:59.521  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:59.522  3409  3409 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e2228d2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 19:31:59.523  2002  2002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-16 19:31:59.526   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cb452a3:true
,08-16 19:31:59.546  3878  3878 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 19:31:59.553  3894  3894 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 19:31:59.555  3878  3878 D BluetoothMap: Create BluetoothMap proxy object
,08-16 19:31:59.558   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 19:31:59.559   873  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 19:31:59.560  3878  3878 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 19:31:59.577  3878  3878 D DockEventReceiver: finishStartingService: stopping service
,08-16 19:31:59.580   873  1671 I ActivityManager: Killing 3062:com.google.android.talk/u0a61 (adj 15): empty #17
,08-16 19:31:59.668  2609  2645 I bt_hci  : shut_down
,08-16 19:31:59.669  2609  2663 D bt_hwcfg: hw_epilog_process
,08-16 19:31:59.670  2609  2663 I bt_vendor: low_power_mode_cb
,08-16 19:31:59.691  2609  2663 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 19:31:59.691  2609  2663 I bt_vendor: epilog_cb
08-16 19:31:59.691  2609  2663 I bt_hci  : epilog_finished_callback
,08-16 19:31:59.694  2609  2645 I bt_hci_h4: hal_close
08-16 19:31:59.694  2609  2645 I bt_userial_vendor: device fd = 51 close
,08-16 19:31:59.775  3894  3894 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 19:31:59.775  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 19:31:59.779  3894  3894 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 19:31:59.779  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 19:31:59.780  3894  3894 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 19:31:59.780  3894  3894 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 19:31:59.780  3894  3894 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.j,ava:290)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 19:31:59.780  3894  3894 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-,16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 19:31:59.780  3894  3894 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 19:31:59.780  3894  3894 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 19:31:59.780  3894  3894 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 19:31:59.809   873  1983 I ActivityManager: Start proc 3927:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-16 19:31:59.810   873  1983 I ActivityManager: Killing 3570:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 19:31:59.855  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 19:31:59.867  2609  2642 D bt_stack_manager: event_shut_down_stack finished.
,08-16 19:31:59.867  2609  2641 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 19:31:59.872  2609  2609 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 19:31:59.873  2609  2609 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 19:31:59.874  2609  2609 D BtGatt.GattService: stop()
08-16 19:31:59.874  2609  2641 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 19:31:59.874  2609  2609 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 19:31:59.877  2609  2609 V BluetoothAdapterState: isTurningOff()=false
,08-16 19:31:59.877  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-16 19:31:59.878  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:31:59.878  2609  2609 V BluetoothAdapterState: isBleTurningOff()=true
08-16 19:31:59.878  2609  2641 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 19:31:59.879  2609  2641 D BluetoothAdapterProperties: Setting state to 10
08-16 19:31:59.879  2609  2641 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 19:31:59.880  2609  2641 I BluetoothAdapterState: Entering OffState
,08-16 19:31:59.882   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 19:31:59.888  3927  3927 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-16 19:31:59.903  2609  2609 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 19:31:59.903  2609  2609 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 19:31:59.903  2609  2642 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-16 19:31:59.903  2609  2609 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 19:31:59.906  2609  2642 D bt_stack_manager: event_clean_up_stack finished.
,08-16 19:31:59.922  2609  2609 I art     : System.exit called, status: 0
,08-16 19:31:59.922  2609  2609 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 19:31:59.962  3927  3927 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-16 19:32:00.043  3894  3925 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 19:32:00.046   873  1947 I ActivityManager: Start proc 3955:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 19:32:00.049   873  1372 I ActivityManager: Process com.android.bluetooth (pid 2609) has died
08-16 19:32:00.051   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a4b7a85:true
,08-16 19:32:00.106  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 19:32:00.270  3955  3975 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 19:32:00.270  3955  3975 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 19:32:00.277  3955  3975 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 19:32:00.277  3955  3975 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 19:32:00.312  3955  3975 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 19:32:00.312  3955  3975 I Babel_SMS: MmsConfig.loadFromResources
,08-16 19:32:00.314  3955  3975 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 19:32:00.315  3955  3975 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 19:32:00.336  3955  3955 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 19:32:00.347  3955  3955 I Babel_Crash: startup - clean
,08-16 19:32:00.373  3955  3955 I Babel_telephony: TeleModule.launchCompleted
,08-16 19:32:00.378   873  1939 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 19:32:00.393  3955  3955 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 19:32:00.400  3955  3955 W Babel   : BAM#gBA: invalid account id: -1
,08-16 19:32:00.400  3955  3955 W Babel   : BAM#gBA: invalid account id: -1
08-16 19:32:00.400  3955  3955 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 19:32:00.404   873  1982 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 19:32:00.409  3955  3980 I Babel   : deleted: false for 0
,08-16 19:32:00.422  3878  3878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 19:32:00.455   873  1372 I ActivityManager: Start proc 3983:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-16 19:32:00.456  3878  3878 D DockEventReceiver: finishStartingService: stopping service
,08-16 19:32:00.472  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 19:32:00.548  3955  3955 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 19:32:00.557  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 19:32:00.566  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 19:32:00.569  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 19:32:00.586  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 19:32:00.601  3983  3983 D AdapterServiceConfig: Adding HeadsetService
,08-16 19:32:00.601  3983  3983 D AdapterServiceConfig: Adding A2dpService
08-16 19:32:00.602  3983  3983 D AdapterServiceConfig: Adding HidService
08-16 19:32:00.602  3983  3983 D AdapterServiceConfig: Adding HealthService
,08-16 19:32:00.602  3983  3983 D AdapterServiceConfig: Adding PanService
08-16 19:32:00.602  3983  3983 D AdapterServiceConfig: Adding GattService
,08-16 19:32:00.606   873  1671 I ActivityManager: Killing 3409:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 19:32:00.602  3983  3983 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 19:32:00.729   873   884 I ActivityManager: Killing 3462:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 19:32:00.765  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 19:32:00.769  3955  3955 I vclib   : onServiceConnected
,08-16 19:32:00.793  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 19:32:00.797  1739  1739 D SystemUpdateService: onCreate
,08-16 19:32:00.800  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 19:32:00.802  1739  3995 I SystemUpdateService: active receiver: enabled
,08-16 19:32:00.805  1739  3995 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 19:32:00.807  1739  3995 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 19:32:00.809  1739  3995 I SystemUpdateService: now status is 0 (complete)
,08-16 19:32:00.809  1739  3995 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 19:32:00.809  1739  3995 I SystemUpdateService: file has been verified
,08-16 19:32:00.811  1739  3995 I SystemUpdateService: OTA package size = 12249756
,08-16 19:32:00.813  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 19:32:00.814  1739  2411 I iu.UploadsManager: num queued entries: 0
,08-16 19:32:00.815  1739  2411 I iu.UploadsManager: num updated entries: 0
08-16 19:32:00.815  1739  2411 I iu.SyncManager: NEXT; no task
08-16 19:32:00.821  1739  3995 I SystemUpdateService: showing system update notification
,08-16 19:32:00.847  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 19:32:00.849  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 19:32:00.849  1739  1739 D SystemUpdateService: onDestroy
,08-16 19:32:00.867   873  1372 I ActivityManager: Start proc 3997:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 19:32:00.898  3997  3997 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 19:32:00.900  3997  3997 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 19:32:00.906  3997  3997 D SprintDMHelper: simOperator: 
,08-16 19:32:00.906  3997  3997 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 19:32:00.923   873  1966 I ActivityManager: Start proc 4009:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-16 19:32:00.924   873  1966 I ActivityManager: Killing 3498:android.process.acore/u0a5 (adj 15): empty #17
,08-16 19:32:01.039   873  1939 I ActivityManager: Start proc 4024:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 19:32:01.044  3955  4023 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 19:32:01.050   873   883 I ActivityManager: Killing 3689:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 19:32:01.107  4024  4024 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 19:32:01.167  4024  4024 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 19:32:01.167  4024  4024 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 19:32:01.167  4024  4024 I GAv4    :   adb logcat -s GAv4
,08-16 19:32:01.183  4024  4024 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 19:32:01.190  4024  4024 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 19:32:01.216  4024  4041 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 19:32:01.328  4024  4024 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 19:32:01.368  4024  4024 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 19:32:01.378  4024  4024 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2684-2689)
,08-16 19:32:01.379  4024  4024 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 19:32:01.390  4024  4024 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a26a82}
,08-16 19:32:01.390  4024  4024 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 19:32:01.391  4024  4024 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 19:32:01.399  4024  4024 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 19:32:01.404  4024  4024 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 19:32:01.417  4024  4024 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 19:32:01.428  4024  4024 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 19:32:01.428  4024  4024 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 19:32:01.428  4024  4024 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 19:32:01.428  4024  4024 I Adreno  : Build Date                       : 10/20/15
08-16 19:32:01.428  4024  4024 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 19:32:01.428  4024  4024 I Adreno  : Local Branch                     : M14
08-16 19:32:01.428  4024  4024 I Adreno  : Remote Branch                    : 
08-16 19:32:01.428  4024  4024 I Adreno  : Remote Branch                    : 
08-16 19:32:01.428  4024  4024 I Adreno  : Reconstruct Branch               : 
,08-16 19:32:01.494  4024  4024 I NSApplication: Starting up...
,08-16 19:32:01.518  4024  4070 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 19:32:01.523   873  1988 I ActivityManager: Start proc 4075:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 19:32:01.525   873  1988 I ActivityManager: Killing 3704:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 19:32:01.606  4075  4075 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 19:32:01.783   873  1939 I ActivityManager: Killing 2187:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 19:32:02.435   873  1940 D WifiService: setWifiEnabled: true pid=3807, uid=10000
,08-16 19:32:02.435   873  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 19:32:02.453   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-16 19:32:02.459  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 19:32:02.460  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:02.460  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:02.460  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:02.460  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:02.460  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:32:02.460  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:02.460  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:02.460  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 19:32:02.460  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 19:32:02.461  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 19:32:02.463  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:32:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 19:32:02.464  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:02.464  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 19:32:02.489   873  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-16 19:32:02.490   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 19:32:02.490   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 19:32:02.491   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 19:32:02.491   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 19:32:02.492   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 19:32:02.492   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 19:32:02.507   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 19:32:02.507   873  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.19 rxSuccessRate=7.75 delta 1000 -> 994
08-16 19:32:02.508   372   871 D CommandListener: Setting iface cfg
,08-16 19:32:02.509   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-16 19:32:02.509   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 19:32:02.518   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 19:32:02.518   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 19:32:02.518   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 19:32:02.526   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 19:32:02.526   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 19:32:02.573   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 19:32:02.879  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 19:32:03.303  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 19:32:03.346  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 19:32:03.347  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-16 19:32:03.352   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 19:32:03.371   873  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 19:32:03.372   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 19:32:03.372   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 19:32:03.394   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 19:32:03.411   372   871 D CommandListener: Setting iface cfg
,08-16 19:32:03.412   873  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 19:32:03.424   873  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-16 19:32:03.427   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 19:32:03.464   873  4098 D DhcpClient: Receive thread started
,08-16 19:32:03.547   873  1308 E native  : do suspend false
,08-16 19:32:03.566   873  1839 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 19:32:03.579   873  4098 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172678, domain null
,08-16 19:32:03.580   873  1839 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172678 seconds
,08-16 19:32:03.584   873  1839 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 19:32:03.596   873  4098 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 19:32:03.597   873  1839 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 19:32:03.602   372   871 D CommandListener: Setting iface cfg
,08-16 19:32:03.614   873  1839 D DhcpClient: Scheduling renewal in 86399s
,08-16 19:32:03.618   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 19:32:03.636   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 19:32:03.641   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 19:32:03.641   873  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 19:32:03.643   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 19:32:03.646   873  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 19:32:03.647   873  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 19:32:03.712   873  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 19:32:03.713   873  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 19:32:03.716   873  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 19:32:03.719   873  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 19:32:03.722   873  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 19:32:03.731   873  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 19:32:03.736   873  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 19:32:03.736   873  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 19:32:03.736   873  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-16 19:32:03.736   873  1310 D ConnectivityService:    accepting network in place of null
,08-16 19:32:03.736   873  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 19:32:03.737   873  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 19:32:03.738   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 19:32:03.748   873  4097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=145058, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:32:03.775   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 19:32:03.809   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 19:32:03.813   873  4096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:816::200e
,08-16 19:32:03.822   873  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 19:32:03.823   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 19:32:03.836   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 19:32:03.840   873  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 19:32:03.856  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 19:32:03.856  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:03.856  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:03.856  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:03.856  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:03.856  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:32:03.856  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:03.856  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:32:03.856  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 19:32:03.856  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 19:32:03.856  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:03.860  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:03.860  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:03.860  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:03.860  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:03.860  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:03.860  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:32:03.860  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:03.860  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:32:03.860  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 19:32:03.860  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:03.860  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:03.865  2002  2002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 19:32:03.868  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 19:32:03.871  1739  1739 D SystemUpdateService: onCreate
,08-16 19:32:03.878  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 19:32:03.884  1739  4108 I SystemUpdateService: active receiver: enabled
,08-16 19:32:03.893  1739  4108 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 19:32:03.894  1739  4108 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 19:32:03.895  1739  4108 I SystemUpdateService: now status is 0 (complete)
08-16 19:32:03.895  1739  4108 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 19:32:03.895  1739  4108 I SystemUpdateService: file has been verified
08-16 19:32:03.896  1739  4108 I SystemUpdateService: OTA package size = 12249756
,08-16 19:32:03.900   873  4096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 17:32:03 GMT], X-Android-Received-Millis=[1471368723897], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471368723866]}
08-16 19:32:03.900  1739  4108 I SystemUpdateService: showing system update notification
08-16 19:32:03.902   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 19:32:03.903   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 19:32:03.903   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 19:32:03.909   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 19:32:03.915  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 19:32:03.917  1739  2411 I iu.UploadsManager: num queued entries: 0
08-16 19:32:03.917  1739  2411 I iu.UploadsManager: num updated entries: 0
,08-16 19:32:03.918  1739  2411 I iu.SyncManager: NEXT; no task
,08-16 19:32:03.922  1739  1739 D SystemUpdateService: onDestroy
,08-16 19:32:03.922  1739  4113 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 19:32:03.922  1739  4113 W BaseAppContext: Using Auth Proxy for data requests.
08-16 19:32:03.923  1739  4113 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 19:32:03.929  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 19:32:03.931  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 19:32:03.932  3997  3997 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 19:32:03.936  3997  3997 D SprintDMHelper: simOperator: 
,08-16 19:32:03.936  3997  3997 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 19:32:03.942  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:03.944  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:03.978  1516  2251 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 19:32:03.978  1516  2251 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 19:32:03.978  1516  2251 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:32:03.978  1516  2251 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:03.991  1739  4113 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-16 19:32:04.068  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:32:04.068  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 19:32:04.069  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 19:32:04.069  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:04.090  3955  4118 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 19:32:04.101  3553  4116 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 19:32:04.101  3553  4116 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at blb.a(PG:3937)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at czp.a(PG:18188)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:32:04.101  3553  4116 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	... 12 more
08-16 19:32:04.101  3553  4116 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at fal.a(PG:38)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:32:04.101  3553  4116 E HttpOperation: 	... 14 more
,08-16 19:32:04.168  1516  2882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:32:04.168  1516  2882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 19:32:04.168  1516  2882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:32:04.168  1516  2882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:04.199  3553  4116 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 19:32:04.199  3553  4116 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at hec.a(PG:42)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at hee.a(PG:102)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at czr.a(PG:65)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at kka.a(PG:108)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at czp.a(PG:19176)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:32:04.199  3553  4116 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	... 15 more
08-16 19:32:04.199  3553  4116 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at fal.a(PG:38)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:32:04.199  3553  4116 E HttpOperation: 	... 17 more
,08-16 19:32:04.201  3553  4116 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 19:32:04.201  3553  4116 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at hec.a(PG:42)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at hee.a(PG:102)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at czr.a(PG:65)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at kka.a(PG:108)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	... 15 more
08-16 19:32:04.201  3553  4116 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at fal.a(PG:38)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 19:32:04.201  3553  4116 E ExperimentLoader: 	... 17 more
,08-16 19:32:04.297   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 130695, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:32:04.822   873  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 19:32:05.177   873  1940 I ActivityManager: Killing 3654:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-16 19:32:05.444   873  1670 D WifiService: setWifiEnabled: false pid=3807, uid=10000
,08-16 19:32:05.444   873  1670 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 19:32:05.485  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 19:32:05.493   873  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 19:32:05.493   873  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 19:32:05.494   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 19:32:05.494   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 19:32:05.511   873  1839 D DhcpClient: Clearing IP address
,08-16 19:32:05.512   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 19:32:05.516   372   871 D CommandListener: Setting iface cfg
,08-16 19:32:05.528  1516  4122 V NativeCrypto: Read error: ssl=0x9a26a000: I/O error during system call, Connection timed out
,08-16 19:32:05.532  1516  4122 V NativeCrypto: SSL shutdown failed: ssl=0x9a26a000: I/O error during system call, Broken pipe
,08-16 19:32:05.534   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 19:32:05.535   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 19:32:05.535   873  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
08-16 19:32:05.537   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 19:32:05.539   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 19:32:05.550   395   395 E Parcel  : Reading a NULL string not supported here.
08-16 19:32:05.553   873  4098 D DhcpClient: Receive thread stopped
,08-16 19:32:05.562   873  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 19:32:05.564   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 19:32:05.569   873  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 19:32:05.572  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:05.572  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:05.572  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:05.572  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:05.572  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:32:05.572  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:32:05.572  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:05.572  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:05.572  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 19:32:05.572  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 19:32:05.572  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 19:32:05.573  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:05.573  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:05.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:05.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:05.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:32:05.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:32:05.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:05.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:05.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 19:32:05.573  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:05.573  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 19:32:05.582  2091  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 19:32:05.600   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 19:32:05.637   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 19:32:05.638   873  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 19:32:05.638   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 19:32:05.640   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 19:32:05.643  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:05.643  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:05.647  2002  2002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-16 19:32:05.652  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 19:32:05.655  1739  1739 D SystemUpdateService: onCreate
,08-16 19:32:05.659  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 19:32:05.666  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 19:32:05.672  1739  2411 I iu.UploadsManager: num queued entries: 0
,08-16 19:32:05.672  1739  2411 I iu.UploadsManager: num updated entries: 0
08-16 19:32:05.673  1739  4134 I SystemUpdateService: active receiver: enabled
08-16 19:32:05.674  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 19:32:05.677  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 19:32:05.679  3997  3997 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 19:32:05.684  3997  3997 D SprintDMHelper: simOperator: 
08-16 19:32:05.684  3997  3997 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 19:32:05.709  1739  4134 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 19:32:05.714  1739  2411 I iu.SyncManager: NEXT; no task
08-16 19:32:05.714  3955  4139 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 19:32:05.719  1739  4134 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 19:32:05.719  1739  4134 I SystemUpdateService: now status is 0 (complete)
08-16 19:32:05.719  1739  4134 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 19:32:05.719  1739  4134 I SystemUpdateService: file has been verified
,08-16 19:32:05.720  1739  4134 I SystemUpdateService: OTA package size = 12249756
08-16 19:32:05.720   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 19:32:05.724  1739  4134 I SystemUpdateService: showing system update notification
,08-16 19:32:05.733  1739  1739 D SystemUpdateService: onDestroy
,08-16 19:32:08.501  3983  3983 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 19:32:08.501   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e298bd:true
,08-16 19:32:08.507  3983  3983 I bt_bluedroid: init
,08-16 19:32:08.508  3983  4142 I BluetoothAdapterState: Entering OffState
,08-16 19:32:08.513  3983  4143 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 19:32:08.513  3983  4143 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 19:32:08.514  3983  4143 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 19:32:08.514  3983  4143 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 19:32:08.516  3983  3983 I bt_bluedroid: get_profile_interface socket
,08-16 19:32:08.518  3983  3983 I bt_bluedroid: get_profile_interface sdp
08-16 19:32:08.521  3983  4146 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 19:32:08.522  3983  4146 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 19:32:08.526  3983  3994 I bt_bluedroid: config_hci_snoop_log
,08-16 19:32:08.530   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 19:32:08.543  3983  4142 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 19:32:08.543  3983  4142 D BluetoothAdapterProperties: Setting state to 14
,08-16 19:32:08.544  3983  4142 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 19:32:08.548  3983  4142 D BluetoothBondStateMachine: make
,08-16 19:32:08.560  3983  4147 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 19:32:08.568  3983  4142 I BluetoothAdapterState: Entering PendingCommandState
08-16 19:32:08.570  3983  3983 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 19:32:08.578  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:08.580  3983  3983 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 19:32:08.582  3983  3983 D BtGatt.GattService: Received start request. Starting profile...
,08-16 19:32:08.582  3983  3983 D BtGatt.GattService: start()
08-16 19:32:08.582  3983  3983 I bt_bluedroid: get_profile_interface gatt
,08-16 19:32:08.584  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:08.585  3983  3983 D BtGatt.AdvertiseManager: advertise manager created
,08-16 19:32:08.594  3983  3983 V BluetoothAdapterState: isTurningOff()=false
,08-16 19:32:08.595  3983  3983 V BluetoothAdapterState: isTurningOn()=false
08-16 19:32:08.595  3983  3983 V BluetoothAdapterState: isBleTurningOn()=true
08-16 19:32:08.595  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:08.596  3983  4142 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 19:32:08.596  3983  4142 I bt_bluedroid: enable
08-16 19:32:08.596  3983  4143 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 19:32:08.597  3983  4143 I bt_hci  : start_up
,08-16 19:32:08.614  3983  4143 I bt_vendor: alloc value 0xb39f9189
,08-16 19:32:08.614  3983  4143 I bt_vendor: init
08-16 19:32:08.614  3983  4143 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 19:32:08.614  3983  4143 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 19:32:08.721  3983  4143 D bt_hci  : start_up starting async portion
,08-16 19:32:08.722  3983  4150 I bt_hci  : event_finish_startup
08-16 19:32:08.722  3983  4150 I bt_hci_h4: hal_open
,08-16 19:32:08.724  3983  4150 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 19:32:08.737  3983  4150 I bt_userial_vendor: device fd = 51 open
,08-16 19:32:08.763  3983  4150 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 19:32:08.795  3983  4150 D bt_hwcfg: Chipset BCM4354A2
,08-16 19:32:08.795  3983  4150 D bt_hwcfg: Target name = [BCM4354A2]
08-16 19:32:08.796  3983  4150 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 19:32:08.827   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 19:32:08.845  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-16 19:32:08.854   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 19:32:08.854   873   893 I Adreno  : Build Date                       : 10/20/15
08-16 19:32:08.854   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 19:32:08.854   873   893 I Adreno  : Local Branch                     : M14
08-16 19:32:08.854   873   893 I Adreno  : Remote Branch                    : 
08-16 19:32:08.854   873   893 I Adreno  : Remote Branch                    : 
08-16 19:32:08.854   873   893 I Adreno  : Reconstruct Branch               : 
,08-16 19:32:08.891   282  1300 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (336 us)
,08-16 19:32:09.419  3983  4150 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 19:32:09.421  3983  4150 D bt_hwcfg: Settlement delay -- 100 ms
08-16 19:32:09.422  3983  4150 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 19:32:09.539  3983  4150 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 19:32:09.542  3983  4150 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 19:32:09.552  3807  3807 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 19:32:09.552  3807  3807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 19:32:09.567  3983  4150 I bt_hwcfg: vendor lib fwcfg completed
,08-16 19:32:09.567  3983  4150 I bt_vendor: firmware callback
,08-16 19:32:09.567  3983  4150 I bt_hci  : firmware_config_callback
,08-16 19:32:09.593   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 19:32:09.599  3807  3807 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f0f2c74 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@dd85d9f, 16908290=android.view.AbsSavedState$1@dd85d9f}, android:focusedViewId=100}]}]
08-16 19:32:09.601  3807  3807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 19:32:09.603  3807  3807 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 19:32:09.603  3983  4153 I bt_btu  : btu_task pending for preload complete event
,08-16 19:32:09.603  3983  4153 I bt_btu_task: Bluetooth chip preload is complete
08-16 19:32:09.603  3983  4153 I bt_btu  : btu_task received preload complete event
08-16 19:32:09.603  3807  3807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 19:32:09.609  3983  4153 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 19:32:09.609  3983  4153 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 19:32:09.610  3983  4153 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 19:32:09.619   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 19:32:09.623   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 19:32:09.626   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-16 19:32:09.626   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 19:32:09.648   873   882 I art     : Background partial concurrent mark sweep GC freed 66948(4MB) AllocSpace objects, 17(512KB) LOS objects, 33% free, 29MB/43MB, paused 1.971ms total 120.800ms
,08-16 19:32:09.749  3983  4153 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
08-16 19:32:09.749  3983  4153 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-16 19:32:09.759  3983  4146 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 19:32:09.763  3983  4146 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 19:32:09.763  3983  4146 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 19:32:09.769  3983  4146 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 19:32:09.773  3983  4146 D BluetoothAdapterProperties: Scan Mode:20
,08-16 19:32:09.774  3983  4146 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 19:32:09.774  3983  4146 D bt_hci  : do_postload posting postload work item
,08-16 19:32:09.775  3983  4150 I bt_hci  : event_postload
,08-16 19:32:09.775  3983  4150 I bt_vendor: sco_config_cb
08-16 19:32:09.775  3983  4150 I bt_hci  : sco_config_callback postload finished.
08-16 19:32:09.778  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:09.778  3983  4146 D bt_bte_conf: Device ID record 1 : primary
,08-16 19:32:09.778  3983  4146 D bt_bte_conf:   vendorId            = 000f
08-16 19:32:09.778  3983  4146 D bt_bte_conf:   vendorIdSource      = 0001,
08-16 19:32:09.778  3983  4146 D bt_bte_conf:   product             = 1200
08-16 19:32:09.778  3983  4146 D bt_bte_conf:   version             = 1436
,08-16 19:32:09.779  3983  4146 D bt_bte_conf:   clientExecutableURL = 
08-16 19:32:09.779  3983  4146 D bt_bte_conf:   serviceDescription  = 
,08-16 19:32:09.779  3983  4146 D bt_bte_conf:   documentationURL    = 
08-16 19:32:09.779  3983  4146 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 19:32:09.780  3983  4143 D bt_stack_manager: event_start_up_stack finished
08-16 19:32:09.781  3983  4142 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 19:32:09.781  3983  4142 D BluetoothAdapterProperties: Setting state to 15
,08-16 19:32:09.782  3983  4142 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 19:32:09.782  3983  4150 I bt_vendor: low_power_mode_cb
,08-16 19:32:09.782  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:09.783  3983  4142 I BluetoothAdapterState: Entering BleOnState
,08-16 19:32:09.790  3983  4142 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 19:32:09.791  3983  4142 D BluetoothAdapterProperties: Setting state to 11
,08-16 19:32:09.791  3983  4142 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 19:32:09.796  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
08-16 19:32:09.797  3983  3983 D HeadsetService: Received start request. Starting profile...,
08-16 19:32:09.805  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:09.807  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:09.810  3983  3983 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 19:32:09.811  3983  3983 D HeadsetStateMachine: make
,08-16 19:32:09.815  3983  4142 I BluetoothAdapterState: Entering PendingCommandState
,08-16 19:32:09.821  3983  3983 D HeadsetStateMachine: max_hf_connections = 1
,08-16 19:32:09.821  3983  3983 I bt_bluedroid: get_profile_interface handsfree
,08-16 19:32:09.821  3983  4146 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-16 19:32:09.822  3983  4146 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 19:32:09.826  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:09.827  3983  3983 D A2dpService: Received start request. Starting profile...
,08-16 19:32:09.827  3983  3983 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 19:32:09.828  3983  3983 I bt_bluedroid: get_profile_interface avrcp
,08-16 19:32:09.834  3983  3983 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 19:32:09.835  3983  3983 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 19:32:09.835  3983  3983 D A2dpStateMachine: make
,08-16 19:32:09.836  3983  3983 I bt_bluedroid: get_profile_interface a2dp
,08-16 19:32:09.837  3983  4146 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 19:32:09.841  3983  4162 D A2dpStateMachine: Enter Disconnected: -2
,08-16 19:32:09.842  3983  3983 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 19:32:09.844  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:09.845  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 19:32:09.845  3878  3878 D BluetoothInputDevice: Proxy object connected
08-16 19:32:09.845  3983  3983 D HidService: Received start request. Starting profile...
08-16 19:32:09.846  3983  3983 I bt_bluedroid: get_profile_interface hidhost
08-16 19:32:09.846  3983  4146 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-16 19:32:09.846  3983  4146 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 19:32:09.846  3983  3983 D HidService: setHidService(): set to: null
08-16 19:32:09.847  3878  3878 D HidProfile: Bluetooth service connected
,08-16 19:32:09.848  3983  3983 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 19:32:09.849  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:09.850  3983  3983 D HealthService: Received start request. Starting profile...
,08-16 19:32:09.851  3983  3983 I bt_bluedroid: get_profile_interface health
,08-16 19:32:09.852  3983  3983 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 19:32:09.853  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:09.855  3983  3983 D PanService: Received start request. Starting profile...
,08-16 19:32:09.856  3983  3983 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 19:32:09.856  3983  3983 I bt_bluedroid: get_profile_interface pan
,08-16 19:32:09.857  3983  4146 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 19:32:09.859   282   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 19:32:09.861  3878  3878 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 19:32:09.861  3983  3983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:09.862   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-16 19:32:09.865   873  1334 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
08-16 19:32:09.866  3983  3983 D BluetoothMapService: Received start request. Starting profile...
,08-16 19:32:09.866   873   893 I DreamManagerService: Entering dreamland.
08-16 19:32:09.866  3983  3983 D BluetoothMapService: start()
08-16 19:32:09.866   873   893 I PowerManagerService: Dozing...
,08-16 19:32:09.867   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
08-16 19:32:09.867  3878  3878 D PanProfile: Bluetooth service connected
,08-16 19:32:09.868  3878  3878 D BluetoothMap: Proxy object connected
08-16 19:32:09.869  3878  3878 D MapProfile: Bluetooth service connected
,08-16 19:32:09.870  3878  3878 D BluetoothMap: getConnectedDevices()
08-16 19:32:09.871  3878  3878 D BluetoothMap: Bluetooth is Not enabled
08-16 19:32:09.879  3983  3983 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 19:32:09.881  3983  3983 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 19:32:09.881  3983  3983 D BluetoothMapAppObserver: createReceiver()
,08-16 19:32:09.884  3983  3983 D BluetoothMapAppObserver: initObservers()
,08-16 19:32:09.884  3983  3983 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 19:32:09.894  3983  3983 V BluetoothAdapterState: isTurningOff()=false
08-16 19:32:09.894  3983  3983 V BluetoothAdapterState: isTurningOn()=true
,08-16 19:32:09.894  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:09.894  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:32:09.897  3983  4160 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 19:32:09.898  3983  3983 V BluetoothAdapterState: isTurningOff()=false
08-16 19:32:09.898  3983  3983 V BluetoothAdapterState: isTurningOn()=true
,08-16 19:32:09.898  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:32:09.898  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:32:09.898  3983  3983 V BluetoothAdapterState: isTurningOff()=false
,08-16 19:32:09.898  3983  3983 V BluetoothAdapterState: isTurningOn()=true
,08-16 19:32:09.898  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:09.898  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:32:09.899  3983  3983 V BluetoothAdapterState: isTurningOff()=false
,08-16 19:32:09.899  3983  3983 V BluetoothAdapterState: isTurningOn()=true
,08-16 19:32:09.899  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:09.900  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:32:09.901  3983  3983 V BluetoothAdapterState: isTurningOff()=false
,08-16 19:32:09.902   376  1279 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-16 19:32:09.903   376  1279 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 19:32:09.903  3983  3983 V BluetoothAdapterState: isTurningOn()=true
,08-16 19:32:09.903  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:09.903  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:09.903  3983  3983 V BluetoothAdapterState: isTurningOff()=false
08-16 19:32:09.903  3983  3983 V BluetoothAdapterState: isTurningOn()=true
,08-16 19:32:09.903  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:09.903  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:09.903  3983  4142 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 19:32:09.903  3983  4142 D BluetoothAdapterProperties: ScanMode =  20
,08-16 19:32:09.904  3983  4142 D BluetoothAdapterProperties: State =  11
08-16 19:32:09.904  3983  4146 D BluetoothAdapterProperties: Scan Mode:21
08-16 19:32:09.905  3983  4146 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 19:32:09.905  3983  4142 D BluetoothAdapterProperties: Setting state to 12
,08-16 19:32:09.905  3983  4142 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 19:32:09.905  1926  2057 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 19:32:09.906   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 19:32:09.906  1366  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 19:32:09.907  3983  4142 I BluetoothAdapterState: Entering OnState
08-16 19:32:09.909  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:09.909  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:09.909  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:09.909  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:32:09.909  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:09.909  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-16 19:32:09.909  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:09.909  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 19:32:09.910   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 19:32:09.911  1366  1366 D BluetoothInputDevice: Proxy object connected
08-16 19:32:09.911  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 19:32:09.911  1366  1366 D HidProfile: Bluetooth service connected
,08-16 19:32:09.913   873  1308 E native  : do suspend false
,08-16 19:32:09.913  3878  3888 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 19:32:09.914  3983  3983 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 19:32:09.914  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:09.914  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:09.914  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:09.914  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:32:09.914  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:09.914  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:09.914  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:09.914  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 19:32:09.914  3983  3983 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 19:32:09.915  1366  2024 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 19:32:09.917  3983  3983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 19:32:09.918  1366  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 19:32:09.918  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-16 19:32:09.920  1366  1378 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 19:32:09.922  1366  1366 D BluetoothMap: Proxy object connected
08-16 19:32:09.922  1366  1366 D MapProfile: Bluetooth service connected
08-16 19:32:09.922  1366  1366 D BluetoothMap: getConnectedDevices()
08-16 19:32:09.922  3878  3890 D BluetoothMap: onBluetoothStateChange: up=true
08-16 19:32:09.922   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 19:32:09.923  3983  3983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 19:32:09.923  3878  3888 D BluetoothPan: onBluetoothStateChange on: true
08-16 19:32:09.925   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 19:32:09.925   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 19:32:09.925  1366  1384 D BluetoothPan: onBluetoothStateChange on: true
,08-16 19:32:09.926  1911  4169 D NfcService: Discovery configuration equal, not updating.
08-16 19:32:09.927  3983  3983 D ObexServerSockets: Succeed to create listening sockets 
08-16 19:32:09.927  3983  3983 D ObexServerSockets0: startAccept()
08-16 19:32:09.927  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 19:32:09.927  1366  1366 D PanProfile: Bluetooth service connected
08-16 19:32:09.927  3983  3983 D ObexServerSockets0: prepareForNewConnect()
08-16 19:32:09.928  1366  2024 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 19:32:09.928  3878  3890 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 19:32:09.932   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 19:32:09.932  3983  4171 D ObexServerSockets0: Accepting socket connection...
08-16 19:32:09.932  3983  3983 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 19:32:09.932  3983  3983 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 19:32:09.934  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:09.936  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:09.936  3983  3983 D BluetoothMapService: onReceive
08-16 19:32:09.936  3983  3983 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 19:32:09.936  3983  3983 D BluetoothMapService: STATE_ON
08-16 19:32:09.937  3983  4172 D ObexServerSockets0: Accepting socket connection...
,08-16 19:32:09.937  1366  1366 D BluetoothA2dp: Proxy object connected
08-16 19:32:09.937   873   873 D BluetoothA2dp: Proxy object connected
08-16 19:32:09.941   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 19:32:09.943   873  1308 E native  : do suspend true
08-16 19:32:09.944  3878  3878 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-16 19:32:09.947  3878  3878 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 19:32:09.953  3878  3878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 19:32:09.954  3878  3878 D BluetoothA2dp: Proxy object connected
,08-16 19:32:09.956  3983  3983 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 19:32:09.956  3983  3983 D ObexServerSockets0: prepareForNewConnect()
08-16 19:32:09.957  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 19:32:09.959  3878  3878 D DockEventReceiver: finishStartingService: stopping service
,08-16 19:32:09.968  1366  1366 D BluetoothPbap: Proxy object connected
,08-16 19:32:09.968  1366  1366 D PbapServerProfile: Bluetooth service connected
08-16 19:32:09.968  3878  3878 D BluetoothPbap: Proxy object connected
08-16 19:32:09.969  3878  3878 D PbapServerProfile: Bluetooth service connected,
,08-16 19:32:09.978  3983  4179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 19:32:09.990  3983  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 19:32:09.992  3983  4183 I BtOppRfcommListener: Accept thread started.
,08-16 19:32:10.043   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 19:32:10.043   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 19:32:10.044  1926  1936 D BluetoothHeadset: Proxy object connected
,08-16 19:32:10.045  1366  1384 D BluetoothHeadset: Proxy object connected
,08-16 19:32:10.045  1366  1366 D HeadsetProfile: Bluetooth service connected
08-16 19:32:10.045   873   873 D BluetoothHeadset: Proxy object connected
08-16 19:32:10.045   873   873 D BluetoothHeadset: Proxy object connected
,08-16 19:32:10.045   873   873 D BluetoothHeadset: Proxy object connected
,08-16 19:32:10.050  3878  3888 D BluetoothHeadset: Proxy object connected
,08-16 19:32:10.050  3878  3878 D HeadsetProfile: Bluetooth service connected
,08-16 19:32:11.465  3983  4142 D BluetoothAdapterState: Current state: ON, message: 23
08-16 19:32:11.465  3983  4142 D BluetoothAdapterProperties: Setting state to 13
08-16 19:32:11.466  3983  4142 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 19:32:11.468  3983  4142 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 19:32:11.470  3983  4142 I BluetoothAdapterState: Entering PendingCommandState
,08-16 19:32:11.482  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 19:32:11.482  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:11.482  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:11.482  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:11.482  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:32:11.482  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:32:11.482  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:11.482  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:11.482  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 19:32:11.482  3983  3983 D BluetoothMapService: onReceive
,08-16 19:32:11.483  3983  3983 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 19:32:11.483  3983  3983 D BluetoothMapService: STATE_TURNING_OFF
08-16 19:32:11.484  3983  3983 D BluetoothMapService: MAP Service closeService in
08-16 19:32:11.485  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:11.485  3983  3983 D BluetoothMapMasInstance0: MAP Service shutdown
,08-16 19:32:11.485  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 19:32:11.485  3983  3983 D ObexServerSockets0: shutdown(block = true)
08-16 19:32:11.487  3983  4171 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 19:32:11.489  3983  4146 D BluetoothAdapterProperties: Scan Mode:20
,08-16 19:32:11.489  3983  4142 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 19:32:11.491  3983  3983 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 19:32:11.492  3983  4172 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 19:32:11.493  3983  3983 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 19:32:11.493  3983  4156 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 19:32:11.493  3983  3983 I BtOppRfcommListener: stopping Accept Thread
,08-16 19:32:11.494  3983  4183 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 19:32:11.494  3983  4183 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 19:32:11.495  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:11.495  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:11.495  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:11.495  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:11.495  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:32:11.495  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 19:32:11.495  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:11.495  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:11.495  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 19:32:11.495  3878  3878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 19:32:11.496  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 19:32:11.496  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 19:32:11.499  3983  3983 D HeadsetService: Received stop request...Stopping profile...
08-16 19:32:11.500  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:11.502  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:11.506  1926  2057 D BluetoothHeadset: Proxy object disconnected
,08-16 19:32:11.506  1366  1378 D BluetoothHeadset: Proxy object disconnected
08-16 19:32:11.506  1366  1366 D HeadsetProfile: Bluetooth service disconnected
08-16 19:32:11.506  3983  3983 D A2dpService: Received stop request...Stopping profile...
,08-16 19:32:11.507  3878  3890 D BluetoothHeadset: Proxy object disconnected
08-16 19:32:11.507   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 19:32:11.507  3983  4162 D A2dpStateMachine: Exit Disconnected: -1
08-16 19:32:11.507   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 19:32:11.507   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 19:32:11.510   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 19:32:11.510  1366  1366 D BluetoothA2dp: Proxy object disconnected
,08-16 19:32:11.511  3878  3878 D DockEventReceiver: finishStartingService: stopping service
,08-16 19:32:11.512  3878  3878 D HeadsetProfile: Bluetooth service disconnected
,08-16 19:32:11.512  3983  3983 D HidService: Received stop request...Stopping profile...
08-16 19:32:11.512  3983  3983 D HidService: Stopping Bluetooth HidService
,08-16 19:32:11.513  3878  3878 D BluetoothA2dp: Proxy object disconnected
,08-16 19:32:11.514  3878  3878 D BluetoothInputDevice: Proxy object disconnected
,08-16 19:32:11.514  3878  3878 D HidProfile: Bluetooth service disconnected
08-16 19:32:11.514  1366  1366 D BluetoothInputDevice: Proxy object disconnected
08-16 19:32:11.514  1366  1366 D HidProfile: Bluetooth service disconnected
08-16 19:32:11.515  3983  3983 D HealthService: Received stop request...Stopping profile...
,08-16 19:32:11.516  3983  3983 D PanService: Received stop request...Stopping profile...
08-16 19:32:11.517  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 19:32:11.517  1366  1366 D PanProfile: Bluetooth service disconnected
08-16 19:32:11.517  3878  3878 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 19:32:11.517  3878  3878 D PanProfile: Bluetooth service disconnected
08-16 19:32:11.518  3983  3983 D BluetoothMapService: Received stop request...Stopping profile...
08-16 19:32:11.518  3983  3983 D BluetoothMapService: stop()
08-16 19:32:11.518  3983  3983 D BluetoothMapAppObserver: deinitObservers()
08-16 19:32:11.518  3983  3983 D BluetoothMapAppObserver: removeReceiver()
,08-16 19:32:11.520  3878  3878 D BluetoothMap: Proxy object disconnected
08-16 19:32:11.520  1366  1366 D BluetoothMap: Proxy object disconnected
,08-16 19:32:11.520  1366  1366 D MapProfile: Bluetooth service disconnected
08-16 19:32:11.520  3878  3878 D MapProfile: Bluetooth service disconnected
,08-16 19:32:11.520  3983  3983 V BluetoothAdapterState: isTurningOff()=true
,08-16 19:32:11.520  3983  3983 V BluetoothAdapterState: isTurningOn()=false
,08-16 19:32:11.520  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:11.521  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:32:11.524  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 19:32:11.525  3983  3983 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 19:32:11.525  3983  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 19:32:11.525  3983  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 19:32:11.525  3983  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 19:32:11.525  3983  4146 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-16 19:32:11.525  3983  4146 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
08-16 19:32:11.525  3983  3983 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 19:32:11.526  3983  3983 V BluetoothAdapterState: isTurningOff()=true
,08-16 19:32:11.526  3983  3983 V BluetoothAdapterState: isTurningOn()=false
08-16 19:32:11.526  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:11.526  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:32:11.527  3983  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 19:32:11.527  3983  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 19:32:11.527  3983  4153 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 19:32:11.527  3983  4153 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 19:32:11.527  3983  4153 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 19:32:11.527  3983  4153 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 19:32:11.528  3983  4146 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 19:32:11.528  3983  3983 V BluetoothAdapterState: isTurningOff()=true
08-16 19:32:11.528  3983  3983 V BluetoothAdapterState: isTurningOn()=false
,08-16 19:32:11.528  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:32:11.528  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:32:11.529  3983  3983 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 19:32:11.529  3983  4146 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 19:32:11.529  3983  3983 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 19:32:11.529  3983  3983 V BluetoothAdapterState: isTurningOff()=true
08-16 19:32:11.529  3983  3983 V BluetoothAdapterState: isTurningOn()=false
08-16 19:32:11.530  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:11.530  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:11.530  3983  3983 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 19:32:11.530  3983  4146 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 19:32:11.530  3983  3983 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 19:32:11.530  3983  3983 V BluetoothAdapterState: isTurningOff()=true
08-16 19:32:11.531  3983  3983 V BluetoothAdapterState: isTurningOn()=false
08-16 19:32:11.531  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:32:11.531  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:32:11.531  3983  3983 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 19:32:11.531  3983  3983 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 19:32:11.532  3983  3983 D BluetoothMapService: MAP Service closeService in
08-16 19:32:11.532  3983  3983 V BluetoothAdapterState: isTurningOff()=true,
08-16 19:32:11.532  3983  3983 V BluetoothAdapterState: isTurningOn()=false
,08-16 19:32:11.532  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:32:11.533  3983  3983 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:11.533  3983  4142 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 19:32:11.533  3983  4142 D BluetoothAdapterProperties: Setting state to 15
08-16 19:32:11.533  3983  4142 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-16 19:32:11.533  3983  3983 D BluetoothMapService: cleanup()
,08-16 19:32:11.533  3983  4142 I BluetoothAdapterState: Entering BleOnState
08-16 19:32:11.533  3983  3983 D BluetoothMapService: MAP Service closeService in
08-16 19:32:11.534  1926  1938 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:32:11.534   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:32:11.534  1366  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 19:32:11.535  3878  3888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 19:32:11.536  3878  3890 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 19:32:11.537  1366  2024 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 19:32:11.537  1366  1366 D BluetoothPbap: Proxy object disconnected
08-16 19:32:11.537  1366  1366 D PbapServerProfile: Bluetooth service disconnected
,08-16 19:32:11.539  1366  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 19:32:11.539  1366  1378 D BluetoothMap: onBluetoothStateChange: up=false
08-16 19:32:11.540  3878  3888 D BluetoothMap: onBluetoothStateChange: up=false
08-16 19:32:11.540   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 19:32:11.540  3878  3890 D BluetoothPan: onBluetoothStateChange on: false
,08-16 19:32:11.540   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:32:11.541   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:32:11.541  1366  2024 D BluetoothPan: onBluetoothStateChange on: false
08-16 19:32:11.544  1366  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:32:11.544  3878  3888 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 19:32:11.545  3878  4189 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 19:32:11.545  3983  4142 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-16 19:32:11.545  3983  4142 D BluetoothAdapterProperties: Setting state to 16
08-16 19:32:11.545  3983  4142 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 19:32:11.546  3983  4142 D BluetoothAdapterProperties: onBleDisable
,08-16 19:32:11.548  3983  4146 D BluetoothAdapterProperties: Scan Mode:20
08-16 19:32:11.548  3983  4142 I BluetoothAdapterState: Entering PendingCommandState
08-16 19:32:11.549  3983  4143 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 19:32:11.549  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:11.549  3983  4153 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 19:32:11.549  3983  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 19:32:11.551  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:11.551  3878  3878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 19:32:11.552  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:11.553  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:11.557  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 19:32:11.557  3878  3878 D DockEventReceiver: finishStartingService: stopping service
,08-16 19:32:11.741   873  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-16 19:32:11.750  3983  4146 I bt_hci  : shut_down
,08-16 19:32:11.750  3983  4150 D bt_hwcfg: hw_epilog_process
,08-16 19:32:11.765  3983  4150 I bt_vendor: low_power_mode_cb
,08-16 19:32:11.785  3983  4150 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 19:32:11.786  3983  4150 I bt_vendor: epilog_cb
,08-16 19:32:11.786  3983  4150 I bt_hci  : epilog_finished_callback
,08-16 19:32:11.793  3983  4146 I bt_hci_h4: hal_close
,08-16 19:32:11.795  3983  4146 I bt_userial_vendor: device fd = 51 close
,08-16 19:32:11.909  3983  4143 D bt_stack_manager: event_shut_down_stack finished.
,08-16 19:32:11.911  3983  4142 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 19:32:11.916  3983  4142 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 19:32:11.917  3983  3983 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 19:32:11.918  3983  3983 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 19:32:11.918  3983  3983 D BtGatt.GattService: stop()
,08-16 19:32:11.919  3983  3983 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 19:32:11.923  3983  3983 V BluetoothAdapterState: isTurningOff()=false
08-16 19:32:11.924  3983  3983 V BluetoothAdapterState: isTurningOn()=false
08-16 19:32:11.924  3983  3983 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:32:11.924  3983  3983 V BluetoothAdapterState: isBleTurningOff()=true
08-16 19:32:11.926  3983  4142 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 19:32:11.926  3983  4142 D BluetoothAdapterProperties: Setting state to 10
08-16 19:32:11.927  3983  4142 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 19:32:11.928  3983  4142 I BluetoothAdapterState: Entering OffState
,08-16 19:32:11.930   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 19:32:11.953  3983  3983 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 19:32:11.953  3983  3983 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 19:32:11.954  3983  4143 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 19:32:11.960  3983  3983 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 19:32:11.968  3983  4143 D bt_stack_manager: event_clean_up_stack finished.
,08-16 19:32:11.969  3983  3983 I art     : System.exit called, status: 0
,08-16 19:32:11.970  3983  3983 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 19:32:12.023   873  1670 I ActivityManager: Process com.android.bluetooth (pid 3983) has died
,08-16 19:32:12.672  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:12.684  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:12.690  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:12.743  1516  2251 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 19:32:12.744  1516  2251 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 19:32:12.744  1516  2251 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:32:12.744  1516  2251 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:12.764  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 19:32:12.764  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 19:32:12.764  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 19:32:14.462  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 19:32:14.462  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:15.916  2091  2646 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 19:32:17.470  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 19:32:17.470  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a07eec added. We now have 6 listener(s)
08-16 19:32:17.471  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:32:17.474  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 19:32:17.475  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68a22b5 added. We now have 7 listener(s)
08-16 19:32:17.475  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:32:17.477  3807  3859 I System.out: IsBluetoothEnabled
,08-16 19:32:17.486  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:17.532   873   890 I ActivityManager: Start proc 4197:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 19:32:17.648  4197  4197 D AdapterServiceConfig: Adding HeadsetService
,08-16 19:32:17.648  4197  4197 D AdapterServiceConfig: Adding A2dpService
08-16 19:32:17.648  4197  4197 D AdapterServiceConfig: Adding HidService
,08-16 19:32:17.649  4197  4197 D AdapterServiceConfig: Adding HealthService
08-16 19:32:17.649  4197  4197 D AdapterServiceConfig: Adding PanService
,08-16 19:32:17.649  4197  4197 D AdapterServiceConfig: Adding GattService
08-16 19:32:17.649  4197  4197 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 19:32:17.664  4197  4197 D BluetoothAdapterState: make() - Creating AdapterState
08-16 19:32:17.664   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1d7a0f:true
,08-16 19:32:17.669  4197  4197 I bt_bluedroid: init
,08-16 19:32:17.669  4197  4209 I BluetoothAdapterState: Entering OffState
,08-16 19:32:17.673  4197  4210 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 19:32:17.673  4197  4210 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 19:32:17.673  4197  4210 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 19:32:17.673  4197  4210 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 19:32:17.675  4197  4197 I bt_bluedroid: get_profile_interface socket
,08-16 19:32:17.676  4197  4197 I bt_bluedroid: get_profile_interface sdp
,08-16 19:32:17.680  4197  4208 I bt_bluedroid: config_hci_snoop_log
08-16 19:32:17.680  4197  4213 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 19:32:17.682   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 19:32:17.683  4197  4213 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 19:32:17.690  4197  4209 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 19:32:17.691  4197  4209 D BluetoothAdapterProperties: Setting state to 14
08-16 19:32:17.691  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 19:32:17.695  4197  4209 D BluetoothBondStateMachine: make
,08-16 19:32:17.700  4197  4214 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 19:32:17.708  4197  4209 I BluetoothAdapterState: Entering PendingCommandState
,08-16 19:32:17.710  4197  4197 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 19:32:17.718  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:17.719  4197  4197 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 19:32:17.720  4197  4197 D BtGatt.GattService: Received start request. Starting profile...
,08-16 19:32:17.721  4197  4197 D BtGatt.GattService: start()
08-16 19:32:17.721  4197  4197 I bt_bluedroid: get_profile_interface gatt
,08-16 19:32:17.723  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:17.723  4197  4197 D BtGatt.AdvertiseManager: advertise manager created
,08-16 19:32:17.738  4197  4197 V BluetoothAdapterState: isTurningOff()=false
,08-16 19:32:17.739  4197  4197 V BluetoothAdapterState: isTurningOn()=false
08-16 19:32:17.739  4197  4197 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 19:32:17.739  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 19:32:17.740  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 19:32:17.741  4197  4209 I bt_bluedroid: enable
08-16 19:32:17.741  4197  4210 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 19:32:17.742  4197  4210 I bt_hci  : start_up
,08-16 19:32:17.768  4197  4210 I bt_vendor: alloc value 0xb3a70189
08-16 19:32:17.769  4197  4210 I bt_vendor: init
08-16 19:32:17.769  4197  4210 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 19:32:17.769  4197  4210 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 19:32:17.877  4197  4210 D bt_hci  : start_up starting async portion
,08-16 19:32:17.878  4197  4217 I bt_hci  : event_finish_startup
08-16 19:32:17.878  4197  4217 I bt_hci_h4: hal_open
08-16 19:32:17.878  4197  4217 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 19:32:17.889  4197  4217 I bt_userial_vendor: device fd = 51 open
,08-16 19:32:17.920  4197  4217 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 19:32:17.952  4197  4217 D bt_hwcfg: Chipset BCM4354A2
,08-16 19:32:17.952  4197  4217 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 19:32:17.953  4197  4217 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 19:32:18.611  4197  4217 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 19:32:18.613  4197  4217 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 19:32:18.613  4197  4217 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 19:32:18.730  4197  4217 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 19:32:18.731  4197  4217 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 19:32:18.760  4197  4217 I bt_hwcfg: vendor lib fwcfg completed
,08-16 19:32:18.761  4197  4217 I bt_vendor: firmware callback
08-16 19:32:18.761  4197  4217 I bt_hci  : firmware_config_callback
,08-16 19:32:18.772  4197  4219 I bt_btu  : btu_task pending for preload complete event
,08-16 19:32:18.772  4197  4219 I bt_btu_task: Bluetooth chip preload is complete
,08-16 19:32:18.772  4197  4219 I bt_btu  : btu_task received preload complete event
,08-16 19:32:18.782  4197  4219 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 19:32:18.783  4197  4219 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 19:32:18.783  4197  4219 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 19:32:18.783  4197  4219 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 19:32:18.784  4197  4219 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 19:32:18.784  4197  4219 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 19:32:18.784  4197  4219 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 19:32:18.784  4197  4219 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 19:32:18.785  4197  4219 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 19:32:18.785  4197  4219 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 19:32:18.785  4197  4219 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 19:32:18.785  4197  4219 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 19:32:18.786  4197  4219 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 19:32:18.786  4197  4219 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 19:32:18.786  4197  4219 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 19:32:18.923  4197  4219 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39edd9d
,08-16 19:32:18.923  4197  4219 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39edd9d 
,08-16 19:32:18.930  4197  4213 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 19:32:18.932  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 19:32:18.932  4197  4213 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 19:32:18.936  4197  4213 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 19:32:18.938  4197  4213 D BluetoothAdapterProperties: Scan Mode:20
08-16 19:32:18.938  4197  4213 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 19:32:18.939  4197  4213 D bt_hci  : do_postload posting postload work item
08-16 19:32:18.940  4197  4217 I bt_hci  : event_postload
08-16 19:32:18.940  4197  4217 I bt_vendor: sco_config_cb
08-16 19:32:18.940  4197  4217 I bt_hci  : sco_config_callback postload finished.
08-16 19:32:18.940  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:18.942  4197  4213 D bt_bte_conf: Device ID record 1 : primary
08-16 19:32:18.942  4197  4213 D bt_bte_conf:   vendorId            = 000f
08-16 19:32:18.942  4197  4213 D bt_bte_conf:   vendorIdSource      = 0001
08-16 19:32:18.942  4197  4213 D bt_bte_conf:   product             = 1200
08-16 19:32:18.942  4197  4213 D bt_bte_conf:   version             = 1436
08-16 19:32:18.942  4197  4213 D bt_bte_conf:   clientExecutableURL = 
08-16 19:32:18.942  4197  4213 D bt_bte_conf:   serviceDescription  = 
08-16 19:32:18.942  4197  4213 D bt_bte_conf:   documentationURL    = 
08-16 19:32:18.942  4197  4213 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 19:32:18.942  4197  4210 D bt_stack_manager: event_start_up_stack finished
08-16 19:32:18.943  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 19:32:18.944  4197  4209 D BluetoothAdapterProperties: Setting state to 15
08-16 19:32:18.944  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 19:32:18.945  4197  4209 I BluetoothAdapterState: Entering BleOnState
08-16 19:32:18.948  4197  4217 I bt_vendor: low_power_mode_cb
,08-16 19:32:18.950  4197  4209 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 19:32:18.951  4197  4209 D BluetoothAdapterProperties: Setting state to 11
08-16 19:32:18.951  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 19:32:18.959  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:18.960  4197  4197 D HeadsetService: Received start request. Starting profile...
08-16 19:32:18.963  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:18.964  4197  4197 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 19:32:18.966  4197  4197 D HeadsetStateMachine: make
,08-16 19:32:18.977  4197  4209 I BluetoothAdapterState: Entering PendingCommandState
,08-16 19:32:18.977  4197  4197 D HeadsetStateMachine: max_hf_connections = 1
08-16 19:32:18.977  4197  4197 I bt_bluedroid: get_profile_interface handsfree
08-16 19:32:18.977  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-16 19:32:18.977  4197  4213 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 19:32:18.981  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:18.981  4197  4197 D A2dpService: Received start request. Starting profile...
,08-16 19:32:18.982  4197  4197 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 19:32:18.982  4197  4197 I bt_bluedroid: get_profile_interface avrcp
,08-16 19:32:18.987  4197  4197 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 19:32:18.988  4197  4197 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 19:32:18.988  4197  4197 D A2dpStateMachine: make
,08-16 19:32:18.989  4197  4197 I bt_bluedroid: get_profile_interface a2dp
,08-16 19:32:18.989  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 19:32:18.991  4197  4228 D A2dpStateMachine: Enter Disconnected: -2
,08-16 19:32:18.992  4197  4197 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 19:32:18.992  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:18.993  4197  4197 D HidService: Received start request. Starting profile...
,08-16 19:32:18.993  4197  4197 I bt_bluedroid: get_profile_interface hidhost
,08-16 19:32:18.993  4197  4197 D HidService: setHidService(): set to: null
08-16 19:32:18.993  4197  4213 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cf3e5
08-16 19:32:18.993  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 19:32:18.994  4197  4197 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 19:32:18.994  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:18.995  4197  4197 D HealthService: Received start request. Starting profile...
,08-16 19:32:18.996  4197  4197 I bt_bluedroid: get_profile_interface health
08-16 19:32:18.997  4197  4197 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 19:32:18.998  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:18.998  4197  4197 D PanService: Received start request. Starting profile...
08-16 19:32:18.999  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 19:32:18.999  4197  4197 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 19:32:18.999  4197  4197 I bt_bluedroid: get_profile_interface pan
08-16 19:32:19.000  4197  4213 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 19:32:19.004  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
,08-16 19:32:19.004  4197  4197 D BluetoothMapService: Received start request. Starting profile...
08-16 19:32:19.004  4197  4197 D BluetoothMapService: start()
,08-16 19:32:19.006  4197  4197 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 19:32:19.007  4197  4197 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 19:32:19.007  4197  4197 D BluetoothMapAppObserver: createReceiver()
,08-16 19:32:19.008  4197  4197 D BluetoothMapAppObserver: initObservers()
,08-16 19:32:19.008  4197  4197 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 19:32:19.014  4197  4197 V BluetoothAdapterState: isTurningOff()=false
,08-16 19:32:19.014  4197  4197 V BluetoothAdapterState: isTurningOn()=true
08-16 19:32:19.014  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:32:19.014  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:19.014  4197  4226 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 19:32:19.016  4197  4197 V BluetoothAdapterState: isTurningOff()=false
08-16 19:32:19.016  4197  4197 V BluetoothAdapterState: isTurningOn()=true
08-16 19:32:19.016  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:19.016  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:19.016  4197  4197 V BluetoothAdapterState: isTurningOff()=false
08-16 19:32:19.016  4197  4197 V BluetoothAdapterState: isTurningOn()=true
,08-16 19:32:19.016  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:32:19.016  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:19.016  4197  4197 V BluetoothAdapterState: isTurningOff()=false
,08-16 19:32:19.017  4197  4197 V BluetoothAdapterState: isTurningOn()=true
,08-16 19:32:19.017  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:32:19.017  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:19.019  4197  4197 V BluetoothAdapterState: isTurningOff()=false
08-16 19:32:19.019  4197  4197 V BluetoothAdapterState: isTurningOn()=true
08-16 19:32:19.019  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
08-16 19:32:19.019  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:19.020  4197  4197 V BluetoothAdapterState: isTurningOff()=false
08-16 19:32:19.020  4197  4197 V BluetoothAdapterState: isTurningOn()=true
08-16 19:32:19.020  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 19:32:19.020  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
08-16 19:32:19.020  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 19:32:19.021  4197  4209 D BluetoothAdapterProperties: ScanMode =  20
08-16 19:32:19.021  4197  4209 D BluetoothAdapterProperties: State =  11
,08-16 19:32:19.023  4197  4209 D BluetoothAdapterProperties: Setting state to 12
08-16 19:32:19.023  4197  4213 D BluetoothAdapterProperties: Scan Mode:21
08-16 19:32:19.024  4197  4213 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 19:32:19.023  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 19:32:19.024  4197  4209 I BluetoothAdapterState: Entering OnState
08-16 19:32:19.024  1926  1938 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 19:32:19.025   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 19:32:19.026  1366  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 19:32:19.028  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:19.028  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:19.028  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:19.028  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:32:19.028  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:19.028  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:19.028  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:19.028  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 19:32:19.028  3878  4189 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 19:32:19.029  1366  1366 D BluetoothInputDevice: Proxy object connected
,08-16 19:32:19.029  1366  1366 D HidProfile: Bluetooth service connected
08-16 19:32:19.031  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 19:32:19.032  3878  3890 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 19:32:19.035  4197  4197 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 19:32:19.036  4197  4197 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-16 19:32:19.037  1366  1378 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 19:32:19.038  4197  4197 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 19:32:19.041  1366  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 19:32:19.041  4197  4197 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 19:32:19.042  4197  4197 D ObexServerSockets: Succeed to create listening sockets 
,08-16 19:32:19.043  4197  4197 D ObexServerSockets0: startAccept()
,08-16 19:32:19.043  1366  1366 D BluetoothA2dp: Proxy object connected
08-16 19:32:19.043  4197  4197 D ObexServerSockets0: prepareForNewConnect()
08-16 19:32:19.043  1366  1378 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 19:32:19.045  4197  4197 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 19:32:19.045  4197  4197 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 19:32:19.046  4197  4234 D ObexServerSockets0: Accepting socket connection...
08-16 19:32:19.046  3878  4189 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 19:32:19.047  1366  1366 D BluetoothMap: Proxy object connected
,08-16 19:32:19.047  1366  1366 D MapProfile: Bluetooth service connected
,08-16 19:32:19.044  3878  3878 D BluetoothA2dp: Proxy object connected
08-16 19:32:19.047  1366  1366 D BluetoothMap: getConnectedDevices()
,08-16 19:32:19.049  4197  4235 D ObexServerSockets0: Accepting socket connection...
,08-16 19:32:19.051   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 19:32:19.052   873   873 D BluetoothA2dp: Proxy object connected
08-16 19:32:19.052  3878  3890 D BluetoothPan: onBluetoothStateChange on: true
08-16 19:32:19.053  3878  3878 D BluetoothMap: Proxy object connected
08-16 19:32:19.053  3878  3878 D MapProfile: Bluetooth service connected
08-16 19:32:19.053  3878  3878 D BluetoothMap: getConnectedDevices()
,08-16 19:32:19.055   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 19:32:19.055   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 19:32:19.055  1366  1384 D BluetoothPan: onBluetoothStateChange on: true
08-16 19:32:19.055  3878  3878 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 19:32:19.056  3878  3878 D PanProfile: Bluetooth service connected
,08-16 19:32:19.057  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 19:32:19.057  1366  2024 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 19:32:19.057  1366  1366 D PanProfile: Bluetooth service connected
08-16 19:32:19.058  3878  4189 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 19:32:19.060  3878  3890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 19:32:19.061  3878  3878 D BluetoothInputDevice: Proxy object connected
,08-16 19:32:19.061  3878  3878 D HidProfile: Bluetooth service connected
,08-16 19:32:19.063   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 19:32:19.064  4197  4197 D BluetoothMapService: onReceive
08-16 19:32:19.064  4197  4197 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 19:32:19.065  4197  4197 D BluetoothMapService: STATE_ON
08-16 19:32:19.065  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:19.073  3878  3878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 19:32:19.079  3878  3878 D DockEventReceiver: finishStartingService: stopping service
,08-16 19:32:19.082  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 19:32:19.090  3878  3878 D BluetoothPbap: Proxy object connected
,08-16 19:32:19.090  1366  1366 D BluetoothPbap: Proxy object connected
08-16 19:32:19.090  3878  3878 D PbapServerProfile: Bluetooth service connected
08-16 19:32:19.090  1366  1366 D PbapServerProfile: Bluetooth service connected
08-16 19:32:19.090  4197  4197 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 19:32:19.090  4197  4197 D ObexServerSockets0: prepareForNewConnect()
,08-16 19:32:19.099  4197  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 19:32:19.134  1926  1936 D BluetoothHeadset: Proxy object connected
,08-16 19:32:19.134  4197  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 19:32:19.135  1366  1384 D BluetoothHeadset: Proxy object connected
08-16 19:32:19.136  1366  1366 D HeadsetProfile: Bluetooth service connected
08-16 19:32:19.137  3878  4189 D BluetoothHeadset: Proxy object connected
,08-16 19:32:19.137  4197  4243 I BtOppRfcommListener: Accept thread started.
08-16 19:32:19.137   873   873 D BluetoothHeadset: Proxy object connected
08-16 19:32:19.137   873   873 D BluetoothHeadset: Proxy object connected
08-16 19:32:19.137  3878  3878 D HeadsetProfile: Bluetooth service connected
08-16 19:32:19.138   873   873 D BluetoothHeadset: Proxy object connected
,08-16 19:32:19.156   873   890 D BluetoothHeadset: Proxy object connected
08-16 19:32:19.156   873   890 D BluetoothHeadset: Proxy object connected
,08-16 19:32:19.158  1366  1378 D BluetoothHeadset: Proxy object connected
,08-16 19:32:19.158  1366  1366 D HeadsetProfile: Bluetooth service connected
,08-16 19:32:19.161  3878  3890 D BluetoothHeadset: Proxy object connected
,08-16 19:32:19.161  3878  3878 D HeadsetProfile: Bluetooth service connected
,08-16 19:32:19.507  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:19.507  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:19.507  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:19.507  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 19:32:19.507  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:19.507  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:19.507  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:19.507  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 19:32:19.514  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 19:32:19.520  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 19:32:19.520  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c621d4a added. We now have 8 listener(s)
,08-16 19:32:19.521  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:32:19.528   873  1982 D WifiService: setWifiEnabled: false pid=3807, uid=10000
,08-16 19:32:19.528   873  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 19:32:19.538  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:19.539   873   883 D WifiService: setWifiEnabled: true pid=3807, uid=10000
,08-16 19:32:19.539   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 19:32:19.559   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-16 19:32:19.573  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:19.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:19.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:19.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:19.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:19.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 19:32:19.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 19:32:19.573  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 19:32:19.580  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 19:32:19.588   873  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-16 19:32:19.589   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 19:32:19.590   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000,
,08-16 19:32:19.591   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 19:32:19.591   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 19:32:19.591   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 19:32:19.591   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 19:32:19.606   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 19:32:19.607   873  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.22 rxSuccessRate=0.29 delta 1000 -> 1000
08-16 19:32:19.607   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 19:32:19.609   372   871 D CommandListener: Setting iface cfg
,08-16 19:32:19.616   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 19:32:19.616   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 19:32:19.617   873  1308 E native  : do suspend true
,08-16 19:32:19.625   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 19:32:19.630   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 19:32:19.632   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 19:32:19.632   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 19:32:19.642   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 19:32:19.705   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 19:32:19.708  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 19:32:20.130  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 19:32:20.171  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 19:32:20.172  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 19:32:20.180   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 19:32:20.184   873  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 19:32:20.186   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 19:32:20.186   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 19:32:20.203   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 19:32:20.214   372   871 D CommandListener: Setting iface cfg
,08-16 19:32:20.215   873  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 19:32:20.222   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 19:32:20.239   873  4251 D DhcpClient: Receive thread started
,08-16 19:32:20.323   873  1308 E native  : do suspend false
,08-16 19:32:20.344   873  1839 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 19:32:20.358   873  4251 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-16 19:32:20.359   873  1839 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-16 19:32:20.363   873  1839 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 19:32:20.379   873  4251 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 19:32:20.380   873  1839 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 19:32:20.385   372   871 D CommandListener: Setting iface cfg
,08-16 19:32:20.396   873  1839 D DhcpClient: Scheduling renewal in 86399s
,08-16 19:32:20.398   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 19:32:20.402   873  1308 E native  : do suspend true
,08-16 19:32:20.424   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 19:32:20.427   873  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 19:32:20.429   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 19:32:20.431   873  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 19:32:20.444   873  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 19:32:20.485   873  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 19:32:20.486   873  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 19:32:20.488   873  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 19:32:20.491   873  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 19:32:20.493   873  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 19:32:20.505   873  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 19:32:20.511   873  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 19:32:20.511   873  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-16 19:32:20.511   873  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 19:32:20.512   873  1310 D ConnectivityService:    accepting network in place of null
08-16 19:32:20.512   873  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 19:32:20.513   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 19:32:20.514   873  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 19:32:20.528   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=161838, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:32:20.545   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 19:32:20.562  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:20.562  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:20.562  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:20.562  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:20.562  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:20.562  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:20.562  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:32:20.562  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:32:20.569  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:32:20.579  3807  3859 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 19:32:20.581  3807  3859 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 19:32:20.589  3807  3859 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f0f2c74 Bundle[{}]
,08-16 19:32:20.590  3807  3859 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 19:32:20.590  3807  3859 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 19:32:20.590  3807  3859 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 19:32:20.591  3807  3859 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 19:32:20.591  3807  3859 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 19:32:20.592  3807  3859 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 19:32:20.595   873  4249 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.142,2a00:1450:4001:804::200e
,08-16 19:32:20.597  3807  3859 I System.out: Running OutgoingSocketThread
,08-16 19:32:20.598  3807  4259 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 426)
,08-16 19:32:20.599  3807  4259 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47554
,08-16 19:32:20.599  3807  4259 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 19:32:20.622   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 19:32:20.627   873  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 19:32:20.627   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 19:32:20.631   873  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 19:32:20.634   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 19:32:20.643  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 19:32:20.643  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:20.643  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:20.643  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:20.643  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:20.643  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:20.643  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:32:20.643  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 19:32:20.646  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:32:20.654  2002  2002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 19:32:20.658  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 19:32:20.670  1739  1739 D SystemUpdateService: onCreate
08-16 19:32:20.671   873  4249 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 17:32:20 GMT], X-Android-Received-Millis=[1471368740670], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471368740645]}
,08-16 19:32:20.673   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 19:32:20.673   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 19:32:20.673   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 19:32:20.675   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 19:32:20.679  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 19:32:20.700  1739  4262 I SystemUpdateService: active receiver: enabled
,08-16 19:32:20.703  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 19:32:20.705  1739  2411 I iu.UploadsManager: num queued entries: 0
,08-16 19:32:20.711  1739  2411 I iu.UploadsManager: num updated entries: 0
,08-16 19:32:20.712  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 19:32:20.715  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 19:32:20.716  3997  3997 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 19:32:20.721  1739  4265 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 19:32:20.721  1739  4265 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 19:32:20.724  3997  3997 D SprintDMHelper: simOperator: 
,08-16 19:32:20.724  3997  3997 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 19:32:20.733  1739  4265 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 19:32:20.710  1739  4262 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 19:32:20.742  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:20.747  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:20.752  1739  2411 I iu.SyncManager: NEXT; no task
,08-16 19:32:20.757  1739  4262 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 19:32:20.757  1739  4262 I SystemUpdateService: now status is 0 (complete)
08-16 19:32:20.757  1739  4262 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 19:32:20.757  1739  4262 I SystemUpdateService: file has been verified
08-16 19:32:20.757  1739  4262 I SystemUpdateService: OTA package size = 12249756
,08-16 19:32:20.776  1739  4262 I SystemUpdateService: showing system update notification
,08-16 19:32:20.784  1516  2251 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 19:32:20.785  1516  2251 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 19:32:20.785  1516  2251 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:32:20.785  1516  2251 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:20.792  1739  1739 D SystemUpdateService: onDestroy
,08-16 19:32:20.799  1739  4265 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-16 19:32:20.855  3955  4267 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 19:32:21.600  3807  3859 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 427)
08-16 19:32:21.600  3807  3859 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 427)
,08-16 19:32:21.609  3807  3859 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 432)
,08-16 19:32:21.612  3807  3859 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 19:32:21.612  3807  3859 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 433)
,08-16 19:32:21.618  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 19:32:21.618  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bef34bb added. We now have 2 listener(s)
,08-16 19:32:21.620  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 19:32:21.620  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.620  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 19:32:21.620  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:32:21.620  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8c9dd8 added. We now have 9 listener(s)
08-16 19:32:21.620  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 19:32:21.621  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 19:32:21.624  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:32:21.626   873  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 19:32:21.630  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:32:21.630  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:21.630  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:21.630  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:21.630  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:21.630  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:21.630  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:32:21.630  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:32:21.633  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:32:21.634  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 19:32:21.634  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 19:32:21.634  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12cc416 added. We now have 3 listener(s)
,08-16 19:32:21.639  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 19:32:21.640  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.640  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:21.640  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 19:32:21.641  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 19:32:21.641  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d26197 added. We now have 10 listener(s)
08-16 19:32:21.641  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:32:21.642  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:32:21.642  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:32:21.642  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:32:21.643  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 19:32:21.643  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.643  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:32:21.643  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:21.643  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 19:32:21.644  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bef34bb removed from the list
08-16 19:32:21.644  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:32:21.644  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8c9dd8 removed from the list
,08-16 19:32:21.644  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:32:21.644  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:32:21.645  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.645  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.647  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:32:21.647  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:32:21.648  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:32:21.648  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8c9dd8 not in the list
08-16 19:32:21.648  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.648  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.650  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:32:21.651  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:32:21.651  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:32:21.651  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d26197 removed from the list
08-16 19:32:21.651  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 19:32:21.652  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 19:32:21.652  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:32:21.652  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 19:32:21.652  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12cc416 removed from the list
08-16 19:32:21.654  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 19:32:21.654  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f19bf84 added. We now have 2 listener(s)
08-16 19:32:21.660  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 19:32:21.661  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.661  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 19:32:21.661  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:32:21.661  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a68f36d added. We now have 9 listener(s)
08-16 19:32:21.661  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 19:32:21.662  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 19:32:21.664  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:32:21.670  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:32:21.670  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:21.670  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:21.670  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:21.670  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:21.670  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:21.670  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:32:21.670  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:32:21.672  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:32:21.672  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 19:32:21.672  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 19:32:21.673  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@518033 added. We now have 3 listener(s)
,08-16 19:32:21.674  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 19:32:21.674  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.675  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 19:32:21.675  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:32:21.675  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2354ff0 added. We now have 10 listener(s)
08-16 19:32:21.675  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:32:21.675  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 19:32:21.675  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 19:32:21.675  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 19:32:21.675  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:32:21.675  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:32:21.676  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:21.679  3807  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:32:21.679  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 19:32:21.679  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:21.683  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 19:32:21.684  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 19:32:21.684  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 19:32:21.687  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 19:32:21.687  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 19:32:21.688  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 19:32:21.688  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:32:21.691  4197  4225 D BtGatt.GattService: registerClient() - UUID=581b4888-1584-4bec-b2f4-6866f891b023
,08-16 19:32:21.692  4197  4213 D BtGatt.GattService: onClientRegistered() - UUID=581b4888-1584-4bec-b2f4-6866f891b023, clientIf=5
,08-16 19:32:21.693  3807  3819 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 19:32:21.695  4197  4233 D BtGatt.GattService: start scan with filters
,08-16 19:32:21.699  4197  4216 D BtGatt.ScanManager: handling starting scan
,08-16 19:32:21.700  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 19:32:21.700  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 19:32:21.700  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 19:32:21.700  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 19:32:21.702  4197  4216 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1301bc8
08-16 19:32:21.703  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-16 19:32:21.703  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 19:32:21.703  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-16 19:32:21.705  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 19:32:21.708  3807  3859 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 19:32:21.708  4197  4213 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 19:32:21.708  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
,08-16 19:32:21.708  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 19:32:21.708  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.708  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.708  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 19:32:21.708  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 19:32:21.708  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 19:32:21.708  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 19:32:21.708  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 19:32:21.709  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-16 19:32:21.709  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 19:32:21.709  4197  4216 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 19:32:21.710  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:32:21.710  4197  4207 D BtGatt.GattService: stopScan() - queue size =1
,08-16 19:32:21.711  4197  4225 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 19:32:21.711  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:32:21.712  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 19:32:21.712  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 19:32:21.712  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 19:32:21.712  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 19:32:21.713  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 19:32:21.713  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:32:21.713  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 19:32:21.713  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:32:21.714  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 19:32:21.716  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 19:32:21.716  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:32:21.716  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:32:21.718  4197  4213 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 19:32:21.718  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.720  4197  4216 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 19:32:21.720  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:32:21.721  4197  4216 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 19:32:21.721  3807  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 19:32:21.726  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 19:32:21.726  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:32:21.727  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 19:32:21.727  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:32:21.727  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:32:21.727  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 19:32:21.727  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 19:32:21.727  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f19bf84 removed from the list
08-16 19:32:21.727  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:32:21.728  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a68f36d removed from the list
,08-16 19:32:21.728  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:32:21.728  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 19:32:21.729  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.729  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 19:32:21.731  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.732  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 19:32:21.733  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 19:32:21.734  4197  4213 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 19:32:21.734  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.736  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 19:32:21.736  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 19:32:21.736  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 19:32:21.736  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:32:21.736  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:32:21.736  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:32:21.736  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a68f36d not in the list
08-16 19:32:21.736  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.740  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 19:32:21.740  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:32:21.740  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 19:32:21.741  4197  4213 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 19:32:21.741  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.745  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:32:21.745  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:32:21.746  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.749  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 19:32:21.749  4197  4213 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 19:32:21.749  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:32:21.749  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.749  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.750  4197  4216 D BtGatt.ScanManager: stopping BLe Batch
,08-16 19:32:21.751  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:32:21.751  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:32:21.751  3807  3859 D BluetoothLeScanner: could not find callback wrapper
,08-16 19:32:21.752  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:32:21.752  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:32:21.752  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 19:32:21.752  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:32:21.752  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2354ff0 removed from the list
08-16 19:32:21.752  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:32:21.752  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:32:21.752  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:32:21.753  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 19:32:21.753  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@518033 removed from the list
,08-16 19:32:21.754  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 19:32:21.754  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cf2d08 added. We now have 2 listener(s)
,08-16 19:32:21.755  4197  4213 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 19:32:21.755  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.756  4197  4216 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 19:32:21.757  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 19:32:21.757  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.757  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 19:32:21.757  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:32:21.757  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1ecca1 added. We now have 9 listener(s)
08-16 19:32:21.757  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:32:21.758  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 19:32:21.761  4197  4213 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 19:32:21.761  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.762  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:32:21.767  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:32:21.767  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:21.767  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:21.767  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:21.767  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:21.767  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:21.767  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:32:21.767  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:32:21.769  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:32:21.769  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 19:32:21.769  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 19:32:21.769  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@378de87 added. We now have 3 listener(s)
,08-16 19:32:21.771  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:21.772  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 19:32:21.773  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.773  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 19:32:21.773  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:32:21.773  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae11b4 added. We now have 10 listener(s)
,08-16 19:32:21.773  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:21.773  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 19:32:21.773  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 19:32:21.774  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 19:32:21.774  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 19:32:21.775  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 19:32:21.775  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:32:21.775  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 19:32:21.778  3807  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 19:32:21.778  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 19:32:21.782  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 19:32:21.783  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 19:32:21.783  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 19:32:21.786  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 19:32:21.786  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 19:32:21.787  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 19:32:21.787  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:32:21.790  4197  4208 D BtGatt.GattService: registerClient() - UUID=a1fcce50-1478-4493-992d-9247690582fc
,08-16 19:32:21.790  4197  4213 D BtGatt.GattService: onClientRegistered() - UUID=a1fcce50-1478-4493-992d-9247690582fc, clientIf=5
08-16 19:32:21.790  3807  3821 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 19:32:21.791  4197  4207 D BtGatt.GattService: start scan with filters
,08-16 19:32:21.794  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 19:32:21.794  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 19:32:21.794  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 19:32:21.794  4197  4216 D BtGatt.ScanManager: handling starting scan
08-16 19:32:21.794  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 19:32:21.797  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 19:32:21.797  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 19:32:21.797  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 19:32:21.799  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 19:32:21.801  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 19:32:21.801  3807  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 19:32:21.802  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:32:21.802  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:32:21.802  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:32:21.802  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:32:21.802  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:32:21.802  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 19:32:21.802  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 19:32:21.802  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cf2d08 removed from the list
08-16 19:32:21.802  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:32:21.802  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1ecca1 removed from the list
08-16 19:32:21.802  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:32:21.802  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 19:32:21.803  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.804  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 19:32:21.804  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.804  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:32:21.804  4197  4213 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 19:32:21.804  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.804  4197  4216 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 19:32:21.805  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 19:32:21.805  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:32:21.805  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:32:21.805  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1ecca1 not in the list
,08-16 19:32:21.805  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 19:32:21.805  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 19:32:21.805  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 19:32:21.805  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 19:32:21.805  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 19:32:21.806  3807  3859 D BluetoothAdapter: STATE_ON,
08-16 19:32:21.806  4197  4233 D BtGatt.GattService: stopScan() - queue size =1
,08-16 19:32:21.807  4197  4208 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 19:32:21.808  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:32:21.808  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 19:32:21.808  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 19:32:21.808  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 19:32:21.808  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 19:32:21.809  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 19:32:21.809  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 19:32:21.810  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 19:32:21.810  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-16 19:32:21.810  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.811  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 19:32:21.811  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:32:21.811  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:32:21.812  4197  4213 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 19:32:21.812  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.812  4197  4216 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 19:32:21.813  4197  4216 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 19:32:21.815  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:32:21.815  3807  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 19:32:21.821  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 19:32:21.821  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 19:32:21.822  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 19:32:21.822  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 19:32:21.822  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:32:21.824  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 19:32:21.824  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:32:21.825  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 19:32:21.827  4197  4213 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 19:32:21.827  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.828  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 19:32:21.828  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:32:21.828  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-16 19:32:21.830  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:32:21.830  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 19:32:21.831  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:32:21.831  3807  3859 D BluetoothLeScanner: could not find callback wrapper
,08-16 19:32:21.831  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:32:21.831  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 19:32:21.831  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:32:21.831  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:32:21.831  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae11b4 removed from the list
08-16 19:32:21.831  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 19:32:21.832  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.832  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:32:21.832  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 19:32:21.832  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@378de87 removed from the list
08-16 19:32:21.833  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 19:32:21.833  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5de34c added. We now have 2 listener(s)
,08-16 19:32:21.834  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 19:32:21.834  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.835  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-16 19:32:21.835  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:32:21.835  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e031f95 added. We now have 9 listener(s)
08-16 19:32:21.835  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-16 19:32:21.835  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 19:32:21.836  4197  4213 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 19:32:21.837  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.838  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-16 19:32:21.842  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:32:21.842  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:21.842  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:21.842  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:21.842  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:21.842  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:21.842  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:32:21.842  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:32:21.844  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:32:21.844  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 19:32:21.844  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 19:32:21.845  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6dac9b added. We now have 3 listener(s)
08-16 19:32:21.847  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 19:32:21.847  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.847  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 19:32:21.847  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:32:21.847  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:21.847  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62be838 added. We now have 10 listener(s)
,08-16 19:32:21.847  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 19:32:21.847  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 19:32:21.847  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 19:32:21.847  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 19:32:21.848  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:32:21.848  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:32:21.848  4197  4213 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 19:32:21.849  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.849  4197  4216 D BtGatt.ScanManager: stopping BLe Batch
08-16 19:32:21.850  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:21.852  3807  3859 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:32:21.852  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 19:32:21.856  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 19:32:21.857  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 19:32:21.857  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 19:32:21.857  4197  4213 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 19:32:21.858  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.858  4197  4216 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 19:32:21.860  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 19:32:21.860  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 19:32:21.860  3807  3859 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 19:32:21.861  3807  3859 D BluetoothAdapter: STATE_ON
,08-16 19:32:21.863  4197  4208 D BtGatt.GattService: registerClient() - UUID=b2b567b3-ec2f-44f2-8e36-9c294fb2de5a
08-16 19:32:21.863  4197  4213 D BtGatt.GattService: onClientRegistered() - UUID=b2b567b3-ec2f-44f2-8e36-9c294fb2de5a, clientIf=5
,08-16 19:32:21.863  3807  3969 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 19:32:21.864  4197  4207 D BtGatt.GattService: start scan with filters
08-16 19:32:21.865  4197  4213 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 19:32:21.866  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.867  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 19:32:21.867  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 19:32:21.867  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 19:32:21.867  4197  4216 D BtGatt.ScanManager: handling starting scan
08-16 19:32:21.867  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 19:32:21.870  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 19:32:21.870  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 19:32:21.870  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 19:32:21.872  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 19:32:21.875  4197  4213 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 19:32:21.876  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.876  4197  4216 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 19:32:21.876  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:32:21.876  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 19:32:21.876  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:32:21.877  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:32:21.877  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.877  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-16 19:32:21.877  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 19:32:21.877  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5de34c removed from the list
08-16 19:32:21.877  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 19:32:21.877  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e031f95 removed from the list
08-16 19:32:21.877  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:32:21.877  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:32:21.878  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.878  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 19:32:21.878  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.878  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:32:21.879  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:32:21.879  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:32:21.879  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:32:21.879  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e031f95 not in the list
08-16 19:32:21.879  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 19:32:21.880  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 19:32:21.880  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 19:32:21.880  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 19:32:21.880  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 19:32:21.881  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:32:21.881  4197  4207 D BtGatt.GattService: stopScan() - queue size =1
08-16 19:32:21.882  4197  4225 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 19:32:21.882  4197  4213 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 19:32:21.882  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 19:32:21.882  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:32:21.882  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 19:32:21.883  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 19:32:21.883  4197  4216 D BtGatt.ScanManager: Starting BLE batch scan
08-16 19:32:21.883  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 19:32:21.883  4197  4216 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 19:32:21.883  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 19:32:21.885  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 19:32:21.885  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:32:21.885  3807  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 19:32:21.885  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:32:21.886  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.887  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 19:32:21.887  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:32:21.887  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 19:32:21.889  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 19:32:21.889  3807  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 19:32:21.893  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 19:32:21.893  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 19:32:21.894  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 19:32:21.894  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:32:21.894  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.896  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 19:32:21.896  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 19:32:21.896  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 19:32:21.897  4197  4213 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 19:32:21.897  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.898  3807  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 19:32:21.898  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 19:32:21.898  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.900  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:32:21.900  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 19:32:21.901  3807  3859 D BluetoothAdapter: STATE_ON
08-16 19:32:21.901  3807  3859 D BluetoothLeScanner: could not find callback wrapper
08-16 19:32:21.901  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 19:32:21.901  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 19:32:21.901  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 19:32:21.901  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:32:21.901  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62be838 removed from the list
08-16 19:32:21.901  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:32:21.901  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.902  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.902  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 19:32:21.902  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6dac9b removed from the list
08-16 19:32:21.902  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 19:32:21.902  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8678650 added. We now have 2 listener(s)
,08-16 19:32:21.904  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 19:32:21.904  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.904  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 19:32:21.904  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 19:32:21.904  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0c049 added. We now have 9 listener(s)
08-16 19:32:21.904  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:32:21.905  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 19:32:21.905  4197  4213 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 19:32:21.905  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.907  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:32:21.911  3807  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:32:21.911  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:32:21.911  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:32:21.911  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:32:21.911  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:32:21.911  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:32:21.911  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:32:21.911  3807  3859 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 19:32:21.913  4197  4213 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 19:32:21.913  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.914  4197  4216 D BtGatt.ScanManager: stopping BLe Batch
,08-16 19:32:21.914  3807  3859 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 19:32:21.914  3807  3859 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 19:32:21.914  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 19:32:21.914  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e8de6f added. We now have 3 listener(s)
08-16 19:32:21.917  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 19:32:21.917  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 19:32:21.917  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 19:32:21.917  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 19:32:21.918  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 19:32:21.918  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c6b77c added. We now have 10 listener(s)
08-16 19:32:21.918  3807  3859 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 19:32:21.918  3807  3859 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 19:32:21.918  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:32:21.918  3807  3859 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 19:32:21.919  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:32:21.919  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 19:32:21.919  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 19:32:21.919  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 19:32:21.919  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8678650 removed from the list
08-16 19:32:21.919  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:32:21.919  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0c049 removed from the list
08-16 19:32:21.919  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:32:21.920  3807  3859 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:32:21.920  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.921  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.921  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:32:21.921  4197  4213 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 19:32:21.921  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.921  4197  4216 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 19:32:21.922  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:32:21.922  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 19:32:21.922  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:32:21.922  3807  3859 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0c049 not in the list
08-16 19:32:21.922  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.922  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.923  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 19:32:21.923  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 19:32:21.923  3807  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 19:32:21.923  3807  3859 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c6b77c removed from the list
08-16 19:32:21.923  3807  3859 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:32:21.923  3807  3859 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:32:21.923  3807  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 19:32:21.924  3807  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 19:32:21.924  3807  3859 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e8de6f removed from the list
08-16 19:32:21.924  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-16 19:32:21.925  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 19:32:21.925  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 19:32:21.925  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 19:32:21.925  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-16 19:32:21.925  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 19:32:21.929  4197  4213 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 19:32:21.929  4197  4213 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 19:32:21.932  3807  4273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
,08-16 19:32:21.933  3807  4273 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-16 19:32:21.933  3807  4273 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 19:32:21.935  3807  4274 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: My test thread name)
,08-16 19:32:21.935  3807  4274 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: My test thread name)
08-16 19:32:21.935  3807  4274 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 19:32:21.936  3807  3859 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 19:32:21.937  3807  3859 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 19:32:21.937  3807  3859 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 19:32:21.937  3807  3859 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 19:32:21.937  3807  3859 D com.test.thalitest.ThaliTestRunner: Total duration: 22929 ms
,08-16 19:32:21.939  3807  3859 I jxcore-log: Total number of executed tests:  80
08-16 19:32:21.939  3807  3859 I jxcore-log: 
,08-16 19:32:21.939  3807  3859 I jxcore-log: Number of passed tests:  80
08-16 19:32:21.939  3807  3859 I jxcore-log: 
08-16 19:32:21.939  3807  3859 I jxcore-log: Number of failed tests:  0
08-16 19:32:21.939  3807  3859 I jxcore-log: 
08-16 19:32:21.939  3807  3859 I jxcore-log: Number of ignored tests:  0
08-16 19:32:21.939  3807  3859 I jxcore-log: 
,08-16 19:32:21.939  3807  3859 I jxcore-log: Total duration:  22929
08-16 19:32:21.939  3807  3859 I jxcore-log: 
,08-16 19:32:21.942  3807  3859 I jxcore-log: Unit Test app is loaded
08-16 19:32:21.942  3807  3859 I jxcore-log: 
,08-16 19:32:21.950  3807  3807 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 19:32:21.953  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.953  3807  3859 I jxcore-log: 
,08-16 19:32:21.957  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.957  3807  3859 I jxcore-log: 
,08-16 19:32:21.958  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.958  3807  3859 I jxcore-log: 
,08-16 19:32:21.960  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.960  3807  3859 I jxcore-log: 
,08-16 19:32:21.961  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.961  3807  3859 I jxcore-log: 
08-16 19:32:21.962  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.962  3807  3859 I jxcore-log: 
08-16 19:32:21.964  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 19:32:21.964  3807  3859 I jxcore-log: 
,08-16 19:32:21.966  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.966  3807  3859 I jxcore-log: 
,08-16 19:32:21.968  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 19:32:21.968  3807  3859 I jxcore-log: 
,08-16 19:32:21.969  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.969  3807  3859 I jxcore-log: 
,08-16 19:32:21.971  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 19:32:21.971  3807  3859 I jxcore-log: 
,08-16 19:32:21.972  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 19:32:21.972  3807  3859 I jxcore-log: 
08-16 19:32:21.973  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 19:32:21.973  3807  3859 I jxcore-log: 
,08-16 19:32:21.974  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.974  3807  3859 I jxcore-log: 
,08-16 19:32:21.976  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.976  3807  3859 I jxcore-log: 
,08-16 19:32:21.977  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.977  3807  3859 I jxcore-log: 
,08-16 19:32:21.977  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.977  3807  3859 I jxcore-log: 
,08-16 19:32:21.979  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.979  3807  3859 I jxcore-log: 
08-16 19:32:21.979  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.979  3807  3859 I jxcore-log: 
08-16 19:32:21.980  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.980  3807  3859 I jxcore-log: 
08-16 19:32:21.981  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.981  3807  3859 I jxcore-log: 
08-16 19:32:21.981  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.981  3807  3859 I jxcore-log: 
08-16 19:32:21.982  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 19:32:21.982  3807  3859 I jxcore-log: 
08-16 19:32:21.983  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 19:32:21.983  3807  3859 I jxcore-log: 
08-16 19:32:21.984  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.984  3807  3859 I jxcore-log: 
08-16 19:32:21.985  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.985  3807  3859 I jxcore-log: 
,08-16 19:32:21.987  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.987  3807  3859 I jxcore-log: 
08-16 19:32:21.987  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.987  3807  3859 I jxcore-log: 
08-16 19:32:21.988  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.988  3807  3859 I jxcore-log: 
,08-16 19:32:21.989  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.989  3807  3859 I jxcore-log: 
,08-16 19:32:21.990  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 19:32:21.990  3807  3859 I jxcore-log: 
,08-16 19:32:21.995  3807  3859 I jxcore-log: My device name is: motorola-Nexus 6
08-16 19:32:21.995  3807  3859 I jxcore-log: 
,08-16 19:32:22.250  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 19:32:22.331  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 19:32:22.401  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 19:32:23.649   873  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-16 19:32:24.233  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-16 19:32:24.233  3807  3859 I jxcore-log: 
,08-16 19:32:24.888  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-16 19:32:24.888  3807  3859 I jxcore-log: 
,08-16 19:32:24.937  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-16 19:32:24.937  3807  3859 I jxcore-log: 
,08-16 19:32:26.298  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-16 19:32:26.298  3807  3859 I jxcore-log: 
,08-16 19:32:26.524  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-16 19:32:26.524  3807  3859 I jxcore-log: 
,08-16 19:32:26.529  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-16 19:32:26.529  3807  3859 I jxcore-log: 
,08-16 19:32:26.546  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-16 19:32:26.546  3807  3859 I jxcore-log: 
,08-16 19:32:26.551  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-16 19:32:26.551  3807  3859 I jxcore-log: 
,08-16 19:32:27.219  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-16 19:32:27.219  3807  3859 I jxcore-log: 
,08-16 19:32:27.232  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-16 19:32:27.232  3807  3859 I jxcore-log: 
,08-16 19:32:27.238  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-16 19:32:27.238  3807  3859 I jxcore-log: 
,08-16 19:32:27.245  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-16 19:32:27.245  3807  3859 I jxcore-log: 
,08-16 19:32:27.292  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-16 19:32:27.292  3807  3859 I jxcore-log: 
,08-16 19:32:27.346  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-16 19:32:27.346  3807  3859 I jxcore-log: 
,08-16 19:32:27.354  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-16 19:32:27.354  3807  3859 I jxcore-log: 
,08-16 19:32:27.517  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-16 19:32:27.517  3807  3859 I jxcore-log: 
,08-16 19:32:27.544  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-16 19:32:27.544  3807  3859 I jxcore-log: 
,08-16 19:32:27.549  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-16 19:32:27.549  3807  3859 I jxcore-log: 
,08-16 19:32:27.555  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-16 19:32:27.555  3807  3859 I jxcore-log: 
,08-16 19:32:27.573  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-16 19:32:27.573  3807  3859 I jxcore-log: 
,08-16 19:32:27.654  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-16 19:32:27.654  3807  3859 I jxcore-log: 
,08-16 19:32:27.666  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-16 19:32:27.666  3807  3859 I jxcore-log: 
,08-16 19:32:27.694  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-16 19:32:27.694  3807  3859 I jxcore-log: 
,08-16 19:32:27.706  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-16 19:32:27.706  3807  3859 I jxcore-log: 
,08-16 19:32:27.725  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-16 19:32:27.725  3807  3859 I jxcore-log: 
,08-16 19:32:27.761  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-16 19:32:27.761  3807  3859 I jxcore-log: 
,08-16 19:32:27.767  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-16 19:32:27.767  3807  3859 I jxcore-log: 
,08-16 19:32:27.992  3807  3859 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-16 19:32:27.992  3807  3859 I jxcore-log: 
,08-16 19:32:28.002  3807  3859 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-16 19:32:28.003  3807  3859 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-16 19:32:28.003  3807  3859 I jxcore-log: 
,08-16 19:32:28.048  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 19:32:28.048  3807  3859 I jxcore-log: 
,08-16 19:32:28.049  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 19:32:28.049  3807  3859 I jxcore-log: 
,08-16 19:32:28.049  3807  3859 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 19:32:28.049  3807  3859 I jxcore-log: 
08-16 19:32:28.050  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 19:32:28.050  3807  3859 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,08-16 19:32:28.050  3807  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 19:32:28.050  3807  3859 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-16 19:32:28.513   873  1310 D ConnectivityService: handlePromptUnvalidated 102
,08-16 19:32:40.217  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:40.307  1516  4276 I VacuumService: Vacuum at: now=1471368760307 tag=VacuumService
,08-16 19:32:40.374  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:40.383  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:40.388  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:40.433  1516  2086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 19:32:40.433  1516  2086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 19:32:40.433  1516  2086 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:32:40.433  1516  2086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:40.624  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 19:32:40.624  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 19:32:40.625  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-16 19:32:40.722  1516  4277 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-16 19:32:40.725  1516  4277 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 19:32:40.762  1516  4277 W Uploader:  no longer exists, so no auth token.
,08-16 19:32:41.712  1516  4277 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-16 19:32:41.712  1516  4277 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-16 19:32:41.712  1516  4277 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 19:32:41.713  1516  4277 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:41.734  1516  4277 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 19:32:41.734  1516  4277 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 19:32:41.734  1516  4277 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 19:32:42.091  1516  4277 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 19:32:42.091  1516  4277 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 19:32:42.092  1516  4277 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 19:32:42.092  1516  4277 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:42.111  1516  4277 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 19:32:42.111  1516  4277 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 19:32:42.111  1516  4277 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 19:32:42.614  1516  4277 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 19:32:42.614  1516  4277 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 19:32:42.614  1516  4277 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 19:32:42.614  1516  4277 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:42.634  1516  4277 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 19:32:42.634  1516  4277 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 19:32:42.634  1516  4277 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 19:32:50.848  3010  4292 V KeepSync: Connecting to GoogleApiClient
,08-16 19:32:50.849   873  1670 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 19:32:50.871  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:50.879  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:32:50.908  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:32:50.908  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 19:32:50.908  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:32:50.909  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:50.918  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 19:32:50.918  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-16 19:32:50.919  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:32:50.919  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:50.926  3553  4294 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 19:32:50.926  3553  4294 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at blb.a(PG:3937)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at czp.a(PG:18188)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:32:50.926  3553  4294 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	... 12 more
08-16 19:32:50.926  3553  4294 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at fal.a(PG:38)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:32:50.926  3553  4294 E HttpOperation: 	... 14 more
,08-16 19:32:50.944  1739  4295 V BaseAuthAsyncOperation: access token request failed
08-16 19:32:50.945  3010  4292 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 19:32:50.963  1516  2882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:32:50.963  1516  2882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 19:32:50.963  1516  2882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:32:50.963  1516  2882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:50.978  3553  4294 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 19:32:50.978  3553  4294 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at hec.a(PG:42)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at hee.a(PG:102)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at czr.a(PG:65)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at kka.a(PG:108)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at czp.a(PG:19176)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:32:50.978  3553  4294 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	... 15 more
08-16 19:32:50.978  3553  4294 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at fal.a(PG:38)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:32:50.978  3553  4294 E HttpOperation: 	... 17 more
08-16 19:32:50.978  3553  4294 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 19:32:50.978  3553  4294 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at hec.a(PG:42)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at hee.a(PG:102)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at czr.a(PG:65)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at kka.a(PG:108)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	... 15 more
08-16 19:32:50.978  3553  4294 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at fal.a(PG:38)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 19:32:50.978  3553  4294 E ExperimentLoader: 	... 17 more
,08-16 19:32:51.043  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 19:32:51.043  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 19:32:51.043  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:32:51.043  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:32:51.059  3010  4292 E KeepSync: IOException
08-16 19:32:51.059  3010  4292 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 19:32:51.059  3010  4292 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 19:32:51.059  3010  4292 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 19:32:51.059  3010  4292 E KeepSync: 	... 10 more
,08-16 19:32:51.059  3010  4292 W KeepSync: Sync result 2
,08-16 19:32:51.071   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 163312, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:32:51.174   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 178204, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:33:00.827  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:33:00.835  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:33:00.839  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:33:00.873  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 19:33:00.873  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 19:33:00.873  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:33:00.873  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:33:00.905  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 19:33:00.905  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 19:33:00.906  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-16 19:33:08.883  1861  1961 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-16 19:33:08.883  1861  1961 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 19:33:08.922  1516  1516 I ConfigService: onCreate
,08-16 19:33:14.002  1516  1516 I ConfigService: onDestroy
,08-16 19:33:21.341  3010  4299 V KeepSync: Connecting to GoogleApiClient
08-16 19:33:21.341   873  1670 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 19:33:21.388  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:33:21.390  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:33:21.421  1516  2251 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 19:33:21.421  1516  2251 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-16 19:33:21.421  1516  2251 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:33:21.421  1516  2251 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:33:21.442  1739  4300 V BaseAuthAsyncOperation: access token request failed
,08-16 19:33:21.443  3010  4299 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 19:33:21.501  1516  3074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 19:33:21.501  1516  3074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 19:33:21.501  1516  3074 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:33:21.501  1516  3074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:33:21.518  3010  4299 E KeepSync: IOException
08-16 19:33:21.518  3010  4299 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 19:33:21.518  3010  4299 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 19:33:21.518  3010  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 19:33:21.518  3010  4299 E KeepSync: 	... 10 more
,08-16 19:33:21.518  3010  4299 W KeepSync: Sync result 2
,08-16 19:33:21.535   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 222536, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:33:41.194   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=242503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:33:49.273   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=250583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 19:33:51.847  3613  4303 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 19:33:51.959  3613  4305 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 19:33:51.977  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:33:51.985  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:33:52.094  1516  3074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:33:52.094  1516  3074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 19:33:52.094  1516  3074 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:33:52.095  1516  3074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 19:33:52.095  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 19:33:52.095  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 19:33:52.095  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:33:52.095  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:33:52.137  3553  4304 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 19:33:52.137  3553  4304 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at blb.a(PG:3937)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at czp.a(PG:18188)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:33:52.137  3553  4304 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	... 12 more
08-16 19:33:52.137  3553  4304 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at fal.a(PG:38)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:33:52.137  3553  4304 E HttpOperation: 	... 14 more
,08-16 19:33:52.221  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:33:52.221  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 19:33:52.221  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 19:33:52.221  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:33:52.232  1516  2086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 19:33:52.232  1516  2086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 19:33:52.232  1516  2086 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:33:52.232  1516  2086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:33:52.260  3553  4304 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 19:33:52.260  3553  4304 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at hec.a(PG:42)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at hee.a(PG:102)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at czr.a(PG:65)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at kka.a(PG:108)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at czp.a(PG:19176)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:33:52.260  3553  4304 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	... 15 more
08-16 19:33:52.260  3553  4304 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at fal.a(PG:38)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:33:52.260  3553  4304 E HttpOperation: 	... 17 more
,08-16 19:33:52.260  3553  4304 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 19:33:52.260  3553  4304 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at hec.a(PG:42)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at hee.a(PG:102)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at czr.a(PG:65)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at kka.a(PG:108)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	... 15 more
08-16 19:33:52.260  3553  4304 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at fal.a(PG:38)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 19:33:52.260  3553  4304 E ExperimentLoader: 	... 17 more
,08-16 19:33:52.264  3613  4305 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:33:52.265  3613  4303 E BooksSync: Soft error
08-16 19:33:52.265  3613  4303 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:33:52.265  3613  4303 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 19:33:52.265  3613  4303 E BooksSync: Sync error
08-16 19:33:52.265  3613  4303 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:33:52.265  3613  4303 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 19:33:52.265  3613  4303 I BooksSync: Finished books sync
08-16 19:33:52.275   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 249511, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:33:52.387   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 224450, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:34:22.647  3010  4308 V KeepSync: Connecting to GoogleApiClient
,08-16 19:34:22.648   873  1940 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 19:34:22.711  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:34:22.713  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:34:22.757  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-16 19:34:22.757  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 19:34:22.757  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:34:22.758  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:34:22.787  1739  4309 V BaseAuthAsyncOperation: access token request failed
,08-16 19:34:22.788  3010  4308 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 19:34:22.872  1516  2882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 19:34:22.873  1516  2882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 19:34:22.873  1516  2882 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 19:34:22.873  1516  2882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:34:22.910  3010  4308 E KeepSync: IOException
08-16 19:34:22.910  3010  4308 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 19:34:22.910  3010  4308 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 19:34:22.910  3010  4308 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 19:34:22.910  3010  4308 E KeepSync: 	... 10 more
,08-16 19:34:22.910  3010  4308 W KeepSync: Sync result 2
,08-16 19:34:22.923   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 283154, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:34:23.030  3613  4310 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 19:34:23.057  3613  4311 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 19:34:23.112  1516  3074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 19:34:23.113  1516  3074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 19:34:23.113  1516  3074 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 19:34:23.114  1516  3074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:34:23.205  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 19:34:23.205  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 19:34:23.205  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:34:23.206  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:34:23.240  3613  4311 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 19:34:23.242  3613  4310 E BooksSync: Soft error
08-16 19:34:23.242  3613  4310 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:34:23.242  3613  4310 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 19:34:23.242  3613  4310 E BooksSync: Sync error
08-16 19:34:23.242  3613  4310 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:34:23.242  3613  4310 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 19:34:23.243  3613  4310 I BooksSync: Finished books sync
,08-16 19:34:23.257   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 283916, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:34:26.740   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=288050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:34:34.740   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=296050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 19:34:56.611  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:34:56.613  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:34:56.637  1516  2251 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:34:56.637  1516  2251 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 19:34:56.637  1516  2251 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:34:56.637  1516  2251 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:34:56.654  3553  4318 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 19:34:56.654  3553  4318 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at blb.a(PG:3937)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at czp.a(PG:18188)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:34:56.654  3553  4318 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	... 12 more
08-16 19:34:56.654  3553  4318 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at fal.a(PG:38)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:34:56.654  3553  4318 E HttpOperation: 	... 14 more
,08-16 19:34:56.697  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:34:56.697  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 19:34:56.701  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:34:56.702  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:34:56.717  3553  4318 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 19:34:56.717  3553  4318 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at hec.a(PG:42)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at hee.a(PG:102)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at czr.a(PG:65)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at kka.a(PG:108)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at czp.a(PG:19176)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:34:56.717  3553  4318 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	... 15 more
08-16 19:34:56.717  3553  4318 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at fal.a(PG:38)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:34:56.717  3553  4318 E HttpOperation: 	... 17 more
,08-16 19:34:56.717  3553  4318 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 19:34:56.717  3553  4318 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at hec.a(PG:42)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at hee.a(PG:102)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at czr.a(PG:65)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at kka.a(PG:108)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	... 15 more
08-16 19:34:56.717  3553  4318 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at fal.a(PG:38)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 19:34:56.717  3553  4318 E ExperimentLoader: 	... 17 more
,08-16 19:34:56.867   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 317629, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:35:12.180   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=333490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:35:18.167   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=339477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:35:21.749  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:35:21.757  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:35:21.759  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:35:21.799  1516  2882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-16 19:35:21.799  1516  2882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-16 19:35:21.799  1516  2882 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 19:35:21.800  1516  2882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:35:21.820  1516  2882 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 19:35:21.820  1516  2882 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 19:35:21.820  1516  2882 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 19:35:21.820  1516  2882 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-16 19:35:21.820  1516  2882 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-16 19:35:21.820  1516  2882 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-16 19:35:21.820  1516  2882 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 19:35:21.823  3515  3545 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 19:35:21.823  3515  3545 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-16 19:35:21.823  3515  3545 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-16 19:35:21.823  3515  3545 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-16 19:35:21.823  3515  3545 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-16 19:35:21.823  3515  3545 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-16 19:35:21.823  3515  3545 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 19:35:26.959  3613  4333 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 19:35:26.976  3613  4334 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 19:35:26.988  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:35:26.991  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:35:27.012  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 19:35:27.012  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 19:35:27.012  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:35:27.013  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:35:27.032  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:35:27.033  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:35:27.056  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 19:35:27.056  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 19:35:27.056  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:35:27.056  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:35:27.069  3613  4334 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 19:35:27.070  3613  4333 E BooksSync: Soft error
08-16 19:35:27.070  3613  4333 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:35:27.070  3613  4333 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 19:35:27.070  3613  4333 E BooksSync: Sync error
08-16 19:35:27.070  3613  4333 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:35:27.070  3613  4333 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 19:35:27.070  3613  4333 I BooksSync: Finished books sync
,08-16 19:35:27.085   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 345228, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:36:23.741  3010  4342 V KeepSync: Connecting to GoogleApiClient
,08-16 19:36:23.741   873  1670 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 19:36:23.815  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:36:23.817  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:36:23.852  1516  2086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 19:36:23.852  1516  2086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 19:36:23.852  1516  2086 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:36:23.852  1516  2086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:36:23.875  1739  4343 V BaseAuthAsyncOperation: access token request failed
,08-16 19:36:23.876  3010  4342 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 19:36:23.929  1516  2882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-16 19:36:23.929  1516  2882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-16 19:36:23.929  1516  2882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:36:23.929  1516  2882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:36:23.949  3010  4342 E KeepSync: IOException
08-16 19:36:23.949  3010  4342 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 19:36:23.949  3010  4342 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 19:36:23.949  3010  4342 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 19:36:23.949  3010  4342 E KeepSync: 	... 10 more
,08-16 19:36:23.950  3010  4342 W KeepSync: Sync result 2
,08-16 19:36:23.962   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 404849, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:37:05.044  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:37:05.045  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:37:05.074  1516  3074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:37:05.074  1516  3074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 19:37:05.074  1516  3074 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:37:05.074  1516  3074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:37:05.089  3553  4347 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 19:37:05.089  3553  4347 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at blb.a(PG:3937)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at czp.a(PG:18188)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:37:05.089  3553  4347 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	... 12 more
08-16 19:37:05.089  3553  4347 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at fal.a(PG:38)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:37:05.089  3553  4347 E HttpOperation: 	... 14 more
,08-16 19:37:05.147  1516  2882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 19:37:05.147  1516  2882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 19:37:05.147  1516  2882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:37:05.147  1516  2882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:37:05.169  3553  4347 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 19:37:05.169  3553  4347 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at jdm.a(PG:82)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at jcs.o(PG:406)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at jcn.a(PG:1379)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at jcs.i(PG:143)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at hec.a(PG:42)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at hee.a(PG:102)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at czr.a(PG:65)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at kka.a(PG:108)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at czp.a(PG:19176)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at czp.a(PG:9081)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at czq.run(PG:1686)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:37:05.169  3553  4347 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at jdj.a(PG:4091)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at jdj.a(PG:1125)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at jdm.a(PG:77)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	... 15 more
08-16 19:37:05.169  3553  4347 E HttpOperation: Caused by: faj: BadAuthentication
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at fal.a(PG:38)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	at jdj.a(PG:4089)
08-16 19:37:05.169  3553  4347 E HttpOperation: 	... 17 more
,08-16 19:37:05.170  3553  4347 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 19:37:05.170  3553  4347 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at hec.a(PG:42)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at hee.a(PG:102)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at czr.a(PG:65)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at kka.a(PG:108)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	... 15 more
08-16 19:37:05.170  3553  4347 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at fal.a(PG:38)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 19:37:05.170  3553  4347 E ExperimentLoader: 	... 17 more
,08-16 19:37:05.303   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 446038, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:37:35.397  3613  4351 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 19:37:35.447  3613  4352 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 19:37:35.486  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:37:35.493  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:37:35.532  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 19:37:35.532  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 19:37:35.532  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:37:35.532  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:37:35.580  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:37:35.581  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 19:37:35.598  1516  2086 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 19:37:35.598  1516  2086 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 19:37:35.599  1516  2086 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 19:37:35.599  1516  2086 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 19:37:35.618  3613  4352 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 19:37:35.619  3613  4351 E BooksSync: Soft error
08-16 19:37:35.619  3613  4351 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:37:35.619  3613  4351 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 19:37:35.619  3613  4351 E BooksSync: Sync error
08-16 19:37:35.619  3613  4351 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 19:37:35.619  3613  4351 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 19:37:35.619  3613  4351 I BooksSync: Finished books sync
,08-16 19:37:35.633   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 469716, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 19:44:19.327   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=880637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:44:29.874   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=891184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:44:44.394   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=905704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:44:54.927   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=916237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:45:09.460   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=930770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:45:19.993   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=941303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:45:34.527   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=955837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:45:45.047   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=966357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:45:59.593   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=980903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:46:10.100   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=991410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:46:24.607   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1005917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:46:35.167   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1016477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:46:49.674   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1030984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:47:00.233   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1041543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:47:14.740   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1056050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:47:25.300   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1066610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:47:40.607   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1081917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:47:50.353   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1091664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:48:04.873   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1106183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:48:15.407   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1116717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:48:29.940   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1131250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:48:40.500   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1141810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:48:55.060   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1156371, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:49:05.580   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1166890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:49:20.627   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1181937, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:49:30.647   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1191957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:49:45.620   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1206930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:49:55.700   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1217010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:49:57.617   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-16 19:50:10.687   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1231997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:50:20.767   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1242077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:50:35.700   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1257010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:50:45.834   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1267144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:51:00.767   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1282077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:51:10.886   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1292197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:51:25.833   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1307143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:51:35.954   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1317264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:51:50.900   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1332211, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:52:01.007   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1342317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:52:15.966   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1357276, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:52:26.060   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1367370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:52:41.034   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1382344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:52:51.140   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1392450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:53:06.100   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1407410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:53:16.220   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1417530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:53:31.167   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1432477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:53:41.274   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1442584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:53:56.233   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1457543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:54:06.327   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1467637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:54:21.300   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1482610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:54:31.394   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1492704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:54:40.073   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1501384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 19:54:56.447   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1517757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 19:55:05.140   873  4250 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1526450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),08-16 19:55:11.276  4402  4402 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 19:55:11.281  4402  4402 D AndroidRuntime: CheckJNI is OFF
08-16 19:55:11.317  4402  4402 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 19:55:11.357  4402  4402 I Radio-JNI: register_android_hardware_Radio DONE
08-16 19:55:11.377  4402  4402 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-16 19:55:11.386   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-16 19:55:11.387   873   886 I ActivityManager: Killing 3807:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-16 19:55:11.471   873  1309 D WifiService: Client connection lost with reason: 4
08-16 19:55:11.478   873   884 I WindowState: WIN DEATH: Window{275f35a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 19:55:11.487   873  1939 D GraphicsStats: Buffer count: 2
08-16 19:55:11.508   873   896 W PackageSettings: Skipping PackageSetting{660ecf5 com.example.hello/10273} due to missing metadata
08-16 19:55:11.534   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-16 19:55:11.535   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-16 19:55:11.535   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-16 19:55:11.535   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 19:55:11.535   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:55:11.535   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:55:11.535   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 19:55:11.535   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 19:55:11.537   873   886 I ActivityManager:   Force finishing activity ActivityRecord{3176733 u0 com.test.thalitest/.MainActivity t2}
08-16 19:55:11.537   873   896 I art     : Starting a blocking GC Explicit
08-16 19:55:11.549   873  1372 W ActivityManager: Spurious death for ProcessRecord{8f1504 0:com.test.thalitest/u0a0}, curProc for 3807: null
08-16 19:55:11.580   873   896 I art     : Explicit concurrent mark sweep GC freed 37597(2MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 28MB/43MB, paused 774us total 40.999ms
08-16 19:55:11.599   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-16 19:55:11.604  4402  4402 I art     : System.exit called, status: 0
08-16 19:55:11.604  4402  4402 I AndroidRuntime: VM exiting with result code 0.
08-16 19:55:11.618   873   896 I ActivityManager: Start proc 4415:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-16 19:55:11.619   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-16 19:55:11.638   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-16 19:55:11.643  4197  4197 D BluetoothMapAppObserver: onReceive
08-16 19:55:11.644  4197  4197 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-16 19:55:11.646  2091  2294 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 19:55:11.651   873  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 19:55:11.683  3675  3675 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-16 19:55:11.687  1861  1861 I Keyboard.Facilitator: resetDictionaries() : en_US
08-16 19:55:11.696  1926  1926 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-16 19:55:11.717   873  1983 I ActivityManager: Start proc 4431:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-16 19:55:11.728  1861  4430 I Keyboard.Facilitator.DecoderInitializer: run()
08-16 19:55:11.732  1861  4430 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-16 19:55:11.732  1861  4430 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-16 19:55:11.733  1861  4430 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-16 19:55:11.733  1861  4430 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-16 19:55:11.733  1861  4430 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-16 19:55:11.733  1861  4430 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-16 19:55:11.734  1861  4430 I Decoder : createOrResetDecoder
08-16 19:55:11.739   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 19:55:11.742   873  1671 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3807 uid 10000
08-16 19:55:11.742  1861  1861 I Keyboard.Facilitator: onFinishInput()
08-16 19:55:11.751  4431  4431 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-16 19:55:11.754  1516  1516 I ConfigService: onCreate
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 19:55:11.763  1516  4443 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 19:55:11.764  1516  4443 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:55:11.766  1516  4443 W SQLiteOpenHelper: Opened config.db in read-only mode
08-16 19:55:11.773  1941  2029 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-16 19:55:11.779   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-16 19:55:11.780   873   885 E PackageManager: Failed to write settings, restoring backup
08-16 19:55:11.780   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 19:55:11.780   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 19:55:11.780   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 19:55:11.780   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 19:55:11.780   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 19:55:11.780   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:55:11.780   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:55:11.780   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 19:55:11.786   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-16 19:55:11.786   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 19:55:11.786   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 19:55:11.786   873   886 E DropBoxManagerService: 	... 13 more
08-16 19:55:11.786   873  1670 I ActivityManager: Start proc 4447:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-16 19:55:11.787  1941  2029 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 19:55:11.787  1941  2029 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1941
08-16 19:55:11.787  1941  2029 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:55:11.787  1941  2029 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 19:55:11.789   873  1372 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 19:55:11.789   873  4457 E DropBoxManagerService: Can't write: system_app_crash
08-16 19:55:11.789   873  4457 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 19:55:11.789   873  4457 E DropBoxManagerService: 	... 5 more
08-16 19:55:11.823  1941  2029 I Process : Sending signal. PID: 1941 SIG: 9
08-16 19:55:11.825  1861  4430 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-16 19:55:11.847  4431  4431 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-16 19:55:11.868   280   280 E lowmemorykiller: Error writing /proc/1941/oom_score_adj; errno=22
08-16 19:55:11.880   873  1671 I ActivityManager: Start proc 4464:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-16 19:55:11.880   280   280 E lowmemorykiller: Error writing /proc/1941/oom_score_adj; errno=22
08-16 19:55:11.887  1861  4430 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-16 19:55:11.889  1861  4430 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 19:55:11.889  1861  4430 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-16 19:55:11.891  1861  4430 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-16 19:55:11.891  1861  4430 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-16 19:55:11.899  4431  4463 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-16 19:55:11.912  1861  4430 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 19:55:11.913  1861  4430 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-16 19:55:11.913  1861  4430 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 19:55:11.913  1861  4430 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 19:55:11.913  1861  4430 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 19:55:11.914  1861  4430 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-16 19:55:11.914  1861  4430 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 19:55:11.914  1861  4430 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-16 19:55:11.930  4464  4464 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-16 19:55:11.936   873  1298 W InputDispatcher: channel 'ed0c90e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-16 19:55:11.936   873  1298 E InputDispatcher: channel 'ed0c90e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-16 19:55:11.937   873  1966 D GraphicsStats: Buffer count: 1
08-16 19:55:11.937   873  1947 I WindowState: WIN DEATH: Window{ed0c90e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-16 19:55:11.937   873  1947 W InputDispatcher: Attempted to unregister already unregistered input channel 'ed0c90e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:55:11.947  4431  4463 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 19:55:11.948  4431  4463 E AndroidRuntime: Process: android.process.acore, PID: 4431
08-16 19:55:11.948  4431  4463 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:55:11.948  4431  4463 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:55:11.954  4431  4445 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:55:11.954  4431  4445 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 19:55:11.958   873  1966 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1941) has died
08-16 19:55:11.959   873  1966 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-16 19:55:11.961   873  1966 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-16 19:55:11.968   873  4478 E DropBoxManagerService: Can't write: system_app_crash
08-16 19:55:11.968   873  4478 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 19:55:11.968   873  4478 E DropBoxManagerService: 	... 5 more
08-16 19:55:11.979   873   886 I ActivityManager: Start proc 4481:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 19:55:11.983  4431  4463 I Process : Sending signal. PID: 4431 SIG: 9
08-16 19:55:11.988   280   280 E lowmemorykiller: Error writing /proc/4431/oom_score_adj; errno=22
08-16 19:55:11.993   280   280 E lowmemorykiller: Error writing /proc/4431/oom_score_adj; errno=22
08-16 19:55:11.995   873  1982 I ActivityManager: Killing 3728:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-16 19:55:12.002  1739  4477 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-16 19:55:12.002  1739  4477 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-16 19:55:12.054  1516  1516 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-16 19:55:12.054  1516  1516 D AndroidRuntime: Shutting down VM
08-16 19:55:12.055  1516  1516 E AndroidRuntime: FATAL EXCEPTION: main
08-16 19:55:12.055  1516  1516 E AndroidRuntime: Process: com.google.process.gapps, PID: 1516
08-16 19:55:12.055  1516  1516 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 19:55:12.055  1516  1516 E AndroidRuntime: 	... 8 more
08-16 19:55:12.061   873  1671 I ActivityManager: Process android.process.acore (pid 4431) has died
08-16 19:55:12.061   873  1671 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-16 19:55:12.068  1516  1516 I Process : Sending signal. PID: 1516 SIG: 9
08-16 19:55:12.068   873  4494 E DropBoxManagerService: Can't write: system_app_crash
08-16 19:55:12.068   873  4494 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 19:55:12.068   873  4494 E DropBoxManagerService: 	... 5 more

```
