#### Test 8288334193c2946_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-30 12:29:43.759  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 12:29:43.772  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 12:29:43.774  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 12:29:43.818  1503  3093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 12:29:43.819  1503  3093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 12:29:43.819  1503  3093 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:29:43.820  1503  3093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 12:29:43.878  3517  3517 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 12:29:43.878  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 12:29:43.903  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-30 12:29:44.405  3808  3808 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 12:29:44.410  3808  3808 D AndroidRuntime: CheckJNI is OFF
08-30 12:29:44.453  3808  3808 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 12:29:44.503  3808  3808 I Radio-JNI: register_android_hardware_Radio DONE
08-30 12:29:44.525  3808  3808 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 12:29:44.532   871  1953 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 12:29:44.561  2034  2436 W SearchService: Abort, client detached.
08-30 12:29:44.569  2034  2034 I HotwordDetector: Closing mic
08-30 12:29:44.570  2034  2349 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fdf18a4
08-30 12:29:44.570  2034  2361 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 12:29:44.572  3808  3808 D AndroidRuntime: Shutting down VM
08-30 12:29:44.601   871   881 I ActivityManager: Start proc 3819:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 12:29:44.628   376  2364 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 12:29:44.633   376  2364 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 12:29:44.637   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 12:29:44.638  2034  2360 I MicroRecognitionRnrImpl: Detection finished
08-30 12:29:44.638  2034  2354 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 12:29:44.674  3819  3819 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 12:29:44.694  3819  3819 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 12:29:44.701  3819  3819 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1448-1451)
08-30 12:29:44.701  3819  3819 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:29:44.725  3819  3819 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {55d3347}
08-30 12:29:44.726  3819  3819 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:29:44.726  3819  3819 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:29:44.732  3819  3819 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 12:29:44.733  3819  3819 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 12:29:44.747  3819  3819 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 12:29:44.757  3819  3819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:29:44.757  3819  3819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:29:44.757  3819  3819 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 12:29:44.757  3819  3819 I Adreno  : Build Date                       : 10/20/15
08-30 12:29:44.757  3819  3819 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 12:29:44.757  3819  3819 I Adreno  : Local Branch                     : M14
08-30 12:29:44.757  3819  3819 I Adreno  : Remote Branch                    : 
08-30 12:29:44.757  3819  3819 I Adreno  : Remote Branch                    : 
08-30 12:29:44.757  3819  3819 I Adreno  : Reconstruct Branch               : 
08-30 12:29:44.807   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d4a5b:true
,08-30 12:29:44.871  3819  3819 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 12:29:44.885  3819  3819 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 12:29:44.964  3819  3858 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 12:29:44.972  3819  3845 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 12:29:45.020  3819  3858 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 12:29:45.076   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +502ms
,08-30 12:29:45.085  1878  1878 I Keyboard.Facilitator: onFinishInput()
,08-30 12:29:45.159  3819  3819 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3819
,08-30 12:29:45.254  3819  3819 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:29:45.398   871  1992 I ActivityManager: Killing 3397:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 12:29:45.438  3819  3861 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1684014800
,08-30 12:29:45.440   871  1992 I ActivityManager: Killing 3204:com.google.android.gm/u0a78 (adj 15): empty #18
,08-30 12:29:45.443  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:29:45.443  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:29:45.443  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:29:45.443  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:29:45.443  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 12:29:45.443  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b45d32a added. We now have 1 listener(s)
,08-30 12:29:45.447  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 12:29:45.448  3819  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:29:45.449  3819  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:29:45.449  3819  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 12:29:45.452  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f74c91 added. We now have 1 listener(s)
08-30 12:29:45.452  3819  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:29:45.455   871  1307 D WifiService: New client listening to asynchronous messages
08-30 12:29:45.456  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:29:45.456  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 12:29:45.457  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:29:45.457  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-30 12:29:45.457  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 12:29:45.498  3819  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:29:45.498  3819  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 12:29:45.506  3819  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 12:29:45.506  3819  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:29:45.506  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:45.506  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:29:45.506  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:45.506  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:45.506  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:45.506  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:45.506  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:29:45.506  3819  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:29:45.506  3819  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:29:45.507  3819  3861 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:29:45.510  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:29:45.512  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:29:45.532  3819  3819 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 12:29:46.281  3819  3871 W jxcore-log: Initializing JXcore engine
,08-30 12:29:46.281  3819  3871 W jxcore-log: JXcore engine is ready
,08-30 12:29:46.319  3871  3871 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 12:29:46.322  3871  3871 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12691]" dev="sockfs" ino=12691 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 12:29:46.322  3871  3871 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 12:29:46.322  3871  3871 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25092]" dev="sockfs" ino=25092 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 12:29:46.354  3819  3871 W jxcore-log: Starting JXcore engine
,08-30 12:29:46.441  3819  3871 W jxcore-log: Platform android
08-30 12:29:46.441  3819  3871 W jxcore-log: 
,08-30 12:29:46.442  3819  3871 W jxcore-log: Process ARCH arm
08-30 12:29:46.442  3819  3871 W jxcore-log: 
,08-30 12:29:46.547   871  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 12:29:46.691  3819  3871 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:29:46.691  3819  3871 I jxcore-log: 
,08-30 12:29:46.692  3819  3871 W jxcore-log: JXcore engine is started
,08-30 12:29:46.701  3819  3861 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 12:29:46.705  3819  3819 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:29:52.303  3586  3878 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 12:29:52.324  3586  3879 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 12:29:52.337  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:29:52.341  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:29:52.374  1503  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 12:29:52.374  1503  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 12:29:52.374  1503  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:29:52.374  1503  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:29:52.396  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:29:52.398  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:29:52.418  1503  2311 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 12:29:52.418  1503  2311 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 12:29:52.418  1503  2311 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:29:52.418  1503  2311 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:29:52.440  3586  3879 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 12:29:52.441  3586  3878 E BooksSync: Soft error
08-30 12:29:52.441  3586  3878 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:29:52.441  3586  3878 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 12:29:52.441  3586  3878 E BooksSync: Sync error
08-30 12:29:52.441  3586  3878 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 12:29:52.441  3586  3878 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 12:29:52.441  3586  3878 I BooksSync: Finished books sync
,08-30 12:29:52.451   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128999, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:29:52.900   871  1837 D NetlinkSocketObserver: NeighborEvent{elapsedMs=129650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 12:29:56.476  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:29:56.476  3819  3871 I jxcore-log: 
,08-30 12:29:56.479  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:29:56.479  3819  3871 I jxcore-log: 
,08-30 12:29:56.490  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:29:56.490  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:56.490  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:29:56.490  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:56.490  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:56.490  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:56.490  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:56.490  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:29:56.497  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:29:56.499  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:29:56.499  3819  3871 I jxcore-log: 
,08-30 12:29:56.501  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:29:56.501  3819  3871 I jxcore-log: 
,08-30 12:29:56.994  3819  3871 I jxcore-log: Unit Test app is loaded
08-30 12:29:56.994  3819  3871 I jxcore-log: 
,08-30 12:29:57.000  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:29:57.000  3819  3871 I jxcore-log: 
,08-30 12:29:57.006  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 12:29:57.006  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3e8058 added. We now have 2 listener(s)
08-30 12:29:57.007  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:29:57.007  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:29:57.007  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:29:57.007  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-30 12:29:57.007  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc7a5b1 added. We now have 2 listener(s)
08-30 12:29:57.007  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:29:57.008  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:29:57.009  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:29:57.021  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:29:57.021  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:57.021  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:29:57.021  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:57.021  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:57.021  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:57.021  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:57.021  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:29:57.025  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:57.026  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:29:57.027  3819  3871 D ExecuteNativeTests: Running unit tests
,08-30 12:29:57.030  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:29:57.034  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:57.034  3819  3819 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 12:29:57.085  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:29:57.085  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 added. We now have 3 listener(s)
08-30 12:29:57.086  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:29:57.087  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 12:29:57.087  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:29:57.087  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:29:57.087  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 added. We now have 3 listener(s)
08-30 12:29:57.087  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:29:57.087  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:29:57.089  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:29:57.114  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:29:57.114  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:57.114  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:29:57.114  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:57.114  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:57.114  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:57.114  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:57.114  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:29:57.116  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:57.116  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:29:57.118  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 12:29:57.120  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:29:57.120  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:29:57.120  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:29:57.122  3819  3871 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 12:29:57.122  3819  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 12:29:57.122  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 12:29:57.122  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:29:57.122  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 12:29:57.122  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:29:57.123  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:29:57.123  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:29:57.123  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:29:57.123  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:29:57.123  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 removed from the list
,08-30 12:29:57.123  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:29:57.123  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 removed from the list
,08-30 12:29:57.124  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:57.125  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:29:57.125  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-30 12:29:57.127  3819  3871 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 12:29:57.127  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:29:57.127  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:29:57.127  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:29:57.127  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:29:57.127  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:29:57.127  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:29:57.134  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:57.135  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:29:57.135  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:29:57.135  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:29:57.139  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 12:29:57.139  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 12:29:57.139  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 12:29:57.139  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 12:29:57.139  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 12:29:57.139  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:29:57.139  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 12:29:57.139  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 12:29:57.139  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 12:29:57.140  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 12:29:57.141  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 12:29:57.141  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:29:57.141  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:29:57.141  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:29:57.141  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:29:57.141  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:29:57.141  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:29:57.141  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
08-30 12:29:57.141  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:29:57.141  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:29:57.141  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:29:57.144  3819  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-30 12:29:57.145  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:29:57.154  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:29:57.154  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:29:57.154  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:29:57.154  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:29:57.154  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:29:57.154  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:57.154  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:29:57.154  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:29:57.158  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:29:57.158  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:29:57.159  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 12:29:57.159  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 12:29:57.160  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 12:29:57.160  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 12:29:57.160  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:57.160  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 12:29:57.160  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:29:57.161  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 12:29:57.162  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:29:57.164  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 12:29:57.164  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 12:29:57.164  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:29:57.165  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:29:57.165  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 12:29:57.165  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:29:57.165  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:29:57.169  3819  3884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:29:57.169  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:29:57.169  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 12:29:57.173  3819  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 12:29:57.175  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 12:29:57.177  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 12:29:57.177  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 12:29:57.181  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-30 12:29:57.181  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:29:57.181  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-30 12:29:57.182  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 12:29:57.183  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 12:29:57.183  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 12:29:57.184  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:29:57.190  2710  2725 D BtGatt.GattService: registerClient() - UUID=c9e56760-2b1e-457e-8de3-623c48c2549e
08-30 12:29:57.191  2710  2763 D BtGatt.GattService: onClientRegistered() - UUID=c9e56760-2b1e-457e-8de3-623c48c2549e, clientIf=5
08-30 12:29:57.192  3819  3830 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-30 12:29:57.195  2710  2766 D BtGatt.AdvertiseManager: message : 0
08-30 12:29:57.199  2710  2766 D BtGatt.AdvertiseManager: starting multi advertising
08-30 12:29:57.226  2710  2763 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 12:29:57.241  2710  2763 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 12:29:57.242  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-30 12:29:57.242  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 12:29:57.243  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:29:57.245  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 12:29:57.245  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 12:29:57.246  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 12:29:57.246  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 12:29:57.246  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-30 12:29:57.246  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-30 12:29:57.246  3819  3871 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:29:57.248  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-30 12:29:57.248  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 12:29:57.749  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 12:29:57.750  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 12:29:57.750  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:30:02.261  3819  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-30 12:30:02.263  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,08-30 12:30:02.263  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:30:04.339  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:30:04.357  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:30:04.363  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:30:04.433  1503  2311 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 12:30:04.433  1503  2311 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 12:30:04.433  1503  2311 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:30:04.434  1503  2311 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:30:04.490  3517  3517 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 12:30:04.491  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 12:30:04.492  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 12:30:07.274  3819  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-30 12:30:07.274  3819  3871 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-30 12:30:07.274  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,08-30 12:30:07.275  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,08-30 12:30:07.276  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 12:30:07.276  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:30:07.277  3819  3871 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:30:12.287  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:12.287  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 12:30:12.288  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 12:30:12.288  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 12:30:12.291  3819  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 12:30:12.291  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 12:30:12.291  3819  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 12:30:12.292  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:30:12.292  3819  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 12:30:12.293  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 12:30:12.293  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:30:12.293  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:12.294  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:30:12.294  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:30:12.294  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:30:12.294  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 12:30:12.296  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 12:30:12.299  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:30:12.300  3819  3871 D BluetoothLeScanner: could not find callback wrapper
08-30 12:30:12.300  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:30:12.300  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 12:30:12.303  2710  2766 D BtGatt.AdvertiseManager: message : 1
,08-30 12:30:12.306  2710  2766 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 12:30:12.328  2710  2763 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 12:30:12.329  2710  2763 D BtGatt.GattService: Client app is not null!
,08-30 12:30:12.332  2710  2902 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 12:30:12.333  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 12:30:12.334  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 12:30:12.334  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 12:30:12.334  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 12:30:12.335  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 12:30:12.339  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:30:12.340  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:30:12.340  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:30:12.342  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:30:12.347  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:30:12.347  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:30:12.348  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:12.348  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:30:12.348  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:12.348  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:30:12.352  3819  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 12:30:12.361  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:30:12.373  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:30:12.373  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:12.373  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:12.373  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:12.373  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:12.373  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:12.373  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:12.373  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:30:12.378  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:12.378  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:30:12.378  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:30:12.379  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:30:12.379  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 12:30:12.379  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:30:12.379  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 12:30:12.384  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:12.386  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 12:30:12.386  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:30:12.391  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:12.396  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:30:12.398  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 12:30:12.398  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:30:12.403  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 12:30:12.412  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 12:30:12.412  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 12:30:12.412  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 12:30:12.413  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 12:30:12.415  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:30:12.423  2710  2725 D BtGatt.GattService: registerClient() - UUID=3ccde544-195b-4747-8af0-2d078c0071f1
,08-30 12:30:12.426  2710  2763 D BtGatt.GattService: onClientRegistered() - UUID=3ccde544-195b-4747-8af0-2d078c0071f1, clientIf=5
,08-30 12:30:12.427  3819  3831 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 12:30:12.429  2710  2902 D BtGatt.GattService: start scan with filters
,08-30 12:30:12.438  2710  2767 D BtGatt.ScanManager: handling starting scan
,08-30 12:30:12.439  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-30 12:30:12.440  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 12:30:12.440  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 12:30:12.440  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 12:30:12.443  2710  2767 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
08-30 12:30:12.444  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:30:12.444  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 12:30:12.444  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:30:12.446  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 12:30:12.449  3819  3871 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:30:12.459  2710  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 12:30:12.460  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:30:12.461  2710  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:30:12.470  2710  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 12:30:12.470  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:30:12.471  2710  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-30 12:30:12.471  2710  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 12:30:12.494  2710  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 12:30:12.494  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:30:12.508  2710  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:30:12.509  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:30:12.946  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 12:30:12.947  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:30:12.947  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:30:14.016  2710  2710 D BtGatt.ScanManager: awakened up at time 150767
,08-30 12:30:14.018  2710  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:30:14.078  2710  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=11
08-30 12:30:14.078  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:30:14.079  2710  2763 D BtGatt.GattService: current time is 150829557638
08-30 12:30:14.081  2710  2763 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -85, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 120, 14, 52, -72, 3, 100, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, -112, -25, -60, -2, -84, -17, 0, 35, 97, 126, -92, 22, -56, 1, -128, -85, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -7, 49, -33, -97, -43, 68, 1, -128, -59, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 78, -20, -96, 83, -39, -56, 1, -128, -83, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 118, 39, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -99, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 120, 14, 52, -72, 3, 100, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, -112, -25, -60, -2, -84, -17, 0, 78, -20, -96, 83, -39, -56, 1, -128, -83, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 118, 39, 0]
08-30 12:30:14.085  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 12:30:14.087  2710  2763 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, -112, -25, -60, -2, -84, -17]
08-30 12:30:14.087  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 12:30:14.088  2710  2763 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,08-30 12:30:14.089  2710  2763 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 118, 39]
,08-30 12:30:14.090  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 12:30:14.090  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 12:30:14.092  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 12:30:14.093  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-30 12:30:14.093  2710  2763 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, -112, -25, -60, -2, -84, -17]
,08-30 12:30:14.094  2710  2763 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 118, 39]
,08-30 12:30:14.106  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,08-30 12:30:14.108  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 90:E7:C4:FE:AC:EF 1], added - the peer count is 2
,08-30 12:30:14.109  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 90:E7:C4:FE:AC:EF 1] updated - the peer count is 2
,08-30 12:30:14.110  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:76:27 3], added - the peer count is 3
,08-30 12:30:14.111  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 08:EC:A9:50:76:27 3] updated - the peer count is 3
,08-30 12:30:14.112  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-30 12:30:14.113  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 90:E7:C4:FE:AC:EF 1], Bluetooth address: 90:E7:C4:FE:AC:EF, device name: '', device address: ''
,08-30 12:30:14.114  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:76:27 3], Bluetooth address: 08:EC:A9:50:76:27, device name: '', device address: ''
,08-30 12:30:15.581  2710  2710 D BtGatt.ScanManager: awakened up at time 152332
,08-30 12:30:15.583  2710  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:30:15.594  2710  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 12:30:15.595  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:30:16.346   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 12:30:16.359   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 12:30:16.359   871   891 I Adreno  : Build Date                       : 10/20/15
08-30 12:30:16.359   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 12:30:16.359   871   891 I Adreno  : Local Branch                     : M14
08-30 12:30:16.359   871   891 I Adreno  : Remote Branch                    : 
08-30 12:30:16.359   871   891 I Adreno  : Remote Branch                    : 
08-30 12:30:16.359   871   891 I Adreno  : Reconstruct Branch               : 
,08-30 12:30:16.368  1878  1878 I Keyboard.Facilitator: onFinishInput()
,08-30 12:30:16.384   280   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (295 us)
,08-30 12:30:17.037  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 12:30:17.037  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 12:30:17.082   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 12:30:17.086  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d52fa55 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2ac2bf6, 16908290=android.view.AbsSavedState$1@2ac2bf6}, android:focusedViewId=100}]}]
,08-30 12:30:17.089  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-30 12:30:17.089  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 12:30:17.089  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 12:30:17.089   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 12:30:17.094  2710  2710 D BtGatt.ScanManager: awakened up at time 153844
,08-30 12:30:17.094   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 12:30:17.096   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000,
08-30 12:30:17.096  2710  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 12:30:17.097   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 12:30:17.112  2710  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-30 12:30:17.112  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:30:17.113  2710  2763 D BtGatt.GattService: current time is 153863538982
08-30 12:30:17.113  2710  2763 D BtGatt.GattService: Batch record : [78, -20, -96, 83, -39, -56, 1, -128, -74, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 118, 39, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -88, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -67, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -126, -22, -96, 83, -39, -56, 1, -128, -72, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 117, 65, 0]
08-30 12:30:17.113  2710  2763 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 118, 39]
,08-30 12:30:17.113  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 12:30:17.113  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 12:30:17.114  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 12:30:17.114  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 12:30:17.114  2710  2763 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 8, -20, -87, 80, 117, 65]
08-30 12:30:17.115  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 08:EC:A9:50:76:27 3] updated - the peer count is 3
,08-30 12:30:17.116  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 3], added - the peer count is 4
08-30 12:30:17.116  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 3], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,08-30 12:30:17.324   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 12:30:17.328   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 12:30:17.334   871  1331 D SurfaceControl: Excessive delay in setPowerMode(): 240ms
,08-30 12:30:17.339   871   891 I DreamManagerService: Entering dreamland.
08-30 12:30:17.341   871   891 I PowerManagerService: Dozing...
,08-30 12:30:17.343   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 12:30:17.439   376  1276 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 12:30:17.440   376  1276 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 12:30:17.449  3819  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:30:17.450  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:30:17.450  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 12:30:17.451  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:17.451  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left,
,08-30 12:30:17.451  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 12:30:17.452  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 12:30:17.452  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,08-30 12:30:17.452  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:30:17.453  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 12:30:17.453  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 12:30:17.456  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:30:17.457  2710  2725 D BtGatt.GattService: stopScan() - queue size =1
,08-30 12:30:17.460  2710  2723 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 12:30:17.462  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:30:17.462  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 12:30:17.463  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 12:30:17.463   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 12:30:17.463  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 12:30:17.463  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 12:30:17.467  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:30:17.467  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 12:30:17.468  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:30:17.468  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:30:17.478  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:30:17.478  3819  3871 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-30 12:30:17.481  2710  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 12:30:17.481  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:30:17.481  2710  2767 D BtGatt.ScanManager: stopping BLe Batch
08-30 12:30:17.481   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-30 12:30:17.484  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:30:17.484  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:30:17.484  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:30:17.485  1958  3890 D NfcService: Discovery configuration equal, not updating.
08-30 12:30:17.487   871  1306 E native  : do suspend false
08-30 12:30:17.494  2710  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 12:30:17.494  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:30:17.495  2710  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 12:30:17.500   871  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 12:30:17.508   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:30:17.511   871  1306 E native  : do suspend true
,08-30 12:30:17.513  2710  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-30 12:30:17.513  2710  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:30:17.513  2710  2763 D BtGatt.GattService: current time is 154264201313
,08-30 12:30:17.514  2710  2763 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 87, 45, 110, 28, -13, -4, 1, -128, -61, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 55, -106, -85, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -91, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
08-30 12:30:17.514  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 12:30:17.514  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113],
08-30 12:30:17.514  2710  2763 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 55, -106, -85]
08-30 12:30:17.514  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-30 12:30:17.514  2710  2763 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-30 12:30:17.565   376  1314 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 12:30:17.565   376  1314 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 12:30:17.974   871  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-30 12:30:17.985  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:30:17.986  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:30:17.986  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:30:21.670  1894  2647 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 12:30:22.485  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:30:22.485  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:22.486  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:30:22.486  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:30:22.486  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:22.487  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:30:22.487  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:30:22.487  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.492  3819  3871 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 12:30:22.494  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:30:22.495  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:22.495  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:22.495  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:30:22.495  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:22.495  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:30:22.495  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:22.495  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.495  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.496  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 12:30:22.496  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:22.496  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.497  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.497  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:30:22.497  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:22.497  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
08-30 12:30:22.497  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:30:22.497  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.497  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.498  3819  3871 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 12:30:22.498  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:22.498  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.498  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.498  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:30:22.498  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:22.498  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
08-30 12:30:22.498  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:22.498  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.499  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:22.499  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 12:30:22.499  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:22.499  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.500  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.500  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:30:22.500  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:22.500  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
08-30 12:30:22.500  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:22.500  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.500  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.501  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 12:30:22.503  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:30:22.503  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:30:22.503  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 12:30:22.503  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:30:22.504  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:30:22.504  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 12:30:22.504  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:30:22.505  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:30:22.505  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:22.505  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.505  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.506  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:30:22.506  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:22.506  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:30:22.507  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:22.507  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.507  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.509  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:22.513  3819  3871 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:30:22.513  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 12:30:22.520  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:22.520  3819  3871 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 12:30:22.521  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 12:30:22.521  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 12:30:22.521  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 12:30:22.521  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 12:30:22.521  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:30:22.522  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-30 12:30:22.523  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-30 12:30:22.523  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 12:30:22.523  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:30:22.523  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:30:22.523  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-30 12:30:22.523  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 12:30:22.523  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:30:22.523  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:30:22.523  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 12:30:22.524  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 12:30:22.525  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 12:30:22.525  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 12:30:22.525  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-30 12:30:22.525  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:30:22.525  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 12:30:22.527  3819  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:30:22.527  3819  3871 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 12:30:22.527  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:22.527  3819  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:30:22.528  3819  3871 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 12:30:22.528  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:22.528  3819  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:30:22.528  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 12:30:22.531  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 12:30:22.532  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 12:30:22.532  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 12:30:22.533  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 12:30:22.533  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 12:30:22.533  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 12:30:22.534  3819  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:30:22.534  3819  3871 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-30 12:30:22.535  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:22.535  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.535  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.535  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 12:30:22.535  3819  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 395)
,08-30 12:30:22.535  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list,
08-30 12:30:22.536  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:22.536  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:30:22.536  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:22.536  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.536  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:22.536  3819  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 395
08-30 12:30:22.537  3819  3895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:30:22.537  3819  3871 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 12:30:22.537  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:30:22.537  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.537  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:22.537  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:30:22.537  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:22.538  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list,
08-30 12:30:22.538  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:30:22.538  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:22.538  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:22.540  3819  3871 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 12:30:22.540  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:22.540  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.541  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.541  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:30:22.541  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:22.541  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
08-30 12:30:22.541  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:22.541  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.541  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.542  3819  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 12:30:22.542  3819  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 12:30:22.542  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:30:22.543  3819  3871 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 12:30:22.543  3819  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:30:22.543  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 12:30:22.543  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:30:22.543  3819  3871 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 12:30:22.543  3819  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:30:22.543  3819  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:30:22.543  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:30:22.543  3819  3871 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 12:30:22.544  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:22.544  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.544  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:22.544  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:30:22.544  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:22.544  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
08-30 12:30:22.544  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:22.544  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:22.544  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:22.553  3819  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-30 12:30:22.554  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:30:22.558  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:30:22.558  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:22.558  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:22.558  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:22.558  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:22.558  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:22.558  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:22.558  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:30:22.560  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:30:22.560  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:30:22.560  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,08-30 12:30:22.560  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
08-30 12:30:22.561  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 12:30:22.561  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 12:30:22.562  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 12:30:22.562  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:30:22.562  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:22.563  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 12:30:22.563  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 12:30:22.563  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 12:30:22.563  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-30 12:30:22.563  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 12:30:22.563  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:30:22.563  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:30:22.564  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:22.564  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:30:22.569  3819  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:30:22.570  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:30:22.570  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:30:22.572  3819  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 12:30:22.574  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:30:22.574  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 12:30:22.575  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:30:22.577  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 12:30:22.577  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:30:22.577  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
08-30 12:30:22.577  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 12:30:22.577  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 12:30:22.577  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-30 12:30:22.578  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:30:22.580  2710  2723 D BtGatt.GattService: registerClient() - UUID=5dc0ceee-fae8-4e21-b078-9ee7528a6637
08-30 12:30:22.580  2710  2763 D BtGatt.GattService: onClientRegistered() - UUID=5dc0ceee-fae8-4e21-b078-9ee7528a6637, clientIf=5
08-30 12:30:22.580  3819  3830 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 12:30:22.581  2710  2766 D BtGatt.AdvertiseManager: message : 0
,08-30 12:30:22.583  2710  2766 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 12:30:22.592  2710  2763 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 12:30:22.597  2710  2763 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 12:30:22.598  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 12:30:22.598  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 12:30:22.600  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:30:22.601  3819  3871 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:30:22.601  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 12:30:22.601  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-30 12:30:22.601  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 12:30:22.601  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 12:30:22.601  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-30 12:30:22.601  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 12:30:22.604  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 12:30:22.604  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 12:30:22.722  3029  3898 V KeepSync: Connecting to GoogleApiClient
,08-30 12:30:22.723   871  1992 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 12:30:22.773  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:30:22.777  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:30:22.812  1503  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 12:30:22.812  1503  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-30 12:30:22.813  1503  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:30:22.813  1503  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:30:22.823  1503  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 12:30:22.823  1503  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 12:30:22.824  1503  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:30:22.824  1503  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:30:22.841  1710  3901 V BaseAuthAsyncOperation: access token request failed
,08-30 12:30:22.842  3029  3898 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 12:30:22.856  3002  3900 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 12:30:22.856  3002  3900 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at jdm.a(PG:82)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at jcs.o(PG:406)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at jcn.a(PG:1379)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at jcs.i(PG:143)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at blb.a(PG:3937)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at czp.a(PG:18188)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at czp.a(PG:9081)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at czq.run(PG:1686)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:30:22.856  3002  3900 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at jdj.a(PG:4091)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at jdj.a(PG:1125)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at jdm.a(PG:77)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	... 12 more
08-30 12:30:22.856  3002  3900 E HttpOperation: Caused by: faj: BadAuthentication
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at fal.a(PG:38)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	at jdj.a(PG:4089)
08-30 12:30:22.856  3002  3900 E HttpOperation: 	... 14 more
,08-30 12:30:22.919  1503  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 12:30:22.919  1503  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 12:30:22.919  1503  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:30:22.919  1503  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:30:22.922  1503  3093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 12:30:22.922  1503  3093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 12:30:22.922  1503  3093 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:30:22.922  1503  3093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:30:22.933  3002  3900 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 12:30:22.933  3002  3900 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at jdm.a(PG:82)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at jcs.o(PG:406)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at jcn.a(PG:1379)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at jcs.i(PG:143)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at hec.a(PG:42)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at hee.a(PG:102)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at czr.a(PG:65)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at kka.a(PG:108)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at czp.a(PG:19176)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at czp.a(PG:9081)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at czq.run(PG:1686)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:30:22.933  3002  3900 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at jdj.a(PG:4091)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at jdj.a(PG:1125)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at jdm.a(PG:77)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	... 15 more
08-30 12:30:22.933  3002  3900 E HttpOperation: Caused by: faj: BadAuthentication
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at fal.a(PG:38)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	at jdj.a(PG:4089)
08-30 12:30:22.933  3002  3900 E HttpOperation: 	... 17 more
,08-30 12:30:22.933  3002  3900 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 12:30:22.933  3002  3900 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at hec.a(PG:42)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at hee.a(PG:102)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at czr.a(PG:65)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at kka.a(PG:108)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	... 15 more
08-30 12:30:22.933  3002  3900 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at fal.a(PG:38)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 12:30:22.933  3002  3900 E ExperimentLoader: 	... 17 more
,08-30 12:30:22.951  3029  3898 E KeepSync: IOException
08-30 12:30:22.951  3029  3898 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 12:30:22.951  3029  3898 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 12:30:22.951  3029  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 12:30:22.951  3029  3898 E KeepSync: 	... 10 more
,08-30 12:30:22.951  3029  3898 W KeepSync: Sync result 2
,08-30 12:30:22.961   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129890, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:30:23.030   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130155, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 12:30:23.105  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 12:30:23.106  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 12:30:23.106  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:30:24.633  3615  3903 V GoogleAuthProtoRequest: [296] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 12:30:24.681  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 12:30:24.681  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-30 12:30:24.681  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:30:24.681  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: [296] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: [296] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 12:30:24.712  3615  3903 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 12:30:24.778  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:30:24.816  1503  2157 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 12:30:24.816  1503  2157 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 12:30:24.816  1503  2157 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:30:24.816  1503  2157 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:30:24.854  3517  3517 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 12:30:24.854  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 12:30:24.854  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-30 12:30:26.561   871  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-30 12:30:27.601  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:27.601  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 12:30:27.602  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 12:30:27.602  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 12:30:27.603  3819  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 12:30:27.603  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 12:30:27.603  3819  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 12:30:27.603  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:30:27.604  3819  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 12:30:27.604  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:30:27.604  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-30 12:30:27.604  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:27.605  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 12:30:27.605  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:30:27.605  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:30:27.605  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 12:30:27.606  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 12:30:27.608  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:30:27.608  3819  3871 D BluetoothLeScanner: could not find callback wrapper
08-30 12:30:27.609  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:30:27.609  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 12:30:27.612  2710  2766 D BtGatt.AdvertiseManager: message : 1
,08-30 12:30:27.614  2710  2766 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 12:30:27.624  2710  2763 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 12:30:27.624  2710  2763 D BtGatt.GattService: Client app is not null!
,08-30 12:30:27.626  2710  2725 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 12:30:27.627  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 12:30:27.628  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 12:30:27.628  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 12:30:27.628  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 12:30:27.629  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 12:30:27.633  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:30:27.633  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:30:27.633  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:30:27.634  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:30:27.637  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:30:27.637  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:27.637  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:30:27.637  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:27.637  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:30:27.638  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:30:27.669  2710  2888 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-30 12:30:27.669  2710  2893 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,08-30 12:30:27.670  3819  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 395)
,08-30 12:30:28.139  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:30:32.638  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:32.639  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:30:32.639  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:30:32.640  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:32.640  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:32.640  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:30:32.641  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:32.641  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:32.641  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:32.641  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:30:32.642  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:32.642  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
08-30 12:30:32.642  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:30:32.643  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:32.643  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:32.647  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 12:30:32.648  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:30:32.651  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 12:30:32.652  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 12:30:32.653  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 12:30:32.654  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:30:32.654  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:30:32.654  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:30:32.656  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:32.656  3819  3904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:30:32.656  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 12:30:32.656  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 12:30:32.656  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 12:30:32.657  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:32.657  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:30:32.658  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 12:30:32.658  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:30:32.658  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:32.658  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 12:30:32.659  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:30:32.659  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:30:32.660  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:32.660  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:32.661  3819  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-30 12:30:32.662  3819  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 12:30:32.662  3819  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 12:30:32.662  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:30:32.663  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 12:30:32.663  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:30:32.664  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 12:30:32.664  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:30:32.665  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:30:32.665  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:32.665  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:32.665  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:32.666  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:30:32.666  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:32.667  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
08-30 12:30:32.667  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:32.667  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:32.667  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:32.670  3819  3871 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-30 12:30:32.672  3819  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 12:30:32.672  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 12:30:32.673  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 12:30:32.673  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:30:32.673  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:30:32.673  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:32.673  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:32.674  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
08-30 12:30:32.674  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:32.674  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
08-30 12:30:32.674  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:32.674  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:32.675  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:32.682  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:30:32.682  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:32.682  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:32.682  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:30:32.682  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:32.682  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list
,08-30 12:30:32.682  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:32.682  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:32.683  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:32.683  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:30:32.683  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:32.684  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:32.684  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a662307 not in the list
,08-30 12:30:32.684  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:30:32.684  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a933c34 not in the list,
08-30 12:30:32.684  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:32.684  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:30:32.684  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:32.685  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 12:30:32.685  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:30:32.685  3819  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 12:30:32.686  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:30:32.686  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 12:30:32.686  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 12:30:32.688  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 12:30:32.688  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 12:30:32.689  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 12:30:32.689  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 12:30:32.689  3819  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 12:30:32.689  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 12:30:32.689  3819  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 12:30:32.689  3819  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-30 12:30:32.690  3819  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 12:30:32.690  3819  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 12:30:32.691  3819  3871 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 12:30:32.691  3819  3871 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-30 12:30:32.691  3819  3871 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 12:30:32.691  3819  3871 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 12:30:32.692  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:30:32.692  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf8c3ce added. We now have 3 listener(s)
,08-30 12:30:32.692  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:30:32.695  3819  3871 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 12:30:32.695   871  1970 D WifiService: setWifiEnabled: true pid=3819, uid=10000
08-30 12:30:32.696   871  1970 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:30:33.166  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:30:37.706  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:30:37.707  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e852ef added. We now have 4 listener(s)
,08-30 12:30:37.707  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:30:37.723  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:37.724  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e852ef removed from the list
,08-30 12:30:37.724  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:30:37.724  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:37.726  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:30:37.732  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:30:37.732  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a51fc added. We now have 4 listener(s)
08-30 12:30:37.733  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:30:37.736  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:30:37.737  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a51fc removed from the list
,08-30 12:30:37.737  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:30:37.737  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:30:37.737  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:30:37.740  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:30:37.740  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e47e085 added. We now have 4 listener(s)
08-30 12:30:37.741  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:30:37.747   871  1992 D WifiService: setWifiEnabled: false pid=3819, uid=10000
,08-30 12:30:37.747   871  1992 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:30:37.757  2710  2758 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 12:30:37.757  2710  2758 D BluetoothAdapterProperties: Setting state to 13
08-30 12:30:37.757  2710  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
,08-30 12:30:37.762  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:30:37.763  2710  2758 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 12:30:37.767  2710  2758 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:30:37.770  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.770  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:30:37.770  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.770  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.770  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:37.770  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.770  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:37.770  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:37.770  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:30:37.770  2710  2710 D BluetoothMapService: onReceive
08-30 12:30:37.771  2710  2710 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:37.771  2710  2710 D BluetoothMapService: STATE_TURNING_OFF
08-30 12:30:37.771  2710  2710 D BluetoothMapService: MAP Service closeService in
08-30 12:30:37.771  2710  2710 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 12:30:37.771  2710  2710 D ObexServerSockets0: shutdown(block = true)
,08-30 12:30:37.772  2710  2710 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:30:37.772  2710  2710 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:30:37.772  2710  2918 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 12:30:37.774  2710  2893 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 12:30:37.775  2710  2919 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-30 12:30:37.776  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.777  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:30:37.777  2710  2710 I BtOppRfcommListener: stopping Accept Thread
08-30 12:30:37.777  2710  3428 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:37.777  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:30:37.778  2710  3428 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 12:30:37.786  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:37.788  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:37.791  1444  1444 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:30:37.791  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.792  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:37.792  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.792  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.792  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:37.792  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.792  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:37.792  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:37.792  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:30:37.792  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:37.792  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:37.794   871  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 12:30:37.794   871  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 12:30:37.794   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:30:37.795   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:30:37.796  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:37.796  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:37.796  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.796  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.796  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:37.796  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.796  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:37.796  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:37.796  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:37.797  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:37.797   871   884 I ActivityManager: Start proc 3908:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-30 12:30:37.797  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:37.798  2710  2763 D BluetoothAdapterProperties: Scan Mode:20,
,08-30 12:30:37.798  2710  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 12:30:37.802  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:37.803  2710  2710 D HeadsetService: Received stop request...Stopping profile...
,08-30 12:30:37.807   871  1306 E native  : do suspend true
08-30 12:30:37.807  1361  2049 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:37.807  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:37.807   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:37.807  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-30 12:30:37.807   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:37.807  1973  2291 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:37.807   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:37.809  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:37.809  2710  2710 D A2dpService: Received stop request...Stopping profile...
08-30 12:30:37.810  2710  2912 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:30:37.810  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:37.811   871   871 D BluetoothA2dp: Proxy object disconnected
08-30 12:30:37.811  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-30 12:30:37.811  2710  2710 D HidService: Received stop request...Stopping profile...
08-30 12:30:37.811  2710  2710 D HidService: Stopping Bluetooth HidService
08-30 12:30:37.812  2710  2710 D HealthService: Received stop request...Stopping profile...
08-30 12:30:37.812  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-30 12:30:37.812  1361  1361 D HidProfile: Bluetooth service disconnected
08-30 12:30:37.813  2710  2710 V BluetoothAdapterState: isTurningOff()=true
,08-30 12:30:37.813  2710  2710 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:37.813  2710  2710 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:37.813  2710  2710 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:37.814  2710  2710 D PanService: Received stop request...Stopping profile...
08-30 12:30:37.815  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 12:30:37.815  1361  1361 D PanProfile: Bluetooth service disconnected
,08-30 12:30:37.816  2710  2710 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 12:30:37.816  2710  2763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 12:30:37.817  2710  2710 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:30:37.817  2710  2888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:30:37.817  2710  2888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 12:30:37.817  2710  2888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:30:37.817  2710  2763 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-30 12:30:37.818  2710  2710 D BluetoothMapService: Received stop request...Stopping profile...
08-30 12:30:37.818  2710  2710 D BluetoothMapService: stop()
08-30 12:30:37.818  2710  2710 D BluetoothMapAppObserver: deinitObservers()
08-30 12:30:37.819  2710  2710 D BluetoothMapAppObserver: removeReceiver()
,08-30 12:30:37.820  1361  1361 D BluetoothMap: Proxy object disconnected
08-30 12:30:37.820  1361  1361 D MapProfile: Bluetooth service disconnected
08-30 12:30:37.820  2710  2710 V BluetoothAdapterState: isTurningOff()=true
,08-30 12:30:37.820  2710  2710 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:37.820  2710  2710 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:37.820  2710  2710 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:30:37.821   871  1843 D DhcpClient: Clearing IP address
08-30 12:30:37.821  2710  2763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 12:30:37.821  2710  2888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 12:30:37.821   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:30:37.821  2710  2888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 12:30:37.821  2710  2888 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:37.821  2710  2710 V BluetoothAdapterState: isTurningOff()=true
08-30 12:30:37.821  2710  2888 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 12:30:37.822  2710  2710 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:37.822  2710  2888 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:37.822  2710  2710 V BluetoothAdapterState: isBleTurningOn()=false,
08-30 12:30:37.822  2710  2888 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:37.822  2710  2710 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:30:37.822  2710  2710 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 12:30:37.822  2710  2763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 12:30:37.822  2710  2710 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-30 12:30:37.822  2710  2710 V BluetoothAdapterState: isTurningOff()=true
08-30 12:30:37.823  2710  2710 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:30:37.823  2710  2710 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:37.823  2710  2710 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:30:37.823  2710  2710 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 12:30:37.823  2710  2763 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-30 12:30:37.823  2710  2710 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 12:30:37.823  2710  2710 V BluetoothAdapterState: isTurningOff()=true
,08-30 12:30:37.823  2710  2710 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:37.824  2710  2710 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:30:37.824  2710  2710 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:37.824   372   869 D CommandListener: Setting iface cfg
,08-30 12:30:37.824  2710  2710 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 12:30:37.825  2710  2710 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 12:30:37.825  2710  2710 D BluetoothMapService: MAP Service closeService in
08-30 12:30:37.825  2710  2710 V BluetoothAdapterState: isTurningOff()=true
08-30 12:30:37.826  2710  2710 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:37.826  2710  2710 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:37.826  2710  2710 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:30:37.826  2710  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-30 12:30:37.826  2710  2758 D BluetoothAdapterProperties: Setting state to 15
08-30 12:30:37.826  2710  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 12:30:37.827  1361  2049 D BluetoothPan: onBluetoothStateChange on: false
08-30 12:30:37.827  2710  2758 I BluetoothAdapterState: Entering BleOnState
,08-30 12:30:37.827   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:37.827   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:30:37.827  1361  1381 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 12:30:37.828  1361  1389 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:37.828  1361  2049 D BluetoothMap: onBluetoothStateChange: up=false
08-30 12:30:37.829   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:37.829  1973  2147 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:37.830  1361  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 12:30:37.830   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:37.830  1361  1389 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 12:30:37.831   871  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 12:30:37.831  2710  2758 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 12:30:37.831  2710  2758 D BluetoothAdapterProperties: Setting state to 16
08-30 12:30:37.831  2710  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 12:30:37.831   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:30:37.831  2710  2758 D BluetoothAdapterProperties: onBleDisable
08-30 12:30:37.831   871  1306 E native  : do suspend true
,08-30 12:30:37.832   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 12:30:37.832  2710  2758 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:30:37.832   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 12:30:37.832  2710  2759 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 12:30:37.834  2710  2888 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 12:30:37.834  2710  2888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 12:30:37.834  1503  2423 V NativeCrypto: Read error: ssl=0x9ac85600: I/O error during system call, Connection timed out
08-30 12:30:37.836   444   444 E Parcel  : Reading a NULL string not supported here.
08-30 12:30:37.837  2710  2763 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:30:37.837  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-30 12:30:37.837  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:37.837  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.837  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.837  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:37.837  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.837  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:37.837  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:37.837  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:37.838   871  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 12:30:37.838  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.838  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:37.840  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.840  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:37.840  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.840  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.840  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:37.840  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.840  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:37.840  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:37.840  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:37.842  1503  2423 V NativeCrypto: SSL shutdown failed: ssl=0x9ac85600: I/O error during system call, Broken pipe
08-30 12:30:37.844  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.844  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:37.846  2710  2710 D BluetoothMapService: cleanup()
08-30 12:30:37.846  2710  2710 D BluetoothMapService: MAP Service closeService in
08-30 12:30:37.850  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.850  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:37.850  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.850  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.850  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:37.850  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.850  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:37.850  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:37.850  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:37.851  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.851  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:37.852  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.853  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:37.853  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.853  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.853  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:37.853  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.853  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:37.853  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:37.853  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:37.853   871  1848 D DhcpClient: Receive thread stopped
,08-30 12:30:37.854  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:37.855  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:37.872   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:30:37.873  3908  3908 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 12:30:37.882  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:30:37.886   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8ab73d9:true
,08-30 12:30:37.887  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:30:37.891   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:30:37.891   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:30:37.892   871  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 12:30:37.892   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:37.899   871  1953 I ActivityManager: Start proc 3924:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 12:30:37.901   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:30:37.903   871   888 D Tethering: MasterInitialState.processMessage what=3
08-30 12:30:37.907  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:37.909  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:37.911  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:37.918   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 12:30:37.920  1894  2297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:37.921   871  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 12:30:37.923  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:37.923  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:37.923  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.923  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.923  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:37.923  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.923  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:37.923  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:37.923  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:30:37.923  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:37.923  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:37.925  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.925  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:37.925  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.925  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.925  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:37.925  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.925  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:37.925  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:37.925  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:37.926  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.926  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:37.927  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.927  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:37.927  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:37.927  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:37.927  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:37.927  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:37.927  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:37.927  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:37.927  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:37.928  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:37.928  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:37.937  3908  3908 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 12:30:37.939  3908  3908 D BluetoothMap: Create BluetoothMap proxy object
08-30 12:30:37.948  3924  3924 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-30 12:30:37.949  3908  3908 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 12:30:37.959  3908  3908 D DockEventReceiver: finishStartingService: stopping service
08-30 12:30:37.962   372   869 E Netd    : netlink response contains error (No such file or directory)
,08-30 12:30:37.970   871  2981 I ActivityManager: Killing 2270:com.google.android.talk/u0a61 (adj 15): empty #17
,08-30 12:30:38.045  2710  2763 I bt_hci  : shut_down
,08-30 12:30:38.045  2710  2781 D bt_hwcfg: hw_epilog_process
,08-30 12:30:38.046  2710  2781 I bt_vendor: low_power_mode_cb
,08-30 12:30:38.075  2710  2781 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 12:30:38.075  2710  2781 I bt_vendor: epilog_cb
,08-30 12:30:38.076  2710  2781 I bt_hci  : epilog_finished_callback
,08-30 12:30:38.084  2710  2763 I bt_hci_h4: hal_close
,08-30 12:30:38.085  2710  2763 I bt_userial_vendor: device fd = 51 close
,08-30 12:30:38.184  3924  3924 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 12:30:38.184  3924  3924 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:30:38.184  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:30:38.185  3924  3924 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:30:38.185  3924  3924 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:30:38.185  3924  3924 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:30:38.185  3924  3924 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:30:38.185  3924  3924 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:30:38.185  3924  3924 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:30:38.185  3924  3924 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:30:38.192  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 12:30:38.199  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:30:38.204  2710  2759 D bt_stack_manager: event_shut_down_stack finished.
08-30 12:30:38.205  2710  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-30 12:30:38.206  3908  3908 D DockEventReceiver: finishStartingService: stopping service
08-30 12:30:38.221   871   882 I ActivityManager: Start proc 3958:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-30 12:30:38.225  2710  2710 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 12:30:38.225  2710  2710 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 12:30:38.225  2710  2758 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 12:30:38.226  2710  2710 D BtGatt.GattService: stop()
08-30 12:30:38.227  2710  2710 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 12:30:38.230   871   882 I ActivityManager: Killing 3559:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-30 12:30:38.267  2710  2710 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:30:38.267  2710  2710 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:30:38.267  2710  2710 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:38.267  2710  2710 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 12:30:38.267  2710  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 12:30:38.267  2710  2758 D BluetoothAdapterProperties: Setting state to 10
,08-30 12:30:38.267  2710  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 12:30:38.268  2710  2758 I BluetoothAdapterState: Entering OffState
08-30 12:30:38.270   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 12:30:38.298  2710  2710 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 12:30:38.298  2710  2710 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 12:30:38.298  2710  2759 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 12:30:38.298  2710  2710 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 12:30:38.300  2710  2759 D bt_stack_manager: event_clean_up_stack finished.
,08-30 12:30:38.310  3958  3958 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-30 12:30:38.311  2710  2710 I art     : System.exit called, status: 0
,08-30 12:30:38.311  2710  2710 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 12:30:38.381   871  1382 I ActivityManager: Process com.android.bluetooth (pid 2710) has died
,08-30 12:30:38.506  3958  3978 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-30 12:30:38.506  3958  3978 I Babel_SMS: MmsConfig.loadMmsSettings
08-30 12:30:38.507  3958  3978 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-30 12:30:38.507  3958  3978 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 12:30:38.553  3958  3978 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-30 12:30:38.553  3958  3978 I Babel_SMS: MmsConfig.loadFromResources
,08-30 12:30:38.556  3958  3978 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 12:30:38.556  3958  3978 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-30 12:30:38.585  3958  3958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:30:38.588  3958  3958 I Babel_Crash: startup - clean
,08-30 12:30:38.611  3958  3958 I Babel_telephony: TeleModule.launchCompleted
,08-30 12:30:38.622   871  1416 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-30 12:30:38.630  3958  3958 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-30 12:30:38.638  3958  3958 W Babel   : BAM#gBA: invalid account id: -1
,08-30 12:30:38.638  3958  3958 W Babel   : BAM#gBA: invalid account id: -1
08-30 12:30:38.638  3958  3958 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-30 12:30:38.642  3958  3984 I Babel   : deleted: false for 0
,08-30 12:30:38.650   871  1957 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-30 12:30:38.668  1710  1710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:30:38.673  1710  1710 D SystemUpdateService: onCreate
,08-30 12:30:38.677  1710  1710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:30:38.689  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 12:30:38.692  1710  2396 I iu.UploadsManager: num queued entries: 0
,08-30 12:30:38.693  1710  3986 I SystemUpdateService: active receiver: enabled
,08-30 12:30:38.693  1710  2396 I iu.UploadsManager: num updated entries: 0
,08-30 12:30:38.698  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:30:38.700  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:30:38.722   871  2981 I ActivityManager: Start proc 3988:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 12:30:38.736  1710  3986 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:30:38.737  1710  2396 I iu.SyncManager: NEXT; no task
,08-30 12:30:38.757  1710  3986 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 12:30:38.757  1710  3986 I SystemUpdateService: now status is 0 (complete)
08-30 12:30:38.757  1710  3986 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 12:30:38.757  1710  3986 I SystemUpdateService: file has been verified,
08-30 12:30:38.757  1710  3986 I SystemUpdateService: OTA package size = 12249756
,08-30 12:30:38.771  3958  3958 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 12:30:38.820  3988  3988 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 12:30:38.822  1710  3986 I SystemUpdateService: showing system update notification
,08-30 12:30:38.834  3988  3988 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:38.850  3958  3958 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 12:30:38.864  3958  3958 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 12:30:38.865  3958  3958 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 12:30:38.875  3988  3988 D SprintDMHelper: simOperator: 
08-30 12:30:38.875  3988  3988 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:30:38.897  3958  3958 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 12:30:38.901   871  1992 I ActivityManager: Start proc 4000:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 12:30:38.916  3958  3958 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 12:30:38.921   871  1957 I ActivityManager: Killing 2784:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 12:30:38.983  3958  3958 I vclib   : onServiceConnected
,08-30 12:30:39.009  1710  1710 D SystemUpdateService: onDestroy
,08-30 12:30:39.013   871  1962 I ActivityManager: Killing 3500:android.process.acore/u0a5 (adj 15): empty #17
,08-30 12:30:39.125  3924  3948 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 12:30:39.137   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@347f17b:true
,08-30 12:30:39.143   871  1382 I ActivityManager: Start proc 4016:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 12:30:39.150  3958  4014 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-30 12:30:39.194  4016  4016 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 12:30:39.257  4016  4016 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 12:30:39.257  4016  4016 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 12:30:39.257  4016  4016 I GAv4    :   adb logcat -s GAv4
,08-30 12:30:39.267  4016  4016 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:30:39.272  4016  4016 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:30:39.301  4016  4033 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 12:30:39.404  4016  4016 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 12:30:39.448  4016  4016 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 12:30:39.462  4016  4016 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 6205-6212)
08-30 12:30:39.462  4016  4016 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 12:30:39.472  4016  4016 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bae4b0b}
,08-30 12:30:39.472  4016  4016 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 12:30:39.474  4016  4016 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 12:30:39.482  4016  4016 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 12:30:39.484  4016  4016 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 12:30:39.502  4016  4016 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 12:30:39.514  4016  4016 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:30:39.514  4016  4016 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 12:30:39.514  4016  4016 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 12:30:39.514  4016  4016 I Adreno  : Build Date                       : 10/20/15
08-30 12:30:39.514  4016  4016 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 12:30:39.514  4016  4016 I Adreno  : Local Branch                     : M14
08-30 12:30:39.514  4016  4016 I Adreno  : Remote Branch                    : 
08-30 12:30:39.514  4016  4016 I Adreno  : Remote Branch                    : 
08-30 12:30:39.514  4016  4016 I Adreno  : Reconstruct Branch               : 
,08-30 12:30:39.581  4016  4016 I NSApplication: Starting up...
,08-30 12:30:39.591  4016  4062 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 12:30:39.626   871  1992 I ActivityManager: Start proc 4067:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-30 12:30:39.627   871  1992 I ActivityManager: Killing 3690:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 12:30:39.681  4067  4067 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 12:30:39.863   871  2981 I ActivityManager: Killing 3707:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 12:30:42.781   871   881 D WifiService: setWifiEnabled: true pid=3819, uid=10000
,08-30 12:30:42.781   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:30:42.793   871  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-30 12:30:42.804  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:42.804  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:42.804  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:42.804  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:42.804  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:42.804  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:42.804  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:42.804  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:42.804  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:42.805  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.805  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:42.807  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.807  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:42.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:42.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:42.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:42.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:42.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:42.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:42.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:30:42.808  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.808  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:42.810  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:42.810  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:42.810  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:42.810  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:42.810  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:42.810  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:42.810  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:42.810  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:42.810  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:42.810  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:42.810  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:42.817   871  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-30 12:30:42.818   871  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 12:30:42.818   871  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 12:30:42.819   871  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 12:30:42.820   871  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 12:30:42.820   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 12:30:42.820   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 12:30:42.848   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 12:30:42.849   372   869 D CommandListener: Setting iface cfg
,08-30 12:30:42.850   871  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
,08-30 12:30:42.850   871  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 12:30:42.852   871  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 12:30:42.852   871  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 12:30:42.855   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:30:42.866   871  1306 E native  : do suspend true
,08-30 12:30:42.893   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:30:44.256   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:30:44.266   871  1416 I ActivityManager: Killing 3449:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 12:30:44.293   871  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.81 rxSuccessRate=5.69 delta 1000 -> 1000
,08-30 12:30:44.352   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 12:30:44.352   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:30:44.366   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 12:30:44.431   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 12:30:44.433  1444  1444 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 12:30:44.853  1444  1444 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 12:30:44.896  1444  1444 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 12:30:44.897  1444  1444 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 12:30:44.902   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:30:44.912   871  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:30:44.913   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 12:30:44.914   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:30:44.935   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:30:44.949   372   869 D CommandListener: Setting iface cfg
,08-30 12:30:44.950   871  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 12:30:44.966   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 12:30:45.010   871  4094 D DhcpClient: Receive thread started
,08-30 12:30:45.098   871  1306 E native  : do suspend false
,08-30 12:30:45.121   871  1843 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 12:30:45.137   871  4094 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172642, domain null
,08-30 12:30:45.138   871  1843 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172642 seconds
,08-30 12:30:45.141   871  1843 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 12:30:45.163   871  4094 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 12:30:45.164   871  1843 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 12:30:45.169   372   869 D CommandListener: Setting iface cfg
,08-30 12:30:45.182   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 12:30:45.184   871  1843 D DhcpClient: Scheduling renewal in 86399s
08-30 12:30:45.184   871  1306 E native  : do suspend true
,08-30 12:30:45.205   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 12:30:45.208   871  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 12:30:45.209   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 12:30:45.213   871  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 12:30:45.228   871  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 12:30:45.294   871  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 12:30:45.294   871  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 12:30:45.299   871  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 12:30:45.304   871  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 12:30:45.309   871  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 12:30:45.327   871  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 12:30:45.340   871  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 12:30:45.340   871  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 12:30:45.341   871  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 12:30:45.343   871  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-30 12:30:45.343   871  1308 D ConnectivityService:    accepting network in place of null
08-30 12:30:45.343   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 12:30:45.346   871  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:30:45.399   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:30:45.408   871  4093 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182158, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 12:30:45.434   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:30:45.441   871  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 12:30:45.442   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:45.453   871  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 12:30:45.454   871   888 D Tethering: MasterInitialState.processMessage what=3
08-30 12:30:45.466  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:45.466  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:45.466  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:45.466  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:45.466  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:45.466  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:45.466  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:45.466  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:45.466  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:45.466  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:45.467  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:45.469  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:45.470  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:45.470  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:45.470  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:45.470  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:45.470  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:45.470  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:45.470  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:45.470  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:45.470  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:45.470  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:45.473  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:45.473  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:45.473  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:45.473  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:45.473  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:30:45.473  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:45.473  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:30:45.473  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:30:45.473  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:30:45.473  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:45.474  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:30:45.485  1710  1710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:30:45.490  1710  1710 D SystemUpdateService: onCreate
,08-30 12:30:45.493  1710  1710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:30:45.500   871  4092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 12:30:45.520  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 12:30:45.522  1710  2396 I iu.UploadsManager: num queued entries: 0
,08-30 12:30:45.526  1710  4104 I SystemUpdateService: active receiver: enabled
,08-30 12:30:45.531  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:30:45.532  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:30:45.534  3988  3988 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:45.540  1710  4107 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 12:30:45.540  1710  4107 W BaseAppContext: Using Auth Proxy for data requests.
08-30 12:30:45.540  3988  3988 D SprintDMHelper: simOperator: 
,08-30 12:30:45.540  3988  3988 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:30:45.545  1710  4107 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 12:30:45.552  1710  2396 I iu.UploadsManager: num updated entries: 0
,08-30 12:30:45.553  1710  2396 I iu.SyncManager: NEXT; no task
,08-30 12:30:45.561  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:30:45.566  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:30:45.558  1710  4104 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:30:45.591  1710  4104 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 12:30:45.591  1710  4104 I SystemUpdateService: now status is 0 (complete)
08-30 12:30:45.591  1710  4104 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 12:30:45.591  1710  4104 I SystemUpdateService: file has been verified
,08-30 12:30:45.592  1710  4104 I SystemUpdateService: OTA package size = 12249756
,08-30 12:30:45.613  1710  4104 I SystemUpdateService: showing system update notification
,08-30 12:30:45.627   871  4092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:30:45 GMT], X-Android-Received-Millis=[1472553045627], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472553045571]}
,08-30 12:30:45.628   871  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 12:30:45.628   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-30 12:30:45.629   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 12:30:45.633   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 12:30:45.636  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 12:30:45.636  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 12:30:45.636  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 12:30:45.641  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:30:45.655  1710  1710 D SystemUpdateService: onDestroy
,08-30 12:30:45.673  1710  4107 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-30 12:30:45.713  3958  4111 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 12:30:46.440   871  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 12:30:47.787   871  1687 D WifiService: setWifiEnabled: false pid=3819, uid=10000
,08-30 12:30:47.787   871  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:30:47.817  1444  1444 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 12:30:47.825  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 12:30:47.826   871  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 12:30:47.826   871  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 12:30:47.826   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:30:47.827   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:30:47.855   871  1306 E native  : do suspend true
,08-30 12:30:47.869   871  1843 D DhcpClient: Clearing IP address
,08-30 12:30:47.869   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:30:47.873   372   869 D CommandListener: Setting iface cfg
,08-30 12:30:47.880  1503  2157 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 12:30:47.881  1503  2157 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 12:30:47.881  1503  2157 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:30:47.881  1503  2157 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:30:47.882  1503  4117 V NativeCrypto: Read error: ssl=0x9a11a200: I/O error during system call, Connection timed out
,08-30 12:30:47.885  1503  4117 V NativeCrypto: SSL shutdown failed: ssl=0x9a11a200: I/O error during system call, Broken pipe
,08-30 12:30:47.888   871  4094 D DhcpClient: Receive thread stopped
,08-30 12:30:47.888   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 12:30:47.888   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-30 12:30:47.893   871  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-30 12:30:47.894   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 12:30:47.894   871  1306 E native  : do suspend true
,08-30 12:30:47.896   444   444 E Parcel  : Reading a NULL string not supported here.
,08-30 12:30:47.908   871  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 12:30:47.909   372   869 D CommandListener: Clearing all IP addresses on wlan0
,08-30 12:30:47.911   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:30:47.928  3517  3517 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 12:30:47.928  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 12:30:47.929  3517  3517 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 12:30:47.932   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:30:47.935  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:47.935  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:47.935  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:47.935  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:47.935  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:47.935  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:47.935  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:47.935  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:47.935  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:30:47.935  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:47.935  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:47.936  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:47.936  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:47.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:47.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:47.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:47.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:47.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:47.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:47.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:30:47.936  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:47.936  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:47.937   871  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 12:30:47.937  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:47.937  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:47.937  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:47.937  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:47.937  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:47.937  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:47.937  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:47.937  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:47.937  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:47.937  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:47.938  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:30:47.940  1894  2297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:30:47.954   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:30:47.981   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:30:47.982   871  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 12:30:47.983   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:47.987   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-30 12:30:47.991  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:47.993  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:47.995  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:48.004  1710  1710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:30:48.009  1710  1710 D SystemUpdateService: onCreate
,08-30 12:30:48.015  1710  1710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:30:48.029  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 12:30:48.032  1710  2396 I iu.UploadsManager: num queued entries: 0
,08-30 12:30:48.039  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:30:48.041  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:30:48.044  3988  3988 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:30:48.048  1710  4127 I SystemUpdateService: active receiver: enabled
,08-30 12:30:48.049  3988  3988 D SprintDMHelper: simOperator: 
,08-30 12:30:48.049  3988  3988 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:30:48.054  1710  2396 I iu.UploadsManager: num updated entries: 0
,08-30 12:30:48.061  1710  4127 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:30:48.073   372   869 E Netd    : netlink response contains error (No such file or directory)
08-30 12:30:48.077  3958  4132 I Babel   : connection state changed from CONNECTED to DISCONNECTED
08-30 12:30:48.078   871  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 12:30:48.080  1710  2396 I iu.SyncManager: NEXT; no task
,08-30 12:30:48.083  1710  4127 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 12:30:48.083  1710  4127 I SystemUpdateService: now status is 0 (complete)
08-30 12:30:48.083  1710  4127 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 12:30:48.083  1710  4127 I SystemUpdateService: file has been verified
08-30 12:30:48.083  1710  4127 I SystemUpdateService: OTA package size = 12249756
,08-30 12:30:48.088  1710  4127 I SystemUpdateService: showing system update notification
,08-30 12:30:48.100  1710  1710 D SystemUpdateService: onDestroy
,08-30 12:30:52.842   871   888 I ActivityManager: Start proc 4137:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 12:30:52.961  4137  4137 D AdapterServiceConfig: Adding HeadsetService
,08-30 12:30:52.961  4137  4137 D AdapterServiceConfig: Adding A2dpService
,08-30 12:30:52.961  4137  4137 D AdapterServiceConfig: Adding HidService
08-30 12:30:52.961  4137  4137 D AdapterServiceConfig: Adding HealthService
08-30 12:30:52.962  4137  4137 D AdapterServiceConfig: Adding PanService
,08-30 12:30:52.962  4137  4137 D AdapterServiceConfig: Adding GattService
08-30 12:30:52.962  4137  4137 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 12:30:52.978   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a912f0b:true
,08-30 12:30:52.980  4137  4137 D BluetoothAdapterState: make() - Creating AdapterState
08-30 12:30:52.988  4137  4137 I bt_bluedroid: init
,08-30 12:30:52.988  4137  4149 I BluetoothAdapterState: Entering OffState
,08-30 12:30:52.991  4137  4150 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 12:30:52.991  4137  4150 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 12:30:52.991  4137  4150 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 12:30:52.992  4137  4150 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 12:30:52.992  4137  4137 I bt_bluedroid: get_profile_interface socket
,08-30 12:30:52.994  4137  4137 I bt_bluedroid: get_profile_interface sdp
,08-30 12:30:52.998  4137  4148 I bt_bluedroid: config_hci_snoop_log
,08-30 12:30:52.998  4137  4153 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 12:30:52.999   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 12:30:53.001  4137  4153 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 12:30:53.071  4137  4149 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 12:30:53.071  4137  4149 D BluetoothAdapterProperties: Setting state to 14
08-30 12:30:53.071  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 12:30:53.073  4137  4149 D BluetoothBondStateMachine: make
,08-30 12:30:53.076  4137  4154 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 12:30:53.079  4137  4149 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:30:53.080  4137  4137 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 12:30:53.082  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:30:53.083  4137  4137 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:30:53.083  4137  4137 D BtGatt.GattService: Received start request. Starting profile...
08-30 12:30:53.083  4137  4137 D BtGatt.GattService: start()
,08-30 12:30:53.083  4137  4137 I bt_bluedroid: get_profile_interface gatt
,08-30 12:30:53.084  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
08-30 12:30:53.084  4137  4137 D BtGatt.AdvertiseManager: advertise manager created
,08-30 12:30:53.093  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:30:53.093  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:53.093  4137  4137 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 12:30:53.093  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:30:53.094  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 12:30:53.094  4137  4149 I bt_bluedroid: enable
,08-30 12:30:53.094  4137  4150 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 12:30:53.095  4137  4150 I bt_hci  : start_up
,08-30 12:30:53.101  4137  4150 I bt_vendor: alloc value 0xb3995189
,08-30 12:30:53.101  4137  4150 I bt_vendor: init
08-30 12:30:53.101  4137  4150 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-30 12:30:53.101  4137  4150 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 12:30:53.209  4137  4150 D bt_hci  : start_up starting async portion
,08-30 12:30:53.210  4137  4157 I bt_hci  : event_finish_startup
08-30 12:30:53.210  4137  4157 I bt_hci_h4: hal_open
08-30 12:30:53.211  4137  4157 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 12:30:53.223  4137  4157 I bt_userial_vendor: device fd = 51 open
,08-30 12:30:53.251  4137  4157 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:30:53.283  4137  4157 D bt_hwcfg: Chipset BCM4354A2
,08-30 12:30:53.283  4137  4157 D bt_hwcfg: Target name = [BCM4354A2]
08-30 12:30:53.284  4137  4157 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 12:30:53.347   871  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-30 12:30:54.118  4137  4157 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 12:30:54.120  4137  4157 D bt_hwcfg: Settlement delay -- 100 ms
08-30 12:30:54.120  4137  4157 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 12:30:54.238  4137  4157 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:30:54.240  4137  4157 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 12:30:54.267  4137  4157 I bt_hwcfg: vendor lib fwcfg completed
,08-30 12:30:54.267  4137  4157 I bt_vendor: firmware callback
08-30 12:30:54.267  4137  4157 I bt_hci  : firmware_config_callback
,08-30 12:30:54.280  4137  4159 I bt_btu  : btu_task pending for preload complete event
,08-30 12:30:54.280  4137  4159 I bt_btu_task: Bluetooth chip preload is complete
08-30 12:30:54.280  4137  4159 I bt_btu  : btu_task received preload complete event
,08-30 12:30:54.290  4137  4159 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 12:30:54.290  4137  4159 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 12:30:54.291  4137  4159 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 12:30:54.291  4137  4159 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 12:30:54.291  4137  4159 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 12:30:54.291  4137  4159 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 12:30:54.292  4137  4159 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 12:30:54.292  4137  4159 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 12:30:54.292  4137  4159 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 12:30:54.293  4137  4159 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 12:30:54.294  4137  4159 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 12:30:54.295  4137  4159 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 12:30:54.296  4137  4159 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 12:30:54.296  4137  4159 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 12:30:54.296  4137  4159 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 12:30:54.451  4137  4159 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3912d9d
,08-30 12:30:54.451  4137  4159 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3912d9d 
,08-30 12:30:54.463  4137  4153 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 12:30:54.466  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 12:30:54.467  4137  4153 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 12:30:54.470  4137  4153 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 12:30:54.473  4137  4153 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:30:54.473  4137  4153 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 12:30:54.474  4137  4153 D bt_hci  : do_postload posting postload work item
,08-30 12:30:54.475  4137  4157 I bt_hci  : event_postload
,08-30 12:30:54.475  4137  4157 I bt_vendor: sco_config_cb
,08-30 12:30:54.475  4137  4157 I bt_hci  : sco_config_callback postload finished.
08-30 12:30:54.477  4137  4153 D bt_bte_conf: Device ID record 1 : primary
08-30 12:30:54.477  4137  4153 D bt_bte_conf:   vendorId            = 000f
08-30 12:30:54.477  4137  4153 D bt_bte_conf:   vendorIdSource      = 0001
08-30 12:30:54.478  4137  4153 D bt_bte_conf:   product             = 1200
,08-30 12:30:54.478  4137  4153 D bt_bte_conf:   version             = 1436
08-30 12:30:54.478  4137  4153 D bt_bte_conf:   clientExecutableURL = 
,08-30 12:30:54.478  4137  4153 D bt_bte_conf:   serviceDescription  = 
08-30 12:30:54.478  4137  4153 D bt_bte_conf:   documentationURL    = 
08-30 12:30:54.479  4137  4153 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 12:30:54.479  4137  4150 D bt_stack_manager: event_start_up_stack finished
08-30 12:30:54.481  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 12:30:54.481  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.482  4137  4149 D BluetoothAdapterProperties: Setting state to 15
08-30 12:30:54.482  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 12:30:54.486  4137  4157 I bt_vendor: low_power_mode_cb
,08-30 12:30:54.486  4137  4149 I BluetoothAdapterState: Entering BleOnState
08-30 12:30:54.487  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.487  4137  4149 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 12:30:54.487  4137  4149 D BluetoothAdapterProperties: Setting state to 11
,08-30 12:30:54.487  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 12:30:54.490  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.494  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
08-30 12:30:54.495  4137  4137 D HeadsetService: Received start request. Starting profile...
,08-30 12:30:54.498  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.498  4137  4137 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 12:30:54.498  4137  4137 D HeadsetStateMachine: make
08-30 12:30:54.500  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.504  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.509  4137  4149 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:30:54.513  4137  4137 D HeadsetStateMachine: max_hf_connections = 1
,08-30 12:30:54.513  4137  4137 I bt_bluedroid: get_profile_interface handsfree
08-30 12:30:54.513  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 12:30:54.513  4137  4153 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 12:30:54.517  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:30:54.519  4137  4137 D A2dpService: Received start request. Starting profile...
,08-30 12:30:54.520  4137  4137 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 12:30:54.521  4137  4137 I bt_bluedroid: get_profile_interface avrcp
,08-30 12:30:54.529  4137  4137 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 12:30:54.529  4137  4137 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:30:54.530  4137  4137 D A2dpStateMachine: make
,08-30 12:30:54.531  4137  4137 I bt_bluedroid: get_profile_interface a2dp
,08-30 12:30:54.532  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 12:30:54.537  4137  4170 D A2dpStateMachine: Enter Disconnected: -2
,08-30 12:30:54.537  4137  4137 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 12:30:54.538  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:30:54.540  3908  3908 D BluetoothInputDevice: Proxy object connected
08-30 12:30:54.540  4137  4137 D HidService: Received start request. Starting profile...
08-30 12:30:54.540  4137  4137 I bt_bluedroid: get_profile_interface hidhost
08-30 12:30:54.540  4137  4137 D HidService: setHidService(): set to: null
08-30 12:30:54.540  3908  3908 D HidProfile: Bluetooth service connected
,08-30 12:30:54.541  4137  4153 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38f43e5
08-30 12:30:54.541  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 12:30:54.541  4137  4137 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 12:30:54.542  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
08-30 12:30:54.542  4137  4137 D HealthService: Received start request. Starting profile...
,08-30 12:30:54.544  4137  4137 I bt_bluedroid: get_profile_interface health
08-30 12:30:54.545  4137  4137 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 12:30:54.545  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:30:54.547  3908  3908 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:30:54.547  4137  4137 D PanService: Received start request. Starting profile...
08-30 12:30:54.547  4137  4137 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 12:30:54.547  3908  3908 D PanProfile: Bluetooth service connected,
08-30 12:30:54.547  4137  4137 I bt_bluedroid: get_profile_interface pan
08-30 12:30:54.548  4137  4153 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 12:30:54.553  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:30:54.554  4137  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:30:54.556  4137  4137 D BluetoothMapService: Received start request. Starting profile...
,08-30 12:30:54.556  4137  4137 D BluetoothMapService: start()
,08-30 12:30:54.557  3908  3908 D BluetoothMap: Proxy object connected
08-30 12:30:54.557  3908  3908 D MapProfile: Bluetooth service connected
08-30 12:30:54.558  3908  3908 D BluetoothMap: getConnectedDevices()
,08-30 12:30:54.559  4137  4137 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 12:30:54.559  3908  3908 D BluetoothMap: Bluetooth is Not enabled
08-30 12:30:54.560  4137  4137 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 12:30:54.560  4137  4137 D BluetoothMapAppObserver: createReceiver()
08-30 12:30:54.561  4137  4137 D BluetoothMapAppObserver: initObservers()
,08-30 12:30:54.561  4137  4137 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 12:30:54.571  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:30:54.571  4137  4137 V BluetoothAdapterState: isTurningOn()=true
08-30 12:30:54.571  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:54.571  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:30:54.576  4137  4168 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isTurningOff()=false
08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isTurningOn()=true
08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isTurningOff()=false
08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isTurningOn()=true
08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:54.577  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:54.578  4137  4137 V BluetoothAdapterState: isTurningOff()=false
08-30 12:30:54.578  4137  4137 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:30:54.578  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:30:54.578  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:54.578  4137  4137 V BluetoothAdapterState: isTurningOff()=false
08-30 12:30:54.578  4137  4137 V BluetoothAdapterState: isTurningOn()=true
08-30 12:30:54.578  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:54.578  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:54.579  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 12:30:54.579  4137  4149 D BluetoothAdapterProperties: ScanMode =  20
08-30 12:30:54.579  4137  4149 D BluetoothAdapterProperties: State =  11
08-30 12:30:54.580  4137  4149 D BluetoothAdapterProperties: Setting state to 12
08-30 12:30:54.580  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 12:30:54.581  1361  1389 D BluetoothPan: onBluetoothStateChange on: true
08-30 12:30:54.581  4137  4149 I BluetoothAdapterState: Entering OnState
08-30 12:30:54.582  4137  4153 D BluetoothAdapterProperties: Scan Mode:21
08-30 12:30:54.582  4137  4153 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 12:30:54.583  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:30:54.583  1361  1361 D PanProfile: Bluetooth service connected
,08-30 12:30:54.583   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:30:54.583  3908  3918 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:30:54.583   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:30:54.584  1361  3973 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:30:54.585   871   871 D BluetoothA2dp: Proxy object connected
08-30 12:30:54.587  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:54.587  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:54.587  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:54.587  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:54.587  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:54.587  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:54.587  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:54.587  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:54.593  1361  2049 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:30:54.593  1361  1389 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:30:54.594  4137  4137 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 12:30:54.595  1361  1361 D BluetoothMap: Proxy object connected
08-30 12:30:54.595  4137  4137 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 12:30:54.595  1361  1361 D MapProfile: Bluetooth service connected
08-30 12:30:54.595  1361  1361 D BluetoothMap: getConnectedDevices()
08-30 12:30:54.596   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:30:54.596  1973  2291 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:30:54.596  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:54.597  4137  4137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:30:54.598  1361  3973 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 12:30:54.599  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:54.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:54.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:54.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:54.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:54.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:54.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:54.599  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:30:54.599  1361  1361 D BluetoothInputDevice: Proxy object connected
08-30 12:30:54.599  3908  3920 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:30:54.599  1361  1361 D HidProfile: Bluetooth service connected
08-30 12:30:54.600   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:30:54.600  3908  3918 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 12:30:54.601  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:54.601  4137  4137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:30:54.601  3908  3920 D BluetoothPan: onBluetoothStateChange on: true
,08-30 12:30:54.602  4137  4137 D ObexServerSockets: Succeed to create listening sockets 
,08-30 12:30:54.602  1361  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:30:54.602  4137  4137 D ObexServerSockets0: startAccept()
08-30 12:30:54.603  4137  4137 D ObexServerSockets0: prepareForNewConnect()
08-30 12:30:54.603  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:54.603  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:54.603  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:54.603  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:54.603  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:30:54.603  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:54.603  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:54.603  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:54.604  1361  1361 D BluetoothA2dp: Proxy object connected
08-30 12:30:54.605  4137  4137 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 12:30:54.606  4137  4137 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 12:30:54.606   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 12:30:54.606  4137  4179 D ObexServerSockets0: Accepting socket connection...
08-30 12:30:54.607  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:54.607  4137  4137 D BluetoothMapService: onReceive
08-30 12:30:54.607  4137  4137 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:30:54.607  4137  4137 D BluetoothMapService: STATE_ON
08-30 12:30:54.608  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.609  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:54.609  4137  4178 D ObexServerSockets0: Accepting socket connection...
08-30 12:30:54.610  3908  3908 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 12:30:54.610  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:54.613  3908  3908 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 12:30:54.620  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:30:54.623  3908  3908 D BluetoothA2dp: Proxy object connected
,08-30 12:30:54.631  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:30:54.632  1361  1361 D BluetoothPbap: Proxy object connected
08-30 12:30:54.632  1361  1361 D PbapServerProfile: Bluetooth service connected
08-30 12:30:54.632  4137  4137 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 12:30:54.632  4137  4137 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:30:54.635  4137  4181 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:30:54.640  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:30:54.640  3908  3908 D BluetoothPbap: Proxy object connected
08-30 12:30:54.641  3908  3908 D PbapServerProfile: Bluetooth service connected
,08-30 12:30:54.671  4137  4188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:30:54.673  4137  4188 I BtOppRfcommListener: Accept thread started.
,08-30 12:30:54.684  1361  1389 D BluetoothHeadset: Proxy object connected
,08-30 12:30:54.684   871   871 D BluetoothHeadset: Proxy object connected
,08-30 12:30:54.684   871   871 D BluetoothHeadset: Proxy object connected
08-30 12:30:54.684  1361  1361 D HeadsetProfile: Bluetooth service connected
08-30 12:30:54.684  1973  2147 D BluetoothHeadset: Proxy object connected
08-30 12:30:54.685   871   871 D BluetoothHeadset: Proxy object connected
,08-30 12:30:54.694  1361  1381 D BluetoothHeadset: Proxy object connected
,08-30 12:30:54.695  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-30 12:30:54.696   871   888 D BluetoothHeadset: Proxy object connected
,08-30 12:30:54.699  1973  1984 D BluetoothHeadset: Proxy object connected
,08-30 12:30:54.699   871   888 D BluetoothHeadset: Proxy object connected
,08-30 12:30:54.718  3908  3918 D BluetoothHeadset: Proxy object connected
,08-30 12:30:54.718  3908  3908 D HeadsetProfile: Bluetooth service connected
,08-30 12:30:57.803  4137  4149 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 12:30:57.803  4137  4149 D BluetoothAdapterProperties: Setting state to 13
,08-30 12:30:57.804  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 12:30:57.805  4137  4149 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 12:30:57.809  4137  4149 I BluetoothAdapterState: Entering PendingCommandState
08-30 12:30:57.817  4137  4137 D BluetoothMapService: onReceive
08-30 12:30:57.817  4137  4137 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:30:57.818  4137  4137 D BluetoothMapService: STATE_TURNING_OFF
,08-30 12:30:57.818  4137  4137 D BluetoothMapService: MAP Service closeService in
08-30 12:30:57.818  4137  4137 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 12:30:57.819  4137  4137 D ObexServerSockets0: shutdown(block = true)
08-30 12:30:57.819  4137  4178 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 12:30:57.822  4137  4137 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 12:30:57.823  4137  4179 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 12:30:57.826  4137  4163 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 12:30:57.827  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:57.827  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:57.827  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:57.827  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:57.827  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:57.827  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:57.827  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:57.827  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:57.827  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:57.834  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:57.834  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:57.835  4137  4137 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 12:30:57.835  4137  4153 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:30:57.835  4137  4137 I BtOppRfcommListener: stopping Accept Thread
08-30 12:30:57.835  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 12:30:57.835  4137  4188 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:30:57.836  4137  4188 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 12:30:57.839  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:57.839  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:57.839  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:57.839  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:57.839  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:57.839  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:57.839  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:57.839  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:57.839  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:57.839  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:30:57.840  4137  4137 D HeadsetService: Received stop request...Stopping profile...
08-30 12:30:57.841  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:30:57.841  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:57.845  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:57.845  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:30:57.845  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:30:57.845  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:30:57.845  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:30:57.845  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:30:57.845  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:30:57.845  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:30:57.845  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:30:57.846  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:30:57.846  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:30:57.847  1361  2049 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:57.847   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:57.847   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:57.847  4137  4137 D A2dpService: Received stop request...Stopping profile...
08-30 12:30:57.848  1973  1985 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:57.848  4137  4170 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:30:57.849  3908  3918 D BluetoothHeadset: Proxy object disconnected
,08-30 12:30:57.849   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 12:30:57.849   871   871 D BluetoothA2dp: Proxy object disconnected
08-30 12:30:57.851  4137  4137 D HidService: Received stop request...Stopping profile...
,08-30 12:30:57.851  4137  4137 D HidService: Stopping Bluetooth HidService
08-30 12:30:57.853  4137  4137 V BluetoothAdapterState: isTurningOff()=true
08-30 12:30:57.853  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:57.853  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:57.853  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:57.853  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-30 12:30:57.853  1361  1361 D BluetoothA2dp: Proxy object disconnected
,08-30 12:30:57.854  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-30 12:30:57.854  1361  1361 D HidProfile: Bluetooth service disconnected
08-30 12:30:57.854  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:57.856  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:57.857  4137  4137 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 12:30:57.857  4137  4137 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:30:57.857  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:57.858  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 12:30:57.858  4137  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:30:57.858  4137  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:30:57.858  4137  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:30:57.858  4137  4137 D HealthService: Received stop request...Stopping profile...
08-30 12:30:57.858  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:30:57.859  4137  4153 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 12:30:57.860  4137  4137 V BluetoothAdapterState: isTurningOff()=true
,08-30 12:30:57.860  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:57.860  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:57.860  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:30:57.861  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:30:57.861  4137  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:30:57.861  4137  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 12:30:57.862  4137  4159 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:57.862  4137  4159 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:57.862  4137  4159 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:30:57.862  4137  4159 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:30:57.862  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 12:30:57.863  4137  4137 D PanService: Received stop request...Stopping profile...
,08-30 12:30:57.866  3908  3908 D HeadsetProfile: Bluetooth service disconnected
08-30 12:30:57.866  4137  4137 V BluetoothAdapterState: isTurningOff()=true
08-30 12:30:57.866  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 12:30:57.866  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:57.866  1361  1361 D PanProfile: Bluetooth service disconnected
,08-30 12:30:57.866  3908  3908 D BluetoothA2dp: Proxy object disconnected
08-30 12:30:57.866  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:57.866  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:57.866  3908  3908 D BluetoothInputDevice: Proxy object disconnected
08-30 12:30:57.867  3908  3908 D HidProfile: Bluetooth service disconnected
08-30 12:30:57.867  4137  4137 D BluetoothMapService: Received stop request...Stopping profile...
08-30 12:30:57.867  4137  4137 D BluetoothMapService: stop()
,08-30 12:30:57.868  3908  3908 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 12:30:57.868  4137  4137 D BluetoothMapAppObserver: deinitObservers()
08-30 12:30:57.868  3908  3908 D PanProfile: Bluetooth service disconnected
,08-30 12:30:57.868  4137  4137 D BluetoothMapAppObserver: removeReceiver()
08-30 12:30:57.869  1361  1361 D BluetoothMap: Proxy object disconnected
08-30 12:30:57.869  1361  1361 D MapProfile: Bluetooth service disconnected
08-30 12:30:57.869  3908  3908 D BluetoothMap: Proxy object disconnected
,08-30 12:30:57.870  3908  3908 D MapProfile: Bluetooth service disconnected
08-30 12:30:57.870  4137  4137 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 12:30:57.870  4137  4137 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 12:30:57.872  4137  4153 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 12:30:57.873  1361  1361 D BluetoothPbap: Proxy object disconnected
,08-30 12:30:57.873  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-30 12:30:57.874  4137  4137 V BluetoothAdapterState: isTurningOff()=true
,08-30 12:30:57.874  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:57.874  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:57.874  3908  3908 D BluetoothPbap: Proxy object disconnected
08-30 12:30:57.874  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:57.874  4137  4137 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 12:30:57.874  4137  4153 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 12:30:57.874  3908  3908 D PbapServerProfile: Bluetooth service disconnected
08-30 12:30:57.875  4137  4137 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:30:57.875  4137  4137 V BluetoothAdapterState: isTurningOff()=true
08-30 12:30:57.875  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:57.875  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:30:57.875  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:57.876  4137  4137 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-30 12:30:57.876  4137  4137 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 12:30:57.877  4137  4137 D BluetoothMapService: MAP Service closeService in
08-30 12:30:57.877  4137  4137 V BluetoothAdapterState: isTurningOff()=true
08-30 12:30:57.877  4137  4137 V BluetoothAdapterState: isTurningOn()=false
08-30 12:30:57.877  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:30:57.877  4137  4137 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:30:57.877  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 12:30:57.877  4137  4149 D BluetoothAdapterProperties: Setting state to 15
08-30 12:30:57.877  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 12:30:57.878  4137  4149 I BluetoothAdapterState: Entering BleOnState
,08-30 12:30:57.878  3908  3920 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 12:30:57.878  4137  4137 D BluetoothMapService: cleanup()
08-30 12:30:57.880  4137  4137 D BluetoothMapService: MAP Service closeService in
08-30 12:30:57.880  1361  1381 D BluetoothPan: onBluetoothStateChange on: false
08-30 12:30:57.882  3908  3918 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:57.882   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 12:30:57.882  3908  3920 D BluetoothMap: onBluetoothStateChange: up=false
08-30 12:30:57.882   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:30:57.883  1361  2049 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 12:30:57.883  1361  3973 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:57.883  1361  1389 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 12:30:57.884   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:57.884  1973  2291 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:30:57.884  1361  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 12:30:57.885  3908  3918 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 12:30:57.885   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 12:30:57.886  3908  3920 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 12:30:57.886  3908  3918 D BluetoothPan: onBluetoothStateChange on: false
,08-30 12:30:57.887  1361  2049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 12:30:57.887  4137  4149 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 12:30:57.887  4137  4149 D BluetoothAdapterProperties: Setting state to 16
08-30 12:30:57.888  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-30 12:30:57.889  4137  4149 D BluetoothAdapterProperties: onBleDisable
,08-30 12:30:57.889  4137  4149 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:30:57.889  4137  4150 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-30 12:30:57.891  4137  4159 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 12:30:57.891  4137  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 12:30:57.893  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:57.893  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 12:30:57.894  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:57.895  4137  4153 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:30:57.896  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:30:57.898  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:57.899  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:30:57.899  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:57.900  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:30:57.906  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:30:58.094  4137  4153 I bt_hci  : shut_down
,08-30 12:30:58.112  4137  4157 D bt_hwcfg: hw_epilog_process
,08-30 12:30:58.113  4137  4157 I bt_vendor: low_power_mode_cb
,08-30 12:30:58.135  4137  4157 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 12:30:58.135  4137  4157 I bt_vendor: epilog_cb
,08-30 12:30:58.135  4137  4157 I bt_hci  : epilog_finished_callback
,08-30 12:30:58.144  4137  4153 I bt_hci_h4: hal_close
,08-30 12:30:58.146  4137  4153 I bt_userial_vendor: device fd = 51 close
,08-30 12:30:58.268  4137  4150 D bt_stack_manager: event_shut_down_stack finished.
,08-30 12:30:58.270  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 12:30:58.275  4137  4137 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:30:58.276  4137  4149 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 12:30:58.277  4137  4137 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 12:30:58.277  4137  4137 D BtGatt.GattService: stop()
08-30 12:30:58.278  4137  4137 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 12:30:58.285  4137  4137 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:30:58.285  4137  4137 V BluetoothAdapterState: isTurningOn()=false
,08-30 12:30:58.285  4137  4137 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 12:30:58.286  4137  4137 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 12:30:58.286  4137  4149 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 12:30:58.287  4137  4149 D BluetoothAdapterProperties: Setting state to 10
08-30 12:30:58.288  4137  4149 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 12:30:58.290  4137  4149 I BluetoothAdapterState: Entering OffState
,08-30 12:30:58.291   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 12:30:58.313  4137  4137 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 12:30:58.313  4137  4137 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-30 12:30:58.313  4137  4137 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 12:30:58.314  4137  4150 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 12:30:58.318  4137  4150 D bt_stack_manager: event_clean_up_stack finished.
,08-30 12:30:58.320  4137  4137 I art     : System.exit called, status: 0
08-30 12:30:58.320  4137  4137 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 12:30:58.374   871  1416 I ActivityManager: Process com.android.bluetooth (pid 4137) has died
,08-30 12:31:02.800  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:31:02.800  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:02.808  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:31:02.808  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e47e085 removed from the list
,08-30 12:31:02.808  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:02.809  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:31:02.809  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:02.817  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:31:02.818  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a912f0b added. We now have 4 listener(s)
08-30 12:31:02.818  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:31:02.821  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:02.821  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a912f0b removed from the list
08-30 12:31:02.821  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:02.822  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:31:02.822  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:02.824  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:31:02.824  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a891e8 added. We now have 4 listener(s)
08-30 12:31:02.824  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:31:07.838  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:07.882   871   888 I ActivityManager: Start proc 4198:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 12:31:08.030  4198  4198 D AdapterServiceConfig: Adding HeadsetService
08-30 12:31:08.031  4198  4198 D AdapterServiceConfig: Adding A2dpService
,08-30 12:31:08.031  4198  4198 D AdapterServiceConfig: Adding HidService
08-30 12:31:08.032  4198  4198 D AdapterServiceConfig: Adding HealthService
,08-30 12:31:08.033  4198  4198 D AdapterServiceConfig: Adding PanService
,08-30 12:31:08.034  4198  4198 D AdapterServiceConfig: Adding GattService
,08-30 12:31:08.057  4198  4198 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 12:31:08.095  4198  4198 D BluetoothAdapterState: make() - Creating AdapterState
08-30 12:31:08.095   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ce05abc:true
,08-30 12:31:08.103  4198  4198 I bt_bluedroid: init
08-30 12:31:08.103  4198  4210 I BluetoothAdapterState: Entering OffState
,08-30 12:31:08.109  4198  4211 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 12:31:08.109  4198  4211 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 12:31:08.110  4198  4211 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 12:31:08.110  4198  4211 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 12:31:08.112  4198  4198 I bt_bluedroid: get_profile_interface socket
,08-30 12:31:08.116  4198  4198 I bt_bluedroid: get_profile_interface sdp
,08-30 12:31:08.117  4198  4214 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 12:31:08.121  4198  4214 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 12:31:08.123  4198  4209 I bt_bluedroid: config_hci_snoop_log
,08-30 12:31:08.127   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 12:31:08.139  4198  4210 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 12:31:08.140  4198  4210 D BluetoothAdapterProperties: Setting state to 14
08-30 12:31:08.140  4198  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 12:31:08.144  4198  4210 D BluetoothBondStateMachine: make
,08-30 12:31:08.150  4198  4215 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 12:31:08.162  4198  4210 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:31:08.163  4198  4198 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 12:31:08.173  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:31:08.176  4198  4198 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 12:31:08.178  4198  4198 D BtGatt.GattService: Received start request. Starting profile...
,08-30 12:31:08.178  4198  4198 D BtGatt.GattService: start()
,08-30 12:31:08.179  4198  4198 I bt_bluedroid: get_profile_interface gatt
08-30 12:31:08.182  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
08-30 12:31:08.182  4198  4198 D BtGatt.AdvertiseManager: advertise manager created
,08-30 12:31:08.198  4198  4198 V BluetoothAdapterState: isTurningOff()=false
08-30 12:31:08.198  4198  4198 V BluetoothAdapterState: isTurningOn()=false
08-30 12:31:08.199  4198  4198 V BluetoothAdapterState: isBleTurningOn()=true
08-30 12:31:08.199  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:31:08.200  4198  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 12:31:08.203  4198  4210 I bt_bluedroid: enable
08-30 12:31:08.204  4198  4211 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 12:31:08.205  4198  4211 I bt_hci  : start_up
,08-30 12:31:08.225  4198  4211 I bt_vendor: alloc value 0xb3995189
08-30 12:31:08.226  4198  4211 I bt_vendor: init
,08-30 12:31:08.226  4198  4211 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 12:31:08.226  4198  4211 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 12:31:08.335  4198  4211 D bt_hci  : start_up starting async portion
,08-30 12:31:08.335  4198  4218 I bt_hci  : event_finish_startup
08-30 12:31:08.336  4198  4218 I bt_hci_h4: hal_open
08-30 12:31:08.336  4198  4218 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 12:31:08.348  4198  4218 I bt_userial_vendor: device fd = 51 open
,08-30 12:31:08.378  4198  4218 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:31:08.409  4198  4218 D bt_hwcfg: Chipset BCM4354A2
,08-30 12:31:08.410  4198  4218 D bt_hwcfg: Target name = [BCM4354A2]
08-30 12:31:08.411  4198  4218 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 12:31:09.185  4198  4218 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 12:31:09.187  4198  4218 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 12:31:09.187  4198  4218 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 12:31:09.303  4198  4218 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 12:31:09.305  4198  4218 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 12:31:09.335  4198  4218 I bt_hwcfg: vendor lib fwcfg completed
,08-30 12:31:09.335  4198  4218 I bt_vendor: firmware callback
08-30 12:31:09.335  4198  4218 I bt_hci  : firmware_config_callback
,08-30 12:31:09.348  4198  4222 I bt_btu  : btu_task pending for preload complete event
,08-30 12:31:09.348  4198  4222 I bt_btu_task: Bluetooth chip preload is complete
08-30 12:31:09.349  4198  4222 I bt_btu  : btu_task received preload complete event
,08-30 12:31:09.360  4198  4222 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 12:31:09.360  4198  4222 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 12:31:09.360  4198  4222 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 12:31:09.361  4198  4222 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 12:31:09.361  4198  4222 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 12:31:09.361  4198  4222 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 12:31:09.361  4198  4222 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 12:31:09.361  4198  4222 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 12:31:09.362  4198  4222 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 12:31:09.362  4198  4222 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 12:31:09.362  4198  4222 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 12:31:09.362  4198  4222 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 12:31:09.362  4198  4222 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 12:31:09.363  4198  4222 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 12:31:09.363  4198  4222 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 12:31:09.490  4198  4222 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3912d9d
,08-30 12:31:09.491  4198  4222 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3912d9d 
,08-30 12:31:09.513  4198  4214 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 12:31:09.515  4198  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 12:31:09.516  4198  4214 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 12:31:09.519  4198  4214 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 12:31:09.524  4198  4214 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:31:09.525  4198  4214 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 12:31:09.525  4198  4214 D bt_hci  : do_postload posting postload work item
,08-30 12:31:09.525  4198  4218 I bt_hci  : event_postload
,08-30 12:31:09.525  4198  4218 I bt_vendor: sco_config_cb
08-30 12:31:09.525  4198  4218 I bt_hci  : sco_config_callback postload finished.
08-30 12:31:09.530  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:09.530  4198  4214 D bt_bte_conf: Device ID record 1 : primary
08-30 12:31:09.530  4198  4214 D bt_bte_conf:   vendorId            = 000f
08-30 12:31:09.530  4198  4214 D bt_bte_conf:   vendorIdSource      = 0001
08-30 12:31:09.530  4198  4214 D bt_bte_conf:   product             = 1200
,08-30 12:31:09.531  4198  4214 D bt_bte_conf:   version             = 1436
08-30 12:31:09.531  4198  4214 D bt_bte_conf:   clientExecutableURL = 
08-30 12:31:09.531  4198  4214 D bt_bte_conf:   serviceDescription  = 
08-30 12:31:09.531  4198  4214 D bt_bte_conf:   documentationURL    = 
08-30 12:31:09.531  4198  4214 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 12:31:09.532  4198  4211 D bt_stack_manager: event_start_up_stack finished
08-30 12:31:09.533  4198  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 12:31:09.534  4198  4210 D BluetoothAdapterProperties: Setting state to 15
08-30 12:31:09.534  4198  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 12:31:09.534  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:09.534  4198  4210 I BluetoothAdapterState: Entering BleOnState
08-30 12:31:09.534  4198  4218 I bt_vendor: low_power_mode_cb
,08-30 12:31:09.538  4198  4210 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 12:31:09.539  4198  4210 D BluetoothAdapterProperties: Setting state to 11
08-30 12:31:09.539  4198  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 12:31:09.548  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:31:09.549  4198  4198 D HeadsetService: Received start request. Starting profile...
08-30 12:31:09.549  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:09.550  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:09.553  4198  4198 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 12:31:09.554  4198  4198 D HeadsetStateMachine: make
08-30 12:31:09.555  4198  4210 I BluetoothAdapterState: Entering PendingCommandState
,08-30 12:31:09.567  4198  4198 D HeadsetStateMachine: max_hf_connections = 1
08-30 12:31:09.568  4198  4198 I bt_bluedroid: get_profile_interface handsfree
08-30 12:31:09.568  4198  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 12:31:09.568  4198  4214 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-30 12:31:09.572  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
08-30 12:31:09.573  4198  4198 D A2dpService: Received start request. Starting profile...
08-30 12:31:09.573  4198  4198 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 12:31:09.574  4198  4198 I bt_bluedroid: get_profile_interface avrcp
,08-30 12:31:09.580  4198  4198 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 12:31:09.580  4198  4198 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:31:09.581  4198  4198 D A2dpStateMachine: make
08-30 12:31:09.582  4198  4198 I bt_bluedroid: get_profile_interface a2dp
08-30 12:31:09.582  4198  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 12:31:09.583  4198  4231 D A2dpStateMachine: Enter Disconnected: -2
,08-30 12:31:09.584  4198  4198 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 12:31:09.585  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99,
08-30 12:31:09.585  4198  4198 D HidService: Received start request. Starting profile...
,08-30 12:31:09.586  4198  4198 I bt_bluedroid: get_profile_interface hidhost
,08-30 12:31:09.586  4198  4198 D HidService: setHidService(): set to: null
08-30 12:31:09.586  4198  4214 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38f43e5
,08-30 12:31:09.586  4198  4214 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 12:31:09.586  4198  4198 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 12:31:09.587  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:31:09.587  4198  4198 D HealthService: Received start request. Starting profile...
08-30 12:31:09.590  4198  4198 I bt_bluedroid: get_profile_interface health
,08-30 12:31:09.590  4198  4198 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 12:31:09.591  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
08-30 12:31:09.592  4198  4198 D PanService: Received start request. Starting profile...
,08-30 12:31:09.592  4198  4198 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 12:31:09.592  4198  4198 I bt_bluedroid: get_profile_interface pan
,08-30 12:31:09.593  4198  4214 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 12:31:09.595  4198  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:31:09.596  4198  4198 D BluetoothMapService: Received start request. Starting profile...
08-30 12:31:09.596  4198  4198 D BluetoothMapService: start()
,08-30 12:31:09.598  4198  4198 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 12:31:09.599  4198  4198 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 12:31:09.599  4198  4198 D BluetoothMapAppObserver: createReceiver()
,08-30 12:31:09.600  4198  4198 D BluetoothMapAppObserver: initObservers()
08-30 12:31:09.600  4198  4198 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 12:31:09.607  4198  4198 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:31:09.607  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:31:09.607  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 12:31:09.607  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:31:09.607  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:31:09.610  4198  4229 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 12:31:09.610  4198  4198 V BluetoothAdapterState: isTurningOff()=false
08-30 12:31:09.610  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 12:31:09.610  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:31:09.610  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 12:31:09.610  4198  4198 V BluetoothAdapterState: isTurningOff()=false
08-30 12:31:09.610  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 12:31:09.610  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:31:09.610  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:31:09.610  4198  4198 V BluetoothAdapterState: isTurningOff()=false
,08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isTurningOff()=false
08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isTurningOn()=true
,08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isTurningOff()=false
08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isTurningOn()=true
08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isBleTurningOn()=false
08-30 12:31:09.611  4198  4198 V BluetoothAdapterState: isBleTurningOff()=false
08-30 12:31:09.612  4198  4210 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 12:31:09.612  4198  4210 D BluetoothAdapterProperties: ScanMode =  20
08-30 12:31:09.612  4198  4210 D BluetoothAdapterProperties: State =  11
,08-30 12:31:09.612  4198  4210 D BluetoothAdapterProperties: Setting state to 12
08-30 12:31:09.612  4198  4210 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 12:31:09.613  4198  4210 I BluetoothAdapterState: Entering OnState
08-30 12:31:09.613  3908  3918 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 12:31:09.614  4198  4214 D BluetoothAdapterProperties: Scan Mode:21
,08-30 12:31:09.615  4198  4214 D BluetoothAdapterProperties: Discoverable Timeout:120,
08-30 12:31:09.617  1361  1389 D BluetoothPan: onBluetoothStateChange on: true
08-30 12:31:09.618  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:09.618  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:09.618  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:09.618  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:31:09.618  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:09.618  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:09.618  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:09.618  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:31:09.618  3908  3918 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:31:09.619  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:31:09.619   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:31:09.619  1361  1361 D PanProfile: Bluetooth service connected
08-30 12:31:09.619  3908  3920 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:31:09.620  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:31:09.621   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:31:09.621  1361  2049 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:31:09.621   871   871 D BluetoothA2dp: Proxy object connected
08-30 12:31:09.622  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:09.622  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:09.622  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:09.622  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:31:09.622  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:09.622  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:09.622  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:09.622  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:31:09.623  3908  3908 D BluetoothA2dp: Proxy object connected
08-30 12:31:09.623  1361  3973 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:31:09.623  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:31:09.624  1361  1389 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:31:09.624  3908  3908 D BluetoothMap: Proxy object connected
08-30 12:31:09.624  3908  3908 D MapProfile: Bluetooth service connected
08-30 12:31:09.624  3908  3908 D BluetoothMap: getConnectedDevices()
08-30 12:31:09.625  4198  4198 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 12:31:09.626  4198  4198 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 12:31:09.627  1361  1361 D BluetoothMap: Proxy object connected
08-30 12:31:09.627  1361  1361 D MapProfile: Bluetooth service connected
08-30 12:31:09.627  1361  1361 D BluetoothMap: getConnectedDevices()
08-30 12:31:09.627   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:31:09.627  4198  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:31:09.627  1973  2291 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:31:09.628  1361  2049 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:31:09.629  4198  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:31:09.629  4198  4198 D ObexServerSockets: Succeed to create listening sockets 
08-30 12:31:09.629  4198  4198 D ObexServerSockets0: startAccept()
08-30 12:31:09.629  4198  4198 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:31:09.631  3908  3920 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:31:09.631  4198  4198 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 12:31:09.631  4198  4198 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 12:31:09.632  4198  4237 D ObexServerSockets0: Accepting socket connection...
08-30 12:31:09.632  4198  4238 D ObexServerSockets0: Accepting socket connection...
,08-30 12:31:09.633  1361  1361 D BluetoothInputDevice: Proxy object connected
,08-30 12:31:09.633  1361  1361 D HidProfile: Bluetooth service connected
08-30 12:31:09.634   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:31:09.634  3908  3918 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:31:09.635  3908  3908 D BluetoothInputDevice: Proxy object connected
,08-30 12:31:09.635  3908  3908 D HidProfile: Bluetooth service connected
,08-30 12:31:09.636  3908  3920 D BluetoothPan: onBluetoothStateChange on: true
,08-30 12:31:09.638  1361  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:31:09.638  3908  3908 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:31:09.638  3908  3908 D PanProfile: Bluetooth service connected
,08-30 12:31:09.639  1361  1361 D BluetoothA2dp: Proxy object connected
,08-30 12:31:09.641   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 12:31:09.642  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:09.642  4198  4198 D BluetoothMapService: onReceive
08-30 12:31:09.642  4198  4198 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:31:09.642  4198  4198 D BluetoothMapService: STATE_ON
08-30 12:31:09.642  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:09.646  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 12:31:09.652  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:31:09.655  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:31:09.657  3908  3908 D BluetoothPbap: Proxy object connected
,08-30 12:31:09.657  3908  3908 D PbapServerProfile: Bluetooth service connected
,08-30 12:31:09.663  1361  1361 D BluetoothPbap: Proxy object connected
,08-30 12:31:09.663  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-30 12:31:09.665  4198  4245 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:31:09.672  4198  4198 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 12:31:09.672  4198  4198 D ObexServerSockets0: prepareForNewConnect()
,08-30 12:31:09.675  4198  4249 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 12:31:09.676  4198  4249 I BtOppRfcommListener: Accept thread started.
,08-30 12:31:09.723  1361  1389 D BluetoothHeadset: Proxy object connected
,08-30 12:31:09.723  1361  1361 D HeadsetProfile: Bluetooth service connected
08-30 12:31:09.723   871   871 D BluetoothHeadset: Proxy object connected
08-30 12:31:09.723   871   871 D BluetoothHeadset: Proxy object connected
,08-30 12:31:09.723  1973  2147 D BluetoothHeadset: Proxy object connected
08-30 12:31:09.723  1361  1381 D BluetoothHeadset: Proxy object connected
,08-30 12:31:09.723  3908  4239 D BluetoothHeadset: Proxy object connected
,08-30 12:31:09.724   871   871 D BluetoothHeadset: Proxy object connected
08-30 12:31:09.725  3908  3908 D HeadsetProfile: Bluetooth service connected
08-30 12:31:09.725  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-30 12:31:09.729   871   888 D BluetoothHeadset: Proxy object connected
,08-30 12:31:09.730  1973  1984 D BluetoothHeadset: Proxy object connected
,08-30 12:31:09.736   871   888 D BluetoothHeadset: Proxy object connected
,08-30 12:31:12.858  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:12.858  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:12.858  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:12.858  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:31:12.858  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:12.858  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:12.858  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:12.858  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:31:12.865  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:31:12.866  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:12.867  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a891e8 removed from the list
,08-30 12:31:12.867  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:12.867  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:31:12.868  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:12.870  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:31:12.871  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aab0001 added. We now have 4 listener(s)
,08-30 12:31:12.871  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:31:12.875   871  1962 D WifiService: setWifiEnabled: false pid=3819, uid=10000
08-30 12:31:12.875   871  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:31:16.409  1878  1923 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-30 12:31:16.410  1878  1923 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 12:31:16.458  1503  1503 I ConfigService: onCreate
,08-30 12:31:17.888  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:17.889   871  1992 D WifiService: setWifiEnabled: true pid=3819, uid=10000
,08-30 12:31:17.889   871  1992 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:31:17.904   871  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-30 12:31:17.921  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:17.921  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:17.921  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:17.921  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:17.921  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:17.921  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:17.921  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:17.921  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:31:17.928  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:31:17.936  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:17.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:17.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:17.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:17.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:17.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:31:17.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:31:17.936  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:31:17.939   871  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-30 12:31:17.940   871  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 12:31:17.942   871  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-30 12:31:17.942  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:31:17.943   871  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 12:31:17.943   871  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 12:31:17.944   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 12:31:17.944   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 12:31:17.970   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 12:31:17.971   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 12:31:17.972   372   869 D CommandListener: Setting iface cfg
,08-30 12:31:17.973   871  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
08-30 12:31:17.973   871  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 12:31:18.028   871  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 12:31:18.028   871  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 12:31:18.030   871  1306 E native  : do suspend true
,08-30 12:31:18.071   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:31:19.441   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 12:31:19.590   871  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.56 rxSuccessRate=7.25 delta 1000 -> 994
,08-30 12:31:19.594   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 12:31:19.594   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:31:19.621   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 12:31:19.709   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 12:31:19.714  1444  1444 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 12:31:20.195  1444  1444 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 12:31:20.242  1444  1444 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 12:31:20.244  1444  1444 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 12:31:20.249   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 12:31:20.276   871  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:31:20.277   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:31:20.277   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 12:31:20.310   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 12:31:20.329   372   869 D CommandListener: Setting iface cfg
08-30 12:31:20.330   871  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 12:31:20.341   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 12:31:20.399   871  4259 D DhcpClient: Receive thread started
,08-30 12:31:20.500   871  1306 E native  : do suspend false
,08-30 12:31:20.530   871  1843 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 12:31:20.544   871  4259 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-30 12:31:20.546   871  1843 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-30 12:31:20.549   871  1843 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 12:31:20.563   871  4259 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 12:31:20.565   871  1843 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 12:31:20.570   372   869 D CommandListener: Setting iface cfg
,08-30 12:31:20.580   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 12:31:20.583   871  1843 D DhcpClient: Scheduling renewal in 86399s
,08-30 12:31:20.583   871  1306 E native  : do suspend true
,08-30 12:31:20.612   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 12:31:20.617   871  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 12:31:20.619   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 12:31:20.622   871  1308 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 12:31:20.625   871  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 12:31:20.680   871  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 12:31:20.681   871  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 12:31:20.685   871  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 12:31:20.687   871  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 12:31:20.690   871  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 12:31:20.700   871  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 12:31:20.705   871  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 12:31:20.705   871  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 12:31:20.705   871  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 12:31:20.706   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 12:31:20.706   871  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-30 12:31:20.706   871  1308 D ConnectivityService:    accepting network in place of null
08-30 12:31:20.708   871  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 12:31:20.769   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:31:20.817   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 12:31:20.828   871  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 12:31:20.828   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:31:20.839   871   888 D Tethering: MasterInitialState.processMessage what=3
08-30 12:31:20.843   871  4258 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217593, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
08-30 12:31:20.845   871  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 12:31:20.847  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:20.847  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:20.847  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:20.847  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:20.847  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:20.847  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:20.847  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:20.847  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:31:20.851  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:31:20.862  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:20.862  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:20.862  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:20.862  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:20.862  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:20.862  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:20.862  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:20.862  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:20.865  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:31:20.868  1710  1710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 12:31:20.873  1710  1710 D SystemUpdateService: onCreate
,08-30 12:31:20.877  1710  1710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 12:31:20.898  1710  4268 I SystemUpdateService: active receiver: enabled
,08-30 12:31:20.899  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 12:31:20.904  1710  2396 I iu.UploadsManager: num queued entries: 0
,08-30 12:31:20.904  1710  2396 I iu.UploadsManager: num updated entries: 0
,08-30 12:31:20.912  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 12:31:20.913  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 12:31:20.915  3988  3988 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:31:20.928  3988  3988 D SprintDMHelper: simOperator: 
,08-30 12:31:20.928  3988  3988 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 12:31:20.935  1710  4271 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 12:31:20.940  1710  4271 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 12:31:20.958  1710  4271 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 12:31:20.961  1710  4268 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 12:31:20.983  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:31:20.985  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 12:31:20.994   871  4257 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:401b:801::200e
,08-30 12:31:20.997  1710  2396 I iu.SyncManager: NEXT; no task
,08-30 12:31:21.002  1710  4268 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 12:31:21.002  1710  4268 I SystemUpdateService: now status is 0 (complete)
08-30 12:31:21.003  1710  4268 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 12:31:21.003  1710  4268 I SystemUpdateService: file has been verified
08-30 12:31:21.003  1710  4268 I SystemUpdateService: OTA package size = 12249756
,08-30 12:31:21.038  1710  4268 I SystemUpdateService: showing system update notification
,08-30 12:31:21.085   871  4257 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:31:20 GMT], X-Android-Received-Millis=[1472553081085], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472553081053]}
,08-30 12:31:21.086   871  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 12:31:21.086   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 12:31:21.086   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 12:31:21.087  3958  4273 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 12:31:21.091   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 12:31:21.097  1710  1710 D SystemUpdateService: onDestroy
,08-30 12:31:21.111  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 12:31:21.111  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 12:31:21.111  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 12:31:21.111  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 12:31:21.124  1710  4271 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-30 12:31:21.552  1503  1503 I ConfigService: onDestroy
,08-30 12:31:21.825   871  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 12:31:22.916  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:31:22.916  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:22.916  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:22.916  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:22.916  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:22.916  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:22.916  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:22.916  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:22.923  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:31:22.925  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:22.926  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aab0001 removed from the list
08-30 12:31:22.926  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:31:22.927  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:22.927  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:22.939  3819  4280 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-30 12:31:22.939  3819  4280 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 12:31:25.946  3819  4281 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-30 12:31:25.947  3819  4280 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 12:31:25.948  3819  4281 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:31:25.948  3819  4280 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:31:25.949  3819  4281 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:31:25.949  3819  4280 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:31:25.950  3819  4281 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:25.953  3819  4280 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:31:25.953  3819  4281 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 12:31:25.958  3819  4283 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Sender)
,08-30 12:31:25.958  3819  4280 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 12:31:25.959  3819  4286 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Receiver)
,08-30 12:31:25.960  3819  4286 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: OutgoingSocketThread/Receiver)
08-30 12:31:25.960  3819  4286 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-30 12:31:25.960  3819  4286 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 12:31:25.962  3819  4285 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Receiver)
,08-30 12:31:25.963  3819  4285 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: IncomingSocketThread/Receiver)
08-30 12:31:25.963  3819  4285 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-30 12:31:25.963  3819  4285 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 12:31:25.965  3819  4284 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Sender)
,08-30 12:31:28.713   871  1308 D ConnectivityService: handlePromptUnvalidated 102
,08-30 12:31:28.946  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 12:31:28.948  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 12:31:28.955  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d52fa55 Bundle[{}]
,08-30 12:31:28.955  3819  3871 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:31:28.956  3819  3871 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 12:31:28.956  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 12:31:28.957  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 12:31:28.957  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 12:31:28.958  3819  3871 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 12:31:28.962  3819  3871 I System.out: Running OutgoingSocketThread
,08-30 12:31:28.965  3819  4287 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-30 12:31:28.965  3819  4287 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 12:31:31.975  3819  4288 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-30 12:31:31.975  3819  4288 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 12:31:31.976  3819  4287 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 12:31:31.976  3819  4288 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:31:31.976  3819  4287 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-30 12:31:31.977  3819  4287 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:31.977  3819  4288 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:31:31.979  3819  4288 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 12:31:31.983  3819  4287 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:31:31.983  3819  4290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Sender)
08-30 12:31:31.986  3819  4287 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 12:31:31.992  3819  4292 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Sender)
,08-30 12:31:31.995  3819  4291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: IncomingSocketThread/Receiver)
,08-30 12:31:31.996  3819  4293 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: OutgoingSocketThread/Receiver)
,08-30 12:31:31.997  3819  4291 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: IncomingSocketThread/Receiver)
08-30 12:31:31.997  3819  4291 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 12:31:31.997  3819  4291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 12:31:31.998  3819  4293 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: OutgoingSocketThread/Receiver)
08-30 12:31:31.998  3819  4293 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 12:31:31.998  3819  4293 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 12:31:34.977  3819  3871 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
,08-30 12:31:34.979  3819  3871 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 12:31:34.980  3819  3871 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 452)
,08-30 12:31:34.986  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:31:34.986  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6957ea6 added. We now have 3 listener(s)
,08-30 12:31:34.988  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-30 12:31:34.988  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:31:34.988  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:34.989  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:31:34.989  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a1b0e7 added. We now have 4 listener(s)
,08-30 12:31:34.989  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:31:34.989  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:31:34.992  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:31:35.007  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:35.007  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:35.007  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:35.007  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:35.007  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:35.007  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:35.007  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:35.007  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:35.012  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:31:35.012  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:31:35.013  3819  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:31:35.014  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:35.014  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:31:35.014  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:35.014  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:35.015  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:35.015  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 12:31:35.015  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6957ea6 removed from the list
08-30 12:31:35.015  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:35.016  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a1b0e7 removed from the list
,08-30 12:31:35.016  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:35.021  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:35.021  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:31:35.021  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:35.023  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:35.023  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:35.026  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:35.027  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:35.027  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:35.027  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a1b0e7 not in the list
08-30 12:31:35.027  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:35.028  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:35.031  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:35.031  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:35.031  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:35.032  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a1b0e7 not in the list
08-30 12:31:35.032  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:35.032  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:35.033  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:35.033  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6957ea6 not in the list
08-30 12:31:35.035  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:31:35.035  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec69b3d added. We now have 3 listener(s)
08-30 12:31:35.042  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:31:35.042  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:31:35.043  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:35.043  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:31:35.044  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0adf32 added. We now have 4 listener(s)
08-30 12:31:35.044  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:31:35.045  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:31:35.050  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:35.062  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:35.062  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:35.062  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:35.062  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:35.062  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:35.062  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:35.062  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:35.062  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:35.067  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:35.067  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:31:35.068  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:31:35.068  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:31:35.068  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:31:35.068  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:35.068  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:31:35.074  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:35.077  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:31:35.078  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 12:31:35.079  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:35.090  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 12:31:35.092  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 12:31:35.093  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:31:35.105  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 12:31:35.105  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 12:31:35.106  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 12:31:35.108  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:31:35.117  4198  4236 D BtGatt.GattService: registerClient() - UUID=a04413c4-1286-4d6c-a207-c66d36d26c02
,08-30 12:31:35.119  4198  4214 D BtGatt.GattService: onClientRegistered() - UUID=a04413c4-1286-4d6c-a207-c66d36d26c02, clientIf=5
,08-30 12:31:35.121  3819  3831 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 12:31:35.123  4198  4227 D BtGatt.GattService: start scan with filters
,08-30 12:31:35.132  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 12:31:35.132  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 12:31:35.133  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 12:31:35.133  4198  4217 D BtGatt.ScanManager: handling starting scan
,08-30 12:31:35.133  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 12:31:35.138  4198  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c371d99
,08-30 12:31:35.139  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:31:35.140  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 12:31:35.140  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 12:31:35.145  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:31:35.154  4198  4214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 12:31:35.154  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:31:35.156  4198  4217 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:31:35.156  3819  3871 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 12:31:35.157  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:31:35.157  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 12:31:35.157  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:35.158  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 12:31:35.158  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:31:35.158  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:31:35.158  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 12:31:35.159  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:31:35.160  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 12:31:35.160  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 12:31:35.162  3819  3871 D BluetoothAdapter: STATE_ON
08-30 12:31:35.163  4198  4208 D BtGatt.GattService: stopScan() - queue size =1
,08-30 12:31:35.165  4198  4236 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 12:31:35.165  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 12:31:35.165  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 12:31:35.166  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 12:31:35.166  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 12:31:35.166  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 12:31:35.168  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:31:35.169  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 12:31:35.169  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:31:35.170  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:31:35.170  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:35.173  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:31:35.173  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:31:35.174  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:31:35.177  4198  4214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 12:31:35.177  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:31:35.178  4198  4217 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 12:31:35.178  4198  4217 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 12:31:35.198  4198  4214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 12:31:35.198  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:31:35.209  4198  4214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:31:35.209  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:31:35.233  4198  4214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 12:31:35.233  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:31:35.234  4198  4217 D BtGatt.ScanManager: stopping BLe Batch
,08-30 12:31:35.254  4198  4214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 12:31:35.254  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:31:35.255  4198  4217 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:31:35.278  4198  4214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 12:31:35.278  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:31:35.674  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:31:35.675  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:35.675  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:31:38.174  3819  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:31:38.174  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:38.174  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:31:38.175  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:38.175  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:31:38.176  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:38.176  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 12:31:38.177  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec69b3d removed from the list
08-30 12:31:38.177  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:38.177  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0adf32 removed from the list
08-30 12:31:38.178  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:38.178  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:38.179  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:38.180  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:38.183  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 12:31:38.183  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:38.184  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 12:31:38.184  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0adf32 not in the list
08-30 12:31:38.184  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:31:38.184  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:38.188  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:31:38.188  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:38.188  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:38.189  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0adf32 not in the list
,08-30 12:31:38.189  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-30 12:31:38.189  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:38.190  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:38.190  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec69b3d not in the list
08-30 12:31:38.192  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:31:38.193  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f79d5df added. We now have 3 listener(s)
,08-30 12:31:38.199  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:31:38.200  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:31:38.200  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:38.200  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:31:38.201  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84322c added. We now have 4 listener(s)
08-30 12:31:38.201  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:31:38.202  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:31:38.208  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:31:38.218  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:38.218  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:38.218  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:38.218  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:38.218  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:38.218  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:38.218  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:38.218  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:38.224  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:31:38.224  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:31:38.225  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 12:31:38.226  3819  3871 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,08-30 12:31:38.227  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
08-30 12:31:38.227  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 12:31:38.227  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-30 12:31:38.228  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 12:31:38.228  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:31:38.230  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:38.232  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 12:31:38.233  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 12:31:38.234  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 12:31:38.234  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:31:38.234  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-30 12:31:38.234  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:38.235  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:31:38.235  3819  4294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:31:38.237  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:38.238  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:31:38.243  3819  4294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 12:31:38.244  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 12:31:38.244  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:31:38.252  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:31:38.254  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 12:31:38.254  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:31:38.257  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 12:31:38.258  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:31:38.258  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
08-30 12:31:38.258  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 12:31:38.258  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 12:31:38.258  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 12:31:38.259  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:31:38.265  4198  4208 D BtGatt.GattService: registerClient() - UUID=8723d807-fbea-486f-99c4-39070c3a8c5e
08-30 12:31:38.265  4198  4214 D BtGatt.GattService: onClientRegistered() - UUID=8723d807-fbea-486f-99c4-39070c3a8c5e, clientIf=5
,08-30 12:31:38.266  3819  3830 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 12:31:38.270  4198  4216 D BtGatt.AdvertiseManager: message : 0
,08-30 12:31:38.275  4198  4216 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 12:31:38.294  4198  4214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 12:31:38.304  4198  4214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 12:31:38.306  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 12:31:38.306  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 12:31:38.312  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:31:38.314  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 12:31:38.315  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-30 12:31:38.315  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 12:31:38.316  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 12:31:38.316  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-30 12:31:38.316  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 12:31:38.322  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 12:31:38.327  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 12:31:38.328  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 12:31:38.829  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 12:31:38.830  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 12:31:38.830  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,08-30 12:31:41.323  3819  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:31:41.324  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-30 12:31:41.324  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 12:31:41.324  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 12:31:41.325  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 12:31:41.325  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 12:31:41.326  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 12:31:41.326  3819  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:31:41.326  3819  4294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 12:31:41.326  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:31:41.326  3819  4294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 12:31:41.326  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 12:31:41.327  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:31:41.327  3819  4294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 12:31:41.327  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:31:41.327  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:31:41.328  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 12:31:41.330  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:31:41.331  3819  3871 D BluetoothLeScanner: could not find callback wrapper
08-30 12:31:41.331  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:31:41.331  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 12:31:41.334  4198  4216 D BtGatt.AdvertiseManager: message : 1
08-30 12:31:41.336  4198  4216 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 12:31:41.347  4198  4214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0,
08-30 12:31:41.347  4198  4214 D BtGatt.GattService: Client app is not null!
,08-30 12:31:41.349  4198  4240 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 12:31:41.350  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 12:31:41.350  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 12:31:41.350  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-30 12:31:41.350  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-30 12:31:41.351  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-30 12:31:41.352  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:31:41.353  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 12:31:41.353  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:31:41.354  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 12:31:41.356  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:31:41.356  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:41.357  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:41.357  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:31:41.357  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f79d5df removed from the list
,08-30 12:31:41.357  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:41.357  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84322c removed from the list
08-30 12:31:41.357  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:41.358  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:41.359  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 12:31:41.359  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:31:41.359  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:31:41.360  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:41.360  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 12:31:41.360  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:41.362  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:41.363  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:41.363  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:41.363  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84322c not in the list
,08-30 12:31:41.363  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:41.364  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:41.366  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:41.366  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:41.367  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:41.367  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84322c not in the list
08-30 12:31:41.367  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:31:41.367  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:41.368  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:41.368  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f79d5df not in the list
,08-30 12:31:41.370  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:31:41.370  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff2eb71 added. We now have 3 listener(s)
,08-30 12:31:41.376  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 12:31:41.377  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:31:41.377  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:41.377  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:31:41.378  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@890dd56 added. We now have 4 listener(s)
08-30 12:31:41.378  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:31:41.379  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:31:41.383  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:31:41.391  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:41.391  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:41.391  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:41.391  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:41.391  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:41.391  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:41.391  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:41.391  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:41.395  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:31:41.395  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:31:41.395  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 12:31:41.396  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:31:41.396  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 12:31:41.396  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:41.396  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:31:41.400  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:41.401  3819  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 12:31:41.401  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:31:41.407  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:41.407  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 12:31:41.409  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 12:31:41.409  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:31:41.415  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 12:31:41.415  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 12:31:41.416  3819  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 12:31:41.417  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:31:41.421  4198  4240 D BtGatt.GattService: registerClient() - UUID=cda3cb72-8cbf-45b2-bfbb-9ae538100db8
,08-30 12:31:41.421  4198  4214 D BtGatt.GattService: onClientRegistered() - UUID=cda3cb72-8cbf-45b2-bfbb-9ae538100db8, clientIf=5
08-30 12:31:41.422  3819  3867 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 12:31:41.422  4198  4209 D BtGatt.GattService: start scan with filters
,08-30 12:31:41.430  4198  4217 D BtGatt.ScanManager: handling starting scan
,08-30 12:31:41.430  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 12:31:41.430  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 12:31:41.430  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 12:31:41.431  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 12:31:41.439  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:31:41.440  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 12:31:41.440  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 12:31:41.444  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 12:31:41.447  4198  4214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 12:31:41.447  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:31:41.448  4198  4217 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 12:31:41.462  4198  4214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 12:31:41.462  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:31:41.463  4198  4217 D BtGatt.ScanManager: Starting BLE batch scan
08-30 12:31:41.463  4198  4217 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 12:31:41.487  4198  4214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 12:31:41.488  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:31:41.500  4198  4214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 12:31:41.500  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:31:41.861  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:31:41.940  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 12:31:41.940  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:31:41.941  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 12:31:43.006  4198  4198 D BtGatt.ScanManager: awakened up at time 239756
,08-30 12:31:43.011  4198  4217 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 12:31:43.081  4198  4214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=10
08-30 12:31:43.081  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:31:43.081  4198  4214 D BtGatt.GattService: current time is 239832355236
08-30 12:31:43.082  4198  4214 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -63, -37, -36, 4, 105, 93, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -112, -25, -60, -2, -84, -17, 0, 81, 34, 97, 112, -14, -5, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 51, 57, -85, 11, 100, 121, 1, -128, -58, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 124, -7, 14, 52, -118, -96, 0, 116, -43, -111, -91, -20, -29, 1, -128, -98, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 53, 33, -121, 80, 73, -44, 1, 0, -106, 28, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -75, -69, -18, 2, 2, -29, 21, 63, -112, 84, 79, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 51, 57, -85, 11, 100, 121, 1, -128, -58, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 124, -7, 14, 52, -118, -96, 0]
08-30 12:31:43.083  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-30 12:31:43.084  4198  4214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, -112, -25, -60, -2, -84, -17]
08-30 12:31:43.084  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 12:31:43.085  4198  4214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 124, -7, 14, 52, -118, -96]
08-30 12:31:43.085  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-30 12:31:43.085  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -75, -69, -18, 2, 2, -29, 21, 63, -112, 84, 79, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -,38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-30 12:31:43.085  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 12:31:43.085  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 12:31:43.086  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 12:31:43.086  4198  4214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 124, -7, 14, 52, -118, -96]
08-30 12:31:43.091  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 90:E7:C4:FE:AC:EF 4], added - the peer count is 1
,08-30 12:31:43.093  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 4], added - the peer count is 2
,08-30 12:31:43.095  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 4] updated - the peer count is 2
,08-30 12:31:43.097  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 90:E7:C4:FE:AC:EF 4], Bluetooth address: 90:E7:C4:FE:AC:EF, device name: '', device address: ''
,08-30 12:31:43.098  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 4], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-30 12:31:43.912  1503  2122 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 12:31:44.462  3819  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:31:44.463  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:44.463  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 12:31:44.463  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:44.464  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 12:31:44.464  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:31:44.464  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:31:44.464  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:31:44.465  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:31:44.465  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 12:31:44.465  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 12:31:44.468  3819  3871 D BluetoothAdapter: STATE_ON
,08-30 12:31:44.470  4198  4241 D BtGatt.GattService: stopScan() - queue size =1
,08-30 12:31:44.474  4198  4236 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 12:31:44.475  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:31:44.475  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 12:31:44.476  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 12:31:44.476  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 12:31:44.476  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 12:31:44.482  4198  4198 D BtGatt.ScanManager: awakened up at time 241232
,08-30 12:31:44.482  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:31:44.482  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 12:31:44.483  3819  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:31:44.483  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:31:44.487  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:44.487  3819  3871 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-30 12:31:44.491  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:44.491  4198  4214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 12:31:44.491  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:44.491  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:31:44.491  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:31:44.491  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:44.492  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:31:44.492  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 12:31:44.492  4198  4217 D BtGatt.ScanManager: stopping BLe Batch
08-30 12:31:44.492  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:31:44.492  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff2eb71 removed from the list
08-30 12:31:44.492  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:44.493  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@890dd56 removed from the list
08-30 12:31:44.493  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:31:44.493  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:44.495  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:44.495  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:44.499  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:44.499  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:44.500  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:44.500  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@890dd56 not in the list
08-30 12:31:44.500  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:44.501  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:44.504  4198  4214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 12:31:44.504  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 12:31:44.504  4198  4217 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 12:31:44.504  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:44.504  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:44.504  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:44.505  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@890dd56 not in the list
08-30 12:31:44.505  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 12:31:44.505  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:44.505  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:44.506  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff2eb71 not in the list
08-30 12:31:44.508  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 12:31:44.508  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d6412e added. We now have 3 listener(s)
,08-30 12:31:44.513  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 12:31:44.514  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 12:31:44.514  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:31:44.514  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:31:44.514  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba9f4cf added. We now have 4 listener(s)
08-30 12:31:44.514  3819  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:31:44.515  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:31:44.517  4198  4214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-30 12:31:44.517  4198  4214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 12:31:44.517  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:31:44.517  4198  4214 D BtGatt.GattService: current time is 241268402012
08-30 12:31:44.518  4198  4214 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -90, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
08-30 12:31:44.518  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 12:31:44.518  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 12:31:44.518  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 12:31:44.519  4198  4214 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-30 12:31:44.522  3819  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:31:44.522  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:31:44.522  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:31:44.522  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:31:44.522  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:31:44.522  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:44.522  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:31:44.522  3819  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:31:44.523  3819  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:31:44.524  3819  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:31:44.524  3819  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:31:44.524  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:31:44.524  3819  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:31:44.524  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:44.524  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:44.525  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:31:44.525  3819  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:31:44.525  3819  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d6412e removed from the list
08-30 12:31:44.525  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:44.525  3819  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba9f4cf removed from the list
08-30 12:31:44.526  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:31:44.526  3819  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:31:44.526  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:44.527  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:31:44.527  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:31:44.528  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:44.528  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:44.529  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:44.529  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba9f4cf not in the list
08-30 12:31:44.529  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:31:44.529  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:44.529  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:31:44.530  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:31:44.530  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:31:44.530  3819  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:31:44.530  3819  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba9f4cf not in the list
08-30 12:31:44.530  3819  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:31:44.530  3819  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 12:31:44.530  3819  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:31:44.530  3819  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d6412e not in the list
08-30 12:31:44.531  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 12:31:44.532  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 12:31:44.532  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 12:31:44.532  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:31:44.532  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 12:31:44.532  3819  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:31:44.993  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:31:46.547  3819  4295 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
,08-30 12:31:48.387   871  4258 D NetlinkSocketObserver: NeighborEvent{elapsedMs=245137, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 12:31:48.545  3819  3871 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 461
,08-30 12:31:48.545  3819  3871 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 461, name: My test thread name)
,08-30 12:31:48.558  3819  4297 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: My test thread name)
,08-30 12:31:48.558  3819  4297 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 462, thread name: My test thread name)
,08-30 12:31:48.559  3819  4297 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 12:31:48.566  3819  3871 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:31:48.573  3819  4298 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: My test thread name)
,08-30 12:31:48.574  3819  4298 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 466, thread name: My test thread name): Test exception.
08-30 12:31:48.574  3819  4298 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 466, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 12:31:48.582  3819  3871 I jxcore-log: Total number of executed tests:  82
08-30 12:31:48.582  3819  3871 I jxcore-log: 
,08-30 12:31:48.583  3819  3871 I jxcore-log: Number of passed tests:  82
08-30 12:31:48.583  3819  3871 I jxcore-log: 
08-30 12:31:48.583  3819  3871 I jxcore-log: Number of failed tests:  0
08-30 12:31:48.583  3819  3871 I jxcore-log: 
,08-30 12:31:48.586  3819  3871 I jxcore-log: Number of ignored tests:  0
08-30 12:31:48.586  3819  3871 I jxcore-log: 
,08-30 12:31:48.586  3819  3871 I jxcore-log: Total duration:  111494
08-30 12:31:48.586  3819  3871 I jxcore-log: 
,08-30 12:31:48.591  3819  3871 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 12:31:48.591  3819  3871 I jxcore-log: 
,08-30 12:31:48.594  3819  3871 I jxcore-log: My device name is: motorola-Nexus 6
08-30 12:31:48.594  3819  3871 I jxcore-log: 
08-30 12:31:48.603  3819  3871 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 12:31:48.603  3819  3871 I jxcore-log: 
,08-30 12:31:48.611  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.611  3819  3871 I jxcore-log: 
,08-30 12:31:48.612  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.612  3819  3871 I jxcore-log: 
,08-30 12:31:48.613  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.613  3819  3871 I jxcore-log: 
,08-30 12:31:48.616  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 12:31:48.616  3819  3871 I jxcore-log: 
,08-30 12:31:48.623  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.623  3819  3871 I jxcore-log: 
,08-30 12:31:48.628  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 12:31:48.628  3819  3871 I jxcore-log: 
,08-30 12:31:48.632  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 12:31:48.632  3819  3871 I jxcore-log: 
,08-30 12:31:48.635  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 12:31:48.635  3819  3871 I jxcore-log: 
,08-30 12:31:48.641  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 12:31:48.641  3819  3871 I jxcore-log: 
,08-30 12:31:48.645  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 12:31:48.645  3819  3871 I jxcore-log: 
08-30 12:31:48.646  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:31:48.646  3819  3871 I jxcore-log: 
08-30 12:31:48.648  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.648  3819  3871 I jxcore-log: 
,08-30 12:31:48.650  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 12:31:48.650  3819  3871 I jxcore-log: 
,08-30 12:31:48.652  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:31:48.652  3819  3871 I jxcore-log: 
,08-30 12:31:48.654  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:31:48.654  3819  3871 I jxcore-log: 
,08-30 12:31:48.655  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.655  3819  3871 I jxcore-log: 
,08-30 12:31:48.656  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.656  3819  3871 I jxcore-log: 
,08-30 12:31:48.656  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.656  3819  3871 I jxcore-log: 
,08-30 12:31:48.657  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:48.657  3819  3871 I jxcore-log: 
,08-30 12:31:48.659  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:48.659  3819  3871 I jxcore-log: 
,08-30 12:31:48.660  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:48.660  3819  3871 I jxcore-log: 
,08-30 12:31:48.661  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.661  3819  3871 I jxcore-log: ,
,08-30 12:31:48.662  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.662  3819  3871 I jxcore-log: 
,08-30 12:31:48.663  3819  4295 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,08-30 12:31:48.663  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.663  3819  3871 I jxcore-log: 
,08-30 12:31:48.665  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:48.665  3819  3871 I jxcore-log: 
,08-30 12:31:48.667  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:31:48.667  3819  3871 I jxcore-log: 
,08-30 12:31:48.668  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-30 12:31:48.668  3819  3871 I jxcore-log: 
,08-30 12:31:48.669  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-30 12:31:48.669  3819  3871 I jxcore-log: 
08-30 12:31:48.670  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.670  3819  3871 I jxcore-log: ,
08-30 12:31:48.671  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-30 12:31:48.671  3819  3871 I jxcore-log: 
08-30 12:31:48.673  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.673  3819  3871 I jxcore-log: 
,08-30 12:31:48.674  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.674  3819  3871 I jxcore-log: 
08-30 12:31:48.675  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.675  3819  3871 I jxcore-log: ,
,08-30 12:31:48.676  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.676  3819  3871 I jxcore-log: 
,08-30 12:31:48.677  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.677  3819  3871 I jxcore-log: 
,08-30 12:31:48.678  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.678  3819  3871 I jxcore-log: 
,08-30 12:31:48.679  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.679  3819  3871 I jxcore-log: 
,08-30 12:31:48.680  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.680  3819  3871 I jxcore-log: 
,08-30 12:31:48.681  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.681  3819  3871 I jxcore-log: 
,08-30 12:31:48.682  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.682  3819  3871 I jxcore-log: 
,08-30 12:31:48.684  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.684  3819  3871 I jxcore-log: 
,08-30 12:31:48.686  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:31:48.686  3819  3871 I jxcore-log: 
,08-30 12:31:48.687  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 12:31:48.687  3819  3871 I jxcore-log: 
,08-30 12:31:48.689  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 12:31:48.689  3819  3871 I jxcore-log: 
,08-30 12:31:48.690  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.690  3819  3871 I jxcore-log: 
,08-30 12:31:48.691  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.691  3819  3871 I jxcore-log: 
,08-30 12:31:48.693  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.693  3819  3871 I jxcore-log: 
,08-30 12:31:48.694  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.694  3819  3871 I jxcore-log: 
,08-30 12:31:48.694  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.694  3819  3871 I jxcore-log: 
,08-30 12:31:48.696  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:31:48.696  3819  3871 I jxcore-log: 
,08-30 12:31:48.696  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-30 12:31:48.696  3819  3871 I jxcore-log: 
,08-30 12:31:48.697  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 12:31:48.697  3819  3871 I jxcore-log: 
,08-30 12:31:48.698  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.698  3819  3871 I jxcore-log: 
,08-30 12:31:48.698  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:31:48.698  3819  3871 I jxcore-log: 
,08-30 12:31:48.699  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 12:31:48.699  3819  3871 I jxcore-log: 
,08-30 12:31:48.700  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 12:31:48.700  3819  3871 I jxcore-log: 
,08-30 12:31:48.700  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 12:31:48.700  3819  3871 I jxcore-log: 
,08-30 12:31:48.701  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:31:48.701  3819  3871 I jxcore-log: 
,08-30 12:31:48.702  3819  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:31:48.702  3819  3871 I jxcore-log: 
,08-30 12:31:49.250  4299  4299 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 12:31:49.259  4299  4299 D AndroidRuntime: CheckJNI is OFF
,08-30 12:31:49.308  4299  4299 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 12:31:49.384  4299  4299 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 12:31:49.415  4299  4299 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 12:31:49.428   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 12:31:49.429   871   884 I ActivityManager: Killing 3819:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 12:31:49.509   871   894 W PackageSettings: Skipping PackageSetting{b6bc3e2 com.example.hello/10273} due to missing metadata
,08-30 12:31:49.524   871  1962 I WindowState: WIN DEATH: Window{ab9f0e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:31:49.526   871  1992 D GraphicsStats: Buffer count: 2
,08-30 12:31:49.528   871  1307 D WifiService: Client connection lost with reason: 4
,08-30 12:31:49.555   871   894 I art     : Starting a blocking GC Explicit
,08-30 12:31:49.569   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-30 12:31:49.570   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 12:31:49.571   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-30 12:31:49.571   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 12:31:49.571   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:49.571   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:31:49.571   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:31:49.571   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 12:31:49.571   871   884 I ActivityManager:   Force finishing activity ActivityRecord{48f3e4f u0 com.test.thalitest/.MainActivity t2}
,08-30 12:31:49.587   871  1970 W ActivityManager: Spurious death for ProcessRecord{6ee6ca4 0:com.test.thalitest/u0a0}, curProc for 3819: null
,08-30 12:31:49.629   871   894 I art     : Explicit concurrent mark sweep GC freed 21134(1335KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 868us total 72.297ms
,08-30 12:31:49.656   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 12:31:49.661  4299  4299 I art     : System.exit called, status: 0
,08-30 12:31:49.661  4299  4299 I AndroidRuntime: VM exiting with result code 0.
,08-30 12:31:49.672   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 12:31:49.683   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 12:31:49.688  4198  4198 D BluetoothMapAppObserver: onReceive
,08-30 12:31:49.688  4198  4198 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 12:31:49.692  1894  2238 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 12:31:49.697  1878  1878 I Keyboard.Facilitator: resetDictionaries() : en_US
08-30 12:31:49.697  3675  3675 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 12:31:49.702   871  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:31:49.720  1878  4311 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 12:31:49.734  1878  4311 I Decoder : createOrResetDecoder
,08-30 12:31:49.743   871   881 I ActivityManager: Start proc 4314:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 12:31:49.746  1973  1973 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 12:31:49.764  1503  1503 I ConfigService: onCreate
,08-30 12:31:49.806   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 12:31:49.808  1878  4311 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 12:31:49.810  4314  4314 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 12:31:49.816   871  1687 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3819 uid 10000
,08-30 12:31:49.817  1878  1878 I Keyboard.Facilitator: onFinishInput()
,08-30 12:31:49.841  1987  2064 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 12:31:49.841   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-30 12:31:49.841   871   883 E PackageManager: Failed to write settings, restoring backup
08-30 12:31:49.841   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 12:31:49.841   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 12:31:49.841   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 12:31:49.841   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 12:31:49.841   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 12:31:49.841   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:49.841   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:31:49.841   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:31:49.846   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-30 12:31:49.846   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 12:31:49.846   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:31:49.846   871   884 E DropBoxManagerService: 	... 13 more
,08-30 12:31:49.854   871  1970 I ActivityManager: Start proc 4330:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 12:31:49.855  1987  2064 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 12:31:49.855  1987  2064 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1987
08-30 12:31:49.855  1987  2064 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:31:49.855  1987  2064 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:31:49.857   871  1382 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 12:31:49.858   871  4336 E DropBoxManagerService: Can't write: system_app_crash
08-30 12:31:49.858   871  4336 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:31:49.858   871  4336 E DropBoxManagerService: 	... 5 more
,08-30 12:31:49.909  1987  2064 I Process : Sending signal. PID: 1987 SIG: 9
,08-30 12:31:49.932  1878  4311 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 12:31:49.934  1878  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 12:31:49.934  1878  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 12:31:49.938  4314  4314 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 12:31:49.941  1878  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 12:31:49.941  1878  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 12:31:49.944  1878  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 12:31:49.944  1878  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 12:31:49.969  1878  4311 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-30 12:31:49.970  1878  4311 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 12:31:49.970  1878  4311 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 12:31:49.970  1878  4311 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 12:31:49.970  1878  4311 I StatsUtilsManager: startPeriodStatsRecorder() : Success,
08-30 12:31:49.970  1878  4311 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 12:31:50.010  4314  4347 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 12:31:50.016   871   881 I ActivityManager: Start proc 4348:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 12:31:50.039  4314  4347 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:31:50.039  4314  4347 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:31:50.044  4314  4347 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 12:31:50.044  4314  4347 E AndroidRuntime: Process: android.process.acore, PID: 4314
08-30 12:31:50.044  4314  4347 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:31:50.044  4314  4347 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:31:50.047   871  4361 E DropBoxManagerService: Can't write: system_app_crash
08-30 12:31:50.047   871  4361 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 12:31:50.047   871  4361 E DropBoxManagerService: 	... 5 more
,08-30 12:31:50.049  4314  4347 I Process : Sending signal. PID: 4314 SIG: 9
,08-30 12:31:50.053   278   278 E lowmemorykiller: Error writing /proc/4314/oom_score_adj; errno=22
,08-30 12:31:50.060  1710  4353 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 12:31:50.061  1710  4353 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 12:31:50.071   871  1416 I WindowState: WIN DEATH: Window{1fbb465 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-30 12:31:50.071   871  1992 D GraphicsStats: Buffer count: 1
,08-30 12:31:50.081  4348  4348 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 12:31:50.082   871  1382 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1987) has died
08-30 12:31:50.082   871  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-30 12:31:50.087   871  1382 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 12:31:50.106   871   884 I ActivityManager: Start proc 4362:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 12:31:50.123   871   889 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
08-30 12:31:50.123   871   889 W DisplayManagerService: Failed to notify process 4314 that displays changed, assuming it died.
08-30 12:31:50.123   871   889 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:31:50.123   871   889 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 12:31:50.127   871  1957 I ActivityManager: Process android.process.acore (pid 4314) has died
,08-30 12:31:50.127   871  1957 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-30 12:31:50.138  1503  1503 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 12:31:50.141  1503  1503 D AndroidRuntime: Shutting down VM
,08-30 12:31:50.143   871  1687 I ActivityManager: Killing 3728:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 12:31:50.146  1503  1503 E AndroidRuntime: FATAL EXCEPTION: main
08-30 12:31:50.146  1503  1503 E AndroidRuntime: Process: com.google.process.gapps, PID: 1503
08-30 12:31:50.146  1503  1503 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 12:31:50.146  1503  1503 E AndroidRuntime: 	... 8 more
,08-30 12:31:50.164  4362  4362 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 12:31:50.164  4362  4362 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 12:31:50.164  4362  4362 D AndroidRuntime: Shutting down VM
,08-30 12:31:50.168   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
