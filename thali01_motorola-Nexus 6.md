#### Test 846566318ce6636_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 12:40:02.136  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:02.152  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 12:40:02.159  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 12:40:02.235  1495  2016 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 12:40:02.235  1495  2016 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:40:02.235  1495  2016 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:40:02.235  1495  2016 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 12:40:02.277  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 12:40:02.278  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 12:40:02.279  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-12 12:40:02.785  3782  3782 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 12:40:02.789  3782  3782 D AndroidRuntime: CheckJNI is OFF
09-12 12:40:02.825  3782  3782 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 12:40:02.867  3782  3782 I Radio-JNI: register_android_hardware_Radio DONE
09-12 12:40:02.888  3782  3782 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 12:40:02.894   872   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 12:40:02.935  2057  2076 W SearchService: Abort, client detached.
09-12 12:40:02.948  2057  2331 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fd1e6dd
09-12 12:40:02.948  2057  2343 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 12:40:02.949  2057  2057 I HotwordDetector: Closing mic
09-12 12:40:02.953  3782  3782 D AndroidRuntime: Shutting down VM
09-12 12:40:02.996   872  2007 I ActivityManager: Start proc 3791:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 12:40:03.007   376  2345 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 12:40:03.008   376  2345 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 12:40:03.014   376  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 12:40:03.018  2057  2342 I MicroRecognitionRnrImpl: Detection finished
09-12 12:40:03.017  2057  2336 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 12:40:03.092  3791  3791 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 12:40:03.126  3791  3791 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 12:40:03.140  3791  3791 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 202-210)
09-12 12:40:03.140  3791  3791 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 12:40:03.162  3791  3791 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31f5a16}
09-12 12:40:03.163  3791  3791 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 12:40:03.163  3791  3791 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 12:40:03.172  3791  3791 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 12:40:03.174  3791  3791 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 12:40:03.199  3791  3791 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 12:40:03.211  3791  3791 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 12:40:03.211  3791  3791 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 12:40:03.211  3791  3791 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 12:40:03.211  3791  3791 I Adreno  : Build Date                       : 10/20/15
09-12 12:40:03.211  3791  3791 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 12:40:03.211  3791  3791 I Adreno  : Local Branch                     : M14
09-12 12:40:03.211  3791  3791 I Adreno  : Remote Branch                    : 
09-12 12:40:03.211  3791  3791 I Adreno  : Remote Branch                    : 
09-12 12:40:03.211  3791  3791 I Adreno  : Reconstruct Branch               : 
,09-12 12:40:03.285   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7ba53a7:true
,09-12 12:40:03.360  3791  3791 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 12:40:03.377  3791  3791 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 12:40:03.431  3791  3829 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 12:40:03.438  3791  3816 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 12:40:03.475  3791  3829 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 12:40:03.536   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +565ms
,09-12 12:40:03.542  1895  1895 I Keyboard.Facilitator: onFinishInput()
,09-12 12:40:03.617  3791  3791 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3791
,09-12 12:40:03.723  3791  3791 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 12:40:03.808   872   883 I ActivityManager: Killing 3230:com.google.android.gm/u0a78 (adj 15): empty #17
,09-12 12:40:03.877   872   883 I ActivityManager: Killing 3140:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-12 12:40:04.031  3791  3831 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1698039504
,09-12 12:40:04.043  3791  3831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 12:40:04.043  3791  3831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 12:40:04.043  3791  3831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 12:40:04.043  3791  3831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 12:40:04.043  3791  3831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 12:40:04.043  3791  3831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@447cae5 added. We now have 1 listener(s)
,09-12 12:40:04.048  3791  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 12:40:04.049  3791  3831 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 12:40:04.058  3791  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 12:40:04.058  3791  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 12:40:04.070  3791  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42f3061 added. We now have 1 listener(s)
,09-12 12:40:04.072  3791  3831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:40:04.081   872  1313 D WifiService: New client listening to asynchronous messages
09-12 12:40:04.083  3791  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 12:40:04.083  3791  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 12:40:04.083  3791  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 12:40:04.084  3791  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-12 12:40:04.084  3791  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 12:40:04.088  3791  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:40:04.088  3791  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 12:40:04.098  3791  3831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 12:40:04.099  3791  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:40:04.099  3791  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:04.099  3791  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:04.099  3791  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:04.099  3791  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:40:04.099  3791  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:04.099  3791  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:04.099  3791  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:40:04.099  3791  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-12 12:40:04.099  3791  3831 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:40:04.102  3791  3831 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 12:40:04.255  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:04.261  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:04.266  3791  3791 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 12:40:04.939  3791  3839 W jxcore-log: Initializing JXcore engine
,09-12 12:40:04.939  3791  3839 W jxcore-log: JXcore engine is ready
,09-12 12:40:04.982  3839  3839 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 12:40:04.982  3839  3839 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11717]" dev="sockfs" ino=11717 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-12 12:40:04.982  3839  3839 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 12:40:04.982  3839  3839 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26684]" dev="sockfs" ino=26684 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 12:40:04.997  3791  3839 W jxcore-log: Starting JXcore engine
,09-12 12:40:05.080  3791  3839 W jxcore-log: Platform android
09-12 12:40:05.080  3791  3839 W jxcore-log: 
,09-12 12:40:05.080  3791  3839 W jxcore-log: Process ARCH arm
09-12 12:40:05.080  3791  3839 W jxcore-log: 
,09-12 12:40:05.340  3791  3839 I jxcore-log: JXcore Cordova bridge is ready!
09-12 12:40:05.340  3791  3839 I jxcore-log: 
,09-12 12:40:05.341  3791  3839 W jxcore-log: JXcore engine is started
,09-12 12:40:05.349  3791  3831 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 12:40:05.354  3791  3791 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 12:40:05.550   872  1312 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 12:40:09.354  3595  3847 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:40:09.393  3595  3848 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:40:09.413  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:09.418  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:09.463  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 12:40:09.463  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 12:40:09.464  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:40:09.464  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:40:09.521  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:09.528  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:09.591  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:40:09.591  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 12:40:09.592  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:40:09.592  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:40:09.635  3595  3848 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 12:40:09.639  3595  3847 E BooksSync: Soft error
09-12 12:40:09.639  3595  3847 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:40:09.639  3595  3847 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:40:09.640  3595  3847 E BooksSync: Sync error
09-12 12:40:09.640  3595  3847 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:40:09.640  3595  3847 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:40:09.640  3595  3847 I BooksSync: Finished books sync
,09-12 12:40:09.646   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126350, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:40:22.458  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:22.471  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:22.477  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:22.541  1495  2016 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:40:22.541  1495  2016 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:40:22.541  1495  2016 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:40:22.541  1495  2016 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:40:22.556  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:40:22.556  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 12:40:22.557  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 12:40:23.377  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 12:40:23.377  3791  3839 I jxcore-log: 
,09-12 12:40:23.381  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 12:40:23.381  3791  3839 I jxcore-log: 
,09-12 12:40:23.391  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:40:23.391  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:23.391  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:23.391  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:23.391  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:40:23.391  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:23.391  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:23.391  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:40:23.397  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:40:23.399  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 12:40:23.399  3791  3839 I jxcore-log: 
,09-12 12:40:23.401  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 12:40:23.401  3791  3839 I jxcore-log: 
,09-12 12:40:23.459  3791  3839 I jxcore-log: Running unit tests
09-12 12:40:23.459  3791  3839 I jxcore-log: 
,09-12 12:40:23.462  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 12:40:23.462  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f9e01d added. We now have 2 listener(s)
,09-12 12:40:23.464  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 12:40:23.464  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:40:23.464  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 12:40:23.464  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:40:23.465  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b7292 added. We now have 2 listener(s)
09-12 12:40:23.465  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:40:23.466  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:40:23.473  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:40:23.486  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:40:23.486  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:23.486  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:23.486  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:23.486  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:40:23.486  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:23.486  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:23.486  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:40:23.491  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:40:23.492  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:40:23.493  3791  3839 D executeNativeTests: Running unit tests
,09-12 12:40:23.497  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:23.505  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:23.586  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:40:23.586  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 added. We now have 3 listener(s)
,09-12 12:40:23.587  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 12:40:23.587  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 12:40:23.587  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 12:40:23.587  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:40:23.587  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 added. We now have 3 listener(s)
09-12 12:40:23.588  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:40:23.588  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 12:40:23.590  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:40:23.606  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:40:23.606  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:23.606  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:23.606  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:23.606  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:40:23.606  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:23.606  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:23.606  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:40:23.609  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:23.609  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:40:23.617  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 12:40:23.617  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:23.617  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:40:23.617  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 12:40:23.618  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:40:23.620  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:23.622  3791  3839 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 12:40:23.624  3791  3839 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 12:40:23.624  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 12:40:23.624  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 12:40:23.625  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 12:40:23.625  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 12:40:23.626  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:23.627  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:23.628  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:23.628  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:23.629  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:23.631  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:40:23.631  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 12:40:23.632  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 removed from the list
09-12 12:40:23.632  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:23.632  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 removed from the list
,09-12 12:40:23.632  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:23.633  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:23.634  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:23.635  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:23.636  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:40:23.636  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:23.636  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:23.636  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:23.638  3791  3839 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 12:40:23.638  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:23.638  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:23.638  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:23.639  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:23.639  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:23.639  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:23.639  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:23.639  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:23.639  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:23.639  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:23.639  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:23.639  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:23.639  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:23.639  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:23.641  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:23.641  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:23.642  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:23.642  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:23.661  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 12:40:23.662  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 12:40:23.662  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-12 12:40:23.662  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 12:40:23.663  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 12:40:23.663  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 12:40:23.663  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-12 12:40:23.663  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 12:40:23.664  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 12:40:23.664  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 12:40:23.664  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 12:40:23.664  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-12 12:40:23.665  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 12:40:23.665  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 12:40:23.665  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 12:40:23.665  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-12 12:40:23.666  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 12:40:23.666  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-12 12:40:23.666  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 12:40:23.667  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 12:40:23.668  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 12:40:23.668  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:23.668  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:40:23.668  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:23.668  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:23.668  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:23.668  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:23.668  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:23.668  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:23.668  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:23.668  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:23.668  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:23.668  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:23.669  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:23.669  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:23.671  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:23.671  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:23.671  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:23.671  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:23.672  3791  3839 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 12:40:23.673  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:40:23.678  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:40:23.678  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:23.678  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:23.678  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:23.678  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:40:23.678  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:23.678  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:23.678  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:40:23.682  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:23.682  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:40:23.682  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:40:23.683  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 12:40:23.683  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 12:40:23.683  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:40:23.683  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 12:40:23.685  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:23.688  3791  3839 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 12:40:23.688  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 12:40:23.689  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:23.695  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 12:40:23.698  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 12:40:23.698  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 12:40:23.701  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 12:40:23.704  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 12:40:23.704  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 12:40:23.705  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 12:40:23.705  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 12:40:23.706  3791  3839 D BluetoothAdapter: STATE_ON
09-12 12:40:23.712  2708  2721 D BtGatt.GattService: registerClient() - UUID=79a736bf-c1ef-43ab-8669-926168241be3
09-12 12:40:23.713  2708  2759 D BtGatt.GattService: onClientRegistered() - UUID=79a736bf-c1ef-43ab-8669-926168241be3, clientIf=5
09-12 12:40:23.715  3791  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 12:40:23.716  2708  2892 D BtGatt.GattService: start scan with filters
09-12 12:40:23.725  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 12:40:23.725  2708  2763 D BtGatt.ScanManager: handling starting scan
09-12 12:40:23.727  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 12:40:23.727  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 12:40:23.728  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 12:40:23.728  2708  2763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
09-12 12:40:23.732  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 12:40:23.732  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 12:40:23.732  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 12:40:23.735  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 12:40:23.739  2708  2759 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 12:40:23.739  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:23.740  3791  3839 I io.jxcore.node.ConnectionHelper: start: OK
09-12 12:40:23.741  2708  2763 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 12:40:23.757  2708  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 12:40:23.757  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:23.758  2708  2763 D BtGatt.ScanManager: Starting BLE batch scan
09-12 12:40:23.759  2708  2763 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 12:40:23.795  2708  2759 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 12:40:23.795  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:23.819  2708  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 12:40:23.819  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:24.236  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 12:40:24.237  3791  3791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:40:24.237  3791  3791 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:40:25.322  2708  2708 D BtGatt.ScanManager: awakened up at time 142392
,09-12 12:40:25.324  2708  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:40:25.368  2708  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 12:40:25.369  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:25.369  2708  2759 D BtGatt.GattService: current time is 142439867380
,09-12 12:40:25.371  2708  2759 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -86, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -92, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -96, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -96, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 12:40:25.374  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 12:40:25.376  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 12:40:25.377  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 12:40:25.377  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 12:40:25.378  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 12:40:25.378  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 12:40:26.873  2708  2708 D BtGatt.ScanManager: awakened up at time 143942
,09-12 12:40:26.875  2708  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:40:26.886  2708  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 12:40:26.886  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:28.388  2708  2708 D BtGatt.ScanManager: awakened up at time 145457
,09-12 12:40:28.390  2708  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:40:28.428  2708  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-12 12:40:28.428  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:28.429  2708  2759 D BtGatt.GattService: current time is 145498955186
,09-12 12:40:28.429  2708  2759 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -92, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 12:40:28.430  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 12:40:28.750  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:40:28.750  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:28.751  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 12:40:28.751  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:28.751  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 12:40:28.752  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:40:28.752  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 12:40:28.752  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 12:40:28.753  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 12:40:28.755  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 12:40:28.756  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 12:40:28.758  3791  3839 D BluetoothAdapter: STATE_ON
,09-12 12:40:28.760  2708  2722 D BtGatt.GattService: stopScan() - queue size =1
,09-12 12:40:28.762  2708  2721 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 12:40:28.764  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 12:40:28.764  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 12:40:28.764  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 12:40:28.765  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 12:40:28.765  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 12:40:28.769  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:40:28.770  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 12:40:28.771  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 12:40:28.771  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 12:40:28.773  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:40:28.778  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:40:28.778  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:28.779  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:40:28.779  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:28.779  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:40:28.779  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:40:28.779  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:28.780  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:28.780  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:28.780  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:28.781  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:28.784  2708  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 12:40:28.784  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:28.784  2708  2763 D BtGatt.ScanManager: stopping BLe Batch
,09-12 12:40:28.791  2708  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 12:40:28.791  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:28.791  2708  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:40:28.824  2708  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-12 12:40:28.824  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:28.824  2708  2759 D BtGatt.GattService: current time is 145894873240
,09-12 12:40:28.825  2708  2759 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -93, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -94, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 12:40:28.825  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 12:40:28.826  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-12 12:40:28.827  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-12 12:40:28.827  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 12:40:28.827  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 12:40:29.280  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:40:33.196   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 12:40:33.205  1895  1895 I Keyboard.Facilitator: onFinishInput()
,09-12 12:40:33.209   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 12:40:33.209   872   892 I Adreno  : Build Date                       : 10/20/15
09-12 12:40:33.209   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 12:40:33.209   872   892 I Adreno  : Local Branch                     : M14
09-12 12:40:33.209   872   892 I Adreno  : Remote Branch                    : 
09-12 12:40:33.209   872   892 I Adreno  : Remote Branch                    : 
09-12 12:40:33.209   872   892 I Adreno  : Reconstruct Branch               : 
,09-12 12:40:33.239   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (193 us)
,09-12 12:40:33.783  3791  3839 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 12:40:33.844  3791  3791 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 12:40:33.844  3791  3791 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 12:40:33.879   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 12:40:33.883  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-12 12:40:33.907  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:40:33.907  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:33.907  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:33.907  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:33.907  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:40:33.907  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:33.907  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:33.907  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:40:33.908   872   881 I art     : Background partial concurrent mark sweep GC freed 29743(2MB) AllocSpace objects, 13(348KB) LOS objects, 33% free, 29MB/43MB, paused 991us total 101.874ms
,09-12 12:40:33.910  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:33.910  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:40:33.910  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:40:33.910  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 12:40:33.910  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 12:40:33.910  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:40:33.910  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 12:40:33.912  3791  3839 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 12:40:33.912  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 12:40:33.913   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 12:40:33.913  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:33.915  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:33.915  3791  3791 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@41dc11c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@db839c1, 16908290=android.view.AbsSavedState$1@db839c1}, android:focusedViewId=100}]}]
09-12 12:40:33.915  3791  3791 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 12:40:33.916  3791  3791 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 12:40:33.916  3791  3791 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-12 12:40:33.916   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-12 12:40:33.916   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-12 12:40:33.916   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-12 12:40:33.915  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 12:40:33.921  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 12:40:33.921  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 12:40:33.925  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 12:40:33.925  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 12:40:33.926  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 12:40:33.927  3791  3839 D BluetoothAdapter: STATE_ON
09-12 12:40:33.928  2708  2892 D BtGatt.GattService: registerClient() - UUID=be49fd8c-b529-480e-9022-aa04d3abed13
09-12 12:40:33.928  2708  2759 D BtGatt.GattService: onClientRegistered() - UUID=be49fd8c-b529-480e-9022-aa04d3abed13, clientIf=5
09-12 12:40:33.928  3791  3803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 12:40:33.929  2708  2721 D BtGatt.GattService: start scan with filters
09-12 12:40:33.931  2708  2763 D BtGatt.ScanManager: handling starting scan
,09-12 12:40:33.932  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 12:40:33.932  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 12:40:33.932  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 12:40:33.932  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 12:40:33.933  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 12:40:33.933  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 12:40:33.933  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:40:33.934  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 12:40:33.936  2708  2759 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 12:40:33.936  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:33.936  2708  2763 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 12:40:33.937  3791  3839 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 12:40:33.938  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:40:33.938  3791  3839 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 12:40:33.938  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:33.939  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 12:40:33.939  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:33.939  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 12:40:33.939  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:40:33.939  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 12:40:33.939  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-12 12:40:33.939  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:40:33.939  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 12:40:33.939  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 12:40:33.939  3791  3839 D BluetoothAdapter: STATE_ON,
,09-12 12:40:33.940  2708  2892 D BtGatt.GattService: stopScan() - queue size =1
09-12 12:40:33.940  2708  2721 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 12:40:33.940  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 12:40:33.940  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 12:40:33.940  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 12:40:33.941  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 12:40:33.941  2708  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 12:40:33.941  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:33.941  2708  2763 D BtGatt.ScanManager: Starting BLE batch scan
09-12 12:40:33.941  2708  2763 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 12:40:33.941  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 12:40:33.941  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:40:33.941  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 12:40:33.942  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 12:40:33.942  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 12:40:33.942  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:40:33.943  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:40:33.943  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:33.943  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:40:33.943  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:33.943  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:40:33.943  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:40:33.943  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:33.943  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:33.943  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:33.943  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:33.943  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:33.943  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:33.943  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:33.944  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:33.944  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:33.944  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:33.944  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:33.944  3791  3839 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 12:40:33.946  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:40:33.948  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:40:33.948  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:33.948  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:33.948  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:33.948  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:40:33.948  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:33.948  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:33.948  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:40:33.949  2708  2759 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 12:40:33.949  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:33.949  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:33.949  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:40:33.950  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 12:40:33.951  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:33.950  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 12:40:33.952  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 12:40:33.952  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:40:33.952  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:33.952  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 12:40:33.953  2708  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 12:40:33.954  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:33.955  3791  3839 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 12:40:33.955  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 12:40:33.958  2708  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 12:40:33.958  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:33.958  2708  2763 D BtGatt.ScanManager: stopping BLe Batch
09-12 12:40:33.959  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 12:40:33.959  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 12:40:33.960  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 12:40:33.962  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 12:40:33.963  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 12:40:33.963  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 12:40:33.963  3791  3839 D BluetoothAdapter: STATE_ON
09-12 12:40:33.963  2708  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 12:40:33.964  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:33.964  2708  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:40:33.965  2708  2721 D BtGatt.GattService: registerClient() - UUID=179d41d7-b554-4ea4-a3dd-7f5e8e536911
,09-12 12:40:33.965  2708  2759 D BtGatt.GattService: onClientRegistered() - UUID=179d41d7-b554-4ea4-a3dd-7f5e8e536911, clientIf=5
,09-12 12:40:33.966  3791  3802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 12:40:33.966  2708  2722 D BtGatt.GattService: start scan with filters
,09-12 12:40:33.967  2708  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 12:40:33.968  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:33.968  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 12:40:33.968  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 12:40:33.969  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 12:40:33.969  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 12:40:33.969  2708  2763 D BtGatt.ScanManager: handling starting scan
,09-12 12:40:33.971  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:40:33.971  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:40:33.971  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 12:40:33.973  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 12:40:33.973  2708  2759 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 12:40:33.973  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:33.974  2708  2763 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 12:40:33.975  3791  3839 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 12:40:33.977  2708  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 12:40:33.977  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:33.977  2708  2763 D BtGatt.ScanManager: Starting BLE batch scan
09-12 12:40:33.977  2708  2763 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 12:40:33.984  2708  2759 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 12:40:33.984  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:33.987  2708  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 12:40:33.987  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:34.149   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 12:40:34.155   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 12:40:34.162   872  1335 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
,09-12 12:40:34.166   872   892 I DreamManagerService: Entering dreamland.
09-12 12:40:34.167   872   892 I PowerManagerService: Dozing...
09-12 12:40:34.169   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 12:40:34.244   376  1284 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-12 12:40:34.244   376  1284 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 12:40:34.262   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:40:34.283  1977  3860 D NfcService: Discovery configuration equal, not updating.
,09-12 12:40:34.286   872  1312 E native  : do suspend false
,09-12 12:40:34.306   872  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 12:40:34.325   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:40:34.328   872  1312 E native  : do suspend true
,09-12 12:40:34.369   376  1283 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 12:40:34.370   376  1283 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 12:40:34.472  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 12:40:34.473  3791  3791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:40:34.473  3791  3791 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:40:34.490  2708  2708 D BtGatt.ScanManager: awakened up at time 151559
,09-12 12:40:34.493  2708  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:40:34.555  2708  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
09-12 12:40:34.555  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:34.556  2708  2759 D BtGatt.GattService: current time is 151626079748
,09-12 12:40:34.557  2708  2759 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -97, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 12:40:34.558  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 12:40:34.558  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 12:40:34.560  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 12:40:34.771   872  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-12 12:40:36.059  2708  2708 D BtGatt.ScanManager: awakened up at time 153128
,09-12 12:40:36.062  2708  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:40:36.114  2708  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 12:40:36.114  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:36.115  2708  2759 D BtGatt.GattService: current time is 153185155371
09-12 12:40:36.116  2708  2759 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -90, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -77, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -83, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -95, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 12:40:36.117  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 12:40:36.118  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 12:40:36.119  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 12:40:36.120  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 12:40:36.121  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-12 12:40:36.122  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 12:40:37.614  2708  2708 D BtGatt.ScanManager: awakened up at time 154684
,09-12 12:40:37.618  2708  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:40:37.628  2708  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 12:40:37.628  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:38.976  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:40:38.977  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:40:38.977  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 12:40:38.977  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:38.978  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 12:40:38.978  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 12:40:38.979  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 12:40:38.979  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 12:40:38.979  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:40:38.980  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 12:40:38.980  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 12:40:38.983  3791  3839 D BluetoothAdapter: STATE_ON,
09-12 12:40:38.985  2708  2721 D BtGatt.GattService: stopScan() - queue size =1
09-12 12:40:38.988  2708  2722 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 12:40:38.989  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 12:40:38.989  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 12:40:38.989  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 12:40:38.990  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
09-12 12:40:38.990  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 12:40:38.994  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:40:38.994  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 12:40:38.994  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 12:40:38.995  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 12:40:38.997  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:40:38.998  2708  2708 D BtGatt.ScanManager: awakened up at time 156068
09-12 12:40:39.001  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:40:39.002  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:40:39.002  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:40:39.011  2708  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 12:40:39.011  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:39.012  2708  2763 D BtGatt.ScanManager: stopping BLe Batch
,09-12 12:40:39.024  2708  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 12:40:39.024  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:40:39.024  2708  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:40:39.051  2708  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-12 12:40:39.051  2708  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:40:39.051  2708  2759 D BtGatt.GattService: current time is 156121621862
09-12 12:40:39.052  2708  2759 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -91, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -95, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -93, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 12:40:39.054  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 12:40:39.056  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 12:40:39.058  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 12:40:39.059  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 12:40:39.061  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 12:40:39.062  2708  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 12:40:39.183  1863  2646 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 12:40:39.503  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:40:39.504  3791  3791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:39.504  3791  3791 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:40:39.931  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:39.936  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:39.971  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 12:40:39.971  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:40:39.971  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:40:39.971  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:40:40.001  2999  3866 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:40:40.001  2999  3866 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:40:40.001  2999  3866 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	... 12 more
09-12 12:40:40.001  2999  3866 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at fal.a(PG:38)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:40:40.001  2999  3866 E HttpOperation: 	... 14 more
,09-12 12:40:40.048  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:40:40.048  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 12:40:40.048  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:40:40.048  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:40:40.069  2999  3866 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:40:40.069  2999  3866 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at hec.a(PG:42)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at hee.a(PG:102)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at czr.a(PG:65)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at kka.a(PG:108)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:40:40.069  2999  3866 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	... 15 more
09-12 12:40:40.069  2999  3866 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at fal.a(PG:38)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:40:40.069  2999  3866 E HttpOperation: 	... 17 more
,09-12 12:40:40.070  2999  3866 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 12:40:40.070  2999  3866 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	,at jcs.i(PG:143)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	... 15 more
09-12 12:40:40.070  2999  3866 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:40:40.070  2999  3866 E ExperimentLoader: 	... 17 more
,09-12 12:40:40.200   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130444, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:40:42.687  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:42.898  1495  3869 I VacuumService: Vacuum at: now=1473676842898 tag=VacuumService
,09-12 12:40:42.902  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:42.957  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 12:40:42.958  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:40:42.958  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:40:42.958  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:40:42.985  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:40:42.985  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 12:40:42.985  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 12:40:43.066  1495  3870 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-12 12:40:43.069  1495  3870 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 12:40:43.097  1495  3870 W Uploader:  no longer exists, so no auth token.
,09-12 12:40:44.002  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:40:44.003  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:40:44.003  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:40:44.003  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:40:44.004  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.004  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:40:44.004  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:44.005  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:44.005  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.005  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:40:44.005  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.007  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:44.007  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.010  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:44.010  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:40:44.011  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.011  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.012  3791  3839 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 12:40:44.014  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:40:44.015  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:44.015  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:40:44.016  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:44.016  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:44.016  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.017  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
,09-12 12:40:44.017  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.017  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:44.017  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:44.017  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:44.018  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.018  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:44.018  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.021  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:40:44.021  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:40:44.021  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.022  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.024  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 12:40:44.025  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:44.025  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:44.025  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:44.026  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:44.026  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.026  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.026  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:44.026  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.026  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:44.027  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:44.027  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.027  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.027  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.027  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.029  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:44.029  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:44.029  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.029  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:44.031  3791  3839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 12:40:44.031  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:44.031  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:44.031  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:44.032  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:44.032  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.032  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.033  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:44.033  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:44.033  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.034  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:44.034  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.034  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.034  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.034  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:44.035  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:44.036  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:40:44.036  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.036  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.036  3791  3839 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 12:40:44.036  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:44.037  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:44.037  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:44.037  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:44.037  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.037  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.037  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:44.037  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.037  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:44.037  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:44.037  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.037  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.037  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.037  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.039  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:40:44.039  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:40:44.039  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.040  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:44.041  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 12:40:44.043  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:40:44.043  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 12:40:44.044  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 12:40:44.044  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 12:40:44.044  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 12:40:44.044  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 12:40:44.044  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:40:44.044  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:40:44.044  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:44.044  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:44.044  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:44.044  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:40:44.044  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.044  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.045  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
,09-12 12:40:44.045  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:44.045  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.045  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:40:44.045  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:44.045  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:44.045  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:44.045  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.047  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:40:44.047  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:44.047  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.047  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.048  3791  3839 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 12:40:44.048  3791  3839 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 12:40:44.048  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 12:40:44.056  3791  3839 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 12:40:44.056  3791  3839 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-12 12:40:44.056  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 12:40:44.056  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 12:40:44.056  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 12:40:44.057  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 12:40:44.057  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 12:40:44.057  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 12:40:44.057  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 12:40:44.057  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 12:40:44.057  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 12:40:44.057  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 12:40:44.057  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 12:40:44.058  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 12:40:44.058  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 12:40:44.058  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 12:40:44.058  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 12:40:44.058  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 12:40:44.058  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 12:40:44.058  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 12:40:44.058  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 12:40:44.059  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 12:40:44.059  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 12:40:44.059  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 12:40:44.059  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 12:40:44.059  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 12:40:44.059  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 12:40:44.059  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 12:40:44.059  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
09-12 12:40:44.060  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 12:40:44.060  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 12:40:44.060  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 12:40:44.060  3791  3839 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 12:40:44.060  3791  3839 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 12:40:44.061  3791  3839 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 12:40:44.061  3791  3839 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 12:40:44.061  3791  3839 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 12:40:44.061  3791  3839 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 12:40:44.061  3791  3839 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 12:40:44.061  3791  3839 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 12:40:44.061  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 12:40:44.064  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 12:40:44.065  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 12:40:44.065  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-12 12:40:44.065  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 12:40:44.065  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 12:40:44.065  3791  3839 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-12 12:40:44.065  3791  3839 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 12:40:44.066  3791  3839 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 12:40:44.066  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:40:44.066  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-12 12:40:44.067  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:40:44.067  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:44.067  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.067  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:44.067  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 12:40:44.067  3791  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
09-12 12:40:44.068  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:44.068  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.068  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.068  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:44.068  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.068  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:44.068  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.068  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:44.069  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:44.069  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:44.069  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.069  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:44.070  3791  3839 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 12:40:44.070  3791  3878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 12:40:44.070  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:40:44.070  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:40:44.070  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:44.071  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:44.071  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.071  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.071  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:44.071  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.071  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:44.071  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:44.071  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.071  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.071  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.071  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.072  3791  3879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
09-12 12:40:44.072  3791  3879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 389)
,09-12 12:40:44.072  3791  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
09-12 12:40:44.073  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:44.073  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:44.073  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.073  2708  2889 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-12 12:40:44.073  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.074  3791  3839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-12 12:40:44.074  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:44.074  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:44.074  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:44.075  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:44.075  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.075  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:44.075  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:44.075  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.075  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.075  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:44.075  3791  3879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 389)
09-12 12:40:44.075  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.075  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:44.075  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.075  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.076  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:44.077  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:44.077  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.077  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.077  3791  3839 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-12 12:40:44.077  3791  3839 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 12:40:44.078  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 12:40:44.078  3791  3839 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 12:40:44.078  3791  3839 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 12:40:44.078  3791  3839 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 12:40:44.078  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 12:40:44.078  3791  3839 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 12:40:44.078  3791  3839 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-12 12:40:44.078  3791  3839 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 12:40:44.078  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 12:40:44.078  3791  3839 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 12:40:44.078  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:44.078  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:44.078  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:44.079  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:44.079  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:44.079  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.079  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:44.079  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.079  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.079  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:44.079  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.079  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.079  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:44.079  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.080  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:44.080  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:44.080  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.080  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.081  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:44.081  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:44.081  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:44.081  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:44.081  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:44.081  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:44.081  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:44.081  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:44.081  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:45.565   872  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-12 12:40:48.127   872  2081 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:40:49.082  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:49.083  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.083  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:49.083  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:49.084  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:49.084  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:49.084  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:49.085  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:40:49.085  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:40:49.086  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:49.086  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:49.087  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:49.087  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:49.087  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:49.088  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:49.088  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:49.088  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:49.089  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.089  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.089  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.093  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:40:49.093  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:49.093  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:49.094  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.098  3791  3839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 12:40:49.099  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:40:49.101  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 12:40:49.102  3791  3839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 12:40:49.102  3791  3839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 12:40:49.103  3791  3791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 12:40:49.103  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 12:40:49.103  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:40:49.104  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:40:49.104  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 12:40:49.104  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 12:40:49.104  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-12 12:40:49.104  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.104  3791  3839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 12:40:49.104  3791  3791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 12:40:49.104  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
,09-12 12:40:49.104  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:49.105  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 12:40:49.105  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 12:40:49.105  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 12:40:49.105  3791  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-12 12:40:49.105  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:49.105  3791  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
,09-12 12:40:49.105  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:49.106  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:40:49.107  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:40:49.107  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:40:49.107  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.107  3791  3791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-12 12:40:49.107  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,09-12 12:40:49.107  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:40:49.107  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:40:49.107  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:40:49.107  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:40:49.107  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-12 12:40:49.107  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.108  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:49.108  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:49.108  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.108  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:49.108  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:49.108  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.108  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.108  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.110  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:49.110  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:49.110  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:49.110  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.111  3791  3839 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 12:40:49.112  3791  3839 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 12:40:49.112  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 12:40:49.112  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 12:40:49.112  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 12:40:49.112  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:49.112  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:49.113  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:40:49.113  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:49.113  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.113  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.113  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:49.113  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:49.113  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.113  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:49.113  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.114  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.114  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:49.114  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.115  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:49.115  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:49.115  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:49.115  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.119  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:49.119  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:40:49.119  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:49.119  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:49.120  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.120  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.120  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
,09-12 12:40:49.120  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:49.120  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.120  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:49.120  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.120  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:49.120  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.120  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.122  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:49.123  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:49.123  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:49.123  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.124  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:40:49.124  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:40:49.124  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:40:49.125  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:40:49.125  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.125  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.125  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77c2990 not in the list
09-12 12:40:49.125  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:49.125  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
09-12 12:40:49.125  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:49.125  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.125  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.125  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:49.125  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:49.126  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:40:49.127  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:40:49.127  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:40:49.127  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7c289 not in the list
,09-12 12:40:49.129  3791  3839 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 12:40:49.129  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 12:40:49.129  3791  3839 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 12:40:49.129  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 12:40:49.129  3791  3839 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 12:40:49.129  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 12:40:49.133  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 12:40:49.133  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 12:40:49.133  3791  3839 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 12:40:49.134  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 12:40:49.134  3791  3839 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 12:40:49.134  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 12:40:49.134  3791  3839 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-12 12:40:49.134  3791  3839 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 12:40:49.135  3791  3839 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 12:40:49.135  3791  3839 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 12:40:49.135  3791  3839 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 12:40:49.135  3791  3839 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 12:40:49.136  3791  3839 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 12:40:49.136  3791  3839 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-12 12:40:49.137  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:40:49.137  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df516c0 added. We now have 3 listener(s)
09-12 12:40:49.137  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:40:49.141  3791  3839 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 12:40:49.141   872  2173 D WifiService: setWifiEnabled: true pid=3791, uid=10000
,09-12 12:40:49.141   872  2173 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:40:49.200  2708  2883 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-12 12:40:49.200  2708  2883 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-12 12:40:49.341  1495  3870 I art     : Waiting for a blocking GC DisableMovingGc
,09-12 12:40:49.356  1495  3870 I art     : WaitForGcToComplete blocked for 14.677ms for cause DisableMovingGc
,09-12 12:40:49.356  1495  3870 I art     : Starting a blocking GC DisableMovingGc
,09-12 12:40:49.402  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:49.404  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:40:49.436  1495  3870 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 12:40:49.436  1495  3870 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-12 12:40:49.436  1495  3870 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:40:49.436  1495  3870 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:40:49.457  1495  3870 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 12:40:49.457  1495  3870 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 12:40:49.457  1495  3870 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 12:40:49.608  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:40:49.650  1495  3870 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 12:40:49.651  1495  3870 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 12:40:49.651  1495  3870 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:40:49.651  1495  3870 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:40:49.675  1495  3870 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 12:40:49.675  1495  3870 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 12:40:49.675  1495  3870 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 12:40:50.327  1495  3870 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 12:40:50.327  1495  3870 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 12:40:50.328  1495  3870 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:40:50.328  1495  3870 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:40:50.351  1495  3870 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 12:40:50.351  1495  3870 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 12:40:50.351  1495  3870 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 12:40:54.149  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:40:54.149  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c95ff9 added. We now have 4 listener(s)
09-12 12:40:54.150  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:40:54.166  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:54.166  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c95ff9 removed from the list
09-12 12:40:54.166  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:40:54.167  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:40:54.167  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:40:54.170  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 12:40:54.171  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@291eb3e added. We now have 4 listener(s)
09-12 12:40:54.171  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:40:54.175  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:40:54.175  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@291eb3e removed from the list
09-12 12:40:54.176  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:40:54.176  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:40:54.176  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:40:54.178  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:40:54.179  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc23d9f added. We now have 4 listener(s)
,09-12 12:40:54.179  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:40:54.187   872  1374 D WifiService: setWifiEnabled: false pid=3791, uid=10000
,09-12 12:40:54.188   872  1374 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:40:54.205  2708  2755 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 12:40:54.205  2708  2755 D BluetoothAdapterProperties: Setting state to 13
,09-12 12:40:54.205  2708  2755 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 12:40:54.205  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:40:54.209  2708  2755 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 12:40:54.215  2708  2755 I BluetoothAdapterState: Entering PendingCommandState
09-12 12:40:54.220  2708  2708 D BluetoothMapService: onReceive
09-12 12:40:54.220  2708  2708 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 12:40:54.223  2708  2708 D BluetoothMapService: STATE_TURNING_OFF
09-12 12:40:54.223  2708  2708 D BluetoothMapService: MAP Service closeService in
09-12 12:40:54.223  2708  2708 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 12:40:54.223  2708  2708 D ObexServerSockets0: shutdown(block = true)
09-12 12:40:54.224  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.224  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:40:54.224  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:54.224  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:54.224  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:54.224  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:54.224  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:54.224  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:54.224  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:40:54.224  2708  2708 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 12:40:54.225  2708  2901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 12:40:54.225  2708  2900 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 12:40:54.226  2708  2708 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 12:40:54.227  2708  2889 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 12:40:54.227  2708  2708 I BtOppRfcommListener: stopping Accept Thread
09-12 12:40:54.228  2708  3438 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 12:40:54.228  2708  3438 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 12:40:54.230  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:40:54.230  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-12 12:40:54.231  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:40:54.233  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:54.235  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:54.239  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.239  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:54.239  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:54.239  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:54.239  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:54.239  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:54.239  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:54.239  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:54.239  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
09-12 12:40:54.240  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.240  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:54.243  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:40:54.243  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:54.243  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:54.243  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:54.243  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:54.243  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:54.243  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:54.243  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:40:54.243  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:40:54.244  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.244  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:40:54.245  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 12:40:54.248   872  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 12:40:54.248   872  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 12:40:54.248   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 12:40:54.248  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:54.248   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 12:40:54.251   872   885 I ActivityManager: Start proc 3890:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-12 12:40:54.252  2708  2759 D BluetoothAdapterProperties: Scan Mode:20
09-12 12:40:54.252  2708  2755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 12:40:54.255  2708  2708 D HeadsetService: Received stop request...Stopping profile...
,09-12 12:40:54.256  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:54.257   872   872 D BluetoothHeadset: Proxy object disconnected
,09-12 12:40:54.257   872   872 D BluetoothHeadset: Proxy object disconnected
,09-12 12:40:54.257   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 12:40:54.258  1363  2087 D BluetoothHeadset: Proxy object disconnected
09-12 12:40:54.258  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:54.258  1986  2068 D BluetoothHeadset: Proxy object disconnected
,09-12 12:40:54.260  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-12 12:40:54.260  2708  2708 V BluetoothAdapterState: isTurningOn()=false
09-12 12:40:54.260  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:40:54.260  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:40:54.260  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:54.260   872  1312 E native  : do suspend true
09-12 12:40:54.261  2708  2708 D A2dpService: Received stop request...Stopping profile...,
09-12 12:40:54.261  2708  2895 D A2dpStateMachine: Exit Disconnected: -1
09-12 12:40:54.262   872   872 D BluetoothA2dp: Proxy object disconnected
,09-12 12:40:54.264  2708  2708 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 12:40:54.264  2708  2759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 12:40:54.264  2708  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:40:54.264  2708  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 12:40:54.264  2708  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 12:40:54.264  2708  2759 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-12 12:40:54.268  1363  1363 D HeadsetProfile: Bluetooth service disconnected
,09-12 12:40:54.264  2708  2708 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 12:40:54.270  2708  2708 D HidService: Received stop request...Stopping profile...
,09-12 12:40:54.270  2708  2708 D HidService: Stopping Bluetooth HidService
,09-12 12:40:54.271  2708  2708 V BluetoothAdapterState: isTurningOff()=true
,09-12 12:40:54.271  2708  2708 V BluetoothAdapterState: isTurningOn()=false
09-12 12:40:54.271  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:40:54.271  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:40:54.272  2708  2708 D HealthService: Received stop request...Stopping profile...
,09-12 12:40:54.272   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 12:40:54.272  1363  1363 D BluetoothA2dp: Proxy object disconnected
09-12 12:40:54.273  1363  1363 D BluetoothInputDevice: Proxy object disconnected
09-12 12:40:54.273  1363  1363 D HidProfile: Bluetooth service disconnected
09-12 12:40:54.274   872  2083 D DhcpClient: Clearing IP address
09-12 12:40:54.275  2708  2759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 12:40:54.275  2708  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:40:54.275  2708  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 12:40:54.275  2708  2883 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 12:40:54.275  2708  2883 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 12:40:54.275  2708  2883 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 12:40:54.275  2708  2883 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 12:40:54.276  2708  2708 D PanService: Received stop request...Stopping profile...
09-12 12:40:54.278  2708  2708 D BluetoothMapService: Received stop request...Stopping profile...
09-12 12:40:54.278  2708  2708 D BluetoothMapService: stop()
09-12 12:40:54.276   372   871 D CommandListener: Setting iface cfg
09-12 12:40:54.280   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 12:40:54.280  2708  2708 D BluetoothMapAppObserver: deinitObservers()
09-12 12:40:54.280   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-12 12:40:54.280  2708  2708 D BluetoothMapAppObserver: removeReceiver()
,09-12 12:40:54.281   872  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
09-12 12:40:54.282   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 12:40:54.282   872  1312 E native  : do suspend true
,09-12 12:40:54.284   872  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 12:40:54.285   403   403 E Parcel  : Reading a NULL string not supported here.
09-12 12:40:54.287  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 12:40:54.287  1363  1363 D PanProfile: Bluetooth service disconnected
09-12 12:40:54.288  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-12 12:40:54.288  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,09-12 12:40:54.288  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:40:54.288  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:40:54.289  2708  2708 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 12:40:54.289  2708  2759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 12:40:54.289  2708  2708 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 12:40:54.289  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-12 12:40:54.289  2708  2708 V BluetoothAdapterState: isTurningOn()=false
09-12 12:40:54.289  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:40:54.290  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:40:54.291  2708  2708 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 12:40:54.291  2708  2759 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-12 12:40:54.291  1363  1363 D BluetoothMap: Proxy object disconnected
09-12 12:40:54.291  1495  3492 V NativeCrypto: Read error: ssl=0x9aefda00: I/O error during system call, Connection timed out
09-12 12:40:54.291  1363  1363 D MapProfile: Bluetooth service disconnected
09-12 12:40:54.291  2708  2708 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 12:40:54.292  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-12 12:40:54.292  2708  2708 V BluetoothAdapterState: isTurningOn()=false
09-12 12:40:54.292  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:40:54.292  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:40:54.292  2708  2708 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 12:40:54.293  2708  2708 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 12:40:54.294  2708  2708 D BluetoothMapService: MAP Service closeService in
09-12 12:40:54.294  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-12 12:40:54.294  2708  2708 V BluetoothAdapterState: isTurningOn()=false
09-12 12:40:54.294  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:40:54.294  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:40:54.294  2708  2755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 12:40:54.294  2708  2755 D BluetoothAdapterProperties: Setting state to 15
09-12 12:40:54.294  2708  2755 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 12:40:54.295  1495  3492 V NativeCrypto: SSL shutdown failed: ssl=0x9aefda00: I/O error during system call, Broken pipe
09-12 12:40:54.295  1363  2087 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 12:40:54.296  2708  2755 I BluetoothAdapterState: Entering BleOnState
09-12 12:40:54.296  1363  1380 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:40:54.296  2708  2708 D BluetoothMapService: cleanup()
09-12 12:40:54.296  2708  2708 D BluetoothMapService: MAP Service closeService in
09-12 12:40:54.298  1363  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 12:40:54.299   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 12:40:54.299   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 12:40:54.299  1363  2087 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 12:40:54.300  1986  2005 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:40:54.301  1363  1380 D BluetoothMap: onBluetoothStateChange: up=false
09-12 12:40:54.301  1363  1379 D BluetoothPan: onBluetoothStateChange on: false
09-12 12:40:54.302   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:40:54.302   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 12:40:54.302   872  2086 D DhcpClient: Receive thread stopped
09-12 12:40:54.302  2708  2755 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 12:40:54.302  2708  2755 D BluetoothAdapterProperties: Setting state to 16
09-12 12:40:54.302  2708  2755 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-12 12:40:54.303  2708  2755 D BluetoothAdapterProperties: onBleDisable
09-12 12:40:54.303  2708  2755 I BluetoothAdapterState: Entering PendingCommandState
09-12 12:40:54.303  2708  2756 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 12:40:54.304  2708  2759 D BluetoothAdapterProperties: Scan Mode:20
09-12 12:40:54.304  2708  2883 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 12:40:54.305  2708  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:40:54.311  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.311  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:54.311  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:54.311  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:54.311  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:54.311  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:54.311  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:40:54.311  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:40:54.311  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:40:54.312  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.312  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:40:54.314  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.314  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:54.314  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:54.314  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:54.314  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:54.314  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:54.314  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:40:54.314  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:40:54.314  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:40:54.315  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.315  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:40:54.319  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.319  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:54.319  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:54.319  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:54.319  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:54.319  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:54.319  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:40:54.319  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:40:54.319  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:40:54.319  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.319  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:40:54.320  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:54.321  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:54.322  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:54.327   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:40:54.351   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:40:54.351   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 12:40:54.353   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:40:54.354   872  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 12:40:54.354   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:40:54.357   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 12:40:54.361  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:54.362  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:40:54.363  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:40:54.370   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:40:54.372   872  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 12:40:54.373  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.373  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:54.373  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:54.373  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:54.373  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:40:54.373  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:54.373  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:40:54.373  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:40:54.373  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:40:54.374  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.374  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:40:54.362  3425  3425 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a7852b0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-12 12:40:54.375  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.375  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:54.375  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:54.375  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:54.375  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:40:54.375  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:54.375  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:40:54.375  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:40:54.375  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:40:54.376  1863  2298 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 12:40:54.376  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.376  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:40:54.377  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:40:54.377  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:54.377  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:54.377  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:54.377  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:40:54.377  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:54.377  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:40:54.377  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:40:54.377  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:40:54.378  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:54.378  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:40:54.383  3890  3890 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 12:40:54.392  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 12:40:54.395   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e961fe8:true
,09-12 12:40:54.396  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 12:40:54.408   872   883 I ActivityManager: Start proc 3911:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 12:40:54.411   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 12:40:54.412   872  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 12:40:54.417  3890  3890 D LocalBluetoothProfileManager: Adding local MAP profile
09-12 12:40:54.419  3890  3890 D BluetoothMap: Create BluetoothMap proxy object
,09-12 12:40:54.423  3890  3890 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 12:40:54.428  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,09-12 12:40:54.431   872  2006 I ActivityManager: Killing 2983:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-12 12:40:54.484  3911  3911 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 12:40:54.520  2708  2759 I bt_hci  : shut_down
,09-12 12:40:54.537  2708  2764 I bt_vendor: low_power_mode_cb
,09-12 12:40:54.541  2708  2764 D bt_hwcfg: hw_epilog_process
,09-12 12:40:54.553  2708  2764 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 12:40:54.553  2708  2764 I bt_vendor: epilog_cb
,09-12 12:40:54.553  2708  2764 I bt_hci  : epilog_finished_callback
,09-12 12:40:54.560  2708  2759 I bt_hci_h4: hal_close
,09-12 12:40:54.561  2708  2759 I bt_userial_vendor: device fd = 51 close
,09-12 12:40:54.648  3911  3911 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:40:54.648  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:40:54.649  3911  3911 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:40:54.649  3911  3911 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:40:54.649  3911  3911 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:40:54.649  3911  3911 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:40:54.649  3911  3911 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:40:54.649  3911  3911 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:40:54.649  3911  3911 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:40:54.649  3911  3911 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:40:54.658  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 12:40:54.665  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 12:40:54.672  3890  3890 D DockEventReceiver: finishStartingService: stopping service
09-12 12:40:54.686  2708  2756 D bt_stack_manager: event_shut_down_stack finished.
09-12 12:40:54.687  2708  2755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-12 12:40:54.687  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-12 12:40:54.691  2708  2708 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 12:40:54.692  2708  2708 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 12:40:54.692  2708  2708 D BtGatt.GattService: stop()
09-12 12:40:54.693  2708  2708 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 12:40:54.692  2708  2755 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 12:40:54.694  1713  1713 D SystemUpdateService: onCreate
09-12 12:40:54.695  2708  2708 V BluetoothAdapterState: isTurningOff()=false
09-12 12:40:54.696  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,09-12 12:40:54.696  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:40:54.696  2708  2708 V BluetoothAdapterState: isBleTurningOff()=true
09-12 12:40:54.697  2708  2755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 12:40:54.697  2708  2755 D BluetoothAdapterProperties: Setting state to 10
09-12 12:40:54.698  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-12 12:40:54.698  2708  2755 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 12:40:54.699  2708  2755 I BluetoothAdapterState: Entering OffState
09-12 12:40:54.700   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-12 12:40:54.724  1713  3941 I SystemUpdateService: active receiver: enabled
09-12 12:40:54.730  2708  2708 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 12:40:54.731  2708  2708 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 12:40:54.731  2708  2708 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 12:40:54.732  2708  2756 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-12 12:40:54.735  2708  2756 D bt_stack_manager: event_clean_up_stack finished.
,09-12 12:40:54.736  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 12:40:54.739  1713  2521 I iu.UploadsManager: num queued entries: 0
,09-12 12:40:54.751  2708  2708 I art     : System.exit called, status: 0
,09-12 12:40:54.751  2708  2708 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 12:40:54.764  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 12:40:54.767  1713  2521 I iu.UploadsManager: num updated entries: 0
,09-12 12:40:54.770  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 12:40:54.775  1713  2521 I iu.SyncManager: NEXT; no task
,09-12 12:40:54.797  1713  3941 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 12:40:54.798   872   882 I ActivityManager: Start proc 3944:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 12:40:54.811   872  2041 I ActivityManager: Process com.android.bluetooth (pid 2708) has died
,09-12 12:40:54.816  1713  3941 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 12:40:54.817  1713  3941 I SystemUpdateService: now status is 0 (complete)
,09-12 12:40:54.819  1713  3941 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 12:40:54.819  1713  3941 I SystemUpdateService: file has been verified
09-12 12:40:54.819  1713  3941 I SystemUpdateService: OTA package size = 12249756
,09-12 12:40:54.833  1713  3941 I SystemUpdateService: showing system update notification
,09-12 12:40:54.856  3944  3944 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 12:40:54.860  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:40:54.877  3944  3944 D SprintDMHelper: simOperator: 
,09-12 12:40:54.877  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 12:40:54.894   872  1680 I ActivityManager: Start proc 3957:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 12:40:54.895   872  1680 I ActivityManager: Killing 3425:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 12:40:54.988  1713  1713 D SystemUpdateService: onDestroy
,09-12 12:40:54.992   872  2006 I ActivityManager: Killing 3479:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 12:40:55.068  3911  3928 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 12:40:55.104   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28b8606:true
,09-12 12:40:55.147   872  1687 I ActivityManager: Start proc 3974:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 12:40:55.150  3083  3973 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 12:40:55.224  3974  3974 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 12:40:55.273  3974  3974 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 12:40:55.273  3974  3974 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 12:40:55.273  3974  3974 I GAv4    :   adb logcat -s GAv4
,09-12 12:40:55.288  3974  3974 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 12:40:55.294  3974  3974 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 12:40:55.325  3974  3992 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 12:40:55.428  3974  3974 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 12:40:55.465  3974  3974 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 12:40:55.475  3974  3974 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2542-2545)
,09-12 12:40:55.475  3974  3974 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 12:40:55.492  3974  3974 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7c3a56a}
,09-12 12:40:55.492  3974  3974 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 12:40:55.493  3974  3974 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 12:40:55.502  3974  3974 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 12:40:55.507  3974  3974 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 12:40:55.524  3974  3974 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 12:40:55.540  3974  3974 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
09-12 12:40:55.540  3974  3974 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 12:40:55.540  3974  3974 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 12:40:55.540  3974  3974 I Adreno  : Build Date                       : 10/20/15
09-12 12:40:55.540  3974  3974 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 12:40:55.540  3974  3974 I Adreno  : Local Branch                     : M14
09-12 12:40:55.540  3974  3974 I Adreno  : Remote Branch                    : 
09-12 12:40:55.540  3974  3974 I Adreno  : Remote Branch                    : 
09-12 12:40:55.540  3974  3974 I Adreno  : Reconstruct Branch               : 
,09-12 12:40:55.604  3974  3974 I NSApplication: Starting up...
,09-12 12:40:55.620  3974  4020 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 12:40:55.644   872   882 I ActivityManager: Start proc 4025:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-12 12:40:55.645   872   882 I ActivityManager: Killing 1693:android.process.acore/u0a5 (adj 15): empty #17
,09-12 12:40:55.717  4025  4025 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 12:40:55.922   872  1679 I ActivityManager: Killing 3674:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 12:40:56.018   872  1679 I ActivityManager: Start proc 4039:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 12:40:56.103  4039  4039 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 12:40:56.162  4039  4039 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 12:40:56.225   872  1687 I ActivityManager: Killing 3689:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 12:40:59.233   872  1403 D WifiService: setWifiEnabled: true pid=3791, uid=10000
,09-12 12:40:59.234   872  1403 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:40:59.247   872  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-12 12:40:59.256  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:59.256  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:59.256  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:59.256  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:59.256  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:59.256  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:59.256  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:40:59.256  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:40:59.256  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:40:59.256  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:40:59.257  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:40:59.260  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:40:59.260  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:59.260  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:59.260  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:59.260  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:59.260  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:59.260  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:40:59.260  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:40:59.260  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:40:59.261  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:59.261  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:40:59.264  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:59.265  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:40:59.265  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:40:59.265  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:40:59.265  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:40:59.265  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:40:59.265  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:40:59.265  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:40:59.265  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:40:59.265  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:40:59.265  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:40:59.281   872  1312 D WifiConfigStore: loaded 0 passpoint configs
09-12 12:40:59.282   872  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 12:40:59.283   872  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 12:40:59.284   872  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 12:40:59.284   872  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 12:40:59.284   872  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 12:40:59.284   872  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 12:40:59.301   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-12 12:40:59.301   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:40:59.304   372   871 D CommandListener: Setting iface cfg
,09-12 12:40:59.355   872  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-12 12:40:59.357   872  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 12:40:59.374   872  1312 E native  : do suspend true
09-12 12:40:59.376   872  1310 D WifiNative-HAL: p2pGetDeviceAddress
09-12 12:40:59.376   872  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 12:40:59.428   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:41:00.260   872  1679 I ActivityManager: Killing 3498:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 12:41:00.596   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:41:00.661   872  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.06 rxSuccessRate=9.44 delta 1000 -> 994
,09-12 12:41:00.663   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 12:41:00.663   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:41:00.682   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 12:41:00.732   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 12:41:00.734  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 12:41:01.503  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 12:41:01.579  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 12:41:01.581  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 12:41:01.589   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:41:01.602   872  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 12:41:01.602   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 12:41:01.602   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 12:41:01.618   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:41:01.629   372   871 D CommandListener: Setting iface cfg
,09-12 12:41:01.630   872  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 12:41:01.639   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 12:41:01.664   872  4074 D DhcpClient: Receive thread started
,09-12 12:41:01.752   872  1312 E native  : do suspend false
,09-12 12:41:01.772   872  2083 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 12:41:01.784   872  4074 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172644, domain null
,09-12 12:41:01.786   872  2083 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172644 seconds
,09-12 12:41:01.789   872  2083 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 12:41:01.804   872  4074 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 12:41:01.805   872  2083 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 12:41:01.811   372   871 D CommandListener: Setting iface cfg
,09-12 12:41:01.821   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 12:41:01.822   872  2083 D DhcpClient: Scheduling renewal in 86399s
,09-12 12:41:01.825   872  1312 E native  : do suspend true
,09-12 12:41:01.843   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 12:41:01.844   872  1312 D WifiConfigStore: No blacklist allowed without epno enabled
09-12 12:41:01.845   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 12:41:01.846   872  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 12:41:01.848   872  1314 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 12:41:01.898   872  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 12:41:01.899   872  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 12:41:01.900   872  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 12:41:01.903   872  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 12:41:01.908   872  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 12:41:01.921   872  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 12:41:01.927   872  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 12:41:01.927   872  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-12 12:41:01.928   872  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 12:41:01.928   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 12:41:01.928   872  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-12 12:41:01.929   872  1314 D ConnectivityService:    accepting network in place of null
,09-12 12:41:01.930   872  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 12:41:01.944   872  4073 D NetlinkSocketObserver: NeighborEvent{elapsedMs=179014, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:41:01.974   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:41:02.009   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:41:02.018   872  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 12:41:02.019   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:41:02.029   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 12:41:02.031   872  4072 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
09-12 12:41:02.034   872  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-12 12:41:02.043  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:02.043  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:02.043  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:02.043  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:02.043  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:02.043  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:41:02.043  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:02.043  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:02.043  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:41:02.044  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:02.044  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:41:02.045  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:02.045  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:02.045  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:02.045  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:02.045  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:02.045  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:41:02.045  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:02.045  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:02.045  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:41:02.046  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:02.046  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:02.047  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:02.047  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:02.047  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:02.047  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:02.047  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:02.047  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:41:02.047  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:02.047  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:02.047  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:41:02.048  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:02.048  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:41:02.062  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 12:41:02.068  1713  1713 D SystemUpdateService: onCreate
,09-12 12:41:02.070  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 12:41:02.094  1713  4085 I SystemUpdateService: active receiver: enabled
,09-12 12:41:02.097  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 12:41:02.102  1713  2521 I iu.UploadsManager: num queued entries: 0
,09-12 12:41:02.103  1713  2521 I iu.UploadsManager: num updated entries: 0
09-12 12:41:02.103  1713  2521 I iu.SyncManager: NEXT; no task
,09-12 12:41:02.110  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 12:41:02.110  1713  4085 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 12:41:02.111  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 12:41:02.113  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:41:02.126  1713  4087 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 12:41:02.126  1713  4087 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 12:41:02.129  3944  3944 D SprintDMHelper: simOperator: 
,09-12 12:41:02.129  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 12:41:02.131   872  4072 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 10:41:02 GMT], X-Android-Received-Millis=[1473676862129], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473676862084]}
,09-12 12:41:02.134   872  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 12:41:02.135   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-12 12:41:02.135   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 12:41:02.136  1713  4087 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 12:41:02.142   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 12:41:02.155  1713  4085 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 12:41:02.155  1713  4085 I SystemUpdateService: now status is 0 (complete)
09-12 12:41:02.155  1713  4085 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 12:41:02.155  1713  4085 I SystemUpdateService: file has been verified
,09-12 12:41:02.155  1713  4085 I SystemUpdateService: OTA package size = 12249756
,09-12 12:41:02.160  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:41:02.161  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-12 12:41:02.203  1713  4085 I SystemUpdateService: showing system update notification
,09-12 12:41:02.236  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 12:41:02.237  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 12:41:02.237  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:41:02.237  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:41:02.238  1713  1713 D SystemUpdateService: onDestroy
,09-12 12:41:02.264  3042  4084 V KeepSync: Connecting to GoogleApiClient
,09-12 12:41:02.265   872  2041 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:41:02.267  1713  4087 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-12 12:41:02.273  3083  4093 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 12:41:02.345  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 12:41:02.345  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 12:41:02.345  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:41:02.345  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:41:02.365  1713  4100 V BaseAuthAsyncOperation: access token request failed
,09-12 12:41:02.366  3042  4084 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:41:02.420  1495  2016 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 12:41:02.421  1495  2016 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 12:41:02.421  1495  2016 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:41:02.421  1495  2016 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:41:02.440  3042  4084 E KeepSync: IOException
09-12 12:41:02.440  3042  4084 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:41:02.440  3042  4084 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:41:02.440  3042  4084 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:41:02.440  3042  4084 E KeepSync: 	... 10 more
,09-12 12:41:02.440  3042  4084 W KeepSync: Sync result 2
,09-12 12:41:02.451   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 161437, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:41:03.018   872  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 12:41:04.241   872  2041 D WifiService: setWifiEnabled: false pid=3791, uid=10000
09-12 12:41:04.241   872  2041 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:41:04.279  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 12:41:04.290   872  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 12:41:04.290   872  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 12:41:04.291   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 12:41:04.292   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:41:04.312   872  1312 E native  : do suspend true
,09-12 12:41:04.332   872  2083 D DhcpClient: Clearing IP address
,09-12 12:41:04.333   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 12:41:04.344  1495  4099 V NativeCrypto: Read error: ssl=0xaece9e00: I/O error during system call, Connection timed out
09-12 12:41:04.351  1495  4099 V NativeCrypto: SSL shutdown failed: ssl=0xaece9e00: I/O error during system call, Broken pipe
09-12 12:41:04.352   372   871 D CommandListener: Setting iface cfg
,09-12 12:41:04.365   872  1374 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-12 12:41:04.365   872  4072 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-12 12:41:04.366   872  4074 D DhcpClient: Receive thread stopped
,09-12 12:41:04.377   872  4072 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 12:41:04.379   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-12 12:41:04.379   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 12:41:04.386   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 12:41:04.388   403   403 E Parcel  : Reading a NULL string not supported here.
,09-12 12:41:04.393   872  1312 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-12 12:41:04.393   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 12:41:04.393   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-12 12:41:04.394   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 12:41:04.394   872  1312 E native  : do suspend true
,09-12 12:41:04.405   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 12:41:04.405   872  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 12:41:04.407   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:41:04.433   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:41:04.440  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:41:04.440  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:04.440  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:04.440  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:04.440  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:04.440  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:41:04.440  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:04.440  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:04.440  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:41:04.441  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:04.441  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:41:04.443   872  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 12:41:04.443  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:04.443  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:04.443  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:04.443  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:04.443  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:04.443  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:41:04.443  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:04.443  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:04.443  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:41:04.443  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:41:04.443  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:41:04.443   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-12 12:41:04.444  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:04.444  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:04.444  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:04.444  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:04.444  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:04.444  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:41:04.444  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:04.444  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:04.444  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:41:04.444  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:04.444  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:41:04.444  1863  2298 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 12:41:04.450   872   881 I art     : Background partial concurrent mark sweep GC freed 58129(3MB) AllocSpace objects, 8(204KB) LOS objects, 33% free, 29MB/44MB, paused 1.049ms total 102.862ms
,09-12 12:41:04.474   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:41:04.475   872  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 12:41:04.475   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:41:04.477   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 12:41:04.482  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:04.483  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:04.484  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:04.494  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 12:41:04.501  1713  1713 D SystemUpdateService: onCreate
,09-12 12:41:04.503  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 12:41:04.514  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 12:41:04.516  1713  2521 I iu.UploadsManager: num queued entries: 0
,09-12 12:41:04.521  1713  4112 I SystemUpdateService: active receiver: enabled
,09-12 12:41:04.523  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 12:41:04.524  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 12:41:04.526  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:41:04.529  1713  2521 I iu.UploadsManager: num updated entries: 0
,09-12 12:41:04.531   372   871 E Netd    : netlink response contains error (No such file or directory)
09-12 12:41:04.531  3944  3944 D SprintDMHelper: simOperator: 
09-12 12:41:04.531  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-12 12:41:04.533   872  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 12:41:04.542  1713  4112 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 12:41:04.545  3083  4115 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 12:41:04.550  1713  2521 I iu.SyncManager: NEXT; no task
,09-12 12:41:04.551  1713  4112 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 12:41:04.551  1713  4112 I SystemUpdateService: now status is 0 (complete)
09-12 12:41:04.551  1713  4112 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 12:41:04.551  1713  4112 I SystemUpdateService: file has been verified
,09-12 12:41:04.552  1713  4112 I SystemUpdateService: OTA package size = 12249756
,09-12 12:41:04.566  1713  4112 I SystemUpdateService: showing system update notification
,09-12 12:41:04.576  1713  1713 D SystemUpdateService: onDestroy
,09-12 12:41:05.287  1713  1723 W art     : Suspending all threads took: 6.961ms
,09-12 12:41:09.033  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:41:09.043  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:41:09.046  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:41:09.090  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:41:09.090  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:41:09.090  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:41:09.091  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:41:09.125  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:41:09.126  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.,
09-12 12:41:09.127  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 12:41:09.301   872   889 I ActivityManager: Start proc 4120:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 12:41:09.434  4120  4120 D AdapterServiceConfig: Adding HeadsetService
09-12 12:41:09.435  4120  4120 D AdapterServiceConfig: Adding A2dpService
09-12 12:41:09.435  4120  4120 D AdapterServiceConfig: Adding HidService
09-12 12:41:09.435  4120  4120 D AdapterServiceConfig: Adding HealthService
09-12 12:41:09.435  4120  4120 D AdapterServiceConfig: Adding PanService
09-12 12:41:09.436  4120  4120 D AdapterServiceConfig: Adding GattService
09-12 12:41:09.436  4120  4120 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 12:41:09.456  4120  4120 D BluetoothAdapterState: make() - Creating AdapterState
09-12 12:41:09.456   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a728e99:true
,09-12 12:41:09.461  4120  4120 I bt_bluedroid: init
,09-12 12:41:09.462  4120  4132 I BluetoothAdapterState: Entering OffState
,09-12 12:41:09.467  4120  4133 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 12:41:09.468  4120  4133 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 12:41:09.468  4120  4133 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 12:41:09.469  4120  4133 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 12:41:09.470  4120  4120 I bt_bluedroid: get_profile_interface socket
09-12 12:41:09.473  4120  4120 I bt_bluedroid: get_profile_interface sdp
,09-12 12:41:09.477  4120  4131 I bt_bluedroid: config_hci_snoop_log
,09-12 12:41:09.477  4120  4136 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 12:41:09.480  4120  4136 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 12:41:09.483   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 12:41:09.493  4120  4132 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 12:41:09.494  4120  4132 D BluetoothAdapterProperties: Setting state to 14
09-12 12:41:09.494  4120  4132 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 12:41:09.498  4120  4132 D BluetoothBondStateMachine: make
,09-12 12:41:09.502  4120  4137 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 12:41:09.508  4120  4132 I BluetoothAdapterState: Entering PendingCommandState
,09-12 12:41:09.510  4120  4120 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 12:41:09.515  4120  4120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:09.516  4120  4120 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 12:41:09.517  4120  4120 D BtGatt.GattService: Received start request. Starting profile...
,09-12 12:41:09.517  4120  4120 D BtGatt.GattService: start()
,09-12 12:41:09.517  4120  4120 I bt_bluedroid: get_profile_interface gatt
09-12 12:41:09.518  4120  4120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:09.519  4120  4120 D BtGatt.AdvertiseManager: advertise manager created
,09-12 12:41:09.529  4120  4120 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:09.529  4120  4120 V BluetoothAdapterState: isTurningOn()=false
09-12 12:41:09.529  4120  4120 V BluetoothAdapterState: isBleTurningOn()=true
,09-12 12:41:09.529  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:09.530  4120  4132 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 12:41:09.531  4120  4132 I bt_bluedroid: enable
09-12 12:41:09.531  4120  4133 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 12:41:09.532  4120  4133 I bt_hci  : start_up
,09-12 12:41:09.540  4120  4133 I bt_vendor: alloc value 0xb3a48189
,09-12 12:41:09.541  4120  4133 I bt_vendor: init
09-12 12:41:09.541  4120  4133 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-12 12:41:09.541  4120  4133 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 12:41:09.649  4120  4133 D bt_hci  : start_up starting async portion
,09-12 12:41:09.650  4120  4140 I bt_hci  : event_finish_startup
,09-12 12:41:09.650  4120  4140 I bt_hci_h4: hal_open
09-12 12:41:09.650  4120  4140 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 12:41:09.658  4120  4140 I bt_userial_vendor: device fd = 51 open
,09-12 12:41:09.691  4120  4140 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 12:41:09.722  4120  4140 D bt_hwcfg: Chipset BCM4354A2
,09-12 12:41:09.723  4120  4140 D bt_hwcfg: Target name = [BCM4354A2]
09-12 12:41:09.724  4120  4140 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 12:41:09.930   872  1314 D ConnectivityService: handlePromptUnvalidated 101
,09-12 12:41:10.377  4120  4140 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 12:41:10.378  4120  4140 D bt_hwcfg: Settlement delay -- 100 ms
09-12 12:41:10.379  4120  4140 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 12:41:10.495  4120  4140 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 12:41:10.497  4120  4140 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 12:41:10.527  4120  4140 I bt_hwcfg: vendor lib fwcfg completed
,09-12 12:41:10.527  4120  4140 I bt_vendor: firmware callback
,09-12 12:41:10.527  4120  4140 I bt_hci  : firmware_config_callback
,09-12 12:41:10.538  4120  4142 I bt_btu  : btu_task pending for preload complete event
,09-12 12:41:10.539  4120  4142 I bt_btu_task: Bluetooth chip preload is complete
,09-12 12:41:10.539  4120  4142 I bt_btu  : btu_task received preload complete event
,09-12 12:41:10.549  4120  4142 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 12:41:10.549  4120  4142 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 12:41:10.549  4120  4142 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 12:41:10.550  4120  4142 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 12:41:10.550  4120  4142 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 12:41:10.550  4120  4142 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 12:41:10.550  4120  4142 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 12:41:10.552  4120  4142 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 12:41:10.553  4120  4142 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 12:41:10.554  4120  4142 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 12:41:10.554  4120  4142 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 12:41:10.555  4120  4142 I         : BTE_InitTraceLevels -- TRC_GATT
,09-12 12:41:10.555  4120  4142 I         : BTE_InitTraceLevels -- TRC_SMP
,09-12 12:41:10.556  4120  4142 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 12:41:10.557  4120  4142 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 12:41:10.688  4120  4142 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c5d9d
,09-12 12:41:10.689  4120  4142 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c5d9d 
,09-12 12:41:10.699  4120  4136 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 12:41:10.702  4120  4136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 12:41:10.703  4120  4136 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 12:41:10.706  4120  4136 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 12:41:10.713  4120  4136 D BluetoothAdapterProperties: Scan Mode:20
,09-12 12:41:10.714  4120  4136 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 12:41:10.715  4120  4136 D bt_hci  : do_postload posting postload work item
,09-12 12:41:10.715  4120  4140 I bt_hci  : event_postload
,09-12 12:41:10.716  4120  4140 I bt_vendor: sco_config_cb
,09-12 12:41:10.716  4120  4140 I bt_hci  : sco_config_callback postload finished.
,09-12 12:41:10.717  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:10.720  4120  4136 D bt_bte_conf: Device ID record 1 : primary
,09-12 12:41:10.720  4120  4136 D bt_bte_conf:   vendorId            = 000f
09-12 12:41:10.721  4120  4136 D bt_bte_conf:   vendorIdSource      = 0001
09-12 12:41:10.721  4120  4136 D bt_bte_conf:   product             = 1200
09-12 12:41:10.721  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:10.721  4120  4136 D bt_bte_conf:   version             = 1436
09-12 12:41:10.722  4120  4136 D bt_bte_conf:   clientExecutableURL = 
09-12 12:41:10.722  4120  4136 D bt_bte_conf:   serviceDescription  = 
,09-12 12:41:10.722  4120  4136 D bt_bte_conf:   documentationURL    = 
,09-12 12:41:10.722  4120  4136 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-12 12:41:10.723  4120  4133 D bt_stack_manager: event_start_up_stack finished
09-12 12:41:10.726  4120  4140 I bt_vendor: low_power_mode_cb
,09-12 12:41:10.725  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:10.726  4120  4132 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 12:41:10.726  4120  4132 D BluetoothAdapterProperties: Setting state to 15
,09-12 12:41:10.726  4120  4132 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 12:41:10.726  4120  4132 I BluetoothAdapterState: Entering BleOnState
,09-12 12:41:10.731  4120  4132 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 12:41:10.731  4120  4132 D BluetoothAdapterProperties: Setting state to 11
,09-12 12:41:10.731  4120  4132 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 12:41:10.737  4120  4120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:10.738  4120  4120 D HeadsetService: Received start request. Starting profile...
,09-12 12:41:10.742  4120  4120 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 12:41:10.743  4120  4120 D HeadsetStateMachine: make
,09-12 12:41:10.743  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:10.745  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:10.747  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:10.754  4120  4120 D HeadsetStateMachine: max_hf_connections = 1
,09-12 12:41:10.754  4120  4120 I bt_bluedroid: get_profile_interface handsfree
09-12 12:41:10.754  4120  4136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 12:41:10.755  4120  4136 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 12:41:10.757  4120  4132 I BluetoothAdapterState: Entering PendingCommandState
,09-12 12:41:10.759  4120  4120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:10.759  4120  4120 D A2dpService: Received start request. Starting profile...
09-12 12:41:10.760  4120  4120 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 12:41:10.760  4120  4120 I bt_bluedroid: get_profile_interface avrcp
,09-12 12:41:10.766  4120  4120 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 12:41:10.766  4120  4120 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 12:41:10.766  4120  4120 D A2dpStateMachine: make
,09-12 12:41:10.767  4120  4120 I bt_bluedroid: get_profile_interface a2dp
,09-12 12:41:10.768  4120  4136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 12:41:10.770  4120  4120 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 12:41:10.771  4120  4120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:10.772  4120  4151 D A2dpStateMachine: Enter Disconnected: -2
09-12 12:41:10.772  4120  4120 D HidService: Received start request. Starting profile...
09-12 12:41:10.772  4120  4120 I bt_bluedroid: get_profile_interface hidhost
09-12 12:41:10.772  4120  4120 D HidService: setHidService(): set to: null
09-12 12:41:10.772  4120  4136 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a73e5
09-12 12:41:10.773  4120  4136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 12:41:10.773  3890  3890 D BluetoothInputDevice: Proxy object connected
09-12 12:41:10.773  4120  4120 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 12:41:10.774  4120  4120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
09-12 12:41:10.774  3890  3890 D HidProfile: Bluetooth service connected
,09-12 12:41:10.776  4120  4120 D HealthService: Received start request. Starting profile...
,09-12 12:41:10.777  4120  4120 I bt_bluedroid: get_profile_interface health
,09-12 12:41:10.779  4120  4120 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 12:41:10.779  4120  4120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:10.780  4120  4120 D PanService: Received start request. Starting profile...
09-12 12:41:10.781  4120  4120 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 12:41:10.781  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 12:41:10.781  4120  4120 I bt_bluedroid: get_profile_interface pan
09-12 12:41:10.781  4120  4136 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 12:41:10.782  3890  3890 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 12:41:10.782  3890  3890 D PanProfile: Bluetooth service connected
,09-12 12:41:10.787  4120  4120 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:10.788  4120  4120 D BluetoothMapService: Received start request. Starting profile...
,09-12 12:41:10.788  4120  4120 D BluetoothMapService: start()
09-12 12:41:10.788  3890  3890 D BluetoothMap: Proxy object connected
09-12 12:41:10.789  3890  3890 D MapProfile: Bluetooth service connected
,09-12 12:41:10.789  3890  3890 D BluetoothMap: getConnectedDevices()
09-12 12:41:10.790  3890  3890 D BluetoothMap: Bluetooth is Not enabled
09-12 12:41:10.790  4120  4120 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 12:41:10.791  4120  4120 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 12:41:10.791  4120  4120 D BluetoothMapAppObserver: createReceiver()
,09-12 12:41:10.792  4120  4120 D BluetoothMapAppObserver: initObservers()
09-12 12:41:10.792  4120  4120 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 12:41:10.797  4120  4120 V BluetoothAdapterState: isTurningOff()=false
,09-12 12:41:10.797  4120  4120 V BluetoothAdapterState: isTurningOn()=true
09-12 12:41:10.797  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:10.797  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:41:10.799  4120  4120 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:10.799  4120  4120 V BluetoothAdapterState: isTurningOn()=true
09-12 12:41:10.799  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:41:10.799  4120  4148 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 12:41:10.799  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:10.799  4120  4120 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:10.799  4120  4120 V BluetoothAdapterState: isTurningOn()=true
09-12 12:41:10.799  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:10.799  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:41:10.799  4120  4120 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:10.800  4120  4120 V BluetoothAdapterState: isTurningOn()=true
09-12 12:41:10.800  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:10.800  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:10.800  4120  4120 V BluetoothAdapterState: isTurningOff()=false
,09-12 12:41:10.800  4120  4120 V BluetoothAdapterState: isTurningOn()=true
09-12 12:41:10.800  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:10.800  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:10.801  4120  4120 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:10.801  4120  4120 V BluetoothAdapterState: isTurningOn()=true
09-12 12:41:10.801  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:41:10.801  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:41:10.801  4120  4132 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 12:41:10.801  4120  4132 D BluetoothAdapterProperties: ScanMode =  20
09-12 12:41:10.801  4120  4132 D BluetoothAdapterProperties: State =  11
09-12 12:41:10.802  4120  4132 D BluetoothAdapterProperties: Setting state to 12
09-12 12:41:10.802  4120  4132 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 12:41:10.802  4120  4132 I BluetoothAdapterState: Entering OnState
09-12 12:41:10.804  4120  4136 D BluetoothAdapterProperties: Scan Mode:21
09-12 12:41:10.804  4120  4136 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 12:41:10.804  1363  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 12:41:10.806  1363  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:41:10.806  1363  1363 D BluetoothInputDevice: Proxy object connected
09-12 12:41:10.806  1363  1363 D HidProfile: Bluetooth service connected
09-12 12:41:10.806  1363  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 12:41:10.807  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:10.807  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:10.807  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:10.807  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:10.807  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:10.807  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:10.807  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:10.807  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:41:10.808   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:41:10.808   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:41:10.808  1363  2087 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 12:41:10.809  1363  1363 D BluetoothA2dp: Proxy object connected
,09-12 12:41:10.809  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:41:10.810  3890  3901 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 12:41:10.811  3890  3900 D BluetoothMap: onBluetoothStateChange: up=true
09-12 12:41:10.811  1986  2003 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:41:10.812  3890  3901 D BluetoothPan: onBluetoothStateChange on: true
,09-12 12:41:10.812  3890  3900 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 12:41:10.812  1363  1380 D BluetoothMap: onBluetoothStateChange: up=true
09-12 12:41:10.813  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:10.813  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:10.813  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:10.813  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:10.813  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:10.813  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:10.813  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:10.813  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:41:10.814  1363  1363 D BluetoothMap: Proxy object connected
09-12 12:41:10.814  1363  1363 D MapProfile: Bluetooth service connected
,09-12 12:41:10.814  1363  1363 D BluetoothMap: getConnectedDevices()
09-12 12:41:10.814  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:41:10.814  1363  1379 D BluetoothPan: onBluetoothStateChange on: true
,09-12 12:41:10.816  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 12:41:10.816  1363  1363 D PanProfile: Bluetooth service connected
09-12 12:41:10.816   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:41:10.816   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 12:41:10.817   872   872 D BluetoothA2dp: Proxy object connected
,09-12 12:41:10.818  4120  4120 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 12:41:10.818  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:10.818  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:10.818  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:10.818  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:10.818  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:10.818  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:10.818  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:10.818  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:41:10.819  4120  4120 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 12:41:10.820  4120  4120 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 12:41:10.820  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:41:10.820   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 12:41:10.821  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:10.822  4120  4120 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 12:41:10.822  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:10.823  4120  4120 D ObexServerSockets: Succeed to create listening sockets 
,09-12 12:41:10.823  4120  4120 D ObexServerSockets0: startAccept()
09-12 12:41:10.823  4120  4120 D ObexServerSockets0: prepareForNewConnect()
09-12 12:41:10.823  3890  3890 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 12:41:10.824  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:10.825  4120  4120 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 12:41:10.825  4120  4120 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 12:41:10.826  4120  4158 D ObexServerSockets0: Accepting socket connection...
09-12 12:41:10.826  4120  4120 D BluetoothMapService: onReceive
09-12 12:41:10.826  4120  4120 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 12:41:10.826  4120  4120 D BluetoothMapService: STATE_ON
09-12 12:41:10.826  4120  4159 D ObexServerSockets0: Accepting socket connection...
,09-12 12:41:10.829  3890  3890 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 12:41:10.834  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 12:41:10.836  3890  3890 D BluetoothA2dp: Proxy object connected
,09-12 12:41:10.841  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 12:41:10.847  1363  1363 D BluetoothPbap: Proxy object connected
09-12 12:41:10.847  1363  1363 D PbapServerProfile: Bluetooth service connected
,09-12 12:41:10.849  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,09-12 12:41:10.850  3890  3890 D BluetoothPbap: Proxy object connected
,09-12 12:41:10.851  3890  3890 D PbapServerProfile: Bluetooth service connected
,09-12 12:41:10.855  4120  4120 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 12:41:10.855  4120  4120 D ObexServerSockets0: prepareForNewConnect()
,09-12 12:41:10.858  4120  4163 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:41:10.874  4120  4167 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:41:10.875  4120  4167 I BtOppRfcommListener: Accept thread started.
,09-12 12:41:10.907   872   872 D BluetoothHeadset: Proxy object connected
09-12 12:41:10.907   872   872 D BluetoothHeadset: Proxy object connected
,09-12 12:41:10.907   872   872 D BluetoothHeadset: Proxy object connected
09-12 12:41:10.908  1363  2087 D BluetoothHeadset: Proxy object connected
,09-12 12:41:10.908   872   889 D BluetoothHeadset: Proxy object connected
09-12 12:41:10.908   872   889 D BluetoothHeadset: Proxy object connected
09-12 12:41:10.908  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-12 12:41:10.910  1986  2068 D BluetoothHeadset: Proxy object connected
,09-12 12:41:10.912  1986  2005 D BluetoothHeadset: Proxy object connected
,09-12 12:41:10.917   872   889 D BluetoothHeadset: Proxy object connected
,09-12 12:41:10.931  3890  3901 D BluetoothHeadset: Proxy object connected
,09-12 12:41:10.934  3890  3890 D HeadsetProfile: Bluetooth service connected
,09-12 12:41:14.256  4120  4132 D BluetoothAdapterState: Current state: ON, message: 23
09-12 12:41:14.257  4120  4132 D BluetoothAdapterProperties: Setting state to 13
,09-12 12:41:14.257  4120  4132 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 12:41:14.258  4120  4132 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 12:41:14.260  4120  4132 I BluetoothAdapterState: Entering PendingCommandState,
,09-12 12:41:14.262  4120  4136 D BluetoothAdapterProperties: Scan Mode:20
,09-12 12:41:14.263  4120  4132 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 12:41:14.273  4120  4120 D HeadsetService: Received stop request...Stopping profile...
,09-12 12:41:14.280  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:41:14.280  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:14.280  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:14.280  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:14.280  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:14.280  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:41:14.280  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:14.280  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:14.280  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:41:14.282  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:41:14.282  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:41:14.282   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 12:41:14.283  4120  4120 V BluetoothAdapterState: isTurningOff()=true
09-12 12:41:14.283  4120  4120 V BluetoothAdapterState: isTurningOn()=false
09-12 12:41:14.283  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:41:14.283  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:14.283  3890  3900 D BluetoothHeadset: Proxy object disconnected
09-12 12:41:14.287  4120  4120 D A2dpService: Received stop request...Stopping profile...
09-12 12:41:14.288  4120  4151 D A2dpStateMachine: Exit Disconnected: -1
09-12 12:41:14.288   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 12:41:14.289   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 12:41:14.289  1363  1363 D BluetoothA2dp: Proxy object disconnected
09-12 12:41:14.289  1363  1380 D BluetoothHeadset: Proxy object disconnected
09-12 12:41:14.290  1363  1363 D HeadsetProfile: Bluetooth service disconnected
09-12 12:41:14.290  1986  2003 D BluetoothHeadset: Proxy object disconnected
,09-12 12:41:14.291   872   872 D BluetoothA2dp: Proxy object disconnected
,09-12 12:41:14.290  3890  3890 D HeadsetProfile: Bluetooth service disconnected
09-12 12:41:14.291  3890  3890 D BluetoothA2dp: Proxy object disconnected
09-12 12:41:14.291  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:14.291  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:14.291  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:14.291  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:14.291  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:14.291  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:41:14.291  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:14.291  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:14.291  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:41:14.292  4120  4120 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 12:41:14.292  4120  4120 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 12:41:14.292  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:14.292  4120  4120 V BluetoothAdapterState: isTurningOff()=true
,09-12 12:41:14.292  4120  4120 V BluetoothAdapterState: isTurningOn()=false
09-12 12:41:14.292  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:41:14.292  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:41:14.292  4120  4136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-12 12:41:14.293  4120  4142 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 12:41:14.293  4120  4142 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 12:41:14.292  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:41:14.293  4120  4142 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:41:14.293  4120  4136 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 12:41:14.293  4120  4120 D HidService: Received stop request...Stopping profile...
,09-12 12:41:14.293  4120  4120 D HidService: Stopping Bluetooth HidService
09-12 12:41:14.294  3890  3890 D BluetoothInputDevice: Proxy object disconnected
,09-12 12:41:14.294  3890  3890 D HidProfile: Bluetooth service disconnected
,09-12 12:41:14.294  1363  1363 D BluetoothInputDevice: Proxy object disconnected
,09-12 12:41:14.294  1363  1363 D HidProfile: Bluetooth service disconnected
,09-12 12:41:14.295  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:14.295  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:14.295  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:14.295  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:14.295  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:14.295  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:41:14.295  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:14.295  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:14.295  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:41:14.296  3791  3791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:41:14.296  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:41:14.297  4120  4136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-12 12:41:14.297  4120  4142 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:41:14.297  4120  4142 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:41:14.297  4120  4142 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 12:41:14.297  4120  4142 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 12:41:14.297  4120  4142 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 12:41:14.297  4120  4142 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 12:41:14.298  4120  4120 D HealthService: Received stop request...Stopping profile...
09-12 12:41:14.299  4120  4120 D PanService: Received stop request...Stopping profile...
09-12 12:41:14.300  4120  4120 V BluetoothAdapterState: isTurningOff()=true
09-12 12:41:14.300  3890  3890 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 12:41:14.300  3890  3890 D PanProfile: Bluetooth service disconnected
09-12 12:41:14.300  4120  4120 V BluetoothAdapterState: isTurningOn()=false
09-12 12:41:14.300  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:14.300  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:14.301  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 12:41:14.301  1363  1363 D PanProfile: Bluetooth service disconnected
09-12 12:41:14.301  4120  4120 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 12:41:14.301  4120  4120 D BluetoothMapService: stop()
09-12 12:41:14.302  4120  4120 D BluetoothMapAppObserver: deinitObservers()
,09-12 12:41:14.302  4120  4120 D BluetoothMapAppObserver: removeReceiver()
09-12 12:41:14.303  1363  1363 D BluetoothMap: Proxy object disconnected
09-12 12:41:14.303  1363  1363 D MapProfile: Bluetooth service disconnected
09-12 12:41:14.303  3890  3890 D BluetoothMap: Proxy object disconnected
,09-12 12:41:14.303  3890  3890 D MapProfile: Bluetooth service disconnected
09-12 12:41:14.303  4120  4120 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 12:41:14.303  4120  4120 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 12:41:14.303  4120  4136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 12:41:14.304  4120  4120 V BluetoothAdapterState: isTurningOff()=true
,09-12 12:41:14.304  4120  4120 V BluetoothAdapterState: isTurningOn()=false
09-12 12:41:14.304  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:14.304  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:14.304  4120  4120 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 12:41:14.304  4120  4136 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-12 12:41:14.304  4120  4120 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 12:41:14.305  4120  4120 V BluetoothAdapterState: isTurningOff()=true
09-12 12:41:14.305  4120  4120 V BluetoothAdapterState: isTurningOn()=false
09-12 12:41:14.305  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:14.305  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:14.305  4120  4120 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-12 12:41:14.305  4120  4120 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 12:41:14.306  4120  4120 D BluetoothMapService: MAP Service closeService in
,09-12 12:41:14.306  4120  4120 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 12:41:14.306  4120  4120 D ObexServerSockets0: shutdown(block = true)
09-12 12:41:14.307  4120  4158 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 12:41:14.307  4120  4120 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 12:41:14.308  4120  4159 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 12:41:14.308  4120  4144 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 12:41:14.308  4120  4120 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 12:41:14.309  4120  4120 V BluetoothAdapterState: isTurningOff()=true
09-12 12:41:14.309  4120  4120 V BluetoothAdapterState: isTurningOn()=false
09-12 12:41:14.309  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:41:14.309  4120  4120 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:14.309  4120  4132 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 12:41:14.309  4120  4132 D BluetoothAdapterProperties: Setting state to 15
09-12 12:41:14.309  4120  4132 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 12:41:14.310  4120  4120 D BluetoothMapService: cleanup()
09-12 12:41:14.310  4120  4120 D BluetoothMapService: MAP Service closeService in
09-12 12:41:14.311  4120  4120 I BtOppRfcommListener: stopping Accept Thread
09-12 12:41:14.311  4120  4167 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 12:41:14.312  1363  2087 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 12:41:14.311  4120  4132 I BluetoothAdapterState: Entering BleOnState
09-12 12:41:14.314  4120  4167 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 12:41:14.314  1363  1379 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:41:14.315  1363  1380 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 12:41:14.315   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:41:14.315   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:41:14.316  1363  2087 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 12:41:14.316  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 12:41:14.316  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:14.317  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:14.318  3890  3901 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 12:41:14.319  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:14.319  3890  3900 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:41:14.320  3890  4170 D BluetoothMap: onBluetoothStateChange: up=false
09-12 12:41:14.321  1986  2068 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:41:14.321  3890  3901 D BluetoothPan: onBluetoothStateChange on: false
09-12 12:41:14.322  3890  3900 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 12:41:14.322  1363  1379 D BluetoothMap: onBluetoothStateChange: up=false
09-12 12:41:14.323  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 12:41:14.323  1363  1380 D BluetoothPan: onBluetoothStateChange on: false
,09-12 12:41:14.324  3890  4170 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 12:41:14.326   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:41:14.326   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 12:41:14.328  4120  4132 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 12:41:14.328  4120  4132 D BluetoothAdapterProperties: Setting state to 16
09-12 12:41:14.328  4120  4132 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 12:41:14.330  4120  4132 D BluetoothAdapterProperties: onBleDisable,
09-12 12:41:14.331  4120  4133 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 12:41:14.332  4120  4142 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 12:41:14.332  4120  4142 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:41:14.332  4120  4136 D BluetoothAdapterProperties: Scan Mode:20
09-12 12:41:14.332  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:14.332  4120  4132 I BluetoothAdapterState: Entering PendingCommandState
09-12 12:41:14.334  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:14.336  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:14.337  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:14.338  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:14.339  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:14.343  3890  3890 D DockEventReceiver: finishStartingService: stopping service
09-12 12:41:14.345  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 12:41:14.349  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 12:41:14.353  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,09-12 12:41:14.533  4120  4136 I bt_hci  : shut_down
,09-12 12:41:14.534  4120  4140 D bt_hwcfg: hw_epilog_process
,09-12 12:41:14.535  4120  4140 I bt_vendor: low_power_mode_cb
,09-12 12:41:14.557  4120  4140 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 12:41:14.557  4120  4140 I bt_vendor: epilog_cb
09-12 12:41:14.558  4120  4140 I bt_hci  : epilog_finished_callback
,09-12 12:41:14.562  4120  4136 I bt_hci_h4: hal_close
,09-12 12:41:14.562  4120  4136 I bt_userial_vendor: device fd = 51 close
,09-12 12:41:14.686  4120  4133 D bt_stack_manager: event_shut_down_stack finished.
,09-12 12:41:14.688  4120  4132 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 12:41:14.693  4120  4132 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 12:41:14.694  4120  4120 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 12:41:14.695  4120  4120 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 12:41:14.695  4120  4120 D BtGatt.GattService: stop()
09-12 12:41:14.696  4120  4120 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 12:41:14.702  4120  4120 V BluetoothAdapterState: isTurningOff()=false
,09-12 12:41:14.702  4120  4120 V BluetoothAdapterState: isTurningOn()=false
09-12 12:41:14.702  4120  4120 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:14.702  4120  4120 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 12:41:14.704  4120  4132 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 12:41:14.705  4120  4132 D BluetoothAdapterProperties: Setting state to 10
,09-12 12:41:14.706  4120  4132 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-12 12:41:14.732  4120  4132 I BluetoothAdapterState: Entering OffState
,09-12 12:41:14.734   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 12:41:14.745  4120  4120 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 12:41:14.746  4120  4120 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 12:41:14.746  4120  4120 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 12:41:14.749  4120  4133 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 12:41:14.757  4120  4133 D bt_stack_manager: event_clean_up_stack finished.
,09-12 12:41:14.763  4120  4120 I art     : System.exit called, status: 0
,09-12 12:41:14.763  4120  4120 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 12:41:14.837   872  1936 I ActivityManager: Process com.android.bluetooth (pid 4120) has died
,09-12 12:41:19.256  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:41:19.256  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:41:19.261  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:41:19.261  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc23d9f removed from the list
,09-12 12:41:19.262  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:41:19.262  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:41:19.262  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:41:19.267  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 12:41:19.268  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3702b5 added. We now have 4 listener(s)
,09-12 12:41:19.268  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:41:19.270  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:41:19.270  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3702b5 removed from the list
09-12 12:41:19.270  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:41:19.270  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:19.271  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:41:19.273  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:41:19.274  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d3d7d4a added. We now have 4 listener(s)
09-12 12:41:19.275  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:41:24.287  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:24.343   872   889 I ActivityManager: Start proc 4180:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 12:41:24.478  4180  4180 D AdapterServiceConfig: Adding HeadsetService
,09-12 12:41:24.479  4180  4180 D AdapterServiceConfig: Adding A2dpService
09-12 12:41:24.479  4180  4180 D AdapterServiceConfig: Adding HidService
09-12 12:41:24.479  4180  4180 D AdapterServiceConfig: Adding HealthService
09-12 12:41:24.479  4180  4180 D AdapterServiceConfig: Adding PanService
,09-12 12:41:24.479  4180  4180 D AdapterServiceConfig: Adding GattService
09-12 12:41:24.480  4180  4180 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 12:41:24.496   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@418e8d2:true
09-12 12:41:24.497  4180  4180 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 12:41:24.502  4180  4180 I bt_bluedroid: init
,09-12 12:41:24.503  4180  4192 I BluetoothAdapterState: Entering OffState
,09-12 12:41:24.508  4180  4193 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 12:41:24.508  4180  4193 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 12:41:24.508  4180  4193 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 12:41:24.509  4180  4193 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 12:41:24.511  4180  4180 I bt_bluedroid: get_profile_interface socket
,09-12 12:41:24.515  4180  4180 I bt_bluedroid: get_profile_interface sdp
,09-12 12:41:24.519  4180  4196 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 12:41:24.521  4180  4196 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 12:41:24.523  4180  4190 I bt_bluedroid: config_hci_snoop_log
,09-12 12:41:24.527   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 12:41:24.538  4180  4192 D BluetoothAdapterState: Current state: OFF, message: 0
09-12 12:41:24.539  4180  4192 D BluetoothAdapterProperties: Setting state to 14
,09-12 12:41:24.539  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 12:41:24.544  4180  4192 D BluetoothBondStateMachine: make
,09-12 12:41:24.549  4180  4197 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 12:41:24.559  4180  4192 I BluetoothAdapterState: Entering PendingCommandState
,09-12 12:41:24.562  4180  4180 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 12:41:24.572  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:24.575  4180  4180 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 12:41:24.577  4180  4180 D BtGatt.GattService: Received start request. Starting profile...
09-12 12:41:24.577  4180  4180 D BtGatt.GattService: start()
,09-12 12:41:24.577  4180  4180 I bt_bluedroid: get_profile_interface gatt
,09-12 12:41:24.579  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
09-12 12:41:24.580  4180  4180 D BtGatt.AdvertiseManager: advertise manager created
,09-12 12:41:24.594  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,09-12 12:41:24.594  4180  4180 V BluetoothAdapterState: isTurningOn()=false
09-12 12:41:24.595  4180  4180 V BluetoothAdapterState: isBleTurningOn()=true
09-12 12:41:24.595  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:24.596  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-12 12:41:24.596  4180  4192 I bt_bluedroid: enable
09-12 12:41:24.597  4180  4193 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 12:41:24.598  4180  4193 I bt_hci  : start_up
,09-12 12:41:24.618  4180  4193 I bt_vendor: alloc value 0xb3a48189
,09-12 12:41:24.619  4180  4193 I bt_vendor: init
09-12 12:41:24.619  4180  4193 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 12:41:24.619  4180  4193 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 12:41:24.728  4180  4193 D bt_hci  : start_up starting async portion
,09-12 12:41:24.729  4180  4200 I bt_hci  : event_finish_startup
09-12 12:41:24.729  4180  4200 I bt_hci_h4: hal_open
,09-12 12:41:24.729  4180  4200 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 12:41:24.742  4180  4200 I bt_userial_vendor: device fd = 51 open
,09-12 12:41:24.772  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 12:41:24.803  4180  4200 D bt_hwcfg: Chipset BCM4354A2
09-12 12:41:24.803  4180  4200 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 12:41:24.804  4180  4200 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 12:41:25.663  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 12:41:25.664  4180  4200 D bt_hwcfg: Settlement delay -- 100 ms
09-12 12:41:25.664  4180  4200 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 12:41:25.781  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 12:41:25.782  4180  4200 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 12:41:25.812  4180  4200 I bt_hwcfg: vendor lib fwcfg completed
,09-12 12:41:25.813  4180  4200 I bt_vendor: firmware callback
09-12 12:41:25.813  4180  4200 I bt_hci  : firmware_config_callback
,09-12 12:41:25.824  4180  4202 I bt_btu  : btu_task pending for preload complete event
,09-12 12:41:25.824  4180  4202 I bt_btu_task: Bluetooth chip preload is complete
,09-12 12:41:25.825  4180  4202 I bt_btu  : btu_task received preload complete event
,09-12 12:41:25.838  4180  4202 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 12:41:25.838  4180  4202 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 12:41:25.838  4180  4202 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 12:41:25.839  4180  4202 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 12:41:25.840  4180  4202 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 12:41:25.840  4180  4202 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 12:41:25.840  4180  4202 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 12:41:25.840  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 12:41:25.841  4180  4202 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 12:41:25.841  4180  4202 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 12:41:25.841  4180  4202 I         : BTE_InitTraceLevels -- TRC_SDP
,09-12 12:41:25.841  4180  4202 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 12:41:25.842  4180  4202 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 12:41:25.842  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 12:41:25.842  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 12:41:25.975  4180  4202 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c5d9d
,09-12 12:41:25.975  4180  4202 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c5d9d 
,09-12 12:41:25.987  4180  4196 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 12:41:25.988  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 12:41:25.989  4180  4196 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 12:41:25.992  4180  4196 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 12:41:25.995  4180  4196 D BluetoothAdapterProperties: Scan Mode:20
,09-12 12:41:25.996  4180  4196 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 12:41:25.997  4180  4196 D bt_hci  : do_postload posting postload work item
09-12 12:41:25.997  4180  4200 I bt_hci  : event_postload
,09-12 12:41:25.997  4180  4200 I bt_vendor: sco_config_cb
09-12 12:41:25.997  4180  4200 I bt_hci  : sco_config_callback postload finished.
09-12 12:41:26.002  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:26.004  4180  4196 D bt_bte_conf: Device ID record 1 : primary
09-12 12:41:26.004  4180  4196 D bt_bte_conf:   vendorId            = 000f
09-12 12:41:26.004  4180  4196 D bt_bte_conf:   vendorIdSource      = 0001
09-12 12:41:26.004  4180  4196 D bt_bte_conf:   product             = 1200
,09-12 12:41:26.005  4180  4196 D bt_bte_conf:   version             = 1436
09-12 12:41:26.005  4180  4200 I bt_vendor: low_power_mode_cb
09-12 12:41:26.005  4180  4196 D bt_bte_conf:   clientExecutableURL = 
,09-12 12:41:26.005  4180  4196 D bt_bte_conf:   serviceDescription  = 
09-12 12:41:26.005  4180  4196 D bt_bte_conf:   documentationURL    = 
,09-12 12:41:26.005  4180  4196 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 12:41:26.006  4180  4193 D bt_stack_manager: event_start_up_stack finished
,09-12 12:41:26.008  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:26.009  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 12:41:26.011  4180  4192 D BluetoothAdapterProperties: Setting state to 15
09-12 12:41:26.011  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 12:41:26.013  4180  4192 I BluetoothAdapterState: Entering BleOnState
,09-12 12:41:26.018  4180  4192 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 12:41:26.018  4180  4192 D BluetoothAdapterProperties: Setting state to 11
09-12 12:41:26.018  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 12:41:26.024  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:26.025  4180  4180 D HeadsetService: Received start request. Starting profile...
,09-12 12:41:26.029  4180  4180 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 12:41:26.030  4180  4180 D HeadsetStateMachine: make
09-12 12:41:26.031  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:26.033  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:26.040  4180  4192 I BluetoothAdapterState: Entering PendingCommandState
,09-12 12:41:26.041  4180  4180 D HeadsetStateMachine: max_hf_connections = 1
,09-12 12:41:26.041  4180  4180 I bt_bluedroid: get_profile_interface handsfree
,09-12 12:41:26.042  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 12:41:26.043  4180  4196 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 12:41:26.046  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:26.047  4180  4180 D A2dpService: Received start request. Starting profile...
,09-12 12:41:26.047  4180  4180 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 12:41:26.048  4180  4180 I bt_bluedroid: get_profile_interface avrcp
,09-12 12:41:26.053  4180  4180 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 12:41:26.054  4180  4180 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-12 12:41:26.054  4180  4180 D A2dpStateMachine: make
09-12 12:41:26.055  4180  4180 I bt_bluedroid: get_profile_interface a2dp
,09-12 12:41:26.056  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 12:41:26.059  4180  4180 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 12:41:26.059  4180  4211 D A2dpStateMachine: Enter Disconnected: -2
,09-12 12:41:26.060  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:26.061  4180  4180 D HidService: Received start request. Starting profile...
,09-12 12:41:26.061  4180  4180 I bt_bluedroid: get_profile_interface hidhost
,09-12 12:41:26.062  4180  4180 D HidService: setHidService(): set to: null
09-12 12:41:26.062  4180  4196 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a73e5
09-12 12:41:26.062  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 12:41:26.063  4180  4180 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 12:41:26.065  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
09-12 12:41:26.066  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 12:41:26.066  4180  4180 D HealthService: Received start request. Starting profile...
,09-12 12:41:26.067  4180  4180 I bt_bluedroid: get_profile_interface health
,09-12 12:41:26.068  4180  4180 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 12:41:26.069  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:26.069  4180  4180 D PanService: Received start request. Starting profile...
,09-12 12:41:26.070  4180  4180 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 12:41:26.070  4180  4180 I bt_bluedroid: get_profile_interface pan
,09-12 12:41:26.070  4180  4196 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 12:41:26.074  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:26.075  4180  4180 D BluetoothMapService: Received start request. Starting profile...
,09-12 12:41:26.075  4180  4180 D BluetoothMapService: start()
,09-12 12:41:26.077  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 12:41:26.078  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 12:41:26.078  4180  4180 D BluetoothMapAppObserver: createReceiver()
,09-12 12:41:26.079  4180  4180 D BluetoothMapAppObserver: initObservers()
,09-12 12:41:26.079  4180  4180 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 12:41:26.086  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,09-12 12:41:26.086  4180  4180 V BluetoothAdapterState: isTurningOn()=true
09-12 12:41:26.086  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:26.086  4180  4207 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 12:41:26.086  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:41:26.088  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:26.088  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,09-12 12:41:26.088  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:26.088  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:26.088  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:26.088  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,09-12 12:41:26.088  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:41:26.088  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:41:26.091  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:26.091  4180  4180 V BluetoothAdapterState: isTurningOn()=true
09-12 12:41:26.091  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:26.092  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:26.092  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:26.092  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,09-12 12:41:26.092  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:26.092  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:26.092  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-12 12:41:26.092  4180  4180 V BluetoothAdapterState: isTurningOn()=true
09-12 12:41:26.092  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:41:26.092  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:41:26.093  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 12:41:26.093  4180  4192 D BluetoothAdapterProperties: ScanMode =  20
,09-12 12:41:26.093  4180  4192 D BluetoothAdapterProperties: State =  11
09-12 12:41:26.093  4180  4192 D BluetoothAdapterProperties: Setting state to 12
09-12 12:41:26.093  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 12:41:26.094  4180  4192 I BluetoothAdapterState: Entering OnState
09-12 12:41:26.094  1363  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 12:41:26.095  4180  4196 D BluetoothAdapterProperties: Scan Mode:21
09-12 12:41:26.095  4180  4196 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 12:41:26.097  1363  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:41:26.098  1363  1363 D BluetoothInputDevice: Proxy object connected
09-12 12:41:26.098  1363  1363 D HidProfile: Bluetooth service connected
09-12 12:41:26.098  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:26.098  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:26.098  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:26.098  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:26.098  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:26.098  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:26.098  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:26.098  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:41:26.099  1363  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 12:41:26.100  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:41:26.102   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 12:41:26.102  1363  1363 D BluetoothA2dp: Proxy object connected
09-12 12:41:26.102   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:41:26.102  1363  1379 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 12:41:26.102  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:26.102  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:26.102  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:26.102  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:26.102  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:26.102  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:26.102  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:26.102  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:41:26.104  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:41:26.104  3890  4170 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 12:41:26.105  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 12:41:26.105  4180  4180 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 12:41:26.106  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 12:41:26.106  3890  3901 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:41:26.107  3890  3900 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 12:41:26.108  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 12:41:26.108  4180  4180 D ObexServerSockets: Succeed to create listening sockets 
09-12 12:41:26.109  4180  4180 D ObexServerSockets0: startAccept()
09-12 12:41:26.109  4180  4180 D ObexServerSockets0: prepareForNewConnect()
,09-12 12:41:26.110  4180  4180 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 12:41:26.110  4180  4180 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-12 12:41:26.110  1986  2005 D BluetoothHeadset: onBluetoothStateChange: up=true,
09-12 12:41:26.111  4180  4217 D ObexServerSockets0: Accepting socket connection...
,09-12 12:41:26.111  4180  4218 D ObexServerSockets0: Accepting socket connection...
,09-12 12:41:26.112  3890  3901 D BluetoothPan: onBluetoothStateChange on: true
,09-12 12:41:26.114  3890  3900 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 12:41:26.116  3890  3890 D BluetoothMap: Proxy object connected
,09-12 12:41:26.116  1363  4171 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 12:41:26.116  3890  3890 D MapProfile: Bluetooth service connected
,09-12 12:41:26.116  3890  3890 D BluetoothMap: getConnectedDevices()
,09-12 12:41:26.117  3890  3890 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 12:41:26.118  3890  3890 D PanProfile: Bluetooth service connected
09-12 12:41:26.118  3890  3890 D BluetoothInputDevice: Proxy object connected
,09-12 12:41:26.118  3890  3890 D HidProfile: Bluetooth service connected
09-12 12:41:26.118  1363  1363 D BluetoothMap: Proxy object connected
09-12 12:41:26.118  1363  1363 D MapProfile: Bluetooth service connected
09-12 12:41:26.118  1363  1363 D BluetoothMap: getConnectedDevices()
09-12 12:41:26.118  1363  2087 D BluetoothPan: onBluetoothStateChange on: true
,09-12 12:41:26.120  3890  3901 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 12:41:26.121  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 12:41:26.121  1363  1363 D PanProfile: Bluetooth service connected
09-12 12:41:26.123   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 12:41:26.123  3890  3890 D BluetoothA2dp: Proxy object connected
09-12 12:41:26.123   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 12:41:26.124   872   872 D BluetoothA2dp: Proxy object connected
,09-12 12:41:26.126  4180  4180 D BluetoothMapService: onReceive
,09-12 12:41:26.126  4180  4180 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 12:41:26.127  4180  4180 D BluetoothMapService: STATE_ON
,09-12 12:41:26.128  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:26.128   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 12:41:26.129  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:26.133  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 12:41:26.141  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 12:41:26.147  4180  4221 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
09-12 12:41:26.148  3890  3890 D DockEventReceiver: finishStartingService: stopping service
09-12 12:41:26.149  3890  3890 D BluetoothPbap: Proxy object connected
09-12 12:41:26.149  3890  3890 D PbapServerProfile: Bluetooth service connected,
,09-12 12:41:26.150  1363  1363 D BluetoothPbap: Proxy object connected
,09-12 12:41:26.151  1363  1363 D PbapServerProfile: Bluetooth service connected
,09-12 12:41:26.152  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 12:41:26.152  4180  4180 D ObexServerSockets0: prepareForNewConnect()
,09-12 12:41:26.166  4180  4227 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:41:26.168  4180  4227 I BtOppRfcommListener: Accept thread started.
,09-12 12:41:26.201   872   872 D BluetoothHeadset: Proxy object connected
09-12 12:41:26.202  3890  3900 D BluetoothHeadset: Proxy object connected
09-12 12:41:26.202   872   889 D BluetoothHeadset: Proxy object connected
09-12 12:41:26.202   872   889 D BluetoothHeadset: Proxy object connected
09-12 12:41:26.202   872   872 D BluetoothHeadset: Proxy object connected
09-12 12:41:26.202   872   872 D BluetoothHeadset: Proxy object connected
09-12 12:41:26.203  1363  1380 D BluetoothHeadset: Proxy object connected
09-12 12:41:26.203  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-12 12:41:26.205  1986  2003 D BluetoothHeadset: Proxy object connected
,09-12 12:41:26.208  3890  4170 D BluetoothHeadset: Proxy object connected
,09-12 12:41:26.212  1986  2068 D BluetoothHeadset: Proxy object connected
,09-12 12:41:26.203  3890  3890 D HeadsetProfile: Bluetooth service connected
,09-12 12:41:26.219  3890  3890 D HeadsetProfile: Bluetooth service connected
,09-12 12:41:26.223   872   889 D BluetoothHeadset: Proxy object connected
,09-12 12:41:29.306  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:29.306  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:29.306  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:29.306  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:41:29.306  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:29.306  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:29.306  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:29.306  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:41:29.313  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:41:29.314  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:41:29.314  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d3d7d4a removed from the list
09-12 12:41:29.315  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:41:29.315  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:29.316  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:41:29.320  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 12:41:29.321  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9714bb added. We now have 4 listener(s)
,09-12 12:41:29.321  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:41:29.327   872  2214 D WifiService: setWifiEnabled: false pid=3791, uid=10000
,09-12 12:41:29.327   872  2214 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:41:33.247  1895  1935 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-12 12:41:33.247  1895  1935 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 12:41:33.285  1495  1495 I ConfigService: onCreate
,09-12 12:41:34.340  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:34.341   872  1936 D WifiService: setWifiEnabled: true pid=3791, uid=10000
09-12 12:41:34.341   872  1936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:41:34.353   872  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-12 12:41:34.371  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:34.371  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:34.371  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:34.371  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:34.371  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:34.371  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:34.371  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:34.371  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:41:34.378  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:41:34.382  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:34.382  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:34.382  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:34.382  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:34.382  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:34.382  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:41:34.382  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:41:34.382  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:41:34.384  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:41:34.399   872  1312 D WifiConfigStore: loaded 0 passpoint configs
,09-12 12:41:34.400   872  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 12:41:34.401   872  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 12:41:34.402   872  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 12:41:34.402   872  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 12:41:34.402   872  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 12:41:34.402   872  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 12:41:34.417   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 12:41:34.417   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:41:34.418   372   871 D CommandListener: Setting iface cfg
09-12 12:41:34.419   872  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-12 12:41:34.419   872  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 12:41:34.471   872  1310 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 12:41:34.473   872  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 12:41:34.474   872  1312 E native  : do suspend true
,09-12 12:41:34.516   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:41:35.685   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:41:35.828   872  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.88 rxSuccessRate=11.00 delta 1000 -> 994
,09-12 12:41:35.829   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-12 12:41:35.829   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:41:35.850   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 12:41:35.922   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 12:41:35.928  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 12:41:36.367  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 12:41:36.418  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 12:41:36.419  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 12:41:36.422   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:41:36.437   872  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 12:41:36.438   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 12:41:36.438   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 12:41:36.460   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:41:36.475   372   871 D CommandListener: Setting iface cfg
,09-12 12:41:36.477   872  1312 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 12:41:36.497   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 12:41:36.511   872  4238 D DhcpClient: Receive thread started
,09-12 12:41:36.609   872  1312 E native  : do suspend false
,09-12 12:41:36.636   872  2083 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 12:41:36.650   872  4238 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-12 12:41:36.652   872  2083 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-12 12:41:36.655   872  2083 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 12:41:36.668   872  4238 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 12:41:36.669   872  2083 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 12:41:36.675   372   871 D CommandListener: Setting iface cfg
,09-12 12:41:36.686   872  2083 D DhcpClient: Scheduling renewal in 86399s
,09-12 12:41:36.686   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 12:41:36.691   872  1312 E native  : do suspend true
,09-12 12:41:36.712   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 12:41:36.713   872  1312 D WifiConfigStore: No blacklist allowed without epno enabled
09-12 12:41:36.714   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 12:41:36.716   872  1314 D ConnectivityService: Adding iface wlan0 to network 102
09-12 12:41:36.721   872  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 12:41:36.764   872  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 12:41:36.764   872  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 12:41:36.765   872  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 12:41:36.766   872  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 12:41:36.767   872  1314 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 12:41:36.783   872  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 12:41:36.790   872  1314 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-12 12:41:36.790   872  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 12:41:36.790   872  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-12 12:41:36.790   872  1314 D ConnectivityService:    accepting network in place of null
09-12 12:41:36.790   872  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 12:41:36.791   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 12:41:36.791   872  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 12:41:36.815   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=213885, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:41:36.821   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:41:36.861   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:41:36.866   872  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-12 12:41:36.867   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:41:36.869   872  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 12:41:36.871   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 12:41:36.886  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:36.886  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:36.886  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:36.886  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:36.886  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:36.886  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:36.886  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:36.886  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:41:36.889  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:41:36.894   872  4236 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-12 12:41:36.897  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:36.897  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:36.897  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:36.897  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:36.897  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:36.897  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:36.897  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:36.897  3791  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:41:36.902  3791  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:41:36.906  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 12:41:36.913  1713  1713 D SystemUpdateService: onCreate
,09-12 12:41:36.917  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 12:41:36.939  1713  4248 I SystemUpdateService: active receiver: enabled
,09-12 12:41:36.951  1713  4248 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-12 12:41:36.951  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 12:41:36.959  1713  2521 I iu.UploadsManager: num queued entries: 0
,09-12 12:41:36.959  1713  2521 I iu.UploadsManager: num updated entries: 0
,09-12 12:41:36.962  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 12:41:36.963  1713  4248 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 12:41:36.964  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 12:41:36.965  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:41:36.982  1713  4248 I SystemUpdateService: now status is 0 (complete)
,09-12 12:41:36.982  1713  4248 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 12:41:36.983   872  4236 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 10:41:36 GMT], X-Android-Received-Millis=[1473676896981], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473676896950]}
09-12 12:41:36.984  1713  4248 I SystemUpdateService: file has been verified
,09-12 12:41:36.984  1713  4248 I SystemUpdateService: OTA package size = 12249756
,09-12 12:41:36.985  3944  3944 D SprintDMHelper: simOperator: 
09-12 12:41:36.985  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-12 12:41:36.986   872  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 12:41:36.987   872  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 12:41:36.987   872  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 12:41:36.992   872  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 12:41:36.995  1713  2521 I iu.SyncManager: NEXT; no task
,09-12 12:41:37.001  1713  4251 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 12:41:37.001  1713  4251 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 12:41:37.011  1713  4251 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 12:41:37.028  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 12:41:37.030  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:41:37.047  1713  4248 I SystemUpdateService: showing system update notification
,09-12 12:41:37.157  1713  1713 D SystemUpdateService: onDestroy
,09-12 12:41:37.182  1495  2016 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 12:41:37.183  1495  2016 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 12:41:37.183  1495  2016 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:41:37.183  1495  2016 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:41:37.189  3042  4247 V KeepSync: Connecting to GoogleApiClient
,09-12 12:41:37.189   872  1403 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:41:37.222  1713  4251 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-12 12:41:37.225  3083  4254 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 12:41:37.251  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 12:41:37.251  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 12:41:37.251  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:41:37.251  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:41:37.269  1713  4259 V BaseAuthAsyncOperation: access token request failed
,09-12 12:41:37.270  3042  4247 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:41:37.311  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 12:41:37.311  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 12:41:37.311  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:41:37.311  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:41:37.324  3042  4247 E KeepSync: IOException
09-12 12:41:37.324  3042  4247 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:41:37.324  3042  4247 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:41:37.324  3042  4247 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:41:37.324  3042  4247 E KeepSync: 	... 10 more
,09-12 12:41:37.324  3042  4247 W KeepSync: Sync result 2
,09-12 12:41:37.334   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 211196, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:41:37.867   872  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 12:41:38.333  1495  1495 I ConfigService: onDestroy
,09-12 12:41:39.366  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:41:39.366  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:39.366  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:39.366  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:39.366  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:39.366  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:39.366  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:39.366  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:41:39.373  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:41:39.375  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:41:39.375  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9714bb removed from the list
09-12 12:41:39.375  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:41:39.375  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:41:39.376  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:41:39.388  3791  4262 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-12 12:41:39.388  3791  4262 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 12:41:42.389  3791  4263 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-12 12:41:42.389  3791  4263 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 12:41:42.390  3791  4263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 12:41:42.390  3791  4262 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-12 12:41:42.390  3791  4262 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 12:41:42.390  3791  4263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 12:41:42.391  3791  4262 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 12:41:42.392  3791  4263 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-12 12:41:42.395  3791  4262 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 12:41:42.395  3791  4265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: IncomingSocketThread/Sender)
,09-12 12:41:42.398  3791  4262 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-12 12:41:42.398  3791  4266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 421, name: IncomingSocketThread/Receiver)
,09-12 12:41:42.400  3791  4266 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 421, thread name: IncomingSocketThread/Receiver)
09-12 12:41:42.400  3791  4266 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 12:41:42.401  3791  4266 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 421, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 12:41:42.401  3791  4267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 422, name: OutgoingSocketThread/Sender)
09-12 12:41:42.401  3791  4268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: OutgoingSocketThread/Receiver)
09-12 12:41:42.402  3791  4268 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 423, thread name: OutgoingSocketThread/Receiver)
09-12 12:41:42.402  3791  4268 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 12:41:42.402  3791  4268 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 423, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-12 12:41:44.798   872  1314 D ConnectivityService: handlePromptUnvalidated 102
,09-12 12:41:45.395  3791  3839 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 12:41:45.397  3791  3839 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 12:41:45.405  3791  3839 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@41dc11c Bundle[{}]
,09-12 12:41:45.406  3791  3839 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 12:41:45.406  3791  3839 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 12:41:45.407  3791  3839 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 12:41:45.407  3791  3839 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 12:41:45.408  3791  3839 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 12:41:45.408  3791  3839 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 12:41:45.412  3791  3839 I System.out: Running OutgoingSocketThread
,09-12 12:41:45.415  3791  4269 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-12 12:41:45.416  3791  4269 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 12:41:48.425  3791  4271 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-12 12:41:48.425  3791  4271 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-12 12:41:48.426  3791  4269 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-12 12:41:48.426  3791  4271 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 12:41:48.426  3791  4269 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 12:41:48.427  3791  4271 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 12:41:48.429  3791  4269 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 12:41:48.430  3791  4271 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 12:41:48.436  3791  4269 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 12:41:48.437  3791  4273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: IncomingSocketThread/Sender)
,09-12 12:41:48.442  3791  4269 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-12 12:41:48.444  3791  4274 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: IncomingSocketThread/Receiver)
,09-12 12:41:48.448  3791  4275 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: OutgoingSocketThread/Sender)
,09-12 12:41:48.449  3791  4274 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: IncomingSocketThread/Receiver)
09-12 12:41:48.449  3791  4274 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 12:41:48.449  3791  4274 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-12 12:41:48.451  3791  4276 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: OutgoingSocketThread/Receiver)
09-12 12:41:48.453  3791  4276 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: OutgoingSocketThread/Receiver)
,09-12 12:41:48.454  3791  4276 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 12:41:48.454  3791  4276 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 12:41:51.427  3791  3839 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 444)
,09-12 12:41:51.429  3791  3839 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 12:41:51.430  3791  3839 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 445)
,09-12 12:41:51.436  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:41:51.436  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46fdd8 added. We now have 3 listener(s)
,09-12 12:41:51.438  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 12:41:51.438  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:41:51.438  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 12:41:51.439  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:41:51.439  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a21531 added. We now have 4 listener(s)
09-12 12:41:51.439  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:41:51.439  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:41:51.444  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:41:51.459  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:41:51.459  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:51.459  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:51.459  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:51.459  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:51.459  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:51.459  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:51.459  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:41:51.466  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:41:51.466  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:41:51.467  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:41:51.468  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:41:51.468  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:41:51.468  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:41:51.468  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:51.469  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:41:51.469  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 12:41:51.469  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46fdd8 removed from the list
,09-12 12:41:51.469  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:41:51.470  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a21531 removed from the list
,09-12 12:41:51.470  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:51.470  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:41:51.471  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:41:51.472  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:41:51.472  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:41:51.481  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:41:51.482  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:41:51.482  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:41:51.482  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:51.482  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a21531 not in the list
09-12 12:41:51.482  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:51.483  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:41:51.485  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:41:51.485  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:41:51.485  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:41:51.485  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a21531 not in the list
09-12 12:41:51.485  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:41:51.485  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:51.485  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:41:51.485  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46fdd8 not in the list
09-12 12:41:51.486  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:41:51.486  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a184197 added. We now have 3 listener(s)
09-12 12:41:51.489  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 12:41:51.489  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:41:51.489  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 12:41:51.489  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:41:51.489  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21a1f84 added. We now have 4 listener(s)
09-12 12:41:51.489  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:41:51.491  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:41:51.494  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:41:51.505  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:41:51.505  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:51.505  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:51.505  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:51.505  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:51.505  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:51.505  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:51.505  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:41:51.510  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:41:51.510  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:41:51.511  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:41:51.511  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 12:41:51.511  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 12:41:51.511  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:41:51.511  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 12:41:51.515  3791  3839 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 12:41:51.515  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 12:41:51.516  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:51.521  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:51.521  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 12:41:51.522  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 12:41:51.522  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 12:41:51.529  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 12:41:51.529  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 12:41:51.529  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 12:41:51.531  3791  3839 D BluetoothAdapter: STATE_ON
,09-12 12:41:51.536  4180  4219 D BtGatt.GattService: registerClient() - UUID=921a27cf-5bf9-45fe-b1d6-c53137006545
09-12 12:41:51.537  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=921a27cf-5bf9-45fe-b1d6-c53137006545, clientIf=5
,09-12 12:41:51.537  3791  3802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 12:41:51.538  4180  4190 D BtGatt.GattService: start scan with filters
,09-12 12:41:51.545  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 12:41:51.545  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 12:41:51.546  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 12:41:51.546  4180  4199 D BtGatt.ScanManager: handling starting scan
,09-12 12:41:51.546  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 12:41:51.549  4180  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2335f0
,09-12 12:41:51.550  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:41:51.550  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 12:41:51.551  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
09-12 12:41:51.553  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 12:41:51.557  3791  3839 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
09-12 12:41:51.557  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:41:51.557  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 12:41:51.557  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:51.557  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 12:41:51.557  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:41:51.558  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 12:41:51.558  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 12:41:51.558  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:41:51.558  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 12:41:51.558  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 12:41:51.559  3791  3839 D BluetoothAdapter: STATE_ON
09-12 12:41:51.560  4180  4219 D BtGatt.GattService: stopScan() - queue size =1
,09-12 12:41:51.561  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 12:41:51.561  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:41:51.561  4180  4190 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 12:41:51.562  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 12:41:51.562  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 12:41:51.562  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 12:41:51.562  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 12:41:51.562  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 12:41:51.562  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 12:41:51.567  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:41:51.567  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 12:41:51.567  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 12:41:51.568  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 12:41:51.569  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:41:51.572  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:41:51.573  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:41:51.573  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:41:51.575  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 12:41:51.575  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:41:51.576  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 12:41:51.576  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 12:41:51.596  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 12:41:51.596  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:41:51.605  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 12:41:51.605  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:41:51.624  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 12:41:51.624  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:41:51.625  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
,09-12 12:41:51.637  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 12:41:51.637  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:41:51.637  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:41:51.649  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 12:41:51.650  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:41:52.074  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-12 12:41:52.075  3791  3791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:41:52.075  3791  3791 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:41:54.574  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:41:54.574  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:41:54.575  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:41:54.576  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:41:54.576  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:54.576  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:41:54.577  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 12:41:54.577  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a184197 removed from the list
09-12 12:41:54.577  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:41:54.578  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21a1f84 removed from the list
09-12 12:41:54.578  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:41:54.578  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:41:54.580  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:54.580  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:41:54.584  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:41:54.584  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:41:54.584  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:41:54.585  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21a1f84 not in the list
09-12 12:41:54.585  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:41:54.585  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:41:54.589  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:41:54.589  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:41:54.589  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:41:54.590  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21a1f84 not in the list
09-12 12:41:54.590  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:41:54.590  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:54.591  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:41:54.591  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a184197 not in the list
09-12 12:41:54.593  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:41:54.594  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c53969 added. We now have 3 listener(s),
,09-12 12:41:54.599  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
09-12 12:41:54.600  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:41:54.600  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 12:41:54.601  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:41:54.601  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fad9fee added. We now have 4 listener(s)
09-12 12:41:54.602  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:41:54.603  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:41:54.609  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-12 12:41:54.620  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:41:54.620  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:54.620  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:54.620  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:54.620  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:54.620  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:54.620  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:54.620  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:41:54.624  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:54.624  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:41:54.624  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 12:41:54.625  3791  3839 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-12 12:41:54.625  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-12 12:41:54.626  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 12:41:54.626  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 12:41:54.626  3791  3839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 12:41:54.626  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:41:54.627  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 12:41:54.627  3791  3839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-12 12:41:54.628  3791  3839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 12:41:54.628  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-12 12:41:54.628  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 12:41:54.628  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:41:54.628  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 12:41:54.629  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:54.634  3791  3839 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 12:41:54.634  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:41:54.634  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 12:41:54.634  3791  3791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 12:41:54.639  3791  4277 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:41:54.642  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 12:41:54.643  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 12:41:54.644  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 12:41:54.647  3791  4277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 12:41:54.648  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 12:41:54.649  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 12:41:54.650  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-12 12:41:54.652  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 12:41:54.653  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 12:41:54.653  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 12:41:54.654  3791  3839 D BluetoothAdapter: STATE_ON
,09-12 12:41:54.657  4180  4191 D BtGatt.GattService: registerClient() - UUID=08d47af5-bd08-4eea-bb91-81c0c4b0cc19
,09-12 12:41:54.658  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=08d47af5-bd08-4eea-bb91-81c0c4b0cc19, clientIf=5
,09-12 12:41:54.659  3791  3802 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5,
,09-12 12:41:54.663  4180  4198 D BtGatt.AdvertiseManager: message : 0
,09-12 12:41:54.667  4180  4198 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 12:41:54.690  4180  4196 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 12:41:54.707  4180  4196 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 12:41:54.710  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-12 12:41:54.711  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 12:41:54.715  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 12:41:54.719  3791  3791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 12:41:54.719  3791  3791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 12:41:54.720  3791  3791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 12:41:54.721  3791  3791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-12 12:41:54.722  3791  3791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-12 12:41:54.722  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-12 12:41:54.724  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-12 12:41:54.730  3791  3791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 12:41:54.731  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 12:41:55.232  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 12:41:55.232  3791  3791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 12:41:55.233  3791  3791 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:41:57.726  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:41:57.726  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-12 12:41:57.727  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 12:41:57.727  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 12:41:57.727  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 12:41:57.728  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 12:41:57.728  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 12:41:57.729  3791  4277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 12:41:57.729  3791  3839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 12:41:57.729  3791  4277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 12:41:57.730  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:41:57.730  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 12:41:57.730  3791  3791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 12:41:57.730  3791  4277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 12:41:57.730  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 12:41:57.731  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:41:57.731  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 12:41:57.734  3791  3839 D BluetoothAdapter: STATE_ON
09-12 12:41:57.734  3791  3839 D BluetoothLeScanner: could not find callback wrapper
09-12 12:41:57.734  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 12:41:57.734  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-12 12:41:57.737  4180  4198 D BtGatt.AdvertiseManager: message : 1
09-12 12:41:57.738  4180  4198 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 12:41:57.747  4180  4196 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-12 12:41:57.748  4180  4196 D BtGatt.GattService: Client app is not null!
,09-12 12:41:57.750  4180  4219 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 12:41:57.751  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 12:41:57.751  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 12:41:57.751  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 12:41:57.751  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 12:41:57.751  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 12:41:57.753  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:41:57.754  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 12:41:57.754  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 12:41:57.755  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:41:57.758  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:41:57.759  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:41:57.759  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:41:57.759  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 12:41:57.760  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c53969 removed from the list
,09-12 12:41:57.760  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:41:57.760  3791  3791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-12 12:41:57.760  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fad9fee removed from the list
09-12 12:41:57.760  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:41:57.760  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:41:57.760  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:41:57.761  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:41:57.761  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:41:57.762  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:41:57.762  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:41:57.765  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:41:57.765  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:41:57.765  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:41:57.766  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fad9fee not in the list
,09-12 12:41:57.766  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:41:57.766  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:41:57.768  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:41:57.768  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:41:57.768  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:41:57.769  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fad9fee not in the list
09-12 12:41:57.769  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:41:57.769  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:41:57.769  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:41:57.769  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c53969 not in the list
,09-12 12:41:57.770  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:41:57.770  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db2a2ab added. We now have 3 listener(s)
,09-12 12:41:57.772  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 12:41:57.772  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:41:57.772  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 12:41:57.772  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:41:57.772  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de18d08 added. We now have 4 listener(s)
,09-12 12:41:57.772  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:41:57.773  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:41:57.775  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:41:57.780  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:41:57.780  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:41:57.780  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:41:57.780  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:41:57.780  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:41:57.780  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:57.780  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:41:57.780  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:41:57.782  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:41:57.782  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:41:57.783  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 12:41:57.783  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 12:41:57.783  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 12:41:57.783  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:41:57.783  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 12:41:57.786  3791  3839 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 12:41:57.786  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 12:41:57.786  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:57.790  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:41:57.790  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 12:41:57.790  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 12:41:57.791  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 12:41:57.793  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 12:41:57.793  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 12:41:57.794  3791  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 12:41:57.794  3791  3839 D BluetoothAdapter: STATE_ON
,09-12 12:41:57.796  4180  4219 D BtGatt.GattService: registerClient() - UUID=d4d8cd1c-67f7-402a-bd1e-7082dcc98a25
,09-12 12:41:57.797  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=d4d8cd1c-67f7-402a-bd1e-7082dcc98a25, clientIf=5
09-12 12:41:57.797  3791  3802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 12:41:57.797  4180  4191 D BtGatt.GattService: start scan with filters
,09-12 12:41:57.800  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 12:41:57.800  4180  4199 D BtGatt.ScanManager: handling starting scan
09-12 12:41:57.800  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 12:41:57.800  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 12:41:57.800  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 12:41:57.803  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:41:57.803  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 12:41:57.803  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:41:57.805  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 12:41:57.807  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 12:41:57.807  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:41:57.808  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 12:41:57.814  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 12:41:57.814  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:41:57.814  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 12:41:57.814  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 12:41:57.827  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 12:41:57.827  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:41:57.834  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 12:41:57.834  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:41:58.262  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:41:58.303  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 12:41:58.304  3791  3791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:41:58.304  3791  3791 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:41:59.341  4180  4180 D BtGatt.ScanManager: awakened up at time 236411
,09-12 12:41:59.343  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:41:59.397  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,09-12 12:41:59.398  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:41:59.398  4180  4196 D BtGatt.GattService: current time is 236468425345
,09-12 12:41:59.400  4180  4196 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -71, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, 116, -43, -111, -91, -20, -29, 1, -128, -95, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -126, -22, -96, 83, -39, -56, 1, -128, -83, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -91, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -94, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 87, 45, 110, 28, -13, -4, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0]
,09-12 12:41:59.403  4180  4196 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,09-12 12:41:59.405  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 12:41:59.406  4180  4196 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
09-12 12:41:59.407  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,09-12 12:41:59.407  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 12:41:59.408  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 12:41:59.409  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 12:41:59.410  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 12:41:59.411  4180  4196 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,09-12 12:41:59.416  3791  3791 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 1
,09-12 12:41:59.419  3791  3791 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:37:96:AB 1] updated - the peer count is 1
,09-12 12:41:59.420  3791  3791 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 1], added - the peer count is 2
09-12 12:41:59.420  3791  3791 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
09-12 12:41:59.422  3791  3791 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 1], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,09-12 12:42:00.815  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:42:00.816  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 12:42:00.816  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 12:42:00.817  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:42:00.817  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 12:42:00.817  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:42:00.818  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 12:42:00.818  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 12:42:00.818  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:42:00.819  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 12:42:00.819  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 12:42:00.821  3791  3839 D BluetoothAdapter: STATE_ON
,09-12 12:42:00.823  4180  4219 D BtGatt.GattService: stopScan() - queue size =1
,09-12 12:42:00.826  4180  4191 D BtGatt.GattService: unregisterClient() - clientIf=5,
,09-12 12:42:00.828  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 12:42:00.828  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 12:42:00.828  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 12:42:00.829  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 12:42:00.829  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 12:42:00.833  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:42:00.833  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 12:42:00.834  3791  3839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 12:42:00.834  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 12:42:00.837  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:42:00.837  3791  3839 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-12 12:42:00.840  4180  4180 D BtGatt.ScanManager: awakened up at time 237910
09-12 12:42:00.846  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:42:00.847  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:42:00.847  3791  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:42:00.848  3791  3791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:42:00.849  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 12:42:00.849  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:42:00.847  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:42:00.850  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:42:00.850  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 12:42:00.850  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db2a2ab removed from the list
09-12 12:42:00.850  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:42:00.850  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
09-12 12:42:00.850  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de18d08 removed from the list
09-12 12:42:00.850  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:42:00.850  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:42:00.853  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:42:00.853  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:42:00.854  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:42:00.854  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:42:00.855  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:42:00.855  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de18d08 not in the list
,09-12 12:42:00.855  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:42:00.855  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:42:00.856  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:42:00.856  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:42:00.856  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:42:00.856  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de18d08 not in the list
09-12 12:42:00.857  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:42:00.857  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:42:00.857  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:42:00.857  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db2a2ab not in the list
09-12 12:42:00.858  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:42:00.858  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f2f520 added. We now have 3 listener(s)
09-12 12:42:00.860  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 12:42:00.860  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:42:00.860  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 12:42:00.860  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:42:00.860  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce24ed9 added. We now have 4 listener(s)
09-12 12:42:00.860  3791  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:42:00.862  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:42:00.863  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 12:42:00.863  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:42:00.864  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:42:00.865  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:42:00.869  3791  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:42:00.869  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:42:00.869  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:42:00.869  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:42:00.869  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:42:00.869  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:42:00.869  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:42:00.869  3791  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:42:00.872  3791  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:42:00.872  3791  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:42:00.873  3791  3839 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:42:00.873  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:42:00.873  3791  3839 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:42:00.873  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:42:00.873  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:42:00.873  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:42:00.873  3791  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 12:42:00.873  3791  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f2f520 removed from the list
09-12 12:42:00.874  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:42:00.874  3791  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce24ed9 removed from the list
,09-12 12:42:00.877  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:42:00.880  3791  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:42:00.880  3791  3839 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:42:00.880  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:42:00.881  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:42:00.882  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:42:00.883  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:42:00.883  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:42:00.883  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:42:00.883  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce24ed9 not in the list
09-12 12:42:00.883  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:42:00.883  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:42:00.883  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-12 12:42:00.884  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:42:00.884  4180  4196 D BtGatt.GattService: current time is 237954496919
09-12 12:42:00.884  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:42:00.884  4180  4196 D BtGatt.GattService: Batch record : [-126, -22, -96, 83, -39, -56, 1, -128, -86, 29, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -11, -88, -73, 66, -22, 95, 1, -128, -61, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0]
09-12 12:42:00.885  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:42:00.885  3791  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:42:00.885  3791  3839 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce24ed9 not in the list
09-12 12:42:00.885  3791  3839 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:42:00.885  3791  3839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:42:00.885  3791  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:42:00.885  4180  4196 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
09-12 12:42:00.885  3791  3839 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f2f520 not in the list
09-12 12:42:00.886  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 12:42:00.886  4180  4196 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
09-12 12:42:00.887  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 12:42:00.887  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 12:42:00.887  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-12 12:42:00.887  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:42:00.887  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 12:42:00.887  3791  3839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:42:01.349  3791  3791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:42:02.904  3791  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: My test thread name)
,09-12 12:42:03.161   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=240230, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:42:04.901  3791  3839 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 454
,09-12 12:42:04.902  3791  3839 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 454, name: My test thread name)
,09-12 12:42:04.910  3791  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: My test thread name)
,09-12 12:42:04.911  3791  4279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 455, thread name: My test thread name)
09-12 12:42:04.911  3791  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-12 12:42:04.916  3791  3839 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 12:42:04.926  3791  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,09-12 12:42:04.927  3791  4280 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 459, thread name: My test thread name): Test exception.
09-12 12:42:04.928  3791  4280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-12 12:42:04.936  3791  3839 I jxcore-log: Total number of executed tests:  82
09-12 12:42:04.936  3791  3839 I jxcore-log: 
,09-12 12:42:04.937  3791  3839 I jxcore-log: Number of passed tests:  82
09-12 12:42:04.937  3791  3839 I jxcore-log: 
,09-12 12:42:04.938  3791  3839 I jxcore-log: Number of failed tests:  0
09-12 12:42:04.938  3791  3839 I jxcore-log: 
09-12 12:42:04.939  3791  3839 I jxcore-log: Number of ignored tests:  0
09-12 12:42:04.939  3791  3839 I jxcore-log: 
09-12 12:42:04.940  3791  3839 I jxcore-log: Total duration:  101346
09-12 12:42:04.940  3791  3839 I jxcore-log: 
,09-12 12:42:04.952  3791  3839 I jxcore-log: Unit Test app is loaded
09-12 12:42:04.952  3791  3839 I jxcore-log: 
,09-12 12:42:04.970  3791  3791 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-12 12:42:04.979  3791  4278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-12 12:42:04.980  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:04.980  3791  3839 I jxcore-log: 
,09-12 12:42:04.985  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:04.985  3791  3839 I jxcore-log: 
,09-12 12:42:04.986  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:04.986  3791  3839 I jxcore-log: 
09-12 12:42:04.987  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:04.987  3791  3839 I jxcore-log: 
,09-12 12:42:04.988  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 12:42:04.988  3791  3839 I jxcore-log: 
09-12 12:42:04.990  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:42:04.990  3791  3839 I jxcore-log: 
,09-12 12:42:04.994  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:04.994  3791  3839 I jxcore-log: 
,09-12 12:42:04.996  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:04.996  3791  3839 I jxcore-log: 
09-12 12:42:04.996  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 12:42:04.996  3791  3839 I jxcore-log: 
09-12 12:42:04.997  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:42:04.997  3791  3839 I jxcore-log: 
09-12 12:42:04.998  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:42:04.998  3791  3839 I jxcore-log: 
,09-12 12:42:04.999  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:04.999  3791  3839 I jxcore-log: 
09-12 12:42:04.999  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:04.999  3791  3839 I jxcore-log: 
09-12 12:42:05.002  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.002  3791  3839 I jxcore-log: 
,09-12 12:42:05.004  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:42:05.004  3791  3839 I jxcore-log: 
,09-12 12:42:05.007  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:42:05.007  3791  3839 I jxcore-log: 
,09-12 12:42:05.010  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:42:05.010  3791  3839 I jxcore-log: 
,09-12 12:42:05.012  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.012  3791  3839 I jxcore-log: 
,09-12 12:42:05.014  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.014  3791  3839 I jxcore-log: 
,09-12 12:42:05.016  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.016  3791  3839 I jxcore-log: 
,09-12 12:42:05.019  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:42:05.019  3791  3839 I jxcore-log: 
,09-12 12:42:05.021  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:42:05.021  3791  3839 I jxcore-log: 
,09-12 12:42:05.021  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:42:05.021  3791  3839 I jxcore-log: 
09-12 12:42:05.022  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.022  3791  3839 I jxcore-log: 
,09-12 12:42:05.023  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.023  3791  3839 I jxcore-log: 
09-12 12:42:05.023  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.023  3791  3839 I jxcore-log: 
,09-12 12:42:05.024  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.024  3791  3839 I jxcore-log: 
09-12 12:42:05.025  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.025  3791  3839 I jxcore-log: 
,09-12 12:42:05.026  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.026  3791  3839 I jxcore-log: 
,09-12 12:42:05.027  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.027  3791  3839 I jxcore-log: 
09-12 12:42:05.027  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.027  3791  3839 I jxcore-log: 
,09-12 12:42:05.028  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.028  3791  3839 I jxcore-log: 
09-12 12:42:05.029  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.029  3791  3839 I jxcore-log: 
,09-12 12:42:05.030  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.030  3791  3839 I jxcore-log: 
09-12 12:42:05.030  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.030  3791  3839 I jxcore-log: 
,09-12 12:42:05.031  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.031  3791  3839 I jxcore-log: 
09-12 12:42:05.032  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.032  3791  3839 I jxcore-log: 
,09-12 12:42:05.032  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:42:05.032  3791  3839 I jxcore-log: 
09-12 12:42:05.033  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 12:42:05.033  3791  3839 I jxcore-log: 
,09-12 12:42:05.034  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 12:42:05.034  3791  3839 I jxcore-log: 
09-12 12:42:05.035  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.035  3791  3839 I jxcore-log: 
,09-12 12:42:05.035  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.035  3791  3839 I jxcore-log: 
,09-12 12:42:05.036  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.036  3791  3839 I jxcore-log: 
09-12 12:42:05.037  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.037  3791  3839 I jxcore-log: 
,09-12 12:42:05.038  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.038  3791  3839 I jxcore-log: 
09-12 12:42:05.039  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:42:05.039  3791  3839 I jxcore-log: 
09-12 12:42:05.039  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.039  3791  3839 I jxcore-log: 
,09-12 12:42:05.040  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 12:42:05.040  3791  3839 I jxcore-log: 
09-12 12:42:05.041  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.041  3791  3839 I jxcore-log: 
,09-12 12:42:05.042  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:42:05.042  3791  3839 I jxcore-log: 
09-12 12:42:05.042  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 12:42:05.042  3791  3839 I jxcore-log: 
,09-12 12:42:05.044  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-12 12:42:05.044  3791  3839 I jxcore-log: 
09-12 12:42:05.044  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-12 12:42:05.044  3791  3839 I jxcore-log: 
,09-12 12:42:05.045  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:42:05.045  3791  3839 I jxcore-log: 
,09-12 12:42:05.046  3791  3839 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:42:05.046  3791  3839 I jxcore-log: 
,09-12 12:42:05.053  3791  3839 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-12 12:42:05.053  3791  3839 I jxcore-log:   bluetooth: 'on',
09-12 12:42:05.053  3791  3839 I jxcore-log:   wifi: 'on',
09-12 12:42:05.053  3791  3839 I jxcore-log:   cellular: 'doNotCare',
09-12 12:42:05.053  3791  3839 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 12:42:05.053  3791  3839 I jxcore-log: 
,09-12 12:42:05.061  3791  3839 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-12 12:42:05.061  3791  3839 I jxcore-log:   bluetooth: 'on',
09-12 12:42:05.061  3791  3839 I jxcore-log:   wifi: 'on',
09-12 12:42:05.061  3791  3839 I jxcore-log:   cellular: 'doNotCare',
09-12 12:42:05.061  3791  3839 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 12:42:05.061  3791  3839 I jxcore-log: 
,09-12 12:42:05.062  3791  3839 I jxcore-log: My device name is: motorola-Nexus 6
09-12 12:42:05.062  3791  3839 I jxcore-log: 
,09-12 12:42:05.063  3791  3839 I jxcore-log: Running for WIFI network type
09-12 12:42:05.063  3791  3839 I jxcore-log: 
09-12 12:42:05.063  3791  3839 I jxcore-log: [TTR] ::  Looking for tests in bv_tests
09-12 12:42:05.063  3791  3839 I jxcore-log: 
,09-12 12:42:05.073  3791  3839 I jxcore-log: [TTR] ::  Going to execute 32 test file(s)
09-12 12:42:05.073  3791  3839 I jxcore-log: 
,09-12 12:42:05.078  3791  3839 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-12 12:42:05.079  3791  3839 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-12 12:42:05.079  3791  3839 I jxcore-log: 
,09-12 12:42:05.082  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-12 12:42:05.082  3791  3839 I jxcore-log: 
,09-12 12:42:05.560  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-12 12:42:05.560  3791  3839 I jxcore-log: 
,09-12 12:42:05.590  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-12 12:42:05.590  3791  3839 I jxcore-log: 
,09-12 12:42:07.082  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-12 12:42:07.082  3791  3839 I jxcore-log: 
,09-12 12:42:07.342  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-12 12:42:07.342  3791  3839 I jxcore-log: 
,09-12 12:42:07.349  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-12 12:42:07.349  3791  3839 I jxcore-log: 
,09-12 12:42:07.359  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-12 12:42:07.359  3791  3839 I jxcore-log: 
,09-12 12:42:07.436  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-12 12:42:07.436  3791  3839 I jxcore-log: 
,09-12 12:42:07.457  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-12 12:42:07.457  3791  3839 I jxcore-log: 
,09-12 12:42:07.462  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-12 12:42:07.462  3791  3839 I jxcore-log: 
,09-12 12:42:08.323  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-12 12:42:08.323  3791  3839 I jxcore-log: 
,09-12 12:42:08.490  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-12 12:42:08.490  3791  3839 I jxcore-log: 
,09-12 12:42:08.812  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-12 12:42:08.812  3791  3839 I jxcore-log: 
,09-12 12:42:08.823  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-12 12:42:08.823  3791  3839 I jxcore-log: 
,09-12 12:42:08.831  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-12 12:42:08.831  3791  3839 I jxcore-log: 
,09-12 12:42:08.838  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-12 12:42:08.838  3791  3839 I jxcore-log: 
,09-12 12:42:08.878  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-12 12:42:08.878  3791  3839 I jxcore-log: 
,09-12 12:42:08.943  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-12 12:42:08.943  3791  3839 I jxcore-log: 
,09-12 12:42:08.951  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-12 12:42:08.951  3791  3839 I jxcore-log: 
,09-12 12:42:08.960  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-12 12:42:08.960  3791  3839 I jxcore-log: 
,09-12 12:42:08.981  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-12 12:42:08.981  3791  3839 I jxcore-log: 
,09-12 12:42:08.986  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-12 12:42:08.986  3791  3839 I jxcore-log: 
,09-12 12:42:08.992  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-12 12:42:08.992  3791  3839 I jxcore-log: 
,09-12 12:42:09.009  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-12 12:42:09.009  3791  3839 I jxcore-log: 
,09-12 12:42:09.036  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-12 12:42:09.036  3791  3839 I jxcore-log: 
,09-12 12:42:09.048  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-12 12:42:09.048  3791  3839 I jxcore-log: 
,09-12 12:42:09.062  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-12 12:42:09.062  3791  3839 I jxcore-log: 
,09-12 12:42:09.075  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-12 12:42:09.075  3791  3839 I jxcore-log: 
,09-12 12:42:09.093  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-12 12:42:09.093  3791  3839 I jxcore-log: 
,09-12 12:42:09.106  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-12 12:42:09.106  3791  3839 I jxcore-log: 
,09-12 12:42:09.111  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-12 12:42:09.111  3791  3839 I jxcore-log: 
,09-12 12:42:09.138  3791  3839 I jxcore-log: [TTR] ::  Loading /data/user/0/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-12 12:42:09.138  3791  3839 I jxcore-log: 
,09-12 12:42:09.145  3791  3839 I jxcore-log: ThaliTape :: Started ThaliTape
09-12 12:42:09.145  3791  3839 I jxcore-log: 
,09-12 12:42:09.150  3791  3839 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-12 12:42:09.150  3791  3839 I jxcore-log: 
,09-12 12:42:09.222  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:09.222  3791  3839 I jxcore-log: 
09-12 12:42:09.222  3791  3839 I jxcore-log: websocket error
09-12 12:42:09.222  3791  3839 I jxcore-log: 
,09-12 12:42:09.222  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:09.222  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:09.222  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:09.222  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:09.222  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:09.222  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:09.222  3791  3839 I jxcore-log: 
,09-12 12:42:09.249  3042  4282 V KeepSync: Connecting to GoogleApiClient
09-12 12:42:09.250   872   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:42:09.303  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:42:09.308  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:42:09.334  1495  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 12:42:09.334  1495  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 12:42:09.334  1495  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:42:09.334  1495  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:42:09.355  1713  4283 V BaseAuthAsyncOperation: access token request failed
,09-12 12:42:09.356  3042  4282 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:42:09.415  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 12:42:09.416  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 12:42:09.417  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:42:09.417  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:42:09.437  3042  4282 E KeepSync: IOException
09-12 12:42:09.437  3042  4282 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:42:09.437  3042  4282 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:42:09.437  3042  4282 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:42:09.437  3042  4282 E KeepSync: 	... 10 more
,09-12 12:42:09.437  3042  4282 W KeepSync: Sync result 2
,09-12 12:42:09.441   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 246136, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:42:10.525  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:10.525  3791  3839 I jxcore-log: 
,09-12 12:42:10.525  3791  3839 I jxcore-log: websocket error
09-12 12:42:10.525  3791  3839 I jxcore-log: 
,09-12 12:42:10.526  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:10.526  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:10.526  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:10.526  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:10.526  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:10.526  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:10.526  3791  3839 I jxcore-log: 
,09-12 12:42:13.359  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:13.359  3791  3839 I jxcore-log: 
,09-12 12:42:13.364  3791  3839 I jxcore-log: websocket error,
09-12 12:42:13.364  3791  3839 I jxcore-log: 
09-12 12:42:13.364  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:13.364  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:13.364  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:13.364  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:13.364  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:13.364  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:13.364  3791  3839 I jxcore-log: 
,09-12 12:42:14.207   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=251277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 12:42:16.545  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:16.545  3791  3839 I jxcore-log: 
,09-12 12:42:16.545  3791  3839 I jxcore-log: websocket error
09-12 12:42:16.545  3791  3839 I jxcore-log: 
09-12 12:42:16.546  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:16.546  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:16.546  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:16.546  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:16.546  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:16.546  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:16.546  3791  3839 I jxcore-log: 
,09-12 12:42:21.613  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:21.613  3791  3839 I jxcore-log: 
,09-12 12:42:21.613  3791  3839 I jxcore-log: websocket error
09-12 12:42:21.613  3791  3839 I jxcore-log: 
,09-12 12:42:21.614  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:21.614  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:21.614  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:21.614  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:21.614  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:21.614  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:21.614  3791  3839 I jxcore-log: 
,09-12 12:42:26.671  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:26.671  3791  3839 I jxcore-log: 
,09-12 12:42:26.671  3791  3839 I jxcore-log: websocket error
09-12 12:42:26.671  3791  3839 I jxcore-log: 
09-12 12:42:26.671  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:26.671  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:26.671  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:26.671  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:26.671  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:26.671  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:26.671  3791  3839 I jxcore-log: 
,09-12 12:42:31.733  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:31.733  3791  3839 I jxcore-log: 
,09-12 12:42:31.734  3791  3839 I jxcore-log: websocket error
09-12 12:42:31.734  3791  3839 I jxcore-log: 
09-12 12:42:31.734  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:31.734  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:31.734  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:31.734  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:31.734  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:31.734  3791  3839 I jxcore-log: emit@events.js:82:1,
09-12 12:42:31.734  3791  3839 I jxcore-log: 
,09-12 12:42:36.785  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:36.785  3791  3839 I jxcore-log: 
,09-12 12:42:36.785  3791  3839 I jxcore-log: websocket error
09-12 12:42:36.785  3791  3839 I jxcore-log: 
,09-12 12:42:36.786  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:36.786  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:36.786  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:36.786  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:36.786  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:36.786  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:36.786  3791  3839 I jxcore-log: 
,09-12 12:42:39.546  3595  4286 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:42:39.593  3595  4287 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:42:39.622  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:42:39.630  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:42:39.682  1495  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:42:39.683  1495  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:42:39.683  1495  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:42:39.683  1495  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:42:39.722  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:42:39.725  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:42:39.762  1495  2016 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:42:39.762  1495  2016 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:42:39.762  1495  2016 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:42:39.762  1495  2016 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:42:39.788  3595  4287 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 12:42:39.789  3595  4286 E BooksSync: Soft error
09-12 12:42:39.789  3595  4286 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:42:39.789  3595  4286 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:42:39.790  3595  4286 E BooksSync: Sync error
09-12 12:42:39.790  3595  4286 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:42:39.790  3595  4286 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:42:39.790  3595  4286 I BooksSync: Finished books sync
,09-12 12:42:39.802   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 249176, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:42:40.100   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=277170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:42:41.847  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:41.847  3791  3839 I jxcore-log: 
09-12 12:42:41.847  3791  3839 I jxcore-log: websocket error
09-12 12:42:41.847  3791  3839 I jxcore-log: 
09-12 12:42:41.847  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:41.847  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:41.847  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:41.847  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:41.847  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:41.847  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:41.847  3791  3839 I jxcore-log: 
,09-12 12:42:46.821   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=283890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 12:42:46.904  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:46.904  3791  3839 I jxcore-log: 
09-12 12:42:46.904  3791  3839 I jxcore-log: websocket error
09-12 12:42:46.904  3791  3839 I jxcore-log: 
09-12 12:42:46.904  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:46.904  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:46.904  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:46.904  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:46.904  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:46.904  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:46.904  3791  3839 I jxcore-log: 
,09-12 12:42:52.005  3791  3839 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:42:52.005  3791  3839 I jxcore-log: 
,09-12 12:42:52.005  3791  3839 I jxcore-log: websocket error
09-12 12:42:52.005  3791  3839 I jxcore-log: 
09-12 12:42:52.005  3791  3839 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:42:52.005  3791  3839 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:42:52.005  3791  3839 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:42:52.005  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:52.005  3791  3839 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:42:52.005  3791  3839 I jxcore-log: emit@events.js:82:1
09-12 12:42:52.005  3791  3839 I jxcore-log: 
,09-12 12:42:57.356  3791  3839 I jxcore-log: ThaliTape :: Reconnected to the test server
09-12 12:42:57.356  3791  3839 I jxcore-log: 
,09-12 12:42:57.374  3791  3839 I jxcore-log: ThaliTape :: Connected to the test server
09-12 12:42:57.374  3791  3839 I jxcore-log: 
,09-12 12:43:10.402  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:43:10.408  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:43:10.485  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 12:43:10.486  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:43:10.486  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:43:10.486  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:43:10.527  2999  4302 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:43:10.527  2999  4302 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:43:10.527  2999  4302 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	... 12 more
09-12 12:43:10.527  2999  4302 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at fal.a(PG:38)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:43:10.527  2999  4302 E HttpOperation: 	... 14 more
,09-12 12:43:10.598  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 12:43:10.599  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:43:10.599  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:43:10.599  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:43:10.621  2999  4302 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:43:10.621  2999  4302 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at hec.a(PG:42)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at hee.a(PG:102)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at czr.a(PG:65)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at kka.a(PG:108)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:43:10.621  2999  4302 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	... 15 more
09-12 12:43:10.621  2999  4302 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at fal.a(PG:38)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:43:10.621  2999  4302 E HttpOperation: 	... 17 more
,09-12 12:43:10.622  2999  4302 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 12:43:10.622  2999  4302 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	... 15 more
09-12 12:43:10.622  2999  4302 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:43:10.622  2999  4302 E ExperimentLoader: 	... 17 more
,09-12 12:43:10.786   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 286939, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:43:40.893  3595  4306 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:43:40.937  3595  4307 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:43:40.954  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:43:40.956  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:43:41.000  3042  4305 V KeepSync: Connecting to GoogleApiClient
,09-12 12:43:41.000   872  1936 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:43:41.008  1495  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:43:41.008  1495  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 12:43:41.008  1495  2017 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-12 12:43:41.008  1495  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:43:41.056  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:43:41.059  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:43:41.097  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 12:43:41.097  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 12:43:41.097  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:43:41.097  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:43:41.102  1495  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:43:41.103  1495  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 12:43:41.103  1495  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:43:41.103  1495  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:43:41.124  3595  4307 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 12:43:41.127  3595  4306 E BooksSync: Soft error
09-12 12:43:41.127  3595  4306 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:43:41.127  3595  4306 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:43:41.127  3595  4306 E BooksSync: Sync error
09-12 12:43:41.127  3595  4306 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:43:41.127  3595  4306 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:43:41.127  3595  4306 I BooksSync: Finished books sync
09-12 12:43:41.128  1713  4308 V BaseAuthAsyncOperation: access token request failed
09-12 12:43:41.129  3042  4305 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:43:41.139   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 309221, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:43:41.183  1495  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 12:43:41.184  1495  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 12:43:41.184  1495  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:43:41.184  1495  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:43:41.199  3042  4305 E KeepSync: IOException
09-12 12:43:41.199  3042  4305 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:43:41.199  3042  4305 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:43:41.199  3042  4305 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:43:41.199  3042  4305 E KeepSync: 	... 10 more
09-12 12:43:41.199  3042  4305 W KeepSync: Sync result 2
,09-12 12:43:41.236   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 309975, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:43:44.680  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:43:44.733  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-12 12:43:44.734  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 12:43:44.734  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:43:44.734  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:43:44.773  1495  1507 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 12:43:44.773  1495  1507 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 12:43:44.773  1495  1507 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 12:43:44.773  1495  1507 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-12 12:43:44.773  1495  1507 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-12 12:43:44.773  1495  1507 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-12 12:43:44.773  1495  1507 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 12:43:44.782  3535  3566 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 12:43:44.782  3535  3566 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-12 12:43:44.782  3535  3566 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-12 12:43:44.782  3535  3566 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-12 12:43:44.782  3535  3566 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-12 12:43:44.782  3535  3566 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-12 12:43:44.782  3535  3566 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 12:44:11.614  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:44:11.615  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:44:11.674  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:44:11.674  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 12:44:11.674  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:44:11.674  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:44:11.705  2999  4316 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:44:11.705  2999  4316 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:44:11.705  2999  4316 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	... 12 more
09-12 12:44:11.705  2999  4316 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at fal.a(PG:38)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:44:11.705  2999  4316 E HttpOperation: 	... 14 more
,09-12 12:44:11.820  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:44:11.820  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:44:11.820  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:44:11.820  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:44:11.838  2999  4316 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:44:11.838  2999  4316 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at hec.a(PG:42)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at hee.a(PG:102)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at czr.a(PG:65)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at kka.a(PG:108)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at czq.run(PG:1686)
,09-12 12:44:11.838  2999  4316 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:44:11.838  2999  4316 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	... 15 more
09-12 12:44:11.838  2999  4316 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at fal.a(PG:38)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:44:11.838  2999  4316 E HttpOperation: 	... 17 more
,09-12 12:44:11.838  2999  4316 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 12:44:11.838  2999  4316 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	... 15 more
09-12 12:44:11.838  2999  4316 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:44:11.838  2999  4316 E ExperimentLoader: 	... 17 more
,09-12 12:44:11.985   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 340353, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:44:45.921  3595  4319 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:44:45.941  3595  4320 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:44:45.952  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:44:45.957  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:44:46.015  1495  2016 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:44:46.015  1495  2016 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 12:44:46.015  1495  2016 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:44:46.016  1495  2016 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:44:46.061  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:44:46.062  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:44:46.092  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 12:44:46.092  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:44:46.092  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:44:46.092  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:44:46.109  3595  4320 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:44:46.110  3595  4319 E BooksSync: Soft error
09-12 12:44:46.110  3595  4319 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:44:46.110  3595  4319 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:44:46.110  3595  4319 E BooksSync: Sync error
09-12 12:44:46.110  3595  4319 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:44:46.110  3595  4319 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:44:46.110  3595  4319 I BooksSync: Finished books sync
,09-12 12:44:46.114   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 402907, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:45:17.390  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:45:17.394  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:45:17.441  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:45:17.441  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 12:45:17.441  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:45:17.441  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:45:17.471  2999  4324 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:45:17.471  2999  4324 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:45:17.471  2999  4324 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	... 12 more
09-12 12:45:17.471  2999  4324 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at fal.a(PG:38)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:45:17.471  2999  4324 E HttpOperation: 	... 14 more
,09-12 12:45:17.560  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:45:17.560  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:45:17.561  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:45:17.561  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:45:17.589  2999  4324 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:45:17.589  2999  4324 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at hec.a(PG:42)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at hee.a(PG:102)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at czr.a(PG:65)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at kka.a(PG:108)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:45:17.589  2999  4324 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	... 15 more
09-12 12:45:17.589  2999  4324 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at fal.a(PG:38)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:45:17.589  2999  4324 E HttpOperation: 	... 17 more
,09-12 12:45:17.589  2999  4324 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 12:45:17.589  2999  4324 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	... 15 more
09-12 12:45:17.589  2999  4324 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:45:17.589  2999  4324 E ExperimentLoader: 	... 17 more
,09-12 12:45:17.748   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 434050, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:45:44.771  1495  2233 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 12:45:48.296  3042  4327 V KeepSync: Connecting to GoogleApiClient
09-12 12:45:48.297   872  2041 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:45:48.360  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:45:48.364  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:45:48.400  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 12:45:48.400  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 12:45:48.400  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:45:48.400  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:45:48.423  1713  4328 V BaseAuthAsyncOperation: access token request failed
09-12 12:45:48.425  3042  4327 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:45:48.489  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 12:45:48.489  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 12:45:48.489  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:45:48.489  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:45:48.513  3042  4327 E KeepSync: IOException
09-12 12:45:48.513  3042  4327 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:45:48.513  3042  4327 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:45:48.513  3042  4327 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:45:48.513  3042  4327 E KeepSync: 	... 10 more
09-12 12:45:48.513  3042  4327 W KeepSync: Sync result 2
,09-12 12:45:48.524   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 465234, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:46:55.576  3595  4335 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:46:55.600  3595  4336 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:46:55.612  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:46:55.619  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:46:55.648  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:46:55.648  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:46:55.648  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:46:55.649  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:46:55.682  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:46:55.685  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:46:55.721  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:46:55.721  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 12:46:55.721  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:46:55.721  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:46:55.740  3595  4336 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 12:46:55.741  3595  4335 E BooksSync: Soft error
09-12 12:46:55.741  3595  4335 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:46:55.741  3595  4335 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:46:55.742  3595  4335 E BooksSync: Sync error
09-12 12:46:55.742  3595  4335 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:46:55.742  3595  4335 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:46:55.742  3595  4335 I BooksSync: Finished books sync
,09-12 12:46:55.748   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 532580, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:47:28.058  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:47:28.060  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:47:28.094  1495  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:47:28.094  1495  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 12:47:28.094  1495  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:47:28.095  1495  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:47:28.111  2999  4339 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:47:28.111  2999  4339 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:47:28.111  2999  4339 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	... 12 more
09-12 12:47:28.111  2999  4339 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at fal.a(PG:38)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:47:28.111  2999  4339 E HttpOperation: 	... 14 more
,09-12 12:47:28.175  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:47:28.175  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:47:28.176  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:47:28.176  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:47:28.195  2999  4339 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:47:28.195  2999  4339 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at hec.a(PG:42)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at hee.a(PG:102)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at czr.a(PG:65)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at kka.a(PG:108)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:47:28.195  2999  4339 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	... 15 more
09-12 12:47:28.195  2999  4339 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at fal.a(PG:38)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:47:28.195  2999  4339 E HttpOperation: 	... 17 more
09-12 12:47:28.195  2999  4339 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
,09-12 12:47:28.195  2999  4339 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	... 15 more
09-12 12:47:28.195  2999  4339 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:47:28.195  2999  4339 E ExperimentLoader: 	... 17 more
,09-12 12:47:28.366   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 564806, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:48:25.681  3535  3535 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-12 12:48:25.703  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:48:25.718  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:48:25.721  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:48:25.805  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-12 12:48:25.806  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 12:48:25.806  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:48:25.807  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:48:25.872  3535  3535 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 12:48:25.895  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:48:25.972  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 12:48:25.972  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 12:48:25.973  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:48:25.973  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:48:26.065  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:48:26.136  1495  2016 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 12:48:26.137  1495  2016 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 12:48:26.137  1495  2016 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:48:26.138  1495  2016 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:48:26.198  3535  3535 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 12:48:26.530  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:48:26.602  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 12:48:26.602  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 12:48:26.603  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:48:26.603  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:48:26.667  3535  3535 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
09-12 12:48:26.669  3535  3535 D Finsky  : [1] WearSupportService.startHygiene: disabled
09-12 12:48:26.671  3535  3535 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-12 12:48:26.677  3535  3589 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-12 12:48:26.680  3535  3535 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,09-12 12:48:41.463  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:48:41.472  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 12:48:41.474  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:48:41.541  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:48:41.541  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 12:48:41.541  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:48:41.541  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:48:41.575  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 12:48:41.575  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 12:48:41.576  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-12 12:49:01.939  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:49:01.956  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:49:01.963  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:49:02.043  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:49:02.044  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:49:02.044  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:49:02.045  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:49:02.116  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:49:02.117  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 12:49:02.119  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-12 12:49:22.449  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:49:22.462  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:49:22.468  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:49:22.536  1495  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:49:22.537  1495  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:49:22.537  1495  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:49:22.538  1495  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:49:22.584  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:49:22.585  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 12:49:22.586  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-12 12:49:42.867  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:49:42.878  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:49:42.884  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:49:42.945  1495  2016 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:49:42.946  1495  2016 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:49:42.946  1495  2016 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:49:42.946  1495  2016 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:49:42.995  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:49:42.995  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 12:49:42.997  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 12:50:03.352  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:50:03.369  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:50:03.375  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:50:03.458  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:50:03.459  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:50:03.460  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:50:03.460  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:50:03.533  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:50:03.536  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 12:50:03.537  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 12:50:23.866  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:50:23.878  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:50:23.885  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:50:23.949  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:50:23.949  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:50:23.950  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:50:23.950  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:50:24.001  3535  3535 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:50:24.002  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 12:50:24.003  3535  3535 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 12:52:46.448   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=883517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:53:04.021   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=901090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:53:11.487   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=908557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:53:29.087   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=926157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:53:36.554   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=933623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:53:54.154   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=951224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:54:01.647   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=958717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:54:19.221   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=976290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:54:26.687   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=983757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:54:44.287   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1001357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:54:51.754   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1008824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:55:09.354   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1026424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:55:16.821   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1033890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:55:34.407   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1051477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:55:41.888   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1058957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:55:59.487   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1076557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:56:06.954   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1084024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:56:24.554   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1101624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:56:32.021   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1109090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:56:49.621   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1126690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:56:57.114   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1134183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:57:14.727   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1151797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:57:22.207   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1159277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:57:39.794   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1176863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:57:52.368   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1189437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:58:04.861   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1201930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:58:17.434   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1214503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:58:20.931   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,09-12 12:58:29.914   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1226984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:58:42.474   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1239543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:58:54.981   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1252050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:58:59.722  1713  4379 I EventLogService: Opted in for usage reporting
,09-12 12:58:59.723  1713  4379 I EventLogService: Aggregate from 1473676139524 (log), 1473676139524 (data)
,09-12 12:58:59.779  1713  4379 W EventLogAggregator: Unknown tag: snet_gcore
,09-12 12:58:59.779  1713  4379 W EventLogAggregator: Unknown tag: snet_launch_service
,09-12 12:58:59.912  1713  4379 I ServiceDumpSys: dumping service [account]
,09-12 12:59:32.634   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1289704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:59:45.114   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1302184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:59:57.648   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1314717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:00:10.194   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1327263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:00:22.767   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1339837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:00:35.261   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1352330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:00:47.807   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1364877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:01:00.314   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1377384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:01:12.848   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1389917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:01:25.381   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1402450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:01:37.914   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1414983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:01:50.434   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1427504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:02:02.981   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1440050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:02:15.501   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1452570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:02:28.047   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1465117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:02:40.568   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1477637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:02:53.114   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1490184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:03:05.621   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1502690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:03:12.127   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1509197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:03:30.687   872  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1527757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms),09-12 13:03:33.858  4394  4394 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 13:03:33.863  4394  4394 D AndroidRuntime: CheckJNI is OFF
09-12 13:03:33.906  4394  4394 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 13:03:33.953  4394  4394 I Radio-JNI: register_android_hardware_Radio DONE
09-12 13:03:33.976  4394  4394 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-12 13:03:33.989   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-12 13:03:33.990   872   885 I ActivityManager: Killing 3791:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-12 13:03:34.117   872   895 W PackageSettings: Skipping PackageSetting{aa59d7d com.example.hello/10273} due to missing metadata
09-12 13:03:34.130   872  1403 I WindowState: WIN DEATH: Window{a897497 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 13:03:34.130   872  1313 D WifiService: Client connection lost with reason: 4
09-12 13:03:34.131   872  1679 D GraphicsStats: Buffer count: 2
09-12 13:03:34.186   872   895 I art     : Starting a blocking GC Explicit
09-12 13:03:34.204   872   885 E libprocessgroup: failed to kill 1 processes for processgroup 3791
09-12 13:03:34.205   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-12 13:03:34.205   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-12 13:03:34.205   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-12 13:03:34.205   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 13:03:34.205   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:03:34.205   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:03:34.205   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:03:34.205   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 13:03:34.206   872   885 I ActivityManager:   Force finishing activity ActivityRecord{a1a818c u0 com.test.thalitest/.MainActivity t4}
09-12 13:03:34.213   872  2173 W ActivityManager: Spurious death for ProcessRecord{8a138ad 0:com.test.thalitest/u0a0}, curProc for 3791: null
09-12 13:03:34.250   872   895 I art     : Explicit concurrent mark sweep GC freed 50324(4MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 29MB/44MB, paused 924us total 59.831ms
09-12 13:03:34.275   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-12 13:03:34.279   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-12 13:03:34.283  4394  4394 I art     : System.exit called, status: 0
09-12 13:03:34.283  4394  4394 I AndroidRuntime: VM exiting with result code 0.
09-12 13:03:34.293   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-12 13:03:34.298  4180  4180 D BluetoothMapAppObserver: onReceive
09-12 13:03:34.298  4180  4180 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-12 13:03:34.301   872  1301 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-12 13:03:34.309  1863  2257 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 13:03:34.310  3660  3660 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-12 13:03:34.331  1895  1895 I Keyboard.Facilitator: resetDictionaries() : en_US
09-12 13:03:34.333  1895  4408 I Keyboard.Facilitator.DecoderInitializer: run()
09-12 13:03:34.361  1895  4408 I Decoder : createOrResetDecoder
09-12 13:03:34.361  1986  1986 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-12 13:03:34.365   872   882 I ActivityManager: Start proc 4410:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-12 13:03:34.381  1495  1495 I ConfigService: onCreate
09-12 13:03:34.399  1895  4408 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-12 13:03:34.410   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 13:03:34.443   872  2214 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3791 uid 10000
09-12 13:03:34.444  1895  1895 I Keyboard.Facilitator: onFinishInput()
09-12 13:03:34.445  2008  2091 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-12 13:03:34.445   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-12 13:03:34.446   872   884 E PackageManager: Failed to write settings, restoring backup
09-12 13:03:34.446   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 13:03:34.446   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 13:03:34.446   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 13:03:34.446   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 13:03:34.446   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 13:03:34.446   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:03:34.446   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:03:34.446   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:03:34.450   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-12 13:03:34.450   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 13:03:34.450   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:03:34.450   872   885 E DropBoxManagerService: 	... 13 more
09-12 13:03:34.454  4410  4410 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-12 13:03:34.460   872   883 I ActivityManager: Start proc 4423:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-12 13:03:34.461  2008  2091 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 13:03:34.461  2008  2091 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2008
09-12 13:03:34.461  2008  2091 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:03:34.461  2008  2091 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:03:34.463   872  2007 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 13:03:34.463   872  4429 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:03:34.463   872  4429 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:03:34.463   872  4429 E DropBoxManagerService: 	... 5 more
09-12 13:03:34.467  2008  2091 I Process : Sending signal. PID: 2008 SIG: 9
09-12 13:03:34.483  1895  4408 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-12 13:03:34.485  1895  4408 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-12 13:03:34.485  1895  4408 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-12 13:03:34.487  1895  4408 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-12 13:03:34.487  1895  4408 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 13:03:34.490  1895  4408 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-12 13:03:34.490  1895  4408 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 13:03:34.496  1895  4408 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 13:03:34.507  1895  4408 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 13:03:34.507  1895  4408 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-12 13:03:34.507  1895  4408 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-12 13:03:34.507  1895  4408 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 13:03:34.507  1895  4408 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-12 13:03:34.655   872  1374 D GraphicsStats: Buffer count: 1
09-12 13:03:34.655   872  1680 I WindowState: WIN DEATH: Window{5b6bde5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-12 13:03:34.666   872   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2008) has died
09-12 13:03:34.666   872   882 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-12 13:03:34.668   872   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-12 13:03:34.686   872   885 I ActivityManager: Start proc 4443:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 13:03:34.691  4410  4410 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-12 13:03:34.711  1713  4442 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-12 13:03:34.712  1713  4442 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-12 13:03:34.727   872  2173 I ActivityManager: Start proc 4455:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-12 13:03:34.742  4410  4458 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:03:34.748  4443  4443 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:03:34.748  4443  4443 D AndroidRuntime: Shutting down VM
09-12 13:03:34.758  4443  4443 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:03:34.758  4443  4443 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4443
09-12 13:03:34.758  4443  4443 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:03:34.758  4443  4443 E AndroidRuntime: 	... 10 more
09-12 13:03:34.760   872  1936 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 13:03:34.761  4443  4443 I Process : Sending signal. PID: 4443 SIG: 9
09-12 13:03:34.761   872  4468 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:03:34.761   872  4468 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:03:34.761   872  4468 E DropBoxManagerService: 	... 5 more
09-12 13:03:34.770  1713  4442 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-12 13:03:34.771  1713  4442 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:03:34.772  4410  4458 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:03:34.773  4455  4455 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-12 13:03:34.772  4410  4458 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 13:03:34.772  4410  4458 E AndroidRuntime: Process: android.process.acore, PID: 4410
09-12 13:03:34.772  4410  4458 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:03:34.772  4410  4458 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:03:34.778  4410  4458 I Process : Sending signal. PID: 4410 SIG: 9
09-12 13:03:34.779   872  4469 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:03:34.779   872  4469 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:03:34.779   872  4469 E DropBoxManagerService: 	... 5 more
09-12 13:03:34.784   279   279 E lowmemorykiller: Error writing /proc/4410/oom_score_adj; errno=22
09-12 13:03:34.786   279   279 E lowmemorykiller: Error writing /proc/4410/oom_score_adj; errno=22
09-12 13:03:34.795  1495  1495 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-12 13:03:34.798  1495  1495 D AndroidRuntime: Shutting down VM
09-12 13:03:34.798   872   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4443) has died
09-12 13:03:34.798  1495  1495 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:03:34.798  1495  1495 E AndroidRuntime: Process: com.google.process.gapps, PID: 1495
09-12 13:03:34.798  1495  1495 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 13:03:34.798  1495  1495 E AndroidRuntime: 	... 8 more
09-12 13:03:34.799   872   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-12 13:03:34.807   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
