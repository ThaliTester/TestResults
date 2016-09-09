#### Test 846390997f1f1fd_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 14:24:27.237  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:24:27.261  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 14:24:27.263  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 14:24:27.294  1499  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 14:24:27.294  1499  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 14:24:27.294  1499  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:24:27.294  1499  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 14:24:27.317  3554  3554 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 14:24:27.318  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 14:24:27.318  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-09 14:24:27.814  3835  3835 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 14:24:27.819  3835  3835 D AndroidRuntime: CheckJNI is OFF
09-09 14:24:27.862  3835  3835 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 14:24:27.911  3835  3835 I Radio-JNI: register_android_hardware_Radio DONE
09-09 14:24:27.933  3835  3835 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 14:24:27.937   873  1964 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 14:24:27.962  2021  2032 W SearchService: Abort, client detached.
09-09 14:24:27.973  2021  2021 I HotwordDetector: Closing mic
09-09 14:24:27.974  2021  2336 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@23e3184
09-09 14:24:27.974  2021  2351 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 14:24:27.997  3835  3835 D AndroidRuntime: Shutting down VM
09-09 14:24:28.013   873  1983 I ActivityManager: Start proc 3844:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 14:24:28.038   376  2353 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 14:24:28.040   376  2353 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 14:24:28.044   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 14:24:28.046  2021  2343 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 14:24:28.046  2021  2350 I MicroRecognitionRnrImpl: Detection finished
09-09 14:24:28.083  3844  3844 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 14:24:28.104  3844  3844 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 14:24:28.112  3844  3844 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 118-121)
09-09 14:24:28.112  3844  3844 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:24:28.127  3844  3844 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9c4ac08}
09-09 14:24:28.128  3844  3844 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:24:28.129  3844  3844 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 14:24:28.136  3844  3844 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 14:24:28.138  3844  3844 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 14:24:28.163  3844  3844 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 14:24:28.179  3844  3844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 14:24:28.179  3844  3844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 14:24:28.179  3844  3844 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 14:24:28.179  3844  3844 I Adreno  : Build Date                       : 10/20/15
09-09 14:24:28.179  3844  3844 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 14:24:28.179  3844  3844 I Adreno  : Local Branch                     : M14
09-09 14:24:28.179  3844  3844 I Adreno  : Remote Branch                    : 
09-09 14:24:28.179  3844  3844 I Adreno  : Remote Branch                    : 
09-09 14:24:28.179  3844  3844 I Adreno  : Reconstruct Branch               : 
,09-09 14:24:28.250   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8576325:true
,09-09 14:24:28.292  3844  3844 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 14:24:28.307  3844  3844 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 14:24:28.363  3844  3882 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 14:24:28.374  3844  3869 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 14:24:28.423  3844  3882 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 14:24:28.497   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +498ms
,09-09 14:24:28.514  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-09 14:24:28.568  3844  3844 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3844
,09-09 14:24:28.788  3844  3844 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 14:24:28.875   873  1394 I ActivityManager: Killing 3251:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 14:24:28.912   873  1394 I ActivityManager: Killing 3002:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-09 14:24:28.934  3844  3885 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1695811280
,09-09 14:24:28.946  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 14:24:28.946  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 14:24:28.946  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 14:24:28.946  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 14:24:28.946  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 14:24:28.946  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7020b0c added. We now have 1 listener(s)
09-09 14:24:28.951  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 14:24:28.953  3844  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:24:28.954  3844  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:24:28.954  3844  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 14:24:28.958  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ec75b added. We now have 1 listener(s)
09-09 14:24:28.958  3844  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:24:28.961   873  1307 D WifiService: New client listening to asynchronous messages
,09-09 14:24:28.962  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 14:24:28.962  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 14:24:28.963  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 14:24:28.963  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-09 14:24:28.963  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 14:24:28.968  3844  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:24:28.968  3844  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 14:24:28.973  3844  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 14:24:28.973  3844  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:28.973  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:28.973  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:28.973  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:28.973  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:28.973  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:28.973  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:28.973  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:24:28.973  3844  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 14:24:28.973  3844  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:24:28.974  3844  3885 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 14:24:29.072  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:29.076  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:29.080  3844  3844 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 14:24:29.801  3844  3895 W jxcore-log: Initializing JXcore engine
,09-09 14:24:29.801  3844  3895 W jxcore-log: JXcore engine is ready
,09-09 14:24:29.837  3895  3895 W Thread-338: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 14:24:29.837  3895  3895 W Thread-338: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11741]" dev="sockfs" ino=11741 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 14:24:29.837  3895  3895 W Thread-338: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 14:24:29.837  3895  3895 W Thread-338: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25226]" dev="sockfs" ino=25226 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-09 14:24:29.856  3844  3895 W jxcore-log: Starting JXcore engine
,09-09 14:24:29.934  3844  3895 W jxcore-log: Platform android
09-09 14:24:29.934  3844  3895 W jxcore-log: 
,09-09 14:24:29.934  3844  3895 W jxcore-log: Process ARCH arm
09-09 14:24:29.934  3844  3895 W jxcore-log: 
,09-09 14:24:30.176  3844  3895 I jxcore-log: JXcore Cordova bridge is ready!
09-09 14:24:30.176  3844  3895 I jxcore-log: 
09-09 14:24:30.177  3844  3895 W jxcore-log: JXcore engine is started
,09-09 14:24:30.185  3844  3885 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 14:24:30.189  3844  3844 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 14:24:31.700   873  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 14:24:37.087  3626  3902 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 14:24:37.110  3626  3904 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 14:24:37.122  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:24:37.123  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:24:37.148  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 14:24:37.148  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 14:24:37.148  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:24:37.148  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:24:37.174  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:24:37.175  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:24:37.209  1499  2999 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 14:24:37.209  1499  2999 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 14:24:37.209  1499  2999 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:24:37.210  1499  2999 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:24:37.227  3626  3904 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 14:24:37.229  3626  3902 E BooksSync: Soft error
09-09 14:24:37.229  3626  3902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 14:24:37.229  3626  3902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 14:24:37.229  3626  3902 E BooksSync: Sync error
09-09 14:24:37.229  3626  3902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 14:24:37.229  3626  3902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 14:24:37.229  3626  3902 I BooksSync: Finished books sync
,09-09 14:24:37.233   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127874, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 14:24:40.340  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 14:24:40.340  3844  3895 I jxcore-log: 
,09-09 14:24:40.343  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 14:24:40.343  3844  3895 I jxcore-log: 
,09-09 14:24:40.355  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:40.355  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:40.355  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:40.355  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:40.355  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:40.355  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:40.355  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:40.355  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:24:40.363  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:24:40.365  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 14:24:40.365  3844  3895 I jxcore-log: 
,09-09 14:24:40.367  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 14:24:40.367  3844  3895 I jxcore-log: 
,09-09 14:24:40.860  3844  3895 D executeNativeTests: Running unit tests
,09-09 14:24:40.917  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 14:24:40.918  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc added. We now have 2 listener(s)
,09-09 14:24:40.919  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:24:40.919  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:24:40.919  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:24:40.919  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:24:40.919  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 added. We now have 2 listener(s)
09-09 14:24:40.919  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:40.920  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 14:24:40.927  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:24:40.948  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:40.948  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:40.948  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:40.948  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:40.948  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:40.948  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:40.948  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:40.948  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:24:40.953  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:24:40.954  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:24:40.960  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 14:24:40.962  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 14:24:40.963  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 14:24:40.965  3844  3895 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 14:24:40.965  3844  3895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 14:24:40.965  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 14:24:40.965  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 14:24:40.965  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 14:24:40.966  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:24:40.966  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 14:24:40.966  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 14:24:40.966  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:24:40.966  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:24:40.966  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:40.967  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 14:24:40.967  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc removed from the list
09-09 14:24:40.967  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:40.967  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 removed from the list
09-09 14:24:40.968  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:40.969  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:40.969  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:40.971  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:40.971  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:40.972  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:40.972  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:40.972  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:40.972  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:40.973  3844  3895 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 14:24:40.974  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:40.974  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:40.974  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:40.974  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:40.974  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:40.974  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:40.974  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:40.974  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:40.974  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:40.977  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:40.978  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:40.978  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:40.978  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:40.978  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:40.978  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:40.979  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:40.979  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:40.979  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:40.979  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: cl,oseAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 14:24:40.986  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 14:24:40.987  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 14:24:40.988  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 14:24:40.988  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 14:24:40.988  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:40.988  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:40.988  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:40.988  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:40.988  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:40.988  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:40.988  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:40.988  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:40.988  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:40.988  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:40.989  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:40.989  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:40.989  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:40.989  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:40.990  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:40.990  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:40.990  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:40.991  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:40.991  3844  3895 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:24:40.994  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:40.999  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:40.999  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:40.999  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:40.999  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:40.999  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:40.999  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:40.999  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:40.999  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:41.001  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:41.001  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:24:41.001  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:24:41.001  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:24:41.001  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:24:41.002  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:41.002  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:24:41.008  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:24:41.008  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:24:41.009  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:41.012  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:41.012  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:24:41.015  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 14:24:41.015  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 14:24:41.020  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-09 14:24:41.023  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 14:24:41.024  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 14:24:41.024  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:24:41.024  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 14:24:41.025  3844  3895 D BluetoothAdapter: STATE_ON
09-09 14:24:41.031  2713  2725 D BtGatt.GattService: registerClient() - UUID=6af16f7c-b451-4fc7-ba43-bdd02165d491
,09-09 14:24:41.032  2713  2764 D BtGatt.GattService: onClientRegistered() - UUID=6af16f7c-b451-4fc7-ba43-bdd02165d491, clientIf=5
09-09 14:24:41.032  3844  3855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 14:24:41.034  2713  2727 D BtGatt.GattService: start scan with filters
09-09 14:24:41.038  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 14:24:41.038  2713  2768 D BtGatt.ScanManager: handling starting scan
09-09 14:24:41.038  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:24:41.039  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:24:41.039  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 14:24:41.040  2713  2768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
09-09 14:24:41.042  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:24:41.042  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 14:24:41.042  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:24:41.044  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 14:24:41.048  3844  3895 I io.jxcore.node.ConnectionHelper: start: OK
09-09 14:24:41.051  2713  2764 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 14:24:41.051  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.052  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.052  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 14:24:41.052  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.052  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 14:24:41.052  2713  2768 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 14:24:41.052  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.052  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 14:24:41.052  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:24:41.052  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:24:41.052  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:24:41.052  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:24:41.053  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:24:41.053  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:24:41.054  3844  3895 D BluetoothAdapter: STATE_ON
09-09 14:24:41.055  2713  2725 D BtGatt.GattService: stopScan() - queue size =1
09-09 14:24:41.055  2713  2727 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 14:24:41.056  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:41.056  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 14:24:41.056  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 14:24:41.056  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:24:41.056  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 14:24:41.058  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:24:41.058  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 14:24:41.058  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:24:41.058  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:24:41.059  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:41.061  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.061  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.061  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:41.061  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.061  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:41.061  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.061  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.061  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.061  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.061  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:41.061  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:24:41.062  3844  3895 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:24:41.063  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:41.068  2713  2764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:24:41.068  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.069  2713  2768 D BtGatt.ScanManager: Starting BLE batch scan
09-09 14:24:41.069  2713  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 14:24:41.069  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:41.069  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.069  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.069  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:41.069  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:41.069  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:41.069  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:41.069  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:24:41.071  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:24:41.071  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:24:41.072  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:24:41.072  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:24:41.072  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 14:24:41.072  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:41.072  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:24:41.075  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:41.076  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:24:41.076  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:24:41.078  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:41.079  2713  2764 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:24:41.079  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.081  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 14:24:41.082  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 14:24:41.082  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:24:41.086  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 14:24:41.086  2713  2764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:24:41.086  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.086  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:24:41.086  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 14:24:41.087  3844  3895 D BluetoothAdapter: STATE_ON
,09-09 14:24:41.089  2713  2727 D BtGatt.GattService: registerClient() - UUID=5435ef14-d666-4cf9-b8e4-63ea8fdd399a
,09-09 14:24:41.090  2713  2764 D BtGatt.GattService: onClientRegistered() - UUID=5435ef14-d666-4cf9-b8e4-63ea8fdd399a, clientIf=5
,09-09 14:24:41.090  3844  3855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 14:24:41.090  2713  2930 D BtGatt.GattService: start scan with filters
,09-09 14:24:41.093  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 14:24:41.093  2713  2764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:24:41.094  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.094  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 14:24:41.094  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:24:41.094  2713  2768 D BtGatt.ScanManager: stopping BLe Batch
09-09 14:24:41.094  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 14:24:41.096  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:24:41.096  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 14:24:41.096  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:24:41.097  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 14:24:41.100  3844  3895 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 14:24:41.100  2713  2764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:24:41.100  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.100  2713  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 14:24:41.103  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:24:41.103  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 14:24:41.103  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 14:24:41.104  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 14:24:41.104  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.104  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 14:24:41.104  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:24:41.104  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:24:41.104  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:24:41.104  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:24:41.104  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 14:24:41.104  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:24:41.105  3844  3895 D BluetoothAdapter: STATE_ON
09-09 14:24:41.106  2713  2930 D BtGatt.GattService: stopScan() - queue size =0
09-09 14:24:41.106  2713  2912 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 14:24:41.107  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 14:24:41.107  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 14:24:41.107  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 14:24:41.107  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:24:41.107  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 14:24:41.108  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 14:24:41.108  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 14:24:41.108  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:24:41.108  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:24:41.109  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:24:41.110  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:24:41.110  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:41.110  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:41.110  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.110  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:24:41.110  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:41.110  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.110  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:41.110  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.110  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.111  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.111  2713  2764 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-09 14:24:41.111  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:24:41.111  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.111  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.112  2713  2764 D BtGatt.GattService: current time is 133121926968
09-09 14:24:41.112  2713  2764 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 14:24:41.112  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:24:41.112  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.113  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.113  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.113  2713  2768 D BtGatt.ScanManager: handling starting scan
09-09 14:24:41.113  3844  3895 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 14:24:41.114  2713  2764 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 14:24:41.115  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:41.114  2713  2764 E BtGatt.ContextMap: Context not found for ID 5
,09-09 14:24:41.121  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:41.121  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.121  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.121  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:41.121  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:41.121  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:41.121  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:41.121  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:24:41.123  2713  2764 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 14:24:41.123  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.123  2713  2768 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 14:24:41.124  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:41.124  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:24:41.125  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:24:41.125  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 14:24:41.126  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 14:24:41.126  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:41.126  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:24:41.126  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:41.130  2713  2764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:24:41.130  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:24:41.131  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:24:41.131  2713  2768 D BtGatt.ScanManager: Starting BLE batch scan
09-09 14:24:41.131  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:24:41.131  2713  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 14:24:41.131  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:41.136  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:24:41.137  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 14:24:41.137  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 14:24:41.142  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 14:24:41.142  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 14:24:41.142  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 14:24:41.143  3844  3895 D BluetoothAdapter: STATE_ON
09-09 14:24:41.143  2713  2764 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:24:41.143  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:24:41.145  2713  2725 D BtGatt.GattService: registerClient() - UUID=8b9cadad-5513-43d4-a607-6b8dd89464e4
,09-09 14:24:41.146  2713  2764 D BtGatt.GattService: onClientRegistered() - UUID=8b9cadad-5513-43d4-a607-6b8dd89464e4, clientIf=5
,09-09 14:24:41.147  3844  3855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 14:24:41.147  2713  2930 D BtGatt.GattService: start scan with filters
,09-09 14:24:41.150  2713  2764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:24:41.150  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 14:24:41.150  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:24:41.150  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:24:41.150  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:24:41.151  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 14:24:41.154  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:24:41.154  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:24:41.154  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 14:24:41.156  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 14:24:41.159  3844  3895 I io.jxcore.node.ConnectionHelper: start: OK
09-09 14:24:41.159  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:24:41.159  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 14:24:41.159  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.159  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 14:24:41.159  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.159  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 14:24:41.159  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:24:41.159  2713  2764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:24:41.159  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 14:24:41.159  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:24:41.159  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 14:24:41.159  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.160  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:24:41.160  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:24:41.160  2713  2768 D BtGatt.ScanManager: stopping BLe Batch
09-09 14:24:41.161  3844  3895 D BluetoothAdapter: STATE_ON
09-09 14:24:41.161  2713  2930 D BtGatt.GattService: stopScan() - queue size =0
09-09 14:24:41.162  2713  2727 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 14:24:41.162  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:41.162  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 14:24:41.163  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 14:24:41.163  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:24:41.163  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 14:24:41.164  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:24:41.164  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 14:24:41.164  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:24:41.164  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:24:41.165  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:24:41.166  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:41.166  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:41.166  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:24:41.167  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.167  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 14:24:41.167  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.167  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.167  2713  2764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:24:41.168  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.168  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.168  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.168  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:41.168  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.168  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.168  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.168  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 14:24:41.168  2713  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 14:24:41.168  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.171  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.171  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:24:41.172  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.172  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.172  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.172  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.173  3844  3895 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 14:24:41.174  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:24:41.174  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.174  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.175  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.175  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.175  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.175  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.175  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.175  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.175  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.175  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.175  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.175  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.175  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:24:41.176  2713  2764 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 14:24:41.177  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.177  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.177  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.177  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.177  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
,09-09 14:24:41.178  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 14:24:41.178  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:24:41.178  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.178  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.179  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.179  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:24:41.179  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.179  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.179  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.179  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.179  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.179  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:24:41.179  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.179  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.179  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.180  2713  2768 D BtGatt.ScanManager: handling starting scan
09-09 14:24:41.181  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.181  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.181  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.181  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.181  3844  3895 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-09 14:24:41.182  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.182  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.182  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 14:24:41.182  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.182  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.182  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.182  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.182  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.183  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.183  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.183  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:24:41.183  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.183  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.183  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.184  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.184  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.184  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.184  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
,09-09 14:24:41.185  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 14:24:41.185  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.185  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.185  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.186  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:24:41.186  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.186  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.186  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.186  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:41.186  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.186  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 14:24:41.186  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.186  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.186  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.186  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:24:41.187  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:24:41.188  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:24:41.188  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:41.188  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
,09-09 14:24:41.188  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 14:24:41.189  2713  2764 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 14:24:41.189  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.189  2713  2768 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 14:24:41.190  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 14:24:41.190  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:24:41.190  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:24:41.190  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 14:24:41.190  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:24:41.191  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:24:41.191  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.191  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.192  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.192  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.192  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.193  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.193  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:41.193  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.193  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.193  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:24:41.193  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:24:41.193  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.193  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.194  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:24:41.194  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.194  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:41.194  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.195  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:41.195  3844  3895 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 14:24:41.195  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 14:24:41.196  2713  2764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:24:41.196  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.197  2713  2768 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 14:24:41.197  2713  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 14:24:41.199  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:41.199  3844  3895 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 14:24:41.199  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 14:24:41.200  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 14:24:41.201  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 14:24:41.201  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 14:24:41.201  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 14:24:41.201  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 14:24:41.201  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 14:24:41.201  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-09 14:24:41.201  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 14:24:41.201  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 14:24:41.201  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 14:24:41.201  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 14:24:41.201  3844  3895 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:24:41.202  3844  3895 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 14:24:41.202  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:41.202  3844  3895 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-09 14:24:41.202  3844  3895 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 14:24:41.202  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:41.202  3844  3895 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:24:41.202  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 14:24:41.205  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 14:24:41.206  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-09 14:24:41.206  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 14:24:41.207  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 14:24:41.207  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 14:24:41.207  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-09 14:24:41.207  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:41.207  3844  3895 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 14:24:41.208  3844  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 402)
09-09 14:24:41.208  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:24:41.208  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.208  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.208  2713  2764 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:24:41.208  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.208  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:24:41.208  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.208  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.208  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 14:24:41.209  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.209  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.209  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
,09-09 14:24:41.209  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.209  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.209  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.209  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.209  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:24:41.210  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.210  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:24:41.210  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:41.210  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list,
,09-09 14:24:41.210  3844  3908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:24:41.211  3844  3895 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 14:24:41.211  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.211  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.211  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.212  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.212  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.212  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.212  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.212  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.212  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.212  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.212  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.212  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.212  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.212  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.213  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.213  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.213  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.213  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.213  3844  3895 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 14:24:41.213  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.214  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.214  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.214  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.214  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.214  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.214  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.C,onnectionManager@c1a06dc not in the list
09-09 14:24:41.214  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.214  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.214  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.214  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.214  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.214  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.214  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.215  2713  2764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:24:41.215  3844  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 402
09-09 14:24:41.215  3844  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 402)
09-09 14:24:41.215  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.215  2713  2908 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-09 14:24:41.216  3844  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 402)
09-09 14:24:41.216  3844  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 402)
09-09 14:24:41.217  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.217  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.217  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.217  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.218  3844  3895 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 14:24:41.218  3844  3895 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 14:24:41.218  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:24:41.219  3844  3895 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 14:24:41.219  3844  3895 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 14:24:41.219  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 14:24:41.219  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:24:41.219  3844  3895 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 14:24:41.219  3844  3895 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 14:24:41.219  3844  3895 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connecti,on to peer with ID 00:11:22:33:44:55
09-09 14:24:41.219  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:24:41.219  3844  3895 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 14:24:41.219  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.219  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.219  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.219  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.219  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.219  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.219  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.219  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.220  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.220  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.220  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.220  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.220  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.220  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.220  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.220  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.220  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.220  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.221  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.221  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.221  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.221  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.221  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.221  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.221  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.221  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.221  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.221  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.221  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.221  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.221  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.222  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.222  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.222  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.222  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.222  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.222  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.222  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.222  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.222  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.222  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.222  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.222  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.222  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.222  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.222  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.222  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.223  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.223  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.223  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.224  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.225  2713  2764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:24:41.225  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.226  2713  2768 D BtGatt.ScanManager: stopping BLe Batch
09-09 14:24:41.227  3844  3895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 14:24:41.227  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:41.228  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 14:24:41.228  3844  3895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 14:24:41.228  3844  3895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 14:24:41.229  3844  3844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 14:24:41.229  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 14:24:41.229  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:24:41.229  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.229  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 14:24:41.229  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 14:24:41.229  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 14:24:41.229  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.229  3844  3895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 14:24:41.229  3844  3844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 14:24:41.229  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.229  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.229  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:24:41.229  3844  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 14:24:41.229  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:24:41.230  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:24:41.230  3844  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 14:24:41.230  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.230  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.230  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:24:41.231  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:41.231  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:41.231  3844  3844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 14:24:41.231  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:24:41.231  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.231  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.231  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.231  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.231  2713  2764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:24:41.231  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.231  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.231  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.231  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.231  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.231  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.231  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.232  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.232  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.232  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.232  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.232  2713  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 14:24:41.232  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.232  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.232  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.232  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.232  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.233  3844  3895 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 14:24:41.234  3844  3895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 14:24:41.234  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:24:41.234  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:24:41.234  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.234  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.234  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.235  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.235  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.235  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.235  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.235  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.236  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.236  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.236  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.236  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.236  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.236  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.237  2713  2764 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 14:24:41.237  2713  2764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:24:41.238  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.238  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.238  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.238  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.240  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.240  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.240  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.241  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.241  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.241  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.241  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.241  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.241  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.241  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.241  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.241  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.241  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.241  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.242  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.242  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.242  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.242  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.242  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:41.242  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:41.242  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:41.242  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:41.243  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.243  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.243  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1a06dc not in the list
09-09 14:24:41.243  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.243  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.243  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:41.243  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.243  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.243  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:41.243  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:41.244  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:41.244  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:41.244  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:41.244  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5423e5 not in the list
09-09 14:24:41.244  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 14:24:41.244  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:24:41.244  3844  3895 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 14:24:41.244  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:24:41.245  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 14:24:41.245  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:24:41.246  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 14:24:41.246  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 14:24:41.246  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 14:24:41.246  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 14:24:41.247  3844  3895 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 14:24:41.247  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 14:24:41.247  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 14:24:41.247  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 14:24:41.247  3844  3895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 14:24:41.247  3844  3895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 14:24:41.247  3844  3895 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 14:24:41.247  3844  3895 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 14:24:41.248  3844  3895 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 14:24:41.248  3844  3895 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 14:24:41.248  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:24:41.248  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b3daa3f added. We now have 2 listener(s)
09-09 14:24:41.248  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:41.249  3844  3895 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 14:24:41.249   873  1944 D WifiService: setWifiEnabled: true pid=3844, uid=10000
09-09 14:24:41.250   873  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:24:41.250  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:24:41.250  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@edadf0c added. We now have 3 listener(s)
09-09 14:24:41.250  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:41.254  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:24:41.254  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26ed055 added. We now have 4 listener(s)
09-09 14:24:41.254  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:41.255  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:24:41.255  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@366ca6a added. We now have 5 listener(s)
09-09 14:24:41.255  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:41.257   873  1858 D WifiService: setWifiEnabled: false pid=3844, uid=10000
09-09 14:24:41.257   873  1858 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:24:41.261  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:41.262  2713  2760 D BluetoothAdapterState: Current state: ON, message: 23
09-09 14:24:41.262  2713  2760 D BluetoothAdapterProperties: Setting state to 13
09-09 14:24:41.262  2713  2760 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 14:24:41.263  2713  2760 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 14:24:41.263  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.263  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:41.263  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.263  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.263  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:41.263  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:41.263  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:41.263  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:41.263  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:41.263  2713  2760 I BluetoothAdapterState: Entering PendingCommandState
09-09 14:24:41.264  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.264  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:41.265  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:24:41.266  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:41.268  2713  2713 D BluetoothMapService: onReceive
09-09 14:24:41.268  2713  2713 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:41.268  2713  2713 D BluetoothMapService: STATE_TURNING_OFF
09-09 14:24:41.268  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:41.269  2713  2713 D BluetoothMapService: MAP Service closeService in
09-09 14:24:41.269  2713  2713 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 14:24:41.269  2713  2713 D ObexServerSockets0: shutdown(block = true)
09-09 14:24:41.270  2713  2932 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 14:24:41.271  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 14:24:41.271  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 14:24:41.272  2713  2908 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 14:24:41.272  2713  2933 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 14:24:41.273  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.273  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:41.273  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.273  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.273  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:41.273  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:41.273  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:41.273  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:41.273  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:41.273  2713  2713 I BtOppRfcommListener: stopping Accept Thread
09-09 14:24:41.273  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:24:41.273  2713  3471 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:41.274  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.274  2713  3471 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 14:24:41.274  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:41.275   873  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 14:24:41.275   873  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 14:24:41.275   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 14:24:41.275   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:24:41.275  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:41.283   873  2098 D DhcpClient: Clearing IP address
09-09 14:24:41.284   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:24:41.287   372   871 D CommandListener: Setting iface cfg
09-09 14:24:41.290  1499  2542 V NativeCrypto: Read error: ssl=0x9affcc00: I/O error during system call, Connection timed out
09-09 14:24:41.292  1499  2542 V NativeCrypto: SSL shutdown failed: ssl=0x9affcc00: I/O error during system call, Broken pipe
09-09 14:24:41.293   873   884 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-09 14:24:41.293   873  2101 D DhcpClient: Receive thread stopped
09-09 14:24:41.294   873  2090 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-09 14:24:41.296   873  2090 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-09 14:24:41.297   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-09 14:24:41.297   873   886 I ActivityManager: Start proc 3913:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-09 14:24:41.297   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-09 14:24:41.297  2713  2764 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:24:41.298   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 14:24:41.298  2713  2760 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 14:24:41.298   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 14:24:41.298   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-09 14:24:41.301  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:41.301  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:41.301  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.301  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.301  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:41.301  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:41.301  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:41.301  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:41.301  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:41.302  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:41.302  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:41.302  2713  2713 D HeadsetService: Received stop request...Stopping profile...
09-09 14:24:41.304   873  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 14:24:41.304  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.304  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:41.304  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.304  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.304  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:41.304  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:41.304  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:41.304  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:41.304  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:41.304   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 14:24:41.304  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:41.304  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:41.306   400   400 E Parcel  : Reading a NULL string not supported here.
09-09 14:24:41.307   873   873 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:41.307  1364  2058 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:41.307  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-09 14:24:41.308   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:24:41.310   873   873 D BluetoothHeadset: Proxy object disconnected
,09-09 14:24:41.311  1958  2102 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:41.311  2713  2713 D A2dpService: Received stop request...Stopping profile...
09-09 14:24:41.312   873   873 D BluetoothHeadset: Proxy object disconnected
,09-09 14:24:41.312  2713  2914 D A2dpStateMachine: Exit Disconnected: -1
09-09 14:24:41.314   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 14:24:41.316  1364  1364 D BluetoothA2dp: Proxy object disconnected
,09-09 14:24:41.316   873   873 D BluetoothA2dp: Proxy object disconnected
,09-09 14:24:41.317  2713  2713 V BluetoothAdapterState: isTurningOff()=true
,09-09 14:24:41.317  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:41.317  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:41.318  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.318   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 14:24:41.318  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:41.318  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.318  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.318  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:41.318  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:41.318  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:41.318  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:41.318  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:41.319   873  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 14:24:41.319  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:41.319  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:41.320  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:41.321  2713  2713 D HidService: Received stop request...Stopping profile...
,09-09 14:24:41.321  2713  2713 D HidService: Stopping Bluetooth HidService
09-09 14:24:41.321  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.321  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:41.321  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.321  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.321  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:41.321  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:41.321  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:41.321  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:41.321  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:41.322  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.322  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:41.324  1859  2292 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:24:41.324  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 14:24:41.324  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:24:41.324  2713  2764 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 14:24:41.324  2713  2904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:41.324  2713  2904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:41.324  2713  2904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:41.327  2713  2713 D HealthService: Received stop request...Stopping profile...
09-09 14:24:41.327  2713  2764 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-09 14:24:41.331  2713  2713 D PanService: Received stop request...Stopping profile...
,09-09 14:24:41.332  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-09 14:24:41.332  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:41.332  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:41.332  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:41.333  2713  2764 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 14:24:41.333  2713  2904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:41.333  2713  2904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:41.333  2713  2904 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 14:24:41.333  2713  2904 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:41.333  2713  2904 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:24:41.333  2713  2904 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:41.334  2713  2713 D BluetoothMapService: Received stop request...Stopping profile...
09-09 14:24:41.334  2713  2713 D BluetoothMapService: stop()
09-09 14:24:41.336  2713  2713 D BluetoothMapAppObserver: deinitObservers()
09-09 14:24:41.336  2713  2713 D BluetoothMapAppObserver: removeReceiver()
,09-09 14:24:41.338  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-09 14:24:41.338  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:41.338  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:41.338  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:41.339  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 14:24:41.339  2713  2764 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 14:24:41.339  1364  1364 D BluetoothInputDevice: Proxy object disconnected
,09-09 14:24:41.339  1364  1364 D HidProfile: Bluetooth service disconnected
09-09 14:24:41.339  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 14:24:41.340  1364  1364 D PanProfile: Bluetooth service disconnected
09-09 14:24:41.340  1364  1364 D BluetoothMap: Proxy object disconnected
09-09 14:24:41.340  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 14:24:41.340  1364  1364 D MapProfile: Bluetooth service disconnected
09-09 14:24:41.340  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-09 14:24:41.340  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:41.340  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:24:41.340  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:24:41.341  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 14:24:41.341  2713  2764 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 14:24:41.341  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:24:41.341  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-09 14:24:41.341  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:41.341  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:41.341  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:41.342  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 14:24:41.342  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 14:24:41.345  2713  2713 D BluetoothMapService: MAP Service closeService in
09-09 14:24:41.345  2713  2713 V BluetoothAdapterState: isTurningOff()=true
,09-09 14:24:41.345  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:41.345  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:41.345  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:41.346  2713  2713 D BluetoothMapService: cleanup()
09-09 14:24:41.346  2713  2760 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 14:24:41.346  2713  2713 D BluetoothMapService: MAP Service closeService in
09-09 14:24:41.346  2713  2760 D BluetoothAdapterProperties: Setting state to 15
09-09 14:24:41.346  2713  2760 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 14:24:41.346   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:24:41.346   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:41.347  2713  2760 I BluetoothAdapterState: Entering BleOnState
,09-09 14:24:41.347  1364  2058 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:41.347  1364  1377 D BluetoothPan: onBluetoothStateChange on: false
09-09 14:24:41.348   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:41.348  1958  2116 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:41.348   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:41.348  1364  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:24:41.349  1364  2058 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:24:41.349  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 14:24:41.350  1364  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:24:41.351  2713  2760 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 14:24:41.351  2713  2760 D BluetoothAdapterProperties: Setting state to 16
09-09 14:24:41.351  2713  2760 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 14:24:41.351  2713  2760 D BluetoothAdapterProperties: onBleDisable
,09-09 14:24:41.351  2713  2760 I BluetoothAdapterState: Entering PendingCommandState
09-09 14:24:41.352  2713  2761 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 14:24:41.353  2713  2904 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 14:24:41.353  2713  2904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:41.354  2713  2764 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:24:41.355  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.355  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:41.355  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.355  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.355  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:41.355  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:41.355  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:41.355  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:41.355  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:41.356  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:41.356  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:41.356  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:41.356  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:41.356  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:41.356  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:41.356  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:41.356  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:41.356  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:41.357  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:41.358  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:41.370   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:24:41.377  3913  3913 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 14:24:41.387  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:24:41.392  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:41.394   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7ceccf8:true
,09-09 14:24:41.396   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:24:41.397   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-09 14:24:41.397   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:41.409   873   884 I ActivityManager: Start proc 3930:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 14:24:41.411   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-09 14:24:41.414  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:41.415  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:41.419  3439  3439 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6807712 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-09 14:24:41.436  3913  3913 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 14:24:41.440  3913  3913 D BluetoothMap: Create BluetoothMap proxy object
,09-09 14:24:41.447  3930  3930 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 14:24:41.451  3913  3913 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 14:24:41.467   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-09 14:24:41.468   873  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 14:24:41.468   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 14:24:41.468  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:24:41.471   873  2247 I ActivityManager: Killing 3109:com.google.android.talk/u0a61 (adj 15): empty #17
,09-09 14:24:41.559  2713  2764 I bt_hci  : shut_down
,09-09 14:24:41.560  2713  2770 D bt_hwcfg: hw_epilog_process
,09-09 14:24:41.561  2713  2770 I bt_vendor: low_power_mode_cb
,09-09 14:24:41.580  2713  2770 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 14:24:41.580  2713  2770 I bt_vendor: epilog_cb
,09-09 14:24:41.580  2713  2770 I bt_hci  : epilog_finished_callback
,09-09 14:24:41.588  2713  2764 I bt_hci_h4: hal_close
,09-09 14:24:41.589  2713  2764 I bt_userial_vendor: device fd = 51 close
,09-09 14:24:41.710  3930  3930 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:24:41.710  3930  3930 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:24:41.710  3930  3930 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:24:41.710  3930  3930 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:24:41.710  3930  3930 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:24:41.710  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:24:41.711  3930  3930 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:24:41.711  3930  3930 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:24:41.711  3930  3930 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:24:41.711  3930  3930 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:24:41.712  2713  2761 D bt_stack_manager: event_shut_down_stack finished.
,09-09 14:24:41.713  2713  2760 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 14:24:41.732   873  2248 I ActivityManager: Start proc 3964:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-09 14:24:41.732  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 14:24:41.735   873  2248 I ActivityManager: Killing 3439:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 14:24:41.803  3930  3952 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 14:24:41.813   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b4b47d:true
,09-09 14:24:41.836  2713  2713 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 14:24:41.836  2713  2760 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 14:24:41.838  2713  2713 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 14:24:41.838  2713  2713 D BtGatt.GattService: stop()
09-09 14:24:41.838  2713  2713 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 14:24:41.870  2713  2713 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:24:41.870  2713  2713 V BluetoothAdapterState: isTurningOn()=false
,09-09 14:24:41.871  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:24:41.871  2713  2713 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 14:24:41.871  2713  2760 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 14:24:41.871  2713  2760 D BluetoothAdapterProperties: Setting state to 10
,09-09 14:24:41.871  2713  2760 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 14:24:41.874  2713  2760 I BluetoothAdapterState: Entering OffState
,09-09 14:24:41.881   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 14:24:41.906  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 14:24:41.906  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 14:24:41.906  2713  2713 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 14:24:41.907  2713  2761 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 14:24:41.909  2713  2761 D bt_stack_manager: event_clean_up_stack finished.
,09-09 14:24:41.917  2713  2713 I art     : System.exit called, status: 0
,09-09 14:24:41.917  2713  2713 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 14:24:41.935  3964  3964 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-09 14:24:41.987   873  2250 I ActivityManager: Process com.android.bluetooth (pid 2713) has died
,09-09 14:24:42.123  3964  3984 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 14:24:42.123  3964  3984 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 14:24:42.126  3964  3984 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 14:24:42.126  3964  3984 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 14:24:42.160  3964  3984 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-09 14:24:42.161  3964  3984 I Babel_SMS: MmsConfig.loadFromResources
,09-09 14:24:42.162  3964  3984 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 14:24:42.163  3964  3984 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 14:24:42.193  3964  3964 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:24:42.195  3964  3964 I Babel_Crash: startup - clean
,09-09 14:24:42.225  3964  3964 I Babel_telephony: TeleModule.launchCompleted
,09-09 14:24:42.236   873   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 14:24:42.245  3964  3964 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-09 14:24:42.255  3964  3964 W Babel   : BAM#gBA: invalid account id: -1
,09-09 14:24:42.255  3964  3964 W Babel   : BAM#gBA: invalid account id: -1
,09-09 14:24:42.255  3964  3964 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-09 14:24:42.258  3964  3989 I Babel   : deleted: false for 0
,09-09 14:24:42.270   873  1860 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 14:24:42.319   873  2247 I ActivityManager: Start proc 3991:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 14:24:42.329  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 14:24:42.382  3964  3964 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 14:24:42.399  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 14:24:42.405  3991  3991 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 14:24:42.408  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 14:24:42.412  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 14:24:42.428  3964  3964 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 14:24:42.443  3964  3964 I vclib   : onServiceConnected
,09-09 14:24:42.502  3991  3991 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 14:24:42.536  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:24:42.575   873   884 I ActivityManager: Start proc 4016:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-09 14:24:42.577  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:24:42.581   873  1858 I ActivityManager: Killing 3596:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-09 14:24:42.676  4016  4016 D AdapterServiceConfig: Adding HeadsetService
09-09 14:24:42.677  4016  4016 D AdapterServiceConfig: Adding A2dpService
,09-09 14:24:42.677  4016  4016 D AdapterServiceConfig: Adding HidService
,09-09 14:24:42.677  4016  4016 D AdapterServiceConfig: Adding HealthService
,09-09 14:24:42.677  4016  4016 D AdapterServiceConfig: Adding PanService
,09-09 14:24:42.677  4016  4016 D AdapterServiceConfig: Adding GattService
,09-09 14:24:42.677  4016  4016 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 14:24:42.681   873  2250 I ActivityManager: Killing 2786:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 14:24:42.730  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:42.754  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 14:24:42.761  1719  1719 D SystemUpdateService: onCreate
,09-09 14:24:42.770  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 14:24:42.773  1719  4028 I SystemUpdateService: active receiver: enabled
,09-09 14:24:42.775  1719  4028 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 14:24:42.777  1719  4028 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 14:24:42.777  1719  4028 I SystemUpdateService: now status is 0 (complete)
09-09 14:24:42.777  1719  4028 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 14:24:42.777  1719  4028 I SystemUpdateService: file has been verified
09-09 14:24:42.777  1719  4028 I SystemUpdateService: OTA package size = 12249756
,09-09 14:24:42.782  1719  4028 I SystemUpdateService: showing system update notification
,09-09 14:24:42.791  1719  1719 D SystemUpdateService: onDestroy
,09-09 14:24:42.795  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 14:24:42.797  1719  2520 I iu.UploadsManager: num queued entries: 0
,09-09 14:24:42.797  1719  2520 I iu.UploadsManager: num updated entries: 0
,09-09 14:24:42.798  1719  2520 I iu.SyncManager: NEXT; no task
,09-09 14:24:42.802  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 14:24:42.803  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 14:24:42.816   873   883 I ActivityManager: Start proc 4030:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 14:24:42.857  4030  4030 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 14:24:42.860  4030  4030 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:42.866  4030  4030 D SprintDMHelper: simOperator: 
,09-09 14:24:42.866  4030  4030 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 14:24:42.891   873  1858 I ActivityManager: Start proc 4042:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 14:24:42.892   873  1858 I ActivityManager: Killing 3537:android.process.acore/u0a5 (adj 15): empty #17
,09-09 14:24:43.073   873  1964 I ActivityManager: Start proc 4057:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 14:24:43.078  3964  4056 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 14:24:43.082   873   883 I ActivityManager: Killing 3703:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 14:24:43.162  4057  4057 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 14:24:43.223  4057  4057 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 14:24:43.223  4057  4057 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 14:24:43.223  4057  4057 I GAv4    :   adb logcat -s GAv4
,09-09 14:24:43.248  4057  4057 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 14:24:43.257  4057  4057 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 14:24:43.286  4057  4075 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 14:24:43.405  4057  4057 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 14:24:43.440  4057  4057 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 14:24:43.451  4057  4057 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5455-5460)
09-09 14:24:43.451  4057  4057 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 14:24:43.465  4057  4057 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ba44f3c}
,09-09 14:24:43.465  4057  4057 I LibraryLoader: Expected native library version number "",actual native library version number "",
,09-09 14:24:43.467  4057  4057 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 14:24:43.476  4057  4057 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 14:24:43.478  4057  4057 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 14:24:43.497  4057  4057 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 14:24:43.512  4057  4057 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 14:24:43.512  4057  4057 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 14:24:43.512  4057  4057 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 14:24:43.512  4057  4057 I Adreno  : Build Date                       : 10/20/15
09-09 14:24:43.512  4057  4057 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 14:24:43.512  4057  4057 I Adreno  : Local Branch                     : M14
09-09 14:24:43.512  4057  4057 I Adreno  : Remote Branch                    : 
09-09 14:24:43.512  4057  4057 I Adreno  : Remote Branch                    : 
09-09 14:24:43.512  4057  4057 I Adreno  : Reconstruct Branch               : 
,09-09 14:24:43.565  4057  4103 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 14:24:43.580  4057  4057 I NSApplication: Starting up...
,09-09 14:24:43.624   873  1944 I ActivityManager: Start proc 4108:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 14:24:43.626   873  1944 I ActivityManager: Killing 3718:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 14:24:43.738  4108  4108 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 14:24:43.937   873  1371 I ActivityManager: Killing 3488:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 14:24:44.267   873  1371 D WifiService: setWifiEnabled: true pid=3844, uid=10000
,09-09 14:24:44.267   873  1371 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:24:44.281   873  1306 D WifiConfigStore: Loading config and enabling all networks 
09-09 14:24:44.289  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:44.290  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:44.290  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:44.290  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:44.290  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:44.290  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:44.290  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:44.290  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:44.290  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:44.290  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:44.291  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:44.293  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:44.293  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:44.293  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:44.293  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:44.293  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:44.293  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:44.293  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:44.293  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:44.293  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:44.293  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:44.293  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:24:44.315   873  1306 D WifiConfigStore: loaded 0 passpoint configs
09-09 14:24:44.317   873  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 14:24:44.318   873  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 14:24:44.319   873  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 14:24:44.319   873  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 14:24:44.319   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 14:24:44.319   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 14:24:44.333   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-09 14:24:44.334   873  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.62 rxSuccessRate=11.50 delta 1000 -> 994
,09-09 14:24:44.335   372   871 D CommandListener: Setting iface cfg
,09-09 14:24:44.336   873  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-09 14:24:44.337   873  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 14:24:44.342   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 14:24:44.342   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:24:44.345   873  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 14:24:44.352   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 14:24:44.352   873  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 14:24:44.440   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 14:24:44.446  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 14:24:44.881  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 14:24:44.953  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 14:24:44.956  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 14:24:44.963   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 14:24:44.969   873  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 14:24:44.970   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:24:44.970   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 14:24:44.987   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:24:44.995   372   871 D CommandListener: Setting iface cfg
,09-09 14:24:44.997   873  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 14:24:45.009   873  1308 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-09 14:24:45.011   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 14:24:45.040   873  4133 D DhcpClient: Receive thread started
,09-09 14:24:45.125   873  1306 E native  : do suspend false
,09-09 14:24:45.147   873  2098 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 14:24:45.175   873  4133 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,09-09 14:24:45.177   873  2098 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,09-09 14:24:45.182   873  2098 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 14:24:45.204   873  4133 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 14:24:45.205   873  2098 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 14:24:45.213   372   871 D CommandListener: Setting iface cfg
,09-09 14:24:45.223   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 14:24:45.224   873  2098 D DhcpClient: Scheduling renewal in 86399s
,09-09 14:24:45.241   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 14:24:45.244   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
09-09 14:24:45.244   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 14:24:45.245   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 14:24:45.250   873  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 14:24:45.255   873  1308 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 14:24:45.311   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 14:24:45.311   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-09 14:24:45.312   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 14:24:45.314   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 14:24:45.315   873  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-09 14:24:45.322   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 14:24:45.332   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 14:24:45.332   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-09 14:24:45.332   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 14:24:45.332   873  1308 D ConnectivityService:    accepting network in place of null
09-09 14:24:45.333   873  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 14:24:45.334   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 14:24:45.334   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 14:24:45.354   873  4132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137364, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:24:45.366   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:24:45.397   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:24:45.403   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 14:24:45.403   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:45.409   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-09 14:24:45.417   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 14:24:45.417  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:45.417  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:45.417  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:45.417  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:45.417  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:45.417  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:45.417  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:45.417  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:45.417  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:24:45.417  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:45.418  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:24:45.428  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:45.428  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:45.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:45.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:45.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:45.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:45.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:45.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:45.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:24:45.428  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:45.429  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:45.431  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 14:24:45.435  1719  1719 D SystemUpdateService: onCreate
,09-09 14:24:45.442  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 14:24:45.445  1719  4144 I SystemUpdateService: active receiver: enabled
,09-09 14:24:45.450  1719  4144 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 14:24:45.453  1719  4144 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 14:24:45.453  1719  4144 I SystemUpdateService: now status is 0 (complete)
,09-09 14:24:45.453  1719  4144 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 14:24:45.453  1719  4144 I SystemUpdateService: file has been verified
,09-09 14:24:45.453  1719  4144 I SystemUpdateService: OTA package size = 12249756
,09-09 14:24:45.461  1719  4144 I SystemUpdateService: showing system update notification
,09-09 14:24:45.469   873  4131 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 14:24:45.472  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 14:24:45.478  1719  4148 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 14:24:45.479  1719  4148 W BaseAppContext: Using Auth Proxy for data requests.
09-09 14:24:45.479  1719  1719 D SystemUpdateService: onDestroy
09-09 14:24:45.480  1719  4148 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 14:24:45.482  1719  2520 I iu.UploadsManager: num queued entries: 0
,09-09 14:24:45.485  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-09 14:24:45.485  1719  2520 I iu.UploadsManager: num updated entries: 0
09-09 14:24:45.486  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 14:24:45.486  1719  2520 I iu.SyncManager: NEXT; no task
,09-09 14:24:45.488  4030  4030 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:45.492  4030  4030 D SprintDMHelper: simOperator: 
09-09 14:24:45.492  4030  4030 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 14:24:45.494  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:24:45.495  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:24:45.532  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 14:24:45.532  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 14:24:45.532  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:24:45.532  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:24:45.547  1719  4148 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-09 14:24:45.548   873  4131 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 12:24:45 GMT], X-Android-Received-Millis=[1473423885548], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473423885518]}
,09-09 14:24:45.549   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 14:24:45.549   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-09 14:24:45.549   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 14:24:45.551   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 14:24:45.648  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 14:24:45.648  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 14:24:45.648  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 14:24:45.649  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:24:45.653  3964  4150 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 14:24:45.673  3018  4152 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 14:24:45.673  3018  4152 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at jdm.a(PG:82)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at jcs.o(PG:406)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at jcn.a(PG:1379)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at jcs.i(PG:143)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at blb.a(PG:3937)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at czp.a(PG:18188)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at czp.a(PG:9081)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at czq.run(PG:1686)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:24:45.673  3018  4152 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at jdj.a(PG:4091)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at jdj.a(PG:1125)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at jdm.a(PG:77)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	... 12 more
09-09 14:24:45.673  3018  4152 E HttpOperation: Caused by: faj: BadAuthentication
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at fal.a(PG:38)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	at jdj.a(PG:4089)
09-09 14:24:45.673  3018  4152 E HttpOperation: 	... 14 more
,09-09 14:24:45.751  1499  2291 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 14:24:45.752  1499  2291 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 14:24:45.752  1499  2291 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 14:24:45.752  1499  2291 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:24:45.780  3018  4152 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 14:24:45.780  3018  4152 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at jdm.a(PG:82)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at jcs.o(PG:406)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at jcn.a(PG:1379)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at jcs.i(PG:143)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at hec.a(PG:42)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at hee.a(PG:102)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at czr.a(PG:65)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at kka.a(PG:108)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at czp.a(PG:19176)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at czp.a(PG:9081)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at czq.run(PG:1686)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:24:45.780  3018  4152 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at jdj.a(PG:4091)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at jdj.a(PG:1125)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at jdm.a(PG:77)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	... 15 more
09-09 14:24:45.780  3018  4152 E HttpOperation: Caused by: faj: BadAuthentication
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at fal.a(PG:38)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	at jdj.a(PG:4089)
09-09 14:24:45.780  3018  4152 E HttpOperation: 	... 17 more
,09-09 14:24:45.781  3018  4152 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 14:24:45.781  3018  4152 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at hec.a(PG:42)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at hee.a(PG:102)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at czr.a(PG:65)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at kka.a(PG:108)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	... 15 more
09-09 14:24:45.781  3018  4152 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at fal.a(PG:38)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 14:24:45.781  3018  4152 E ExperimentLoader: 	... 17 more
,09-09 14:24:45.879   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131849, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 14:24:46.403   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 14:24:47.007   873  1964 I ActivityManager: Killing 3741:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 14:24:47.274   873  1968 D WifiService: setWifiEnabled: false pid=3844, uid=10000
,09-09 14:24:47.274   873  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:24:47.310  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 14:24:47.316   873  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 14:24:47.317   873  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 14:24:47.317   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 14:24:47.318   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:24:47.338   873  2098 D DhcpClient: Clearing IP address
,09-09 14:24:47.339   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-09 14:24:47.343   372   871 D CommandListener: Setting iface cfg
,09-09 14:24:47.349  1499  4158 V NativeCrypto: Read error: ssl=0x9affcc00: I/O error during system call, Connection timed out
,09-09 14:24:47.369   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 14:24:47.369   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-09 14:24:47.370  1499  4158 V NativeCrypto: SSL shutdown failed: ssl=0x9affcc00: I/O error during system call, Broken pipe
09-09 14:24:47.373   873  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
09-09 14:24:47.374   873  4133 D DhcpClient: Receive thread stopped
09-09 14:24:47.375   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 14:24:47.375   400   400 E Parcel  : Reading a NULL string not supported here.
,09-09 14:24:47.382   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:24:47.389   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 14:24:47.393   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 14:24:47.398  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:47.398  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:47.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:47.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:47.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:47.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:47.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:47.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:47.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:47.398  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:47.398  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:47.399   873  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 14:24:47.399  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:47.399  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:47.399  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:47.399  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:47.399  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:47.399  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:47.399  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:47.399  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:47.399  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:24:47.399  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:47.399  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:47.400  1859  2292 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:24:47.429   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:24:47.456   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:24:47.457   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 14:24:47.457   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:47.463  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:47.463   873   890 D Tethering: MasterInitialState.processMessage what=3
09-09 14:24:47.464  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:47.480  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 14:24:47.483  1719  1719 D SystemUpdateService: onCreate
,09-09 14:24:47.485  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 14:24:47.490  1719  4171 I SystemUpdateService: active receiver: enabled
,09-09 14:24:47.497  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 14:24:47.499  1719  2520 I iu.UploadsManager: num queued entries: 0
09-09 14:24:47.499  1719  2520 I iu.UploadsManager: num updated entries: 0
,09-09 14:24:47.503  1719  4171 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 14:24:47.506  1719  2520 I iu.SyncManager: NEXT; no task
,09-09 14:24:47.506  1719  4171 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 14:24:47.507  1719  4171 I SystemUpdateService: now status is 0 (complete)
09-09 14:24:47.507  1719  4171 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 14:24:47.507  1719  4171 I SystemUpdateService: file has been verified
,09-09 14:24:47.509  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 14:24:47.510  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 14:24:47.512  4030  4030 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:47.523  4030  4030 D SprintDMHelper: simOperator: 
,09-09 14:24:47.523  4030  4030 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 14:24:47.541   372   871 E Netd    : netlink response contains error (No such file or directory)
09-09 14:24:47.543   873  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 14:24:47.516  1719  4171 I SystemUpdateService: OTA package size = 12249756
,09-09 14:24:47.557  3964  4175 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 14:24:47.565  1719  4171 I SystemUpdateService: showing system update notification
,09-09 14:24:47.577  1719  1719 D SystemUpdateService: onDestroy
,09-09 14:24:47.685  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:24:47.721  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 14:24:47.721  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 14:24:47.721  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 14:24:47.721  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:24:47.760  3554  3554 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 14:24:47.760  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 14:24:47.760  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 14:24:50.315   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a0fb8f:true
,09-09 14:24:50.317  4016  4016 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 14:24:50.326  4016  4016 I bt_bluedroid: init
,09-09 14:24:50.327  4016  4177 I BluetoothAdapterState: Entering OffState
,09-09 14:24:50.330  4016  4178 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 14:24:50.330  4016  4178 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 14:24:50.330  4016  4178 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 14:24:50.330  4016  4178 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 14:24:50.331  4016  4016 I bt_bluedroid: get_profile_interface socket
09-09 14:24:50.334  4016  4181 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-09 14:24:50.336  4016  4181 D BluetoothAdapterProperties: Name is: Nexus 6
09-09 14:24:50.336  4016  4016 I bt_bluedroid: get_profile_interface sdp
,09-09 14:24:50.341  4016  4026 I bt_bluedroid: config_hci_snoop_log
,09-09 14:24:50.345   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 14:24:50.355  4016  4177 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 14:24:50.355  4016  4177 D BluetoothAdapterProperties: Setting state to 14
,09-09 14:24:50.357  4016  4177 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 14:24:50.363  4016  4177 D BluetoothBondStateMachine: make
,09-09 14:24:50.366  4016  4182 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 14:24:50.373  4016  4177 I BluetoothAdapterState: Entering PendingCommandState
,09-09 14:24:50.374  4016  4016 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 14:24:50.378  4016  4016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:24:50.378  4016  4016 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 14:24:50.379  4016  4016 D BtGatt.GattService: Received start request. Starting profile...
09-09 14:24:50.379  4016  4016 D BtGatt.GattService: start()
,09-09 14:24:50.379  4016  4016 I bt_bluedroid: get_profile_interface gatt
,09-09 14:24:50.381  4016  4016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:24:50.381  4016  4016 D BtGatt.AdvertiseManager: advertise manager created
,09-09 14:24:50.390  4016  4016 V BluetoothAdapterState: isTurningOff()=false
09-09 14:24:50.390  4016  4016 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:50.390  4016  4016 V BluetoothAdapterState: isBleTurningOn()=true
09-09 14:24:50.390  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:24:50.391  4016  4177 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 14:24:50.391  4016  4177 I bt_bluedroid: enable
,09-09 14:24:50.392  4016  4178 D bt_stack_manager: event_start_up_stack is bringing up the stack.,
,09-09 14:24:50.392  4016  4178 I bt_hci  : start_up
,09-09 14:24:50.402  4016  4178 I bt_vendor: alloc value 0xb3969189
,09-09 14:24:50.402  4016  4178 I bt_vendor: init
,09-09 14:24:50.402  4016  4178 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-09 14:24:50.402  4016  4178 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 14:24:50.508  4016  4178 D bt_hci  : start_up starting async portion
,09-09 14:24:50.508  4016  4185 I bt_hci  : event_finish_startup
,09-09 14:24:50.509  4016  4185 I bt_hci_h4: hal_open
,09-09 14:24:50.509  4016  4185 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 14:24:50.524  4016  4185 I bt_userial_vendor: device fd = 51 open
,09-09 14:24:50.550  4016  4185 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 14:24:50.583  4016  4185 D bt_hwcfg: Chipset BCM4354A2
,09-09 14:24:50.583  4016  4185 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 14:24:50.585  4016  4185 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 14:24:51.244  4016  4185 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 14:24:51.245  4016  4185 D bt_hwcfg: Settlement delay -- 100 ms
,09-09 14:24:51.246  4016  4185 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 14:24:51.362  4016  4185 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 14:24:51.364  4016  4185 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 14:24:51.393  4016  4185 I bt_hwcfg: vendor lib fwcfg completed
,09-09 14:24:51.393  4016  4185 I bt_vendor: firmware callback
,09-09 14:24:51.394  4016  4185 I bt_hci  : firmware_config_callback
,09-09 14:24:51.404  4016  4187 I bt_btu  : btu_task pending for preload complete event
,09-09 14:24:51.405  4016  4187 I bt_btu_task: Bluetooth chip preload is complete
,09-09 14:24:51.405  4016  4187 I bt_btu  : btu_task received preload complete event
,09-09 14:24:51.415  4016  4187 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 14:24:51.415  4016  4187 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 14:24:51.415  4016  4187 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 14:24:51.416  4016  4187 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 14:24:51.416  4016  4187 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 14:24:51.416  4016  4187 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 14:24:51.417  4016  4187 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 14:24:51.417  4016  4187 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 14:24:51.417  4016  4187 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 14:24:51.417  4016  4187 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 14:24:51.418  4016  4187 I         : BTE_InitTraceLevels -- TRC_SDP,
,09-09 14:24:51.418  4016  4187 I         : BTE_InitTraceLevels -- TRC_GATT,
09-09 14:24:51.418  4016  4187 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 14:24:51.419  4016  4187 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 14:24:51.419  4016  4187 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 14:24:51.554  4016  4187 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e6d9d,
09-09 14:24:51.554  4016  4187 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e6d9d 
,09-09 14:24:51.564  4016  4181 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-09 14:24:51.566  4016  4181 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 14:24:51.566  4016  4181 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 14:24:51.571  4016  4181 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 14:24:51.574  4016  4181 D BluetoothAdapterProperties: Scan Mode:20
,09-09 14:24:51.575  4016  4181 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 14:24:51.575  4016  4181 D bt_hci  : do_postload posting postload work item
,09-09 14:24:51.576  4016  4185 I bt_hci  : event_postload
09-09 14:24:51.576  4016  4185 I bt_vendor: sco_config_cb
09-09 14:24:51.576  4016  4185 I bt_hci  : sco_config_callback postload finished.
,09-09 14:24:51.579  4016  4181 D bt_bte_conf: Device ID record 1 : primary
,09-09 14:24:51.579  4016  4181 D bt_bte_conf:   vendorId            = 000f
,09-09 14:24:51.581  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:51.579  4016  4181 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 14:24:51.582  4016  4181 D bt_bte_conf:   product             = 1200
,09-09 14:24:51.585  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:51.585  4016  4185 I bt_vendor: low_power_mode_cb
,09-09 14:24:51.582  4016  4181 D bt_bte_conf:   version             = 1436
09-09 14:24:51.586  4016  4181 D bt_bte_conf:   clientExecutableURL = 
,09-09 14:24:51.586  4016  4181 D bt_bte_conf:   serviceDescription  = 
,09-09 14:24:51.586  4016  4181 D bt_bte_conf:   documentationURL    = 
,09-09 14:24:51.587  4016  4181 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 14:24:51.587  4016  4178 D bt_stack_manager: event_start_up_stack finished
,09-09 14:24:51.588  4016  4177 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-09 14:24:51.588  4016  4177 D BluetoothAdapterProperties: Setting state to 15
,09-09 14:24:51.589  4016  4177 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 14:24:51.590  4016  4177 I BluetoothAdapterState: Entering BleOnState
09-09 14:24:51.595  4016  4177 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 14:24:51.595  4016  4177 D BluetoothAdapterProperties: Setting state to 11
09-09 14:24:51.596  4016  4177 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 14:24:51.606  4016  4016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
09-09 14:24:51.611  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:51.615  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:51.615  4016  4016 D HeadsetService: Received start request. Starting profile...
09-09 14:24:51.618  4016  4016 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:24:51.618  4016  4016 D HeadsetStateMachine: make
,09-09 14:24:51.630  4016  4016 D HeadsetStateMachine: max_hf_connections = 1
,09-09 14:24:51.631  4016  4016 I bt_bluedroid: get_profile_interface handsfree
09-09 14:24:51.631  4016  4181 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 14:24:51.631  4016  4181 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-09 14:24:51.633  4016  4177 I BluetoothAdapterState: Entering PendingCommandState
,09-09 14:24:51.637  4016  4016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:24:51.638  4016  4016 D A2dpService: Received start request. Starting profile...
09-09 14:24:51.638  4016  4016 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 14:24:51.639  4016  4016 I bt_bluedroid: get_profile_interface avrcp
,09-09 14:24:51.640  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:51.644  4016  4016 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 14:24:51.644  4016  4016 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:24:51.644  4016  4016 D A2dpStateMachine: make
,09-09 14:24:51.645  4016  4016 I bt_bluedroid: get_profile_interface a2dp
,09-09 14:24:51.646  4016  4181 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-09 14:24:51.647  4016  4197 D A2dpStateMachine: Enter Disconnected: -2
09-09 14:24:51.647  4016  4016 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 14:24:51.648  4016  4016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:24:51.649  4016  4016 D HidService: Received start request. Starting profile...
,09-09 14:24:51.649  4016  4016 I bt_bluedroid: get_profile_interface hidhost
09-09 14:24:51.649  3913  3913 D BluetoothInputDevice: Proxy object connected
09-09 14:24:51.649  4016  4016 D HidService: setHidService(): set to: null
09-09 14:24:51.649  4016  4181 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c83e5
09-09 14:24:51.649  4016  4181 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 14:24:51.650  3913  3913 D HidProfile: Bluetooth service connected
,09-09 14:24:51.651  4016  4016 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 14:24:51.651  4016  4016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
09-09 14:24:51.652  4016  4016 D HealthService: Received start request. Starting profile...
,09-09 14:24:51.653  4016  4016 I bt_bluedroid: get_profile_interface health
,09-09 14:24:51.654  4016  4016 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 14:24:51.655  4016  4016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:24:51.656  3913  3913 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 14:24:51.656  4016  4016 D PanService: Received start request. Starting profile...
09-09 14:24:51.656  4016  4016 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 14:24:51.656  4016  4016 I bt_bluedroid: get_profile_interface pan
09-09 14:24:51.656  4016  4181 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 14:24:51.657  3913  3913 D PanProfile: Bluetooth service connected
09-09 14:24:51.658  4016  4016 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
09-09 14:24:51.659  3913  3913 D BluetoothMap: Proxy object connected
09-09 14:24:51.659  4016  4016 D BluetoothMapService: Received start request. Starting profile...
,09-09 14:24:51.659  4016  4016 D BluetoothMapService: start()
09-09 14:24:51.659  3913  3913 D MapProfile: Bluetooth service connected
09-09 14:24:51.659  3913  3913 D BluetoothMap: getConnectedDevices()
,09-09 14:24:51.660  3913  3913 D BluetoothMap: Bluetooth is Not enabled
09-09 14:24:51.661  4016  4016 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 14:24:51.662  4016  4016 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 14:24:51.662  4016  4016 D BluetoothMapAppObserver: createReceiver()
,09-09 14:24:51.662  4016  4016 D BluetoothMapAppObserver: initObservers()
,09-09 14:24:51.663  4016  4016 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 14:24:51.668  4016  4016 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:24:51.668  4016  4016 V BluetoothAdapterState: isTurningOn()=true
09-09 14:24:51.668  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:24:51.668  4016  4195 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 14:24:51.668  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:24:51.671  4016  4016 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:24:51.671  4016  4016 V BluetoothAdapterState: isTurningOn()=true
09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isTurningOn()=true
,09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isTurningOn()=true
09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isTurningOff()=false
09-09 14:24:51.672  4016  4016 V BluetoothAdapterState: isTurningOn()=true
09-09 14:24:51.673  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:24:51.673  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:51.673  4016  4016 V BluetoothAdapterState: isTurningOff()=false
09-09 14:24:51.673  4016  4016 V BluetoothAdapterState: isTurningOn()=true
09-09 14:24:51.673  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:51.673  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:24:51.673  4016  4177 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 14:24:51.673  4016  4177 D BluetoothAdapterProperties: ScanMode =  20
09-09 14:24:51.673  4016  4177 D BluetoothAdapterProperties: State =  11
09-09 14:24:51.674  4016  4177 D BluetoothAdapterProperties: Setting state to 12
09-09 14:24:51.674  4016  4177 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 14:24:51.674  3913  3924 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 14:24:51.674   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 14:24:51.675   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:24:51.675  1364  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:24:51.676  4016  4181 D BluetoothAdapterProperties: Scan Mode:21
09-09 14:24:51.676  4016  4181 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:24:51.676  1364  1384 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:24:51.676  4016  4177 I BluetoothAdapterState: Entering OnState
09-09 14:24:51.677   873   873 D BluetoothA2dp: Proxy object connected
09-09 14:24:51.677  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 14:24:51.677  1364  1364 D PanProfile: Bluetooth service connected
09-09 14:24:51.678  3913  3926 D BluetoothMap: onBluetoothStateChange: up=true
09-09 14:24:51.678   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:24:51.678  1958  2251 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:24:51.678  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:51.678  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:51.678  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:51.678  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:51.678  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:51.678  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:51.678  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:51.678  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:24:51.679   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:24:51.679  1364  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 14:24:51.681  1364  1364 D BluetoothA2dp: Proxy object connected
09-09 14:24:51.681  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:51.681  3913  3924 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 14:24:51.684  1364  1384 D BluetoothMap: onBluetoothStateChange: up=true
09-09 14:24:51.684  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:51.684  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:51.684  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:51.684  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:51.684  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:51.684  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:51.684  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:51.684  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:24:51.686  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:24:51.686  1364  1364 D BluetoothMap: Proxy object connected
09-09 14:24:51.686  1364  1364 D MapProfile: Bluetooth service connected
09-09 14:24:51.686  3913  3926 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:24:51.686  1364  1364 D BluetoothMap: getConnectedDevices()
,09-09 14:24:51.687  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 14:24:51.688  4016  4016 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 14:24:51.688  1364  2058 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 14:24:51.688  4016  4016 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 14:24:51.690  1364  1364 D BluetoothInputDevice: Proxy object connected
,09-09 14:24:51.690  1364  1364 D HidProfile: Bluetooth service connected
09-09 14:24:51.692   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 14:24:51.693  4016  4016 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:51.693  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:51.694  3913  3913 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 14:24:51.694  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:51.695  4016  4016 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:24:51.696  4016  4016 D ObexServerSockets: Succeed to create listening sockets 
09-09 14:24:51.696  4016  4016 D ObexServerSockets0: startAccept()
09-09 14:24:51.696  4016  4016 D ObexServerSockets0: prepareForNewConnect()
,09-09 14:24:51.697  3913  3913 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 14:24:51.698  4016  4016 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 14:24:51.698  4016  4202 D ObexServerSockets0: Accepting socket connection...
,09-09 14:24:51.698  4016  4016 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-09 14:24:51.699  4016  4016 D BluetoothMapService: onReceive
,09-09 14:24:51.699  4016  4016 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:51.699  4016  4016 D BluetoothMapService: STATE_ON
09-09 14:24:51.699  4016  4203 D ObexServerSockets0: Accepting socket connection...
,09-09 14:24:51.712  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:24:51.718  3913  3913 D BluetoothA2dp: Proxy object connected
,09-09 14:24:51.721  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:51.725  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:24:51.727  4016  4016 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 14:24:51.727  4016  4016 D ObexServerSockets0: prepareForNewConnect()
,09-09 14:24:51.728  3913  3913 D BluetoothPbap: Proxy object connected
09-09 14:24:51.728  1364  1364 D BluetoothPbap: Proxy object connected
09-09 14:24:51.729  1364  1364 D PbapServerProfile: Bluetooth service connected
,09-09 14:24:51.729  3913  3913 D PbapServerProfile: Bluetooth service connected
,09-09 14:24:51.735  4016  4207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:24:51.750  4016  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:24:51.751  4016  4211 I BtOppRfcommListener: Accept thread started.
,09-09 14:24:51.777   873   873 D BluetoothHeadset: Proxy object connected
,09-09 14:24:51.778  1364  1384 D BluetoothHeadset: Proxy object connected
09-09 14:24:51.778   873   873 D BluetoothHeadset: Proxy object connected
09-09 14:24:51.778  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-09 14:24:51.778  1958  2116 D BluetoothHeadset: Proxy object connected
,09-09 14:24:51.778   873   873 D BluetoothHeadset: Proxy object connected
09-09 14:24:51.779   873   890 D BluetoothHeadset: Proxy object connected
,09-09 14:24:51.779  1958  2102 D BluetoothHeadset: Proxy object connected
09-09 14:24:51.779   873   890 D BluetoothHeadset: Proxy object connected
,09-09 14:24:51.803  3913  3924 D BluetoothHeadset: Proxy object connected
,09-09 14:24:51.804  3913  3913 D HeadsetProfile: Bluetooth service connected
,09-09 14:24:53.294  4016  4177 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 14:24:53.295  4016  4177 D BluetoothAdapterProperties: Setting state to 13
09-09 14:24:53.295  4016  4177 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 14:24:53.298  4016  4177 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 14:24:53.305  4016  4177 I BluetoothAdapterState: Entering PendingCommandState
,09-09 14:24:53.305  4016  4016 D BluetoothMapService: onReceive
,09-09 14:24:53.305  4016  4016 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:24:53.306  4016  4016 D BluetoothMapService: STATE_TURNING_OFF
,09-09 14:24:53.307  4016  4016 D BluetoothMapService: MAP Service closeService in
09-09 14:24:53.308  4016  4016 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 14:24:53.308  4016  4016 D ObexServerSockets0: shutdown(block = true)
09-09 14:24:53.309  4016  4202 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-09 14:24:53.314  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:53.315  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:53.315  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:53.315  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:53.315  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:53.315  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:53.315  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:53.315  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:53.315  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:24:53.318  4016  4016 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 14:24:53.319  4016  4203 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-09 14:24:53.319  4016  4189 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 14:24:53.319  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:53.319  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:24:53.320  4016  4016 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 14:24:53.320  4016  4016 I BtOppRfcommListener: stopping Accept Thread
,09-09 14:24:53.321  4016  4211 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:53.323  4016  4181 D BluetoothAdapterProperties: Scan Mode:20
,09-09 14:24:53.323  4016  4177 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 14:24:53.324  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:53.324  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:53.324  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:53.324  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:24:53.324  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:53.324  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:53.324  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:53.324  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:53.324  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:24:53.324  4016  4211 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 14:24:53.325  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:53.325  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:53.327  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:53.328  4016  4016 D HeadsetService: Received stop request...Stopping profile...
09-09 14:24:53.329  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:53.330  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 14:24:53.330   873   873 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:53.332  1364  1377 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:53.332  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-09 14:24:53.333  3913  3926 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:53.333   873   873 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:53.333  1958  1982 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:53.334   873   873 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:53.335  3913  3913 D HeadsetProfile: Bluetooth service disconnected
09-09 14:24:53.335  4016  4016 D A2dpService: Received stop request...Stopping profile...
09-09 14:24:53.335  4016  4197 D A2dpStateMachine: Exit Disconnected: -1
09-09 14:24:53.337   873  1308 D ConnectivityService: handlePromptUnvalidated 101
09-09 14:24:53.339   873   873 D BluetoothA2dp: Proxy object disconnected
,09-09 14:24:53.339  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-09 14:24:53.339  4016  4016 D HidService: Received stop request...Stopping profile...
09-09 14:24:53.339  4016  4016 D HidService: Stopping Bluetooth HidService
09-09 14:24:53.341  4016  4016 D HealthService: Received stop request...Stopping profile...
,09-09 14:24:53.341  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-09 14:24:53.341  1364  1364 D HidProfile: Bluetooth service disconnected
09-09 14:24:53.342  4016  4016 V BluetoothAdapterState: isTurningOff()=true
09-09 14:24:53.342  4016  4016 V BluetoothAdapterState: isTurningOn()=false
,09-09 14:24:53.342  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:53.342  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:53.342  4016  4016 D PanService: Received stop request...Stopping profile...
,09-09 14:24:53.342  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:24:53.343  3913  3913 D BluetoothA2dp: Proxy object disconnected
09-09 14:24:53.344  3913  3913 D BluetoothInputDevice: Proxy object disconnected
09-09 14:24:53.344  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 14:24:53.344  3913  3913 D HidProfile: Bluetooth service disconnected
,09-09 14:24:53.344  1364  1364 D PanProfile: Bluetooth service disconnected
09-09 14:24:53.344  3913  3913 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 14:24:53.344  3913  3913 D PanProfile: Bluetooth service disconnected
09-09 14:24:53.345  4016  4016 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 14:24:53.345  4016  4016 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:24:53.345  4016  4187 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:53.345  4016  4187 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:53.345  4016  4187 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:53.345  4016  4016 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 14:24:53.345  4016  4016 D BluetoothMapService: stop()
09-09 14:24:53.346  4016  4016 D BluetoothMapAppObserver: deinitObservers()
09-09 14:24:53.346  4016  4016 D BluetoothMapAppObserver: removeReceiver()
09-09 14:24:53.347  4016  4181 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 14:24:53.347  4016  4181 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-09 14:24:53.348  1364  1364 D BluetoothMap: Proxy object disconnected
09-09 14:24:53.348  1364  1364 D MapProfile: Bluetooth service disconnected
09-09 14:24:53.348  4016  4016 V BluetoothAdapterState: isTurningOff()=true
09-09 14:24:53.348  4016  4016 V BluetoothAdapterState: isTurningOn()=false
,09-09 14:24:53.349  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:53.349  3913  3913 D BluetoothMap: Proxy object disconnected
09-09 14:24:53.349  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:53.349  3913  3913 D MapProfile: Bluetooth service disconnected
09-09 14:24:53.354  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:24:53.354  4016  4016 V BluetoothAdapterState: isTurningOff()=true
09-09 14:24:53.355  4016  4016 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:53.355  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:24:53.355  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:24:53.355  4016  4187 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 14:24:53.355  4016  4016 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 14:24:53.355  4016  4187 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:53.355  4016  4016 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 14:24:53.356  4016  4187 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 14:24:53.356  4016  4187 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:53.356  4016  4016 V BluetoothAdapterState: isTurningOff()=true
,09-09 14:24:53.356  4016  4187 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 14:24:53.356  4016  4016 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:53.356  4016  4187 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:53.356  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:53.356  4016  4181 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 14:24:53.356  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:53.356  4016  4016 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 14:24:53.356  4016  4181 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 14:24:53.356  4016  4181 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 14:24:53.356  4016  4016 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 14:24:53.357  4016  4016 V BluetoothAdapterState: isTurningOff()=true
09-09 14:24:53.357  4016  4016 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:53.357  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:24:53.357  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:53.358  4016  4016 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 14:24:53.358  4016  4016 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 14:24:53.359  4016  4016 D BluetoothMapService: MAP Service closeService in
09-09 14:24:53.359  4016  4016 V BluetoothAdapterState: isTurningOff()=true
09-09 14:24:53.359  4016  4016 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:53.359  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:24:53.359  4016  4016 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:53.360  4016  4177 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 14:24:53.360  4016  4177 D BluetoothAdapterProperties: Setting state to 15
09-09 14:24:53.360  4016  4177 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 14:24:53.360  4016  4177 I BluetoothAdapterState: Entering BleOnState
09-09 14:24:53.361  3913  3926 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:24:53.360  4016  4016 D BluetoothMapService: cleanup()
,09-09 14:24:53.361  4016  4016 D BluetoothMapService: MAP Service closeService in
09-09 14:24:53.361   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:24:53.361   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:53.361  1364  2058 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:53.362  3913  3924 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:53.362  1364  1377 D BluetoothPan: onBluetoothStateChange on: false
09-09 14:24:53.362  1364  1364 D BluetoothPbap: Proxy object disconnected
09-09 14:24:53.363  1364  1364 D PbapServerProfile: Bluetooth service disconnected
,09-09 14:24:53.363  3913  3924 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:24:53.364   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:53.365  1958  1973 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:53.365  3913  3926 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:24:53.367   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:53.367  1364  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:24:53.368  3913  3924 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 14:24:53.368  1364  2058 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:24:53.370  3913  3926 D BluetoothPan: onBluetoothStateChange on: false
09-09 14:24:53.371  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 14:24:53.371  1364  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:24:53.372  4016  4177 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 14:24:53.372  4016  4177 D BluetoothAdapterProperties: Setting state to 16
09-09 14:24:53.372  4016  4177 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-09 14:24:53.373  4016  4177 D BluetoothAdapterProperties: onBleDisable
09-09 14:24:53.374  4016  4177 I BluetoothAdapterState: Entering PendingCommandState
09-09 14:24:53.374  4016  4178 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 14:24:53.374  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:53.375  4016  4181 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:24:53.376  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:53.376  4016  4187 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 14:24:53.376  4016  4187 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 14:24:53.377  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:53.378  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:53.379  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:24:53.387  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:53.390  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:24:53.577  4016  4181 I bt_hci  : shut_down
,09-09 14:24:53.577  4016  4185 D bt_hwcfg: hw_epilog_process
,09-09 14:24:53.586  4016  4185 I bt_vendor: low_power_mode_cb
,09-09 14:24:53.611  4016  4185 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 14:24:53.611  4016  4185 I bt_vendor: epilog_cb
,09-09 14:24:53.611  4016  4185 I bt_hci  : epilog_finished_callback
,09-09 14:24:53.617  4016  4181 I bt_hci_h4: hal_close
,09-09 14:24:53.619  4016  4181 I bt_userial_vendor: device fd = 51 close
,09-09 14:24:53.744  4016  4178 D bt_stack_manager: event_shut_down_stack finished.
,09-09 14:24:53.745  4016  4177 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 14:24:53.750  4016  4177 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 14:24:53.751  4016  4016 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:24:53.752  4016  4016 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 14:24:53.753  4016  4016 D BtGatt.GattService: stop()
09-09 14:24:53.753  4016  4016 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 14:24:53.757  4016  4016 V BluetoothAdapterState: isTurningOff()=false
09-09 14:24:53.758  4016  4016 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:53.758  4016  4016 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:24:53.758  4016  4016 V BluetoothAdapterState: isBleTurningOff()=true
09-09 14:24:53.759  4016  4177 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 14:24:53.760  4016  4177 D BluetoothAdapterProperties: Setting state to 10
09-09 14:24:53.760  4016  4177 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 14:24:53.762  4016  4177 I BluetoothAdapterState: Entering OffState
,09-09 14:24:53.764   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 14:24:53.784  4016  4016 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-09 14:24:53.784  4016  4016 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 14:24:53.784  4016  4178 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 14:24:53.787  4016  4178 D bt_stack_manager: event_clean_up_stack finished.
09-09 14:24:53.787  4016  4016 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 14:24:53.789  4016  4016 I art     : System.exit called, status: 0
,09-09 14:24:53.789  4016  4016 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 14:24:53.843   873  1964 I ActivityManager: Process com.android.bluetooth (pid 4016) has died
,09-09 14:24:56.291  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 14:24:56.291  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:24:59.298  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:24:59.299  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9dcdff8 added. We now have 6 listener(s)
09-09 14:24:59.299  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:24:59.303  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:24:59.303  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1191cd1 added. We now have 7 listener(s)
,09-09 14:24:59.304  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:59.305  3844  3895 I System.out: IsBluetoothEnabled
,09-09 14:24:59.317  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:59.359   873   890 I ActivityManager: Start proc 4222:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 14:24:59.484  4222  4222 D AdapterServiceConfig: Adding HeadsetService
,09-09 14:24:59.484  4222  4222 D AdapterServiceConfig: Adding A2dpService
,09-09 14:24:59.485  4222  4222 D AdapterServiceConfig: Adding HidService
,09-09 14:24:59.485  4222  4222 D AdapterServiceConfig: Adding HealthService
,09-09 14:24:59.485  4222  4222 D AdapterServiceConfig: Adding PanService
09-09 14:24:59.485  4222  4222 D AdapterServiceConfig: Adding GattService
,09-09 14:24:59.485  4222  4222 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 14:24:59.523   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7329fb0:true
,09-09 14:24:59.525  4222  4222 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 14:24:59.534  4222  4222 I bt_bluedroid: init
,09-09 14:24:59.535  4222  4234 I BluetoothAdapterState: Entering OffState
,09-09 14:24:59.542  4222  4235 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 14:24:59.543  4222  4235 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 14:24:59.543  4222  4235 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 14:24:59.544  4222  4235 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 14:24:59.546  4222  4222 I bt_bluedroid: get_profile_interface socket
,09-09 14:24:59.552  4222  4222 I bt_bluedroid: get_profile_interface sdp
,09-09 14:24:59.555  4222  4238 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 14:24:59.559  4222  4238 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 14:24:59.560  4222  4233 I bt_bluedroid: config_hci_snoop_log
,09-09 14:24:59.563   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 14:24:59.571  4222  4234 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 14:24:59.572  4222  4234 D BluetoothAdapterProperties: Setting state to 14
,09-09 14:24:59.572  4222  4234 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 14:24:59.576  4222  4234 D BluetoothBondStateMachine: make
,09-09 14:24:59.580  4222  4239 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 14:24:59.586  4222  4234 I BluetoothAdapterState: Entering PendingCommandState
,09-09 14:24:59.587  4222  4222 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 14:24:59.590  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:24:59.591  4222  4222 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:24:59.591  4222  4222 D BtGatt.GattService: Received start request. Starting profile...
,09-09 14:24:59.591  4222  4222 D BtGatt.GattService: start()
09-09 14:24:59.592  4222  4222 I bt_bluedroid: get_profile_interface gatt
09-09 14:24:59.592  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
09-09 14:24:59.593  4222  4222 D BtGatt.AdvertiseManager: advertise manager created
,09-09 14:24:59.603  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:24:59.603  4222  4222 V BluetoothAdapterState: isTurningOn()=false
09-09 14:24:59.603  4222  4222 V BluetoothAdapterState: isBleTurningOn()=true
09-09 14:24:59.603  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:24:59.604  4222  4234 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 14:24:59.605  4222  4234 I bt_bluedroid: enable
,09-09 14:24:59.605  4222  4235 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 14:24:59.606  4222  4235 I bt_hci  : start_up
,09-09 14:24:59.614  4222  4235 I bt_vendor: alloc value 0xb39ba189
,09-09 14:24:59.615  4222  4235 I bt_vendor: init
09-09 14:24:59.615  4222  4235 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 14:24:59.615  4222  4235 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 14:24:59.723  4222  4235 D bt_hci  : start_up starting async portion
,09-09 14:24:59.723  4222  4242 I bt_hci  : event_finish_startup
09-09 14:24:59.724  4222  4242 I bt_hci_h4: hal_open
09-09 14:24:59.724  4222  4242 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 14:24:59.734  4222  4242 I bt_userial_vendor: device fd = 51 open
,09-09 14:24:59.764  4222  4242 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 14:24:59.796  4222  4242 D bt_hwcfg: Chipset BCM4354A2
09-09 14:24:59.796  4222  4242 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 14:24:59.797  4222  4242 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 14:25:00.494  4222  4242 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 14:25:00.496  4222  4242 D bt_hwcfg: Settlement delay -- 100 ms
09-09 14:25:00.497  4222  4242 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 14:25:00.613  4222  4242 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-09 14:25:00.615  4222  4242 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 14:25:00.644  4222  4242 I bt_hwcfg: vendor lib fwcfg completed
,09-09 14:25:00.644  4222  4242 I bt_vendor: firmware callback
,09-09 14:25:00.645  4222  4242 I bt_hci  : firmware_config_callback
,09-09 14:25:00.655  4222  4244 I bt_btu  : btu_task pending for preload complete event
,09-09 14:25:00.656  4222  4244 I bt_btu_task: Bluetooth chip preload is complete
,09-09 14:25:00.656  4222  4244 I bt_btu  : btu_task received preload complete event
,09-09 14:25:00.666  4222  4244 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 14:25:00.666  4222  4244 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 14:25:00.667  4222  4244 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 14:25:00.667  4222  4244 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 14:25:00.668  4222  4244 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 14:25:00.668  4222  4244 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 14:25:00.668  4222  4244 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 14:25:00.668  4222  4244 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 14:25:00.669  4222  4244 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 14:25:00.669  4222  4244 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 14:25:00.669  4222  4244 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 14:25:00.670  4222  4244 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 14:25:00.670  4222  4244 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 14:25:00.670  4222  4244 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 14:25:00.670  4222  4244 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 14:25:00.805  4222  4244 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3937d9d
,09-09 14:25:00.805  4222  4244 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3937d9d 
,09-09 14:25:00.844  4222  4238 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 14:25:00.845  4222  4238 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 14:25:00.846  4222  4238 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 14:25:00.848  4222  4238 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 14:25:00.850  4222  4238 D BluetoothAdapterProperties: Scan Mode:20
,09-09 14:25:00.852  4222  4238 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 14:25:00.852  4222  4238 D bt_hci  : do_postload posting postload work item
,09-09 14:25:00.853  4222  4242 I bt_hci  : event_postload
,09-09 14:25:00.853  4222  4242 I bt_vendor: sco_config_cb
,09-09 14:25:00.853  4222  4242 I bt_hci  : sco_config_callback postload finished.
09-09 14:25:00.854  4222  4238 D bt_bte_conf: Device ID record 1 : primary
09-09 14:25:00.854  4222  4238 D bt_bte_conf:   vendorId            = 000f
,09-09 14:25:00.854  4222  4238 D bt_bte_conf:   vendorIdSource      = 0001
09-09 14:25:00.854  4222  4238 D bt_bte_conf:   product             = 1200
09-09 14:25:00.854  4222  4238 D bt_bte_conf:   version             = 1436
09-09 14:25:00.854  4222  4238 D bt_bte_conf:   clientExecutableURL = 
09-09 14:25:00.855  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:00.855  4222  4238 D bt_bte_conf:   serviceDescription  = 
,09-09 14:25:00.855  4222  4238 D bt_bte_conf:   documentationURL    = 
09-09 14:25:00.855  4222  4238 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 14:25:00.855  4222  4235 D bt_stack_manager: event_start_up_stack finished
09-09 14:25:00.856  4222  4234 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 14:25:00.857  4222  4234 D BluetoothAdapterProperties: Setting state to 15
09-09 14:25:00.857  4222  4234 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 14:25:00.858  4222  4234 I BluetoothAdapterState: Entering BleOnState
09-09 14:25:00.860  4222  4242 I bt_vendor: low_power_mode_cb
,09-09 14:25:00.863  4222  4234 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 14:25:00.865  4222  4234 D BluetoothAdapterProperties: Setting state to 11
,09-09 14:25:00.865  4222  4234 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 14:25:00.874  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:25:00.881  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
09-09 14:25:00.882  4222  4222 D HeadsetService: Received start request. Starting profile...
09-09 14:25:00.885  4222  4222 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:25:00.885  4222  4222 D HeadsetStateMachine: make
,09-09 14:25:00.898  4222  4234 I BluetoothAdapterState: Entering PendingCommandState
,09-09 14:25:00.899  4222  4222 D HeadsetStateMachine: max_hf_connections = 1
,09-09 14:25:00.899  4222  4222 I bt_bluedroid: get_profile_interface handsfree
09-09 14:25:00.900  4222  4238 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040,
09-09 14:25:00.900  4222  4238 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-09 14:25:00.904  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:25:00.904  4222  4222 D A2dpService: Received start request. Starting profile...
,09-09 14:25:00.905  4222  4222 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 14:25:00.905  4222  4222 I bt_bluedroid: get_profile_interface avrcp,
,09-09 14:25:00.910  4222  4222 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 14:25:00.911  4222  4222 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:25:00.911  4222  4222 D A2dpStateMachine: make
,09-09 14:25:00.912  4222  4222 I bt_bluedroid: get_profile_interface a2dp
,09-09 14:25:00.912  4222  4238 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 14:25:00.914  4222  4253 D A2dpStateMachine: Enter Disconnected: -2
,09-09 14:25:00.915  4222  4222 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 14:25:00.916  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
09-09 14:25:00.916  4222  4222 D HidService: Received start request. Starting profile...
09-09 14:25:00.916  4222  4222 I bt_bluedroid: get_profile_interface hidhost
09-09 14:25:00.916  4222  4238 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39193e5
,09-09 14:25:00.917  4222  4238 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 14:25:00.917  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:25:00.917  4222  4222 D HidService: setHidService(): set to: null
09-09 14:25:00.917  4222  4222 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 14:25:00.918  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:25:00.920   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 14:25:00.921  4222  4222 D HealthService: Received start request. Starting profile...
,09-09 14:25:00.922  1890  1890 I Keyboard.Facilitator: onFinishInput()
09-09 14:25:00.922  4222  4222 I bt_bluedroid: get_profile_interface health
,09-09 14:25:00.924  4222  4222 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 14:25:00.925  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:25:00.925  4222  4222 D PanService: Received start request. Starting profile...
,09-09 14:25:00.925  4222  4222 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 14:25:00.925  4222  4222 I bt_bluedroid: get_profile_interface pan
09-09 14:25:00.926  4222  4238 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 14:25:00.929  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:25:00.929  4222  4222 D BluetoothMapService: Received start request. Starting profile...
09-09 14:25:00.929  4222  4222 D BluetoothMapService: start()
,09-09 14:25:00.931  4222  4222 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 14:25:00.932  4222  4222 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 14:25:00.932  4222  4222 D BluetoothMapAppObserver: createReceiver()
,09-09 14:25:00.933  4222  4222 D BluetoothMapAppObserver: initObservers()
09-09 14:25:00.933  4222  4222 D BluetoothMapAppObserver: getEnabledAccountItems()
09-09 14:25:00.933   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 14:25:00.933   873   893 I Adreno  : Build Date                       : 10/20/15
09-09 14:25:00.933   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
,09-09 14:25:00.933   873   893 I Adreno  : Local Branch                     : M14
09-09 14:25:00.933   873   893 I Adreno  : Remote Branch                    : 
09-09 14:25:00.933   873   893 I Adreno  : Remote Branch                    : 
09-09 14:25:00.933   873   893 I Adreno  : Reconstruct Branch               : 
,09-09 14:25:00.941  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:25:00.944  4222  4222 V BluetoothAdapterState: isTurningOn()=true
,09-09 14:25:00.945  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:25:00.945  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:25:00.950  4222  4251 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 14:25:00.953  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:25:00.954  4222  4222 V BluetoothAdapterState: isTurningOn()=true
,09-09 14:25:00.956  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:25:00.960  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:25:00.961  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:25:00.962  4222  4222 V BluetoothAdapterState: isTurningOn()=true
,09-09 14:25:00.962  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 14:25:00.963  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:25:00.968  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:25:00.969   281   359 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (138 us)
09-09 14:25:00.969  4222  4222 V BluetoothAdapterState: isTurningOn()=true
09-09 14:25:00.969  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:25:00.970  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:25:00.970  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-09 14:25:00.970  4222  4222 V BluetoothAdapterState: isTurningOn()=true
09-09 14:25:00.970  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:25:00.970  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 14:25:00.970  4222  4222 V BluetoothAdapterState: isTurningOff()=false
09-09 14:25:00.970  4222  4222 V BluetoothAdapterState: isTurningOn()=true
09-09 14:25:00.970  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
09-09 14:25:00.970  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
09-09 14:25:00.971  4222  4234 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 14:25:00.971  4222  4234 D BluetoothAdapterProperties: ScanMode =  20
09-09 14:25:00.971  4222  4234 D BluetoothAdapterProperties: State =  11
09-09 14:25:00.971  4222  4234 D BluetoothAdapterProperties: Setting state to 12
09-09 14:25:00.971  4222  4234 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 14:25:00.972  3913  3924 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 14:25:00.973  4222  4238 D BluetoothAdapterProperties: Scan Mode:21
09-09 14:25:00.973  4222  4238 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:25:00.973  4222  4234 I BluetoothAdapterState: Entering OnState
,09-09 14:25:00.974  4222  4222 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 14:25:00.975  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:25:00.975  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:00.975  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:00.975  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:25:00.975  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:00.975  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:00.975  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:00.975  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:25:00.975  4222  4222 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 14:25:00.978   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 14:25:00.979  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:25:00.979  4222  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:25:00.983  4222  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:25:00.982   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:25:00.984  4222  4222 D ObexServerSockets: Succeed to create listening sockets 
09-09 14:25:00.984  1364  2058 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:25:00.987  3913  3926 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:25:00.985  4222  4222 D ObexServerSockets0: startAccept()
09-09 14:25:00.987  4222  4222 D ObexServerSockets0: prepareForNewConnect()
,09-09 14:25:00.990  4222  4258 D ObexServerSockets0: Accepting socket connection...
,09-09 14:25:00.989  4222  4222 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 14:25:00.990  4222  4259 D ObexServerSockets0: Accepting socket connection...
09-09 14:25:00.990  1364  1377 D BluetoothPan: onBluetoothStateChange on: true,
09-09 14:25:00.990  4222  4222 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-09 14:25:00.992   873   873 D BluetoothA2dp: Proxy object connected
09-09 14:25:00.992  3913  3924 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 14:25:00.993  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 14:25:00.993  3913  3913 D BluetoothInputDevice: Proxy object connected
09-09 14:25:00.993  1364  1364 D PanProfile: Bluetooth service connected
09-09 14:25:00.993  3913  3913 D HidProfile: Bluetooth service connected
,09-09 14:25:00.995   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:25:00.995  1958  2116 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:25:01.001  3913  3924 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 14:25:01.003   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:25:01.004  1364  2058 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 14:25:01.005  3913  3913 D BluetoothMap: Proxy object connected
,09-09 14:25:01.005  3913  3913 D MapProfile: Bluetooth service connected
09-09 14:25:01.005  3913  3913 D BluetoothMap: getConnectedDevices()
,09-09 14:25:01.005  1364  1364 D BluetoothA2dp: Proxy object connected
09-09 14:25:01.006  3913  3926 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 14:25:01.007  3913  3913 D BluetoothA2dp: Proxy object connected
09-09 14:25:01.008  1364  1384 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 14:25:01.010  1364  1364 D BluetoothMap: Proxy object connected
,09-09 14:25:01.010  1364  1364 D MapProfile: Bluetooth service connected
09-09 14:25:01.010  1364  1364 D BluetoothMap: getConnectedDevices()
,09-09 14:25:01.010  3913  3924 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:25:01.012  1364  2058 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 14:25:01.013  1364  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 14:25:01.013  3913  3913 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 14:25:01.014  3913  3913 D PanProfile: Bluetooth service connected
,09-09 14:25:01.015  1364  1364 D BluetoothInputDevice: Proxy object connected
,09-09 14:25:01.015  1364  1364 D HidProfile: Bluetooth service connected
09-09 14:25:01.015   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 14:25:01.016  4222  4222 D BluetoothMapService: onReceive
09-09 14:25:01.016  4222  4222 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:25:01.016  4222  4222 D BluetoothMapService: STATE_ON
,09-09 14:25:01.017  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:01.020  3913  3913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 14:25:01.026  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:25:01.029  3913  3913 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:25:01.038  3913  3913 D BluetoothPbap: Proxy object connected
,09-09 14:25:01.038  3913  3913 D PbapServerProfile: Bluetooth service connected
,09-09 14:25:01.039  1364  1364 D BluetoothPbap: Proxy object connected
09-09 14:25:01.039  1364  1364 D PbapServerProfile: Bluetooth service connected
,09-09 14:25:01.045  4222  4222 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 14:25:01.045  4222  4222 D ObexServerSockets0: prepareForNewConnect()
,09-09 14:25:01.051  4222  4266 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:25:01.060  4222  4270 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:25:01.064  4222  4270 I BtOppRfcommListener: Accept thread started.
,09-09 14:25:01.086   873   873 D BluetoothHeadset: Proxy object connected
,09-09 14:25:01.086  1364  1377 D BluetoothHeadset: Proxy object connected
09-09 14:25:01.087  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-09 14:25:01.087  3913  4260 D BluetoothHeadset: Proxy object connected
09-09 14:25:01.087   873   873 D BluetoothHeadset: Proxy object connected
,09-09 14:25:01.087  3913  3913 D HeadsetProfile: Bluetooth service connected
09-09 14:25:01.087  1958  2102 D BluetoothHeadset: Proxy object connected
09-09 14:25:01.088   873   873 D BluetoothHeadset: Proxy object connected
,09-09 14:25:01.089  3913  3924 D BluetoothHeadset: Proxy object connected
,09-09 14:25:01.093  3913  3913 D HeadsetProfile: Bluetooth service connected
,09-09 14:25:01.094   873   890 D BluetoothHeadset: Proxy object connected
,09-09 14:25:01.096  1958  1982 D BluetoothHeadset: Proxy object connected
,09-09 14:25:01.103   873   890 D BluetoothHeadset: Proxy object connected
,09-09 14:25:01.342  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:25:01.342  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:01.342  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:01.342  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:25:01.342  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:01.342  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:01.342  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:01.342  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:25:01.349  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:25:01.355  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:01.356  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@91f2336 added. We now have 8 listener(s)
09-09 14:25:01.357  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:25:01.363   873  2247 D WifiService: setWifiEnabled: false pid=3844, uid=10000
,09-09 14:25:01.363   873  2247 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:25:01.377  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:01.378   873  1968 D WifiService: setWifiEnabled: true pid=3844, uid=10000
,09-09 14:25:01.378   873  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:25:01.396   873  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-09 14:25:01.404  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:25:01.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:01.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:01.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:01.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:01.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:01.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:01.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:25:01.410  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:25:01.419   873  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-09 14:25:01.420   873  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 14:25:01.421   873  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 14:25:01.422   873  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 14:25:01.422   873  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 14:25:01.423   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 14:25:01.423   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 14:25:01.442   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 14:25:01.443   873  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.16 rxSuccessRate=0.23 delta 1000 -> 1000
,09-09 14:25:01.443   372   871 D CommandListener: Setting iface cfg
,09-09 14:25:01.445   873  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-09 14:25:01.445   873  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 14:25:01.449   873  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 14:25:01.449   873  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 14:25:01.457   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 14:25:01.457   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:25:01.464   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 14:25:01.574  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
09-09 14:25:01.574  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 14:25:01.617   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
09-09 14:25:01.617   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 14:25:01.620  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b25779e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c0a237, 16908290=android.view.AbsSavedState$1@c0a237}, android:focusedViewId=100}]}]
,09-09 14:25:01.620  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-09 14:25:01.620  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 14:25:01.620  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 14:25:01.621  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 14:25:01.640   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 14:25:01.643   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-09 14:25:01.644   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-09 14:25:01.644   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-09 14:25:01.877   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-09 14:25:01.880   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-09 14:25:01.882   873  1333 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
09-09 14:25:01.888   873   893 I DreamManagerService: Entering dreamland.
09-09 14:25:01.890   873   893 I PowerManagerService: Dozing...
,09-09 14:25:01.891   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 14:25:01.942   376  1278 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 14:25:01.942   376  1278 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 14:25:01.945   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 14:25:01.954   873  1306 E native  : do suspend false
,09-09 14:25:01.962  1945  4278 D NfcService: Discovery configuration equal, not updating.
,09-09 14:25:02.040   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 14:25:02.074   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 14:25:02.075  1461  1461 E wpa_supplicant: PNO: In assoc process
09-09 14:25:02.076   873  1306 E WifiStateMachine:  Fail to set up pno, want true now false
,09-09 14:25:02.078   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-09 14:25:02.078   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
09-09 14:25:02.079   873  1306 E native  : do suspend true
,09-09 14:25:02.204  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 14:25:02.280  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 14:25:02.281  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 14:25:02.294   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 14:25:02.307   873  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 14:25:02.308   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 14:25:02.308   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:25:02.331   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 14:25:02.346   372   871 D CommandListener: Setting iface cfg
,09-09 14:25:02.349   873  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 14:25:02.369   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 14:25:02.400  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:25:02.400  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:02.400  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:02.400  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:02.400  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:02.400  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:02.400  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:02.400  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:25:02.408   873  4287 D DhcpClient: Receive thread started
,09-09 14:25:02.408  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:25:02.423  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 14:25:02.426  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 14:25:02.433  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b25779e Bundle[{}]
,09-09 14:25:02.436  3844  3895 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 14:25:02.438  3844  3895 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 14:25:02.438  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 14:25:02.439  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 14:25:02.440  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 14:25:02.441  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 14:25:02.446  3844  3895 I System.out: Running OutgoingSocketThread
,09-09 14:25:02.449  3844  4288 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 432)
,09-09 14:25:02.451  3844  4288 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48662
,09-09 14:25:02.451  3844  4288 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 14:25:02.502   873  1306 E native  : do suspend false
,09-09 14:25:02.524   873  2098 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 14:25:02.541   873  4287 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-09 14:25:02.543   873  2098 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-09 14:25:02.546   873  2098 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 14:25:02.562   873  4287 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 14:25:02.563   873  2098 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 14:25:02.568   372   871 D CommandListener: Setting iface cfg
,09-09 14:25:02.580   873  2098 D DhcpClient: Scheduling renewal in 86399s
,09-09 14:25:02.580   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 14:25:02.585   873  1306 E native  : do suspend true
,09-09 14:25:02.610   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 14:25:02.614   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 14:25:02.615   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 14:25:02.618   873  1308 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 14:25:02.622   873  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 14:25:02.682   873  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
09-09 14:25:02.682   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 14:25:02.683   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 14:25:02.686   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 14:25:02.688   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 14:25:02.691   873  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 14:25:02.706   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 14:25:02.715   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-09 14:25:02.716   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-09 14:25:02.716   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 14:25:02.716   873  1308 D ConnectivityService:    accepting network in place of null
09-09 14:25:02.716   873  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 14:25:02.717   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 14:25:02.717   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 14:25:02.737   873  4286 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154747, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:25:02.762   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:25:02.809   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 14:25:02.818   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 14:25:02.819   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:25:02.828   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-09 14:25:02.833   873  4285 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 14:25:02.836   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-09 14:25:02.847  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:25:02.847  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:02.847  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:02.847  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:02.847  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:02.847  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:25:02.847  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:25:02.847  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:25:02.852  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:25:02.857  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 14:25:02.865  1719  1719 D SystemUpdateService: onCreate
,09-09 14:25:02.869  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 14:25:02.882  1719  4297 I SystemUpdateService: active receiver: enabled
,09-09 14:25:02.887  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 14:25:02.893  1719  2520 I iu.UploadsManager: num queued entries: 0
,09-09 14:25:02.893  1719  2520 I iu.UploadsManager: num updated entries: 0
,09-09 14:25:02.894  1719  4297 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 14:25:02.896  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 14:25:02.899  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 14:25:02.900  1719  4297 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-09 14:25:02.900   873  4285 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 12:25:02 GMT], X-Android-Received-Millis=[1473423902900], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473423902873]}
09-09 14:25:02.900  1719  4297 I SystemUpdateService: now status is 0 (complete)
,09-09 14:25:02.900  1719  4297 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 14:25:02.901  1719  4297 I SystemUpdateService: file has been verified
,09-09 14:25:02.901  1719  4297 I SystemUpdateService: OTA package size = 12249756
,09-09 14:25:02.901  4030  4030 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:25:02.902  1719  2520 I iu.SyncManager: NEXT; no task
09-09 14:25:02.903   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 14:25:02.903   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 14:25:02.903   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 14:25:02.905   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
09-09 14:25:02.908  1719  4300 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 14:25:02.908  1719  4300 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 14:25:02.909  4030  4030 D SprintDMHelper: simOperator: 
,09-09 14:25:02.910  4030  4030 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 14:25:02.915  1719  4300 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 14:25:02.924  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:25:02.928  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 14:25:02.938  1719  4297 I SystemUpdateService: showing system update notification
,09-09 14:25:02.978  1719  1719 D SystemUpdateService: onDestroy
,09-09 14:25:02.987  1499  2291 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-09 14:25:02.987  1499  2291 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 14:25:02.987  1499  2291 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 14:25:02.987  1499  2291 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 14:25:03.016  1719  4300 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-09 14:25:03.042  3964  4303 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 14:25:03.271  1499  2246 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 14:25:03.449  3844  3895 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 433)
,09-09 14:25:03.450  3844  3895 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 433)
,09-09 14:25:03.463  3844  3895 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,09-09 14:25:03.466  3844  3895 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 14:25:03.467  3844  3895 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 439)
,09-09 14:25:03.471  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 14:25:03.471  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc03a4 added. We now have 2 listener(s)
09-09 14:25:03.473  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:25:03.473  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:03.473  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:03.473  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:25:03.473  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@941b50d added. We now have 9 listener(s)
09-09 14:25:03.473  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:03.474  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 14:25:03.479  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:25:03.488  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:03.488  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:03.488  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:03.488  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:03.488  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:03.488  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:25:03.488  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:25:03.488  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:25:03.493  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:25:03.494  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:25:03.494  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-09 14:25:03.494  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f32ad3 added. We now have 3 listener(s)
,09-09 14:25:03.500  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:25:03.500  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:03.501  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:25:03.501  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:03.501  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:25:03.502  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac7b610 added. We now have 10 listener(s)
09-09 14:25:03.502  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:25:03.502  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:25:03.503  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:03.503  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 14:25:03.503  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:03.503  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.504  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:03.504  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 14:25:03.504  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc03a4 removed from the list
09-09 14:25:03.504  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.505  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@941b50d removed from the list
,09-09 14:25:03.508  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:25:03.509  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:25:03.509  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:25:03.510  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.511  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:25:03.513  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:25:03.513  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:03.513  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.514  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@941b50d not in the list
,09-09 14:25:03.514  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.514  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:25:03.516  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:25:03.517  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:25:03.517  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.517  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac7b610 removed from the list
,09-09 14:25:03.517  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:25:03.517  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.518  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.518  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 14:25:03.518  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f32ad3 removed from the list
,09-09 14:25:03.520  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 14:25:03.520  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e19509 added. We now have 2 listener(s)
,09-09 14:25:03.526  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:25:03.526  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:25:03.527  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:03.528  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:25:03.528  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96b630e added. We now have 9 listener(s)
09-09 14:25:03.528  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:03.529  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 14:25:03.534  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:25:03.542  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:03.542  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:03.542  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:03.542  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:03.542  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:03.542  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:25:03.542  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:25:03.542  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:25:03.546  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:25:03.547  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:25:03.547  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 14:25:03.547  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55a233c added. We now have 3 listener(s)
,09-09 14:25:03.552  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:25:03.552  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:03.552  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:03.552  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:03.553  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:03.553  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8578c5 added. We now have 10 listener(s)
,09-09 14:25:03.553  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:03.553  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:03.554  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 14:25:03.554  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:25:03.554  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:03.554  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 14:25:03.557  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:25:03.560  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 14:25:03.560  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 14:25:03.569  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 14:25:03.570  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 14:25:03.570  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:25:03.574  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 14:25:03.574  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:25:03.574  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 14:25:03.576  3844  3895 D BluetoothAdapter: STATE_ON
,09-09 14:25:03.580  4222  4271 D BtGatt.GattService: registerClient() - UUID=091c5bb3-1dce-4f3e-92c8-1dc5b6b9d408
,09-09 14:25:03.581  4222  4238 D BtGatt.GattService: onClientRegistered() - UUID=091c5bb3-1dce-4f3e-92c8-1dc5b6b9d408, clientIf=5
,09-09 14:25:03.582  3844  3856 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 14:25:03.583  4222  4262 D BtGatt.GattService: start scan with filters
,09-09 14:25:03.587  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 14:25:03.587  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:25:03.587  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:25:03.587  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 14:25:03.588  4222  4241 D BtGatt.ScanManager: handling starting scan
,09-09 14:25:03.590  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:25:03.590  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 14:25:03.590  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:25:03.592  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 14:25:03.592  4222  4241 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c12852
,09-09 14:25:03.594  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 14:25:03.595  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:03.595  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 14:25:03.595  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.595  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 14:25:03.595  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:25:03.595  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 14:25:03.595  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:25:03.595  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:25:03.595  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 14:25:03.595  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:25:03.596  3844  3895 D BluetoothAdapter: STATE_ON
,09-09 14:25:03.597  4222  4271 D BtGatt.GattService: stopScan() - queue size =1
09-09 14:25:03.598  4222  4262 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 14:25:03.598  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:25:03.598  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 14:25:03.599  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 14:25:03.599  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:25:03.599  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 14:25:03.600  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:25:03.600  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 14:25:03.600  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:25:03.600  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:25:03.601  4222  4238 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 14:25:03.601  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.601  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:25:03.603  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:25:03.603  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:25:03.603  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:25:03.605  4222  4241 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 14:25:03.606  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:25:03.606  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:03.606  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:03.606  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:25:03.606  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.607  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:03.607  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 14:25:03.607  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e19509 removed from the list,
09-09 14:25:03.607  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:25:03.607  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96b630e removed from the list
09-09 14:25:03.607  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 14:25:03.607  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:25:03.608  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.608  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:25:03.611  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:03.611  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:03.611  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:25:03.611  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96b630e not in the list
,09-09 14:25:03.611  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.611  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.612  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:03.612  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:03.612  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.612  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8578c5 removed from the list
,09-09 14:25:03.612  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:03.612  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.612  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.613  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 14:25:03.613  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55a233c removed from the list
09-09 14:25:03.614  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:25:03.614  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.614  4222  4241 D BtGatt.ScanManager: Starting BLE batch scan
09-09 14:25:03.614  4222  4241 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 14:25:03.615  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:03.615  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9dc41 added. We now have 2 listener(s)
09-09 14:25:03.617  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:25:03.617  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:03.617  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:03.617  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:03.617  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@454c5e6 added. We now have 9 listener(s)
09-09 14:25:03.618  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:03.618  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:25:03.621  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:25:03.626  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:03.626  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:03.626  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:03.626  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:03.626  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:03.626  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:25:03.626  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:25:03.626  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:25:03.626  4222  4238 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:25:03.626  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:25:03.628  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:25:03.628  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:25:03.628  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:03.628  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1399dd4 added. We now have 3 listener(s)
,09-09 14:25:03.630  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:25:03.631  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:25:03.632  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:03.632  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:03.632  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:25:03.632  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:03.632  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:25:03.632  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:03.632  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@996fb7d added. We now have 10 listener(s)
09-09 14:25:03.633  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:03.633  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:03.633  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:03.634  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 14:25:03.634  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:25:03.634  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:03.634  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 14:25:03.637  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 14:25:03.637  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 14:25:03.639  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 14:25:03.639  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.639  4222  4241 D BtGatt.ScanManager: stopping BLe Batch
,09-09 14:25:03.641  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 14:25:03.641  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 14:25:03.641  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:25:03.644  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 14:25:03.644  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:25:03.644  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 14:25:03.645  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:25:03.645  3844  3895 D BluetoothAdapter: STATE_ON
,09-09 14:25:03.645  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.645  4222  4241 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 14:25:03.647  4222  4232 D BtGatt.GattService: registerClient() - UUID=720b5fcf-b95e-447e-ae64-91e00a6bf7cf
09-09 14:25:03.647  4222  4238 D BtGatt.GattService: onClientRegistered() - UUID=720b5fcf-b95e-447e-ae64-91e00a6bf7cf, clientIf=5
09-09 14:25:03.647  3844  3856 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 14:25:03.647  4222  4271 D BtGatt.GattService: start scan with filters
,09-09 14:25:03.650  4222  4238 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 14:25:03.650  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.651  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 14:25:03.651  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:25:03.651  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:25:03.651  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 14:25:03.652  4222  4241 D BtGatt.ScanManager: handling starting scan
,09-09 14:25:03.653  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 14:25:03.654  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 14:25:03.654  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:25:03.655  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 14:25:03.657  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 14:25:03.657  3844  3895 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 14:25:03.657  4222  4238 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 14:25:03.657  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.657  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:25:03.658  4222  4241 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 14:25:03.658  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:03.658  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:03.658  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:03.658  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.658  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 14:25:03.658  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:03.658  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9dc41 removed from the list
09-09 14:25:03.658  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:25:03.658  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@454c5e6 removed from the list
09-09 14:25:03.658  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:25:03.658  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:25:03.659  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.659  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 14:25:03.659  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.659  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:03.660  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:03.660  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:03.660  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.660  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@454c5e6 not in the list
09-09 14:25:03.660  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 14:25:03.660  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:25:03.660  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:25:03.660  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:25:03.660  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 14:25:03.661  3844  3895 D BluetoothAdapter: STATE_ON
09-09 14:25:03.661  4222  4271 D BtGatt.GattService: stopScan() - queue size =1
09-09 14:25:03.662  4222  4262 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 14:25:03.662  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 14:25:03.662  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 14:25:03.662  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 14:25:03.663  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:25:03.663  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:25:03.663  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 14:25:03.663  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.663  4222  4241 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 14:25:03.663  4222  4241 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 14:25:03.663  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:25:03.663  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 14:25:03.664  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:25:03.664  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:25:03.664  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.665  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:25:03.665  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:03.665  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.665  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@996fb7d removed from the list
09-09 14:25:03.665  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:25:03.665  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:03.665  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.665  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.665  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:25:03.665  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:03.665  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:25:03.665  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1399dd4 removed from the list
09-09 14:25:03.666  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 14:25:03.666  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1cd279 added. We now have 2 listener(s)
09-09 14:25:03.667  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:25:03.668  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:25:03.668  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:25:03.668  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:03.668  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fcabbe added. We now have 9 listener(s)
09-09 14:25:03.668  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:03.668  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:25:03.670  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:25:03.672  4222  4238 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:25:03.672  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:25:03.673  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:03.673  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:03.673  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:03.673  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:03.673  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:03.673  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:25:03.673  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:25:03.673  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:25:03.675  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:25:03.675  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:25:03.675  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 14:25:03.675  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ad36c added. We now have 3 listener(s)
,09-09 14:25:03.677  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:25:03.677  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:25:03.678  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:25:03.679  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:25:03.679  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:03.679  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:03.679  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:03.679  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:03.679  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8f1d35 added. We now have 10 listener(s)
09-09 14:25:03.679  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:03.679  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:03.679  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:25:03.679  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:25:03.680  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:03.680  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:25:03.682  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 14:25:03.682  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 14:25:03.684  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 14:25:03.684  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:25:03.684  4222  4241 D BtGatt.ScanManager: stopping BLe Batch
,09-09 14:25:03.686  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 14:25:03.686  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 14:25:03.686  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:25:03.689  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 14:25:03.689  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 14:25:03.689  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 14:25:03.689  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 14:25:03.690  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.690  4222  4241 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 14:25:03.690  3844  3895 D BluetoothAdapter: STATE_ON
,09-09 14:25:03.691  4222  4271 D BtGatt.GattService: registerClient() - UUID=9fa79caa-fbdb-4956-a537-1325aedc8b1f
,09-09 14:25:03.692  4222  4238 D BtGatt.GattService: onClientRegistered() - UUID=9fa79caa-fbdb-4956-a537-1325aedc8b1f, clientIf=5
,09-09 14:25:03.693  3844  3856 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 14:25:03.693  4222  4232 D BtGatt.GattService: start scan with filters
,09-09 14:25:03.694  4222  4238 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 14:25:03.695  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.695  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 14:25:03.695  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 14:25:03.695  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 14:25:03.695  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 14:25:03.697  4222  4241 D BtGatt.ScanManager: handling starting scan
,09-09 14:25:03.697  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:25:03.698  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 14:25:03.698  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 14:25:03.699  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 14:25:03.702  4222  4238 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 14:25:03.702  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.702  4222  4241 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 14:25:03.703  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:25:03.703  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 14:25:03.703  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:03.703  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:03.703  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.703  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 14:25:03.703  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 14:25:03.703  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1cd279 removed from the list
09-09 14:25:03.703  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.703  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fcabbe removed from the list
09-09 14:25:03.703  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:25:03.703  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:25:03.704  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.704  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 14:25:03.704  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.704  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:25:03.705  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:25:03.705  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:25:03.705  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.705  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fcabbe not in the list
09-09 14:25:03.705  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:25:03.705  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 14:25:03.705  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:25:03.705  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:25:03.705  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 14:25:03.706  3844  3895 D BluetoothAdapter: STATE_ON
09-09 14:25:03.706  4222  4249 D BtGatt.GattService: stopScan() - queue size =1
,09-09 14:25:03.707  4222  4232 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 14:25:03.707  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 14:25:03.707  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 14:25:03.707  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.707  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 14:25:03.707  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 14:25:03.707  4222  4241 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 14:25:03.707  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 14:25:03.707  4222  4241 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 14:25:03.707  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 14:25:03.708  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 14:25:03.708  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 14:25:03.708  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:25:03.708  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 14:25:03.709  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.709  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:25:03.710  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 14:25:03.710  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:25:03.710  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.710  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 14:25:03.710  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8f1d35 removed from the list
,09-09 14:25:03.710  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:03.710  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.710  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:25:03.710  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:03.710  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ad36c removed from the list
,09-09 14:25:03.710  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 14:25:03.711  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 14:25:03.711  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a157b1 added. We now have 2 listener(s)
,09-09 14:25:03.713  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 14:25:03.713  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:25:03.713  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:03.713  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:03.714  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1507496 added. We now have 9 listener(s)
,09-09 14:25:03.714  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:03.714  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 14:25:03.716  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:03.716  4222  4238 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 14:25:03.716  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.719  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:03.719  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:03.719  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 14:25:03.719  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:03.719  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:03.719  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:25:03.719  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:25:03.719  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:25:03.721  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:25:03.721  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:25:03.721  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:03.721  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ea2404 added. We now have 3 listener(s)
09-09 14:25:03.721  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 14:25:03.721  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 14:25:03.723  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:03.724  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 14:25:03.724  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:03.724  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:03.724  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:25:03.724  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c2bded added. We now have 10 listener(s)
09-09 14:25:03.725  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:03.725  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:25:03.725  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:03.725  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:03.725  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:03.725  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:25:03.725  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:03.725  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:03.725  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a157b1 removed from the list
09-09 14:25:03.726  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.726  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1507496 removed from the list
09-09 14:25:03.726  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:03.727  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 14:25:03.727  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.727  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:25:03.727  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.727  4222  4241 D BtGatt.ScanManager: stopping BLe Batch
09-09 14:25:03.727  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.727  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.728  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 14:25:03.728  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:03.728  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.728  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1507496 not in the list
,09-09 14:25:03.729  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.729  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.729  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:03.729  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:03.730  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:03.730  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c2bded removed from the list
09-09 14:25:03.730  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:25:03.730  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:03.730  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:03.730  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:03.730  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ea2404 removed from the list
,09-09 14:25:03.731  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 14:25:03.731  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 14:25:03.731  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 14:25:03.731  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:03.731  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 14:25:03.731  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:03.732  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 14:25:03.732  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.732  4222  4241 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 14:25:03.736  3844  4311 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: My test thread name)
09-09 14:25:03.736  3844  4311 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: My test thread name)
09-09 14:25:03.736  4222  4238 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 14:25:03.737  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 14:25:03.737  3844  4311 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 14:25:03.738  3844  4312 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
,09-09 14:25:03.738  3844  4312 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
09-09 14:25:03.738  3844  4312 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 14:25:03.740  3844  3895 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-09 14:25:03.740  3844  3895 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 14:25:03.740  3844  3895 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 14:25:03.740  3844  3895 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 14:25:03.740  3844  3895 D com.test.thalitest.ThaliTestRunner: Total duration: 22825 ms
,09-09 14:25:03.742  3844  3895 I jxcore-log: *Native tests were executed*
09-09 14:25:03.742  3844  3895 I jxcore-log: 
,09-09 14:25:03.742  3844  3895 I jxcore-log: Total number of executed tests:  80
09-09 14:25:03.742  3844  3895 I jxcore-log: 
09-09 14:25:03.742  3844  3895 I jxcore-log: Number of passed tests:  80
09-09 14:25:03.742  3844  3895 I jxcore-log: 
09-09 14:25:03.742  3844  3895 I jxcore-log: Number of failed tests:  0
09-09 14:25:03.742  3844  3895 I jxcore-log: 
09-09 14:25:03.742  3844  3895 I jxcore-log: Number of ignored tests:  0
09-09 14:25:03.742  3844  3895 I jxcore-log: 
,09-09 14:25:03.743  3844  3895 I jxcore-log: Total duration:  22825
09-09 14:25:03.743  3844  3895 I jxcore-log: 
09-09 14:25:03.743  3844  3895 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 14:25:03.743  3844  3895 I jxcore-log: 
,09-09 14:25:03.746  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.746  3844  3895 I jxcore-log: 
09-09 14:25:03.750  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.750  3844  3895 I jxcore-log: 
09-09 14:25:03.750  3844  3844 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 14:25:03.751  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.751  3844  3895 I jxcore-log: 
09-09 14:25:03.752  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.752  3844  3895 I jxcore-log: 
09-09 14:25:03.752  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.752  3844  3895 I jxcore-log: 
09-09 14:25:03.753  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.753  3844  3895 I jxcore-log: 
,09-09 14:25:03.755  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.755  3844  3895 I jxcore-log: 
,09-09 14:25:03.757  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:25:03.757  3844  3895 I jxcore-log: 
,09-09 14:25:03.757  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:25:03.757  3844  3895 I jxcore-log: 
09-09 14:25:03.758  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.758  3844  3895 I jxcore-log: 
,09-09 14:25:03.758  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.758  3844  3895 I jxcore-log: 
,09-09 14:25:03.759  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:25:03.759  3844  3895 I jxcore-log: 
,09-09 14:25:03.760  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:25:03.760  3844  3895 I jxcore-log: 
,09-09 14:25:03.761  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:25:03.761  3844  3895 I jxcore-log: 
,09-09 14:25:03.761  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.761  3844  3895 I jxcore-log: 
,09-09 14:25:03.762  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.762  3844  3895 I jxcore-log: 
09-09 14:25:03.762  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.762  3844  3895 I jxcore-log: 
,09-09 14:25:03.763  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.763  3844  3895 I jxcore-log: 
,09-09 14:25:03.764  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.764  3844  3895 I jxcore-log: 
09-09 14:25:03.764  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.764  3844  3895 I jxcore-log: 
,09-09 14:25:03.765  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.765  3844  3895 I jxcore-log: 
09-09 14:25:03.765  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.765  3844  3895 I jxcore-log: 
,09-09 14:25:03.766  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.766  3844  3895 I jxcore-log: 
,09-09 14:25:03.766  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:25:03.766  3844  3895 I jxcore-log: 
,09-09 14:25:03.767  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:25:03.767  3844  3895 I jxcore-log: 
,09-09 14:25:03.768  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:25:03.768  3844  3895 I jxcore-log: 
09-09 14:25:03.768  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.768  3844  3895 I jxcore-log: 
,09-09 14:25:03.768  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.768  3844  3895 I jxcore-log: 
09-09 14:25:03.769  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.769  3844  3895 I jxcore-log: 
,09-09 14:25:03.769  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.769  3844  3895 I jxcore-log: 
,09-09 14:25:03.770  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.770  3844  3895 I jxcore-log: 
,09-09 14:25:03.770  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:03.770  3844  3895 I jxcore-log: 
,09-09 14:25:03.817   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 14:25:04.104  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 14:25:04.107  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:25:04.107  3844  3895 I jxcore-log: 
,09-09 14:25:04.166  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 14:25:04.168  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:25:04.168  3844  3895 I jxcore-log: 
,09-09 14:25:04.210  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 14:25:04.213  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:25:04.213  3844  3895 I jxcore-log: 
,09-09 14:25:04.381  4313  4313 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-09 14:25:04.386  4313  4313 D AndroidRuntime: CheckJNI is OFF
,09-09 14:25:04.429  4313  4313 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-09 14:25:04.477  4313  4313 I Radio-JNI: register_android_hardware_Radio DONE
,09-09 14:25:04.499  4313  4313 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 14:25:04.512   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-09 14:25:04.513   873   886 I ActivityManager: Killing 3844:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-09 14:25:04.615   873  1983 I WindowState: WIN DEATH: Window{b605f95 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 14:25:04.615   873  1968 D GraphicsStats: Buffer count: 2
,09-09 14:25:04.616   873  1307 D WifiService: Client connection lost with reason: 4
,09-09 14:25:04.654   873   896 W PackageSettings: Skipping PackageSetting{e38717 com.example.hello/10273} due to missing metadata
,09-09 14:25:04.677   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-09 14:25:04.678   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-09 14:25:04.678   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-09 14:25:04.678   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 14:25:04.678   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:04.678   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:04.678   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:25:04.678   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 14:25:04.679   873   886 I ActivityManager:   Force finishing activity ActivityRecord{3ac81f2 u0 com.test.thalitest/.MainActivity t4}
,09-09 14:25:04.682   873   896 I art     : Starting a blocking GC Explicit
,09-09 14:25:04.695   873   883 W ActivityManager: Spurious death for ProcessRecord{f271930 0:com.test.thalitest/u0a0}, curProc for 3844: null
,09-09 14:25:04.757   873   896 I art     : Explicit concurrent mark sweep GC freed 44946(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 854us total 71.976ms
,09-09 14:25:04.788   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-09 14:25:04.794  4313  4313 I art     : System.exit called, status: 0
,09-09 14:25:04.794  4313  4313 I AndroidRuntime: VM exiting with result code 0.
09-09 14:25:04.795   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-09 14:25:04.823   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-09 14:25:04.827  4222  4222 D BluetoothMapAppObserver: onReceive
,09-09 14:25:04.827  4222  4222 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-09 14:25:04.831  1890  1890 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-09 14:25:04.832  1859  2268 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 14:25:04.834  3689  3689 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-09 14:25:04.836   873  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 14:25:04.838  1890  4324 I Keyboard.Facilitator.DecoderInitializer: run()
,09-09 14:25:04.841  1890  4324 I Decoder : createOrResetDecoder
,09-09 14:25:04.874   873  1968 I ActivityManager: Start proc 4327:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-09 14:25:04.886  1958  1958 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-09 14:25:04.922   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 14:25:04.927  1499  1499 I ConfigService: onCreate
,09-09 14:25:04.929  1499  4339 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 14:25:04.929  1499  4339 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 14:25:04.929  1499  4339 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:25:04.931  1499  4339 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-09 14:25:04.941  1974  2065 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 14:25:04.941  1890  4324 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-09 14:25:04.944   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-09 14:25:04.947   873   885 E PackageManager: Failed to write settings, restoring backup
09-09 14:25:04.947   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 14:25:04.947   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 14:25:04.947   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 14:25:04.947   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 14:25:04.947   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 14:25:04.947   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:04.947   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:04.947   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 14:25:04.949   873  1968 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3844 uid 10000
,09-09 14:25:04.950  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-09 14:25:04.951   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-09 14:25:04.951   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 14:25:04.951   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:25:04.951   873   886 E DropBoxManagerService: 	... 13 more
,09-09 14:25:04.952  4327  4327 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-09 14:25:04.956   873  2248 I ActivityManager: Start proc 4340:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-09 14:25:04.957  1974  2065 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 14:25:04.957  1974  2065 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1974
09-09 14:25:04.957  1974  2065 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:04.957  1974  2065 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 14:25:04.959   873  4345 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:25:04.959   873  4345 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:25:04.959   873  4345 E DropBoxManagerService: 	... 5 more
,09-09 14:25:04.959   873  1964 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 14:25:04.962  1974  2065 I Process : Sending signal. PID: 1974 SIG: 9
,09-09 14:25:04.997  1890  4324 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-09 14:25:04.999  1890  4324 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-09 14:25:04.999  1890  4324 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-09 14:25:05.001  1890  4324 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-09 14:25:05.001  1890  4324 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-09 14:25:05.002  1890  4324 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-09 14:25:05.002  1890  4324 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-09 14:25:05.004  1890  4324 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-09 14:25:05.005  1890  4324 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 14:25:05.005  1890  4324 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-09 14:25:05.005  1890  4324 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 14:25:05.006  1890  4324 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-09 14:25:05.006  1890  4324 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-09 14:25:05.051   873  2250 D GraphicsStats: Buffer count: 1
,09-09 14:25:05.052   873  1964 I WindowState: WIN DEATH: Window{5f5f4d6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-09 14:25:05.062   873  1394 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1974) has died
,09-09 14:25:05.062   873  1394 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 14:25:05.063   873  1394 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 14:25:05.077   873   886 I ActivityManager: Start proc 4358:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 14:25:05.094  4327  4327 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-09 14:25:05.133   873  1944 I ActivityManager: Start proc 4372:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-09 14:25:05.137  4358  4358 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:25:05.137  4358  4358 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:25:05.138  4358  4358 D AndroidRuntime: Shutting down VM
,09-09 14:25:05.141  4327  4377 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-09 14:25:05.145  4358  4358 E AndroidRuntime: FATAL EXCEPTION: main
09-09 14:25:05.145  4358  4358 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4358
09-09 14:25:05.145  4358  4358 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 14:25:05.145  4358  4358 E AndroidRuntime: 	... 10 more
,09-09 14:25:05.146   873   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 14:25:05.147  4358  4358 I Process : Sending signal. PID: 4358 SIG: 9
,09-09 14:25:05.147   873  4378 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:25:05.147   873  4378 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:25:05.147   873  4378 E DropBoxManagerService: 	... 5 more
,09-09 14:25:05.171   873  2250 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4358) has died
,09-09 14:25:05.173   873  2250 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 14:25:05.174  1719  4371 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-09 14:25:05.175  1719  4371 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-09 14:25:05.187   873   886 I ActivityManager: Start proc 4386:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 14:25:05.190  1719  4371 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-09 14:25:05.190  1719  4371 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-09 14:25:05.196  4372  4372 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-09 14:25:05.201  4327  4356 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:05.201  4327  4356 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:05.202  4327  4356 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 14:25:05.216  1499  1499 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-09 14:25:05.216  1499  1499 D AndroidRuntime: Shutting down VM
09-09 14:25:05.217  1499  1499 E AndroidRuntime: FATAL EXCEPTION: main
09-09 14:25:05.217  1499  1499 E AndroidRuntime: Process: com.google.process.gapps, PID: 1499
09-09 14:25:05.217  1499  1499 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 14:25:05.217  1499  1499 E AndroidRuntime: 	... 8 more
,09-09 14:25:05.221  1499  1499 I Process : Sending signal. PID: 1499 SIG: 9
,09-09 14:25:05.221   873  4400 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:25:05.221   873  4400 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
,09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:25:05.221   873  4400 E DropBoxManagerService: 	... 5 more
,09-09 14:25:05.244  4386  4386 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:25:05.244  4386  4386 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 14:25:05.244  4386  4386 D AndroidRuntime: Shutting down VM
,09-09 14:25:05.253  4386  4386 E AndroidRuntime: FATAL EXCEPTION: main
09-09 14:25:05.253  4386  4386 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4386
09-09 14:25:05.253  4386  4386 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 14:25:05.253  4386  4386 E AndroidRuntime: 	... 10 more
,09-09 14:25:05.254  4327  4356 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-09 14:25:05.254   873  1371 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 14:25:05.255  4386  4386 I Process : Sending signal. PID: 4386 SIG: 9
09-09 14:25:05.255   873  4402 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:25:05.255   873  4402 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:25:05.255   873  4402 E DropBoxManagerService: 	... 5 more
,09-09 14:25:05.257   873  1307 D WifiService: Client connection lost with reason: 4
09-09 14:25:05.261   873   884 I ActivityManager: Process com.google.process.gapps (pid 1499) has died
,09-09 14:25:05.262   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-09 14:25:05.262   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
09-09 14:25:05.262   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
,09-09 14:25:05.262   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
,09-09 14:25:05.273  1719  1719 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-09 14:25:05.282   873  1371 I ActivityManager: Start proc 4403:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService

```
