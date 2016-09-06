#### Test 83268893665f77c_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-06 16:55:40.208  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 16:55:40.227  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 16:55:40.233  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 16:55:40.320  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-06 16:55:40.320  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-06 16:55:40.320  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 16:55:40.321  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-06 16:55:40.362  3583  3583 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-06 16:55:40.363  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-06 16:55:40.364  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
09-06 16:55:40.880  3849  3849 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-06 16:55:40.885  3849  3849 D AndroidRuntime: CheckJNI is OFF
09-06 16:55:40.921  3849  3849 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-06 16:55:40.963  3849  3849 I Radio-JNI: register_android_hardware_Radio DONE
09-06 16:55:40.983  3849  3849 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 16:55:40.988   876  2117 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 16:55:41.029  3849  3849 D AndroidRuntime: Shutting down VM
09-06 16:55:41.039  2099  2116 W SearchService: Abort, client detached.
09-06 16:55:41.045  2099  2099 I HotwordDetector: Closing mic
09-06 16:55:41.046  2099  2346 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@f93c281
09-06 16:55:41.047  2099  2355 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-06 16:55:41.064   876  2121 I ActivityManager: Start proc 3860:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-06 16:55:41.111   378  2357 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-06 16:55:41.113   378  2357 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-06 16:55:41.125   378  1289 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-06 16:55:41.128  2099  2353 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-06 16:55:41.129  2099  2354 I MicroRecognitionRnrImpl: Detection finished
09-06 16:55:41.144  3860  3860 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-06 16:55:41.166  3860  3860 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-06 16:55:41.176  3860  3860 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 1253-1259)
09-06 16:55:41.176  3860  3860 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 16:55:41.196  3860  3860 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b6e1438}
09-06 16:55:41.197  3860  3860 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 16:55:41.198  3860  3860 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 16:55:41.206  3860  3860 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-06 16:55:41.207  3860  3860 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 16:55:41.227  3860  3860 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-06 16:55:41.236  3860  3860 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 16:55:41.237  3860  3860 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 16:55:41.237  3860  3860 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 16:55:41.237  3860  3860 I Adreno  : Build Date                       : 10/20/15
09-06 16:55:41.237  3860  3860 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 16:55:41.237  3860  3860 I Adreno  : Local Branch                     : M14
09-06 16:55:41.237  3860  3860 I Adreno  : Remote Branch                    : 
09-06 16:55:41.237  3860  3860 I Adreno  : Remote Branch                    : 
09-06 16:55:41.237  3860  3860 I Adreno  : Reconstruct Branch               : 
,09-06 16:55:41.331   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed0b895:true
,09-06 16:55:41.361  3860  3860 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-06 16:55:41.376  3860  3860 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-06 16:55:41.455  3860  3898 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-06 16:55:41.469  3860  3885 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,09-06 16:55:41.508  3860  3898 I OpenGLRenderer: Initialized EGL, version 1.4
,09-06 16:55:41.601   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +553ms
,09-06 16:55:41.602  1894  1894 I Keyboard.Facilitator: onFinishInput()
,09-06 16:55:41.669  3860  3860 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3860
,09-06 16:55:41.775  3860  3860 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 16:55:41.861   876  1704 I ActivityManager: Killing 2982:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-06 16:55:41.904   876  1704 I ActivityManager: Killing 3249:com.google.android.gm/u0a78 (adj 15): empty #18
,09-06 16:55:42.038  3860  3900 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1683818192
,09-06 16:55:42.057  3860  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 16:55:42.057  3860  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 16:55:42.057  3860  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 16:55:42.057  3860  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 16:55:42.057  3860  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 16:55:42.058  3860  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d74ac3c added. We now have 1 listener(s)
,09-06 16:55:42.064  3860  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61,
09-06 16:55:42.065  3860  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 16:55:42.066  3860  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 16:55:42.066  3860  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-06 16:55:42.069  3860  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249fe4b added. We now have 1 listener(s)
,09-06 16:55:42.069  3860  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:55:42.072  3860  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 16:55:42.071   876  1318 D WifiService: New client listening to asynchronous messages
,09-06 16:55:42.072  3860  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 16:55:42.072  3860  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-06 16:55:42.072  3860  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 16:55:42.072  3860  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 16:55:42.076  3860  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:42.076  3860  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-06 16:55:42.088  3860  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 16:55:42.089  3860  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:42.089  3860  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:42.089  3860  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:42.089  3860  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:42.089  3860  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:42.089  3860  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:42.089  3860  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:42.089  3860  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:42.089  3860  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 16:55:42.089  3860  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:42.093  3860  3900 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 16:55:42.171   876  1317 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-06 16:55:42.207  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:42.210  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:42.215  3860  3860 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 16:55:42.581  3860  3870 I art     : Background sticky concurrent mark sweep GC freed 66901(6MB) AllocSpace objects, 17(1116KB) LOS objects, 28% free, 23MB/32MB, paused 529us total 102.077ms
,09-06 16:55:43.484  3860  3908 W jxcore-log: Initializing JXcore engine
,09-06 16:55:43.485  3860  3908 W jxcore-log: JXcore engine is ready
,09-06 16:55:43.524  3908  3908 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-06 16:55:43.524  3908  3908 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9900]" dev="sockfs" ino=9900 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-06 16:55:43.524  3908  3908 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-06 16:55:43.527  3908  3908 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27047]" dev="sockfs" ino=27047 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-06 16:55:43.539  3860  3908 W jxcore-log: Starting JXcore engine
,09-06 16:55:43.618  3860  3908 W jxcore-log: Platform android
09-06 16:55:43.618  3860  3908 W jxcore-log: 
,09-06 16:55:43.618  3860  3908 W jxcore-log: Process ARCH arm
09-06 16:55:43.618  3860  3908 W jxcore-log: 
,09-06 16:55:43.849  3860  3908 I jxcore-log: JXcore Cordova bridge is ready!
09-06 16:55:43.849  3860  3908 I jxcore-log: 
09-06 16:55:43.849  3860  3908 W jxcore-log: JXcore engine is started
,09-06 16:55:43.863  3860  3900 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 16:55:43.868  3860  3860 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 16:55:48.907  3663  3917 I BooksSync: Starting books sync for 61035162, extras: ade
,09-06 16:55:48.935  3663  3918 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-06 16:55:48.944  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 16:55:48.946  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 16:55:48.965  1515  2131 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-06 16:55:48.965  1515  2131 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-06 16:55:48.965  1515  2131 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 16:55:48.965  1515  2131 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 16:55:48.993  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 16:55:48.995  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 16:55:49.025  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-06 16:55:49.025  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-06 16:55:49.025  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 16:55:49.025  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 16:55:49.051  3663  3918 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-06 16:55:49.052  3663  3917 E BooksSync: Soft error
09-06 16:55:49.052  3663  3917 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-06 16:55:49.052  3663  3917 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-06 16:55:49.052  3663  3917 E BooksSync: Sync error
09-06 16:55:49.052  3663  3917 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-06 16:55:49.052  3663  3917 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-06 16:55:49.052  3663  3917 I BooksSync: Finished books sync
,09-06 16:55:49.059   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128890, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-06 16:55:53.567  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 16:55:53.567  3860  3908 I jxcore-log: 
,09-06 16:55:53.569  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 16:55:53.569  3860  3908 I jxcore-log: 
,09-06 16:55:53.579  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:53.579  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:53.579  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:53.579  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:53.579  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:53.579  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:53.579  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:53.579  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:53.582  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:53.584  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 16:55:53.584  3860  3908 I jxcore-log: 
,09-06 16:55:53.586  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 16:55:53.586  3860  3908 I jxcore-log: 
,09-06 16:55:54.078  3860  3908 D executeNativeTests: Running unit tests
,09-06 16:55:54.136  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:55:54.137  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c added. We now have 2 listener(s)
,09-06 16:55:54.138  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 16:55:54.138  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:55:54.138  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:55:54.138  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 16:55:54.138  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 added. We now have 2 listener(s)
09-06 16:55:54.138  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:54.139  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:55:54.141  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:54.151  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:54.151  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.151  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.151  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:54.151  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:54.151  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.151  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:54.151  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:54.152  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.152  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 16:55:54.154  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 16:55:54.156  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-06 16:55:54.156  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 16:55:54.158  3860  3908 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 16:55:54.158  3860  3908 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 16:55:54.158  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 16:55:54.158  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:54.158  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:54.158  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 16:55:54.159  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:55:54.159  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.159  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.159  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.159  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 16:55:54.159  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:55:54.160  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c removed from the list
09-06 16:55:54.160  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.160  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 removed from the list
09-06 16:55:54.161  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.162  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.162  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.162  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.162  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.168  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.168  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.168  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.168  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.171  3860  3908 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 16:55:54.172  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.172  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.172  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 16:55:54.173  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.173  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.173  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.173  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.173  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 16:55:54.173  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
,09-06 16:55:54.173  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.174  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.174  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.174  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.174  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.174  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.176  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.176  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.176  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:55:54.176  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
,09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 16:55:54.181  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710],
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 16:55:54.182  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 16:55:54.182  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.182  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.183  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 16:55:54.183  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.183  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.183  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.183  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.183  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:55:54.183  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.183  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.183  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.183  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.183  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.183  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.184  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.184  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.184  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.184  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.184  3860  3908 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 16:55:54.187  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:54.192  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:54.192  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.192  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.192  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:54.192  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:54.192  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.192  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:54.192  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:54.196  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.196  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:54.196  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:55:54.197  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:55:54.197  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:55:54.197  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:54.197  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:55:54.204  3860  3908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 16:55:54.204  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 16:55:54.208  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.215  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 16:55:54.217  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.218  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 16:55:54.219  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 16:55:54.222  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-06 16:55:54.228  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 16:55:54.229  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 16:55:54.229  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 16:55:54.231  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 16:55:54.233  3860  3908 D BluetoothAdapter: STATE_ON
,09-06 16:55:54.246  2690  2701 D BtGatt.GattService: registerClient() - UUID=14daa0ee-a4a1-494f-9666-219cad304669
,09-06 16:55:54.247  2690  2719 D BtGatt.GattService: onClientRegistered() - UUID=14daa0ee-a4a1-494f-9666-219cad304669, clientIf=5
,09-06 16:55:54.249  3860  3872 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 16:55:54.251  2690  2702 D BtGatt.GattService: start scan with filters
,09-06 16:55:54.258  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 16:55:54.258  2690  2722 D BtGatt.ScanManager: handling starting scan
,09-06 16:55:54.259  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 16:55:54.259  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:55:54.259  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 16:55:54.259  2690  2722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:55:54.262  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 16:55:54.262  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:55:54.263  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 16:55:54.264  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 16:55:54.267  2690  2719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 16:55:54.267  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.268  2690  2722 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 16:55:54.268  3860  3908 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 16:55:54.271  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 16:55:54.271  3860  3908 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 16:55:54.272  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.272  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 16:55:54.272  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.272  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 16:55:54.272  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:55:54.272  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 16:55:54.272  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:55:54.272  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 16:55:54.273  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:55:54.273  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 16:55:54.274  3860  3908 D BluetoothAdapter: STATE_ON
09-06 16:55:54.274  2690  2701 D BtGatt.GattService: stopScan() - queue size =1
,09-06 16:55:54.275  2690  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 16:55:54.275  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:54.275  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 16:55:54.276  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 16:55:54.276  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 16:55:54.276  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 16:55:54.277  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:54.277  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 16:55:54.278  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:55:54.278  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:55:54.278  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:54.278  2690  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 16:55:54.278  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.279  2690  2722 D BtGatt.ScanManager: Starting BLE batch scan
09-06 16:55:54.279  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 16:55:54.279  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:54.279  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.279  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:54.279  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:54.279  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.279  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:54.279  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:55:54.279  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.279  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.279  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.280  2690  2722 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 16:55:54.280  3860  3908 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 16:55:54.281  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:54.285  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:54.285  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.285  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.285  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:54.285  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:54.285  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.285  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:54.285  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:54.287  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.287  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:54.287  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:55:54.287  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:55:54.287  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:55:54.287  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:54.287  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 16:55:54.289  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.290  3860  3908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 16:55:54.290  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 16:55:54.291  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:54.295  2690  2719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 16:55:54.295  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:55:54.296  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 16:55:54.297  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 16:55:54.297  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:55:54.300  2690  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 16:55:54.301  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:55:54.302  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 16:55:54.302  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 16:55:54.302  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 16:55:54.303  3860  3908 D BluetoothAdapter: STATE_ON
,09-06 16:55:54.305  2690  2702 D BtGatt.GattService: registerClient() - UUID=f98956b0-80d5-4d7f-b018-8520960b92c1
,09-06 16:55:54.306  2690  2719 D BtGatt.GattService: onClientRegistered() - UUID=f98956b0-80d5-4d7f-b018-8520960b92c1, clientIf=5
,09-06 16:55:54.306  3860  3871 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 16:55:54.306  2690  2701 D BtGatt.GattService: start scan with filters
09-06 16:55:54.308  2690  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-06 16:55:54.308  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:55:54.308  2690  2722 D BtGatt.ScanManager: stopping BLe Batch
,09-06 16:55:54.309  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 16:55:54.309  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 16:55:54.309  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:55:54.310  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 16:55:54.311  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-06 16:55:54.311  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:55:54.312  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 16:55:54.313  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 16:55:54.313  2690  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 16:55:54.313  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.314  2690  2722 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 16:55:54.315  3860  3908 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 16:55:54.316  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.316  3860  3908 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 16:55:54.316  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.316  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 16:55:54.316  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.316  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 16:55:54.316  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:55:54.317  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:55:54.317  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:55:54.317  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:55:54.317  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 16:55:54.317  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 16:55:54.317  3860  3908 D BluetoothAdapter: STATE_ON
09-06 16:55:54.318  2690  2854 D BtGatt.GattService: stopScan() - queue size =0
09-06 16:55:54.319  2690  2701 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-06 16:55:54.319  2690  2719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 16:55:54.319  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:54.319  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.319  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 16:55:54.319  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 16:55:54.319  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 16:55:54.319  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 16:55:54.320  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:54.320  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 16:55:54.320  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:55:54.320  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:55:54.320  2690  2722 D BtGatt.ScanManager: handling starting scan
09-06 16:55:54.320  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:54.321  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 16:55:54.321  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-06 16:55:54.321  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 16:55:54.321  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.321  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:55:54.321  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:54.322  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
,09-06 16:55:54.322  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.322  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
,09-06 16:55:54.322  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.322  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:54.322  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.322  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.323  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.323  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.323  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.323  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list,
09-06 16:55:54.324  3860  3908 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 16:55:54.325  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:54.327  2690  2719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 16:55:54.328  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.328  2690  2722 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
09-06 16:55:54.331  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:54.331  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.331  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.331  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:54.331  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:54.331  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.331  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:54.331  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:54.332  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.333  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:54.334  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.334  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:55:54.335  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:55:54.335  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:55:54.335  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:54.335  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:55:54.336  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.336  2690  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 16:55:54.337  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.337  2690  2722 D BtGatt.ScanManager: Starting BLE batch scan
09-06 16:55:54.337  2690  2722 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 16:55:54.338  3860  3908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 16:55:54.338  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 16:55:54.341  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-06 16:55:54.341  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
09-06 16:55:54.341  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:55:54.344  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 16:55:54.344  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 16:55:54.344  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 16:55:54.345  3860  3908 D BluetoothAdapter: STATE_ON
,09-06 16:55:54.346  2690  2832 D BtGatt.GattService: registerClient() - UUID=49d49c17-0ce1-43b7-829c-7e04e3ac91db
09-06 16:55:54.346  2690  2719 D BtGatt.GattService: onClientRegistered() - UUID=49d49c17-0ce1-43b7-829c-7e04e3ac91db, clientIf=5
09-06 16:55:54.346  3860  3872 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 16:55:54.347  2690  2854 D BtGatt.GattService: start scan with filters
09-06 16:55:54.347  2690  2719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 16:55:54.347  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:55:54.349  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 16:55:54.349  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 16:55:54.349  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:55:54.349  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 16:55:54.350  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:55:54.351  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:55:54.351  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 16:55:54.352  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 16:55:54.352  2690  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 16:55:54.353  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:55:54.354  3860  3908 I io.jxcore.node.ConnectionHelper: start: OK
09-06 16:55:54.354  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 16:55:54.354  3860  3908 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 16:55:54.354  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.354  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 16:55:54.354  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.354  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 16:55:54.354  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-06 16:55:54.354  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:55:54.354  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:55:54.354  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:55:54.354  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:55:54.354  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 16:55:54.355  3860  3908 D BluetoothAdapter: STATE_ON
09-06 16:55:54.355  2690  2854 D BtGatt.GattService: stopScan() - queue size =0
09-06 16:55:54.355  2690  2701 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 16:55:54.356  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 16:55:54.356  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 16:55:54.356  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 16:55:54.356  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 16:55:54.356  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 16:55:54.357  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:54.357  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 16:55:54.357  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:55:54.357  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 16:55:54.357  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:54.358  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:54.358  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:54.358  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:54.358  2690  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 16:55:54.359  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:55:54.359  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.359  3860  3908 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 16:55:54.359  2690  2722 D BtGatt.ScanManager: stopping BLe Batch
09-06 16:55:54.359  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.359  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.359  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.359  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.359  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 16:55:54.359  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.359  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.359  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.359  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.359  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.360  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.360  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:54.361  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.361  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.361  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.361  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
,09-06 16:55:54.361  3860  3908 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 16:55:54.361  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.362  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.362  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.362  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 16:55:54.362  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.362  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.362  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.362  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:55:54.362  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.362  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.362  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:55:54.363  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.363  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.363  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.363  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 16:55:54.363  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.363  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.363  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.364  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 16:55:54.364  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 16:55:54.364  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.365  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.365  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.365  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.365  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.365  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.365  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.365  2690  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 16:55:54.365  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.365  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
,09-06 16:55:54.365  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.365  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.365  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.365  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.365  2690  2722 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 16:55:54.365  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.366  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.366  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.366  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:55:54.366  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.367  3860  3908 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 16:55:54.367  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.367  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.367  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.367  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.367  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.367  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.367  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.367  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.367  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.368  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.368  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.368  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.368  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.368  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.368  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 16:55:54.368  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.368  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.368  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.369  3860  3908 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 16:55:54.369  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.369  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.369  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.369  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.369  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.369  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.369  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.369  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:55:54.369  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.369  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.369  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.370  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.370  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.370  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.370  2690  2719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 16:55:54.370  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.370  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.370  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.370  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.371  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.371  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 16:55:54.371  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 16:55:54.371  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 16:55:54.371  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:54.371  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 16:55:54.371  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 16:55:54.371  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.371  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.371  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.372  2690  2722 D BtGatt.ScanManager: handling starting scan
09-06 16:55:54.372  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.372  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.372  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.372  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.372  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.372  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.372  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 16:55:54.372  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.372  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.372  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.372  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.373  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.373  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.373  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.373  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.374  3860  3908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:54.374  3860  3908 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 16:55:54.374  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 16:55:54.377  3860  3908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:54.377  3860  3908 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-06 16:55:54.377  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 16:55:54.377  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 16:55:54.377  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 16:55:54.377  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 16:55:54.377  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 16:55:54.378  2690  2719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 16:55:54.378  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.378  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-06 16:55:54.378  2690  2722 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 16:55:54.379  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-06 16:55:54.379  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 16:55:54.379  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 16:55:54.379  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 16:55:54.379  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 16:55:54.379  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 16:55:54.379  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 16:55:54.379  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 16:55:54.380  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-06 16:55:54.381  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 16:55:54.381  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 16:55:54.381  3860  3908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 16:55:54.382  3860  3908 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 16:55:54.382  3860  3908 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 16:55:54.382  3860  3908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:54.382  3860  3908 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-06 16:55:54.382  3860  3908 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 16:55:54.382  3860  3908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:54.382  3860  3908 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 16:55:54.382  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-06 16:55:54.384  2690  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 16:55:54.384  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:55:54.385  2690  2722 D BtGatt.ScanManager: Starting BLE batch scan
09-06 16:55:54.386  2690  2722 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 16:55:54.386  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 16:55:54.388  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 16:55:54.388  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 16:55:54.389  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 16:55:54.389  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-06 16:55:54.389  3860  3908 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 16:55:54.389  3860  3908 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:54.390  3860  3908 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 16:55:54.390  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.390  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.390  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.390  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.390  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.390  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:54.390  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 16:55:54.392  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.392  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.392  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.392  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.392  3860  3920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
09-06 16:55:54.392  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:55:54.392  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.392  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.392  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.392  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.393  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.393  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.393  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.393  3860  3908 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 16:55:54.393  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.393  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:55:54.394  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.394  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.394  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.394  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.394  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.394  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.394  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.394  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 16:55:54.394  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.394  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.394  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.394  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:54.395  3860  3920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:55:54.395  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.395  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.395  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.395  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.395  2690  2719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 16:55:54.395  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.396  3860  3908 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 16:55:54.396  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 16:55:54.396  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.396  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.396  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.396  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.396  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.396  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.396  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.396  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
,09-06 16:55:54.396  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.396  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.396  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.396  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.397  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.397  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 16:55:54.397  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.397  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.397  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.398  3860  3908 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 16:55:54.398  3860  3908 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 16:55:54.398  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 16:55:54.398  3860  3908 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 16:55:54.398  3860  3908 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 16:55:54.398  3860  3908 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 16:55:54.398  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-06 16:55:54.398  3860  3908 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 16:55:54.398  3860  3908 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 16:55:54.398  3860  3908 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 16:55:54.398  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 16:55:54.398  3860  3908 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-06 16:55:54.399  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.399  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.399  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.399  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.399  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.399  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:54.399  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.399  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.399  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
,09-06 16:55:54.399  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 16:55:54.399  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.399  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.399  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.400  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.401  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.401  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.401  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.401  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.401  3860  3921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
,09-06 16:55:54.401  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.401  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.401  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.401  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.401  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.401  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.401  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.401  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.402  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:54.402  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.401  3860  3921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
09-06 16:55:54.402  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.402  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.402  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.402  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.402  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.402  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.402  2690  2824 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-06 16:55:54.402  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:55:54.402  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.402  2690  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 16:55:54.402  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.402  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.402  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.402  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.402  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.402  3860  3920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
09-06 16:55:54.402  3860  3921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
,09-06 16:55:54.403  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.403  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.403  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.403  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.403  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.403  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.403  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.403  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.403  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.403  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.403  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.404  3860  3908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 16:55:54.405  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:54.405  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-06 16:55:54.408  3860  3908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 16:55:54.408  3860  3908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 16:55:54.408  3860  3922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:55:54.409  3860  3860 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 16:55:54.409  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 16:55:54.410  3860  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-06 16:55:54.410  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:55:54.411  2690  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 16:55:54.411  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.411  2690  2722 D BtGatt.ScanManager: stopping BLe Batch
,09-06 16:55:54.411  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.411  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 16:55:54.412  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 16:55:54.413  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 16:55:54.413  3860  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-06 16:55:54.413  3860  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 16:55:54.413  3860  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 16:55:54.414  3860  3860 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 16:55:54.413  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.415  3860  3908 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 16:55:54.415  3860  3860 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-06 16:55:54.415  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.416  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.416  2690  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 16:55:54.416  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:55:54.416  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.416  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:55:54.416  2690  2722 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 16:55:54.416  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:55:54.416  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.416  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.418  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:54.419  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 16:55:54.420  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:54.420  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:54.420  2690  2719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 16:55:54.420  2690  2719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:55:54.421  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.421  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.421  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.421  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.422  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.422  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:55:54.422  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.423  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.423  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.423  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.423  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.423  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.423  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.423  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.423  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.424  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.424  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.424  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.424  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.425  3860  3908 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-06 16:55:54.425  3860  3908 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 16:55:54.425  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 16:55:54.425  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:54.425  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.425  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.426  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.426  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.426  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.426  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.426  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.426  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.426  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.426  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 16:55:54.426  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.426  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.426  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.426  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.427  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.428  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.428  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.428  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
,09-06 16:55:54.431  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.431  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.431  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 16:55:54.431  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.431  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:55:54.431  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.431  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.431  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:55:54.432  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.432  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.432  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.432  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.432  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:55:54.432  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.432  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.433  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.433  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:55:54.433  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.433  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:54.433  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:54.433  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:54.433  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:54.433  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.434  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:54.434  3860  3908 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@859fc0c not in the list
09-06 16:55:54.434  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.434  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.434  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:54.434  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:55:54.434  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.434  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:54.434  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:54.435  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:54.435  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:54.435  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:54.435  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642955 not in the list
09-06 16:55:54.436  3860  3908 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-06 16:55:54.436  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 16:55:54.436  3860  3908 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 16:55:54.436  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 16:55:54.436  3860  3908 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 16:55:54.436  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 16:55:54.438  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 16:55:54.438  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-06 16:55:54.438  3860  3908 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 16:55:54.438  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 16:55:54.438  3860  3908 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 16:55:54.438  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 16:55:54.438  3860  3908 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 16:55:54.439  3860  3908 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-06 16:55:54.439  3860  3908 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 16:55:54.439  3860  3908 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-06 16:55:54.439  3860  3908 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 16:55:54.440  3860  3908 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 16:55:54.440  3860  3908 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 16:55:54.440  3860  3908 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-06 16:55:54.441  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:54.441  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23f522f added. We now have 2 listener(s)
09-06 16:55:54.441  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:55:54.442  3860  3908 D BluetoothAdapter: enable(): BT is already enabled..!
,09-06 16:55:54.442   876  1703 D WifiService: setWifiEnabled: true pid=3860, uid=10000
09-06 16:55:54.442   876  1703 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 16:55:54.443  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:54.443  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5a803c added. We now have 3 listener(s)
09-06 16:55:54.443  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:55:54.446  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 16:55:54.447  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@70311c5 added. We now have 4 listener(s)
09-06 16:55:54.447  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:55:54.448  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:54.448  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f16c71a added. We now have 5 listener(s)
,09-06 16:55:54.448  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:55:54.449   876  2121 D WifiService: setWifiEnabled: false pid=3860, uid=10000
09-06 16:55:54.449   876  2121 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 16:55:54.452  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:54.453  2690  2715 D BluetoothAdapterState: Current state: ON, message: 23
,09-06 16:55:54.453  2690  2715 D BluetoothAdapterProperties: Setting state to 13
09-06 16:55:54.453  2690  2715 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 16:55:54.454  2690  2715 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 16:55:54.454  2690  2715 I BluetoothAdapterState: Entering PendingCommandState
,09-06 16:55:54.456  2690  2690 D BluetoothMapService: onReceive
,09-06 16:55:54.456  2690  2690 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:54.456  2690  2690 D BluetoothMapService: STATE_TURNING_OFF
09-06 16:55:54.456  2690  2690 D BluetoothMapService: MAP Service closeService in
09-06 16:55:54.456  2690  2690 D BluetoothMapMasInstance0: MAP Service shutdown
,09-06 16:55:54.457  2690  2690 D ObexServerSockets0: shutdown(block = true)
09-06 16:55:54.457  2690  2690 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 16:55:54.457  2690  2690 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 16:55:54.457  2690  2824 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-06 16:55:54.458  2690  2863 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 16:55:54.458  2690  2862 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-06 16:55:54.459  2690  2690 I BtOppRfcommListener: stopping Accept Thread
09-06 16:55:54.459  2690  3477 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:55:54.459  2690  3477 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 16:55:54.460  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:54.461  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:54.461  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.461  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.461  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:54.461  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:54.461  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.461  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:54.461  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:54.461  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:54.461  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:54.461  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 16:55:54.465  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:54.467   876   889 I ActivityManager: Start proc 3925:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-06 16:55:54.468  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.469  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 16:55:54.470  2690  2719 D BluetoothAdapterProperties: Scan Mode:20
09-06 16:55:54.470  2690  2715 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-06 16:55:54.471   876  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 16:55:54.472   876  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-06 16:55:54.472   876  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 16:55:54.472   876  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:55:54.472  2690  2690 D HeadsetService: Received stop request...Stopping profile...
09-06 16:55:54.474  1373  1386 D BluetoothHeadset: Proxy object disconnected
09-06 16:55:54.475  1985  1998 D BluetoothHeadset: Proxy object disconnected
,09-06 16:55:54.476  1373  1373 D HeadsetProfile: Bluetooth service disconnected
09-06 16:55:54.475   876   876 D BluetoothHeadset: Proxy object disconnected
09-06 16:55:54.476   876   876 D BluetoothHeadset: Proxy object disconnected
,09-06 16:55:54.476   876   876 D BluetoothHeadset: Proxy object disconnected
,09-06 16:55:54.476  2690  2690 D A2dpService: Received stop request...Stopping profile...
,09-06 16:55:54.476  2690  2848 D A2dpStateMachine: Exit Disconnected: -1
,09-06 16:55:54.476  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:54.476  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:54.476  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.476  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.476  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:54.476  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:54.476  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:54.476  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:54.476  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:54.478   876   876 D BluetoothA2dp: Proxy object disconnected
09-06 16:55:54.479  1373  1373 D BluetoothA2dp: Proxy object disconnected
09-06 16:55:54.479  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:54.479  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:54.481  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.481  2690  2690 D HidService: Received stop request...Stopping profile...
,09-06 16:55:54.482   876  1889 D DhcpClient: Clearing IP address
,09-06 16:55:54.482   374   874 D CommandListener: Clearing all IP addresses on wlan0
09-06 16:55:54.482  2690  2690 D HidService: Stopping Bluetooth HidService
09-06 16:55:54.483  1373  1373 D BluetoothInputDevice: Proxy object disconnected
09-06 16:55:54.484  1373  1373 D HidProfile: Bluetooth service disconnected
09-06 16:55:54.484  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.484  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-06 16:55:54.484  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-06 16:55:54.484  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:55:54.484  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:55:54.485   374   874 D CommandListener: Setting iface cfg
,09-06 16:55:54.486  2690  2690 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 16:55:54.486  2690  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:55:54.486  2690  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:55:54.486  2690  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:55:54.486  2690  2719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 16:55:54.486  2690  2719 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-06 16:55:54.486  2690  2690 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 16:55:54.487  2690  2690 D HealthService: Received stop request...Stopping profile...
,09-06 16:55:54.487  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.489  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-06 16:55:54.489  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-06 16:55:54.489  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:55:54.489  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:55:54.490  2690  2690 D PanService: Received stop request...Stopping profile...
09-06 16:55:54.491  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 16:55:54.491  1515  2453 V NativeCrypto: Read error: ssl=0x9af03a00: I/O error during system call, Connection timed out
09-06 16:55:54.491  1373  1373 D PanProfile: Bluetooth service disconnected
09-06 16:55:54.492  1515  2453 V NativeCrypto: SSL shutdown failed: ssl=0x9af03a00: I/O error during system call, Broken pipe
09-06 16:55:54.493   876  2120 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-06 16:55:54.493   876  1874 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-06 16:55:54.494   876  1874 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-06 16:55:54.495   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-06 16:55:54.495  2690  2719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 16:55:54.495  2690  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:55:54.495   876  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-06 16:55:54.495  2690  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:55:54.495  2690  2812 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 16:55:54.495  2690  2812 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:54.495  2690  2812 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:54.495  2690  2812 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:54.496   876  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 16:55:54.500   876  1891 D DhcpClient: Receive thread stopped
09-06 16:55:54.501  2690  2690 D BluetoothMapService: Received stop request...Stopping profile...
09-06 16:55:54.501  2690  2690 D BluetoothMapService: stop()
09-06 16:55:54.501   876  1317 D WifiStateMachine: Start Disconnecting Watchdog 1
09-06 16:55:54.501  2690  2690 D BluetoothMapAppObserver: deinitObservers()
,09-06 16:55:54.501  2690  2690 D BluetoothMapAppObserver: removeReceiver()
09-06 16:55:54.502   876  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 16:55:54.503  1373  1373 D BluetoothMap: Proxy object disconnected
09-06 16:55:54.503  1373  1373 D MapProfile: Bluetooth service disconnected
09-06 16:55:54.504   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-06 16:55:54.504   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-06 16:55:54.506  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-06 16:55:54.506  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-06 16:55:54.506  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:55:54.506  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:55:54.506  2690  2690 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-06 16:55:54.506  2690  2719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 16:55:54.506  2690  2690 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 16:55:54.507  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-06 16:55:54.507  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-06 16:55:54.507  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:55:54.507  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 16:55:54.507  2690  2690 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 16:55:54.507   374   874 D CommandListener: Clearing all IP addresses on wlan0
09-06 16:55:54.508   402   402 E Parcel  : Reading a NULL string not supported here.
,09-06 16:55:54.508  2690  2719 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 16:55:54.508  2690  2690 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 16:55:54.509  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-06 16:55:54.509  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-06 16:55:54.514   876  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-06 16:55:54.515   876  1317 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 16:55:54.520  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:54.520  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:54.520  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.520  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.520  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:54.520  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:54.520  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:54.520  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:54.520  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:54.521  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:54.521  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:54.523  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:54.523  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:54.523  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.523  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.523  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:54.523  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:54.523  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:54.523  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:54.523  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:54.523  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:54.523  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:54.525   876  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-06 16:55:54.509  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:55:54.527  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:55:54.527  2690  2690 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 16:55:54.527  2690  2690 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 16:55:54.528  2690  2690 D BluetoothMapService: MAP Service closeService in
09-06 16:55:54.528  2690  2690 V BluetoothAdapterState: isTurningOff()=true
09-06 16:55:54.528  2690  2690 V BluetoothAdapterState: isTurningOn()=false
09-06 16:55:54.528  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:55:54.528  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:55:54.528  2690  2715 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 16:55:54.528  2690  2715 D BluetoothAdapterProperties: Setting state to 15
09-06 16:55:54.528  2690  2715 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 16:55:54.529  2690  2715 I BluetoothAdapterState: Entering BleOnState
09-06 16:55:54.529  1373  2133 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:55:54.529   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:55:54.530  1373  3859 D BluetoothPan: onBluetoothStateChange on: false
09-06 16:55:54.529  2690  2690 D BluetoothMapService: cleanup()
09-06 16:55:54.531  2690  2690 D BluetoothMapService: MAP Service closeService in
09-06 16:55:54.531  1373  1385 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 16:55:54.532  1985  1998 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:55:54.533   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:55:54.533   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:55:54.533  1908  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:54.533   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:55:54.533  1373  2133 D BluetoothMap: onBluetoothStateChange: up=false
09-06 16:55:54.533  1373  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:55:54.534  1373  3858 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 16:55:54.536  2690  2715 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 16:55:54.536  2690  2715 D BluetoothAdapterProperties: Setting state to 16
09-06 16:55:54.536  2690  2715 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 16:55:54.537  2690  2715 D BluetoothAdapterProperties: onBleDisable
09-06 16:55:54.537  2690  2715 I BluetoothAdapterState: Entering PendingCommandState
09-06 16:55:54.537  2690  2716 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 16:55:54.538  2690  2812 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 16:55:54.538  2690  2719 D BluetoothAdapterProperties: Scan Mode:20
09-06 16:55:54.538  2690  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:55:54.543  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:54.543  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:54.543  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.543  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.543  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:54.543  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:54.543  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:54.543  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:54.543  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:54.546  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:54.546  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:54.546  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:54.546  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:54.546  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:54.546  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:54.546  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:54.546  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:54.546  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:54.547   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-06 16:55:54.548  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.549  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.564  3925  3925 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-06 16:55:54.566   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-06 16:55:54.567   876  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 16:55:54.567   876  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:54.570   876   893 D Tethering: MasterInitialState.processMessage what=3
09-06 16:55:54.571  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.572  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:54.572  2099  2099 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-06 16:55:54.571  3429  3429 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d74ac3c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-06 16:55:54.589  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 16:55:54.594  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 16:55:54.597   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b8a34b:true
09-06 16:55:54.606   876   887 I ActivityManager: Start proc 3946:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-06 16:55:54.619   374   874 E Netd    : netlink response contains error (No such file or directory)
09-06 16:55:54.620   876  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 16:55:54.632  3925  3925 D LocalBluetoothProfileManager: Adding local MAP profile
,09-06 16:55:54.634  3925  3925 D BluetoothMap: Create BluetoothMap proxy object
,09-06 16:55:54.641  3946  3946 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-06 16:55:54.645  3925  3925 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-06 16:55:54.663  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:55:54.665   876  1703 I ActivityManager: Killing 3560:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-06 16:55:54.740  2690  2719 I bt_hci  : shut_down
,09-06 16:55:54.740  2690  2723 D bt_hwcfg: hw_epilog_process
,09-06 16:55:54.742  2690  2723 I bt_vendor: low_power_mode_cb
,09-06 16:55:54.765  2690  2723 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 16:55:54.765  2690  2723 I bt_vendor: epilog_cb
09-06 16:55:54.765  2690  2723 I bt_hci  : epilog_finished_callback
,09-06 16:55:54.769  2690  2719 I bt_hci_h4: hal_close
,09-06 16:55:54.770  2690  2719 I bt_userial_vendor: device fd = 51 close
,09-06 16:55:54.831  3946  3946 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 16:55:54.831  3946  3946 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 16:55:54.831  3946  3946 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:55:54.831  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 16:55:54.832  3946  3946 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 16:55:54.832  3946  3946 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.k.d(PG:583)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 16:55:54.832  3946  3946 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 16:55:54.832  3946  3946 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 16:55:54.832  3946  3946 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:55:54.832  3946  3946 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 16:55:54.873   876  1703 I ActivityManager: Start proc 3976:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-06 16:55:54.874   876  1703 I ActivityManager: Killing 3429:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-06 16:55:54.920  3860  3860 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 16:55:55.016  3976  3976 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-06 16:55:55.018  2690  2716 D bt_stack_manager: event_shut_down_stack finished.
,09-06 16:55:55.018  2690  2715 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 16:55:55.022  2690  2715 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-06 16:55:55.022  2690  2690 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 16:55:55.023  2690  2690 D BtGatt.GattService: Received stop request...Stopping profile...
,09-06 16:55:55.024  2690  2690 D BtGatt.GattService: stop()
,09-06 16:55:55.024  2690  2690 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 16:55:55.027  2690  2690 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:55:55.027  2690  2690 V BluetoothAdapterState: isTurningOn()=false
,09-06 16:55:55.027  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 16:55:55.028  2690  2690 V BluetoothAdapterState: isBleTurningOff()=true
,09-06 16:55:55.028  2690  2715 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-06 16:55:55.028  2690  2715 D BluetoothAdapterProperties: Setting state to 10
09-06 16:55:55.029  2690  2715 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-06 16:55:55.030  2690  2715 I BluetoothAdapterState: Entering OffState
,09-06 16:55:55.031   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-06 16:55:55.049  2690  2690 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-06 16:55:55.050  2690  2690 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 16:55:55.050  2690  2716 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-06 16:55:55.052  2690  2690 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 16:55:55.053  2690  2716 D bt_stack_manager: event_clean_up_stack finished.
,09-06 16:55:55.064  2690  2690 I art     : System.exit called, status: 0
,09-06 16:55:55.064  2690  2690 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 16:55:55.108  3976  3976 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-06 16:55:55.142   876  1999 I ActivityManager: Process com.android.bluetooth (pid 2690) has died
09-06 16:55:55.146  3946  3967 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 16:55:55.166  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:55:55.180   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8a0efa5:true
,09-06 16:55:55.186   876  1703 I ActivityManager: Start proc 4005:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-06 16:55:55.188  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:55:55.252  4005  4005 D AdapterServiceConfig: Adding HeadsetService
,09-06 16:55:55.252  4005  4005 D AdapterServiceConfig: Adding A2dpService
09-06 16:55:55.253  4005  4005 D AdapterServiceConfig: Adding HidService
09-06 16:55:55.253  4005  4005 D AdapterServiceConfig: Adding HealthService
,09-06 16:55:55.253  4005  4005 D AdapterServiceConfig: Adding PanService
,09-06 16:55:55.253  4005  4005 D AdapterServiceConfig: Adding GattService
,09-06 16:55:55.253  4005  4005 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 16:55:55.256   876   886 I ActivityManager: Killing 3499:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-06 16:55:55.329  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 16:55:55.361  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 16:55:55.366  1729  1729 D SystemUpdateService: onCreate
,09-06 16:55:55.370  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 16:55:55.377  1729  4017 I SystemUpdateService: active receiver: enabled
,09-06 16:55:55.383  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 16:55:55.382  1729  4017 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 16:55:55.385  1729  4017 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-06 16:55:55.385  1729  4017 I SystemUpdateService: now status is 0 (complete)
,09-06 16:55:55.386  1729  4017 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 16:55:55.386  1729  4017 I SystemUpdateService: file has been verified
,09-06 16:55:55.387  1729  4017 I SystemUpdateService: OTA package size = 12249756
,09-06 16:55:55.391  1729  2413 I iu.UploadsManager: num queued entries: 0
,09-06 16:55:55.391  1729  2413 I iu.UploadsManager: num updated entries: 0
,09-06 16:55:55.392  1729  4017 I SystemUpdateService: showing system update notification
,09-06 16:55:55.393  1729  2413 I iu.SyncManager: NEXT; no task
,09-06 16:55:55.415  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 16:55:55.416  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 16:55:55.417  1729  1729 D SystemUpdateService: onDestroy
,09-06 16:55:55.432   876  2119 I ActivityManager: Start proc 4019:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-06 16:55:55.500  4019  4019 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-06 16:55:55.505  4019  4019 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:55.516  4019  4019 D SprintDMHelper: simOperator: 
09-06 16:55:55.516  4019  4019 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 16:55:55.540   876  1999 I ActivityManager: Start proc 4031:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-06 16:55:55.541   876  1999 I ActivityManager: Killing 3544:android.process.acore/u0a5 (adj 15): empty #17
,09-06 16:55:55.669   876  1999 I ActivityManager: Start proc 4046:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-06 16:55:55.674   876  2120 I ActivityManager: Killing 3739:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-06 16:55:55.733  4046  4046 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-06 16:55:55.795  4046  4046 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 16:55:55.795  4046  4046 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 16:55:55.795  4046  4046 I GAv4    :   adb logcat -s GAv4
,09-06 16:55:55.816  4046  4046 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 16:55:55.824  4046  4046 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 16:55:55.860  4046  4063 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 16:55:55.969  4046  4046 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-06 16:55:56.008  4046  4046 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-06 16:55:56.019  4046  4046 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 6095-6101)
09-06 16:55:56.019  4046  4046 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 16:55:56.028  4046  4046 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e599c6c}
,09-06 16:55:56.029  4046  4046 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 16:55:56.030  4046  4046 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 16:55:56.039  4046  4046 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-06 16:55:56.041  4046  4046 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 16:55:56.060  4046  4046 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-06 16:55:56.076  4046  4046 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 16:55:56.076  4046  4046 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 16:55:56.076  4046  4046 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 16:55:56.076  4046  4046 I Adreno  : Build Date                       : 10/20/15
09-06 16:55:56.076  4046  4046 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 16:55:56.076  4046  4046 I Adreno  : Local Branch                     : M14
09-06 16:55:56.076  4046  4046 I Adreno  : Remote Branch                    : 
09-06 16:55:56.076  4046  4046 I Adreno  : Remote Branch                    : 
09-06 16:55:56.076  4046  4046 I Adreno  : Reconstruct Branch               : 
,09-06 16:55:56.139  4046  4046 I NSApplication: Starting up...
,09-06 16:55:56.150  4046  4092 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 16:55:56.187   876  1704 I ActivityManager: Start proc 4097:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-06 16:55:56.188   876  1704 I ActivityManager: Killing 3754:com.android.musicfx/u0a18 (adj 15): empty #17
,09-06 16:55:56.254  4097  4097 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-06 16:55:56.435   876  2119 I ActivityManager: Killing 2084:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-06 16:55:57.464   876  1384 D WifiService: setWifiEnabled: true pid=3860, uid=10000
,09-06 16:55:57.464   876  1384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 16:55:57.477   876  1317 D WifiConfigStore: Loading config and enabling all networks 
,09-06 16:55:57.487  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:57.488  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:57.488  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:57.488  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:57.488  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:57.488  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:57.488  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:57.488  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:57.488  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:57.488  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:57.488  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:55:57.492  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:57.493  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:57.493  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:57.493  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:57.493  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:57.493  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:57.493  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:57.493  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:57.493  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:57.493  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:57.493  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:55:57.510   876  1317 D WifiConfigStore: loaded 0 passpoint configs
,09-06 16:55:57.513   876  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-06 16:55:57.515   876  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 16:55:57.518   876  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 16:55:57.519   876  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-06 16:55:57.519   876  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK,
09-06 16:55:57.519   876  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 16:55:57.537   374   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 16:55:57.538   374   874 D CommandListener: Setting iface cfg
,09-06 16:55:57.538   876  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=15.88 rxSuccessRate=29.50 delta 1000 -> 994
,09-06 16:55:57.539   876  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-06 16:55:57.539   876  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 16:55:57.542   876  1316 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 16:55:57.543   876  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 16:55:57.567   876  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 16:55:57.567   876  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 16:55:57.581   876  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 16:55:57.646   876  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 16:55:57.649  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 16:55:58.075  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 16:55:58.114  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 16:55:58.115  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 16:55:58.126   876  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 16:55:58.137   876  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 16:55:58.138   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 16:55:58.139   876  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 16:55:58.163   876  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 16:55:58.184   374   874 D CommandListener: Setting iface cfg
,09-06 16:55:58.185   876  1317 D WifiStateMachine: Start Dhcp Watchdog 2
,09-06 16:55:58.198   876  1319 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-06 16:55:58.200   876  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 16:55:58.233   876  4122 D DhcpClient: Receive thread started
,09-06 16:55:58.316   876  1317 E native  : do suspend false
,09-06 16:55:58.334   876  1889 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 16:55:58.348   876  4122 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172684, domain null
,09-06 16:55:58.349   876  1889 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172684 seconds
,09-06 16:55:58.352   876  1889 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 16:55:58.368   876  4122 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 16:55:58.370   876  1889 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 16:55:58.374   374   874 D CommandListener: Setting iface cfg
,09-06 16:55:58.386   876  1889 D DhcpClient: Scheduling renewal in 86399s
,09-06 16:55:58.386   876  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 16:55:58.401   876  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 16:55:58.404   876  1317 D WifiConfigStore: No blacklist allowed without epno enabled
09-06 16:55:58.404   876  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.405   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 16:55:58.409   876  1319 D ConnectivityService: Adding iface wlan0 to network 101
,09-06 16:55:58.409   876  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 16:55:58.463   876  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 16:55:58.463   876  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-06 16:55:58.465   876  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-06 16:55:58.466   876  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-06 16:55:58.467   876  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-06 16:55:58.476   876  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 16:55:58.481   876  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-06 16:55:58.481   876  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-06 16:55:58.481   876  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101],
09-06 16:55:58.481   876  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-06 16:55:58.481   876  1319 D ConnectivityService:    accepting network in place of null
,09-06 16:55:58.482   876  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 16:55:58.482   876  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 16:55:58.502   876  4121 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-06 16:55:58.526   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 16:55:58.569   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 16:55:58.572   876  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 16:55:58.572   876  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:58.576   876  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-06 16:55:58.579   876   893 D Tethering: MasterInitialState.processMessage what=3
09-06 16:55:58.585   876  4120 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:814::200e
09-06 16:55:58.591  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:58.591  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:58.591  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:58.591  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:58.591  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:58.591  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:58.591  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:58.591  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:58.591  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:58.592  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:58.592  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:58.594  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:58.594  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:58.594  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:58.594  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:58.594  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:58.594  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:58.594  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:58.594  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:58.594  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:58.594  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:58.594  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:58.603  2099  2099 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-06 16:55:58.604  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-06 16:55:58.609  1729  1729 D SystemUpdateService: onCreate
09-06 16:55:58.613  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-06 16:55:58.616  1729  4133 I SystemUpdateService: active receiver: enabled
09-06 16:55:58.619  1729  4133 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-06 16:55:58.622  1729  4133 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-06 16:55:58.622  1729  4133 I SystemUpdateService: now status is 0 (complete)
09-06 16:55:58.622  1729  4133 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 16:55:58.622  1729  4133 I SystemUpdateService: file has been verified
09-06 16:55:58.622  1729  4133 I SystemUpdateService: OTA package size = 12249756
09-06 16:55:58.631  1729  4133 I SystemUpdateService: showing system update notification
09-06 16:55:58.633  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-06 16:55:58.634  1729  2413 I iu.UploadsManager: num queued entries: 0
09-06 16:55:58.636  1729  2413 I iu.UploadsManager: num updated entries: 0
09-06 16:55:58.637  1729  2413 I iu.SyncManager: NEXT; no task
,09-06 16:55:58.644  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-06 16:55:58.645  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-06 16:55:58.646  1729  4139 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-06 16:55:58.646  1729  4139 W BaseAppContext: Using Auth Proxy for data requests.
09-06 16:55:58.648  1729  4139 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
09-06 16:55:58.648  4019  4019 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:58.652  4019  4019 D SprintDMHelper: simOperator: 
09-06 16:55:58.653  4019  4019 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-06 16:55:58.664  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 16:55:58.666  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 16:55:58.667  1729  1729 D SystemUpdateService: onDestroy
09-06 16:55:58.670   876  4120 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 14:55:58 GMT], X-Android-Received-Millis=[1473173758670], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473173758635]}
09-06 16:55:58.672   876  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-06 16:55:58.672   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-06 16:55:58.672   876  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.674   876  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-06 16:55:58.716  1515  2047 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 16:55:58.717  1515  2047 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 16:55:58.717  1515  2047 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 16:55:58.717  1515  2047 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 16:55:58.732  1729  4139 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-06 16:55:58.735  3040  4134 V KeepSync: Connecting to GoogleApiClient
,09-06 16:55:58.735   876  1384 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-06 16:55:58.778  1515  3095 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-06 16:55:58.778  1515  3095 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-06 16:55:58.778  1515  3095 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-06 16:55:58.778  1515  3095 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 16:55:58.783  1515  2131 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-06 16:55:58.783  1515  2131 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-06 16:55:58.783  1515  2131 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 16:55:58.783  1515  2131 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 16:55:58.792  3625  4138 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-06 16:55:58.792  3625  4138 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at jdm.a(PG:82)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at jcs.o(PG:406)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at jcn.a(PG:1379)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at jcs.i(PG:143)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at blb.a(PG:3937)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	,at czp.a(PG:18188)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at czp.a(PG:9081)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at czq.run(PG:1686)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 16:55:58.792  3625  4138 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at jdj.a(PG:4091)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at jdj.a(PG:1125)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at jdm.a(PG:77)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	... 12 more
09-06 16:55:58.792  3625  4138 E HttpOperation: Caused by: faj: BadAuthentication
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at fal.a(PG:38)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	at jdj.a(PG:4089)
09-06 16:55:58.792  3625  4138 E HttpOperation: 	... 14 more
,09-06 16:55:58.798  1729  4149 V BaseAuthAsyncOperation: access token request failed
,09-06 16:55:58.800  3040  4134 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-06 16:55:58.815  2302  4142 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 16:55:58.835  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-06 16:55:58.835  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-06 16:55:58.835  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 16:55:58.835  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 16:55:58.852  3625  4138 E HttpOperation: [getmobileexperiments] Unexpected exception
09-06 16:55:58.852  3625  4138 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at jdm.a(PG:82)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at jcs.o(PG:406)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at jcn.a(PG:1379)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at jcs.i(PG:143)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at hec.a(PG:42)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at hee.a(PG:102)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at czr.a(PG:65)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at kka.a(PG:108)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at czp.a(PG:19176)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at czp.a(PG:9081)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at czq.run(PG:1686)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 16:55:58.852  3625  4138 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at jdj.a(PG:4091)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at jdj.a(PG:1125)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at jdm.a(PG:77)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	... 15 more
09-06 16:55:58.852  3625  4138 E HttpOperation: Caused by: faj: BadAuthentication
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at fal.a(PG:38)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	at jdj.a(PG:4089)
09-06 16:55:58.852  3625  4138 E HttpOperation: 	... 17 more
,09-06 16:55:58.852  1515  2131 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-06 16:55:58.852  1515  2131 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-06 16:55:58.852  3625  4138 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-06 16:55:58.852  3625  4138 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at jdm.a(PG:82)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at jcs.o(PG:406)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at jcn.a(PG:1379)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at jcs.i(PG:143)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at hec.a(PG:42)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at hee.a(PG:102)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at czr.a(PG:65)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at kka.a(PG:108)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at czp.a(PG:19176)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at czp.a(PG:9081)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at czq.run(PG:1686)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at jdj.a(PG:4091)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at jdj.a(PG:1125)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at jdm.a(PG:77)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	... 15 more
09-06 16:55:58.852  3625  4138 E ExperimentLoader: Caused by: faj: BadAuthentication
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at fal.a(PG:38)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	at jdj.a(PG:4089)
09-06 16:55:58.852  3625  4138 E ExperimentLoader: 	... 17 more
09-06 16:55:58.852  1515  2131 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-06 16:55:58.852  1515  2131 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 16:55:58.870  3040  4134 E KeepSync: IOException
09-06 16:55:58.870  3040  4134 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-06 16:55:58.870  3040  4134 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-06 16:55:58.870  3040  4134 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-06 16:55:58.870  3040  4134 E KeepSync: 	... 10 more
,09-06 16:55:58.870  3040  4134 W KeepSync: Sync result 2
,09-06 16:55:58.874   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129361, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-06 16:55:58.954   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 131043, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-06 16:55:59.573   876  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-06 16:56:00.232   876  2118 I ActivityManager: Killing 3777:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-06 16:56:00.470   876  2042 D WifiService: setWifiEnabled: false pid=3860, uid=10000
09-06 16:56:00.470   876  2042 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 16:56:00.487  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-06 16:56:00.492   876  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 16:56:00.492   876  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-06 16:56:00.492   876  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 16:56:00.492   876  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 16:56:00.503   876  1889 D DhcpClient: Clearing IP address
,09-06 16:56:00.504   374   874 D CommandListener: Setting iface cfg
,09-06 16:56:00.507   374   874 D CommandListener: Clearing all IP addresses on wlan0
,09-06 16:56:00.508   876  4122 D DhcpClient: Receive thread stopped
09-06 16:56:00.509  1515  4148 V NativeCrypto: Read error: ssl=0x9b70e800: I/O error during system call, Connection timed out
,09-06 16:56:00.511  1515  4148 V NativeCrypto: SSL shutdown failed: ssl=0x9b70e800: I/O error during system call, Broken pipe
,09-06 16:56:00.514   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-06 16:56:00.514   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-06 16:56:00.514   876  1317 D WifiStateMachine: Start Disconnecting Watchdog 2
09-06 16:56:00.516   876  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 16:56:00.521   402   402 E Parcel  : Reading a NULL string not supported here.
09-06 16:56:00.522   374   874 D CommandListener: Clearing all IP addresses on wlan0
,09-06 16:56:00.523   876  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-06 16:56:00.528   876  1317 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 16:56:00.532  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 16:56:00.532  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:00.532  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:00.532  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:00.532  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:00.532  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:56:00.532  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:00.532  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:00.532  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:00.532  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:56:00.533  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:00.533   876  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-06 16:56:00.533  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:56:00.533  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:00.533  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:00.533  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:00.533  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:00.533  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:56:00.533  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:00.533  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:00.533  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:00.533  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:56:00.534  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:00.537  1908  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:56:00.564   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 16:56:00.600   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-06 16:56:00.601   876  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 16:56:00.601   876  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:00.604   876   893 D Tethering: MasterInitialState.processMessage what=3
09-06 16:56:00.606  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:00.608  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:00.616  2099  2099 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-06 16:56:00.620  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 16:56:00.627  1729  1729 D SystemUpdateService: onCreate
,09-06 16:56:00.629  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 16:56:00.642  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 16:56:00.644  1729  2413 I iu.UploadsManager: num queued entries: 0
,09-06 16:56:00.644  1729  2413 I iu.UploadsManager: num updated entries: 0
,09-06 16:56:00.652  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 16:56:00.653  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-06 16:56:00.654  4019  4019 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:00.657  4019  4019 D SprintDMHelper: simOperator: 
09-06 16:56:00.657  4019  4019 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-06 16:56:00.667  1729  4161 I SystemUpdateService: active receiver: enabled
09-06 16:56:00.668  1729  2413 I iu.SyncManager: NEXT; no task
09-06 16:56:00.678   374   874 E Netd    : netlink response contains error (No such file or directory)
,09-06 16:56:00.679  1729  4161 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 16:56:00.695  2302  4165 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-06 16:56:00.700  1729  4161 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-06 16:56:00.700  1729  4161 I SystemUpdateService: now status is 0 (complete)
,09-06 16:56:00.700  1729  4161 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 16:56:00.700  1729  4161 I SystemUpdateService: file has been verified
09-06 16:56:00.701  1729  4161 I SystemUpdateService: OTA package size = 12249756
,09-06 16:56:00.711  1729  4161 I SystemUpdateService: showing system update notification
,09-06 16:56:00.732  1729  1729 D SystemUpdateService: onDestroy
09-06 16:56:00.733  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 16:56:00.792  1515  2047 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-06 16:56:00.792  1515  2047 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-06 16:56:00.792  1515  2047 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 16:56:00.792  1515  2047 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 16:56:00.813  3583  3583 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-06 16:56:00.813  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-06 16:56:00.814  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-06 16:56:03.508   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@48e1e6f:true
09-06 16:56:03.509  4005  4005 D BluetoothAdapterState: make() - Creating AdapterState
,09-06 16:56:03.514  4005  4005 I bt_bluedroid: init
,09-06 16:56:03.515  4005  4167 I BluetoothAdapterState: Entering OffState
,09-06 16:56:03.521  4005  4168 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 16:56:03.522  4005  4168 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 16:56:03.522  4005  4168 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 16:56:03.522  4005  4168 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 16:56:03.525  4005  4005 I bt_bluedroid: get_profile_interface socket
,09-06 16:56:03.528  4005  4005 I bt_bluedroid: get_profile_interface sdp
,09-06 16:56:03.532  4005  4016 I bt_bluedroid: config_hci_snoop_log
,09-06 16:56:03.534   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.,
,09-06 16:56:03.535  4005  4171 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-06 16:56:03.537  4005  4171 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 16:56:03.541  4005  4167 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 16:56:03.541  4005  4167 D BluetoothAdapterProperties: Setting state to 14
,09-06 16:56:03.542  4005  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 16:56:03.546  4005  4167 D BluetoothBondStateMachine: make
,09-06 16:56:03.549  4005  4172 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 16:56:03.558  4005  4167 I BluetoothAdapterState: Entering PendingCommandState
,09-06 16:56:03.559  4005  4005 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 16:56:03.563  4005  4005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:03.564  4005  4005 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 16:56:03.565  4005  4005 D BtGatt.GattService: Received start request. Starting profile...
09-06 16:56:03.565  4005  4005 D BtGatt.GattService: start()
,09-06 16:56:03.565  4005  4005 I bt_bluedroid: get_profile_interface gatt
,09-06 16:56:03.567  4005  4005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:03.567  4005  4005 D BtGatt.AdvertiseManager: advertise manager created
,09-06 16:56:03.575  4005  4005 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:56:03.575  4005  4005 V BluetoothAdapterState: isTurningOn()=false
09-06 16:56:03.575  4005  4005 V BluetoothAdapterState: isBleTurningOn()=true
09-06 16:56:03.575  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 16:56:03.576  4005  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-06 16:56:03.576  4005  4167 I bt_bluedroid: enable
,09-06 16:56:03.577  4005  4168 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-06 16:56:03.577  4005  4168 I bt_hci  : start_up
,09-06 16:56:03.583  4005  4168 I bt_vendor: alloc value 0xb39a9189
09-06 16:56:03.583  4005  4168 I bt_vendor: init
,09-06 16:56:03.583  4005  4168 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 16:56:03.583  4005  4168 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 16:56:03.691  4005  4168 D bt_hci  : start_up starting async portion
,09-06 16:56:03.692  4005  4175 I bt_hci  : event_finish_startup
09-06 16:56:03.692  4005  4175 I bt_hci_h4: hal_open
,09-06 16:56:03.692  4005  4175 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 16:56:03.697  4005  4175 I bt_userial_vendor: device fd = 51 open
,09-06 16:56:03.734  4005  4175 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 16:56:03.766  4005  4175 D bt_hwcfg: Chipset BCM4354A2
,09-06 16:56:03.767  4005  4175 D bt_hwcfg: Target name = [BCM4354A2]
,09-06 16:56:03.767  4005  4175 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 16:56:04.428  4005  4175 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 16:56:04.430  4005  4175 D bt_hwcfg: Settlement delay -- 100 ms
,09-06 16:56:04.430  4005  4175 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 16:56:04.546  4005  4175 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 16:56:04.548  4005  4175 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 16:56:04.577  4005  4175 I bt_hwcfg: vendor lib fwcfg completed
,09-06 16:56:04.578  4005  4175 I bt_vendor: firmware callback
09-06 16:56:04.578  4005  4175 I bt_hci  : firmware_config_callback
,09-06 16:56:04.589  4005  4177 I bt_btu  : btu_task pending for preload complete event
,09-06 16:56:04.590  4005  4177 I bt_btu_task: Bluetooth chip preload is complete
09-06 16:56:04.590  4005  4177 I bt_btu  : btu_task received preload complete event
,09-06 16:56:04.601  4005  4177 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 16:56:04.602  4005  4177 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 16:56:04.602  4005  4177 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 16:56:04.602  4005  4177 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 16:56:04.602  4005  4177 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 16:56:04.603  4005  4177 I         : BTE_InitTraceLevels -- TRC_A2D
,09-06 16:56:04.603  4005  4177 I         : BTE_InitTraceLevels -- TRC_BNEP,
,09-06 16:56:04.603  4005  4177 I         : BTE_InitTraceLevels -- TRC_BTM
,09-06 16:56:04.604  4005  4177 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 16:56:04.604  4005  4177 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 16:56:04.604  4005  4177 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 16:56:04.605  4005  4177 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 16:56:04.605  4005  4177 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 16:56:04.605  4005  4177 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 16:56:04.605  4005  4177 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 16:56:04.737  4005  4177 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
09-06 16:56:04.737  4005  4177 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,09-06 16:56:04.745  4005  4171 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 16:56:04.747  4005  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 16:56:04.747  4005  4171 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
,09-06 16:56:04.749  4005  4171 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 16:56:04.754  4005  4171 D BluetoothAdapterProperties: Scan Mode:20
,09-06 16:56:04.756  4005  4171 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 16:56:04.757  4005  4171 D bt_hci  : do_postload posting postload work item
,09-06 16:56:04.757  4005  4175 I bt_hci  : event_postload
09-06 16:56:04.757  4005  4175 I bt_vendor: sco_config_cb
,09-06 16:56:04.757  4005  4175 I bt_hci  : sco_config_callback postload finished.
,09-06 16:56:04.758  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:04.759  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:04.762  4005  4171 D bt_bte_conf: Device ID record 1 : primary
,09-06 16:56:04.762  4005  4171 D bt_bte_conf:   vendorId            = 000f
,09-06 16:56:04.763  4005  4171 D bt_bte_conf:   vendorIdSource      = 0001
,09-06 16:56:04.763  4005  4171 D bt_bte_conf:   product             = 1200
,09-06 16:56:04.763  4005  4171 D bt_bte_conf:   version             = 1436
,09-06 16:56:04.763  4005  4175 I bt_vendor: low_power_mode_cb
09-06 16:56:04.763  4005  4171 D bt_bte_conf:   clientExecutableURL = 
09-06 16:56:04.767  4005  4171 D bt_bte_conf:   serviceDescription  = 
,09-06 16:56:04.767  4005  4171 D bt_bte_conf:   documentationURL    = 
09-06 16:56:04.768  4005  4171 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-06 16:56:04.768  4005  4168 D bt_stack_manager: event_start_up_stack finished
09-06 16:56:04.769  4005  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-06 16:56:04.769  4005  4167 D BluetoothAdapterProperties: Setting state to 15
09-06 16:56:04.769  4005  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-06 16:56:04.770  4005  4167 I BluetoothAdapterState: Entering BleOnState
,09-06 16:56:04.774  4005  4167 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-06 16:56:04.774  4005  4167 D BluetoothAdapterProperties: Setting state to 11
,09-06 16:56:04.774  4005  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-06 16:56:04.779  4005  4005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:04.780  4005  4005 D HeadsetService: Received start request. Starting profile...
,09-06 16:56:04.783  4005  4005 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 16:56:04.784  4005  4005 D HeadsetStateMachine: make
09-06 16:56:04.784  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:04.785  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:04.792  4005  4167 I BluetoothAdapterState: Entering PendingCommandState
,09-06 16:56:04.792  4005  4005 D HeadsetStateMachine: max_hf_connections = 1
09-06 16:56:04.792  4005  4005 I bt_bluedroid: get_profile_interface handsfree
09-06 16:56:04.792  4005  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-06 16:56:04.792  4005  4171 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-06 16:56:04.797  4005  4005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:04.801  4005  4005 D A2dpService: Received start request. Starting profile...
,09-06 16:56:04.802  4005  4005 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 16:56:04.802  4005  4005 I bt_bluedroid: get_profile_interface avrcp
,09-06 16:56:04.808  4005  4005 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 16:56:04.809  4005  4005 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 16:56:04.809  4005  4005 D A2dpStateMachine: make
,09-06 16:56:04.810  4005  4005 I bt_bluedroid: get_profile_interface a2dp
09-06 16:56:04.811  4005  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 16:56:04.813  4005  4188 D A2dpStateMachine: Enter Disconnected: -2
,09-06 16:56:04.814  4005  4005 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 16:56:04.815  4005  4005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:04.816  3925  3925 D BluetoothInputDevice: Proxy object connected
,09-06 16:56:04.817  4005  4005 D HidService: Received start request. Starting profile...
09-06 16:56:04.817  3925  3925 D HidProfile: Bluetooth service connected
09-06 16:56:04.817  4005  4005 I bt_bluedroid: get_profile_interface hidhost
09-06 16:56:04.817  4005  4171 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
09-06 16:56:04.817  4005  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-06 16:56:04.817  4005  4005 D HidService: setHidService(): set to: null
09-06 16:56:04.818  4005  4005 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 16:56:04.819  4005  4005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:04.820  4005  4005 D HealthService: Received start request. Starting profile...
,09-06 16:56:04.821  4005  4005 I bt_bluedroid: get_profile_interface health
,09-06 16:56:04.822  4005  4005 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 16:56:04.822  4005  4005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:04.823  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 16:56:04.823  3925  3925 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 16:56:04.823  4005  4005 D PanService: Received start request. Starting profile...
09-06 16:56:04.824  4005  4005 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 16:56:04.824  4005  4005 I bt_bluedroid: get_profile_interface pan
,09-06 16:56:04.824  4005  4171 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 16:56:04.827  4005  4005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
09-06 16:56:04.828  4005  4005 D BluetoothMapService: Received start request. Starting profile...
,09-06 16:56:04.828  4005  4005 D BluetoothMapService: start()
,09-06 16:56:04.830  4005  4005 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 16:56:04.831  4005  4005 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-06 16:56:04.831  4005  4005 D BluetoothMapAppObserver: createReceiver()
09-06 16:56:04.831  4005  4005 D BluetoothMapAppObserver: initObservers()
,09-06 16:56:04.831  4005  4005 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 16:56:04.835  4005  4005 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:56:04.835  4005  4005 V BluetoothAdapterState: isTurningOn()=true
09-06 16:56:04.835  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 16:56:04.835  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 16:56:04.837  4005  4186 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isTurningOff()=false
09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isTurningOn()=true
,09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:04.824  3925  3925 D PanProfile: Bluetooth service connected
09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isTurningOn()=true
,09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isTurningOff()=false
09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isTurningOn()=true
09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:04.838  3925  3925 D BluetoothMap: Proxy object connected
09-06 16:56:04.838  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:04.839  3925  3925 D MapProfile: Bluetooth service connected
,09-06 16:56:04.839  3925  3925 D BluetoothMap: getConnectedDevices()
09-06 16:56:04.840  4005  4005 V BluetoothAdapterState: isTurningOff()=false
09-06 16:56:04.840  4005  4005 V BluetoothAdapterState: isTurningOn()=true
09-06 16:56:04.840  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:04.840  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:04.840  4005  4005 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:56:04.840  4005  4005 V BluetoothAdapterState: isTurningOn()=true
09-06 16:56:04.840  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 16:56:04.840  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:04.841  4005  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-06 16:56:04.841  4005  4167 D BluetoothAdapterProperties: ScanMode =  20
09-06 16:56:04.841  4005  4167 D BluetoothAdapterProperties: State =  11
,09-06 16:56:04.841  3925  3925 D BluetoothMap: Bluetooth is Not enabled
09-06 16:56:04.843  4005  4171 D BluetoothAdapterProperties: Scan Mode:21
09-06 16:56:04.843  4005  4171 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 16:56:04.843  4005  4167 D BluetoothAdapterProperties: Setting state to 12
09-06 16:56:04.843  4005  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 16:56:04.843  1373  2133 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 16:56:04.845  4005  4167 I BluetoothAdapterState: Entering OnState
09-06 16:56:04.845  3925  3938 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 16:56:04.845   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:04.845  1373  1385 D BluetoothPan: onBluetoothStateChange on: true
09-06 16:56:04.845  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:04.845  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:04.845  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:04.845  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:04.845  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:04.845  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:04.845  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:04.845  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:04.847  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:04.848  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 16:56:04.848  1373  1373 D PanProfile: Bluetooth service connected
09-06 16:56:04.848  1373  3859 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 16:56:04.848  1373  1373 D BluetoothA2dp: Proxy object connected
09-06 16:56:04.850  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:04.850  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:04.850  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:04.850  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:04.850  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:04.850  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:04.850  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:04.850  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:04.851  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:04.853  1985  2168 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 16:56:04.854   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:04.854  3925  3937 D BluetoothPan: onBluetoothStateChange on: true
,09-06 16:56:04.854   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 16:56:04.855   876   876 D BluetoothA2dp: Proxy object connected
09-06 16:56:04.855  3925  3935 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 16:56:04.855   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 16:56:04.855  1373  1386 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 16:56:04.857  4005  4005 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-06 16:56:04.857  3925  3938 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 16:56:04.857  1373  1373 D BluetoothMap: Proxy object connected
09-06 16:56:04.857  1373  1373 D MapProfile: Bluetooth service connected
,09-06 16:56:04.857  1373  1373 D BluetoothMap: getConnectedDevices()
09-06 16:56:04.858  4005  4005 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-06 16:56:04.858  1373  3858 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:04.858  1373  2133 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 16:56:04.859  4005  4005 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:04.860  1373  1373 D BluetoothInputDevice: Proxy object connected
,09-06 16:56:04.860  1373  1373 D HidProfile: Bluetooth service connected
,09-06 16:56:04.862   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 16:56:04.863  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:04.864  4005  4005 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:04.864  3925  3925 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 16:56:04.865  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:04.865  4005  4005 D ObexServerSockets: Succeed to create listening sockets 
09-06 16:56:04.865  4005  4005 D ObexServerSockets0: startAccept()
09-06 16:56:04.865  4005  4005 D ObexServerSockets0: prepareForNewConnect()
09-06 16:56:04.868  3925  3925 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-06 16:56:04.868  4005  4005 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 16:56:04.868  4005  4005 D BluetoothSdpJni: SDP Create record success - handle: 0
09-06 16:56:04.868  4005  4005 D BluetoothMapService: onReceive
09-06 16:56:04.868  4005  4005 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:04.868  4005  4005 D BluetoothMapService: STATE_ON
09-06 16:56:04.869  4005  4195 D ObexServerSockets0: Accepting socket connection...
09-06 16:56:04.869  4005  4196 D ObexServerSockets0: Accepting socket connection...
,09-06 16:56:04.873  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:56:04.876  3925  3925 D BluetoothA2dp: Proxy object connected
,09-06 16:56:04.879  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 16:56:04.883  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:56:04.888  1373  1373 D BluetoothPbap: Proxy object connected
,09-06 16:56:04.888  1373  1373 D PbapServerProfile: Bluetooth service connected
09-06 16:56:04.888  3925  3925 D BluetoothPbap: Proxy object connected
09-06 16:56:04.888  3925  3925 D PbapServerProfile: Bluetooth service connected
,09-06 16:56:04.892  4005  4005 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-06 16:56:04.892  4005  4005 D ObexServerSockets0: prepareForNewConnect()
09-06 16:56:04.893  4005  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:56:04.909  4005  4204 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:56:04.913  4005  4204 I BtOppRfcommListener: Accept thread started.
,09-06 16:56:04.946  1373  2133 D BluetoothHeadset: Proxy object connected
,09-06 16:56:04.947  1373  1373 D HeadsetProfile: Bluetooth service connected
09-06 16:56:04.947  1985  2170 D BluetoothHeadset: Proxy object connected
,09-06 16:56:04.947   876   876 D BluetoothHeadset: Proxy object connected
,09-06 16:56:04.947   876   876 D BluetoothHeadset: Proxy object connected
09-06 16:56:04.947   876   876 D BluetoothHeadset: Proxy object connected
,09-06 16:56:04.954  1985  1997 D BluetoothHeadset: Proxy object connected
,09-06 16:56:04.954   876   893 D BluetoothHeadset: Proxy object connected
09-06 16:56:04.954   876   893 D BluetoothHeadset: Proxy object connected
,09-06 16:56:04.959  1373  1386 D BluetoothHeadset: Proxy object connected
,09-06 16:56:04.959  1373  1373 D HeadsetProfile: Bluetooth service connected
,09-06 16:56:04.970  3925  3938 D BluetoothHeadset: Proxy object connected
,09-06 16:56:04.971  3925  3925 D HeadsetProfile: Bluetooth service connected
,09-06 16:56:06.486  4005  4167 D BluetoothAdapterState: Current state: ON, message: 23
,09-06 16:56:06.487  4005  4167 D BluetoothAdapterProperties: Setting state to 13
,09-06 16:56:06.487  4005  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-06 16:56:06.487   876  1319 D ConnectivityService: handlePromptUnvalidated 101
09-06 16:56:06.488  4005  4167 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 16:56:06.493  4005  4167 I BluetoothAdapterState: Entering PendingCommandState
09-06 16:56:06.498  4005  4005 D BluetoothMapService: onReceive
09-06 16:56:06.498  4005  4005 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:06.499  4005  4005 D BluetoothMapService: STATE_TURNING_OFF
09-06 16:56:06.500  4005  4005 D BluetoothMapService: MAP Service closeService in
09-06 16:56:06.500  4005  4005 D BluetoothMapMasInstance0: MAP Service shutdown
,09-06 16:56:06.501  4005  4005 D ObexServerSockets0: shutdown(block = true)
09-06 16:56:06.501  4005  4195 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-06 16:56:06.504  4005  4005 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 16:56:06.505  4005  4196 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 16:56:06.506  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:56:06.506  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:06.506  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:06.506  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:06.506  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:06.506  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:56:06.506  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:06.506  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:06.506  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:06.507  4005  4005 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-06 16:56:06.508  4005  4181 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-06 16:56:06.508  4005  4005 I BtOppRfcommListener: stopping Accept Thread
09-06 16:56:06.509  4005  4171 D BluetoothAdapterProperties: Scan Mode:20
09-06 16:56:06.510  4005  4204 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 16:56:06.511  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:56:06.511  4005  4204 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 16:56:06.511  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:06.513  4005  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-06 16:56:06.516  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:56:06.518  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:56:06.518  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:06.518  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:06.518  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:06.518  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:06.518  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:56:06.518  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:06.518  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:06.518  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:06.519  4005  4005 D HeadsetService: Received stop request...Stopping profile...
09-06 16:56:06.519  3860  3860 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:56:06.519  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:06.521  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:06.523  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:06.526  3925  3935 D BluetoothHeadset: Proxy object disconnected
09-06 16:56:06.526  1373  2133 D BluetoothHeadset: Proxy object disconnected
09-06 16:56:06.527  4005  4005 D A2dpService: Received stop request...Stopping profile...
,09-06 16:56:06.527  1985  1998 D BluetoothHeadset: Proxy object disconnected
09-06 16:56:06.527   876   876 D BluetoothHeadset: Proxy object disconnected
09-06 16:56:06.527   876   876 D BluetoothHeadset: Proxy object disconnected
,09-06 16:56:06.528   876   876 D BluetoothHeadset: Proxy object disconnected
09-06 16:56:06.528  4005  4188 D A2dpStateMachine: Exit Disconnected: -1
09-06 16:56:06.530   876   876 D BluetoothA2dp: Proxy object disconnected
,09-06 16:56:06.531  4005  4005 D HidService: Received stop request...Stopping profile...
09-06 16:56:06.531  4005  4005 D HidService: Stopping Bluetooth HidService
,09-06 16:56:06.534  3925  3925 D DockEventReceiver: finishStartingService: stopping service
09-06 16:56:06.534  4005  4005 V BluetoothAdapterState: isTurningOff()=true
09-06 16:56:06.534  4005  4005 V BluetoothAdapterState: isTurningOn()=false
,09-06 16:56:06.534  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:06.534  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 16:56:06.538  1373  1373 D HeadsetProfile: Bluetooth service disconnected
09-06 16:56:06.539  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 16:56:06.540  1373  1373 D BluetoothA2dp: Proxy object disconnected
09-06 16:56:06.540  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,09-06 16:56:06.540  1373  1373 D HidProfile: Bluetooth service disconnected
,09-06 16:56:06.541  3925  3925 D HeadsetProfile: Bluetooth service disconnected
,09-06 16:56:06.541  4005  4005 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 16:56:06.541  4005  4005 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 16:56:06.541  3925  3925 D BluetoothA2dp: Proxy object disconnected
09-06 16:56:06.542  4005  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 16:56:06.542  4005  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:56:06.542  4005  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:56:06.542  4005  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:56:06.542  3925  3925 D BluetoothInputDevice: Proxy object disconnected
,09-06 16:56:06.542  3925  3925 D HidProfile: Bluetooth service disconnected
09-06 16:56:06.542  4005  4171 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-06 16:56:06.542  4005  4005 D HealthService: Received stop request...Stopping profile...
,09-06 16:56:06.545  4005  4005 D PanService: Received stop request...Stopping profile...
,09-06 16:56:06.547  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 16:56:06.547  1373  1373 D PanProfile: Bluetooth service disconnected
09-06 16:56:06.547  4005  4005 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 16:56:06.547  4005  4005 D BluetoothMapService: stop()
09-06 16:56:06.548  4005  4005 D BluetoothMapAppObserver: deinitObservers()
09-06 16:56:06.548  4005  4005 D BluetoothMapAppObserver: removeReceiver()
,09-06 16:56:06.548  3925  3925 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 16:56:06.549  3925  3925 D PanProfile: Bluetooth service disconnected
,09-06 16:56:06.549  1373  1373 D BluetoothMap: Proxy object disconnected
09-06 16:56:06.549  1373  1373 D MapProfile: Bluetooth service disconnected
,09-06 16:56:06.549  3925  3925 D BluetoothMap: Proxy object disconnected
09-06 16:56:06.549  3925  3925 D MapProfile: Bluetooth service disconnected
09-06 16:56:06.549  4005  4005 V BluetoothAdapterState: isTurningOff()=true
,09-06 16:56:06.550  4005  4005 V BluetoothAdapterState: isTurningOn()=false
09-06 16:56:06.550  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:06.550  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 16:56:06.551  4005  4005 V BluetoothAdapterState: isTurningOff()=true
09-06 16:56:06.551  4005  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 16:56:06.551  4005  4005 V BluetoothAdapterState: isTurningOn()=false
09-06 16:56:06.551  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 16:56:06.551  4005  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:56:06.552  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:06.552  4005  4177 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:56:06.552  4005  4177 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-06 16:56:06.552  4005  4177 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:56:06.552  4005  4177 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:56:06.551  4005  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 16:56:06.552  4005  4005 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-06 16:56:06.552  4005  4005 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-06 16:56:06.552  4005  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 16:56:06.554  1373  1373 D BluetoothPbap: Proxy object disconnected
09-06 16:56:06.554  1373  1373 D PbapServerProfile: Bluetooth service disconnected
09-06 16:56:06.557  4005  4005 V BluetoothAdapterState: isTurningOff()=true
09-06 16:56:06.557  4005  4005 V BluetoothAdapterState: isTurningOn()=false
,09-06 16:56:06.557  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:06.557  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:06.557  4005  4005 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 16:56:06.557  4005  4171 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 16:56:06.557  4005  4005 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-06 16:56:06.558  4005  4005 V BluetoothAdapterState: isTurningOff()=true
09-06 16:56:06.558  4005  4005 V BluetoothAdapterState: isTurningOn()=false
09-06 16:56:06.558  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 16:56:06.558  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:06.558  4005  4005 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 16:56:06.558  4005  4005 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 16:56:06.559  4005  4005 D BluetoothMapService: MAP Service closeService in
09-06 16:56:06.560  4005  4005 V BluetoothAdapterState: isTurningOff()=true
,09-06 16:56:06.560  4005  4005 V BluetoothAdapterState: isTurningOn()=false
09-06 16:56:06.560  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 16:56:06.560  4005  4005 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:06.560  4005  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 16:56:06.560  4005  4167 D BluetoothAdapterProperties: Setting state to 15
,09-06 16:56:06.560  4005  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-06 16:56:06.561  1373  1386 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 16:56:06.561  4005  4167 I BluetoothAdapterState: Entering BleOnState
09-06 16:56:06.562  3925  3935 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 16:56:06.562  4005  4005 D BluetoothMapService: cleanup()
09-06 16:56:06.562  4005  4005 D BluetoothMapService: MAP Service closeService in
09-06 16:56:06.562   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 16:56:06.563  3925  3938 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:56:06.565  1373  3858 D BluetoothPan: onBluetoothStateChange on: false
,09-06 16:56:06.565  3925  3925 D BluetoothPbap: Proxy object disconnected
09-06 16:56:06.565  3925  3925 D PbapServerProfile: Bluetooth service disconnected,
09-06 16:56:06.565  1373  3859 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 16:56:06.569  1985  2168 D BluetoothHeadset: onBluetoothStateChange: up=false,
09-06 16:56:06.569   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 16:56:06.570  3925  3935 D BluetoothPan: onBluetoothStateChange on: false
,09-06 16:56:06.571  3925  3938 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 16:56:06.571   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:56:06.571  3925  3937 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 16:56:06.572   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 16:56:06.572  1373  2133 D BluetoothMap: onBluetoothStateChange: up=false
09-06 16:56:06.573  3925  3935 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 16:56:06.573  1373  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:56:06.573  1373  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 16:56:06.574  4005  4167 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 16:56:06.574  4005  4167 D BluetoothAdapterProperties: Setting state to 16
,09-06 16:56:06.574  4005  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-06 16:56:06.575  4005  4167 D BluetoothAdapterProperties: onBleDisable
09-06 16:56:06.576  4005  4167 I BluetoothAdapterState: Entering PendingCommandState
09-06 16:56:06.576  4005  4168 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 16:56:06.577  4005  4177 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 16:56:06.577  4005  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 16:56:06.578  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:06.578  4005  4171 D BluetoothAdapterProperties: Scan Mode:20
09-06 16:56:06.579  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:06.579  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:56:06.581  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:06.582  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:06.585  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 16:56:06.587  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:56:06.777  4005  4171 I bt_hci  : shut_down
,09-06 16:56:06.790  4005  4175 D bt_hwcfg: hw_epilog_process
,09-06 16:56:06.791  4005  4175 I bt_vendor: low_power_mode_cb
,09-06 16:56:06.821  4005  4175 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 16:56:06.821  4005  4175 I bt_vendor: epilog_cb
09-06 16:56:06.821  4005  4175 I bt_hci  : epilog_finished_callback
,09-06 16:56:06.827  4005  4171 I bt_hci_h4: hal_close
,09-06 16:56:06.828  4005  4171 I bt_userial_vendor: device fd = 51 close
,09-06 16:56:06.940  4005  4168 D bt_stack_manager: event_shut_down_stack finished.
,09-06 16:56:06.941  4005  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 16:56:06.947  4005  4167 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-06 16:56:06.947  4005  4005 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 16:56:06.949  4005  4005 D BtGatt.GattService: Received stop request...Stopping profile...
,09-06 16:56:06.949  4005  4005 D BtGatt.GattService: stop()
09-06 16:56:06.949  4005  4005 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 16:56:06.955  4005  4005 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:56:06.955  4005  4005 V BluetoothAdapterState: isTurningOn()=false
,09-06 16:56:06.955  4005  4005 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 16:56:06.955  4005  4005 V BluetoothAdapterState: isBleTurningOff()=true
09-06 16:56:06.956  4005  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-06 16:56:06.957  4005  4167 D BluetoothAdapterProperties: Setting state to 10
,09-06 16:56:06.957  4005  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-06 16:56:06.959  4005  4167 I BluetoothAdapterState: Entering OffState
,09-06 16:56:06.960   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 16:56:06.995  4005  4005 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-06 16:56:06.996  4005  4005 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 16:56:06.996  4005  4168 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-06 16:56:06.999  4005  4168 D bt_stack_manager: event_clean_up_stack finished.
,09-06 16:56:06.999  4005  4005 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 16:56:07.002  4005  4005 I art     : System.exit called, status: 0
,09-06 16:56:07.002  4005  4005 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 16:56:07.072   876  1703 I ActivityManager: Process com.android.bluetooth (pid 4005) has died
,09-06 16:56:09.482  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 16:56:09.483  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:10.117   876   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-06 16:56:10.124  1894  1894 I Keyboard.Facilitator: onFinishInput()
,09-06 16:56:10.132   876   896 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 16:56:10.132   876   896 I Adreno  : Build Date                       : 10/20/15
09-06 16:56:10.132   876   896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 16:56:10.132   876   896 I Adreno  : Local Branch                     : M14
09-06 16:56:10.132   876   896 I Adreno  : Remote Branch                    : 
09-06 16:56:10.132   876   896 I Adreno  : Remote Branch                    : 
09-06 16:56:10.132   876   896 I Adreno  : Reconstruct Branch               : 
,09-06 16:56:10.186   280   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (280 us)
,09-06 16:56:10.822  3860  3860 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 16:56:10.823  3860  3860 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 16:56:10.860   876   896 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-06 16:56:10.863  3860  3860 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@84fd94e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@a6d6428, 16908290=android.view.AbsSavedState$1@a6d6428}, android:focusedViewId=100}]}]
,09-06 16:56:10.863  3860  3860 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 16:56:10.866  3860  3860 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 16:56:10.866  3860  3860 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-06 16:56:10.868   876   896 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-06 16:56:10.874   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-06 16:56:10.875   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-06 16:56:10.875   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-06 16:56:11.109   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-06 16:56:11.113   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-06 16:56:11.114   876  1341 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-06 16:56:11.119   876   896 I DreamManagerService: Entering dreamland.
,09-06 16:56:11.120   876   896 I PowerManagerService: Dozing...
,09-06 16:56:11.122   876   891 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-06 16:56:11.213   378  1290 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-06 16:56:11.214   378  1290 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-06 16:56:11.229   876  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 16:56:11.242   876  1317 E native  : do suspend false
,09-06 16:56:11.254  1970  4216 D NfcService: Discovery configuration equal, not updating.
,09-06 16:56:11.302   876  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 16:56:11.314   876  1317 E native  : do suspend true
,09-06 16:56:11.342   378   378 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-06 16:56:11.342   378   378 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-06 16:56:12.491  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 16:56:12.491  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4080541 added. We now have 6 listener(s)
09-06 16:56:12.491  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:12.495  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 16:56:12.495  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a4a3ae6 added. We now have 7 listener(s)
09-06 16:56:12.496  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:12.498  3860  3908 I System.out: IsBluetoothEnabled
,09-06 16:56:12.509  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:12.560   876   893 I ActivityManager: Start proc 4222:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-06 16:56:12.713  4222  4222 D AdapterServiceConfig: Adding HeadsetService
,09-06 16:56:12.715  4222  4222 D AdapterServiceConfig: Adding A2dpService
,09-06 16:56:12.715  4222  4222 D AdapterServiceConfig: Adding HidService
09-06 16:56:12.715  4222  4222 D AdapterServiceConfig: Adding HealthService
09-06 16:56:12.715  4222  4222 D AdapterServiceConfig: Adding PanService
09-06 16:56:12.716  4222  4222 D AdapterServiceConfig: Adding GattService
,09-06 16:56:12.716  4222  4222 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 16:56:12.734   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3715827:true
,09-06 16:56:12.736  4222  4222 D BluetoothAdapterState: make() - Creating AdapterState
,09-06 16:56:12.743  4222  4234 I BluetoothAdapterState: Entering OffState
,09-06 16:56:12.743  4222  4222 I bt_bluedroid: init
,09-06 16:56:12.749  4222  4235 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 16:56:12.750  4222  4235 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 16:56:12.750  4222  4235 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 16:56:12.750  4222  4235 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 16:56:12.752  4222  4222 I bt_bluedroid: get_profile_interface socket
,09-06 16:56:12.757  4222  4222 I bt_bluedroid: get_profile_interface sdp
,09-06 16:56:12.758  4222  4238 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 16:56:12.764  4222  4238 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 16:56:12.765  4222  4232 I bt_bluedroid: config_hci_snoop_log
,09-06 16:56:12.769   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 16:56:12.781  4222  4234 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 16:56:12.782  4222  4234 D BluetoothAdapterProperties: Setting state to 14
09-06 16:56:12.782  4222  4234 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 16:56:12.785  4222  4234 D BluetoothBondStateMachine: make
,09-06 16:56:12.793  4222  4239 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 16:56:12.811  4222  4234 I BluetoothAdapterState: Entering PendingCommandState
,09-06 16:56:12.815  4222  4222 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 16:56:12.826  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:12.827  4222  4222 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 16:56:12.827  4222  4222 D BtGatt.GattService: Received start request. Starting profile...
09-06 16:56:12.827  4222  4222 D BtGatt.GattService: start()
,09-06 16:56:12.828  4222  4222 I bt_bluedroid: get_profile_interface gatt
09-06 16:56:12.828  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
09-06 16:56:12.829  4222  4222 D BtGatt.AdvertiseManager: advertise manager created
,09-06 16:56:12.837  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:56:12.837  4222  4222 V BluetoothAdapterState: isTurningOn()=false
09-06 16:56:12.837  4222  4222 V BluetoothAdapterState: isBleTurningOn()=true
09-06 16:56:12.837  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:12.838  4222  4234 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-06 16:56:12.839  4222  4234 I bt_bluedroid: enable
09-06 16:56:12.839  4222  4235 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-06 16:56:12.839  4222  4235 I bt_hci  : start_up
,09-06 16:56:12.847  4222  4235 I bt_vendor: alloc value 0xb3a04189
,09-06 16:56:12.847  4222  4235 I bt_vendor: init
09-06 16:56:12.847  4222  4235 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 16:56:12.848  4222  4235 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 16:56:12.956  4222  4235 D bt_hci  : start_up starting async portion
,09-06 16:56:12.956  4222  4242 I bt_hci  : event_finish_startup
,09-06 16:56:12.956  4222  4242 I bt_hci_h4: hal_open
09-06 16:56:12.957  4222  4242 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 16:56:12.966  4222  4242 I bt_userial_vendor: device fd = 51 open
,09-06 16:56:12.998  4222  4242 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 16:56:13.030  4222  4242 D bt_hwcfg: Chipset BCM4354A2
,09-06 16:56:13.030  4222  4242 D bt_hwcfg: Target name = [BCM4354A2]
09-06 16:56:13.031  4222  4242 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 16:56:13.691  4222  4242 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 16:56:13.692  4222  4242 D bt_hwcfg: Settlement delay -- 100 ms
09-06 16:56:13.693  4222  4242 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 16:56:13.809  4222  4242 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 16:56:13.811  4222  4242 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 16:56:13.840  4222  4242 I bt_hwcfg: vendor lib fwcfg completed
,09-06 16:56:13.840  4222  4242 I bt_vendor: firmware callback
09-06 16:56:13.840  4222  4242 I bt_hci  : firmware_config_callback
,09-06 16:56:13.852  4222  4244 I bt_btu  : btu_task pending for preload complete event
,09-06 16:56:13.852  4222  4244 I bt_btu_task: Bluetooth chip preload is complete
09-06 16:56:13.853  4222  4244 I bt_btu  : btu_task received preload complete event
,09-06 16:56:13.864  4222  4244 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 16:56:13.865  4222  4244 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 16:56:13.865  4222  4244 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 16:56:13.865  4222  4244 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 16:56:13.866  4222  4244 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-06 16:56:13.866  4222  4244 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 16:56:13.866  4222  4244 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 16:56:13.866  4222  4244 I         : BTE_InitTraceLevels -- TRC_BTM
,09-06 16:56:13.867  4222  4244 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 16:56:13.867  4222  4244 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 16:56:13.867  4222  4244 I         : BTE_InitTraceLevels -- TRC_SDP
,09-06 16:56:13.868  4222  4244 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 16:56:13.868  4222  4244 I         : BTE_InitTraceLevels -- TRC_SMP
,09-06 16:56:13.868  4222  4244 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 16:56:13.868  4222  4244 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 16:56:14.001  4222  4244 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3981d9d
09-06 16:56:14.002  4222  4244 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3981d9d 
,09-06 16:56:14.006  4222  4238 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 16:56:14.008  4222  4238 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 16:56:14.008  4222  4238 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 16:56:14.011  4222  4238 D BluetoothAdapterProperties: Name is: Nexus 6
09-06 16:56:14.012  4222  4238 D BluetoothAdapterProperties: Scan Mode:20
09-06 16:56:14.012  4222  4238 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 16:56:14.013  4222  4238 D bt_hci  : do_postload posting postload work item
09-06 16:56:14.013  4222  4242 I bt_hci  : event_postload
09-06 16:56:14.013  4222  4242 I bt_vendor: sco_config_cb
,09-06 16:56:14.013  4222  4242 I bt_hci  : sco_config_callback postload finished.
,09-06 16:56:14.015  4222  4238 D bt_bte_conf: Device ID record 1 : primary
09-06 16:56:14.015  4222  4238 D bt_bte_conf:   vendorId            = 000f
09-06 16:56:14.015  4222  4238 D bt_bte_conf:   vendorIdSource      = 0001
09-06 16:56:14.015  4222  4238 D bt_bte_conf:   product             = 1200
09-06 16:56:14.015  4222  4238 D bt_bte_conf:   version             = 1436
09-06 16:56:14.015  4222  4238 D bt_bte_conf:   clientExecutableURL = 
09-06 16:56:14.015  4222  4238 D bt_bte_conf:   serviceDescription  = 
09-06 16:56:14.015  4222  4238 D bt_bte_conf:   documentationURL    = 
09-06 16:56:14.015  4222  4238 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-06 16:56:14.015  4222  4235 D bt_stack_manager: event_start_up_stack finished
09-06 16:56:14.016  4222  4234 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-06 16:56:14.016  4222  4234 D BluetoothAdapterProperties: Setting state to 15
,09-06 16:56:14.017  4222  4234 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-06 16:56:14.021  4222  4234 I BluetoothAdapterState: Entering BleOnState
09-06 16:56:14.021  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:14.023  4222  4242 I bt_vendor: low_power_mode_cb
09-06 16:56:14.024  4222  4234 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-06 16:56:14.024  4222  4234 D BluetoothAdapterProperties: Setting state to 11
09-06 16:56:14.024  4222  4234 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-06 16:56:14.030  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:14.037  4222  4222 D HeadsetService: Received start request. Starting profile...
09-06 16:56:14.039  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:14.040  4222  4222 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 16:56:14.041  4222  4222 D HeadsetStateMachine: make
,09-06 16:56:14.049  4222  4222 D HeadsetStateMachine: max_hf_connections = 1
,09-06 16:56:14.049  4222  4222 I bt_bluedroid: get_profile_interface handsfree
09-06 16:56:14.049  4222  4238 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-06 16:56:14.050  4222  4238 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-06 16:56:14.051  4222  4234 I BluetoothAdapterState: Entering PendingCommandState
,09-06 16:56:14.053  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:14.054  4222  4222 D A2dpService: Received start request. Starting profile...
,09-06 16:56:14.054  4222  4222 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 16:56:14.055  4222  4222 I bt_bluedroid: get_profile_interface avrcp
,09-06 16:56:14.060  4222  4222 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 16:56:14.060  4222  4222 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 16:56:14.060  4222  4222 D A2dpStateMachine: make
,09-06 16:56:14.061  4222  4222 I bt_bluedroid: get_profile_interface a2dp
09-06 16:56:14.062  4222  4238 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 16:56:14.066  4222  4253 D A2dpStateMachine: Enter Disconnected: -2
,09-06 16:56:14.067  4222  4222 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 16:56:14.068  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 16:56:14.068  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:14.070  4222  4222 D HidService: Received start request. Starting profile...
09-06 16:56:14.070  4222  4222 I bt_bluedroid: get_profile_interface hidhost
,09-06 16:56:14.070  4222  4238 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39633e5
09-06 16:56:14.070  4222  4222 D HidService: setHidService(): set to: null
09-06 16:56:14.070  4222  4238 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-06 16:56:14.071  4222  4222 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 16:56:14.072  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
09-06 16:56:14.072  4222  4222 D HealthService: Received start request. Starting profile...
,09-06 16:56:14.074  4222  4222 I bt_bluedroid: get_profile_interface health
09-06 16:56:14.075  4222  4222 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 16:56:14.075  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:14.076  4222  4222 D PanService: Received start request. Starting profile...
,09-06 16:56:14.076  4222  4222 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 16:56:14.076  4222  4222 I bt_bluedroid: get_profile_interface pan
09-06 16:56:14.076  4222  4238 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 16:56:14.079  4222  4222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:14.080  4222  4222 D BluetoothMapService: Received start request. Starting profile...
,09-06 16:56:14.080  4222  4222 D BluetoothMapService: start()
,09-06 16:56:14.082  4222  4222 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 16:56:14.083  4222  4222 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-06 16:56:14.083  4222  4222 D BluetoothMapAppObserver: createReceiver()
,09-06 16:56:14.084  4222  4222 D BluetoothMapAppObserver: initObservers()
,09-06 16:56:14.084  4222  4222 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 16:56:14.091  4222  4251 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 16:56:14.091  4222  4222 V BluetoothAdapterState: isTurningOff()=false
09-06 16:56:14.091  4222  4222 V BluetoothAdapterState: isTurningOn()=true
,09-06 16:56:14.091  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:14.092  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 16:56:14.093  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:56:14.093  4222  4222 V BluetoothAdapterState: isTurningOn()=true
09-06 16:56:14.093  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:14.093  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 16:56:14.095  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:56:14.095  4222  4222 V BluetoothAdapterState: isTurningOn()=true
09-06 16:56:14.095  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:14.095  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:14.095  4222  4222 V BluetoothAdapterState: isTurningOff()=false
,09-06 16:56:14.095  4222  4222 V BluetoothAdapterState: isTurningOn()=true
09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isTurningOff()=false
09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isTurningOn()=true
09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isTurningOff()=false
09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isTurningOn()=true
09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isBleTurningOn()=false
09-06 16:56:14.096  4222  4222 V BluetoothAdapterState: isBleTurningOff()=false
09-06 16:56:14.097  4222  4234 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-06 16:56:14.097  4222  4234 D BluetoothAdapterProperties: ScanMode =  20
,09-06 16:56:14.098  4222  4234 D BluetoothAdapterProperties: State =  11
,09-06 16:56:14.098  4222  4234 D BluetoothAdapterProperties: Setting state to 12
09-06 16:56:14.098  4222  4234 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 16:56:14.099  1373  2133 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 16:56:14.100  4222  4238 D BluetoothAdapterProperties: Scan Mode:21
09-06 16:56:14.100  4222  4238 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 16:56:14.100  4222  4234 I BluetoothAdapterState: Entering OnState
09-06 16:56:14.101  1373  1373 D BluetoothA2dp: Proxy object connected
09-06 16:56:14.103  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:14.103  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:14.103  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:14.103  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:14.103  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:14.103  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:14.103  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:14.103  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:14.103  3925  3938 D BluetoothMap: onBluetoothStateChange: up=true
09-06 16:56:14.105  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:14.108   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 16:56:14.108  3925  3937 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 16:56:14.109  3925  3925 D BluetoothMap: Proxy object connected
,09-06 16:56:14.110  4222  4222 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-06 16:56:14.110  3925  3925 D MapProfile: Bluetooth service connected
,09-06 16:56:14.110  1373  1386 D BluetoothPan: onBluetoothStateChange on: true
,09-06 16:56:14.110  4222  4222 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-06 16:56:14.111  3925  3925 D BluetoothMap: getConnectedDevices()
09-06 16:56:14.112  4222  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:14.112  1373  1385 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 16:56:14.112  3925  3925 D BluetoothA2dp: Proxy object connected
09-06 16:56:14.114  1985  2168 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:14.114  4222  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:14.114   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 16:56:14.114  3925  3938 D BluetoothPan: onBluetoothStateChange on: true
09-06 16:56:14.115  4222  4222 D ObexServerSockets: Succeed to create listening sockets 
09-06 16:56:14.115  4222  4222 D ObexServerSockets0: startAccept()
09-06 16:56:14.115  4222  4222 D ObexServerSockets0: prepareForNewConnect()
09-06 16:56:14.116  3925  3935 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:14.117   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 16:56:14.117  4222  4222 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-06 16:56:14.117  4222  4222 D BluetoothSdpJni: SDP Create record success - handle: 0
09-06 16:56:14.118   876   876 D BluetoothA2dp: Proxy object connected
09-06 16:56:14.118  3925  3937 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 16:56:14.118  4222  4260 D ObexServerSockets0: Accepting socket connection...
09-06 16:56:14.119  4222  4259 D ObexServerSockets0: Accepting socket connection...
09-06 16:56:14.119  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 16:56:14.119  1373  1373 D PanProfile: Bluetooth service connected
09-06 16:56:14.119  3925  3925 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 16:56:14.119  3925  3925 D PanProfile: Bluetooth service connected
09-06 16:56:14.120   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:14.121  1373  3858 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 16:56:14.122  1373  1373 D BluetoothMap: Proxy object connected
09-06 16:56:14.122  3925  3938 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 16:56:14.122  1373  1373 D MapProfile: Bluetooth service connected
09-06 16:56:14.122  1373  1373 D BluetoothMap: getConnectedDevices()
,09-06 16:56:14.123  1373  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 16:56:14.123  3925  3925 D BluetoothInputDevice: Proxy object connected
09-06 16:56:14.124  3925  3925 D HidProfile: Bluetooth service connected
09-06 16:56:14.124  1373  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 16:56:14.125  1373  1373 D BluetoothInputDevice: Proxy object connected
09-06 16:56:14.125  1373  1373 D HidProfile: Bluetooth service connected
09-06 16:56:14.126   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 16:56:14.127  4222  4222 D BluetoothMapService: onReceive
,09-06 16:56:14.127  4222  4222 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:14.127  4222  4222 D BluetoothMapService: STATE_ON
09-06 16:56:14.129  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:14.132  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:56:14.138  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 16:56:14.140  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:56:14.148  3925  3925 D BluetoothPbap: Proxy object connected
,09-06 16:56:14.148  3925  3925 D PbapServerProfile: Bluetooth service connected
,09-06 16:56:14.151  1373  1373 D BluetoothPbap: Proxy object connected
,09-06 16:56:14.151  1373  1373 D PbapServerProfile: Bluetooth service connected
,09-06 16:56:14.154  4222  4222 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-06 16:56:14.154  4222  4222 D ObexServerSockets0: prepareForNewConnect()
,09-06 16:56:14.157  4222  4265 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:56:14.176  4222  4269 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:56:14.178  4222  4269 I BtOppRfcommListener: Accept thread started.
,09-06 16:56:14.211  3925  3935 D BluetoothHeadset: Proxy object connected
,09-06 16:56:14.211  3925  3925 D HeadsetProfile: Bluetooth service connected
09-06 16:56:14.212  1373  1385 D BluetoothHeadset: Proxy object connected
,09-06 16:56:14.212  1373  1373 D HeadsetProfile: Bluetooth service connected
,09-06 16:56:14.213  1985  2170 D BluetoothHeadset: Proxy object connected
,09-06 16:56:14.213   876   876 D BluetoothHeadset: Proxy object connected
09-06 16:56:14.213   876   876 D BluetoothHeadset: Proxy object connected
,09-06 16:56:14.213   876   876 D BluetoothHeadset: Proxy object connected
09-06 16:56:14.215  1985  1997 D BluetoothHeadset: Proxy object connected
,09-06 16:56:14.216   876   893 D BluetoothHeadset: Proxy object connected
09-06 16:56:14.218  3925  3938 D BluetoothHeadset: Proxy object connected
09-06 16:56:14.220  3925  3925 D HeadsetProfile: Bluetooth service connected
09-06 16:56:14.221   876   893 D BluetoothHeadset: Proxy object connected
,09-06 16:56:14.224  1373  3859 D BluetoothHeadset: Proxy object connected
09-06 16:56:14.224  1373  1373 D HeadsetProfile: Bluetooth service connected
,09-06 16:56:14.532  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:14.532  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:14.532  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:14.532  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:14.532  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:14.532  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:14.532  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:14.532  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:14.544  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:14.548  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:14.548  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3715827 added. We now have 8 listener(s)
09-06 16:56:14.549  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:14.553   876   886 D WifiService: setWifiEnabled: false pid=3860, uid=10000
,09-06 16:56:14.554   876   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 16:56:14.565  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:14.566   876  1384 D WifiService: setWifiEnabled: true pid=3860, uid=10000
,09-06 16:56:14.567   876  1384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 16:56:14.577   876  1317 D WifiConfigStore: Loading config and enabling all networks 
,09-06 16:56:14.593  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:14.593  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:14.593  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:14.593  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:14.593  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:14.593  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:14.593  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:14.593  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:14.598  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:14.598  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:14.598  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:14.598  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:14.598  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:14.598  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:14.598  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:14.598  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:14.599  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:14.601  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:14.605  3860  3908 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 16:56:14.606  3860  3908 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 16:56:14.608  3860  3908 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@84fd94e Bundle[{}]
,09-06 16:56:14.609  3860  3908 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 16:56:14.609  3860  3908 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-06 16:56:14.609  3860  3908 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 16:56:14.610  3860  3908 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 16:56:14.611  3860  3908 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-06 16:56:14.611  3860  3908 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-06 16:56:14.613   876  1317 D WifiConfigStore: loaded 0 passpoint configs
09-06 16:56:14.614   876  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-06 16:56:14.615   876  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 16:56:14.616   876  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 16:56:14.616  3860  3908 I System.out: Running OutgoingSocketThread
09-06 16:56:14.616   876  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-06 16:56:14.616   876  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-06 16:56:14.616   876  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-06 16:56:14.617  3860  4274 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
,09-06 16:56:14.619  3860  4274 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40401
,09-06 16:56:14.619  3860  4274 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 16:56:14.624   374   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 16:56:14.624   876  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.08 rxSuccessRate=0.13 delta 1000 -> 1000
09-06 16:56:14.625   876  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-06 16:56:14.625   374   874 D CommandListener: Setting iface cfg
09-06 16:56:14.626   876  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-06 16:56:14.626   876  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 16:56:14.634   876  1317 E native  : do suspend true
,09-06 16:56:14.645   876  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 16:56:14.645   876  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:56:14.646   876  1316 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 16:56:14.654   876  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 16:56:14.706   876  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 16:56:14.709  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 16:56:14.741   876  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 16:56:15.151  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 16:56:15.198  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 16:56:15.199  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 16:56:15.208   876  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 16:56:15.226   876  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 16:56:15.226   876  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:56:15.227   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 16:56:15.254   876  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 16:56:15.271   374   874 D CommandListener: Setting iface cfg
,09-06 16:56:15.274   876  1317 D WifiStateMachine: Start Dhcp Watchdog 3
,09-06 16:56:15.280   876  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 16:56:15.323   876  4278 D DhcpClient: Receive thread started
,09-06 16:56:15.406   876  1317 E native  : do suspend false
,09-06 16:56:15.426   876  1889 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 16:56:15.448   876  4278 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-06 16:56:15.450   876  1889 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-06 16:56:15.454   876  1889 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 16:56:15.469   876  4278 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 16:56:15.470   876  1889 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 16:56:15.476   374   874 D CommandListener: Setting iface cfg
,09-06 16:56:15.486   876  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 16:56:15.489   876  1317 E native  : do suspend true
,09-06 16:56:15.489   876  1889 D DhcpClient: Scheduling renewal in 86399s
,09-06 16:56:15.505   876  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 16:56:15.506   876  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,09-06 16:56:15.506   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-06 16:56:15.510   876  1319 D ConnectivityService: Adding iface wlan0 to network 102
09-06 16:56:15.515   876  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 16:56:15.558   876  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 16:56:15.559   876  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-06 16:56:15.562   876  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-06 16:56:15.563   876  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-06 16:56:15.564   876  1319 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-06 16:56:15.576   876  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 16:56:15.582   876  1319 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-06 16:56:15.582   876  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-06 16:56:15.583   876  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-06 16:56:15.583   876  1319 D ConnectivityService:    accepting network in place of null
09-06 16:56:15.583   876  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-06 16:56:15.584   876  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 16:56:15.587   876  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 16:56:15.613   876  4277 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155695, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-06 16:56:15.619  3860  3908 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,09-06 16:56:15.619  3860  3908 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,09-06 16:56:15.627  3860  3908 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,09-06 16:56:15.628  3860  3908 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-06 16:56:15.629  3860  3908 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,09-06 16:56:15.633  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 16:56:15.633  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5489ad4 added. We now have 2 listener(s)
,09-06 16:56:15.635  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 16:56:15.635  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 16:56:15.635  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.635  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.635  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30eb47d added. We now have 9 listener(s)
09-06 16:56:15.635  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.636  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 16:56:15.638   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 16:56:15.639  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:56:15.646  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.646  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.646  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:15.646  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.646  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.646  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.646  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.646  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:56:15.649  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.649  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.649  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.650  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e914fc3 added. We now have 3 listener(s)
09-06 16:56:15.652  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.652  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 16:56:15.653  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.653  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.653  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.653  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfe9040 added. We now have 10 listener(s)
09-06 16:56:15.654  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.654  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.654  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.654  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.654  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.654  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.654  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.655  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.655  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5489ad4 removed from the list
09-06 16:56:15.655  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.655  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.655  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30eb47d removed from the list
09-06 16:56:15.655  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.655  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.656  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.656  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.657  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.657  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.657  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.657  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30eb47d not in the list
09-06 16:56:15.657  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.657  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.658  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.658  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.659  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.659  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfe9040 removed from the list
09-06 16:56:15.659  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.659  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.659  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.659  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.659  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e914fc3 removed from the list
09-06 16:56:15.660  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.660  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d71b79 added. We now have 2 listener(s)
09-06 16:56:15.661  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 16:56:15.662  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.662  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.662  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.662  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8bc0be added. We now have 9 listener(s)
09-06 16:56:15.662  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.662  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:56:15.665  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.670  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.670  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.670  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:15.670  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.670  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.670  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.670  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.670  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:56:15.672  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.673  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.673  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.673  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5c706c added. We now have 3 listener(s)
09-06 16:56:15.676  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 16:56:15.676  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 16:56:15.677  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.677  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.681   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-06 16:56:15.681   876  4276 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:816::200e
09-06 16:56:15.682  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.682  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@424f635 added. We now have 10 listener(s)
09-06 16:56:15.682  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.682  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.684   876  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-06 16:56:15.685   876  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:15.683  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.685  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:56:15.686  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:56:15.686  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.686  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:56:15.690   876   893 D Tethering: MasterInitialState.processMessage what=3
09-06 16:56:15.692   876  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-06 16:56:15.705  3860  3908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 16:56:15.705  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:15.705  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.705  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:15.705  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.705  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.705  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.705  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.705  3860  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:56:15.706  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 16:56:15.706  2099  2099 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-06 16:56:15.707  3860  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.708  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 16:56:15.709  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 16:56:15.709  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 16:56:15.710  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.712  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 16:56:15.712  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 16:56:15.712  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 16:56:15.712  3860  3908 D BluetoothAdapter: STATE_ON
09-06 16:56:15.714  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-06 16:56:15.714  4222  4258 D BtGatt.GattService: registerClient() - UUID=b73c8d77-9c20-4261-a8ec-552d2e063f0b
09-06 16:56:15.715  4222  4238 D BtGatt.GattService: onClientRegistered() - UUID=b73c8d77-9c20-4261-a8ec-552d2e063f0b, clientIf=5
09-06 16:56:15.715  3860  3872 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 16:56:15.716  4222  4232 D BtGatt.GattService: start scan with filters
,09-06 16:56:15.719  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 16:56:15.719  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 16:56:15.719  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:56:15.719  4222  4241 D BtGatt.ScanManager: handling starting scan
09-06 16:56:15.719  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 16:56:15.720  4222  4241 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12fcf02
,09-06 16:56:15.721  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:56:15.721  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 16:56:15.722  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 16:56:15.722  4222  4238 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 16:56:15.722  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.722  4222  4241 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 16:56:15.723  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 16:56:15.724  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 16:56:15.724  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.724  4222  4241 D BtGatt.ScanManager: Starting BLE batch scan
09-06 16:56:15.724  4222  4241 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 16:56:15.726  3860  3908 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 16:56:15.726  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.726  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 16:56:15.726  4222  4238 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 16:56:15.726  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.726  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.726  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 16:56:15.726  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:56:15.726  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:56:15.726  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:56:15.726  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 16:56:15.726  1729  1729 D SystemUpdateService: onCreate
09-06 16:56:15.727  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:56:15.727  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 16:56:15.727  3860  3908 D BluetoothAdapter: STATE_ON
09-06 16:56:15.728  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 16:56:15.728  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.728  4222  4232 D BtGatt.GattService: stopScan() - queue size =1
09-06 16:56:15.728  4222  4261 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 16:56:15.728  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:56:15.728  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 16:56:15.729  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 16:56:15.729  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 16:56:15.729  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 16:56:15.730  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:15.730  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 16:56:15.730  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:56:15.730  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 16:56:15.731  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.731  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 16:56:15.731  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.731  4222  4241 D BtGatt.ScanManager: stopping BLe Batch
09-06 16:56:15.731  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 16:56:15.732  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:15.732  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:15.732  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 16:56:15.733  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.733  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.733  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 16:56:15.733  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.734  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.734  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.734  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 16:56:15.734  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d71b79 removed from the list
09-06 16:56:15.734  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.734  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8bc0be removed from the list
09-06 16:56:15.734  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.734  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.734  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 16:56:15.734  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.734  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.734  4222  4241 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-06 16:56:15.734  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.735  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.735  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.735  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:56:15.735  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8bc0be not in the list
09-06 16:56:15.735  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.735  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.736  4222  4238 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-06 16:56:15.736  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:56:15.736  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.736  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.736  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.736  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@424f635 removed from the list
09-06 16:56:15.736  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.736  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.736  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:15.736  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.736  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5c706c removed from the list
09-06 16:56:15.737  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.737  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3bc0b1 added. We now have 2 listener(s)
09-06 16:56:15.738  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 16:56:15.738  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 16:56:15.738  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.738  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.738  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0d2996 added. We now have 9 listener(s)
09-06 16:56:15.738  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.739  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 16:56:15.741  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:56:15.745  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.745  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.745  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:15.745  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.745  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.745  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.745  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.745  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:56:15.747  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.747  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.747  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.747  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f326104 added. We now have 3 listener(s)
,09-06 16:56:15.749  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 16:56:15.749  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.749  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.749  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.749  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1ab6ed added. We now have 10 listener(s)
,09-06 16:56:15.749  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.749  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.749  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:15.750  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.750  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:56:15.750  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:56:15.750  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:56:15.750  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:56:15.752  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:15.753  3860  3908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 16:56:15.753  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 16:56:15.755  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 16:56:15.755  1729  4288 I SystemUpdateService: active receiver: enabled
09-06 16:56:15.756  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 16:56:15.756  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:56:15.758  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 16:56:15.758  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 16:56:15.758  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 16:56:15.758  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-06 16:56:15.758  3860  3908 D BluetoothAdapter: STATE_ON
,09-06 16:56:15.760  4222  4249 D BtGatt.GattService: registerClient() - UUID=ab530cb9-4f3a-470a-b8f6-ca3a77c7ca42
,09-06 16:56:15.760  4222  4238 D BtGatt.GattService: onClientRegistered() - UUID=ab530cb9-4f3a-470a-b8f6-ca3a77c7ca42, clientIf=5
09-06 16:56:15.760  3860  3872 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 16:56:15.761  4222  4258 D BtGatt.GattService: start scan with filters
,09-06 16:56:15.761   876  4276 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 14:56:15 GMT], X-Android-Received-Millis=[1473173775761], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473173775727]}
,09-06 16:56:15.762  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 16:56:15.762  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 16:56:15.762  4222  4241 D BtGatt.ScanManager: handling starting scan
09-06 16:56:15.762  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 16:56:15.762  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 16:56:15.763   876  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 16:56:15.763   876  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-06 16:56:15.764   876  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 16:56:15.764  4222  4238 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 16:56:15.764  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.764  4222  4241 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 16:56:15.765  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:56:15.765  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 16:56:15.765  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.765  4222  4241 D BtGatt.ScanManager: Starting BLE batch scan
09-06 16:56:15.765   876  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 16:56:15.765  4222  4241 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 16:56:15.765  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:56:15.765  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 16:56:15.767  4222  4238 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 16:56:15.767  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.767  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 16:56:15.768  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 16:56:15.768  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.770  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.770  3860  3908 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-06 16:56:15.770  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.770  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.770  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.771  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 16:56:15.771  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:56:15.771  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 16:56:15.771  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.771  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3bc0b1 removed from the list
09-06 16:56:15.771  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.771  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0d2996 removed from the list
09-06 16:56:15.771  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.771  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.771  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.771  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 16:56:15.772  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:56:15.772  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.772  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.773  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.773  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.773  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0d2996 not in the list
09-06 16:56:15.773  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:56:15.773  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 16:56:15.773  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:56:15.773  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:56:15.773  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 16:56:15.774  3860  3908 D BluetoothAdapter: STATE_ON
09-06 16:56:15.774  1729  2413 I iu.UploadsManager: num queued entries: 0
09-06 16:56:15.774  4222  4258 D BtGatt.GattService: stopScan() - queue size =1
09-06 16:56:15.774  4222  4232 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-06 16:56:15.775  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:56:15.775  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 16:56:15.775  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 16:56:15.775  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 16:56:15.775  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.775  4222  4241 D BtGatt.ScanManager: stopping BLe Batch
09-06 16:56:15.775  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 16:56:15.776  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 16:56:15.776  1729  4288 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-06 16:56:15.776  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:15.776  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 16:56:15.776  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:56:15.776  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:56:15.777  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.777  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-06 16:56:15.778  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 16:56:15.778  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:56:15.778  4222  4241 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 16:56:15.778  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:15.778  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:15.779  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:15.779  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.779  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.779  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 16:56:15.779  4222  4238 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-06 16:56:15.779  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.779  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.779  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1ab6ed removed from the list
09-06 16:56:15.779  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 16:56:15.779  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.779  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.779  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.779  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f326104 removed from the list
09-06 16:56:15.780  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.780  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@778d4e9 added. We now have 2 listener(s)
,09-06 16:56:15.780  4019  4019 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:15.781  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 16:56:15.781  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.782  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.782  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.782  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@487d56e added. We now have 9 listener(s)
09-06 16:56:15.782  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:15.782  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:56:15.784  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.788  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.788  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.788  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:15.788  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.788  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.788  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.788  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.788  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:56:15.788  1729  4291 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-06 16:56:15.788  1729  4291 W BaseAppContext: Using Auth Proxy for data requests.
09-06 16:56:15.789  4019  4019 D SprintDMHelper: simOperator: 
09-06 16:56:15.789  4019  4019 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 16:56:15.790  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.790  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.791  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.791  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@192cc9c added. We now have 3 listener(s)
,09-06 16:56:15.792  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.793  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 16:56:15.793  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.793  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.793  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.793  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@280d6a5 added. We now have 10 listener(s)
09-06 16:56:15.793  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.794  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.794  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.794  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 16:56:15.794  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:56:15.794  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.794  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:56:15.796  3860  3908 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 16:56:15.796  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 16:56:15.799  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 16:56:15.800  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 16:56:15.800  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:56:15.802  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 16:56:15.802  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 16:56:15.802  3860  3908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 16:56:15.803  3860  3908 D BluetoothAdapter: STATE_ON
,09-06 16:56:15.804  4222  4233 D BtGatt.GattService: registerClient() - UUID=9e160aa1-bfd8-4b25-8556-3ad24b537cc3
09-06 16:56:15.805  4222  4238 D BtGatt.GattService: onClientRegistered() - UUID=9e160aa1-bfd8-4b25-8556-3ad24b537cc3, clientIf=5
,09-06 16:56:15.805  3860  3871 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 16:56:15.805  4222  4249 D BtGatt.GattService: start scan with filters
,09-06 16:56:15.807  1729  4291 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-06 16:56:15.807  4222  4241 D BtGatt.ScanManager: handling starting scan
09-06 16:56:15.807  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 16:56:15.807  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 16:56:15.807  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:56:15.807  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 16:56:15.808  4222  4238 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 16:56:15.808  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.808  4222  4241 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 16:56:15.809  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 16:56:15.809  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:56:15.810  4222  4241 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 16:56:15.810  4222  4241 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 16:56:15.810  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:56:15.810  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:56:15.810  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 16:56:15.811  4222  4238 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 16:56:15.811  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.812  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 16:56:15.812  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 16:56:15.812  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 16:56:15.816  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.817  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.817  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.817  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.817  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.817  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 16:56:15.817  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 16:56:15.817  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@778d4e9 removed from the list
09-06 16:56:15.817  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.817  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@487d56e removed from the list
09-06 16:56:15.817  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.818  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 16:56:15.818  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.818  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 16:56:15.819  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.819  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.819  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 16:56:15.819  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.819  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 16:56:15.819  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.820  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@487d56e not in the list
,09-06 16:56:15.820  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:56:15.821  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:56:15.821  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:56:15.821  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 16:56:15.821  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:56:15.821  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 16:56:15.821  3860  3908 D BluetoothAdapter: STATE_ON
,09-06 16:56:15.822  4222  4261 D BtGatt.GattService: stopScan() - queue size =1
,09-06 16:56:15.823  4222  4233 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-06 16:56:15.823  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:56:15.823  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 16:56:15.823  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 16:56:15.823  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 16:56:15.823  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 16:56:15.824  1729  2413 I iu.UploadsManager: num updated entries: 0
,09-06 16:56:15.824  4222  4238 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 16:56:15.824  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.824  4222  4241 D BtGatt.ScanManager: stopping BLe Batch
,09-06 16:56:15.824  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:15.824  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 16:56:15.824  3860  3908 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:56:15.824  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:56:15.825  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:15.825  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:15.826  3860  3860 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:15.826  3860  3860 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:15.826  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 16:56:15.826  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.826  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.826  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@280d6a5 removed from the list
,09-06 16:56:15.826  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.826  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.826  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:15.826  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.826  4222  4238 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 16:56:15.826  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@192cc9c removed from the list
09-06 16:56:15.826  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.827  4222  4241 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 16:56:15.827  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.827  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94d3821 added. We now have 2 listener(s)
09-06 16:56:15.828  4222  4238 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-06 16:56:15.828  4222  4238 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 16:56:15.829  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 16:56:15.829  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.829  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.829  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.829  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7812446 added. We now have 9 listener(s)
09-06 16:56:15.829  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.829  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:56:15.831  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:56:15.834  3860  3908 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.834  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.834  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:15.834  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.834  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.834  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.834  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.834  3860  3908 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:56:15.835  1729  4288 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-06 16:56:15.836  1729  4288 I SystemUpdateService: now status is 0 (complete)
09-06 16:56:15.836  1729  4288 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 16:56:15.836  1729  4288 I SystemUpdateService: file has been verified
09-06 16:56:15.837  3860  3908 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:56:15.837  3860  3908 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.837  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.837  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f21334 added. We now have 3 listener(s)
,09-06 16:56:15.839  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:15.839  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 16:56:15.839  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 16:56:15.839  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.839  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.839  1729  2413 I iu.SyncManager: NEXT; no task
09-06 16:56:15.839  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224355d added. We now have 10 listener(s)
09-06 16:56:15.839  3860  3908 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.840  3860  3908 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.840  1729  4288 I SystemUpdateService: OTA package size = 12249756
,09-06 16:56:15.840  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.840  3860  3908 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.840  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.840  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.840  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.840  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.840  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94d3821 removed from the list
09-06 16:56:15.840  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:56:15.840  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7812446 removed from the list
,09-06 16:56:15.841  3860  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:15.841  3860  3908 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.841  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.842  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.842  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.842  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.842  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 16:56:15.842  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.842  3860  3908 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7812446 not in the list
09-06 16:56:15.842  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.843  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.843  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.843  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.843  3860  3908 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.843  3860  3908 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224355d removed from the list
09-06 16:56:15.843  3860  3908 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.843  3860  3908 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.844  3860  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.844  3860  3908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 16:56:15.844  3860  3908 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f21334 removed from the list
09-06 16:56:15.844  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 16:56:15.845  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 16:56:15.845  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 16:56:15.845  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.845  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 16:56:15.845  3860  3908 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:56:15.851  3860  4298 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
,09-06 16:56:15.852  3860  4298 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
09-06 16:56:15.852  3860  4298 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 16:56:15.852  1729  4288 I SystemUpdateService: showing system update notification
,09-06 16:56:15.854  3860  4299 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
,09-06 16:56:15.854  3860  4299 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
,09-06 16:56:15.854  3860  4299 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 16:56:15.855  3860  3908 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-06 16:56:15.855  3860  3908 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 16:56:15.855  3860  3908 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 16:56:15.856  3860  3908 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 16:56:15.856  3860  3908 D com.test.thalitest.ThaliTestRunner: Total duration: 21721 ms
,09-06 16:56:15.857  3860  3908 I jxcore-log: *Native tests were executed*
09-06 16:56:15.857  3860  3908 I jxcore-log: 
,09-06 16:56:15.857  3860  3908 I jxcore-log: Total number of executed tests:  80
09-06 16:56:15.857  3860  3908 I jxcore-log: 
09-06 16:56:15.857  3860  3908 I jxcore-log: Number of passed tests:  80
09-06 16:56:15.857  3860  3908 I jxcore-log: 
09-06 16:56:15.858  3860  3908 I jxcore-log: Number of failed tests:  0
09-06 16:56:15.858  3860  3908 I jxcore-log: 
,09-06 16:56:15.858  3860  3908 I jxcore-log: Number of ignored tests:  0
09-06 16:56:15.858  3860  3908 I jxcore-log: 
09-06 16:56:15.858  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-06 16:56:15.858  3860  3908 I jxcore-log: Total duration:  21721
09-06 16:56:15.858  3860  3908 I jxcore-log: 
09-06 16:56:15.858  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 16:56:15.859  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-06 16:56:15.859  3860  3908 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 16:56:15.859  3860  3908 I jxcore-log: 
09-06 16:56:15.859  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 16:56:15.862  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.862  3860  3908 I jxcore-log: 
09-06 16:56:15.865  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.865  3860  3908 I jxcore-log: 
09-06 16:56:15.866  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.866  3860  3908 I jxcore-log: 
09-06 16:56:15.867  3860  3860 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 16:56:15.867  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.867  3860  3908 I jxcore-log: 
09-06 16:56:15.868  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.868  3860  3908 I jxcore-log: 
09-06 16:56:15.870  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.870  3860  3908 I jxcore-log: 
09-06 16:56:15.872  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.872  3860  3908 I jxcore-log: 
09-06 16:56:15.874  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.874  3860  3908 I jxcore-log: 
09-06 16:56:15.875  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.875  3860  3908 I jxcore-log: 
09-06 16:56:15.875  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 16:56:15.875  3860  3908 I jxcore-log: 
09-06 16:56:15.876  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 16:56:15.876  3860  3908 I jxcore-log: 
,09-06 16:56:15.877  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 16:56:15.877  3860  3908 I jxcore-log: 
,09-06 16:56:15.878  1729  1729 D SystemUpdateService: onDestroy
09-06 16:56:15.878  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.878  3860  3908 I jxcore-log: 
,09-06 16:56:15.879  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.879  3860  3908 I jxcore-log: 
,09-06 16:56:15.880  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.880  3860  3908 I jxcore-log: 
09-06 16:56:15.880  1729  4291 E MDM     : [182] SitrepService.a: Error sending sitrep.
09-06 16:56:15.881  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.881  3860  3908 I jxcore-log: 
09-06 16:56:15.882  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.882  3860  3908 I jxcore-log: 
09-06 16:56:15.882  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.882  3860  3908 I jxcore-log: 
09-06 16:56:15.883  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.883  3860  3908 I jxcore-log: 
09-06 16:56:15.884  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.884  3860  3908 I jxcore-log: 
09-06 16:56:15.885  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.885  3860  3908 I jxcore-log: 
09-06 16:56:15.885  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.885  3860  3908 I jxcore-log: 
09-06 16:56:15.886  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:15.886  3860  3908 I jxcore-log: 
09-06 16:56:15.886  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:15.886  3860  3908 I jxcore-log: 
,09-06 16:56:15.887  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.887  3860  3908 I jxcore-log: 
,09-06 16:56:15.888  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.888  3860  3908 I jxcore-log: 
09-06 16:56:15.888  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.888  3860  3908 I jxcore-log: 
09-06 16:56:15.889  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.889  3860  3908 I jxcore-log: 
09-06 16:56:15.889  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.889  3860  3908 I jxcore-log: 
09-06 16:56:15.890  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.890  3860  3908 I jxcore-log: 
,09-06 16:56:15.918  1908  2653 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-06 16:56:15.970  2302  4294 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 16:56:16.232  3860  3860 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 16:56:16.235  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 16:56:16.235  3860  3908 I jxcore-log: 
,09-06 16:56:16.279  3860  3860 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 16:56:16.282  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 16:56:16.282  3860  3908 I jxcore-log: 
,09-06 16:56:16.326  3860  3860 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 16:56:16.329  3860  3908 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 16:56:16.329  3860  3908 I jxcore-log: 
,09-06 16:56:16.476  4300  4300 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-06 16:56:16.481  4300  4300 D AndroidRuntime: CheckJNI is OFF
,09-06 16:56:16.525  4300  4300 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-06 16:56:16.573  4300  4300 I Radio-JNI: register_android_hardware_Radio DONE
,09-06 16:56:16.597  4300  4300 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 16:56:16.611   876   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-06 16:56:16.611   876   889 I ActivityManager: Killing 3860:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-06 16:56:16.686   876  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-06 16:56:16.703   876  1705 I WindowState: WIN DEATH: Window{451f105 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 16:56:16.703   876  1384 D GraphicsStats: Buffer count: 2
,09-06 16:56:16.706   876  1318 D WifiService: Client connection lost with reason: 4
,09-06 16:56:16.767   876   899 W PackageSettings: Skipping PackageSetting{d67b507 com.example.hello/10273} due to missing metadata
,09-06 16:56:16.791   876   889 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-06 16:56:16.791   876   889 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-06 16:56:16.792   876   889 E ActivityManager: Failure starting process com.test.thalitest
09-06 16:56:16.792   876   889 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231),
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-06 16:56:16.792   876   889 E ActivityManager: 	,at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-06 16:56:16.792   876   889 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.792   876   889 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:16.792   876   889 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:16.792   876   889 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-06 16:56:16.792   876   889 I ActivityManager:   Force finishing activity ActivityRecord{c8a50a2 u0 com.test.thalitest/.MainActivity t2}
09-06 16:56:16.793   876   899 I art     : Starting a blocking GC Explicit
,09-06 16:56:16.803   876  2120 W ActivityManager: Spurious death for ProcessRecord{1e57c90 0:com.test.thalitest/u0a0}, curProc for 3860: null
,09-06 16:56:16.838   876   899 I art     : Explicit concurrent mark sweep GC freed 54700(3MB) AllocSpace objects, 10(296KB) LOS objects, 33% free, 29MB/43MB, paused 774us total 43.450ms
,09-06 16:56:16.871   876   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-06 16:56:16.874  4300  4300 I art     : System.exit called, status: 0
,09-06 16:56:16.874  4300  4300 I AndroidRuntime: VM exiting with result code 0.
,09-06 16:56:16.884   876   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-06 16:56:16.927   876   889 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-06 16:56:16.937  4222  4222 D BluetoothMapAppObserver: onReceive
09-06 16:56:16.937  4222  4222 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-06 16:56:16.938   876  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-06 16:56:16.938  1908  2268 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-06 16:56:16.942  1894  1894 I Keyboard.Facilitator: resetDictionaries() : en_US
09-06 16:56:16.945  3725  3725 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-06 16:56:16.963   876  2119 I ActivityManager: Start proc 4316:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-06 16:56:16.966  1894  4315 I Keyboard.Facilitator.DecoderInitializer: run()
,09-06 16:56:16.979  1894  4315 I Decoder : createOrResetDecoder
,09-06 16:56:16.993  1985  1985 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-06 16:56:17.025  1515  1515 I ConfigService: onCreate
,09-06 16:56:17.028  1515  4328 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-06 16:56:17.028  1515  4328 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-06 16:56:17.028  1515  4328 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-06 16:56:17.030  1515  4328 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-06 16:56:17.034  4316  4316 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-06 16:56:17.039   876  2118 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3860 uid 10000
,09-06 16:56:17.040  1894  1894 I Keyboard.Facilitator: onFinishInput()
,09-06 16:56:17.044  1894  4315 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-06 16:56:17.062   876   876 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 16:56:17.076  2001  2107 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-06 16:56:17.077   876   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-06 16:56:17.077   876   888 E PackageManager: Failed to write settings, restoring backup
09-06 16:56:17.077   876   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-06 16:56:17.077   876   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-06 16:56:17.077   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-06 16:56:17.077   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-06 16:56:17.077   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-06 16:56:17.077   876   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:17.077   876   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.077   876   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 16:56:17.081   876   889 E DropBoxManagerService: Can't write: system_server_wtf
09-06 16:56:17.081   876   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-06 16:56:17.081   876   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 16:56:17.081   876   889 E DropBoxManagerService: 	... 13 more
,09-06 16:56:17.087  1894  4315 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-06 16:56:17.090   876  1991 I ActivityManager: Start proc 4331:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-06 16:56:17.090  2001  2107 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-06 16:56:17.090  2001  2107 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2001
09-06 16:56:17.090  2001  2107 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.090  2001  2107 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:17.093   876  2120 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-06 16:56:17.093   876  4336 E DropBoxManagerService: Can't write: system_app_crash
09-06 16:56:17.093   876  4336 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 16:56:17.093   876  4336 E DropBoxManagerService: 	... 5 more
,09-06 16:56:17.097  2001  2107 I Process : Sending signal. PID: 2001 SIG: 9
,09-06 16:56:17.110  1894  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-06 16:56:17.111  1894  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-06 16:56:17.125  1894  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-06 16:56:17.125  1894  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-06 16:56:17.126  1894  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-06 16:56:17.126  1894  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-06 16:56:17.126  1894  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-06 16:56:17.127  1894  4315 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-06 16:56:17.127  1894  4315 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-06 16:56:17.127  1894  4315 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-06 16:56:17.127  1894  4315 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-06 16:56:17.127  1894  4315 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-06 16:56:17.153  4316  4316 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-06 16:56:17.169   278   278 E lowmemorykiller: Error writing /proc/2001/oom_score_adj; errno=22
,09-06 16:56:17.176  4316  4348 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 16:56:17.190   876  2120 I ActivityManager: Start proc 4350:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-06 16:56:17.190   278   278 E lowmemorykiller: Error writing /proc/2001/oom_score_adj; errno=22
,09-06 16:56:17.201   876  1991 D GraphicsStats: Buffer count: 1
,09-06 16:56:17.201   876  2042 I WindowState: WIN DEATH: Window{bfc1629 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-06 16:56:17.212   876  1991 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2001) has died
,09-06 16:56:17.213   876  1991 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-06 16:56:17.217   876  1991 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-06 16:56:17.222  4316  4348 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.222  4316  4348 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 16:56:17.224  4316  4348 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-06 16:56:17.224  4316  4348 E AndroidRuntime: Process: android.process.acore, PID: 4316
09-06 16:56:17.224  4316  4348 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.224  4316  4348 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 16:56:17.229  4316  4345 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.229  4316  4345 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.229  4316  4345 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 16:56:17.232   876  2121 I ActivityManager: Start proc 4363:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 16:56:17.235   876  4369 E DropBoxManagerService: Can't write: system_app_crash
09-06 16:56:17.235   876  4369 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 16:56:17.235   876  4369 E DropBoxManagerService: 	... 5 more
,09-06 16:56:17.243  4316  4348 I Process : Sending signal. PID: 4316 SIG: 9
,09-06 16:56:17.247  4350  4350 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-06 16:56:17.267  1729  4362 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-06 16:56:17.268  1729  4362 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-06 16:56:17.269  1515  1515 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-06 16:56:17.270  1515  1515 D AndroidRuntime: Shutting down VM
09-06 16:56:17.271  1515  1515 E AndroidRuntime: FATAL EXCEPTION: main
09-06 16:56:17.271  1515  1515 E AndroidRuntime: Process: com.google.process.gapps, PID: 1515
09-06 16:56:17.271  1515  1515 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	,at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-06 16:56:17.271  1515  1515 E AndroidRuntime: 	... 8 more
09-06 16:56:17.273   876  4378 E DropBoxManagerService: Can't write: system_app_crash
09-06 16:56:17.273   876  4378 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 16:56:17.273   876  4378 E DropBoxManagerService: 	... 5 more
09-06 16:56:17.275  1515  1515 I Process : Sending signal. PID: 1515 SIG: 9
,09-06 16:56:17.283  4363  4363 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:56:17.283  4363  4363 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 16:56:17.283  4363  4363 D AndroidRuntime: Shutting down VM
,09-06 16:56:17.291  4363  4363 E AndroidRuntime: FATAL EXCEPTION: main
09-06 16:56:17.291  4363  4363 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4363
09-06 16:56:17.291  4363  4363 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 16:56:17.291  4363  4363 E AndroidRuntime: 	... 10 more
,09-06 16:56:17.293   876   886 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-06 16:56:17.294   876  4380 E DropBoxManagerService: Can't write: system_app_crash
09-06 16:56:17.294   876  4380 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 16:56:17.294   876  4380 E DropBoxManagerService: 	... 5 more
09-06 16:56:17.294  4363  4363 I Process : Sending signal. PID: 4363 SIG: 9
,09-06 16:56:17.305  1729  4362 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-06 16:56:17.306  1729  4362 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-06 16:56:17.315   876  1318 D WifiService: Client connection lost with reason: 4
,09-06 16:56:17.335   876  2042 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4363) has died
,09-06 16:56:17.336   876  2042 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-06 16:56:17.339   876  1705 I ActivityManager: Process com.google.process.gapps (pid 1515) has died
09-06 16:56:17.339   876  1705 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-06 16:56:17.339   876  1705 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-06 16:56:17.339   876  1705 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
09-06 16:56:17.339   876  1705 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
,09-06 16:56:17.341   876  2121 I ActivityManager: Process android.process.acore (pid 4316) has died
,09-06 16:56:17.341   876  2121 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40998ms
,09-06 16:56:17.353   876   889 I ActivityManager: Start proc 4381:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 16:56:17.359  1729  1729 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-06 16:56:17.367   876  2117 I ActivityManager: Start proc 4393:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-06 16:56:17.397  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-06 16:56:17.397  1729  1729 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded

```
