#### Test 846186378dcb506_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 15:08:39.674   875  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=117598, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:08:40.389  3809  3809 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 15:08:40.393  3809  3809 D AndroidRuntime: CheckJNI is OFF
09-09 15:08:40.429  3809  3809 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 15:08:40.472  3809  3809 I Radio-JNI: register_android_hardware_Radio DONE
09-09 15:08:40.493  3809  3809 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 15:08:40.498   875  2021 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 15:08:40.544  2007  2185 W SearchService: Abort, client detached.
09-09 15:08:40.550  3809  3809 D AndroidRuntime: Shutting down VM
09-09 15:08:40.560  2007  2318 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@941999f
09-09 15:08:40.560  2007  2007 I HotwordDetector: Closing mic
09-09 15:08:40.561  2007  2344 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 15:08:40.583   875  1391 I ActivityManager: Start proc 3819:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 15:08:40.623   377  2346 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 15:08:40.624   377  2346 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 15:08:40.633   377  1288 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 15:08:40.635  2007  2329 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 15:08:40.635  2007  2343 I MicroRecognitionRnrImpl: Detection finished
09-09 15:08:40.676  3819  3819 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 15:08:40.705  3819  3819 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 15:08:40.713  3819  3819 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8635-8638)
09-09 15:08:40.714  3819  3819 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 15:08:40.735  3819  3819 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {311e38e}
09-09 15:08:40.736  3819  3819 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 15:08:40.736  3819  3819 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 15:08:40.743  3819  3819 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 15:08:40.745  3819  3819 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 15:08:40.766  3819  3819 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 15:08:40.787  3819  3819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 15:08:40.788  3819  3819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 15:08:40.788  3819  3819 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 15:08:40.788  3819  3819 I Adreno  : Build Date                       : 10/20/15
09-09 15:08:40.788  3819  3819 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 15:08:40.788  3819  3819 I Adreno  : Local Branch                     : M14
09-09 15:08:40.788  3819  3819 I Adreno  : Remote Branch                    : 
09-09 15:08:40.788  3819  3819 I Adreno  : Remote Branch                    : 
09-09 15:08:40.788  3819  3819 I Adreno  : Reconstruct Branch               : 
09-09 15:08:40.851   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b74da9:true
09-09 15:08:40.937  3819  3819 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 15:08:40.954  3819  3819 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-09 15:08:41.013  3819  3859 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-09 15:08:41.023  3819  3845 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-09 15:08:41.066  3819  3859 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 15:08:41.145   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +592ms
09-09 15:08:41.148  1878  1878 I Keyboard.Facilitator: onFinishInput()
09-09 15:08:41.225  3819  3819 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3819
09-09 15:08:41.406   875  1915 I ActivityManager: Killing 3215:com.google.android.gm/u0a78 (adj 15): empty #17
09-09 15:08:41.413  3819  3819 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-09 15:08:41.444   875  1915 I ActivityManager: Killing 2980:com.google.android.calendar/u0a37 (adj 15): empty #18
09-09 15:08:41.700  3819  3861 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1680410320
09-09 15:08:41.716  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 15:08:41.716  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 15:08:41.716  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 15:08:41.716  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 15:08:41.716  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 15:08:41.716  3819  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8e1b2 added. We now have 1 listener(s)
09-09 15:08:41.724  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-09 15:08:41.725  3819  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 15:08:41.726  3819  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 15:08:41.727  3819  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 15:08:41.744  3819  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65472b9 added. We now have 1 listener(s)
09-09 15:08:41.745  3819  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 15:08:41.749   875  1317 D WifiService: New client listening to asynchronous messages
09-09 15:08:41.750  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 15:08:41.750  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 15:08:41.751  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 15:08:41.751  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 15:08:41.751  3819  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 15:08:41.756  3819  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 15:08:41.756  3819  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-09 15:08:41.763  3819  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-09 15:08:41.763  3819  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:08:41.763  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:08:41.763  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:08:41.763  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:08:41.763  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:08:41.763  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:08:41.763  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:08:41.763  3819  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 15:08:41.763  3819  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 15:08:41.763  3819  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 15:08:41.764  3819  3861 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 15:08:41.808  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:08:41.810  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:08:41.812  3819  3819 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-09 15:08:42.299  3819  3828 I art     : Background sticky concurrent mark sweep GC freed 72097(6MB) AllocSpace objects, 17(1308KB) LOS objects, 29% free, 23MB/32MB, paused 672us total 148.070ms
,09-09 15:08:42.964  3819  3872 W jxcore-log: Initializing JXcore engine
,09-09 15:08:42.964  3819  3872 W jxcore-log: JXcore engine is ready
,09-09 15:08:42.996  3872  3872 W Thread-331: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 15:08:42.996  3872  3872 W Thread-331: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9634]" dev="sockfs" ino=9634 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 15:08:42.996  3872  3872 W Thread-331: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 15:08:42.996  3872  3872 W Thread-331: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26228]" dev="sockfs" ino=26228 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 15:08:43.010  3819  3872 W jxcore-log: Starting JXcore engine
,09-09 15:08:43.087  3819  3872 W jxcore-log: Platform android
09-09 15:08:43.087  3819  3872 W jxcore-log: 
09-09 15:08:43.087  3819  3872 W jxcore-log: Process ARCH arm
09-09 15:08:43.087  3819  3872 W jxcore-log: 
,09-09 15:08:43.274  3819  3872 I jxcore-log: JXcore Cordova bridge is ready!
09-09 15:08:43.274  3819  3872 I jxcore-log: 
,09-09 15:08:43.274  3819  3872 W jxcore-log: JXcore engine is started
,09-09 15:08:43.283  3819  3861 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 15:08:43.290  3819  3819 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 15:08:43.924   875  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 15:08:50.176  3603  3879 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 15:08:50.196  3603  3880 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 15:08:50.209  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:08:50.215  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:08:50.249  1542  2197 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 15:08:50.249  1542  2197 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 15:08:50.249  1542  2197 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:08:50.249  1542  2197 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:08:50.293  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:08:50.296  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:08:50.342  1542  3056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 15:08:50.343  1542  3056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 15:08:50.343  1542  3056 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:08:50.343  1542  3056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:08:50.365  3603  3880 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:08:50.367  3603  3879 E BooksSync: Soft error
09-09 15:08:50.367  3603  3879 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:08:50.367  3603  3879 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 15:08:50.367  3603  3879 E BooksSync: Sync error
09-09 15:08:50.367  3603  3879 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:08:50.367  3603  3879 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 15:08:50.367  3603  3879 I BooksSync: Finished books sync
,09-09 15:08:50.375   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128069, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:08:50.841  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:08:50.847  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 15:08:50.848  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:08:50.867  1542  2303 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 15:08:50.867  1542  2303 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 15:08:50.868  1542  2303 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:08:50.868  1542  2303 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:08:50.880  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 15:08:50.880  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 15:08:50.881  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-09 15:08:57.503  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 15:08:57.503  3819  3872 I jxcore-log: 
,09-09 15:08:57.506  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 15:08:57.506  3819  3872 I jxcore-log: 
,09-09 15:08:57.516  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:08:57.516  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:08:57.516  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:08:57.516  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:08:57.516  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:08:57.516  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:08:57.516  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:08:57.516  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:08:57.521  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:08:57.523  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 15:08:57.523  3819  3872 I jxcore-log: 
,09-09 15:08:57.525  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 15:08:57.525  3819  3872 I jxcore-log: 
,09-09 15:08:57.882  3819  3872 I jxcore-log: Running unit tests
09-09 15:08:57.882  3819  3872 I jxcore-log: 
,09-09 15:08:57.883  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 15:08:57.883  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f20ae32 added. We now have 2 listener(s)
09-09 15:08:57.884  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 15:08:57.884  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 15:08:57.884  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 15:08:57.884  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 15:08:57.884  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a99783 added. We now have 2 listener(s)
09-09 15:08:57.884  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 15:08:57.885  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 15:08:57.890  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:08:57.906  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:08:57.906  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:08:57.906  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:08:57.906  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:08:57.906  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:08:57.906  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:08:57.906  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:08:57.906  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:08:57.910  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:08:57.911  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 15:08:57.913  3819  3872 D executeNativeTests: Running unit tests
,09-09 15:08:57.917  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:08:57.922  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:08:57.996  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 15:08:57.996  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 added. We now have 3 listener(s)
,09-09 15:08:57.997  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 15:08:57.997  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 15:08:57.997  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 15:08:57.997  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 15:08:57.998  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e added. We now have 3 listener(s)
09-09 15:08:57.998  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:08:57.998  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 15:08:58.004  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:08:58.016  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:08:58.016  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:08:58.016  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:08:58.016  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:08:58.016  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:08:58.016  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:08:58.016  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:08:58.016  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:08:58.020  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:08:58.020  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 15:08:58.023  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 15:08:58.024  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 15:08:58.025  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 15:08:58.025  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 15:08:58.025  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:08:58.027  3819  3872 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 15:08:58.027  3819  3872 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 15:08:58.027  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 15:08:58.027  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 15:08:58.027  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 15:08:58.028  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 15:08:58.028  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:08:58.028  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:08:58.029  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 15:08:58.029  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:08:58.029  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:08:58.029  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 15:08:58.029  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 15:08:58.030  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 removed from the list
,09-09 15:08:58.030  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:08:58.030  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e removed from the list
,09-09 15:08:58.035  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:08:58.035  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 15:08:58.035  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:08:58.036  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:08:58.036  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:08:58.037  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 15:08:58.037  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 15:08:58.037  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:08:58.037  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
,09-09 15:08:58.039  3819  3872 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 15:08:58.039  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:08:58.039  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:08:58.039  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 15:08:58.039  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:08:58.040  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:08:58.040  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:08:58.040  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:08:58.040  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:08:58.040  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:08:58.040  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:08:58.040  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:08:58.040  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:08:58.040  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:08:58.040  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:08:58.041  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:08:58.041  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:08:58.042  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:08:58.042  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:08:58.046  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 15:08:58.046  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-09 15:08:58.046  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 15:08:58.046  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 15:08:58.046  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110],
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 15:08:58.047  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
09-09 15:08:58.048  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 15:08:58.048  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-09 15:08:58.048  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 15:08:58.048  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 15:08:58.048  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 15:08:58.048  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-09 15:08:58.048  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:08:58.048  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:08:58.048  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:08:58.048  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:08:58.048  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:08:58.048  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
,09-09 15:08:58.048  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:08:58.048  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:08:58.048  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 15:08:58.048  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:08:58.048  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:08:58.048  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:08:58.048  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:08:58.050  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:08:58.050  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 15:08:58.050  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:08:58.050  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:08:58.050  3819  3872 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 15:08:58.051  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 15:08:58.061  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:08:58.061  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:08:58.061  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:08:58.061  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:08:58.061  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:08:58.061  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:08:58.061  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:08:58.061  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:08:58.064  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 15:08:58.064  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-09 15:08:58.064  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 15:08:58.064  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 15:08:58.064  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 15:08:58.064  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 15:08:58.064  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 15:08:58.076  3819  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 15:08:58.076  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 15:08:58.077  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:08:58.083  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 15:08:58.083  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:08:58.084  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 15:08:58.084  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 15:08:58.088  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 15:08:58.090  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 15:08:58.090  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 15:08:58.090  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 15:08:58.091  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 15:08:58.092  3819  3872 D BluetoothAdapter: STATE_ON
,09-09 15:08:58.095  2687  2700 D BtGatt.GattService: registerClient() - UUID=f35794ef-295a-4a31-8197-6dd24103d173
,09-09 15:08:58.096  2687  2712 D BtGatt.GattService: onClientRegistered() - UUID=f35794ef-295a-4a31-8197-6dd24103d173, clientIf=5
,09-09 15:08:58.096  3819  3830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 15:08:58.100  2687  2830 D BtGatt.GattService: start scan with filters
,09-09 15:08:58.105  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 15:08:58.106  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 15:08:58.106  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 15:08:58.106  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 15:08:58.107  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 15:08:58.107  2687  2715 D BtGatt.ScanManager: handling starting scan
,09-09 15:08:58.108  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 15:08:58.109  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 15:08:58.114  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 15:08:58.116  2687  2715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
,09-09 15:08:58.116  3819  3872 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 15:08:58.124  2687  2712 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 15:08:58.124  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:08:58.124  2687  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 15:08:58.130  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 15:08:58.130  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:08:58.131  2687  2715 D BtGatt.ScanManager: Starting BLE batch scan
09-09 15:08:58.131  2687  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 15:08:58.140  2687  2712 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 15:08:58.140  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:08:58.148  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 15:08:58.148  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:08:58.610  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 15:08:58.610  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 15:08:58.611  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 15:08:59.656  2687  2687 D BtGatt.ScanManager: awakened up at time 137580
,09-09 15:08:59.660  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:08:59.699  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-09 15:08:59.699  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:08:59.700  2687  2712 D BtGatt.GattService: current time is 137624839344
,09-09 15:08:59.701  2687  2712 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -78, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -89, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -79, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 15:08:59.707  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 15:08:59.710  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 15:08:59.710  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 15:08:59.711  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 15:08:59.711  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 15:08:59.712  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 15:09:01.203  2687  2687 D BtGatt.ScanManager: awakened up at time 139128
,09-09 15:09:01.205  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:09:01.218  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 15:09:01.219  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:02.719  2687  2687 D BtGatt.ScanManager: awakened up at time 140643
,09-09 15:09:02.721  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:09:02.766  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-09 15:09:02.766  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:09:02.766  2687  2712 D BtGatt.GattService: current time is 140691321324
,09-09 15:09:02.767  2687  2712 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 15:09:02.768  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 15:09:02.769  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 15:09:02.770  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 15:09:02.770  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-09 15:09:02.771  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 15:09:03.127  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:09:03.128  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:03.128  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 15:09:03.129  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:03.129  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 15:09:03.129  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 15:09:03.130  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 15:09:03.130  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 15:09:03.130  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 15:09:03.132  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 15:09:03.132  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 15:09:03.135  3819  3872 D BluetoothAdapter: STATE_ON
09-09 15:09:03.137  2687  2700 D BtGatt.GattService: stopScan() - queue size =1
,09-09 15:09:03.140  2687  2830 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 15:09:03.141  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 15:09:03.141  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 15:09:03.141  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 15:09:03.142  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 15:09:03.142  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 15:09:03.146  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 15:09:03.147  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 15:09:03.149  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 15:09:03.150  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 15:09:03.151  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 15:09:03.156  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 15:09:03.157  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 15:09:03.157  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 15:09:03.159  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:03.160  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:03.160  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 15:09:03.160  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:03.160  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:03.161  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:03.161  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:03.161  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:03.162  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 15:09:03.162  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:09:03.163  2687  2715 D BtGatt.ScanManager: stopping BLe Batch
,09-09 15:09:03.171  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 15:09:03.172  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:03.172  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:09:03.196  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
09-09 15:09:03.197  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:09:03.197  2687  2712 D BtGatt.GattService: current time is 141121926099
09-09 15:09:03.197  2687  2712 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
09-09 15:09:03.198  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 15:09:03.199  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-09 15:09:03.660  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 15:09:07.317  1542  2226 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 15:09:08.163  3819  3872 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 15:09:08.170  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:09:08.188  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:09:08.188  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:08.188  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:08.188  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:08.188  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:09:08.188  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:08.188  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:09:08.188  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:09:08.197  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:09:08.198  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 15:09:08.198  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 15:09:08.199  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 15:09:08.199  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 15:09:08.199  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:09:08.200  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 15:09:08.206  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:08.213  3819  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 15:09:08.214  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 15:09:08.215  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:08.228  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 15:09:08.230  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 15:09:08.231  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 15:09:08.243  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 15:09:08.244  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
09-09 15:09:08.244  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 15:09:08.246  3819  3872 D BluetoothAdapter: STATE_ON
,09-09 15:09:08.254  2687  2699 D BtGatt.GattService: registerClient() - UUID=6210e461-0ed0-4917-bf56-19e77b07943c
,09-09 15:09:08.255  2687  2712 D BtGatt.GattService: onClientRegistered() - UUID=6210e461-0ed0-4917-bf56-19e77b07943c, clientIf=5
09-09 15:09:08.257  3819  3831 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 15:09:08.258  2687  2700 D BtGatt.GattService: start scan with filters
,09-09 15:09:08.267  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 15:09:08.268  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 15:09:08.268  2687  2715 D BtGatt.ScanManager: handling starting scan
,09-09 15:09:08.268  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 15:09:08.269  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 15:09:08.277  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 15:09:08.278  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 15:09:08.279  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 15:09:08.285  2687  2712 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 15:09:08.285  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.286  2687  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 15:09:08.286  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 15:09:08.294  3819  3872 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 15:09:08.301  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:09:08.302  3819  3872 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 15:09:08.302  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:08.303  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 15:09:08.303  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:08.303  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 15:09:08.304  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 15:09:08.304  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 15:09:08.304  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 15:09:08.304  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 15:09:08.306  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 15:09:08.306  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 15:09:08.306  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 15:09:08.307  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.307  2687  2715 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 15:09:08.307  2687  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 15:09:08.309  3819  3872 D BluetoothAdapter: STATE_ON
,09-09 15:09:08.310  2687  2699 D BtGatt.GattService: stopScan() - queue size =1
09-09 15:09:08.312  2687  2700 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 15:09:08.313  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 15:09:08.314  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 15:09:08.314  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 15:09:08.314  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 15:09:08.314  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 15:09:08.317  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 15:09:08.318  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 15:09:08.318  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 15:09:08.318  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 15:09:08.319  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 15:09:08.323  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:08.323  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 15:09:08.323  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 15:09:08.323  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:08.323  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 15:09:08.323  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 15:09:08.324  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
,09-09 15:09:08.324  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:08.324  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:08.324  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 15:09:08.324  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:08.325  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:08.325  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:08.326  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:08.326  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 15:09:08.327  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:08.327  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:08.327  3819  3872 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 15:09:08.329  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:09:08.338  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:09:08.338  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:08.338  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:08.338  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:08.338  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:09:08.338  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:08.338  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:09:08.338  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:09:08.339  2687  2712 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 15:09:08.339  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.341  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:09:08.341  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 15:09:08.342  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 15:09:08.342  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 15:09:08.342  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 15:09:08.342  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:09:08.342  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 15:09:08.344  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:08.347  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:08.349  3819  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 15:09:08.349  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 15:09:08.352  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 15:09:08.353  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.354  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 15:09:08.356  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 15:09:08.356  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 15:09:08.363  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 15:09:08.363  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 15:09:08.363  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
09-09 15:09:08.364  3819  3872 D BluetoothAdapter: STATE_ON
,09-09 15:09:08.365  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 15:09:08.365  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:09:08.366  2687  2715 D BtGatt.ScanManager: stopping BLe Batch
,09-09 15:09:08.366  2687  2699 D BtGatt.GattService: registerClient() - UUID=c8e28862-8f93-4778-a2b2-38b3529b07bd
,09-09 15:09:08.367  2687  2712 D BtGatt.GattService: onClientRegistered() - UUID=c8e28862-8f93-4778-a2b2-38b3529b07bd, clientIf=5
,09-09 15:09:08.367  3819  3831 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 15:09:08.368  2687  2700 D BtGatt.GattService: start scan with filters
,09-09 15:09:08.371  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 15:09:08.371  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 15:09:08.371  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 15:09:08.371  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 15:09:08.374  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 15:09:08.374  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 15:09:08.374  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 15:09:08.376  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 15:09:08.376  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.376  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 15:09:08.376  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:09:08.379  3819  3872 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 15:09:08.390  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 15:09:08.390  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.393  2687  2715 D BtGatt.ScanManager: handling starting scan
,09-09 15:09:08.407  2687  2712 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 15:09:08.408  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.408  2687  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 15:09:08.415  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 15:09:08.415  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.416  2687  2715 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 15:09:08.416  2687  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 15:09:08.447  2687  2712 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 15:09:08.447  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.470  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 15:09:08.470  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:08.875  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 15:09:08.876  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 15:09:08.876  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 15:09:09.972  2687  2687 D BtGatt.ScanManager: awakened up at time 147897
,09-09 15:09:09.974  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:09:10.021  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-09 15:09:10.021  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:09:10.021  2687  2712 D BtGatt.GattService: current time is 147946356412
09-09 15:09:10.022  2687  2712 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -85, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 15:09:10.022  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 15:09:10.022  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 15:09:10.023  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 15:09:10.023  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 15:09:10.023  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 15:09:10.023  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 15:09:11.525  2687  2687 D BtGatt.ScanManager: awakened up at time 149450
,09-09 15:09:11.527  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:09:11.558  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
09-09 15:09:11.558  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:11.559  2687  2712 D BtGatt.GattService: current time is 149483614826
09-09 15:09:11.559  2687  2712 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -86, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -82, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 15:09:11.560  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 15:09:11.561  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 15:09:12.121   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 15:09:12.132  1878  1878 I Keyboard.Facilitator: onFinishInput()
,09-09 15:09:12.142   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 15:09:12.142   875   895 I Adreno  : Build Date                       : 10/20/15
09-09 15:09:12.142   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 15:09:12.142   875   895 I Adreno  : Local Branch                     : M14
09-09 15:09:12.142   875   895 I Adreno  : Remote Branch                    : 
09-09 15:09:12.142   875   895 I Adreno  : Remote Branch                    : 
09-09 15:09:12.142   875   895 I Adreno  : Reconstruct Branch               : 
,09-09 15:09:12.195   281   300 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (312 us)
,09-09 15:09:12.871  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 15:09:12.871  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 15:09:12.908   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 15:09:12.912  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c836254 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@6011363, 16908290=android.view.AbsSavedState$1@6011363}, android:focusedViewId=100}]}]
,09-09 15:09:12.912  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 15:09:12.913  3819  3819 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 15:09:12.913  3819  3819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 15:09:12.927   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 15:09:12.931   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-09 15:09:12.935   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-09 15:09:12.935   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-09 15:09:13.074  2687  2687 D BtGatt.ScanManager: awakened up at time 150998
,09-09 15:09:13.079  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:09:13.135  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-09 15:09:13.135  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:09:13.135  2687  2712 D BtGatt.GattService: current time is 151059822402
,09-09 15:09:13.135  2687  2712 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 15:09:13.135  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 15:09:13.136  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 15:09:13.136  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 15:09:13.136  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 15:09:13.136  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 15:09:13.184   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 15:09:13.186   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 15:09:13.191   875  1340 D SurfaceControl: Excessive delay in setPowerMode(): 260ms
,09-09 15:09:13.193   875   895 I DreamManagerService: Entering dreamland.
09-09 15:09:13.194   875   895 I PowerManagerService: Dozing...
09-09 15:09:13.194   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 15:09:13.234   377  1475 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 15:09:13.234   377  1475 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 15:09:13.246   875  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 15:09:13.249  1934  3889 D NfcService: Discovery configuration equal, not updating.
,09-09 15:09:13.258   875  1315 E native  : do suspend false
,09-09 15:09:13.275   875  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 15:09:13.289   875  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 15:09:13.293   875  1315 E native  : do suspend true
,09-09 15:09:13.298  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:09:13.376   377  1929 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 15:09:13.377   377  1929 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 15:09:13.379  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:13.380  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:09:13.380  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 15:09:13.381  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:13.381  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 15:09:13.381  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 15:09:13.382  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 15:09:13.384  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 15:09:13.384  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 15:09:13.384  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 15:09:13.384  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 15:09:13.387  3819  3872 D BluetoothAdapter: STATE_ON
09-09 15:09:13.389  2687  2699 D BtGatt.GattService: stopScan() - queue size =1
09-09 15:09:13.394  2687  2833 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 15:09:13.394  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 15:09:13.395  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 15:09:13.395  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 15:09:13.396  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 15:09:13.396  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 15:09:13.399  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 15:09:13.400  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 15:09:13.400  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 15:09:13.400  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 15:09:13.400  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 15:09:13.401  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 15:09:13.406  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 15:09:13.406  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 15:09:13.406  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 15:09:13.406  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-09 15:09:13.411  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 15:09:13.411  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:09:13.411  2687  2715 D BtGatt.ScanManager: stopping BLe Batch
,09-09 15:09:13.423  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 15:09:13.423  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:09:13.424  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:09:13.451  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-09 15:09:13.451  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:09:13.451  2687  2712 D BtGatt.GattService: current time is 151375805714
,09-09 15:09:13.451  2687  2712 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-09 15:09:13.451  2687  2712 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-09 15:09:13.456  1542  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 15:09:13.456  1542  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 15:09:13.456  1542  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 15:09:13.456  1542  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:13.474  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 15:09:13.474  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 15:09:13.475  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 15:09:13.751   875  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-09 15:09:13.907  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 15:09:13.908  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:13.908  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 15:09:18.407  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:09:18.408  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:09:18.408  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:18.411  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:09:18.411  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:18.411  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 15:09:18.413  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
,09-09 15:09:18.414  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.415  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
,09-09 15:09:18.415  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 15:09:18.416  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.420  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:18.421  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:18.424  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:18.424  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 15:09:18.424  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.425  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.427  3819  3872 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 15:09:18.429  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:09:18.429  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:18.430  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 15:09:18.430  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:09:18.430  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.431  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:18.431  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:18.431  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:18.431  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.431  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 15:09:18.432  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.432  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:18.432  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.432  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:18.435  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 15:09:18.435  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:18.435  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:18.436  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
,09-09 15:09:18.438  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 15:09:18.439  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:09:18.439  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:09:18.439  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 15:09:18.439  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:18.439  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:18.439  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.440  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:18.440  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:18.440  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.440  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:18.440  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:18.440  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.440  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.440  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:18.441  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:18.442  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:18.442  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:18.442  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.442  3819  3872 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 15:09:18.443  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:09:18.443  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:18.443  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:18.443  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:18.443  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 15:09:18.443  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.443  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:18.443  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:18.443  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.444  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:18.444  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:18.444  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.444  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:18.444  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.445  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-09 15:09:18.445  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 15:09:18.446  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:18.446  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
,09-09 15:09:18.446  3819  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-09 15:09:18.446  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:18.447  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:09:18.447  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:18.447  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:09:18.447  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.447  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.447  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:18.447  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:18.447  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.447  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:18.447  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.447  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.448  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.448  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.449  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:18.449  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 15:09:18.450  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:18.450  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
,09-09 15:09:18.450  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 15:09:18.451  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 15:09:18.451  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 15:09:18.451  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 15:09:18.451  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 15:09:18.451  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 15:09:18.451  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 15:09:18.451  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 15:09:18.451  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 15:09:18.451  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:18.452  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:09:18.452  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:18.452  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:09:18.452  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.452  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:18.452  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
,09-09 15:09:18.452  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.452  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.452  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 15:09:18.452  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.452  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.453  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.453  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.455  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:18.455  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:18.456  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.456  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.457  3819  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 15:09:18.457  3819  3872 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 15:09:18.457  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 15:09:18.462  3819  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 15:09:18.462  3819  3872 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 15:09:18.463  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 15:09:18.463  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 15:09:18.463  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 15:09:18.463  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 15:09:18.463  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 15:09:18.463  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 15:09:18.465  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 15:09:18.466  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 15:09:18.466  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 15:09:18.466  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 15:09:18.466  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 15:09:18.466  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 15:09:18.466  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 15:09:18.466  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 15:09:18.466  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 15:09:18.467  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 15:09:18.467  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 15:09:18.467  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 15:09:18.467  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 15:09:18.467  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 15:09:18.467  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 15:09:18.467  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 15:09:18.468  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 15:09:18.468  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 15:09:18.468  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 15:09:18.469  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 15:09:18.469  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 15:09:18.469  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 15:09:18.469  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 15:09:18.469  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 15:09:18.469  3819  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 15:09:18.472  3819  3872 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 15:09:18.472  3819  3872 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 15:09:18.472  3819  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 15:09:18.472  3819  3872 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 15:09:18.473  3819  3872 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 15:09:18.473  3819  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 15:09:18.473  3819  3872 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 15:09:18.473  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 15:09:18.477  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 15:09:18.479  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 15:09:18.479  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 15:09:18.480  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 15:09:18.480  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 15:09:18.480  3819  3872 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 15:09:18.480  3819  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 15:09:18.480  3819  3872 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 15:09:18.481  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:18.481  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:18.481  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:18.481  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:18.481  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.481  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.482  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 15:09:18.481  3819  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 395)
09-09 15:09:18.482  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:18.482  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.482  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.482  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:18.483  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.483  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.483  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.483  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.483  3819  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 395
09-09 15:09:18.485  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:18.485  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:18.485  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.485  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.486  3819  3872 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 15:09:18.487  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:18.487  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:18.487  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:18.487  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:18.487  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.487  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.487  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:18.488  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.489  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.489  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:18.489  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.489  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.489  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.489  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.487  3819  3894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 15:09:18.490  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:18.490  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:18.490  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.490  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.492  3819  3872 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 15:09:18.493  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:18.493  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:18.493  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:18.493  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:18.493  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.493  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.493  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:18.493  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.493  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.493  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:18.493  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.493  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.493  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.493  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.495  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:18.495  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:18.495  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.495  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.496  3819  3872 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 15:09:18.496  3819  3872 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 15:09:18.496  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 15:09:18.496  3819  3872 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 15:09:18.496  3819  3872 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 15:09:18.496  3819  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 15:09:18.496  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 15:09:18.496  3819  3872 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 15:09:18.496  3819  3872 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 15:09:18.496  3819  3872 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 15:09:18.496  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 15:09:18.497  3819  3872 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 15:09:18.497  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:18.497  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:18.497  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:18.497  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:18.497  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.497  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.497  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:18.497  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.497  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.497  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:18.497  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.497  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.498  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.498  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.499  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:18.500  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:18.500  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.500  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.501  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:18.501  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.501  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:18.501  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:18.501  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:18.501  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:18.502  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:18.502  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:18.502  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:18.625  2174  2644 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 15:09:20.589  3628  3897 V KeepSync: Connecting to GoogleApiClient
,09-09 15:09:20.589   875  1404 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 15:09:20.651  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:09:20.654  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:09:20.694  1542  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 15:09:20.694  1542  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 15:09:20.695  1542  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:09:20.695  1542  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:20.715  1753  3899 V BaseAuthAsyncOperation: access token request failed
,09-09 15:09:20.719  3628  3897 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 15:09:20.747  1542  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 15:09:20.748  1542  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 15:09:20.748  1542  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:09:20.748  1542  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:20.777  3543  3898 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 15:09:20.777  3543  3898 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at blb.a(PG:3937)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at czp.a(PG:18188)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:09:20.777  3543  3898 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at jdm.a(PG:77)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	... 12 more
09-09 15:09:20.777  3543  3898 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at fal.a(PG:38)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:09:20.777  3543  3898 E HttpOperation: 	... 14 more
,09-09 15:09:20.785  1542  3056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 15:09:20.785  1542  3056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 15:09:20.785  1542  3056 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:09:20.785  1542  3056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:20.810  3628  3897 E KeepSync: IOException
09-09 15:09:20.810  3628  3897 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 15:09:20.810  3628  3897 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:09:20.810  3628  3897 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 15:09:20.810  3628  3897 E KeepSync: 	... 10 more
,09-09 15:09:20.810  3628  3897 W KeepSync: Sync result 2
,09-09 15:09:20.813  1542  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 15:09:20.813  1542  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 15:09:20.813  1542  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:09:20.813  1542  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:20.819   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 133101, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:09:20.843  3543  3898 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 15:09:20.843  3543  3898 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at hec.a(PG:42)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at hee.a(PG:102)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at czr.a(PG:65)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at kka.a(PG:108)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at czp.a(PG:19176)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:09:20.843  3543  3898 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	,at jdm.a(PG:77)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	... 15 more
09-09 15:09:20.843  3543  3898 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at fal.a(PG:38)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:09:20.843  3543  3898 E HttpOperation: 	... 17 more
09-09 15:09:20.843  3543  3898 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 15:09:20.843  3543  3898 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at hec.a(PG:42)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at hee.a(PG:102)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at czr.a(PG:65)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at kka.a(PG:108)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at jdj.a(PG:4091)
,09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	... 15 more
09-09 15:09:20.843  3543  3898 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at fal.a(PG:38)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 15:09:20.843  3543  3898 E ExperimentLoader: 	... 17 more
,09-09 15:09:20.944   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129578, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:09:23.503  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:23.503  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
,09-09 15:09:23.503  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:23.504  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:23.504  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:23.504  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:23.505  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:23.506  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:09:23.506  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:23.506  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:23.506  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:23.507  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.507  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:23.507  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:23.508  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:23.508  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:23.508  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:23.509  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.509  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.509  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:23.513  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:23.513  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:23.513  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:23.514  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:23.518  3819  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 15:09:23.520  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:09:23.523  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 15:09:23.525  3819  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 15:09:23.525  3819  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 15:09:23.526  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-09 15:09:23.526  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 15:09:23.527  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:09:23.528  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 15:09:23.528  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 15:09:23.528  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 15:09:23.528  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 15:09:23.528  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.529  3819  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 15:09:23.529  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:23.529  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 15:09:23.529  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:23.529  3819  3901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 15:09:23.529  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 15:09:23.530  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 15:09:23.530  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 15:09:23.530  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.530  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.532  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 15:09:23.532  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:23.532  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:23.532  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 15:09:23.533  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:23.533  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:23.533  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:23.533  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.533  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 15:09:23.534  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.534  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:23.534  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:23.535  3819  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 15:09:23.535  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listen,er org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:23.534  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 15:09:23.535  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:23.535  3819  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 15:09:23.535  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.535  3819  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 15:09:23.535  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.535  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.535  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.535  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 15:09:23.536  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:23.536  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:23.536  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:23.536  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:23.538  3819  3872 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 15:09:23.538  3819  3872 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 15:09:23.538  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 15:09:23.541  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 15:09:23.541  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 15:09:23.541  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:23.542  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:23.542  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:09:23.542  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:23.542  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.542  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.542  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:23.542  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:23.542  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:23.542  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:23.542  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.542  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.543  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.543  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.544  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 15:09:23.544  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:23.544  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:23.545  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:23.551  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:09:23.551  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:23.551  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 15:09:23.551  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:23.551  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.552  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.552  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
09-09 15:09:23.552  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:23.552  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
,09-09 15:09:23.552  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:23.552  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:23.552  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.552  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 15:09:23.552  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.554  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 15:09:23.554  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:23.554  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:23.554  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:23.555  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:09:23.555  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:09:23.555  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 15:09:23.555  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:09:23.555  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:23.556  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.556  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb2a9 not in the list
,09-09 15:09:23.556  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:23.556  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list
09-09 15:09:23.556  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 15:09:23.556  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.556  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:23.556  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:23.556  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:23.557  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:09:23.557  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:09:23.557  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:23.557  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7c02e not in the list,
09-09 15:09:23.559  3819  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 15:09:23.559  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 15:09:23.559  3819  3872 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 15:09:23.559  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
09-09 15:09:23.559  3819  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 15:09:23.559  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 15:09:23.563  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 15:09:23.563  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 15:09:23.563  3819  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 15:09:23.563  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left,
09-09 15:09:23.564  3819  3872 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 15:09:23.564  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left,
09-09 15:09:23.564  3819  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 15:09:23.564  3819  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-09 15:09:23.565  3819  3872 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 15:09:23.565  3819  3872 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-09 15:09:23.565  3819  3872 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 15:09:23.565  3819  3872 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 15:09:23.566  3819  3872 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-09 15:09:23.566  3819  3872 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing,
09-09 15:09:23.567  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 15:09:23.567  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a9c9819 added. We now have 3 listener(s)
09-09 15:09:23.567  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 15:09:23.569  3819  3872 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 15:09:23.569   875  1391 D WifiService: setWifiEnabled: true pid=3819, uid=10000
,09-09 15:09:23.569   875  1391 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 15:09:23.627  2687  2795 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40,
09-09 15:09:23.628  2687  2812 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
09-09 15:09:23.629  3819  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 395)
,09-09 15:09:23.938   875  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-09 15:09:24.035  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 15:09:28.576  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 15:09:28.577  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@75a90de added. We now have 4 listener(s)
09-09 15:09:28.577  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:09:28.594  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:28.595  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@75a90de removed from the list
,09-09 15:09:28.595  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:28.595  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:28.596  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:28.598  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 15:09:28.599  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36782bf added. We now have 4 listener(s)
,09-09 15:09:28.599  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:09:28.603  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:28.604  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36782bf removed from the list
,09-09 15:09:28.604  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:28.604  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:09:28.605  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:09:28.607  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 15:09:28.607  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba30d8c added. We now have 4 listener(s)
,09-09 15:09:28.608  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:09:28.614   875  2021 D WifiService: setWifiEnabled: false pid=3819, uid=10000
09-09 15:09:28.614   875  2021 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 15:09:28.629  2687  2708 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 15:09:28.629  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:09:28.629  2687  2708 D BluetoothAdapterProperties: Setting state to 13
,09-09 15:09:28.631  2687  2708 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 15:09:28.633  2687  2708 D BluetoothAdapterProperties: onBluetoothDisable(),
09-09 15:09:28.638  2687  2687 D BluetoothMapService: onReceive
,09-09 15:09:28.638  2687  2687 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 15:09:28.639  2687  2687 D BluetoothMapService: STATE_TURNING_OFF
,09-09 15:09:28.640  2687  2687 D BluetoothMapService: MAP Service closeService in
,09-09 15:09:28.643  2687  2687 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 15:09:28.643  2687  2687 D ObexServerSockets0: shutdown(block = true)
09-09 15:09:28.646  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 15:09:28.646  2687  2845 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 15:09:28.647  2687  2846 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 15:09:28.637  2687  2708 I BluetoothAdapterState: Entering PendingCommandState
,09-09 15:09:28.649  2687  2812 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 15:09:28.649  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 15:09:28.650  2687  2687 I BtOppRfcommListener: stopping Accept Thread
09-09 15:09:28.651  2687  3450 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 15:09:28.656  2687  3450 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 15:09:28.656  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.657  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:09:28.657  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.657  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.657  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:28.657  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.657  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:28.657  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:09:28.657  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 15:09:28.657  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.658  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:28.658  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 15:09:28.661  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:28.664  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:28.668  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:28.668  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:28.668  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.668  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.668  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:28.668  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.668  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:28.668  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:09:28.668  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 15:09:28.669  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.669  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:09:28.672  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 15:09:28.672  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.672  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:28.672  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.672  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.672  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-09 15:09:28.672  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.672  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:28.672  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:09:28.672  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:09:28.673   875   888 I ActivityManager: Start proc 3905:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-09 15:09:28.674  2687  2712 D BluetoothAdapterProperties: Scan Mode:20
,09-09 15:09:28.674  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:28.674  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:09:28.674  2687  2708 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 15:09:28.674   875  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 15:09:28.674   875  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 15:09:28.675   875  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 15:09:28.675   875  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 15:09:28.680  2687  2687 D HeadsetService: Received stop request...Stopping profile...
09-09 15:09:28.681   875   875 D BluetoothHeadset: Proxy object disconnected
,09-09 15:09:28.682  1947  1958 D BluetoothHeadset: Proxy object disconnected
09-09 15:09:28.683  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:28.683   875  1315 E native  : do suspend true
09-09 15:09:28.683   875   875 D BluetoothHeadset: Proxy object disconnected
09-09 15:09:28.684  1372  2219 D BluetoothHeadset: Proxy object disconnected
09-09 15:09:28.684   875   875 D BluetoothHeadset: Proxy object disconnected
09-09 15:09:28.684  2687  2687 D A2dpService: Received stop request...Stopping profile...
,09-09 15:09:28.684  2687  2819 D A2dpStateMachine: Exit Disconnected: -1
09-09 15:09:28.685  1372  1372 D HeadsetProfile: Bluetooth service disconnected
09-09 15:09:28.686  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:28.686   875   875 D BluetoothA2dp: Proxy object disconnected
09-09 15:09:28.686  1372  1372 D BluetoothA2dp: Proxy object disconnected
09-09 15:09:28.688  2687  2687 V BluetoothAdapterState: isTurningOff()=true
09-09 15:09:28.688  2687  2687 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:28.688  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:28.688  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:28.688  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:28.690  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 15:09:28.690  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 15:09:28.690  2687  2795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:28.691  2687  2795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:28.691  2687  2795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 15:09:28.691  2687  2712 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 15:09:28.691  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:28.691  2687  2712 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 15:09:28.691  2687  2687 D HidService: Received stop request...Stopping profile...
09-09 15:09:28.691  2687  2687 D HidService: Stopping Bluetooth HidService
09-09 15:09:28.692  1372  1372 D BluetoothInputDevice: Proxy object disconnected
09-09 15:09:28.692  1372  1372 D HidProfile: Bluetooth service disconnected
09-09 15:09:28.693  2687  2687 D HealthService: Received stop request...Stopping profile...
09-09 15:09:28.695  2687  2687 D PanService: Received stop request...Stopping profile...
09-09 15:09:28.697   875  1876 D DhcpClient: Clearing IP address
09-09 15:09:28.697  2687  2687 D BluetoothMapService: Received stop request...Stopping profile...
09-09 15:09:28.697   373   873 D CommandListener: Clearing all IP addresses on wlan0
09-09 15:09:28.698  2687  2687 D BluetoothMapService: stop()
09-09 15:09:28.698  2687  2687 D BluetoothMapAppObserver: deinitObservers()
09-09 15:09:28.698  2687  2687 D BluetoothMapAppObserver: removeReceiver()
09-09 15:09:28.699  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 15:09:28.699  1372  1372 D PanProfile: Bluetooth service disconnected
09-09 15:09:28.700  1372  1372 D BluetoothMap: Proxy object disconnected
09-09 15:09:28.700  2687  2687 V BluetoothAdapterState: isTurningOff()=true
09-09 15:09:28.700  1372  1372 D MapProfile: Bluetooth service disconnected
09-09 15:09:28.700  2687  2687 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:28.700  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:28.700  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:28.701   373   873 D CommandListener: Setting iface cfg
09-09 15:09:28.701  2687  2795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:28.702  2687  2795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:28.702  2687  2795 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 15:09:28.702  2687  2795 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 15:09:28.702  2687  2795 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 15:09:28.702  2687  2687 V BluetoothAdapterState: isTurningOff()=true
09-09 15:09:28.702  2687  2795 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 15:09:28.702  2687  2687 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:28.702  2687  2712 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 15:09:28.702  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 15:09:28.702  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 15:09:28.702  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 15:09:28.703  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 15:09:28.703  2687  2712 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 15:09:28.703  2687  2687 V BluetoothAdapterState: isTurningOff()=true
09-09 15:09:28.703  2687  2687 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:28.703  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:28.703  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:28.703  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 15:09:28.703  2687  2712 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 15:09:28.703  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 15:09:28.704  2687  2687 V BluetoothAdapterState: isTurningOff()=true
09-09 15:09:28.704  2687  2687 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:28.704  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:28.704  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:28.704  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 15:09:28.704  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 15:09:28.707   875  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 15:09:28.708   875  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 15:09:28.708   875  1315 E native  : do suspend true
,09-09 15:09:28.709  2687  2687 D BluetoothMapService: MAP Service closeService in
09-09 15:09:28.709  2687  2687 V BluetoothAdapterState: isTurningOff()=true
09-09 15:09:28.709  2687  2687 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:28.710  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:28.710  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:28.710  2687  2708 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 15:09:28.710  2687  2708 D BluetoothAdapterProperties: Setting state to 15
09-09 15:09:28.710  2687  2708 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 15:09:28.710   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 15:09:28.710   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 15:09:28.710   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 15:09:28.711  1372  1383 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 15:09:28.711  2687  2708 I BluetoothAdapterState: Entering BleOnState
09-09 15:09:28.712   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 15:09:28.712  1372  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 15:09:28.713   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 15:09:28.713   875  1890 D DhcpClient: Receive thread stopped
09-09 15:09:28.714  1372  2219 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 15:09:28.714   875  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-09 15:09:28.714  1372  1384 D BluetoothPan: onBluetoothStateChange on: false
09-09 15:09:28.714   396   396 E Parcel  : Reading a NULL string not supported here.
09-09 15:09:28.715  1372  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 15:09:28.716  1947  2087 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 15:09:28.716  1372  2219 D BluetoothMap: onBluetoothStateChange: up=false
09-09 15:09:28.716  2687  2687 D BluetoothMapService: cleanup()
09-09 15:09:28.716  2687  2687 D BluetoothMapService: MAP Service closeService in
09-09 15:09:28.716   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 15:09:28.717  2687  2708 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 15:09:28.717  2687  2708 D BluetoothAdapterProperties: Setting state to 16
09-09 15:09:28.717  2687  2708 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 15:09:28.718  2687  2708 D BluetoothAdapterProperties: onBleDisable
,09-09 15:09:28.718  2687  2708 I BluetoothAdapterState: Entering PendingCommandState
09-09 15:09:28.718  2687  2709 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 15:09:28.720  2687  2712 D BluetoothAdapterProperties: Scan Mode:20
09-09 15:09:28.720  2687  2795 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 15:09:28.720  2687  2795 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:28.721  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.721  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:28.721  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.721  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.721  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:28.721  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.721  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:28.721  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:28.721  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 15:09:28.722  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:28.722  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:28.723  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.723  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:28.723  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.723  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.723  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:28.723  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.723  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:28.723  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:28.723  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:28.724  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.724  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:28.725  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.726  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:28.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:28.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:28.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:28.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:28.726  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:28.726  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:28.728  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.728  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:28.728  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.728  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.728  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:28.728  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.728  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:28.728  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:28.728  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:28.730  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:28.731  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:28.758   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 15:09:28.760  3905  3905 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 15:09:28.779  3905  3905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 15:09:28.781   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 15:09:28.782   875  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-09 15:09:28.782   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 15:09:28.783   373   873 D CommandListener: Clearing all IP addresses on wlan0
09-09 15:09:28.784   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a20abe:true
,09-09 15:09:28.785   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-09 15:09:28.788  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:28.788   875  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 15:09:28.790  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:28.791  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:28.795  3398  3398 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@de8e1b2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-09 15:09:28.804   875  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 15:09:28.807  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.807  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:28.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:28.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:28.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:28.807  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 15:09:28.807  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.808  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:28.808  2174  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 15:09:28.809  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.809  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:28.809  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.809  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.809  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:28.809  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.809  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:28.809  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:28.809  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:28.809   875  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 15:09:28.809  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.809  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:28.811  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.811  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:28.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:28.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:28.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:28.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:28.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:28.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:28.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:28.812  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:28.812  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 15:09:28.820  1542  1542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 15:09:28.820  1542  2141 V NativeCrypto: Read error: ssl=0xaee76c00: I/O error during system call, Connection timed out
,09-09 15:09:28.821  1542  2141 I art     : Waiting for a blocking GC DisableMovingGc
,09-09 15:09:28.826  1542  2141 I art     : WaitForGcToComplete blocked for 5.286ms for cause DisableMovingGc
,09-09 15:09:28.826  1542  2141 I art     : Starting a blocking GC DisableMovingGc
09-09 15:09:28.827  1542  2141 V NativeCrypto: SSL shutdown failed: ssl=0xaee76c00: I/O error during system call, Broken pipe
,09-09 15:09:28.832   875  1915 I ActivityManager: Start proc 3925:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 15:09:28.836  3905  3905 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 15:09:28.838  3905  3905 D BluetoothMap: Create BluetoothMap proxy object
,09-09 15:09:28.844  3905  3905 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 15:09:28.850  3905  3905 D DockEventReceiver: finishStartingService: stopping service
,09-09 15:09:28.853   875  2022 I ActivityManager: Killing 3082:com.google.android.talk/u0a61 (adj 15): empty #17
,09-09 15:09:28.862   373   873 E Netd    : netlink response contains error (No such file or directory)
,09-09 15:09:28.918  3925  3925 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 15:09:28.921  2687  2712 I bt_hci  : shut_down
,09-09 15:09:28.922  2687  2716 D bt_hwcfg: hw_epilog_process
,09-09 15:09:28.923  2687  2716 I bt_vendor: low_power_mode_cb
,09-09 15:09:28.950  2687  2716 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-09 15:09:28.950  2687  2716 I bt_vendor: epilog_cb
,09-09 15:09:28.950  2687  2716 I bt_hci  : epilog_finished_callback
,09-09 15:09:28.958  2687  2712 I bt_hci_h4: hal_close
,09-09 15:09:28.959  2687  2712 I bt_userial_vendor: device fd = 51 close
,09-09 15:09:29.079  2687  2709 D bt_stack_manager: event_shut_down_stack finished.
,09-09 15:09:29.080  2687  2708 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 15:09:29.084  2687  2687 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 15:09:29.085  2687  2708 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 15:09:29.086  2687  2687 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 15:09:29.086  2687  2687 D BtGatt.GattService: stop()
,09-09 15:09:29.086  2687  2687 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 15:09:29.090  2687  2687 V BluetoothAdapterState: isTurningOff()=false
,09-09 15:09:29.090  2687  2687 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:29.090  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:29.091  2687  2687 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 15:09:29.091  2687  2708 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 15:09:29.091  2687  2708 D BluetoothAdapterProperties: Setting state to 10
09-09 15:09:29.091  2687  2708 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 15:09:29.092  2687  2708 I BluetoothAdapterState: Entering OffState
,09-09 15:09:29.094   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 15:09:29.115  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 15:09:29.115  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 15:09:29.115  2687  2709 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 15:09:29.117  2687  2709 D bt_stack_manager: event_clean_up_stack finished.
,09-09 15:09:29.117  2687  2687 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 15:09:29.139  2687  2687 I art     : System.exit called, status: 0
,09-09 15:09:29.139  2687  2687 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 15:09:29.165  3925  3925 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:09:29.165  3925  3925 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:09:29.165  3925  3925 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:09:29.165  3925  3925 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:09:29.165  3925  3925 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:09:29.165  3925  3925 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:09:29.165  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:09:29.166  3925  3925 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:09:29.166  3925  3925 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:09:29.166  3925  3925 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:09:29.172  3905  3905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 15:09:29.175   875  2022 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-09 15:09:29.175   875  2022 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-09 15:09:29.177   875  2022 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-09 15:09:29.177   875  2022 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-09 15:09:29.177   875  2022 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 15:09:29.177   875  2022 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-09 15:09:29.177   875  2022 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-09 15:09:29.177   875  2022 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-09 15:09:29.177   875  2022 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-09 15:09:29.177   875  2022 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-09 15:09:29.177   875  2022 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-09 15:09:29.177   875  2022 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-09 15:09:29.177   875  2022 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 15:09:29.220   875  2022 I ActivityManager: Start proc 3958:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-09 15:09:29.222   875   886 W ActivityManager: Spurious death for ProcessRecord{1c05fb4 3958:com.android.bluetooth/1002}, curProc for 2687: null
09-09 15:09:29.227  3905  3905 D DockEventReceiver: finishStartingService: stopping service
09-09 15:09:29.228   875  2021 I ActivityManager: Killing 3398:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 15:09:29.349  3925  3948 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 15:09:29.429  3958  3958 D AdapterServiceConfig: Adding HeadsetService
09-09 15:09:29.429  3958  3958 D AdapterServiceConfig: Adding A2dpService
09-09 15:09:29.429  3958  3958 D AdapterServiceConfig: Adding HidService
09-09 15:09:29.429  3958  3958 D AdapterServiceConfig: Adding HealthService
09-09 15:09:29.429  3958  3958 D AdapterServiceConfig: Adding PanService
,09-09 15:09:29.429  3958  3958 D AdapterServiceConfig: Adding GattService
,09-09 15:09:29.429  3958  3958 D AdapterServiceConfig: Adding BluetoothMapService
09-09 15:09:29.437  1542  1542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 15:09:29.449   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2adfc59:true
,09-09 15:09:29.480  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 15:09:29.482  1753  1753 D SystemUpdateService: onCreate
,09-09 15:09:29.490  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 15:09:29.505  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 15:09:29.513  1753  3972 I SystemUpdateService: active receiver: enabled
,09-09 15:09:29.516  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 15:09:29.517  1753  2434 I iu.UploadsManager: num queued entries: 0
,09-09 15:09:29.518  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 15:09:29.519  1753  2434 I iu.UploadsManager: num updated entries: 0
,09-09 15:09:29.520  1753  3972 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 15:09:29.522  1753  3972 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 15:09:29.522  1753  3972 I SystemUpdateService: now status is 0 (complete)
09-09 15:09:29.522  1753  3972 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 15:09:29.523  1753  3972 I SystemUpdateService: file has been verified
09-09 15:09:29.523  1753  3972 I SystemUpdateService: OTA package size = 12249756,
,09-09 15:09:29.526  1753  2434 I iu.SyncManager: NEXT; no task
,09-09 15:09:29.528  1753  3972 I SystemUpdateService: showing system update notification
,09-09 15:09:29.539   875   885 I ActivityManager: Start proc 3974:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 15:09:29.562  1753  1753 D SystemUpdateService: onDestroy
,09-09 15:09:29.571  3974  3974 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 15:09:29.573  3974  3974 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 15:09:29.577  3974  3974 D SprintDMHelper: simOperator: 
,09-09 15:09:29.577  3974  3974 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 15:09:29.590   875  1961 I ActivityManager: Start proc 3986:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 15:09:29.591   875  1961 I ActivityManager: Killing 3572:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-09 15:09:29.748   875  2022 I ActivityManager: Start proc 4000:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-09 15:09:29.751   875  2022 I ActivityManager: Killing 2782:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 15:09:29.839  4000  4000 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-09 15:09:30.009  4000  4017 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-09 15:09:30.009  4000  4017 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 15:09:30.016  4000  4017 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 15:09:30.016  4000  4017 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 15:09:30.052  4000  4017 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-09 15:09:30.052  4000  4017 I Babel_SMS: MmsConfig.loadFromResources
09-09 15:09:30.054  4000  4017 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 15:09:30.054  4000  4017 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 15:09:30.085  4000  4000 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 15:09:30.088  4000  4000 I Babel_Crash: startup - clean
,09-09 15:09:30.112  4000  4000 I Babel_telephony: TeleModule.launchCompleted
,09-09 15:09:30.118   875  1961 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 15:09:30.127  4000  4000 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-09 15:09:30.135  4000  4000 W Babel   : BAM#gBA: invalid account id: -1
,09-09 15:09:30.136  4000  4000 W Babel   : BAM#gBA: invalid account id: -1
,09-09 15:09:30.136  4000  4000 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-09 15:09:30.140  4000  4022 I Babel   : deleted: false for 0
,09-09 15:09:30.152   875  2021 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 15:09:30.193   875   886 I ActivityManager: Start proc 4024:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 15:09:30.224  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 15:09:30.284  4024  4024 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 15:09:30.299  4000  4000 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 15:09:30.333  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 15:09:30.334  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 15:09:30.349  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 15:09:30.354  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 15:09:30.387  4000  4000 I vclib   : onServiceConnected
,09-09 15:09:30.395  4000  4036 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 15:09:30.400   875  1916 I ActivityManager: Killing 3489:android.process.acore/u0a5 (adj 15): empty #17
,09-09 15:09:30.489  4024  4024 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 15:09:30.489  4024  4024 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 15:09:30.489  4024  4024 I GAv4    :   adb logcat -s GAv4
,09-09 15:09:30.506  4024  4024 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 15:09:30.513  4024  4024 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 15:09:30.535  4024  4042 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,09-09 15:09:30.656  4024  4024 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 15:09:30.693  4024  4024 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 15:09:30.702  4024  4024 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8623-8626)
,09-09 15:09:30.709  4024  4024 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 15:09:30.720  4024  4024 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2791b62}
,09-09 15:09:30.721  4024  4024 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 15:09:30.721  4024  4024 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 15:09:30.730  4024  4024 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 15:09:30.732  4024  4024 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 15:09:30.751  4024  4024 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 15:09:30.763  4024  4024 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 15:09:30.763  4024  4024 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 15:09:30.764  4024  4024 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 15:09:30.764  4024  4024 I Adreno  : Build Date                       : 10/20/15
09-09 15:09:30.764  4024  4024 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 15:09:30.764  4024  4024 I Adreno  : Local Branch                     : M14
09-09 15:09:30.764  4024  4024 I Adreno  : Remote Branch                    : 
09-09 15:09:30.764  4024  4024 I Adreno  : Remote Branch                    : 
09-09 15:09:30.764  4024  4024 I Adreno  : Reconstruct Branch               : 
,09-09 15:09:30.813  4024  4071 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 15:09:30.829  4024  4024 I NSApplication: Starting up...
,09-09 15:09:30.876   875  1404 I ActivityManager: Start proc 4076:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 15:09:30.877   875  1404 I ActivityManager: Killing 3704:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 15:09:30.967  4076  4076 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 15:09:31.150   875  1917 I ActivityManager: Killing 3719:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 15:09:31.242   875   886 I ActivityManager: Start proc 4090:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 15:09:31.332  4090  4090 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 15:09:31.391  4090  4090 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 15:09:31.454   875  1915 I ActivityManager: Killing 2251:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 15:09:33.661   875  1961 D WifiService: setWifiEnabled: true pid=3819, uid=10000
,09-09 15:09:33.661   875  1961 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 15:09:33.680   875  1315 D WifiConfigStore: Loading config and enabling all networks 
,09-09 15:09:33.684  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:33.684  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:33.684  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:33.684  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:33.684  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:33.684  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:33.684  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:33.684  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:33.684  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:33.684  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:33.684  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 15:09:33.686  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:33.687  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:33.687  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:33.687  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:33.687  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:33.687  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:33.687  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:33.687  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:33.687  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:33.687  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:33.687  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:33.689  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:33.689  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:33.689  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:33.689  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:33.689  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:33.689  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:33.689  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:33.689  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:33.689  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:33.690  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:33.690  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 15:09:33.712   875  1315 D WifiConfigStore: loaded 0 passpoint configs
,09-09 15:09:33.713   875  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 15:09:33.714   875  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 15:09:33.715   875  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 15:09:33.715   875  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 15:09:33.715   875  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 15:09:33.715   875  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 15:09:33.745   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 15:09:33.746   875  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 15:09:33.746   373   873 D CommandListener: Setting iface cfg
09-09 15:09:33.747   875  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-09 15:09:33.747   875  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 15:09:33.757   875  1314 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 15:09:33.757   875  1315 E native  : do suspend true
09-09 15:09:33.757   875  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 15:09:33.769   875  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 15:09:34.815  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:09:34.825  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:09:34.830  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:09:34.877  1542  2197 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 15:09:34.878  1542  2197 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 15:09:34.878  1542  2197 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:09:34.878  1542  2197 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:34.926  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 15:09:34.926  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 15:09:34.927  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-09 15:09:34.947   875  2022 I ActivityManager: Killing 3740:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 15:09:35.056   875  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 15:09:35.121   875  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.38 rxSuccessRate=6.38 delta 1000 -> 1000
,09-09 15:09:35.124   875  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 15:09:35.124   875  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 15:09:35.133   875  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 15:09:35.173   875  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 15:09:35.175  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 15:09:35.597  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 15:09:35.646  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 15:09:35.647  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 15:09:35.653   875  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 15:09:35.673   875  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 15:09:35.674   875  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 15:09:35.675   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 15:09:35.700   875  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 15:09:35.711   373   873 D CommandListener: Setting iface cfg
,09-09 15:09:35.712   875  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 15:09:35.730   875  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 15:09:35.770   875  4126 D DhcpClient: Receive thread started
,09-09 15:09:35.862   875  1315 E native  : do suspend false
,09-09 15:09:35.884   875  1876 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 15:09:35.906   875  4126 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172648, domain null
,09-09 15:09:35.908   875  1876 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172648 seconds
,09-09 15:09:35.913   875  1876 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 15:09:35.929   875  4126 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 15:09:35.930   875  1876 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 15:09:35.935   373   873 D CommandListener: Setting iface cfg
,09-09 15:09:35.947   875  1876 D DhcpClient: Scheduling renewal in 86399s
,09-09 15:09:35.948   875  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 15:09:35.951   875  1315 E native  : do suspend true
,09-09 15:09:35.965   875  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 15:09:35.968   875  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 15:09:35.969   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 15:09:35.972   875  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 15:09:35.973   875  1319 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 15:09:36.018   875  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 15:09:36.018   875  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 15:09:36.019   875  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 15:09:36.020   875  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 15:09:36.021   875  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 15:09:36.026   875  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 15:09:36.031   875  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 15:09:36.031   875  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-09 15:09:36.032   875  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 15:09:36.032   875  1319 D ConnectivityService:    accepting network in place of null
,09-09 15:09:36.032   875  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 15:09:36.032   875  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 15:09:36.033   875  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 15:09:36.059   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 15:09:36.078   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 15:09:36.081   875  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 15:09:36.082   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 15:09:36.084   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-09 15:09:36.084   875  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 15:09:36.093  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:36.093  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:36.093  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:36.093  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:36.093  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:36.093  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:36.093  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:36.093  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:09:36.093  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:09:36.093  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:36.093  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:36.093   875  4125 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174018, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:09:36.097  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:36.097  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:36.097  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:36.097  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:36.097  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:36.097  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:36.097  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:36.097  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:09:36.097  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:09:36.097  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:36.098  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:09:36.100  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:36.101  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:36.101  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:36.101  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:36.101  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:09:36.101  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:36.101  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:09:36.101  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:09:36.101  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:09:36.101  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:36.101  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:09:36.108  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 15:09:36.113  1753  1753 D SystemUpdateService: onCreate
,09-09 15:09:36.122  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 15:09:36.150  1753  4135 I SystemUpdateService: active receiver: enabled
,09-09 15:09:36.168  1753  4135 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 15:09:36.171   875  4124 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 15:09:36.172  1753  4135 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true,
09-09 15:09:36.172  1753  4135 I SystemUpdateService: now status is 0 (complete)
,09-09 15:09:36.172  1753  4135 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 15:09:36.172  1753  4135 I SystemUpdateService: file has been verified
09-09 15:09:36.180  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 15:09:36.183  1753  4135 I SystemUpdateService: OTA package size = 12249756
,09-09 15:09:36.216  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 15:09:36.217  1753  2434 I iu.UploadsManager: num queued entries: 0
09-09 15:09:36.217  1753  2434 I iu.UploadsManager: num updated entries: 0
09-09 15:09:36.218  1753  2434 I iu.SyncManager: NEXT; no task
,09-09 15:09:36.234  1753  4135 I SystemUpdateService: showing system update notification
,09-09 15:09:36.252   875  4124 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 13:09:36 GMT], X-Android-Received-Millis=[1473426576251], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473426576229]}
,09-09 15:09:36.253   875  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 15:09:36.254   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-09 15:09:36.254   875  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 15:09:36.259   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 15:09:36.293  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 15:09:36.298  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 15:09:36.301  3974  3974 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 15:09:36.309  3974  3974 D SprintDMHelper: simOperator: 
,09-09 15:09:36.310  3974  3974 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 15:09:36.332  1753  4139 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 15:09:36.332  1753  4139 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 15:09:36.338  1753  4139 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 15:09:36.395  1542  4145 I VacuumService: Vacuum at: now=1473426576395 tag=VacuumService
,09-09 15:09:36.479  4000  4142 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 15:09:36.650  1542  4146 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-09 15:09:36.655  1542  4146 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 15:09:36.684  1753  1753 D SystemUpdateService: onDestroy
,09-09 15:09:36.734  1542  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 15:09:36.735  1542  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 15:09:36.735  1542  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:09:36.735  1542  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:36.743  1542  4146 W Uploader:  no longer exists, so no auth token.
,09-09 15:09:36.778  1753  4139 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-09 15:09:37.083   875  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 15:09:37.972  1542  4146 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 15:09:37.972  1542  4146 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 15:09:37.973  1542  4146 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 15:09:37.973  1542  4146 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:37.986  1542  4146 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 15:09:37.986  1542  4146 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 15:09:37.986  1542  4146 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 15:09:38.324  1542  4146 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 15:09:38.324  1542  4146 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 15:09:38.324  1542  4146 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:09:38.324  1542  4146 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:38.342  1542  4146 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 15:09:38.342  1542  4146 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 15:09:38.342  1542  4146 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 15:09:38.668   875  2022 D WifiService: setWifiEnabled: false pid=3819, uid=10000
,09-09 15:09:38.669   875  2022 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 15:09:38.688  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 15:09:38.694   875  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 15:09:38.694   875  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 15:09:38.694   875  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 15:09:38.695   875  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 15:09:38.717   875  1315 E native  : do suspend true
,09-09 15:09:38.727   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-09 15:09:38.729   875  1876 D DhcpClient: Clearing IP address
,09-09 15:09:38.733   373   873 D CommandListener: Setting iface cfg
,09-09 15:09:38.751   875  4126 D DhcpClient: Receive thread stopped
,09-09 15:09:38.744  1542  4144 V NativeCrypto: Read error: ssl=0x9a9d4000: I/O error during system call, Connection timed out
09-09 15:09:38.761   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 15:09:38.761   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-09 15:09:38.761   875  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
09-09 15:09:38.762   875  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 15:09:38.762   875  1315 E native  : do suspend true
09-09 15:09:38.766  1542  4144 V NativeCrypto: SSL shutdown failed: ssl=0x9a9d4000: I/O error during system call, Broken pipe
,09-09 15:09:38.767   396   396 E Parcel  : Reading a NULL string not supported here.
09-09 15:09:38.770   875  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 15:09:38.772   373   873 D CommandListener: Clearing all IP addresses on wlan0
09-09 15:09:38.775   875  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 15:09:38.790   875  1315 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 15:09:38.794  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:38.794  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:38.794  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:38.794  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:38.794  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:38.794  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:38.794  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:38.794  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:38.794  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:38.794  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:38.794  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:38.795   875  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 15:09:38.795  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:38.795  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:38.795  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:38.795  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:38.795  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:38.795  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:38.795  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:38.795  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:38.795  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 15:09:38.795  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:38.795  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:38.796  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:38.797  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:38.797  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:38.797  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:38.797  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:38.797  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:38.797  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:38.797  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:38.797  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:38.797  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:38.797  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:38.797  2174  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 15:09:38.808   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 15:09:38.818  1542  4146 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/172.217.20.138 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,09-09 15:09:38.836   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 15:09:38.837   875  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 15:09:38.837   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 15:09:38.839   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-09 15:09:38.846  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:38.847  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:38.848  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:38.857  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 15:09:38.860  1753  1753 D SystemUpdateService: onCreate
09-09 15:09:38.862  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-09 15:09:38.876  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 15:09:38.893  1753  4171 I SystemUpdateService: active receiver: enabled
,09-09 15:09:38.896  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 15:09:38.897  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 15:09:38.899  3974  3974 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 15:09:38.902  3974  3974 D SprintDMHelper: simOperator: 
,09-09 15:09:38.902  3974  3974 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 15:09:38.925   373   873 E Netd    : netlink response contains error (No such file or directory)
,09-09 15:09:38.926   875  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 15:09:38.878  1753  2434 I iu.UploadsManager: num queued entries: 0
,09-09 15:09:38.933  1753  2434 I iu.UploadsManager: num updated entries: 0
,09-09 15:09:38.933  4000  4175 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 15:09:38.937  1753  4171 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 15:09:38.940  1753  2434 I iu.SyncManager: NEXT; no task
,09-09 15:09:38.940  1753  4171 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 15:09:38.940  1753  4171 I SystemUpdateService: now status is 0 (complete)
09-09 15:09:38.940  1753  4171 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 15:09:38.940  1753  4171 I SystemUpdateService: file has been verified
,09-09 15:09:38.941  1753  4171 I SystemUpdateService: OTA package size = 12249756
,09-09 15:09:38.946  1753  4171 I SystemUpdateService: showing system update notification
,09-09 15:09:38.953  1753  1753 D SystemUpdateService: onDestroy
,09-09 15:09:43.721   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2538d26:true
,09-09 15:09:43.721  3958  3958 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 15:09:43.728  3958  3958 I bt_bluedroid: init
,09-09 15:09:43.729  3958  4178 I BluetoothAdapterState: Entering OffState
,09-09 15:09:43.731  3958  4179 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 15:09:43.731  3958  4179 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 15:09:43.731  3958  4179 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 15:09:43.731  3958  4179 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 15:09:43.732  3958  3958 I bt_bluedroid: get_profile_interface socket
,09-09 15:09:43.734  3958  3958 I bt_bluedroid: get_profile_interface sdp
,09-09 15:09:43.738  3958  4182 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-09 15:09:43.740  3958  3968 I bt_bluedroid: config_hci_snoop_log
09-09 15:09:43.742  3958  4182 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 15:09:43.743   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 15:09:43.755  3958  4178 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 15:09:43.756  3958  4178 D BluetoothAdapterProperties: Setting state to 14
09-09 15:09:43.756  3958  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 15:09:43.760  3958  4178 D BluetoothBondStateMachine: make
,09-09 15:09:43.764  3958  4183 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 15:09:43.771  3958  4178 I BluetoothAdapterState: Entering PendingCommandState
,09-09 15:09:43.775  3958  3958 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 15:09:43.781  3958  3958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
,09-09 15:09:43.785  3958  3958 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 15:09:43.786  3958  3958 D BtGatt.GattService: Received start request. Starting profile...
,09-09 15:09:43.787  3958  3958 D BtGatt.GattService: start()
,09-09 15:09:43.788  3958  3958 I bt_bluedroid: get_profile_interface gatt
,09-09 15:09:43.791  3958  3958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
,09-09 15:09:43.792  3958  3958 D BtGatt.AdvertiseManager: advertise manager created
,09-09 15:09:43.810  3958  3958 V BluetoothAdapterState: isTurningOff()=false
,09-09 15:09:43.810  3958  3958 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:43.810  3958  3958 V BluetoothAdapterState: isBleTurningOn()=true
,09-09 15:09:43.811  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:43.812  3958  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 15:09:43.814  3958  4178 I bt_bluedroid: enable
09-09 15:09:43.815  3958  4179 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 15:09:43.816  3958  4179 I bt_hci  : start_up
,09-09 15:09:43.835  3958  4179 I bt_vendor: alloc value 0xb39f9189
,09-09 15:09:43.835  3958  4179 I bt_vendor: init
09-09 15:09:43.836  3958  4179 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 15:09:43.836  3958  4179 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 15:09:43.943  3958  4179 D bt_hci  : start_up starting async portion
,09-09 15:09:43.944  3958  4186 I bt_hci  : event_finish_startup
,09-09 15:09:43.944  3958  4186 I bt_hci_h4: hal_open
09-09 15:09:43.945  3958  4186 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 15:09:43.956  3958  4186 I bt_userial_vendor: device fd = 51 open
,09-09 15:09:43.986  3958  4186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 15:09:44.018  3958  4186 D bt_hwcfg: Chipset BCM4354A2
09-09 15:09:44.018  3958  4186 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 15:09:44.019  3958  4186 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 15:09:44.037   875  1319 D ConnectivityService: handlePromptUnvalidated 101
,09-09 15:09:44.660  3958  4186 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 15:09:44.662  3958  4186 D bt_hwcfg: Settlement delay -- 100 ms
,09-09 15:09:44.662  3958  4186 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 15:09:44.779  3958  4186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 15:09:44.780  3958  4186 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 15:09:44.809  3958  4186 I bt_hwcfg: vendor lib fwcfg completed
,09-09 15:09:44.809  3958  4186 I bt_vendor: firmware callback
,09-09 15:09:44.810  3958  4186 I bt_hci  : firmware_config_callback
,09-09 15:09:44.821  3958  4190 I bt_btu  : btu_task pending for preload complete event
,09-09 15:09:44.822  3958  4190 I bt_btu_task: Bluetooth chip preload is complete
,09-09 15:09:44.822  3958  4190 I bt_btu  : btu_task received preload complete event
,09-09 15:09:44.832  3958  4190 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 15:09:44.832  3958  4190 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 15:09:44.832  3958  4190 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 15:09:44.833  3958  4190 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 15:09:44.833  3958  4190 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 15:09:44.833  3958  4190 I         : BTE_InitTraceLevels -- TRC_A2D
,09-09 15:09:44.833  3958  4190 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 15:09:44.834  3958  4190 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 15:09:44.834  3958  4190 I         : BTE_InitTraceLevels -- TRC_GAP
,09-09 15:09:44.834  3958  4190 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 15:09:44.834  3958  4190 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 15:09:44.835  3958  4190 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 15:09:44.835  3958  4190 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 15:09:44.835  3958  4190 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 15:09:44.835  3958  4190 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 15:09:44.969  3958  4190 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,09-09 15:09:44.969  3958  4190 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,09-09 15:09:45.003  3958  4182 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 15:09:45.005  3958  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 15:09:45.006  3958  4182 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 15:09:45.008  3958  4182 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 15:09:45.010  3958  4182 D BluetoothAdapterProperties: Scan Mode:20
,09-09 15:09:45.011  3958  4182 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 15:09:45.011  3958  4182 D bt_hci  : do_postload posting postload work item
09-09 15:09:45.012  3958  4186 I bt_hci  : event_postload
,09-09 15:09:45.012  3958  4186 I bt_vendor: sco_config_cb
,09-09 15:09:45.012  3958  4186 I bt_hci  : sco_config_callback postload finished.
09-09 15:09:45.013  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:45.014  3958  4182 D bt_bte_conf: Device ID record 1 : primary
09-09 15:09:45.015  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:45.014  3958  4182 D bt_bte_conf:   vendorId            = 000f
,09-09 15:09:45.015  3958  4182 D bt_bte_conf:   vendorIdSource      = 0001
09-09 15:09:45.015  3958  4182 D bt_bte_conf:   product             = 1200
09-09 15:09:45.016  3958  4182 D bt_bte_conf:   version             = 1436
,09-09 15:09:45.016  3958  4182 D bt_bte_conf:   clientExecutableURL = 
,09-09 15:09:45.016  3958  4182 D bt_bte_conf:   serviceDescription  = 
,09-09 15:09:45.016  3958  4182 D bt_bte_conf:   documentationURL    = 
09-09 15:09:45.017  3958  4182 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 15:09:45.017  3958  4179 D bt_stack_manager: event_start_up_stack finished
09-09 15:09:45.017  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:45.020  3958  4186 I bt_vendor: low_power_mode_cb
09-09 15:09:45.020  3958  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-09 15:09:45.020  3958  4178 D BluetoothAdapterProperties: Setting state to 15
09-09 15:09:45.021  3958  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 15:09:45.021  3958  4178 I BluetoothAdapterState: Entering BleOnState
09-09 15:09:45.026  3958  4178 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 15:09:45.026  3958  4178 D BluetoothAdapterProperties: Setting state to 11
09-09 15:09:45.026  3958  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 15:09:45.035  3958  3958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
09-09 15:09:45.036  3958  3958 D HeadsetService: Received start request. Starting profile...
09-09 15:09:45.039  3958  3958 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 15:09:45.039  3958  3958 D HeadsetStateMachine: make
,09-09 15:09:45.040  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:45.042  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:45.044  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:45.051  3958  3958 D HeadsetStateMachine: max_hf_connections = 1
09-09 15:09:45.051  3958  3958 I bt_bluedroid: get_profile_interface handsfree
09-09 15:09:45.051  3958  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 15:09:45.052  3958  4182 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 15:09:45.056  3958  3958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
,09-09 15:09:45.057  3958  3958 D A2dpService: Received start request. Starting profile...
09-09 15:09:45.057  3958  4178 I BluetoothAdapterState: Entering PendingCommandState
09-09 15:09:45.057  3958  3958 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 15:09:45.058  3958  3958 I bt_bluedroid: get_profile_interface avrcp
,09-09 15:09:45.064  3958  3958 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 15:09:45.064  3958  3958 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 15:09:45.064  3958  3958 D A2dpStateMachine: make
,09-09 15:09:45.066  3958  3958 I bt_bluedroid: get_profile_interface a2dp
,09-09 15:09:45.066  3958  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-09 15:09:45.068  3958  3958 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 15:09:45.068  3958  4199 D A2dpStateMachine: Enter Disconnected: -2
09-09 15:09:45.069  3958  3958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
09-09 15:09:45.070  1542  1542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 15:09:45.074  3905  3905 D BluetoothInputDevice: Proxy object connected
,09-09 15:09:45.074  3958  3958 D HidService: Received start request. Starting profile...
09-09 15:09:45.074  3958  3958 I bt_bluedroid: get_profile_interface hidhost
09-09 15:09:45.074  3958  3958 D HidService: setHidService(): set to: null
,09-09 15:09:45.074  3905  3905 D HidProfile: Bluetooth service connected
09-09 15:09:45.074  3958  4182 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
09-09 15:09:45.074  3958  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-09 15:09:45.075  3958  3958 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 15:09:45.076  3958  3958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
09-09 15:09:45.076  3958  3958 D HealthService: Received start request. Starting profile...
,09-09 15:09:45.078  3958  3958 I bt_bluedroid: get_profile_interface health
,09-09 15:09:45.079  3958  3958 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 15:09:45.079  3958  3958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
,09-09 15:09:45.080  3958  3958 V BluetoothAdapterState: isTurningOff()=false
09-09 15:09:45.080  3958  3958 V BluetoothAdapterState: isTurningOn()=true
09-09 15:09:45.080  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 15:09:45.080  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:45.081  3905  3905 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 15:09:45.081  3905  3905 D PanProfile: Bluetooth service connected
,09-09 15:09:45.082  3958  3958 D PanService: Received start request. Starting profile...
09-09 15:09:45.083  3958  3958 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 15:09:45.083  3958  3958 I bt_bluedroid: get_profile_interface pan
,09-09 15:09:45.084  3958  4182 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 15:09:45.085  3958  4196 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 15:09:45.087  3958  3958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
,09-09 15:09:45.088  3958  3958 D BluetoothMapService: Received start request. Starting profile...
,09-09 15:09:45.088  3958  3958 D BluetoothMapService: start()
,09-09 15:09:45.088  3905  3905 D BluetoothMap: Proxy object connected
,09-09 15:09:45.089  3905  3905 D MapProfile: Bluetooth service connected
09-09 15:09:45.089  3905  3905 D BluetoothMap: getConnectedDevices()
,09-09 15:09:45.090  3905  3905 D BluetoothMap: Bluetooth is Not enabled
,09-09 15:09:45.090  3958  3958 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-09 15:09:45.091  3958  3958 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 15:09:45.091  3958  3958 D BluetoothMapAppObserver: createReceiver()
,09-09 15:09:45.092  3958  3958 D BluetoothMapAppObserver: initObservers()
,09-09 15:09:45.092  3958  3958 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 15:09:45.097  3958  3958 V BluetoothAdapterState: isTurningOff()=false
,09-09 15:09:45.097  3958  3958 V BluetoothAdapterState: isTurningOn()=true
,09-09 15:09:45.097  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 15:09:45.098  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 15:09:45.099  3958  3958 V BluetoothAdapterState: isTurningOff()=false
,09-09 15:09:45.099  3958  3958 V BluetoothAdapterState: isTurningOn()=true
,09-09 15:09:45.099  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 15:09:45.099  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 15:09:45.099  3958  3958 V BluetoothAdapterState: isTurningOff()=false
09-09 15:09:45.099  3958  3958 V BluetoothAdapterState: isTurningOn()=true
09-09 15:09:45.099  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:45.099  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:45.100  3958  3958 V BluetoothAdapterState: isTurningOff()=false
09-09 15:09:45.100  3958  3958 V BluetoothAdapterState: isTurningOn()=true
,09-09 15:09:45.100  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 15:09:45.100  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:45.100  3958  3958 V BluetoothAdapterState: isTurningOff()=false
09-09 15:09:45.100  3958  3958 V BluetoothAdapterState: isTurningOn()=true
,09-09 15:09:45.100  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:45.100  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 15:09:45.101  3958  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 15:09:45.101  3958  4178 D BluetoothAdapterProperties: ScanMode =  20
09-09 15:09:45.101  3958  4178 D BluetoothAdapterProperties: State =  11
,09-09 15:09:45.104  3958  4182 D BluetoothAdapterProperties: Scan Mode:21
09-09 15:09:45.104  3958  4178 D BluetoothAdapterProperties: Setting state to 12
,09-09 15:09:45.104  3958  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 15:09:45.105   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 15:09:45.105  3958  4178 I BluetoothAdapterState: Entering OnState
,09-09 15:09:45.105  1372  1384 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 15:09:45.107  3905  3915 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 15:09:45.107  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:45.107  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:45.107  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:45.107  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:45.107  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:09:45.107  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:45.107  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:45.107  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:45.108  3958  4182 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 15:09:45.109  3905  3916 D BluetoothPan: onBluetoothStateChange on: true
09-09 15:09:45.110   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 15:09:45.110  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,09-09 15:09:45.110  1372  1383 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 15:09:45.112  3905  3915 D BluetoothMap: onBluetoothStateChange: up=true
09-09 15:09:45.112   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 15:09:45.112   875   875 D BluetoothA2dp: Proxy object connected
09-09 15:09:45.113  1372  3917 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 15:09:45.115  1372  1372 D BluetoothInputDevice: Proxy object connected
,09-09 15:09:45.116  1372  1372 D HidProfile: Bluetooth service connected
09-09 15:09:45.117  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:45.117  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:45.117  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:45.117  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:45.117  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:09:45.117  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:45.117  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:45.117  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:45.117  1372  1384 D BluetoothPan: onBluetoothStateChange on: true
,09-09 15:09:45.118  3958  3958 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 15:09:45.119  3958  3958 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 15:09:45.120  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 15:09:45.120  1372  2219 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 15:09:45.120  1372  1372 D PanProfile: Bluetooth service connected
09-09 15:09:45.121  1372  1372 D BluetoothA2dp: Proxy object connected
09-09 15:09:45.121  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:45.121  1947  2087 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 15:09:45.121  3958  3958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 15:09:45.122  1372  1384 D BluetoothMap: onBluetoothStateChange: up=true
09-09 15:09:45.123  1372  1372 D BluetoothMap: Proxy object connected
09-09 15:09:45.123  1372  1372 D MapProfile: Bluetooth service connected
09-09 15:09:45.123  1372  1372 D BluetoothMap: getConnectedDevices()
09-09 15:09:45.124  3905  3916 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 15:09:45.124   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 15:09:45.124  3958  3958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 15:09:45.125   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 15:09:45.127  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:45.127  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:45.127  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:45.127  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:45.127  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:09:45.127  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:45.127  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:45.127  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:45.127  3958  3958 D ObexServerSockets: Succeed to create listening sockets 
09-09 15:09:45.127  3958  3958 D ObexServerSockets0: startAccept()
09-09 15:09:45.128  3958  3958 D ObexServerSockets0: prepareForNewConnect()
,09-09 15:09:45.131  3905  3905 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 15:09:45.131  3958  3958 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 15:09:45.131  3958  3958 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 15:09:45.131  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:45.132  3958  3958 D BluetoothMapService: onReceive
09-09 15:09:45.132  3958  3958 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 15:09:45.132  3958  3958 D BluetoothMapService: STATE_ON
,09-09 15:09:45.133  3958  4206 D ObexServerSockets0: Accepting socket connection...
09-09 15:09:45.133  3958  4207 D ObexServerSockets0: Accepting socket connection...
,09-09 15:09:45.137  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:45.139  3905  3905 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 15:09:45.140  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:45.141  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:45.144  3905  3905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 15:09:45.147  3905  3905 D BluetoothA2dp: Proxy object connected
,09-09 15:09:45.150  1542  1542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 15:09:45.155  3905  3905 D DockEventReceiver: finishStartingService: stopping service
,09-09 15:09:45.160  1372  1372 D BluetoothPbap: Proxy object connected
,09-09 15:09:45.160  1372  1372 D PbapServerProfile: Bluetooth service connected
09-09 15:09:45.161  3905  3905 D BluetoothPbap: Proxy object connected
09-09 15:09:45.161  3958  3958 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 15:09:45.161  3905  3905 D PbapServerProfile: Bluetooth service connected
09-09 15:09:45.161  3958  3958 D ObexServerSockets0: prepareForNewConnect()
,09-09 15:09:45.173  3958  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 15:09:45.193  3958  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 15:09:45.195  3958  4215 I BtOppRfcommListener: Accept thread started.
,09-09 15:09:45.207   875   875 D BluetoothHeadset: Proxy object connected
,09-09 15:09:45.207  1947  1958 D BluetoothHeadset: Proxy object connected
,09-09 15:09:45.208   875   875 D BluetoothHeadset: Proxy object connected
,09-09 15:09:45.208  1372  3917 D BluetoothHeadset: Proxy object connected
09-09 15:09:45.209  1372  1372 D HeadsetProfile: Bluetooth service connected
09-09 15:09:45.209   875   875 D BluetoothHeadset: Proxy object connected
,09-09 15:09:45.212  1372  1384 D BluetoothHeadset: Proxy object connected
,09-09 15:09:45.212  1372  1372 D HeadsetProfile: Bluetooth service connected
09-09 15:09:45.213   875   892 D BluetoothHeadset: Proxy object connected
,09-09 15:09:45.222  1947  1965 D BluetoothHeadset: Proxy object connected
,09-09 15:09:45.224   875   892 D BluetoothHeadset: Proxy object connected
,09-09 15:09:45.241  3905  3915 D BluetoothHeadset: Proxy object connected
,09-09 15:09:45.242  3905  3905 D HeadsetProfile: Bluetooth service connected
,09-09 15:09:48.685  3958  4178 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 15:09:48.685  3958  4178 D BluetoothAdapterProperties: Setting state to 13
,09-09 15:09:48.686  3958  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 15:09:48.688  3958  4178 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 15:09:48.699  3958  3958 D BluetoothMapService: onReceive
,09-09 15:09:48.700  3958  3958 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 15:09:48.700  3958  3958 D BluetoothMapService: STATE_TURNING_OFF
09-09 15:09:48.700  3958  3958 D BluetoothMapService: MAP Service closeService in
09-09 15:09:48.701  3958  4178 I BluetoothAdapterState: Entering PendingCommandState
09-09 15:09:48.701  3958  3958 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 15:09:48.701  3958  3958 D ObexServerSockets0: shutdown(block = true)
09-09 15:09:48.702  3958  4206 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 15:09:48.704  3958  3958 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 15:09:48.705  3958  4207 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 15:09:48.707  3958  4192 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 15:09:48.708  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 15:09:48.708  3958  3958 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 15:09:48.708  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:48.708  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:48.708  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:48.708  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:48.708  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:48.708  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:48.708  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:48.708  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:48.708  3958  3958 I BtOppRfcommListener: stopping Accept Thread
09-09 15:09:48.709  3958  4215 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 15:09:48.710  3958  4215 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 15:09:48.713  3958  4182 D BluetoothAdapterProperties: Scan Mode:20
,09-09 15:09:48.713  3958  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 15:09:48.716  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:48.717  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:48.720  3958  3958 D HeadsetService: Received stop request...Stopping profile...
09-09 15:09:48.721  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:48.722  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:48.722  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:48.722  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:48.722  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:48.722  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:48.722  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:48.722  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:48.722  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 15:09:48.722   875   875 D BluetoothHeadset: Proxy object disconnected
09-09 15:09:48.723  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:48.723  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:48.723  1947  1958 D BluetoothHeadset: Proxy object disconnected
09-09 15:09:48.723  3958  3958 D A2dpService: Received stop request...Stopping profile...
09-09 15:09:48.724  3958  4199 D A2dpStateMachine: Exit Disconnected: -1
09-09 15:09:48.724   875   875 D BluetoothHeadset: Proxy object disconnected
,09-09 15:09:48.724  3905  3916 D BluetoothHeadset: Proxy object disconnected
09-09 15:09:48.725  1372  1384 D BluetoothHeadset: Proxy object disconnected
,09-09 15:09:48.725   875   875 D BluetoothHeadset: Proxy object disconnected
09-09 15:09:48.726   875   875 D BluetoothA2dp: Proxy object disconnected
09-09 15:09:48.726  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:48.726  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:09:48.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:09:48.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:09:48.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:09:48.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 15:09:48.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:09:48.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:09:48.726  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:09:48.726  1372  1372 D HeadsetProfile: Bluetooth service disconnected
,09-09 15:09:48.727  3905  3905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 15:09:48.727  1372  1372 D BluetoothA2dp: Proxy object disconnected
09-09 15:09:48.727  3819  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 15:09:48.727  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:09:48.729  3958  3958 D HidService: Received stop request...Stopping profile...
09-09 15:09:48.729  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:48.729  3958  3958 D HidService: Stopping Bluetooth HidService
09-09 15:09:48.730  1372  1372 D BluetoothInputDevice: Proxy object disconnected
,09-09 15:09:48.730  1372  1372 D HidProfile: Bluetooth service disconnected
09-09 15:09:48.731  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:48.732  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:48.733  3958  3958 D HealthService: Received stop request...Stopping profile...
09-09 15:09:48.730  3905  3905 D HeadsetProfile: Bluetooth service disconnected
09-09 15:09:48.734  3905  3905 D BluetoothA2dp: Proxy object disconnected
09-09 15:09:48.734  3905  3905 D BluetoothInputDevice: Proxy object disconnected
09-09 15:09:48.734  3905  3905 D HidProfile: Bluetooth service disconnected
,09-09 15:09:48.735  3958  3958 D PanService: Received stop request...Stopping profile...
09-09 15:09:48.736  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 15:09:48.736  1372  1372 D PanProfile: Bluetooth service disconnected
09-09 15:09:48.737  3958  3958 V BluetoothAdapterState: isTurningOff()=true
,09-09 15:09:48.737  3958  3958 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:48.737  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:48.737  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:48.738  3958  3958 D BluetoothMapService: Received stop request...Stopping profile...
09-09 15:09:48.738  3958  3958 D BluetoothMapService: stop()
09-09 15:09:48.739  3958  3958 D BluetoothMapAppObserver: deinitObservers()
09-09 15:09:48.739  3958  3958 D BluetoothMapAppObserver: removeReceiver()
,09-09 15:09:48.741  1372  1372 D BluetoothMap: Proxy object disconnected
09-09 15:09:48.741  1372  1372 D MapProfile: Bluetooth service disconnected
,09-09 15:09:48.743  3905  3905 D DockEventReceiver: finishStartingService: stopping service
,09-09 15:09:48.743  3958  3958 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-09 15:09:48.744  3958  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:48.744  3958  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:48.744  3958  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 15:09:48.745  3905  3905 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 15:09:48.743  3958  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 15:09:48.745  3958  4182 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 15:09:48.745  3958  3958 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 15:09:48.745  3905  3905 D PanProfile: Bluetooth service disconnected
,09-09 15:09:48.746  3958  3958 V BluetoothAdapterState: isTurningOff()=true
09-09 15:09:48.746  3958  3958 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:48.746  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 15:09:48.746  3905  3905 D BluetoothMap: Proxy object disconnected
09-09 15:09:48.747  3905  3905 D MapProfile: Bluetooth service disconnected
09-09 15:09:48.747  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:48.749  3958  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:48.749  3958  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:48.749  3958  4190 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 15:09:48.749  3958  4190 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 15:09:48.749  3958  4190 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 15:09:48.750  3958  4190 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 15:09:48.750  3958  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 15:09:48.750  3958  3958 V BluetoothAdapterState: isTurningOff()=true
,09-09 15:09:48.750  3958  3958 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:48.751  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:48.751  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 15:09:48.751  3958  3958 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 15:09:48.752  3958  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 15:09:48.752  3958  3958 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 15:09:48.756  3958  3958 V BluetoothAdapterState: isTurningOff()=true
,09-09 15:09:48.756  3958  3958 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:48.756  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:48.756  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:48.756  1542  1542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 15:09:48.756  3958  3958 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 15:09:48.756  3958  4182 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 15:09:48.757  3958  3958 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 15:09:48.757  3958  3958 V BluetoothAdapterState: isTurningOff()=true
,09-09 15:09:48.757  3958  3958 V BluetoothAdapterState: isTurningOn()=false
,09-09 15:09:48.757  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:48.757  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 15:09:48.757  3958  3958 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-09 15:09:48.758  3958  3958 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 15:09:48.758  3958  3958 D BluetoothMapService: MAP Service closeService in
09-09 15:09:48.759  3958  3958 V BluetoothAdapterState: isTurningOff()=true
,09-09 15:09:48.759  3958  3958 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:48.759  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:48.759  3958  3958 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:48.759  3958  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-09 15:09:48.759  3958  4178 D BluetoothAdapterProperties: Setting state to 15
09-09 15:09:48.759  3958  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 15:09:48.760   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 15:09:48.760  3958  3958 D BluetoothMapService: cleanup()
,09-09 15:09:48.760  3958  3958 D BluetoothMapService: MAP Service closeService in
09-09 15:09:48.760  3905  4219 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 15:09:48.761  3958  4178 I BluetoothAdapterState: Entering BleOnState
09-09 15:09:48.761  1372  1383 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 15:09:48.762  3905  4219 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 15:09:48.763  3905  3905 D BluetoothPbap: Proxy object disconnected
,09-09 15:09:48.763  3905  3905 D PbapServerProfile: Bluetooth service disconnected
09-09 15:09:48.765  3905  3915 D BluetoothPan: onBluetoothStateChange on: false
09-09 15:09:48.766   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 15:09:48.766  1372  2219 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 15:09:48.766  3905  3916 D BluetoothMap: onBluetoothStateChange: up=false
09-09 15:09:48.767   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 15:09:48.767  1372  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 15:09:48.770  1372  3917 D BluetoothPan: onBluetoothStateChange on: false
,09-09 15:09:48.771  1372  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 15:09:48.772  1947  1965 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 15:09:48.772  1372  2219 D BluetoothMap: onBluetoothStateChange: up=false
09-09 15:09:48.773  3905  4219 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 15:09:48.773  3905  3915 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 15:09:48.774   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 15:09:48.774  3958  4178 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-09 15:09:48.774  3958  4178 D BluetoothAdapterProperties: Setting state to 16
,09-09 15:09:48.774  3958  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 15:09:48.775  3958  4178 D BluetoothAdapterProperties: onBleDisable
09-09 15:09:48.775  3958  4178 I BluetoothAdapterState: Entering PendingCommandState
09-09 15:09:48.776  3958  4179 D bt_stack_manager: event_shut_down_stack is bringing down the stack.,
09-09 15:09:48.776  3958  4190 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 15:09:48.777  3958  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 15:09:48.778  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:48.779  3958  4182 D BluetoothAdapterProperties: Scan Mode:20
,09-09 15:09:48.780  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:48.780  3905  3905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 15:09:48.781  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:48.784  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:48.785  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:09:48.786  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:48.787  1542  1542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 15:09:48.793  3905  3905 D DockEventReceiver: finishStartingService: stopping service
,09-09 15:09:48.982  3958  4182 I bt_hci  : shut_down
,09-09 15:09:48.983  3958  4186 D bt_hwcfg: hw_epilog_process
,09-09 15:09:48.984  3958  4186 I bt_vendor: low_power_mode_cb
,09-09 15:09:49.015  3958  4186 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 15:09:49.016  3958  4186 I bt_vendor: epilog_cb
09-09 15:09:49.016  3958  4186 I bt_hci  : epilog_finished_callback
,09-09 15:09:49.027  3958  4182 I bt_hci_h4: hal_close
,09-09 15:09:49.029  3958  4182 I bt_userial_vendor: device fd = 51 close
,09-09 15:09:49.145  3958  4179 D bt_stack_manager: event_shut_down_stack finished.
,09-09 15:09:49.146  3958  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 15:09:49.156  3958  3958 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 15:09:49.157  3958  4178 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 15:09:49.157  3958  3958 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 15:09:49.158  3958  3958 D BtGatt.GattService: stop()
09-09 15:09:49.158  3958  3958 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 15:09:49.163  3958  3958 V BluetoothAdapterState: isTurningOff()=false
,09-09 15:09:49.163  3958  3958 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:49.164  3958  3958 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:09:49.164  3958  3958 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 15:09:49.165  3958  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 15:09:49.165  3958  4178 D BluetoothAdapterProperties: Setting state to 10
09-09 15:09:49.166  3958  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 15:09:49.168  3958  4178 I BluetoothAdapterState: Entering OffState
,09-09 15:09:49.169   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 15:09:49.199  3958  3958 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 15:09:49.200  3958  3958 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 15:09:49.200  3958  4179 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 15:09:49.207  3958  4179 D bt_stack_manager: event_clean_up_stack finished.
,09-09 15:09:49.207  3958  3958 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 15:09:49.213  3958  3958 I art     : System.exit called, status: 0
,09-09 15:09:49.213  3958  3958 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 15:09:49.271   875  1391 I ActivityManager: Process com.android.bluetooth (pid 3958) has died
,09-09 15:09:53.683  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:53.683  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:53.688  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:09:53.688  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba30d8c removed from the list
,09-09 15:09:53.689  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 15:09:53.689  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:53.689  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:53.692  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 15:09:53.693  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7adcea added. We now have 4 listener(s)
09-09 15:09:53.693  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:09:53.695  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:09:53.695  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7adcea removed from the list
09-09 15:09:53.695  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:09:53.696  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:09:53.696  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:09:53.698  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 15:09:53.699  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c9b8bdb added. We now have 4 listener(s)
,09-09 15:09:53.699  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:09:55.849  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:09:55.859  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:09:55.863  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:09:55.912  1542  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 15:09:55.912  1542  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 15:09:55.913  1542  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:09:55.913  1542  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:09:55.972  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 15:09:55.973  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 15:09:55.974  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-09 15:09:58.711  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:09:58.764   875   892 I ActivityManager: Start proc 4227:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 15:09:58.952  4227  4227 D AdapterServiceConfig: Adding HeadsetService
09-09 15:09:58.952  4227  4227 D AdapterServiceConfig: Adding A2dpService
09-09 15:09:58.952  4227  4227 D AdapterServiceConfig: Adding HidService
09-09 15:09:58.953  4227  4227 D AdapterServiceConfig: Adding HealthService
09-09 15:09:58.953  4227  4227 D AdapterServiceConfig: Adding PanService
09-09 15:09:58.953  4227  4227 D AdapterServiceConfig: Adding GattService
09-09 15:09:58.953  4227  4227 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 15:09:58.967  4227  4227 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 15:09:58.967   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91d2d6c:true
,09-09 15:09:58.972  4227  4227 I bt_bluedroid: init
09-09 15:09:58.973  4227  4239 I BluetoothAdapterState: Entering OffState
,09-09 15:09:58.979  4227  4240 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 15:09:58.979  4227  4240 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 15:09:58.980  4227  4240 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 15:09:58.980  4227  4240 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 15:09:58.982  4227  4227 I bt_bluedroid: get_profile_interface socket
,09-09 15:09:58.985  4227  4243 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 15:09:58.987  4227  4227 I bt_bluedroid: get_profile_interface sdp
,09-09 15:09:58.988  4227  4243 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 15:09:58.996  4227  4238 I bt_bluedroid: config_hci_snoop_log
,09-09 15:09:58.998   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 15:09:59.010  4227  4239 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 15:09:59.010  4227  4239 D BluetoothAdapterProperties: Setting state to 14
,09-09 15:09:59.011  4227  4239 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 15:09:59.015  4227  4239 D BluetoothBondStateMachine: make
,09-09 15:09:59.023  4227  4244 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 15:09:59.030  4227  4239 I BluetoothAdapterState: Entering PendingCommandState
,09-09 15:09:59.033  4227  4227 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 15:09:59.044  4227  4227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
,09-09 15:09:59.046  4227  4227 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 15:09:59.048  4227  4227 D BtGatt.GattService: Received start request. Starting profile...
,09-09 15:09:59.049  4227  4227 D BtGatt.GattService: start()
09-09 15:09:59.050  4227  4227 I bt_bluedroid: get_profile_interface gatt
09-09 15:09:59.051  4227  4227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
09-09 15:09:59.051  4227  4227 D BtGatt.AdvertiseManager: advertise manager created
,09-09 15:09:59.062  4227  4227 V BluetoothAdapterState: isTurningOff()=false
,09-09 15:09:59.062  4227  4227 V BluetoothAdapterState: isTurningOn()=false
09-09 15:09:59.062  4227  4227 V BluetoothAdapterState: isBleTurningOn()=true
09-09 15:09:59.063  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:09:59.063  4227  4239 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 15:09:59.063  4227  4239 I bt_bluedroid: enable
,09-09 15:09:59.064  4227  4240 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 15:09:59.065  4227  4240 I bt_hci  : start_up
,09-09 15:09:59.081  4227  4240 I bt_vendor: alloc value 0xb3a5a189
09-09 15:09:59.081  4227  4240 I bt_vendor: init
09-09 15:09:59.081  4227  4240 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 15:09:59.081  4227  4240 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 15:09:59.192  4227  4240 D bt_hci  : start_up starting async portion
,09-09 15:09:59.193  4227  4247 I bt_hci  : event_finish_startup
09-09 15:09:59.193  4227  4247 I bt_hci_h4: hal_open
09-09 15:09:59.194  4227  4247 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 15:09:59.208  4227  4247 I bt_userial_vendor: device fd = 51 open
,09-09 15:09:59.234  4227  4247 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 15:09:59.265  4227  4247 D bt_hwcfg: Chipset BCM4354A2
,09-09 15:09:59.266  4227  4247 D bt_hwcfg: Target name = [BCM4354A2]
09-09 15:09:59.266  4227  4247 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 15:10:00.061  4227  4247 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 15:10:00.062  4227  4247 D bt_hwcfg: Settlement delay -- 100 ms
09-09 15:10:00.063  4227  4247 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 15:10:00.180  4227  4247 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 15:10:00.181  4227  4247 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 15:10:00.210  4227  4247 I bt_hwcfg: vendor lib fwcfg completed
,09-09 15:10:00.211  4227  4247 I bt_vendor: firmware callback
09-09 15:10:00.211  4227  4247 I bt_hci  : firmware_config_callback
,09-09 15:10:00.223  4227  4249 I bt_btu  : btu_task pending for preload complete event
,09-09 15:10:00.223  4227  4249 I bt_btu_task: Bluetooth chip preload is complete
09-09 15:10:00.223  4227  4249 I bt_btu  : btu_task received preload complete event
,09-09 15:10:00.233  4227  4249 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 15:10:00.233  4227  4249 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 15:10:00.233  4227  4249 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 15:10:00.234  4227  4249 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 15:10:00.234  4227  4249 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 15:10:00.234  4227  4249 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 15:10:00.236  4227  4249 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 15:10:00.236  4227  4249 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 15:10:00.236  4227  4249 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 15:10:00.236  4227  4249 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 15:10:00.237  4227  4249 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 15:10:00.237  4227  4249 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 15:10:00.237  4227  4249 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 15:10:00.238  4227  4249 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 15:10:00.238  4227  4249 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 15:10:00.373  4227  4249 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d7d9d
,09-09 15:10:00.373  4227  4249 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d7d9d 
,09-09 15:10:00.385  4227  4243 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 15:10:00.386  4227  4243 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 15:10:00.387  4227  4243 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 15:10:00.392  4227  4243 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 15:10:00.395  4227  4243 D BluetoothAdapterProperties: Scan Mode:20
09-09 15:10:00.395  4227  4243 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 15:10:00.396  4227  4243 D bt_hci  : do_postload posting postload work item
,09-09 15:10:00.396  4227  4247 I bt_hci  : event_postload
,09-09 15:10:00.396  4227  4247 I bt_vendor: sco_config_cb
09-09 15:10:00.396  4227  4247 I bt_hci  : sco_config_callback postload finished.
,09-09 15:10:00.398  4227  4243 D bt_bte_conf: Device ID record 1 : primary
,09-09 15:10:00.399  4227  4243 D bt_bte_conf:   vendorId            = 000f
,09-09 15:10:00.399  4227  4243 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 15:10:00.399  4227  4243 D bt_bte_conf:   product             = 1200
09-09 15:10:00.399  4227  4243 D bt_bte_conf:   version             = 1436
09-09 15:10:00.399  4227  4243 D bt_bte_conf:   clientExecutableURL = 
09-09 15:10:00.400  4227  4243 D bt_bte_conf:   serviceDescription  = 
09-09 15:10:00.400  4227  4243 D bt_bte_conf:   documentationURL    = 
,09-09 15:10:00.400  4227  4243 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 15:10:00.400  4227  4240 D bt_stack_manager: event_start_up_stack finished
,09-09 15:10:00.401  4227  4247 I bt_vendor: low_power_mode_cb
09-09 15:10:00.402  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:10:00.402  4227  4239 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 15:10:00.403  4227  4239 D BluetoothAdapterProperties: Setting state to 15
09-09 15:10:00.403  4227  4239 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 15:10:00.405  4227  4239 I BluetoothAdapterState: Entering BleOnState
09-09 15:10:00.406  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:10:00.410  4227  4239 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 15:10:00.410  4227  4239 D BluetoothAdapterProperties: Setting state to 11
,09-09 15:10:00.410  4227  4239 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 15:10:00.418  4227  4227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
09-09 15:10:00.419  4227  4227 D HeadsetService: Received start request. Starting profile...
,09-09 15:10:00.421  4227  4227 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 15:10:00.422  4227  4227 D HeadsetStateMachine: make
,09-09 15:10:00.429  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:10:00.433  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:10:00.434  4227  4239 I BluetoothAdapterState: Entering PendingCommandState
,09-09 15:10:00.440  4227  4227 D HeadsetStateMachine: max_hf_connections = 1
,09-09 15:10:00.440  4227  4227 I bt_bluedroid: get_profile_interface handsfree
09-09 15:10:00.440  4227  4243 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 15:10:00.441  4227  4243 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 15:10:00.444  4227  4227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
,09-09 15:10:00.445  4227  4227 D A2dpService: Received start request. Starting profile...
09-09 15:10:00.445  4227  4227 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 15:10:00.446  4227  4227 I bt_bluedroid: get_profile_interface avrcp,
,09-09 15:10:00.451  4227  4227 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 15:10:00.452  4227  4227 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 15:10:00.452  4227  4227 D A2dpStateMachine: make
,09-09 15:10:00.453  4227  4227 I bt_bluedroid: get_profile_interface a2dp
09-09 15:10:00.453  4227  4243 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 15:10:00.455  4227  4258 D A2dpStateMachine: Enter Disconnected: -2
,09-09 15:10:00.455  4227  4227 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 15:10:00.456  4227  4227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
09-09 15:10:00.457  4227  4227 D HidService: Received start request. Starting profile...
,09-09 15:10:00.457  4227  4227 I bt_bluedroid: get_profile_interface hidhost
09-09 15:10:00.457  4227  4227 D HidService: setHidService(): set to: null
09-09 15:10:00.457  4227  4243 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b93e5
09-09 15:10:00.457  4227  4243 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 15:10:00.458  4227  4227 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 15:10:00.458  4227  4227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
09-09 15:10:00.459  4227  4227 D HealthService: Received start request. Starting profile...
,09-09 15:10:00.460  4227  4227 I bt_bluedroid: get_profile_interface health
09-09 15:10:00.461  4227  4227 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 15:10:00.461  4227  4227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
09-09 15:10:00.462  4227  4227 D PanService: Received start request. Starting profile...
09-09 15:10:00.462  4227  4227 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 15:10:00.462  4227  4227 I bt_bluedroid: get_profile_interface pan
,09-09 15:10:00.463  4227  4243 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 15:10:00.465  4227  4227 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
09-09 15:10:00.466  4227  4227 D BluetoothMapService: Received start request. Starting profile...
09-09 15:10:00.466  4227  4227 D BluetoothMapService: start()
,09-09 15:10:00.468  4227  4227 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 15:10:00.468  4227  4227 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 15:10:00.468  4227  4227 D BluetoothMapAppObserver: createReceiver()
,09-09 15:10:00.469  4227  4227 D BluetoothMapAppObserver: initObservers()
09-09 15:10:00.470  4227  4227 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 15:10:00.478  1542  1542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 15:10:00.479  4227  4227 V BluetoothAdapterState: isTurningOff()=false
,09-09 15:10:00.479  4227  4227 V BluetoothAdapterState: isTurningOn()=true
09-09 15:10:00.480  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:10:00.480  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 15:10:00.481  4227  4227 V BluetoothAdapterState: isTurningOff()=false
09-09 15:10:00.481  4227  4227 V BluetoothAdapterState: isTurningOn()=true
09-09 15:10:00.481  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 15:10:00.481  4227  4255 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 15:10:00.481  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 15:10:00.481  4227  4227 V BluetoothAdapterState: isTurningOff()=false
,09-09 15:10:00.481  4227  4227 V BluetoothAdapterState: isTurningOn()=true
09-09 15:10:00.481  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isTurningOff()=false
09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isTurningOn()=true
09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isTurningOff()=false
09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isTurningOn()=true
09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isTurningOff()=false
,09-09 15:10:00.482  4227  4227 V BluetoothAdapterState: isTurningOn()=true
09-09 15:10:00.483  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
09-09 15:10:00.483  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
09-09 15:10:00.483  4227  4239 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 15:10:00.483  4227  4239 D BluetoothAdapterProperties: ScanMode =  20
09-09 15:10:00.483  4227  4239 D BluetoothAdapterProperties: State =  11
09-09 15:10:00.485  4227  4243 D BluetoothAdapterProperties: Scan Mode:21
09-09 15:10:00.485  4227  4243 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 15:10:00.486  4227  4239 D BluetoothAdapterProperties: Setting state to 12
09-09 15:10:00.486  4227  4239 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 15:10:00.486   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 15:10:00.486  4227  4239 I BluetoothAdapterState: Entering OnState
,09-09 15:10:00.487  3905  3915 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 15:10:00.488  1372  1384 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 15:10:00.489  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:10:00.489  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:00.489  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:00.489  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:10:00.489  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:00.489  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:10:00.489  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:10:00.489  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:10:00.490  3905  4219 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 15:10:00.491  3905  3905 D BluetoothA2dp: Proxy object connected
09-09 15:10:00.491  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:10:00.492  3905  3915 D BluetoothPan: onBluetoothStateChange on: true
09-09 15:10:00.493   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 15:10:00.494  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:10:00.494  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:00.494  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:00.494  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:10:00.494  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:00.494  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:10:00.494  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:10:00.494  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:10:00.494   875   875 D BluetoothA2dp: Proxy object connected
,09-09 15:10:00.495  1372  3917 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 15:10:00.496  3905  4219 D BluetoothMap: onBluetoothStateChange: up=true
09-09 15:10:00.496  4227  4227 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 15:10:00.497  4227  4227 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 15:10:00.497   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 15:10:00.497  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 15:10:00.498  1372  1383 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 15:10:00.498  4227  4227 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 15:10:00.499  1372  2219 D BluetoothPan: onBluetoothStateChange on: true
09-09 15:10:00.500  4227  4227 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 15:10:00.500  3905  3905 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 15:10:00.500  3905  3905 D PanProfile: Bluetooth service connected
09-09 15:10:00.501  4227  4227 D ObexServerSockets: Succeed to create listening sockets 
09-09 15:10:00.501  4227  4227 D ObexServerSockets0: startAccept()
09-09 15:10:00.501  4227  4227 D ObexServerSockets0: prepareForNewConnect()
09-09 15:10:00.502  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 15:10:00.502  1372  1372 D PanProfile: Bluetooth service connected
,09-09 15:10:00.502  1372  3917 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 15:10:00.504  4227  4227 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 15:10:00.504  4227  4227 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 15:10:00.504  1372  1372 D BluetoothA2dp: Proxy object connected
09-09 15:10:00.505  1947  1958 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 15:10:00.505  4227  4265 D ObexServerSockets0: Accepting socket connection...
09-09 15:10:00.506  4227  4266 D ObexServerSockets0: Accepting socket connection...
09-09 15:10:00.506  1372  2219 D BluetoothMap: onBluetoothStateChange: up=true
09-09 15:10:00.506  1372  1372 D BluetoothInputDevice: Proxy object connected
,09-09 15:10:00.507  1372  1372 D HidProfile: Bluetooth service connected
09-09 15:10:00.508  1372  1372 D BluetoothMap: Proxy object connected
09-09 15:10:00.508  1372  1372 D MapProfile: Bluetooth service connected
09-09 15:10:00.508  1372  1372 D BluetoothMap: getConnectedDevices()
,09-09 15:10:00.509  3905  3916 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 15:10:00.509  3905  4219 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 15:10:00.511   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 15:10:00.512   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 15:10:00.513  4227  4227 D BluetoothMapService: onReceive
09-09 15:10:00.513  4227  4227 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 15:10:00.513  4227  4227 D BluetoothMapService: STATE_ON
09-09 15:10:00.512  3905  3905 D BluetoothMap: Proxy object connected
09-09 15:10:00.514  3905  3905 D MapProfile: Bluetooth service connected
09-09 15:10:00.514  3905  3905 D BluetoothMap: getConnectedDevices()
09-09 15:10:00.514  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:10:00.515  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:10:00.517  3905  3905 D BluetoothInputDevice: Proxy object connected
,09-09 15:10:00.517  3905  3905 D HidProfile: Bluetooth service connected
,09-09 15:10:00.523  3905  3905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 15:10:00.529  1542  1542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 15:10:00.533  3905  3905 D DockEventReceiver: finishStartingService: stopping service
,09-09 15:10:00.538  1372  1372 D BluetoothPbap: Proxy object connected
,09-09 15:10:00.538  1372  1372 D PbapServerProfile: Bluetooth service connected
09-09 15:10:00.538  3905  3905 D BluetoothPbap: Proxy object connected
09-09 15:10:00.538  3905  3905 D PbapServerProfile: Bluetooth service connected
,09-09 15:10:00.544  4227  4227 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 15:10:00.544  4227  4227 D ObexServerSockets0: prepareForNewConnect()
,09-09 15:10:00.547  4227  4271 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 15:10:00.562  4227  4275 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 15:10:00.563  4227  4275 I BtOppRfcommListener: Accept thread started.
,09-09 15:10:00.588   875   875 D BluetoothHeadset: Proxy object connected
,09-09 15:10:00.588  1947  1965 D BluetoothHeadset: Proxy object connected
09-09 15:10:00.588   875   875 D BluetoothHeadset: Proxy object connected
,09-09 15:10:00.589  3905  3915 D BluetoothHeadset: Proxy object connected
,09-09 15:10:00.589  3905  3905 D HeadsetProfile: Bluetooth service connected
09-09 15:10:00.589  1372  1383 D BluetoothHeadset: Proxy object connected
09-09 15:10:00.590  1372  1372 D HeadsetProfile: Bluetooth service connected
09-09 15:10:00.590   875   875 D BluetoothHeadset: Proxy object connected
,09-09 15:10:00.596  1372  3917 D BluetoothHeadset: Proxy object connected
09-09 15:10:00.596  1372  1372 D HeadsetProfile: Bluetooth service connected
,09-09 15:10:00.597   875   892 D BluetoothHeadset: Proxy object connected
,09-09 15:10:00.606  1947  2169 D BluetoothHeadset: Proxy object connected
,09-09 15:10:00.609  3905  4219 D BluetoothHeadset: Proxy object connected
09-09 15:10:00.609  3905  3905 D HeadsetProfile: Bluetooth service connected
,09-09 15:10:00.612   875   892 D BluetoothHeadset: Proxy object connected
,09-09 15:10:03.734  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:10:03.734  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:03.734  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:03.734  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 15:10:03.734  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:03.734  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:10:03.734  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:10:03.734  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 15:10:03.741  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 15:10:03.742  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:10:03.743  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c9b8bdb removed from the list
09-09 15:10:03.743  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:10:03.744  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:10:03.744  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:03.748  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 15:10:03.749  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9397678 added. We now have 4 listener(s)
,09-09 15:10:03.750  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:10:03.753   875  2022 D WifiService: setWifiEnabled: false pid=3819, uid=10000
09-09 15:10:03.754   875  2022 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 15:10:08.767  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:10:08.768   875  2021 D WifiService: setWifiEnabled: true pid=3819, uid=10000
09-09 15:10:08.768   875  2021 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 15:10:08.781   875  1315 D WifiConfigStore: Loading config and enabling all networks 
,09-09 15:10:08.805  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:10:08.805  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:08.805  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:08.805  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:08.805  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:08.805  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:10:08.805  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:10:08.805  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 15:10:08.807  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:10:08.811  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:10:08.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:08.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:08.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:08.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:08.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 15:10:08.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 15:10:08.811  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 15:10:08.815  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 15:10:08.816   875  1315 D WifiConfigStore: loaded 0 passpoint configs
,09-09 15:10:08.817   875  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 15:10:08.818   875  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 15:10:08.819   875  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 15:10:08.819   875  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 15:10:08.820   875  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 15:10:08.820   875  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 15:10:08.831   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-09 15:10:08.832   875  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 15:10:08.832   373   873 D CommandListener: Setting iface cfg
09-09 15:10:08.833   875  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-09 15:10:08.833   875  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 15:10:08.885   875  1314 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 15:10:08.885   875  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 15:10:08.888   875  1315 E native  : do suspend true
,09-09 15:10:08.936   875  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 15:10:10.208   875  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 15:10:10.337   875  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.38 rxSuccessRate=8.69 delta 1000 -> 994
,09-09 15:10:10.339   875  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-09 15:10:10.339   875  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 15:10:10.354   875  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 15:10:10.390   875  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 15:10:10.391  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 15:10:10.824  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 15:10:10.876  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 15:10:10.879  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 15:10:10.887   875  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 15:10:10.898   875  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 15:10:10.899   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 15:10:10.899   875  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 15:10:10.918   875  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 15:10:10.932   373   873 D CommandListener: Setting iface cfg
,09-09 15:10:10.934   875  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 15:10:10.941   875  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 15:10:10.969   875  4283 D DhcpClient: Receive thread started
,09-09 15:10:11.066   875  1315 E native  : do suspend false
,09-09 15:10:11.095   875  1876 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 15:10:11.114   875  4283 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-09 15:10:11.116   875  1876 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-09 15:10:11.122   875  1876 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 15:10:11.148   875  4283 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 15:10:11.149   875  1876 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 15:10:11.157   373   873 D CommandListener: Setting iface cfg
,09-09 15:10:11.169   875  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 15:10:11.170   875  1876 D DhcpClient: Scheduling renewal in 86399s
,09-09 15:10:11.174   875  1315 E native  : do suspend true
,09-09 15:10:11.196   875  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 15:10:11.199   875  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 15:10:11.201   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 15:10:11.203   875  1319 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 15:10:11.210   875  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 15:10:11.246   875  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 15:10:11.246   875  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 15:10:11.247   875  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 15:10:11.249   875  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 15:10:11.252   875  1319 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 15:10:11.271   875  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 15:10:11.282   875  1319 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-09 15:10:11.282   875  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 15:10:11.283   875  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 15:10:11.283   875  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 15:10:11.283   875  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 15:10:11.283   875  1319 D ConnectivityService:    accepting network in place of null
,09-09 15:10:11.285   875  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 15:10:11.303   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209227, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:10:11.327   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 15:10:11.358   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 15:10:11.367   875  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 15:10:11.369   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 15:10:11.375   875  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 15:10:11.377   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-09 15:10:11.398  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:10:11.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:11.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:11.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:11.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:11.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:11.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:10:11.398  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:10:11.402  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:11.408  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:10:11.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:11.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:11.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:11.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:11.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:11.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:10:11.408  3819  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:10:11.410  3819  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:10:11.410  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 15:10:11.414  1753  1753 D SystemUpdateService: onCreate
,09-09 15:10:11.417  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 15:10:11.432  1753  4292 I SystemUpdateService: active receiver: enabled
,09-09 15:10:11.435  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 15:10:11.443  1753  2434 I iu.UploadsManager: num queued entries: 0
,09-09 15:10:11.443  1753  2434 I iu.UploadsManager: num updated entries: 0
,09-09 15:10:11.446  1753  4292 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 15:10:11.448  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 15:10:11.449  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 15:10:11.451  3974  3974 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 15:10:11.456  3974  3974 D SprintDMHelper: simOperator: 
,09-09 15:10:11.456  3974  3974 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 15:10:11.481  1753  2434 I iu.SyncManager: NEXT; no task
,09-09 15:10:11.499   875  4281 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 15:10:11.506  1753  4294 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 15:10:11.506  1753  4294 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 15:10:11.508  1753  4294 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 15:10:11.510  1753  4292 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 15:10:11.510  1753  4292 I SystemUpdateService: now status is 0 (complete)
09-09 15:10:11.510  1753  4292 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 15:10:11.510  1753  4292 I SystemUpdateService: file has been verified
,09-09 15:10:11.510  1753  4292 I SystemUpdateService: OTA package size = 12249756
,09-09 15:10:11.517  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:10:11.518  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:10:11.519  1753  4292 I SystemUpdateService: showing system update notification
,09-09 15:10:11.532  1753  1753 D SystemUpdateService: onDestroy
,09-09 15:10:11.555  1542  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 15:10:11.555  1542  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 15:10:11.555  1542  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:10:11.555  1542  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:10:11.569  1753  4294 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-09 15:10:11.742   875  4281 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 13:10:11 GMT], X-Android-Received-Millis=[1473426611740], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473426611655]}
,09-09 15:10:11.747   875  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 15:10:11.748   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 15:10:11.749   875  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 15:10:11.757   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 15:10:11.761  4000  4297 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 15:10:12.173  1878  1918 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-09 15:10:12.173  1878  1918 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-09 15:10:12.203  1542  1542 I ConfigService: onCreate
,09-09 15:10:12.366   875  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 15:10:13.793  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 15:10:13.793  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:13.793  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:13.793  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:13.793  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:13.793  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:13.793  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:10:13.793  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:10:13.801  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:10:13.802  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:10:13.803  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9397678 removed from the list
09-09 15:10:13.804  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:10:13.804  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:13.804  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:10:13.817  3819  4305 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-09 15:10:13.817  3819  4305 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 15:10:16.824  3819  4306 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-09 15:10:16.825  3819  4305 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-09 15:10:16.825  3819  4305 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 15:10:16.826  3819  4306 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 15:10:16.826  3819  4305 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 15:10:16.827  3819  4306 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 15:10:16.828  3819  4305 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 15:10:16.828  3819  4306 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 15:10:16.829  3819  4305 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 15:10:16.831  3819  4306 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 15:10:16.836  3819  4309 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Sender)
,09-09 15:10:16.839  3819  4308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
,09-09 15:10:16.840  3819  4310 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Receiver)
09-09 15:10:16.842  3819  4310 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: OutgoingSocketThread/Receiver)
09-09 15:10:16.842  3819  4311 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Receiver)
09-09 15:10:16.842  3819  4310 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 15:10:16.843  3819  4310 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 15:10:16.843  3819  4311 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: IncomingSocketThread/Receiver)
09-09 15:10:16.844  3819  4311 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 15:10:16.844  3819  4311 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 15:10:17.270  1542  1542 I ConfigService: onDestroy
,09-09 15:10:19.290   875  1319 D ConnectivityService: handlePromptUnvalidated 102
,09-09 15:10:19.824  3819  3872 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 15:10:19.826  3819  3872 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 15:10:19.834  3819  3872 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c836254 Bundle[{}]
,09-09 15:10:19.835  3819  3872 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 15:10:19.835  3819  3872 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 15:10:19.835  3819  3872 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 15:10:19.836  3819  3872 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 15:10:19.836  3819  3872 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 15:10:19.837  3819  3872 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 15:10:19.841  3819  3872 I System.out: Running OutgoingSocketThread
,09-09 15:10:19.845  3819  4313 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-09 15:10:19.845  3819  4313 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 15:10:22.854  3819  4314 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-09 15:10:22.854  3819  4314 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 15:10:22.855  3819  4313 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 15:10:22.855  3819  4314 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 15:10:22.855  3819  4313 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 15:10:22.856  3819  4313 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 15:10:22.857  3819  4314 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 15:10:22.857  3819  4313 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 15:10:22.861  3819  4316 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Sender)
09-09 15:10:22.862  3819  4313 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 15:10:22.863  3819  4314 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 15:10:22.873  3819  4317 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Sender)
,09-09 15:10:22.874  3819  4318 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Receiver)
,09-09 15:10:22.876  3819  4318 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: OutgoingSocketThread/Receiver)
09-09 15:10:22.876  3819  4318 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 15:10:22.876  3819  4318 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-09 15:10:22.877  3819  4319 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Receiver)
,09-09 15:10:22.879  3819  4319 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: IncomingSocketThread/Receiver)
09-09 15:10:22.880  3819  4319 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-09 15:10:22.880  3819  4319 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 15:10:25.856  3819  3872 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,09-09 15:10:25.858  3819  3872 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 15:10:25.860  3819  3872 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
,09-09 15:10:25.865  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 15:10:25.866  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8603151 added. We now have 3 listener(s)
,09-09 15:10:25.867  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 15:10:25.867  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 15:10:25.868  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 15:10:25.868  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 15:10:25.868  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a1ddb6 added. We now have 4 listener(s)
,09-09 15:10:25.868  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 15:10:25.869  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 15:10:25.872  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:10:25.881  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:10:25.881  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:25.881  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:25.881  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:25.881  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:25.881  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:25.881  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:10:25.881  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:10:25.886  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:10:25.887  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 15:10:25.888  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:10:25.889  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:10:25.889  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:10:25.889  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:10:25.890  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:25.890  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 15:10:25.890  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 15:10:25.890  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8603151 removed from the list
09-09 15:10:25.891  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:25.891  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a1ddb6 removed from the list
09-09 15:10:25.891  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:10:25.891  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:10:25.891  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:25.893  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:25.893  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:10:25.897  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 15:10:25.897  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:10:25.897  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:10:25.899  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:25.899  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a1ddb6 not in the list
,09-09 15:10:25.899  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:25.899  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:10:25.902  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:10:25.903  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:10:25.903  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:10:25.903  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a1ddb6 not in the list
09-09 15:10:25.904  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:10:25.904  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:25.904  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:25.905  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8603151 not in the list
,09-09 15:10:25.907  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 15:10:25.907  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bcb8224 added. We now have 3 listener(s)
,09-09 15:10:25.913  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 15:10:25.914  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 15:10:25.914  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 15:10:25.915  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 15:10:25.915  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325918d added. We now have 4 listener(s)
,09-09 15:10:25.915  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:10:25.917  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 15:10:25.922  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:10:25.935  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:10:25.935  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:25.935  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:25.935  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:25.935  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:25.935  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:25.935  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:10:25.935  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:10:25.941  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 15:10:25.941  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 15:10:25.945  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 15:10:25.946  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 15:10:25.946  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 15:10:25.946  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:10:25.947  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 15:10:25.948  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:10:25.953  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:10:25.960  3819  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 15:10:25.960  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 15:10:25.973  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 15:10:25.975  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 15:10:25.976  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 15:10:25.987  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 15:10:25.988  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 15:10:25.988  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 15:10:25.991  3819  3872 D BluetoothAdapter: STATE_ON
,09-09 15:10:26.000  4227  4263 D BtGatt.GattService: registerClient() - UUID=fdce49d5-720b-4f2c-b65b-0d93f7499f36
,09-09 15:10:26.003  4227  4243 D BtGatt.GattService: onClientRegistered() - UUID=fdce49d5-720b-4f2c-b65b-0d93f7499f36, clientIf=5
,09-09 15:10:26.005  3819  3830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 15:10:26.008  4227  4238 D BtGatt.GattService: start scan with filters
,09-09 15:10:26.021  4227  4246 D BtGatt.ScanManager: handling starting scan
09-09 15:10:26.021  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 15:10:26.021  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 15:10:26.022  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 15:10:26.022  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 15:10:26.026  4227  4246 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae2b3a8
,09-09 15:10:26.034  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 15:10:26.035  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 15:10:26.036  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 15:10:26.044  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 15:10:26.046  4227  4243 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 15:10:26.046  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:10:26.048  4227  4246 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 15:10:26.051  3819  3872 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 15:10:26.051  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:10:26.051  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 15:10:26.052  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:10:26.052  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 15:10:26.052  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 15:10:26.052  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 15:10:26.052  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 15:10:26.052  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 15:10:26.052  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 15:10:26.052  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 15:10:26.056  3819  3872 D BluetoothAdapter: STATE_ON
09-09 15:10:26.058  4227  4263 D BtGatt.GattService: stopScan() - queue size =1
,09-09 15:10:26.060  4227  4238 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 15:10:26.062  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 15:10:26.063  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 15:10:26.063  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 15:10:26.063  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 15:10:26.064  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 15:10:26.065  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 15:10:26.065  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 15:10:26.065  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 15:10:26.065  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 15:10:26.069  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 15:10:26.071  4227  4243 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 15:10:26.071  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:10:26.072  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 15:10:26.072  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 15:10:26.072  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 15:10:26.073  4227  4246 D BtGatt.ScanManager: Starting BLE batch scan
09-09 15:10:26.073  4227  4246 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 15:10:26.101  4227  4243 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 15:10:26.102  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:10:26.117  4227  4243 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 15:10:26.117  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:10:26.136  4227  4243 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 15:10:26.136  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:10:26.137  4227  4246 D BtGatt.ScanManager: stopping BLe Batch
,09-09 15:10:26.150  4227  4243 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 15:10:26.150  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:10:26.151  4227  4246 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:10:26.166  4227  4243 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 15:10:26.167  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:10:26.574  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 15:10:26.574  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:10:26.574  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 15:10:29.073  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:10:29.073  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:10:29.074  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 15:10:29.074  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:10:29.074  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:29.075  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 15:10:29.075  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 15:10:29.076  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bcb8224 removed from the list
09-09 15:10:29.076  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:29.076  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325918d removed from the list
,09-09 15:10:29.076  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:10:29.077  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:29.078  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:29.079  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:29.082  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 15:10:29.082  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:10:29.083  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:29.083  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325918d not in the list
09-09 15:10:29.083  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:10:29.084  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:29.087  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:10:29.087  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:10:29.087  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:29.088  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325918d not in the list
,09-09 15:10:29.088  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:10:29.088  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:29.089  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:29.089  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bcb8224 not in the list
09-09 15:10:29.091  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 15:10:29.092  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73aed8e added. We now have 3 listener(s)
,09-09 15:10:29.099  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 15:10:29.099  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 15:10:29.099  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 15:10:29.100  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 15:10:29.100  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c99af added. We now have 4 listener(s)
,09-09 15:10:29.101  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 15:10:29.101  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 15:10:29.107  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:10:29.116  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:10:29.116  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:29.116  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:29.116  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:29.116  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:29.116  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:29.116  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:10:29.116  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:10:29.120  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:29.120  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 15:10:29.120  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 15:10:29.121  3819  3872 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 15:10:29.121  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-09 15:10:29.121  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 15:10:29.121  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 15:10:29.122  3819  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 15:10:29.122  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 15:10:29.123  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 15:10:29.123  3819  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 15:10:29.123  3819  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 15:10:29.123  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 15:10:29.123  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 15:10:29.123  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 15:10:29.123  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-09 15:10:29.126  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:10:29.130  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:10:29.131  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 15:10:29.131  3819  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 15:10:29.131  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 15:10:29.134  3819  4320 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 15:10:29.138  3819  4320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 15:10:29.141  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 15:10:29.142  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 15:10:29.143  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 15:10:29.146  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 15:10:29.146  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 15:10:29.146  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-09 15:10:29.148  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 15:10:29.148  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 15:10:29.148  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 15:10:29.149  3819  3872 D BluetoothAdapter: STATE_ON
,09-09 15:10:29.154  4227  4256 D BtGatt.GattService: registerClient() - UUID=d705c669-967e-45c6-a2eb-9e266853ac3f
,09-09 15:10:29.154  4227  4243 D BtGatt.GattService: onClientRegistered() - UUID=d705c669-967e-45c6-a2eb-9e266853ac3f, clientIf=5
09-09 15:10:29.155  3819  3830 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 15:10:29.158  4227  4245 D BtGatt.AdvertiseManager: message : 0
,09-09 15:10:29.163  4227  4245 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 15:10:29.182  4227  4243 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 15:10:29.201  4227  4243 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 15:10:29.203  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 15:10:29.204  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 15:10:29.209  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 15:10:29.212  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 15:10:29.213  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 15:10:29.214  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 15:10:29.214  3819  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 15:10:29.214  3819  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 15:10:29.215  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 15:10:29.223  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 15:10:29.225  3819  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 15:10:29.225  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 15:10:29.727  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 15:10:29.727  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 15:10:29.727  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 15:10:32.224  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:10:32.225  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 15:10:32.225  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 15:10:32.225  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 15:10:32.226  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 15:10:32.226  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 15:10:32.227  3819  4320 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-09 15:10:32.227  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 15:10:32.228  3819  4320 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 15:10:32.228  3819  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 15:10:32.228  3819  4320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 15:10:32.228  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 15:10:32.228  3819  3819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 15:10:32.229  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 15:10:32.229  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 15:10:32.229  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 15:10:32.229  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 15:10:32.232  3819  3872 D BluetoothAdapter: STATE_ON
,09-09 15:10:32.232  3819  3872 D BluetoothLeScanner: could not find callback wrapper
09-09 15:10:32.232  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 15:10:32.233  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 15:10:32.235  4227  4245 D BtGatt.AdvertiseManager: message : 1
,09-09 15:10:32.236  4227  4245 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 15:10:32.245  4227  4243 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0,
09-09 15:10:32.245  4227  4243 D BtGatt.GattService: Client app is not null!
,09-09 15:10:32.250  4227  4238 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 15:10:32.252  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 15:10:32.252  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 15:10:32.252  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 15:10:32.252  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 15:10:32.252  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 15:10:32.253  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 15:10:32.253  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 15:10:32.253  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 15:10:32.254  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 15:10:32.255  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:10:32.255  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:32.255  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 15:10:32.255  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 15:10:32.255  3819  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 15:10:32.257  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73aed8e removed from the list
,09-09 15:10:32.257  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:32.257  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c99af removed from the list
09-09 15:10:32.257  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:10:32.257  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 15:10:32.257  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:32.258  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 15:10:32.258  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:32.258  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:10:32.258  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 15:10:32.259  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:10:32.259  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:10:32.259  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:32.260  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c99af not in the list
,09-09 15:10:32.260  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:32.260  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:32.261  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:10:32.261  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:10:32.261  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:10:32.262  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c99af not in the list
09-09 15:10:32.262  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:10:32.262  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:10:32.262  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:10:32.262  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73aed8e not in the list
09-09 15:10:32.263  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 15:10:32.263  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1336da8 added. We now have 3 listener(s)
,09-09 15:10:32.265  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 15:10:32.265  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 15:10:32.265  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 15:10:32.265  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 15:10:32.265  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63f10c1 added. We now have 4 listener(s)
09-09 15:10:32.265  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:10:32.266  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 15:10:32.269  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:10:32.274  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:10:32.274  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:32.274  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:32.274  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:32.274  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:32.274  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:32.274  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 15:10:32.274  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:10:32.276  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:32.277  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 15:10:32.277  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 15:10:32.277  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 15:10:32.277  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 15:10:32.277  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 15:10:32.277  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 15:10:32.281  3819  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 15:10:32.281  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 15:10:32.282  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:10:32.287  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 15:10:32.289  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 15:10:32.290  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 15:10:32.290  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 15:10:32.294  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 15:10:32.295  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 15:10:32.295  3819  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 15:10:32.296  3819  3872 D BluetoothAdapter: STATE_ON
,09-09 15:10:32.298  4227  4238 D BtGatt.GattService: registerClient() - UUID=3a940ecb-c2c2-41bf-afeb-0d137fabfb92
,09-09 15:10:32.299  4227  4243 D BtGatt.GattService: onClientRegistered() - UUID=3a940ecb-c2c2-41bf-afeb-0d137fabfb92, clientIf=5
09-09 15:10:32.299  3819  3830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 15:10:32.300  4227  4263 D BtGatt.GattService: start scan with filters
,09-09 15:10:32.303  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 15:10:32.303  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 15:10:32.303  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 15:10:32.303  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 15:10:32.304  4227  4246 D BtGatt.ScanManager: handling starting scan
,09-09 15:10:32.306  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 15:10:32.306  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 15:10:32.307  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 15:10:32.308  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 15:10:32.321  4227  4243 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 15:10:32.321  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:10:32.322  4227  4246 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 15:10:32.336  4227  4243 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 15:10:32.336  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:10:32.336  4227  4246 D BtGatt.ScanManager: Starting BLE batch scan
09-09 15:10:32.337  4227  4246 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 15:10:32.369  4227  4243 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 15:10:32.370  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:10:32.386  4227  4243 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 15:10:32.386  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 15:10:32.759  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 15:10:32.807  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 15:10:32.807  3819  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 15:10:32.807  3819  3819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 15:10:33.892  4227  4227 D BtGatt.ScanManager: awakened up at time 231816
,09-09 15:10:33.896  4227  4246 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 15:10:33.935  4227  4243 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-09 15:10:33.935  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:10:33.935  4227  4243 D BtGatt.GattService: current time is 231860089606
09-09 15:10:33.936  4227  4243 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -71, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, -126, -22, -96, 83, -39, -56, 1, -128, -70, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, -46, -4, -117, 6, 105, -37, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -92, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -126, -22, -96, 83, -39, -56, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0]
09-09 15:10:33.937  4227  4243 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,09-09 15:10:33.938  4227  4243 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
09-09 15:10:33.939  4227  4243 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 15:10:33.940  4227  4243 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-09 15:10:33.940  4227  4243 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 15:10:33.940  4227  4243 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
,09-09 15:10:33.947  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 1], added - the peer count is 1
,09-09 15:10:33.948  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 08:EC:A9:50:75:41 1] updated - the peer count is 1
,09-09 15:10:33.949  3819  3819 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 2
09-09 15:10:33.950  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 1], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
09-09 15:10:33.951  3819  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-09 15:10:35.319  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 15:10:35.320  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 15:10:35.320  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 15:10:35.321  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:35.321  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 15:10:35.321  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 15:10:35.321  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 15:10:35.322  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 15:10:35.322  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 15:10:35.323  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 15:10:35.323  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 15:10:35.326  3819  3872 D BluetoothAdapter: STATE_ON
,09-09 15:10:35.329  4227  4256 D BtGatt.GattService: stopScan() - queue size =1
,09-09 15:10:35.331  4227  4264 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 15:10:35.332  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 15:10:35.332  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 15:10:35.333  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 15:10:35.333  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 15:10:35.333  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 15:10:35.337  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 15:10:35.337  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 15:10:35.338  3819  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 15:10:35.338  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 15:10:35.340  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 15:10:35.340  3819  3872 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-09 15:10:35.343  4227  4227 D BtGatt.ScanManager: awakened up at time 233267
09-09 15:10:35.344  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 15:10:35.345  3819  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 15:10:35.345  3819  3819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 15:10:35.346  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:10:35.346  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:35.346  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 15:10:35.347  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 15:10:35.347  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1336da8 removed from the list
09-09 15:10:35.347  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:35.348  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63f10c1 removed from the list
09-09 15:10:35.348  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-09 15:10:35.348  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:35.350  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:35.351  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:35.353  4227  4243 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 15:10:35.353  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:10:35.354  4227  4246 D BtGatt.ScanManager: stopping BLe Batch
09-09 15:10:35.354  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:10:35.354  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 15:10:35.354  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:35.355  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63f10c1 not in the list
09-09 15:10:35.355  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:35.355  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:10:35.357  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 15:10:35.357  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:10:35.357  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 15:10:35.357  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63f10c1 not in the list
09-09 15:10:35.357  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 15:10:35.358  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:10:35.358  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:35.358  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1336da8 not in the list
09-09 15:10:35.359  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 15:10:35.360  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7416f9 added. We now have 3 listener(s)
,09-09 15:10:35.364  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 15:10:35.364  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 15:10:35.365  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 15:10:35.365  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 15:10:35.365  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e03d63e added. We now have 4 listener(s)
09-09 15:10:35.365  3819  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 15:10:35.367  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 15:10:35.368  4227  4243 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
09-09 15:10:35.368  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:10:35.369  4227  4246 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 15:10:35.371  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 15:10:35.376  3819  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 15:10:35.376  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 15:10:35.376  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 15:10:35.376  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 15:10:35.376  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 15:10:35.376  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:35.376  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
09-09 15:10:35.376  3819  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 15:10:35.380  3819  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 15:10:35.380  3819  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 15:10:35.383  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:10:35.383  4227  4243 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
09-09 15:10:35.383  4227  4243 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 15:10:35.383  4227  4243 D BtGatt.GattService: current time is 233308129307
09-09 15:10:35.383  4227  4243 D BtGatt.GattService: Batch record : [-126, -22, -96, 83, -39, -56, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, 37, -47, 14, -113, 116, -46, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 15:10:35.383  3819  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 15:10:35.384  4227  4243 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
09-09 15:10:35.384  4227  4243 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 15:10:35.384  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 15:10:35.384  3819  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 15:10:35.384  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:10:35.385  3819  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 15:10:35.385  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:10:35.386  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 15:10:35.387  3819  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 15:10:35.387  3819  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7416f9 removed from the list
,09-09 15:10:35.388  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:10:35.388  3819  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e03d63e removed from the list,
,09-09 15:10:35.388  3819  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 15:10:35.388  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:10:35.389  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 15:10:35.389  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:35.391  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 15:10:35.391  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 15:10:35.391  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:10:35.392  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e03d63e not in the list
,09-09 15:10:35.392  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:35.392  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 15:10:35.393  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 15:10:35.393  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 15:10:35.393  3819  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 15:10:35.393  3819  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e03d63e not in the list
09-09 15:10:35.393  3819  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 15:10:35.393  3819  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 15:10:35.394  3819  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 15:10:35.394  3819  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7416f9 not in the list
,09-09 15:10:35.395  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 15:10:35.395  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 15:10:35.395  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 15:10:35.395  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 15:10:35.395  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 15:10:35.395  3819  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 15:10:35.846  3819  3819 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 15:10:37.411  3819  4322 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,09-09 15:10:39.408  3819  3872 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 460
,09-09 15:10:39.409  3819  3872 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 460, name: My test thread name)
,09-09 15:10:39.415  3819  4323 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
09-09 15:10:39.416  3819  4323 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: My test thread name)
09-09 15:10:39.416  3819  4323 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 15:10:39.420  3819  3872 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 15:10:39.428  3819  4324 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: My test thread name)
,09-09 15:10:39.429  3819  4324 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 465, thread name: My test thread name): Test exception.
09-09 15:10:39.430  3819  4324 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 465, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 15:10:39.437  3819  3872 I jxcore-log: Total number of executed tests:  82
09-09 15:10:39.437  3819  3872 I jxcore-log: 
,09-09 15:10:39.438  3819  4322 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
09-09 15:10:39.439  3819  3872 I jxcore-log: Number of passed tests:  82
09-09 15:10:39.439  3819  3872 I jxcore-log: 
,09-09 15:10:39.439  3819  3872 I jxcore-log: Number of failed tests:  0
09-09 15:10:39.439  3819  3872 I jxcore-log: 
09-09 15:10:39.440  3819  3872 I jxcore-log: Number of ignored tests:  0
09-09 15:10:39.440  3819  3872 I jxcore-log: 
,09-09 15:10:39.441  3819  3872 I jxcore-log: Total duration:  101438
09-09 15:10:39.441  3819  3872 I jxcore-log: 
,09-09 15:10:39.451  3819  3872 I jxcore-log: Unit Test app is loaded
09-09 15:10:39.451  3819  3872 I jxcore-log: 
,09-09 15:10:39.471  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.471  3819  3872 I jxcore-log: 
,09-09 15:10:39.477  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.477  3819  3872 I jxcore-log: 
,09-09 15:10:39.478  3819  3819 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 15:10:39.479  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.479  3819  3872 I jxcore-log: 
,09-09 15:10:39.480  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.480  3819  3872 I jxcore-log: 
,09-09 15:10:39.481  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 15:10:39.481  3819  3872 I jxcore-log: 
,09-09 15:10:39.483  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 15:10:39.483  3819  3872 I jxcore-log: 
,09-09 15:10:39.486  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.486  3819  3872 I jxcore-log: 
,09-09 15:10:39.488  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.488  3819  3872 I jxcore-log: 
,09-09 15:10:39.489  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 15:10:39.489  3819  3872 I jxcore-log: 
,09-09 15:10:39.490  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 15:10:39.490  3819  3872 I jxcore-log: 
,09-09 15:10:39.491  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 15:10:39.491  3819  3872 I jxcore-log: 
09-09 15:10:39.492  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.492  3819  3872 I jxcore-log: 
,09-09 15:10:39.493  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.493  3819  3872 I jxcore-log: 
,09-09 15:10:39.493  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.493  3819  3872 I jxcore-log: 
09-09 15:10:39.494  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 15:10:39.494  3819  3872 I jxcore-log: 
,09-09 15:10:39.495  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 15:10:39.495  3819  3872 I jxcore-log: 
09-09 15:10:39.496  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 15:10:39.496  3819  3872 I jxcore-log: 
,09-09 15:10:39.497  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.497  3819  3872 I jxcore-log: 
,09-09 15:10:39.498  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.498  3819  3872 I jxcore-log: 
09-09 15:10:39.499  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.499  3819  3872 I jxcore-log: 
09-09 15:10:39.500  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 15:10:39.500  3819  3872 I jxcore-log: 
09-09 15:10:39.500  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 15:10:39.500  3819  3872 I jxcore-log: 
09-09 15:10:39.501  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 15:10:39.501  3819  3872 I jxcore-log: 
,09-09 15:10:39.502  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.502  3819  3872 I jxcore-log: 
09-09 15:10:39.503  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.503  3819  3872 I jxcore-log: 
,09-09 15:10:39.503  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.503  3819  3872 I jxcore-log: 
,09-09 15:10:39.505  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.505  3819  3872 I jxcore-log: 
,09-09 15:10:39.506  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.506  3819  3872 I jxcore-log: 
,09-09 15:10:39.507  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.507  3819  3872 I jxcore-log: 
09-09 15:10:39.507  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.507  3819  3872 I jxcore-log: 
09-09 15:10:39.508  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.508  3819  3872 I jxcore-log: 
,09-09 15:10:39.508  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.508  3819  3872 I jxcore-log: 
09-09 15:10:39.509  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.509  3819  3872 I jxcore-log: 
09-09 15:10:39.509  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.509  3819  3872 I jxcore-log: 
09-09 15:10:39.510  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.510  3819  3872 I jxcore-log: 
,09-09 15:10:39.510  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.510  3819  3872 I jxcore-log: 
09-09 15:10:39.511  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.511  3819  3872 I jxcore-log: 
09-09 15:10:39.511  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 15:10:39.511  3819  3872 I jxcore-log: 
,09-09 15:10:39.512  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 15:10:39.512  3819  3872 I jxcore-log: 
09-09 15:10:39.512  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 15:10:39.512  3819  3872 I jxcore-log: 
,09-09 15:10:39.513  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.513  3819  3872 I jxcore-log: 
09-09 15:10:39.513  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.513  3819  3872 I jxcore-log: 
09-09 15:10:39.514  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.514  3819  3872 I jxcore-log: 
,09-09 15:10:39.514  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.514  3819  3872 I jxcore-log: 
09-09 15:10:39.515  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.515  3819  3872 I jxcore-log: 
,09-09 15:10:39.515  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 15:10:39.515  3819  3872 I jxcore-log: 
09-09 15:10:39.516  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.516  3819  3872 I jxcore-log: 
09-09 15:10:39.516  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 15:10:39.516  3819  3872 I jxcore-log: 
,09-09 15:10:39.517  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.517  3819  3872 I jxcore-log: 
09-09 15:10:39.517  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 15:10:39.517  3819  3872 I jxcore-log: 
,09-09 15:10:39.518  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 15:10:39.518  3819  3872 I jxcore-log: 
,09-09 15:10:39.519  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 15:10:39.519  3819  3872 I jxcore-log: 
,09-09 15:10:39.519  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 15:10:39.519  3819  3872 I jxcore-log: 
09-09 15:10:39.520  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 15:10:39.520  3819  3872 I jxcore-log: 
,09-09 15:10:39.520  3819  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 15:10:39.520  3819  3872 I jxcore-log: 
,09-09 15:10:39.525  3819  3872 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-09 15:10:39.525  3819  3872 I jxcore-log:   bluetooth: 'on',
09-09 15:10:39.525  3819  3872 I jxcore-log:   wifi: 'on',
09-09 15:10:39.525  3819  3872 I jxcore-log:   cellular: 'doNotCare',
09-09 15:10:39.525  3819  3872 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 15:10:39.525  3819  3872 I jxcore-log: 
,09-09 15:10:39.530  3819  3872 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-09 15:10:39.530  3819  3872 I jxcore-log:   bluetooth: 'on',
09-09 15:10:39.530  3819  3872 I jxcore-log:   wifi: 'on',
09-09 15:10:39.530  3819  3872 I jxcore-log:   cellular: 'doNotCare',
09-09 15:10:39.530  3819  3872 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 15:10:39.530  3819  3872 I jxcore-log: 
,09-09 15:10:39.531  3819  3872 I jxcore-log: My device name is: motorola-Nexus 6
09-09 15:10:39.531  3819  3872 I jxcore-log: 
,09-09 15:10:39.532  3819  3872 I jxcore-log: Running for WIFI network type
09-09 15:10:39.532  3819  3872 I jxcore-log: 
,09-09 15:10:41.993  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-09 15:10:41.993  3819  3872 I jxcore-log: 
,09-09 15:10:42.441  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-09 15:10:42.441  3819  3872 I jxcore-log: 
,09-09 15:10:42.474  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-09 15:10:42.474  3819  3872 I jxcore-log: 
,09-09 15:10:43.830  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-09 15:10:43.830  3819  3872 I jxcore-log: 
,09-09 15:10:44.062  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-09 15:10:44.062  3819  3872 I jxcore-log: 
,09-09 15:10:44.067  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-09 15:10:44.067  3819  3872 I jxcore-log: 
,09-09 15:10:44.074  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-09 15:10:44.074  3819  3872 I jxcore-log: 
,09-09 15:10:44.151  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-09 15:10:44.151  3819  3872 I jxcore-log: 
,09-09 15:10:44.170  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-09 15:10:44.170  3819  3872 I jxcore-log: 
,09-09 15:10:44.176  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-09 15:10:44.176  3819  3872 I jxcore-log: 
,09-09 15:10:45.116  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-09 15:10:45.116  3819  3872 I jxcore-log: 
,09-09 15:10:45.284  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-09 15:10:45.284  3819  3872 I jxcore-log: 
,09-09 15:10:45.616  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-09 15:10:45.616  3819  3872 I jxcore-log: 
,09-09 15:10:45.626  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-09 15:10:45.626  3819  3872 I jxcore-log: 
,09-09 15:10:45.634  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-09 15:10:45.634  3819  3872 I jxcore-log: 
,09-09 15:10:45.641  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-09 15:10:45.641  3819  3872 I jxcore-log: 
,09-09 15:10:45.681  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-09 15:10:45.681  3819  3872 I jxcore-log: 
,09-09 15:10:45.729  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-09 15:10:45.729  3819  3872 I jxcore-log: 
,09-09 15:10:45.736  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-09 15:10:45.736  3819  3872 I jxcore-log: 
,09-09 15:10:45.744  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-09 15:10:45.744  3819  3872 I jxcore-log: 
,09-09 15:10:45.764  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-09 15:10:45.764  3819  3872 I jxcore-log: 
,09-09 15:10:45.770  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-09 15:10:45.770  3819  3872 I jxcore-log: 
,09-09 15:10:45.776  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-09 15:10:45.776  3819  3872 I jxcore-log: 
,09-09 15:10:45.792  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-09 15:10:45.792  3819  3872 I jxcore-log: 
,09-09 15:10:45.819  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-09 15:10:45.819  3819  3872 I jxcore-log: 
,09-09 15:10:45.831  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-09 15:10:45.831  3819  3872 I jxcore-log: 
,09-09 15:10:45.845  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-09 15:10:45.845  3819  3872 I jxcore-log: 
,09-09 15:10:45.856  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-09 15:10:45.856  3819  3872 I jxcore-log: 
,09-09 15:10:45.873  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-09 15:10:45.873  3819  3872 I jxcore-log: 
,09-09 15:10:45.884  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-09 15:10:45.884  3819  3872 I jxcore-log: 
,09-09 15:10:45.890  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-09 15:10:45.890  3819  3872 I jxcore-log: 
,09-09 15:10:45.921  3819  3872 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-09 15:10:45.921  3819  3872 I jxcore-log: 
,09-09 15:10:45.933  3819  3872 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-09 15:10:45.934  3819  3872 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-09 15:10:45.934  3819  3872 I jxcore-log: 
,09-09 15:10:45.937  3819  3872 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-09 15:10:45.937  3819  3872 I jxcore-log: 
,09-09 15:10:45.937  3819  3872 I jxcore-log: ThaliTape :: Started ThaliTape
09-09 15:10:45.937  3819  3872 I jxcore-log: 
,09-09 15:10:45.942  3819  3872 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-09 15:10:45.942  3819  3872 I jxcore-log: 
,09-09 15:10:46.028  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:10:46.028  3819  3872 I jxcore-log: 
09-09 15:10:46.028  3819  3872 I jxcore-log: websocket error
09-09 15:10:46.028  3819  3872 I jxcore-log: 
,09-09 15:10:46.028  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:10:46.028  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:10:46.028  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:10:46.028  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:46.028  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:10:46.028  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:46.028  3819  3872 I jxcore-log: 
,09-09 15:10:47.506  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:10:47.506  3819  3872 I jxcore-log: 
09-09 15:10:47.510  3819  3872 I jxcore-log: websocket error
09-09 15:10:47.510  3819  3872 I jxcore-log: 
,09-09 15:10:47.511  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:10:47.511  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:10:47.511  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:10:47.511  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:47.511  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:10:47.511  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:47.511  3819  3872 I jxcore-log: 
,09-09 15:10:48.930  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:10:48.930  3819  3872 I jxcore-log: 
09-09 15:10:48.930  3819  3872 I jxcore-log: websocket error
09-09 15:10:48.930  3819  3872 I jxcore-log: 
09-09 15:10:48.930  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:10:48.930  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:10:48.930  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:10:48.930  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:48.930  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:10:48.930  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:48.930  3819  3872 I jxcore-log: 
,09-09 15:10:49.933   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=247857, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:10:53.820  3603  4326 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 15:10:53.855  3603  4327 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 15:10:53.868  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:10:53.870  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:10:53.893  1542  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 15:10:53.894  1542  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 15:10:53.894  1542  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:10:53.894  1542  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:10:53.918  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:10:53.923  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:10:53.949  1542  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 15:10:53.949  1542  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 15:10:53.950  1542  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:10:53.950  1542  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:10:53.970  3603  4327 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 15:10:53.971  3603  4326 E BooksSync: Soft error
09-09 15:10:53.971  3603  4326 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:10:53.971  3603  4326 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 15:10:53.971  3603  4326 E BooksSync: Sync error
09-09 15:10:53.971  3603  4326 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:10:53.971  3603  4326 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 15:10:53.971  3603  4326 I BooksSync: Finished books sync
,09-09 15:10:53.981   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 251620, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:10:54.003  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:10:54.003  3819  3872 I jxcore-log: 
09-09 15:10:54.003  3819  3872 I jxcore-log: websocket error
09-09 15:10:54.003  3819  3872 I jxcore-log: 
,09-09 15:10:54.003  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:10:54.003  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:10:54.003  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:10:54.003  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:54.003  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:10:54.003  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:54.003  3819  3872 I jxcore-log: 
,09-09 15:10:58.980   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=256904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 15:10:59.062  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:10:59.062  3819  3872 I jxcore-log: 
09-09 15:10:59.062  3819  3872 I jxcore-log: websocket error
09-09 15:10:59.062  3819  3872 I jxcore-log: 
,09-09 15:10:59.062  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:10:59.062  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:10:59.062  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:10:59.062  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:59.062  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:10:59.062  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:10:59.062  3819  3872 I jxcore-log: 
,09-09 15:11:04.137  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:11:04.137  3819  3872 I jxcore-log: 
,09-09 15:11:04.138  3819  3872 I jxcore-log: websocket error
09-09 15:11:04.138  3819  3872 I jxcore-log: 
09-09 15:11:04.138  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:11:04.138  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:11:04.138  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:11:04.138  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:04.138  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:11:04.138  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:04.138  3819  3872 I jxcore-log: 
,09-09 15:11:09.208  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:11:09.208  3819  3872 I jxcore-log: 
,09-09 15:11:09.209  3819  3872 I jxcore-log: websocket error
09-09 15:11:09.209  3819  3872 I jxcore-log: 
,09-09 15:11:09.209  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:11:09.209  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:11:09.209  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:11:09.209  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:09.209  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:11:09.209  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:09.209  3819  3872 I jxcore-log: 
,09-09 15:11:14.278  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:11:14.278  3819  3872 I jxcore-log: 
09-09 15:11:14.279  3819  3872 I jxcore-log: websocket error
09-09 15:11:14.279  3819  3872 I jxcore-log: 
,09-09 15:11:14.279  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:11:14.279  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:11:14.279  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:11:14.279  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:14.279  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:11:14.279  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:14.279  3819  3872 I jxcore-log: 
,09-09 15:11:19.346  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:11:19.346  3819  3872 I jxcore-log: 
,09-09 15:11:19.346  3819  3872 I jxcore-log: websocket error
09-09 15:11:19.346  3819  3872 I jxcore-log: 
09-09 15:11:19.346  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:11:19.346  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:11:19.346  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:11:19.346  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:19.346  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:11:19.346  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:19.346  3819  3872 I jxcore-log: 
,09-09 15:11:24.406  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:11:24.406  3819  3872 I jxcore-log: 
09-09 15:11:24.406  3819  3872 I jxcore-log: websocket error
09-09 15:11:24.406  3819  3872 I jxcore-log: 
09-09 15:11:24.406  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:11:24.406  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:11:24.406  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:11:24.406  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:24.406  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:11:24.406  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:24.406  3819  3872 I jxcore-log: 
,09-09 15:11:26.728  3603  4329 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 15:11:26.746  3603  4330 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 15:11:26.770  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:11:26.772  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:11:26.795  1542  2303 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 15:11:26.796  1542  2303 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 15:11:26.796  1542  2303 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:11:26.796  1542  2303 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:11:26.819  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:11:26.821  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:11:26.838  1542  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 15:11:26.838  1542  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 15:11:26.839  1542  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:11:26.839  1542  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:11:26.858  3603  4330 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 15:11:26.859  3603  4329 E BooksSync: Soft error
09-09 15:11:26.859  3603  4329 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:11:26.859  3603  4329 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 15:11:26.859  3603  4329 E BooksSync: Sync error
09-09 15:11:26.859  3603  4329 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:11:26.859  3603  4329 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 15:11:26.859  3603  4329 I BooksSync: Finished books sync
,09-09 15:11:26.872   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284469, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:11:29.501  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:11:29.501  3819  3872 I jxcore-log: 
09-09 15:11:29.502  3819  3872 I jxcore-log: websocket error
09-09 15:11:29.502  3819  3872 I jxcore-log: 
,09-09 15:11:29.502  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:11:29.502  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:11:29.502  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:11:29.502  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:29.502  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:11:29.502  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:29.502  3819  3872 I jxcore-log: 
,09-09 15:11:34.589  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:11:34.589  3819  3872 I jxcore-log: 
,09-09 15:11:34.589  3819  3872 I jxcore-log: websocket error
09-09 15:11:34.589  3819  3872 I jxcore-log: 
,09-09 15:11:34.590  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:11:34.590  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:11:34.590  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:11:34.590  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:34.590  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:11:34.590  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:34.590  3819  3872 I jxcore-log: 
,09-09 15:11:36.313   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=294237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:11:39.653  3819  3872 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 15:11:39.653  3819  3872 I jxcore-log: 
,09-09 15:11:39.653  3819  3872 I jxcore-log: websocket error
09-09 15:11:39.653  3819  3872 I jxcore-log: 
09-09 15:11:39.654  3819  3872 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 15:11:39.654  3819  3872 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 15:11:39.654  3819  3872 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 15:11:39.654  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:39.654  3819  3872 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 15:11:39.654  3819  3872 I jxcore-log: emit@events.js:82:1
09-09 15:11:39.654  3819  3872 I jxcore-log: 
,09-09 15:11:44.633   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=302557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 15:11:44.774  3819  3872 I jxcore-log: ThaliTape :: Reconnected to the test server
09-09 15:11:44.774  3819  3872 I jxcore-log: 
,09-09 15:11:44.790  3819  3872 I jxcore-log: ThaliTape :: Connected to the test server
09-09 15:11:44.790  3819  3872 I jxcore-log: 
,09-09 15:11:57.347  3628  4345 V KeepSync: Connecting to GoogleApiClient
,09-09 15:11:57.348   875   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 15:11:57.382  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:11:57.387  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:11:57.467  1542  3056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 15:11:57.467  1542  3056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 15:11:57.467  1542  3056 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:11:57.467  1542  3056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:11:57.470  1542  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 15:11:57.470  1542  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 15:11:57.470  1542  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:11:57.470  1542  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:11:57.491  3543  4346 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 15:11:57.491  3543  4346 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at blb.a(PG:3937)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at czp.a(PG:18188)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:11:57.491  3543  4346 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at jdm.a(PG:77)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	... 12 more
09-09 15:11:57.491  3543  4346 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at fal.a(PG:38)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:11:57.491  3543  4346 E HttpOperation: 	... 14 more
,09-09 15:11:57.500  1753  4347 V BaseAuthAsyncOperation: access token request failed
09-09 15:11:57.501  3628  4345 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 15:11:57.552  1542  2303 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 15:11:57.552  1542  2303 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 15:11:57.552  1542  2303 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:11:57.552  1542  2303 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:11:57.587  3543  4346 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 15:11:57.587  3543  4346 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at hec.a(PG:42)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at hee.a(PG:102)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at czr.a(PG:65)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at kka.a(PG:108)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at czp.a(PG:19176)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:11:57.587  3543  4346 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at jdm.a(PG:77)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	... 15 more
09-09 15:11:57.587  3543  4346 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at fal.a(PG:38)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:11:57.587  3543  4346 E HttpOperation: 	... 17 more
,09-09 15:11:57.588  3543  4346 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 15:11:57.588  3543  4346 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at hec.a(PG:42)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at hee.a(PG:102)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at czr.a(PG:65)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at kka.a(PG:108)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	... 15 more
09-09 15:11:57.588  3543  4346 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at fal.a(PG:38)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 15:11:57.588  3543  4346 E ExperimentLoader: 	... 17 more
,09-09 15:11:57.683  1542  3056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 15:11:57.683  1542  3056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 15:11:57.683  1542  3056 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 15:11:57.683  1542  3056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:11:57.704  3628  4345 E KeepSync: IOException
09-09 15:11:57.704  3628  4345 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 15:11:57.704  3628  4345 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:11:57.704  3628  4345 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 15:11:57.704  3628  4345 E KeepSync: 	... 10 more
09-09 15:11:57.704  3628  4345 W KeepSync: Sync result 2
,09-09 15:11:57.708   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 286809, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:11:57.727   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 290420, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:12:24.261  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-09 15:12:24.274  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:12:24.279  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:12:24.322  1542  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 15:12:24.322  1542  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 15:12:24.322  1542  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 15:12:24.322  1542  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:12:24.351  1542  1555 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 15:12:24.351  1542  1555 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 15:12:24.351  1542  1555 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 15:12:24.351  1542  1555 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-09 15:12:24.351  1542  1555 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-09 15:12:24.351  1542  1555 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-09 15:12:24.351  1542  1555 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 15:12:24.356  3506  3535 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 15:12:24.356  3506  3535 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-09 15:12:24.356  3506  3535 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-09 15:12:24.356  3506  3535 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-09 15:12:24.356  3506  3535 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-09 15:12:24.356  3506  3535 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-09 15:12:24.356  3506  3535 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 15:12:28.389  1542  2303 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 15:12:28.389  1542  2303 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 15:12:28.389  1542  2303 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:12:28.389  1542  2303 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:12:28.408  3543  4354 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 15:12:28.408  3543  4354 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at blb.a(PG:3937)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at czp.a(PG:18188)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:12:28.408  3543  4354 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at jdm.a(PG:77)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	... 12 more
09-09 15:12:28.408  3543  4354 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at fal.a(PG:38)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:12:28.408  3543  4354 E HttpOperation: 	... 14 more
,09-09 15:12:28.457  1542  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 15:12:28.457  1542  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 15:12:28.458  1542  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:12:28.458  1542  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:12:28.485  3543  4354 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 15:12:28.485  3543  4354 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at hec.a(PG:42)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at hee.a(PG:102)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at czr.a(PG:65)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at kka.a(PG:108)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at czp.a(PG:19176)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:12:28.485  3543  4354 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at jdm.a(PG:77)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	... 15 more
09-09 15:12:28.485  3543  4354 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at fal.a(PG:38)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:12:28.485  3543  4354 E HttpOperation: 	... 17 more
,09-09 15:12:28.486  3543  4354 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 15:12:28.486  3543  4354 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at hec.a(PG:42)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at hee.a(PG:102)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at czr.a(PG:65)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at kka.a(PG:108)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	... 15 more
09-09 15:12:28.486  3543  4354 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at fal.a(PG:38)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 15:12:28.486  3543  4354 E ExperimentLoader: 	... 17 more
,09-09 15:12:28.587   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 346032, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:12:58.674  3603  4358 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 15:12:58.720  3603  4359 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 15:12:58.738  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:12:58.748  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:12:58.758  3628  4357 V KeepSync: Connecting to GoogleApiClient
,09-09 15:12:58.758   875   886 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 15:12:58.855  1542  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 15:12:58.855  1542  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 15:12:58.855  1542  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:12:58.855  1542  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:12:58.920  1542  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 15:12:58.920  1542  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 15:12:58.920  1542  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:12:58.920  1542  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:12:58.969  1753  4360 V BaseAuthAsyncOperation: access token request failed
,09-09 15:12:58.970  1542  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 15:12:58.970  1542  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 15:12:58.970  1542  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 15:12:58.970  1542  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:12:58.972  3628  4357 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 15:12:59.023  3603  4359 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 15:12:59.023  3603  4358 E BooksSync: Soft error
09-09 15:12:59.023  3603  4358 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:12:59.023  3603  4358 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 15:12:59.023  3603  4358 E BooksSync: Sync error
09-09 15:12:59.023  3603  4358 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:12:59.023  3603  4358 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 15:12:59.023  3603  4358 I BooksSync: Finished books sync
,09-09 15:12:59.040   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 349924, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:12:59.102  1542  3056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 15:12:59.102  1542  3056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 15:12:59.102  1542  3056 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 15:12:59.103  1542  3056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:12:59.130  3628  4357 E KeepSync: IOException,
09-09 15:12:59.130  3628  4357 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 15:12:59.130  3628  4357 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:12:59.130  3628  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 15:12:59.130  3628  4357 E KeepSync: 	... 10 more
09-09 15:12:59.130  3628  4357 W KeepSync: Sync result 2
,09-09 15:12:59.141   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 347812, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:13:29.714  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:13:29.719  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:13:29.765  1542  2303 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 15:13:29.765  1542  2303 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 15:13:29.765  1542  2303 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:13:29.765  1542  2303 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:13:29.783  3543  4363 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 15:13:29.783  3543  4363 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at blb.a(PG:3937)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at czp.a(PG:18188)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:13:29.783  3543  4363 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at jdm.a(PG:77)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	... 12 more
09-09 15:13:29.783  3543  4363 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at fal.a(PG:38)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:13:29.783  3543  4363 E HttpOperation: 	... 14 more
,09-09 15:13:29.852  1542  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 15:13:29.852  1542  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 15:13:29.852  1542  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:13:29.852  1542  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:13:29.914  3543  4363 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 15:13:29.914  3543  4363 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at hec.a(PG:42)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at hee.a(PG:102)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at czr.a(PG:65)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at kka.a(PG:108)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at czp.a(PG:19176)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:13:29.914  3543  4363 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at jdm.a(PG:77)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	... 15 more
09-09 15:13:29.914  3543  4363 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at fal.a(PG:38)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:13:29.914  3543  4363 E HttpOperation: 	... 17 more
,09-09 15:13:29.914  3543  4363 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 15:13:29.914  3543  4363 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at hec.a(PG:42)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at hee.a(PG:102)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at czr.a(PG:65)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at kka.a(PG:108)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	... 15 more
09-09 15:13:29.914  3543  4363 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at fal.a(PG:38)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 15:13:29.914  3543  4363 E ExperimentLoader: 	... 17 more
,09-09 15:13:30.083   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 407310, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:13:57.156  3819  3872 I jxcore-log: TAP version 13
09-09 15:13:57.156  3819  3872 I jxcore-log: 
,09-09 15:13:57.160  3819  3872 I jxcore-log: # setup
09-09 15:13:57.160  3819  3872 I jxcore-log: 
,09-09 15:13:58.684  3819  3872 I jxcore-log: # 1. calling createNativeListener directly rejects
09-09 15:13:58.684  3819  3872 I jxcore-log: 
,09-09 15:13:59.274  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:13:59.274  3819  3872 I jxcore-log: 
,09-09 15:13:59.280  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 40766
09-09 15:13:59.280  3819  3872 I jxcore-log: 
,09-09 15:13:59.286  3819  3872 I jxcore-log: ok 1 Should throw
09-09 15:13:59.286  3819  3872 I jxcore-log: 
,09-09 15:13:59.288  3819  3872 I jxcore-log: # teardown
09-09 15:13:59.288  3819  3872 I jxcore-log: 
,09-09 15:13:59.997  3819  3872 I jxcore-log: # setup
09-09 15:13:59.997  3819  3872 I jxcore-log: 
,09-09 15:14:00.078  3819  3872 I jxcore-log: # 2. emits incomingConnectionState
09-09 15:14:00.078  3819  3872 I jxcore-log: 
,09-09 15:14:00.187  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:00.187  3819  3872 I jxcore-log: 
,09-09 15:14:00.198  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 46415
09-09 15:14:00.198  3819  3872 I jxcore-log: 
,09-09 15:14:00.214  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:00.214  3819  3872 I jxcore-log: 
,09-09 15:14:00.222  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:00.222  3819  3872 I jxcore-log: 
,09-09 15:14:00.242  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:00.242  3819  3872 I jxcore-log: 
,09-09 15:14:00.248  3819  3872 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-09 15:14:00.248  3819  3872 I jxcore-log: 
,09-09 15:14:00.270  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:00.270  3819  3872 I jxcore-log: 
,09-09 15:14:00.271  3819  3872 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-09 15:14:00.271  3819  3872 I jxcore-log: 
,09-09 15:14:00.280  3819  3872 I jxcore-log: # teardown
09-09 15:14:00.280  3819  3872 I jxcore-log: 
,09-09 15:14:00.397  3819  3872 I jxcore-log: # setup
09-09 15:14:00.397  3819  3872 I jxcore-log: 
,09-09 15:14:00.514  3819  3872 I jxcore-log: # 3. emits routerPortConnectionFailed
09-09 15:14:00.514  3819  3872 I jxcore-log: 
,09-09 15:14:00.608  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:00.608  3819  3872 I jxcore-log: 
,09-09 15:14:00.617  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 44262
09-09 15:14:00.617  3819  3872 I jxcore-log: 
,09-09 15:14:00.623  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:00.623  3819  3872 I jxcore-log: 
,09-09 15:14:00.625  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:00.625  3819  3872 I jxcore-log: 
,09-09 15:14:00.626  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:00.626  3819  3872 I jxcore-log: 
,09-09 15:14:00.657  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:00.657  3819  3872 I jxcore-log: 
,09-09 15:14:00.659  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:00.659  3819  3872 I jxcore-log: 
,09-09 15:14:00.664  3819  3872 I jxcore-log: DEBUG createNativeListener: 
09-09 15:14:00.664  3819  3872 I jxcore-log: 
,09-09 15:14:00.665  3819  3872 I jxcore-log: ok 4 tried to connect to right port
09-09 15:14:00.665  3819  3872 I jxcore-log: 
09-09 15:14:00.666  3819  3872 I jxcore-log: ok 5 failed due to refused connection
09-09 15:14:00.666  3819  3872 I jxcore-log: 
,09-09 15:14:00.666  3819  3872 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-09 15:14:00.666  3819  3872 I jxcore-log: 
,09-09 15:14:00.669  3819  3872 I jxcore-log: # teardown
09-09 15:14:00.669  3819  3872 I jxcore-log: 
,09-09 15:14:00.670  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:00.670  3819  3872 I jxcore-log: 
,09-09 15:14:00.818  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:00.818  3819  3872 I jxcore-log: 
,09-09 15:14:00.823  3819  3872 I jxcore-log: # setup
09-09 15:14:00.823  3819  3872 I jxcore-log: 
,09-09 15:14:00.824  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:00.824  3819  3872 I jxcore-log: 
,09-09 15:14:00.938  3819  3872 I jxcore-log: # 4. native server connections all up
09-09 15:14:00.938  3819  3872 I jxcore-log: 
,09-09 15:14:01.007  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:01.007  3819  3872 I jxcore-log: 
,09-09 15:14:01.017  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 40940
09-09 15:14:01.017  3819  3872 I jxcore-log: 
,09-09 15:14:01.023  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:01.023  3819  3872 I jxcore-log: 
,09-09 15:14:01.025  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:01.025  3819  3872 I jxcore-log: 
,09-09 15:14:01.026  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:01.026  3819  3872 I jxcore-log: 
,09-09 15:14:01.062  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:01.062  3819  3872 I jxcore-log: 
,09-09 15:14:01.064  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:01.064  3819  3872 I jxcore-log: 
,09-09 15:14:01.067  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:01.067  3819  3872 I jxcore-log: 
,09-09 15:14:01.069  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:01.069  3819  3872 I jxcore-log: 
,09-09 15:14:01.089  3819  3872 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-09 15:14:01.089  3819  3872 I jxcore-log: 
,09-09 15:14:01.089  3819  3872 I jxcore-log: ok 8 Send/recvd #1 should be same
09-09 15:14:01.089  3819  3872 I jxcore-log: 
,09-09 15:14:01.091  3819  3872 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-09 15:14:01.091  3819  3872 I jxcore-log: 
09-09 15:14:01.092  3819  3872 I jxcore-log: ok 10 Send/recvd #2 should be same
09-09 15:14:01.092  3819  3872 I jxcore-log: 
,09-09 15:14:01.094  3819  3872 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-09 15:14:01.094  3819  3872 I jxcore-log: 
,09-09 15:14:01.100  3819  3872 I jxcore-log: # teardown
09-09 15:14:01.100  3819  3872 I jxcore-log: 
,09-09 15:14:01.194  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:01.194  3819  3872 I jxcore-log: 
,09-09 15:14:01.197  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:01.197  3819  3872 I jxcore-log: 
,09-09 15:14:01.199  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:01.199  3819  3872 I jxcore-log: 
,09-09 15:14:01.203  3819  3872 I jxcore-log: # setup
09-09 15:14:01.203  3819  3872 I jxcore-log: 
,09-09 15:14:01.205  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:01.205  3819  3872 I jxcore-log: 
,09-09 15:14:01.348  3819  3872 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-09 15:14:01.348  3819  3872 I jxcore-log: 
,09-09 15:14:01.450  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:01.450  3819  3872 I jxcore-log: 
,09-09 15:14:01.458  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 46619
09-09 15:14:01.458  3819  3872 I jxcore-log: 
,09-09 15:14:01.464  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:01.464  3819  3872 I jxcore-log: 
,09-09 15:14:01.465  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:01.465  3819  3872 I jxcore-log: 
,09-09 15:14:01.467  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:01.467  3819  3872 I jxcore-log: 
,09-09 15:14:01.482  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:01.482  3819  3872 I jxcore-log: 
,09-09 15:14:01.485  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:01.485  3819  3872 I jxcore-log: 
,09-09 15:14:01.499  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:01.499  3819  3872 I jxcore-log: 
,09-09 15:14:01.513  3819  3872 I jxcore-log: ok 12 socket shouldn't close until after stream
09-09 15:14:01.513  3819  3872 I jxcore-log: 
,09-09 15:14:01.513  3819  3872 I jxcore-log: ok 13 incoming remains open
09-09 15:14:01.513  3819  3872 I jxcore-log: 
,09-09 15:14:01.517  3819  3872 I jxcore-log: # teardown
09-09 15:14:01.517  3819  3872 I jxcore-log: 
,09-09 15:14:01.624  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:01.624  3819  3872 I jxcore-log: 
,09-09 15:14:01.637  3819  3872 I jxcore-log: # setup
09-09 15:14:01.637  3819  3872 I jxcore-log: 
,09-09 15:14:01.638  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:01.638  3819  3872 I jxcore-log: 
,09-09 15:14:01.722  3819  3872 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-09 15:14:01.722  3819  3872 I jxcore-log: 
,09-09 15:14:01.815  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:01.815  3819  3872 I jxcore-log: 
,09-09 15:14:01.819  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 40681
09-09 15:14:01.819  3819  3872 I jxcore-log: 
,09-09 15:14:01.825  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:01.825  3819  3872 I jxcore-log: 
,09-09 15:14:01.827  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:01.827  3819  3872 I jxcore-log: 
,09-09 15:14:01.828  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:01.828  3819  3872 I jxcore-log: 
,09-09 15:14:01.839  3819  3872 I jxcore-log: ok 14 we should not have gotten an error
09-09 15:14:01.839  3819  3872 I jxcore-log: 
,09-09 15:14:01.847  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:01.847  3819  3872 I jxcore-log: 
,09-09 15:14:01.850  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:01.850  3819  3872 I jxcore-log: 
,09-09 15:14:01.860  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:01.860  3819  3872 I jxcore-log: 
,09-09 15:14:01.863  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:01.863  3819  3872 I jxcore-log: 
,09-09 15:14:01.871  3819  3872 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-09 15:14:01.871  3819  3872 I jxcore-log: 
,09-09 15:14:01.871  3819  3872 I jxcore-log: ok 16 incoming is cleaned up
09-09 15:14:01.871  3819  3872 I jxcore-log: 
,09-09 15:14:01.874  3819  3872 I jxcore-log: # teardown
09-09 15:14:01.874  3819  3872 I jxcore-log: 
,09-09 15:14:01.982  3819  3872 I jxcore-log: # setup
09-09 15:14:01.982  3819  3872 I jxcore-log: 
,09-09 15:14:02.034  3819  3872 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-09 15:14:02.034  3819  3872 I jxcore-log: 
,09-09 15:14:02.157  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:02.157  3819  3872 I jxcore-log: 
,09-09 15:14:02.163  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 43812
09-09 15:14:02.163  3819  3872 I jxcore-log: 
,09-09 15:14:02.177  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.177  3819  3872 I jxcore-log: 
,09-09 15:14:02.178  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.178  3819  3872 I jxcore-log: 
,09-09 15:14:02.181  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.181  3819  3872 I jxcore-log: 
,09-09 15:14:02.200  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:02.200  3819  3872 I jxcore-log: 
,09-09 15:14:02.203  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:02.203  3819  3872 I jxcore-log: 
,09-09 15:14:02.218  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:02.218  3819  3872 I jxcore-log: 
,09-09 15:14:02.228  3819  3872 I jxcore-log: ok 17 stream was closed
09-09 15:14:02.228  3819  3872 I jxcore-log: 
,09-09 15:14:02.229  3819  3872 I jxcore-log: ok 18 incoming should survive
09-09 15:14:02.229  3819  3872 I jxcore-log: 
09-09 15:14:02.229  3819  3872 I jxcore-log: ok 19 mux should have no streams
09-09 15:14:02.229  3819  3872 I jxcore-log: 
,09-09 15:14:02.234  3819  3872 I jxcore-log: # teardown
09-09 15:14:02.234  3819  3872 I jxcore-log: 
,09-09 15:14:02.309  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:02.309  3819  3872 I jxcore-log: 
,09-09 15:14:02.320  3819  3872 I jxcore-log: # setup
09-09 15:14:02.320  3819  3872 I jxcore-log: 
,09-09 15:14:02.321  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:02.321  3819  3872 I jxcore-log: 
,09-09 15:14:02.414  3819  3872 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-09 15:14:02.414  3819  3872 I jxcore-log: 
,09-09 15:14:02.533  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:02.533  3819  3872 I jxcore-log: 
,09-09 15:14:02.542  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 38643
09-09 15:14:02.542  3819  3872 I jxcore-log: 
,09-09 15:14:02.554  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.554  3819  3872 I jxcore-log: 
,09-09 15:14:02.558  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.558  3819  3872 I jxcore-log: 
,09-09 15:14:02.562  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.562  3819  3872 I jxcore-log: 
,09-09 15:14:02.576  3819  3872 I jxcore-log: ok 20 we should not have gotten an error
09-09 15:14:02.576  3819  3872 I jxcore-log: 
,09-09 15:14:02.585  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:02.585  3819  3872 I jxcore-log: 
,09-09 15:14:02.588  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:02.588  3819  3872 I jxcore-log: 
,09-09 15:14:02.598  3819  3872 I jxcore-log: ok 21 Buffers are identical
09-09 15:14:02.598  3819  3872 I jxcore-log: 
,09-09 15:14:02.601  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:02.601  3819  3872 I jxcore-log: 
,09-09 15:14:02.604  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:02.604  3819  3872 I jxcore-log: 
,09-09 15:14:02.606  3819  3872 I jxcore-log: ok 22 native server is nulled out
09-09 15:14:02.606  3819  3872 I jxcore-log: 
,09-09 15:14:02.607  3819  3872 I jxcore-log: ok 23 native server should be closed
09-09 15:14:02.607  3819  3872 I jxcore-log: 
,09-09 15:14:02.607  3819  3872 I jxcore-log: ok 24 incoming has been removed
09-09 15:14:02.607  3819  3872 I jxcore-log: 
09-09 15:14:02.608  3819  3872 I jxcore-log: ok 25 Incoming should be done
09-09 15:14:02.608  3819  3872 I jxcore-log: 
09-09 15:14:02.608  3819  3872 I jxcore-log: ok 26 The mux object should be closed
09-09 15:14:02.608  3819  3872 I jxcore-log: 
09-09 15:14:02.609  3819  3872 I jxcore-log: ok 27 The mux stream should be closed
09-09 15:14:02.609  3819  3872 I jxcore-log: 
09-09 15:14:02.610  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:02.610  3819  3872 I jxcore-log: 
,09-09 15:14:02.623  3819  3872 I jxcore-log: # teardown
09-09 15:14:02.623  3819  3872 I jxcore-log: 
,09-09 15:14:02.710  3819  3872 I jxcore-log: # setup
09-09 15:14:02.710  3819  3872 I jxcore-log: 
,09-09 15:14:02.786  3819  3872 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-09 15:14:02.786  3819  3872 I jxcore-log: 
,09-09 15:14:02.879  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:02.879  3819  3872 I jxcore-log: 
,09-09 15:14:02.887  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 41711
09-09 15:14:02.887  3819  3872 I jxcore-log: 
,09-09 15:14:02.915  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.915  3819  3872 I jxcore-log: 
,09-09 15:14:02.916  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.916  3819  3872 I jxcore-log: 
,09-09 15:14:02.917  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.917  3819  3872 I jxcore-log: 
,09-09 15:14:02.921  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.921  3819  3872 I jxcore-log: 
,09-09 15:14:02.922  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.922  3819  3872 I jxcore-log: 
,09-09 15:14:02.923  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.923  3819  3872 I jxcore-log: 
,09-09 15:14:02.926  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.926  3819  3872 I jxcore-log: 
,09-09 15:14:02.926  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.926  3819  3872 I jxcore-log: 
,09-09 15:14:02.928  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.928  3819  3872 I jxcore-log: 
,09-09 15:14:02.931  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.931  3819  3872 I jxcore-log: 
,09-09 15:14:02.932  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.932  3819  3872 I jxcore-log: 
,09-09 15:14:02.933  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.933  3819  3872 I jxcore-log: 
,09-09 15:14:02.937  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.937  3819  3872 I jxcore-log: 
,09-09 15:14:02.937  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.937  3819  3872 I jxcore-log: 
,09-09 15:14:02.939  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.939  3819  3872 I jxcore-log: 
,09-09 15:14:02.941  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.941  3819  3872 I jxcore-log: 
,09-09 15:14:02.942  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.942  3819  3872 I jxcore-log: 
09-09 15:14:02.943  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.943  3819  3872 I jxcore-log: 
,09-09 15:14:02.952  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.952  3819  3872 I jxcore-log: 
,09-09 15:14:02.953  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.953  3819  3872 I jxcore-log: 
,09-09 15:14:02.955  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.955  3819  3872 I jxcore-log: 
,09-09 15:14:02.959  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.959  3819  3872 I jxcore-log: 
,09-09 15:14:02.959  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.959  3819  3872 I jxcore-log: 
,09-09 15:14:02.960  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.960  3819  3872 I jxcore-log: 
,09-09 15:14:02.961  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.961  3819  3872 I jxcore-log: 
,09-09 15:14:02.962  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.962  3819  3872 I jxcore-log: 
,09-09 15:14:02.963  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.963  3819  3872 I jxcore-log: 
,09-09 15:14:02.964  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:02.964  3819  3872 I jxcore-log: 
,09-09 15:14:02.965  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:02.965  3819  3872 I jxcore-log: 
,09-09 15:14:02.965  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:02.965  3819  3872 I jxcore-log: 
,09-09 15:14:03.043  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.043  3819  3872 I jxcore-log: 
,09-09 15:14:03.046  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.046  3819  3872 I jxcore-log: 
,09-09 15:14:03.048  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.048  3819  3872 I jxcore-log: 
,09-09 15:14:03.051  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.051  3819  3872 I jxcore-log: 
,09-09 15:14:03.053  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.053  3819  3872 I jxcore-log: 
,09-09 15:14:03.054  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.054  3819  3872 I jxcore-log: 
,09-09 15:14:03.056  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.056  3819  3872 I jxcore-log: 
,09-09 15:14:03.058  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.058  3819  3872 I jxcore-log: 
,09-09 15:14:03.061  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.061  3819  3872 I jxcore-log: 
,09-09 15:14:03.063  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.063  3819  3872 I jxcore-log: 
,09-09 15:14:03.064  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.064  3819  3872 I jxcore-log: 
,09-09 15:14:03.066  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.066  3819  3872 I jxcore-log: 
,09-09 15:14:03.067  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.067  3819  3872 I jxcore-log: 
,09-09 15:14:03.068  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.068  3819  3872 I jxcore-log: 
,09-09 15:14:03.070  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.070  3819  3872 I jxcore-log: 
,09-09 15:14:03.071  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.071  3819  3872 I jxcore-log: 
,09-09 15:14:03.073  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.073  3819  3872 I jxcore-log: 
,09-09 15:14:03.075  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.075  3819  3872 I jxcore-log: 
,09-09 15:14:03.076  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.076  3819  3872 I jxcore-log: 
,09-09 15:14:03.078  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.078  3819  3872 I jxcore-log: 
,09-09 15:14:03.079  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.079  3819  3872 I jxcore-log: 
,09-09 15:14:03.081  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.081  3819  3872 I jxcore-log: 
,09-09 15:14:03.082  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.082  3819  3872 I jxcore-log: 
,09-09 15:14:03.083  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.083  3819  3872 I jxcore-log: 
,09-09 15:14:03.085  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.085  3819  3872 I jxcore-log: 
,09-09 15:14:03.087  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.087  3819  3872 I jxcore-log: 
,09-09 15:14:03.088  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.088  3819  3872 I jxcore-log: 
,09-09 15:14:03.090  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.090  3819  3872 I jxcore-log: 
,09-09 15:14:03.091  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.091  3819  3872 I jxcore-log: 
,09-09 15:14:03.092  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.092  3819  3872 I jxcore-log: 
,09-09 15:14:03.093  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.093  3819  3872 I jxcore-log: 
,09-09 15:14:03.095  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.095  3819  3872 I jxcore-log: 
,09-09 15:14:03.097  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.097  3819  3872 I jxcore-log: 
,09-09 15:14:03.098  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.098  3819  3872 I jxcore-log: 
,09-09 15:14:03.100  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.100  3819  3872 I jxcore-log: 
,09-09 15:14:03.101  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.101  3819  3872 I jxcore-log: 
,09-09 15:14:03.102  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.102  3819  3872 I jxcore-log: 
,09-09 15:14:03.110  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.110  3819  3872 I jxcore-log: 
,09-09 15:14:03.111  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.111  3819  3872 I jxcore-log: 
,09-09 15:14:03.113  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.113  3819  3872 I jxcore-log: 
,09-09 15:14:03.115  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.115  3819  3872 I jxcore-log: 
,09-09 15:14:03.116  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.116  3819  3872 I jxcore-log: 
,09-09 15:14:03.118  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.118  3819  3872 I jxcore-log: 
,09-09 15:14:03.119  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.119  3819  3872 I jxcore-log: 
,09-09 15:14:03.120  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.120  3819  3872 I jxcore-log: 
,09-09 15:14:03.121  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.121  3819  3872 I jxcore-log: 
,09-09 15:14:03.122  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.122  3819  3872 I jxcore-log: 
,09-09 15:14:03.124  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.124  3819  3872 I jxcore-log: 
,09-09 15:14:03.129  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.129  3819  3872 I jxcore-log: 
,09-09 15:14:03.131  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.131  3819  3872 I jxcore-log: 
,09-09 15:14:03.132  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.132  3819  3872 I jxcore-log: 
,09-09 15:14:03.133  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.133  3819  3872 I jxcore-log: 
,09-09 15:14:03.134  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.134  3819  3872 I jxcore-log: 
,09-09 15:14:03.136  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.136  3819  3872 I jxcore-log: 
,09-09 15:14:03.137  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.137  3819  3872 I jxcore-log: 
,09-09 15:14:03.138  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.138  3819  3872 I jxcore-log: 
,09-09 15:14:03.140  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.140  3819  3872 I jxcore-log: 
,09-09 15:14:03.141  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.141  3819  3872 I jxcore-log: 
,09-09 15:14:03.143  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.143  3819  3872 I jxcore-log: 
,09-09 15:14:03.144  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.144  3819  3872 I jxcore-log: 
,09-09 15:14:03.145  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.145  3819  3872 I jxcore-log: 
,09-09 15:14:03.146  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.146  3819  3872 I jxcore-log: 
,09-09 15:14:03.147  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.147  3819  3872 I jxcore-log: 
,09-09 15:14:03.149  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.149  3819  3872 I jxcore-log: 
,09-09 15:14:03.151  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.151  3819  3872 I jxcore-log: 
,09-09 15:14:03.152  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.152  3819  3872 I jxcore-log: 
,09-09 15:14:03.153  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.153  3819  3872 I jxcore-log: 
,09-09 15:14:03.155  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.155  3819  3872 I jxcore-log: 
,09-09 15:14:03.156  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.156  3819  3872 I jxcore-log: 
,09-09 15:14:03.157  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.157  3819  3872 I jxcore-log: 
,09-09 15:14:03.158  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.158  3819  3872 I jxcore-log: 
,09-09 15:14:03.159  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.159  3819  3872 I jxcore-log: 
,09-09 15:14:03.161  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.161  3819  3872 I jxcore-log: 
,09-09 15:14:03.163  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.163  3819  3872 I jxcore-log: 
,09-09 15:14:03.164  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.164  3819  3872 I jxcore-log: 
,09-09 15:14:03.165  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.165  3819  3872 I jxcore-log: 
,09-09 15:14:03.166  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.166  3819  3872 I jxcore-log: 
09-09 15:14:03.168  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.168  3819  3872 I jxcore-log: 
,09-09 15:14:03.169  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:03.169  3819  3872 I jxcore-log: 
,09-09 15:14:03.170  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:03.170  3819  3872 I jxcore-log: 
,09-09 15:14:03.259  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.259  3819  3872 I jxcore-log: 
,09-09 15:14:03.261  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.261  3819  3872 I jxcore-log: 
,09-09 15:14:03.262  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.262  3819  3872 I jxcore-log: 
,09-09 15:14:03.263  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.263  3819  3872 I jxcore-log: 
,09-09 15:14:03.265  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.265  3819  3872 I jxcore-log: 
,09-09 15:14:03.266  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.266  3819  3872 I jxcore-log: 
,09-09 15:14:03.267  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.267  3819  3872 I jxcore-log: 
09-09 15:14:03.268  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.268  3819  3872 I jxcore-log: 
,09-09 15:14:03.269  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.269  3819  3872 I jxcore-log: 
,09-09 15:14:03.271  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.271  3819  3872 I jxcore-log: 
,09-09 15:14:03.272  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.272  3819  3872 I jxcore-log: 
,09-09 15:14:03.274  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.274  3819  3872 I jxcore-log: 
,09-09 15:14:03.276  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.276  3819  3872 I jxcore-log: 
09-09 15:14:03.277  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.277  3819  3872 I jxcore-log: 
09-09 15:14:03.279  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.279  3819  3872 I jxcore-log: 
,09-09 15:14:03.283  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.283  3819  3872 I jxcore-log: 
,09-09 15:14:03.285  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.285  3819  3872 I jxcore-log: 
,09-09 15:14:03.286  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.286  3819  3872 I jxcore-log: 
09-09 15:14:03.287  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.287  3819  3872 I jxcore-log: 
,09-09 15:14:03.288  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.288  3819  3872 I jxcore-log: 
,09-09 15:14:03.289  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.289  3819  3872 I jxcore-log: 
,09-09 15:14:03.290  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.290  3819  3872 I jxcore-log: 
,09-09 15:14:03.291  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.291  3819  3872 I jxcore-log: 
09-09 15:14:03.292  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.292  3819  3872 I jxcore-log: 
,09-09 15:14:03.294  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.294  3819  3872 I jxcore-log: 
,09-09 15:14:03.295  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.295  3819  3872 I jxcore-log: 
,09-09 15:14:03.296  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.296  3819  3872 I jxcore-log: 
09-09 15:14:03.297  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.297  3819  3872 I jxcore-log: 
,09-09 15:14:03.298  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.298  3819  3872 I jxcore-log: 
,09-09 15:14:03.300  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.300  3819  3872 I jxcore-log: 
,09-09 15:14:03.301  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.301  3819  3872 I jxcore-log: 
,09-09 15:14:03.302  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.302  3819  3872 I jxcore-log: 
,09-09 15:14:03.303  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.303  3819  3872 I jxcore-log: 
09-09 15:14:03.304  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.304  3819  3872 I jxcore-log: 
,09-09 15:14:03.305  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.305  3819  3872 I jxcore-log: 
,09-09 15:14:03.306  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.306  3819  3872 I jxcore-log: 
,09-09 15:14:03.307  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.307  3819  3872 I jxcore-log: 
09-09 15:14:03.308  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.308  3819  3872 I jxcore-log: 
,09-09 15:14:03.313  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.313  3819  3872 I jxcore-log: 
,09-09 15:14:03.314  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.314  3819  3872 I jxcore-log: 
,09-09 15:14:03.315  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.315  3819  3872 I jxcore-log: 
09-09 15:14:03.316  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.316  3819  3872 I jxcore-log: 
,09-09 15:14:03.317  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.317  3819  3872 I jxcore-log: 
,09-09 15:14:03.318  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.318  3819  3872 I jxcore-log: 
09-09 15:14:03.319  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.319  3819  3872 I jxcore-log: 
,09-09 15:14:03.321  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.321  3819  3872 I jxcore-log: 
,09-09 15:14:03.322  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.322  3819  3872 I jxcore-log: 
,09-09 15:14:03.323  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.323  3819  3872 I jxcore-log: 
09-09 15:14:03.324  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:03.324  3819  3872 I jxcore-log: 
,09-09 15:14:03.325  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:03.325  3819  3872 I jxcore-log: 
,09-09 15:14:03.328  3819  3872 I jxcore-log: ok 28 native server is nulled out
09-09 15:14:03.328  3819  3872 I jxcore-log: 
,09-09 15:14:03.329  3819  3872 I jxcore-log: ok 29 native server should be closed
09-09 15:14:03.329  3819  3872 I jxcore-log: 
09-09 15:14:03.329  3819  3872 I jxcore-log: ok 30 incoming has been removed
09-09 15:14:03.329  3819  3872 I jxcore-log: 
09-09 15:14:03.330  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.330  3819  3872 I jxcore-log: 
,09-09 15:14:03.331  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.331  3819  3872 I jxcore-log: 
09-09 15:14:03.331  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.331  3819  3872 I jxcore-log: 
,09-09 15:14:03.332  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.332  3819  3872 I jxcore-log: 
09-09 15:14:03.332  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.332  3819  3872 I jxcore-log: 
,09-09 15:14:03.333  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.333  3819  3872 I jxcore-log: 
09-09 15:14:03.333  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.333  3819  3872 I jxcore-log: 
,09-09 15:14:03.334  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.334  3819  3872 I jxcore-log: 
09-09 15:14:03.334  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.334  3819  3872 I jxcore-log: 
09-09 15:14:03.334  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:03.334  3819  3872 I jxcore-log: 
,09-09 15:14:03.444  3819  3872 I jxcore-log: # teardown
09-09 15:14:03.444  3819  3872 I jxcore-log: 
,09-09 15:14:03.752  3628  4367 V KeepSync: Connecting to GoogleApiClient
09-09 15:14:03.753   875  2022 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 15:14:03.801  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:14:03.804  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:14:03.838  1542  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 15:14:03.838  1542  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 15:14:03.839  1542  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:14:03.839  1542  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:14:03.864  3819  3872 I jxcore-log: # setup
09-09 15:14:03.864  3819  3872 I jxcore-log: 
,09-09 15:14:03.881  1753  4368 V BaseAuthAsyncOperation: access token request failed
,09-09 15:14:03.884  3628  4367 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 15:14:03.943  1542  2197 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 15:14:03.945  1542  2197 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 15:14:03.945  1542  2197 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 15:14:03.946  1542  2197 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:14:03.967  3628  4367 E KeepSync: IOException
09-09 15:14:03.967  3628  4367 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 15:14:03.967  3628  4367 E KeepSync: 	,at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 15:14:03.967  3628  4367 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:14:03.967  3628  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 15:14:03.967  3628  4367 E KeepSync: 	... 10 more
09-09 15:14:03.967  3628  4367 W KeepSync: Sync result 2
,09-09 15:14:03.977   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 441387, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:14:04.025  3819  3872 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-09 15:14:04.025  3819  3872 I jxcore-log: 
,09-09 15:14:05.097  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:05.097  3819  3872 I jxcore-log: 
,09-09 15:14:05.105  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 42005
09-09 15:14:05.105  3819  3872 I jxcore-log: 
,09-09 15:14:05.114  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:05.114  3819  3872 I jxcore-log: 
,09-09 15:14:05.116  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:05.116  3819  3872 I jxcore-log: 
,09-09 15:14:05.118  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:05.118  3819  3872 I jxcore-log: 
,09-09 15:14:05.126  3819  3872 I jxcore-log: ok 31 we should not have gotten an error
09-09 15:14:05.126  3819  3872 I jxcore-log: 
,09-09 15:14:05.133  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:05.133  3819  3872 I jxcore-log: 
,09-09 15:14:05.137  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:05.137  3819  3872 I jxcore-log: 
,09-09 15:14:05.145  3819  3872 I jxcore-log: ok 32 Buffers are identical
09-09 15:14:05.145  3819  3872 I jxcore-log: 
,09-09 15:14:05.146  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:05.146  3819  3872 I jxcore-log: 
,09-09 15:14:05.149  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:05.149  3819  3872 I jxcore-log: 
,09-09 15:14:05.165  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:05.165  3819  3872 I jxcore-log: 
,09-09 15:14:05.166  3819  3872 I jxcore-log: ok 33 server should be fine
09-09 15:14:05.166  3819  3872 I jxcore-log: 
,09-09 15:14:05.167  3819  3872 I jxcore-log: ok 34 server should be open
09-09 15:14:05.167  3819  3872 I jxcore-log: 
,09-09 15:14:05.168  3819  3872 I jxcore-log: ok 35 incoming has been removed
09-09 15:14:05.168  3819  3872 I jxcore-log: 
,09-09 15:14:05.169  3819  3872 I jxcore-log: ok 36 The mux object should be closed
09-09 15:14:05.169  3819  3872 I jxcore-log: 
,09-09 15:14:05.170  3819  3872 I jxcore-log: ok 37 The mux stream should be closed
09-09 15:14:05.170  3819  3872 I jxcore-log: 
,09-09 15:14:05.175  3819  3872 I jxcore-log: # teardown
09-09 15:14:05.175  3819  3872 I jxcore-log: 
,09-09 15:14:06.020  3819  3872 I jxcore-log: # setup
09-09 15:14:06.020  3819  3872 I jxcore-log: 
,09-09 15:14:06.241  3819  3872 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-09 15:14:06.241  3819  3872 I jxcore-log: 
,09-09 15:14:07.245  3819  3872 I jxcore-log: DEBUG createNativeListener: creating native server
09-09 15:14:07.245  3819  3872 I jxcore-log: 
,09-09 15:14:07.253  3819  3872 I jxcore-log: DEBUG createNativeListener: listening 48558
09-09 15:14:07.253  3819  3872 I jxcore-log: 
,09-09 15:14:07.265  3819  3872 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-09 15:14:07.265  3819  3872 I jxcore-log: 
,09-09 15:14:07.266  3819  3872 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-09 15:14:07.266  3819  3872 I jxcore-log: 
,09-09 15:14:07.268  3819  3872 I jxcore-log: DEBUG createNativeListener: new mux
09-09 15:14:07.268  3819  3872 I jxcore-log: 
,09-09 15:14:07.275  3819  3872 I jxcore-log: ok 38 we should not have gotten an error
09-09 15:14:07.275  3819  3872 I jxcore-log: 
,09-09 15:14:07.282  3819  3872 I jxcore-log: DEBUG createNativeListener: new stream: 
09-09 15:14:07.282  3819  3872 I jxcore-log: 
,09-09 15:14:07.286  3819  3872 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-09 15:14:07.286  3819  3872 I jxcore-log: 
,09-09 15:14:07.299  3819  3872 I jxcore-log: ok 39 Buffers are identical
09-09 15:14:07.299  3819  3872 I jxcore-log: 
,09-09 15:14:07.306  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-09 15:14:07.306  3819  3872 I jxcore-log: 
,09-09 15:14:07.307  3819  3872 I jxcore-log: DEBUG createNativeListener: stream close:
09-09 15:14:07.307  3819  3872 I jxcore-log: 
,09-09 15:14:07.309  3819  3872 I jxcore-log: DEBUG createNativeListener: mux close
09-09 15:14:07.309  3819  3872 I jxcore-log: 
,09-09 15:14:07.314  3819  3872 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-09 15:14:07.314  3819  3872 I jxcore-log: 
,09-09 15:14:07.315  3819  3872 I jxcore-log: ok 40 server should be fine
09-09 15:14:07.315  3819  3872 I jxcore-log: 
09-09 15:14:07.315  3819  3872 I jxcore-log: ok 41 server should be open
09-09 15:14:07.315  3819  3872 I jxcore-log: 
,09-09 15:14:07.316  3819  3872 I jxcore-log: ok 42 incoming has been removed
09-09 15:14:07.316  3819  3872 I jxcore-log: 
09-09 15:14:07.316  3819  3872 I jxcore-log: ok 43 The mux object should be closed
09-09 15:14:07.316  3819  3872 I jxcore-log: 
09-09 15:14:07.317  3819  3872 I jxcore-log: ok 44 The mux stream should be closed
09-09 15:14:07.317  3819  3872 I jxcore-log: 
,09-09 15:14:07.325  3819  3872 I jxcore-log: # teardown
09-09 15:14:07.325  3819  3872 I jxcore-log: 
,09-09 15:14:07.766  3819  3872 I jxcore-log: # setup
09-09 15:14:07.766  3819  3872 I jxcore-log: 
,09-09 15:14:08.164  3819  3872 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
09-09 15:14:08.164  3819  3872 I jxcore-log: 
,09-09 15:14:09.310  3819  3872 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
09-09 15:14:09.310  3819  3872 I jxcore-log: 
,09-09 15:14:09.312  3819  3872 I jxcore-log: ok 45 Got right error
09-09 15:14:09.312  3819  3872 I jxcore-log: 
,09-09 15:14:09.317  3819  3872 I jxcore-log: # teardown
09-09 15:14:09.317  3819  3872 I jxcore-log: 
,09-09 15:14:10.117  3819  3872 I jxcore-log: # setup
09-09 15:14:10.117  3819  3872 I jxcore-log: 
,09-09 15:14:10.523  3819  3872 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
09-09 15:14:10.523  3819  3872 I jxcore-log: 
,09-09 15:14:11.603  3819  3872 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
09-09 15:14:11.603  3819  3872 I jxcore-log: 
,09-09 15:14:11.605  3819  3872 I jxcore-log: ok 46 Got socket hang up
09-09 15:14:11.605  3819  3872 I jxcore-log: 
,09-09 15:14:11.610  3819  3872 I jxcore-log: # teardown
09-09 15:14:11.610  3819  3872 I jxcore-log: 
,09-09 15:14:11.766  3819  3872 I jxcore-log: # setup
09-09 15:14:11.766  3819  3872 I jxcore-log: 
,09-09 15:14:12.776  3819  3872 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
09-09 15:14:12.776  3819  3872 I jxcore-log: 
,09-09 15:14:13.500  3819  3872 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq []
09-09 15:14:13.500  3819  3872 I jxcore-log: 
09-09 15:14:13.501  3819  3872 I jxcore-log: ok 47 Got 500 as expected
09-09 15:14:13.501  3819  3872 I jxcore-log: 
,09-09 15:14:13.505  3819  3872 I jxcore-log: # teardown
09-09 15:14:13.505  3819  3872 I jxcore-log: 
,09-09 15:14:14.525  3819  3872 I jxcore-log: # setup
09-09 15:14:14.525  3819  3872 I jxcore-log: 
,09-09 15:14:14.956  3819  3872 I jxcore-log: # 15. #_doImmediateSeqUpdate - create new seq doc
09-09 15:14:14.956  3819  3872 I jxcore-log: 
,09-09 15:14:17.737  3819  3872 I jxcore-log: ok 48 should be equal
09-09 15:14:17.737  3819  3872 I jxcore-log: 
09-09 15:14:17.737  3819  3872 I jxcore-log: ok 49 revs are equal
09-09 15:14:17.737  3819  3872 I jxcore-log: 
,09-09 15:14:17.741  3819  3872 I jxcore-log: # teardown
09-09 15:14:17.741  3819  3872 I jxcore-log: 
,09-09 15:15:09.359  3603  4372 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 15:15:09.386  3603  4373 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 15:15:09.401  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:15:09.404  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:15:09.435  1542  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 15:15:09.435  1542  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 15:15:09.435  1542  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:15:09.435  1542  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:15:09.469  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:15:09.471  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:15:09.506  1542  2947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 15:15:09.506  1542  2947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 15:15:09.506  1542  2947 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 15:15:09.507  1542  2947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:15:09.529  3603  4373 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 15:15:09.530  3603  4372 E BooksSync: Soft error
09-09 15:15:09.530  3603  4372 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:15:09.530  3603  4372 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 15:15:09.531  3603  4372 E BooksSync: Sync error
09-09 15:15:09.531  3603  4372 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 15:15:09.531  3603  4372 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 15:15:09.531  3603  4372 I BooksSync: Finished books sync
,09-09 15:15:09.545   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 507221, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:15:39.936  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:15:39.937  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:15:39.976  1542  2303 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 15:15:39.976  1542  2303 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 15:15:39.976  1542  2303 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:15:39.976  1542  2303 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:15:39.991  3543  4377 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 15:15:39.991  3543  4377 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at blb.a(PG:3937)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at czp.a(PG:18188)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:15:39.991  3543  4377 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at jdm.a(PG:77)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	... 12 more
09-09 15:15:39.991  3543  4377 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at fal.a(PG:38)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:15:39.991  3543  4377 E HttpOperation: 	... 14 more
,09-09 15:15:40.107  1542  2197 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 15:15:40.107  1542  2197 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 15:15:40.107  1542  2197 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:15:40.107  1542  2197 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:15:40.126  3543  4377 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 15:15:40.126  3543  4377 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at jdm.a(PG:82)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at jcs.o(PG:406)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at jcn.a(PG:1379)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at jcs.i(PG:143)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at hec.a(PG:42)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at hee.a(PG:102)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at czr.a(PG:65)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at kka.a(PG:108)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at czp.a(PG:19176)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at czp.a(PG:9081)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at czq.run(PG:1686)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:15:40.126  3543  4377 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at jdj.a(PG:4091)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at jdj.a(PG:1125)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at jdm.a(PG:77)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	... 15 more
09-09 15:15:40.126  3543  4377 E HttpOperation: Caused by: faj: BadAuthentication
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at fal.a(PG:38)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	at jdj.a(PG:4089)
09-09 15:15:40.126  3543  4377 E HttpOperation: 	... 17 more
09-09 15:15:40.126  3543  4377 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 15:15:40.126  3543  4377 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at hec.a(PG:42)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at hee.a(PG:102)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at czr.a(PG:65)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at kka.a(PG:108)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	... 15 more
09-09 15:15:40.126  3543  4377 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at fal.a(PG:38)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 15:15:40.126  3543  4377 E ExperimentLoader: 	... 17 more
,09-09 15:15:40.268   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 529603, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:16:12.774  3628  4380 V KeepSync: Connecting to GoogleApiClient
,09-09 15:16:12.775   875  1915 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 15:16:12.838  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:16:12.843  1542  1542 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 15:16:12.887  1542  3056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 15:16:12.888  1542  3056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 15:16:12.888  1542  3056 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:16:12.888  1542  3056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:16:12.920  1753  4381 V BaseAuthAsyncOperation: access token request failed
,09-09 15:16:12.922  3628  4380 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 15:16:13.022  1542  2303 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 15:16:13.022  1542  2303 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 15:16:13.022  1542  2303 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 15:16:13.022  1542  2303 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 15:16:13.060  3628  4380 E KeepSync: IOException
09-09 15:16:13.060  3628  4380 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 15:16:13.060  3628  4380 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 15:16:13.060  3628  4380 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 15:16:13.060  3628  4380 E KeepSync: 	... 10 more
,09-09 15:16:13.060  3628  4380 W KeepSync: Sync result 2
,09-09 15:16:13.077   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 570546, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 15:21:39.220   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=897143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:21:51.406   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=909330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:22:04.313   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=922237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:22:16.473   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=934397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:22:29.380   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=947304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:22:41.540   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=959464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:22:54.446   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=972370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:23:06.606   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=984530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:23:19.513   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=997437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:23:31.673   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1009597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:23:44.580   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1022504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:23:56.740   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1034664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:24:09.646   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1047570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:24:21.793   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1059717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:24:34.713   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1072637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:24:46.873   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1084797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:24:59.780   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1097704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:25:11.939   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1109863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:25:12.193  1753  4415 I EventLogService: Opted in for usage reporting
,09-09 15:25:12.194  1753  4415 I EventLogService: Aggregate from 1473425560401 (log), 1473425560401 (data)
,09-09 15:25:12.257  1753  4415 W EventLogAggregator: Unknown tag: snet_gcore
,09-09 15:25:12.258  1753  4415 W EventLogAggregator: Unknown tag: snet_launch_service
,09-09 15:25:12.388  1753  4415 I ServiceDumpSys: dumping service [account]
,09-09 15:25:30.126   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1128050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:25:37.006   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1134930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:25:49.913   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1147837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:26:02.100   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1160024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:26:15.033   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1172957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:26:27.180   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1185104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:26:33.806   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1191730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:26:52.246   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1210170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:26:58.873   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1216797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:27:00.126   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,09-09 15:27:17.340   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1235264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:27:23.966   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1241890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:27:42.406   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1260330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:27:49.033   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1266957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:28:07.460   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1285384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:28:14.086   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1292010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:28:32.526   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1310450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:28:39.166   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1317090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:28:57.606   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1335530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:29:04.232   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1342156, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:29:22.713   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1360637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:29:29.339   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1367263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:29:47.779   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1385703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:29:54.406   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1392330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:30:12.846   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1410770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:30:19.486   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1417410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:30:37.940   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1435864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:30:44.566   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1442490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:31:03.033   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1460957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:31:09.659   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1467583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:31:28.100   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1486024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:31:41.113   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1499037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 15:31:53.166   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1511090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 15:32:06.180   875  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1524104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-09 15:32:13.090  4438  4438 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 15:32:13.095  4438  4438 D AndroidRuntime: CheckJNI is OFF
09-09 15:32:13.131  4438  4438 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 15:32:13.171  4438  4438 I Radio-JNI: register_android_hardware_Radio DONE
09-09 15:32:13.192  4438  4438 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 15:32:13.201   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 15:32:13.202   875   888 I ActivityManager: Killing 3819:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-09 15:32:13.306   875  1915 D GraphicsStats: Buffer count: 2
09-09 15:32:13.307   875  1317 D WifiService: Client connection lost with reason: 4
09-09 15:32:13.311   875  1917 I WindowState: WIN DEATH: Window{2a1f319 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 15:32:13.319   875   898 W PackageSettings: Skipping PackageSetting{3585955 com.example.hello/10273} due to missing metadata
09-09 15:32:13.368   875   898 I art     : Starting a blocking GC Explicit
09-09 15:32:13.377   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-09 15:32:13.379   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-09 15:32:13.382   875   888 E ActivityManager: Failure starting process com.test.thalitest
09-09 15:32:13.382   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 15:32:13.382   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:32:13.382   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.382   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 15:32:13.382   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 15:32:13.386   875   888 I ActivityManager:   Force finishing activity ActivityRecord{ca5bca6 u0 com.test.thalitest/.MainActivity t4}
09-09 15:32:13.397   875  1961 W ActivityManager: Spurious death for ProcessRecord{6652b5a 0:com.test.thalitest/u0a0}, curProc for 3819: null
09-09 15:32:13.416   875   898 I art     : Explicit concurrent mark sweep GC freed 82835(5MB) AllocSpace objects, 13(260KB) LOS objects, 33% free, 29MB/43MB, paused 965us total 47.145ms
09-09 15:32:13.440   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-09 15:32:13.445   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-09 15:32:13.446  4438  4438 I art     : System.exit called, status: 0
09-09 15:32:13.446  4438  4438 I AndroidRuntime: VM exiting with result code 0.
09-09 15:32:13.470   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-09 15:32:13.477  4227  4227 D BluetoothMapAppObserver: onReceive
09-09 15:32:13.477  4227  4227 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 15:32:13.480   875  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 15:32:13.482  1878  1878 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 15:32:13.484  2174  2294 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 15:32:13.485  3688  3688 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 15:32:13.512   875  2022 I ActivityManager: Start proc 4452:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-09 15:32:13.513  1947  1947 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-09 15:32:13.526  1878  4450 I Keyboard.Facilitator.DecoderInitializer: run()
09-09 15:32:13.528  1878  4450 I Decoder : createOrResetDecoder
09-09 15:32:13.551  1542  1542 I ConfigService: onCreate
09-09 15:32:13.553  4452  4452 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 15:32:13.562  1542  4466 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 15:32:13.562  1542  4466 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 15:32:13.563  1542  4466 W SQLiteOpenHelper: Opened config.db in read-only mode
09-09 15:32:13.578   875  1917 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3819 uid 10000
09-09 15:32:13.579  1878  1878 I Keyboard.Facilitator: onFinishInput()
09-09 15:32:13.579  1878  4450 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-09 15:32:13.590   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 15:32:13.602  1878  4450 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-09 15:32:13.605  1878  4450 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 15:32:13.605  1878  4450 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-09 15:32:13.606   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-09 15:32:13.607  1878  4450 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 15:32:13.607   875   887 E PackageManager: Failed to write settings, restoring backup
09-09 15:32:13.607   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 15:32:13.607   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 15:32:13.607   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 15:32:13.607   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 15:32:13.607   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 15:32:13.607   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:32:13.607   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.607   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 15:32:13.607  1878  4450 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 15:32:13.607  1878  4450 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 15:32:13.607  1878  4450 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-09 15:32:13.608  1878  4450 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-09 15:32:13.608  1878  4450 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 15:32:13.608  1878  4450 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 15:32:13.608  1878  4450 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 15:32:13.608  1878  4450 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 15:32:13.609  1878  4450 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-09 15:32:13.611   875   888 E DropBoxManagerService: Can't write: system_server_wtf
09-09 15:32:13.611   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 15:32:13.611   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 15:32:13.611   875   888 E DropBoxManagerService: 	... 13 more
09-09 15:32:13.615  1962  2042 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 15:32:13.627   875   886 I ActivityManager: Start proc 4471:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-09 15:32:13.628  1962  2042 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 15:32:13.628  1962  2042 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1962
09-09 15:32:13.628  1962  2042 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.628  1962  2042 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: Can't write: system_app_crash
09-09 15:32:13.630   875  4477 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 15:32:13.630   875  4477 E DropBoxManagerService: 	... 5 more
09-09 15:32:13.631   875  2021 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 15:32:13.631  4452  4452 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-09 15:32:13.638  1962  2042 I Process : Sending signal. PID: 1962 SIG: 9
09-09 15:32:13.658   875  1915 I ActivityManager: Start proc 4486:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-09 15:32:13.660  4452  4485 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 15:32:13.685  4486  4486 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-09 15:32:13.737  1542  1542 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 15:32:13.739  1542  1542 D AndroidRuntime: Shutting down VM
09-09 15:32:13.740  1542  1542 E AndroidRuntime: FATAL EXCEPTION: main
09-09 15:32:13.740  1542  1542 E AndroidRuntime: Process: com.google.process.gapps, PID: 1542
09-09 15:32:13.740  1542  1542 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 15:32:13.740  1542  1542 E AndroidRuntime: 	... 8 more
09-09 15:32:13.743   875  4503 E DropBoxManagerService: Can't write: system_app_crash
09-09 15:32:13.743   875  4503 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 15:32:13.743   875  4503 E DropBoxManagerService: 	... 5 more
09-09 15:32:13.744  1542  1542 I Process : Sending signal. PID: 1542 SIG: 9
09-09 15:32:13.762   875  1305 W InputDispatcher: channel 'd41d2af com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-09 15:32:13.762   875  1305 E InputDispatcher: channel 'd41d2af com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-09 15:32:13.762   875  1917 D GraphicsStats: Buffer count: 1
09-09 15:32:13.762   875  1391 I WindowState: WIN DEATH: Window{d41d2af u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-09 15:32:13.763   875  1391 W InputDispatcher: Attempted to unregister already unregistered input channel 'd41d2af com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.769  4452  4469 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.769  4452  4469 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 15:32:13.785   875  1917 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1962) has died
09-09 15:32:13.786   875  1917 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 15:32:13.788   875  1917 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 15:32:13.811   875   888 I ActivityManager: Start proc 4505:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 15:32:13.833  4452  4469 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-09 15:32:13.837   875  1317 D WifiService: Client connection lost with reason: 4
09-09 15:32:13.838  1753  4502 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@1c3301f
09-09 15:32:13.848   875  1915 I ActivityManager: Process com.google.process.gapps (pid 1542) has died
09-09 15:32:13.848   875  1915 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-09 15:32:13.848   875  1915 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
09-09 15:32:13.848   875  1915 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
09-09 15:32:13.869  1753  1753 W RocketImpressions: ClearcutLogger connection suspended: 1
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.882  4452  4485 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 15:32:13.883  4452  4485 E AndroidRuntime: Process: android.process.acore, PID: 4452
09-09 15:32:13.883  4452  4485 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.883  4452  4485 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 15:32:13.884  4452  4469 I Process : Sending signal. PID: 4452 SIG: 9
09-09 15:32:13.895   875  2021 I ActivityManager: Start proc 4517:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
09-09 15:32:13.901   875  4528 E DropBoxManagerService: Can't write: system_app_crash
09-09 15:32:13.901   875  4528 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 15:32:13.901   875  4528 E DropBoxManagerService: 	... 5 more
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:32:13.907  4505  4505 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:32:13.908  4505  4505 D AndroidRuntime: Shutting down VM
09-09 15:32:13.921  4505  4505 E AndroidRuntime: FATAL EXCEPTION: main
09-09 15:32:13.921  4505  4505 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4505
09-09 15:32:13.921  4505  4505 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 15:32:13.921  4505  4505 E AndroidRuntime: 	... 10 more
09-09 15:32:13.923   875  1404 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 15:32:13.924  4505  4505 I Process : Sending signal. PID: 4505 SIG: 9
09-09 15:32:13.927   875  4531 E DropBoxManagerService: Can't write: system_app_crash
09-09 15:32:13.927   875  4531 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 15:32:13.927   875  4531 E DropBoxManagerService: 	... 5 more

```
