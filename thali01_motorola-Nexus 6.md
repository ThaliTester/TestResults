#### Test 843892648a10bf1_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 01:28:41.615  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:28:41.626  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 01:28:41.628  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 01:28:41.656  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 01:28:41.656  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 01:28:41.656  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 01:28:41.656  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 01:28:41.679  3553  3553 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-08 01:28:41.681  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 01:28:41.681  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-08 01:28:42.271  3837  3837 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 01:28:42.275  3837  3837 D AndroidRuntime: CheckJNI is OFF
09-08 01:28:42.319  3837  3837 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 01:28:42.363  3837  3837 I Radio-JNI: register_android_hardware_Radio DONE
09-08 01:28:42.384  3837  3837 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 01:28:42.391   872  1964 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 01:28:42.438  3837  3837 D AndroidRuntime: Shutting down VM
09-08 01:28:42.446  2027  2043 W SearchService: Abort, client detached.
09-08 01:28:42.452  2027  2027 I HotwordDetector: Closing mic
09-08 01:28:42.453  2027  2340 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9157a5a
09-08 01:28:42.453  2027  2358 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-08 01:28:42.469   872   882 I ActivityManager: Start proc 3846:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 01:28:42.517   375  2366 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-08 01:28:42.518   375  2366 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-08 01:28:42.530   375  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-08 01:28:42.532  2027  2350 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-08 01:28:42.533  2027  2357 I MicroRecognitionRnrImpl: Detection finished
09-08 01:28:42.562  3846  3846 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 01:28:42.590  3846  3846 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 01:28:42.609  3846  3846 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 590-596)
09-08 01:28:42.610  3846  3846 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 01:28:42.633  3846  3846 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8047f9e}
09-08 01:28:42.635  3846  3846 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 01:28:42.637  3846  3846 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 01:28:42.647  3846  3846 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 01:28:42.650  3846  3846 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 01:28:42.672  3846  3846 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 01:28:42.681  3846  3846 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 01:28:42.681  3846  3846 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 01:28:42.682  3846  3846 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 01:28:42.682  3846  3846 I Adreno  : Build Date                       : 10/20/15
09-08 01:28:42.682  3846  3846 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 01:28:42.682  3846  3846 I Adreno  : Local Branch                     : M14
09-08 01:28:42.682  3846  3846 I Adreno  : Remote Branch                    : 
09-08 01:28:42.682  3846  3846 I Adreno  : Remote Branch                    : 
09-08 01:28:42.682  3846  3846 I Adreno  : Reconstruct Branch               : 
,09-08 01:28:42.742   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8cc3c13:true
,09-08 01:28:42.796  3846  3846 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 01:28:42.811  3846  3846 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 01:28:42.891  3846  3885 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 01:28:42.903  3846  3871 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 01:28:42.944  3846  3885 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 01:28:43.036   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +583ms
,09-08 01:28:43.052  1882  1882 I Keyboard.Facilitator: onFinishInput()
,09-08 01:28:43.174  3846  3846 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3846
,09-08 01:28:43.284   872  1385 I ActivityManager: Killing 3084:com.google.android.talk/u0a61 (adj 15): empty #17
,09-08 01:28:43.357   872  1385 I ActivityManager: Killing 2984:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-08 01:28:43.358  3846  3846 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 01:28:43.548  3846  3887 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1715996368
,09-08 01:28:43.564  3846  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 01:28:43.564  3846  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 01:28:43.564  3846  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 01:28:43.564  3846  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 01:28:43.564  3846  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 01:28:43.565  3846  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b8990d added. We now have 1 listener(s)
,09-08 01:28:43.585  3846  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-08 01:28:43.590  3846  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 01:28:43.591  3846  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 01:28:43.591  3846  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 01:28:43.595  3846  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d46ea10 added. We now have 1 listener(s)
09-08 01:28:43.595  3846  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:28:43.601   872  1315 D WifiService: New client listening to asynchronous messages
,09-08 01:28:43.601  3846  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 01:28:43.602  3846  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 01:28:43.603  3846  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-08 01:28:43.603  3846  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 01:28:43.603  3846  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 01:28:43.609  3846  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:28:43.610  3846  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 01:28:43.623  3846  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 01:28:43.623  3846  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:28:43.623  3846  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:28:43.623  3846  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:28:43.623  3846  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:28:43.623  3846  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:28:43.623  3846  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:28:43.623  3846  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:28:43.623  3846  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:28:43.624  3846  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 01:28:43.624  3846  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 01:28:43.625  3846  3887 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 01:28:43.625  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:28:43.627  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:28:43.844  3846  3846 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 01:28:44.299  3846  3856 I art     : Background sticky concurrent mark sweep GC freed 74914(7MB) AllocSpace objects, 17(1308KB) LOS objects, 27% free, 23MB/32MB, paused 797us total 170.231ms
,09-08 01:28:44.759   872  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-08 01:28:45.332  3846  3898 W jxcore-log: Initializing JXcore engine
,09-08 01:28:45.332  3846  3898 W jxcore-log: JXcore engine is ready
,09-08 01:28:45.369  3898  3898 W Thread-331: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-08 01:28:45.369  3898  3898 W Thread-331: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9661]" dev="sockfs" ino=9661 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-08 01:28:45.369  3898  3898 W Thread-331: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-08 01:28:45.369  3898  3898 W Thread-331: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26749]" dev="sockfs" ino=26749 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 01:28:45.383  3846  3898 W jxcore-log: Starting JXcore engine
,09-08 01:28:45.475  3846  3898 W jxcore-log: Platform android
09-08 01:28:45.475  3846  3898 W jxcore-log: 
09-08 01:28:45.475  3846  3898 W jxcore-log: Process ARCH arm
09-08 01:28:45.475  3846  3898 W jxcore-log: 
,09-08 01:28:45.707  3846  3898 I jxcore-log: JXcore Cordova bridge is ready!
09-08 01:28:45.707  3846  3898 I jxcore-log: 
09-08 01:28:45.708  3846  3898 W jxcore-log: JXcore engine is started
,09-08 01:28:45.720  3846  3887 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 01:28:45.725  3846  3846 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 01:28:49.608  3649  3904 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 01:28:49.639  3649  3905 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 01:28:49.660  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:28:49.661  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:28:49.687  1516  2102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 01:28:49.687  1516  2102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 01:28:49.687  1516  2102 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 01:28:49.687  1516  2102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 01:28:49.708  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:28:49.709  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:28:49.724  1516  2324 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 01:28:49.724  1516  2324 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 01:28:49.724  1516  2324 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-08 01:28:49.724  1516  2324 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-08 01:28:49.734  3649  3905 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 01:28:49.735  3649  3904 E BooksSync: Soft error
09-08 01:28:49.735  3649  3904 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 01:28:49.735  3649  3904 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 01:28:49.735  3649  3904 E BooksSync: Sync error
09-08 01:28:49.735  3649  3904 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 01:28:49.735  3649  3904 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 01:28:49.735  3649  3904 I BooksSync: Finished books sync
,09-08 01:28:49.740   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127532, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 01:28:59.133  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 01:28:59.133  3846  3898 I jxcore-log: 
,09-08 01:28:59.136  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 01:28:59.136  3846  3898 I jxcore-log: 
,09-08 01:28:59.160  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:28:59.160  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:28:59.160  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:28:59.160  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:28:59.160  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:28:59.160  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:28:59.160  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:28:59.160  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:28:59.169  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:28:59.177  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 01:28:59.177  3846  3898 I jxcore-log: 
,09-08 01:28:59.185  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 01:28:59.185  3846  3898 I jxcore-log: 
,09-08 01:28:59.587  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 01:28:59.587  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34bfb8c added. We now have 2 listener(s)
09-08 01:28:59.588  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 01:28:59.589  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 01:28:59.589  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 01:28:59.589  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 01:28:59.589  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@846f2d5 added. We now have 2 listener(s)
09-08 01:28:59.589  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:28:59.590  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 01:28:59.603  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:28:59.613  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:28:59.613  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:28:59.613  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:28:59.613  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:28:59.613  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:28:59.613  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:28:59.613  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:28:59.613  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:28:59.618  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:28:59.618  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 01:28:59.620  3846  3898 D ExecuteNativeTests: Running unit tests
,09-08 01:28:59.624  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:28:59.631  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:28:59.684  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 01:28:59.684  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb added. We now have 3 listener(s)
09-08 01:28:59.685  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 01:28:59.689  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 01:28:59.690  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 01:28:59.691  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 01:28:59.691  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 added. We now have 3 listener(s)
09-08 01:28:59.691  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:28:59.693  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 01:28:59.698  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:28:59.710  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:28:59.710  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:28:59.710  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:28:59.710  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:28:59.710  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:28:59.710  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:28:59.710  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:28:59.710  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:28:59.714  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:28:59.714  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 01:28:59.720  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 01:28:59.720  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 01:28:59.720  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 01:28:59.720  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 01:28:59.721  3846  3898 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-08 01:28:59.721  3846  3898 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 01:28:59.722  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 01:28:59.722  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 01:28:59.722  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 01:28:59.722  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 01:28:59.723  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:28:59.723  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:28:59.724  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 01:28:59.724  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:28:59.724  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:28:59.724  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:28:59.724  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 01:28:59.724  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb removed from the list
09-08 01:28:59.724  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:28:59.724  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 removed from the list
,09-08 01:28:59.728  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:28:59.728  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:28:59.728  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:28:59.729  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:28:59.729  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:28:59.735  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 01:28:59.736  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:28:59.736  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:28:59.736  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:28:59.739  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:28:59.742  3846  3898 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-08 01:28:59.748  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:28:59.749  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:28:59.749  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 01:28:59.749  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:28:59.750  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:28:59.750  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:28:59.750  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:28:59.751  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:28:59.751  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:28:59.751  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:28:59.752  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:28:59.752  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:28:59.752  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:28:59.752  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:28:59.754  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:28:59.754  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:28:59.755  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:28:59.755  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:28:59.759  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 01:28:59.760  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 01:28:59.761  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 01:28:59.762  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 01:28:59.762  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 01:28:59.762  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:28:59.762  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:28:59.762  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:28:59.762  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:28:59.762  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:28:59.762  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:28:59.762  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:28:59.762  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:28:59.762  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:28:59.762  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:28:59.762  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:28:59.762  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:28:59.762  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:28:59.763  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:28:59.764  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:28:59.764  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:28:59.764  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:28:59.765  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:28:59.765  3846  3898 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 01:28:59.768  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 01:28:59.776  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:28:59.776  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:28:59.776  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:28:59.776  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:28:59.776  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:28:59.776  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:28:59.776  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:28:59.776  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 01:28:59.779  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 01:28:59.779  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 01:28:59.779  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 01:28:59.779  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 01:28:59.780  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 01:28:59.780  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 01:28:59.780  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 01:28:59.781  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:28:59.783  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:28:59.787  3846  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 01:28:59.787  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 01:28:59.793  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 01:28:59.794  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 01:28:59.795  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 01:28:59.798  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-08 01:28:59.805  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-08 01:28:59.805  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 01:28:59.805  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 01:28:59.806  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 01:28:59.809  3846  3898 D BluetoothAdapter: STATE_ON
09-08 01:28:59.823  2621  2646 D BtGatt.GattService: registerClient() - UUID=d14b83dc-7cf1-4bd8-9038-314313cb3e09
09-08 01:28:59.823  2621  2656 D BtGatt.GattService: onClientRegistered() - UUID=d14b83dc-7cf1-4bd8-9038-314313cb3e09, clientIf=5
09-08 01:28:59.824  3846  3897 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 01:28:59.825  2621  2732 D BtGatt.GattService: start scan with filters
09-08 01:28:59.829  2621  2668 D BtGatt.ScanManager: handling starting scan
09-08 01:28:59.830  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 01:28:59.830  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 01:28:59.830  2621  2668 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
09-08 01:28:59.831  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 01:28:59.831  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 01:28:59.835  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 01:28:59.836  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 01:28:59.836  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 01:28:59.837  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 01:28:59.838  2621  2656 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 01:28:59.838  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:28:59.838  2621  2668 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 01:28:59.840  3846  3898 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 01:28:59.847  2621  2656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 01:28:59.847  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:28:59.847  2621  2668 D BtGatt.ScanManager: Starting BLE batch scan
09-08 01:28:59.848  2621  2668 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 01:28:59.857  2621  2656 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 01:28:59.857  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:28:59.863  2621  2656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 01:28:59.863  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:00.338  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 01:29:00.338  3846  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 01:29:00.339  3846  3846 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 01:29:01.371  2621  2621 D BtGatt.ScanManager: awakened up at time 139358
,09-08 01:29:01.374  2621  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:29:01.406  2621  2656 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 01:29:01.406  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:01.407  2621  2656 D BtGatt.GattService: current time is 139394609207
,09-08 01:29:01.409  2621  2656 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -91, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -96, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -88, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 01:29:01.410  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 01:29:01.411  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 01:29:01.411  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 01:29:01.412  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 01:29:01.412  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 01:29:01.412  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 01:29:02.573   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 01:29:02.930  2621  2621 D BtGatt.ScanManager: awakened up at time 140917
,09-08 01:29:02.963  2621  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:29:02.994  2621  2656 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
09-08 01:29:02.994  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:29:02.995  2621  2656 D BtGatt.GattService: current time is 140982191396
09-08 01:29:02.995  2621  2656 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -85, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -78, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 01:29:02.995  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 01:29:02.995  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 01:29:02.995  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 01:29:02.996  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 01:29:03.091  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:03.100  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:03.102  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:03.132  1516  2409 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 01:29:03.133  1516  2409 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 01:29:03.133  1516  2409 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 01:29:03.133  1516  2409 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 01:29:03.155  3553  3553 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 01:29:03.155  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 01:29:03.156  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-08 01:29:04.500  2621  2621 D BtGatt.ScanManager: awakened up at time 142488
09-08 01:29:04.503  2621  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:29:04.528  2621  2656 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
09-08 01:29:04.529  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:29:04.529  2621  2656 D BtGatt.GattService: current time is 142516509622
09-08 01:29:04.529  2621  2656 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -94, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -78, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
09-08 01:29:04.529  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-08 01:29:04.530  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 01:29:04.530  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 01:29:04.530  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-08 01:29:04.850  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:04.851  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:04.851  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 01:29:04.851  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:04.852  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 01:29:04.852  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 01:29:04.852  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 01:29:04.853  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 01:29:04.853  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 01:29:04.855  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 01:29:04.855  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 01:29:04.857  3846  3898 D BluetoothAdapter: STATE_ON
,09-08 01:29:04.861  2621  2731 D BtGatt.GattService: stopScan() - queue size =1
,09-08 01:29:04.862  2621  2732 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 01:29:04.863  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 01:29:04.863  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 01:29:04.863  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 01:29:04.863  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 01:29:04.864  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 01:29:04.866  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 01:29:04.867  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 01:29:04.867  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 01:29:04.867  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 01:29:04.868  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:29:04.870  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:04.870  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:04.870  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:29:04.871  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:04.871  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:04.871  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:04.871  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:29:04.871  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:04.871  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:04.871  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:29:04.871  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 01:29:04.877  2621  2656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 01:29:04.878  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:29:04.878  2621  2668 D BtGatt.ScanManager: stopping BLe Batch
,09-08 01:29:04.893  2621  2656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 01:29:04.893  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:29:04.894  2621  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:29:04.907  2621  2656 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 01:29:04.907  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:05.373  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 01:29:05.600   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 01:29:09.872  3846  3898 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 01:29:09.879  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:29:09.897  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:29:09.897  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:09.897  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:09.897  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:09.897  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:29:09.897  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:09.897  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:29:09.897  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:29:09.905  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:29:09.906  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 01:29:09.907  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 01:29:09.907  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
,09-08 01:29:09.907  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 01:29:09.908  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:29:09.908  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 01:29:09.915  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:09.919  3846  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 01:29:09.920  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 01:29:09.924  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:09.935  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 01:29:09.938  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
09-08 01:29:09.939  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 01:29:09.953  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 01:29:09.953  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 01:29:09.954  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 01:29:09.956  3846  3898 D BluetoothAdapter: STATE_ON
,09-08 01:29:09.968  2621  2731 D BtGatt.GattService: registerClient() - UUID=37528d17-0909-457b-93fb-e34d566d3cea
,09-08 01:29:09.970  2621  2656 D BtGatt.GattService: onClientRegistered() - UUID=37528d17-0909-457b-93fb-e34d566d3cea, clientIf=5
09-08 01:29:09.971  3846  3858 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 01:29:09.973  2621  2646 D BtGatt.GattService: start scan with filters
,09-08 01:29:09.982  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 01:29:09.982  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 01:29:09.983  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 01:29:09.983  2621  2668 D BtGatt.ScanManager: handling starting scan
09-08 01:29:09.983  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 01:29:10.002  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 01:29:10.002  2621  2656 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 01:29:10.003  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:10.003  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 01:29:10.003  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 01:29:10.003  2621  2668 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 01:29:10.010  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 01:29:10.022  3846  3898 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 01:29:10.026  2621  2656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 01:29:10.026  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:10.027  2621  2668 D BtGatt.ScanManager: Starting BLE batch scan
09-08 01:29:10.027  2621  2668 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 01:29:10.030  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:29:10.030  3846  3898 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 01:29:10.030  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:29:10.030  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 01:29:10.031  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:10.031  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 01:29:10.031  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 01:29:10.031  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 01:29:10.031  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 01:29:10.031  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 01:29:10.031  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 01:29:10.031  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 01:29:10.032  3846  3898 D BluetoothAdapter: STATE_ON
09-08 01:29:10.034  2621  2646 D BtGatt.GattService: stopScan() - queue size =1
09-08 01:29:10.036  2621  2732 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 01:29:10.037  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 01:29:10.037  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 01:29:10.038  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 01:29:10.038  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 01:29:10.038  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 01:29:10.042  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 01:29:10.043  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 01:29:10.043  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 01:29:10.044  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 01:29:10.045  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 01:29:10.049  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 01:29:10.049  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:29:10.049  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 01:29:10.050  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:10.050  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:10.051  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:29:10.051  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:10.051  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:10.051  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:10.052  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:29:10.052  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:10.053  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:10.053  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:10.056  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 01:29:10.056  2621  2656 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 01:29:10.056  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:10.056  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:29:10.056  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:10.057  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:10.059  3846  3898 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 01:29:10.063  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:29:10.068  2621  2656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 01:29:10.068  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:10.076  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:29:10.076  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:10.076  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:10.076  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:10.076  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:29:10.076  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:10.076  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:29:10.076  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:29:10.083  2621  2656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 01:29:10.083  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:10.084  2621  2668 D BtGatt.ScanManager: stopping BLe Batch
,09-08 01:29:10.085  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:29:10.085  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 01:29:10.087  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,09-08 01:29:10.089  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 01:29:10.090  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 01:29:10.090  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:29:10.090  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 01:29:10.091  2621  2656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 01:29:10.091  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:10.091  2621  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:29:10.092  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:10.094  3846  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
09-08 01:29:10.094  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
09-08 01:29:10.098  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:10.098  2621  2656 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
09-08 01:29:10.098  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-08 01:29:10.102  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 01:29:10.103  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 01:29:10.103  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 01:29:10.108  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 01:29:10.108  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 01:29:10.108  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 01:29:10.109  3846  3898 D BluetoothAdapter: STATE_ON
09-08 01:29:10.112  2621  2731 D BtGatt.GattService: registerClient() - UUID=879bc28d-1d1f-4b6a-84a4-9961290c4c06
,09-08 01:29:10.113  2621  2656 D BtGatt.GattService: onClientRegistered() - UUID=879bc28d-1d1f-4b6a-84a4-9961290c4c06, clientIf=5
,09-08 01:29:10.113  3846  3857 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 01:29:10.114  2621  2646 D BtGatt.GattService: start scan with filters
,09-08 01:29:10.118  2621  2668 D BtGatt.ScanManager: handling starting scan
09-08 01:29:10.118  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 01:29:10.119  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 01:29:10.119  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 01:29:10.119  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 01:29:10.123  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 01:29:10.123  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 01:29:10.123  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 01:29:10.126  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 01:29:10.128  2621  2656 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 01:29:10.129  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:29:10.129  2621  2668 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 01:29:10.131  3846  3898 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 01:29:10.138  2621  2656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 01:29:10.138  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:29:10.138  2621  2668 D BtGatt.ScanManager: Starting BLE batch scan
09-08 01:29:10.138  2621  2668 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 01:29:10.160  2621  2656 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 01:29:10.160  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:10.174  2621  2656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 01:29:10.175  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:10.624  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 01:29:10.624  3846  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 01:29:10.625  3846  3846 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 01:29:11.678  2621  2621 D BtGatt.ScanManager: awakened up at time 149666
,09-08 01:29:11.681  2621  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:29:11.730  2621  2656 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 01:29:11.730  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:11.731  2621  2656 D BtGatt.GattService: current time is 149718775079
09-08 01:29:11.732  2621  2656 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -91, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -93, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -81, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 01:29:11.733  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 01:29:11.734  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 01:29:11.734  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 01:29:11.735  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 01:29:11.736  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 01:29:11.737  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 01:29:12.010   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-08 01:29:12.021  1882  1882 I Keyboard.Facilitator: onFinishInput()
,09-08 01:29:12.035   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 01:29:12.035   872   892 I Adreno  : Build Date                       : 10/20/15
09-08 01:29:12.035   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 01:29:12.035   872   892 I Adreno  : Local Branch                     : M14
09-08 01:29:12.035   872   892 I Adreno  : Remote Branch                    : 
09-08 01:29:12.035   872   892 I Adreno  : Remote Branch                    : 
09-08 01:29:12.035   872   892 I Adreno  : Reconstruct Branch               : 
,09-08 01:29:12.057   279   306 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (315 us)
,09-08 01:29:12.678  3846  3846 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 01:29:12.678  3846  3846 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-08 01:29:12.721   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-08 01:29:12.726  3846  3846 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@966c6e4 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@42a7fb5, 16908290=android.view.AbsSavedState$1@42a7fb5}, android:focusedViewId=100}]}]
,09-08 01:29:12.727  3846  3846 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-08 01:29:12.727  3846  3846 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 01:29:12.727  3846  3846 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-08 01:29:12.742   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-08 01:29:12.745   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-08 01:29:12.753   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-08 01:29:12.753   279   279 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-08 01:29:12.997   279   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-08 01:29:13.000   279   279 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-08 01:29:13.001   872  1340 D SurfaceControl: Excessive delay in setPowerMode(): 256ms
,09-08 01:29:13.005   872   892 I DreamManagerService: Entering dreamland.
09-08 01:29:13.006   872   892 I PowerManagerService: Dozing...
,09-08 01:29:13.007   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-08 01:29:13.056   375  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-08 01:29:13.056   375  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-08 01:29:13.061  2621  2621 D BtGatt.ScanManager: awakened up at time 151048
,09-08 01:29:13.062  2621  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:29:13.065   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 01:29:13.075   872  1314 E native  : do suspend false
,09-08 01:29:13.082  1934  3915 D NfcService: Discovery configuration equal, not updating.
,09-08 01:29:13.085  2621  2656 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 01:29:13.085  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:13.085  2621  2656 D BtGatt.GattService: current time is 151072677974
,09-08 01:29:13.085  2621  2656 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -92, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 01:29:13.086  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 01:29:13.086  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 01:29:13.086  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 01:29:13.086  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 01:29:13.086  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 01:29:13.087  2621  2656 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 01:29:13.097   872  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 01:29:13.112   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 01:29:13.115   872  1314 E native  : do suspend true
,09-08 01:29:13.189   375  2047 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-08 01:29:13.190   375  2047 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-08 01:29:13.572   872  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-08 01:29:14.592  2621  2621 D BtGatt.ScanManager: awakened up at time 152579
,09-08 01:29:14.594  2621  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:29:14.604  2621  2656 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 01:29:14.604  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:15.131  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:29:15.132  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:29:15.132  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 01:29:15.133  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:15.133  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 01:29:15.133  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 01:29:15.134  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 01:29:15.134  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 01:29:15.134  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 01:29:15.135  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 01:29:15.135  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 01:29:15.137  3846  3898 D BluetoothAdapter: STATE_ON
09-08 01:29:15.139  2621  2642 D BtGatt.GattService: stopScan() - queue size =1
,09-08 01:29:15.143  2621  2731 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 01:29:15.144  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 01:29:15.144  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 01:29:15.144  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 01:29:15.145  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 01:29:15.145  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 01:29:15.148  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 01:29:15.149  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 01:29:15.149  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 01:29:15.150  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 01:29:15.151  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:29:15.153  2621  2621 D BtGatt.ScanManager: awakened up at time 153140
,09-08 01:29:15.157  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:29:15.158  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:29:15.158  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 01:29:15.170  2621  2656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 01:29:15.170  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:29:15.170  2621  2668 D BtGatt.ScanManager: stopping BLe Batch
,09-08 01:29:15.191  2621  2656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 01:29:15.192  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:29:15.192  2621  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:29:15.214  2621  2656 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 01:29:15.215  2621  2656 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:29:15.660  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 01:29:15.660  3846  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:15.660  3846  3846 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 01:29:19.727  2144  2680 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 01:29:19.947  3071  3920 V KeepSync: Connecting to GoogleApiClient
,09-08 01:29:19.948   872  1700 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 01:29:20.009  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:20.013  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:20.046  1516  2102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 01:29:20.047  1516  2102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 01:29:20.047  1516  2102 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 01:29:20.047  1516  2102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 01:29:20.076  1743  3923 V BaseAuthAsyncOperation: access token request failed
,09-08 01:29:20.079  3071  3920 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 01:29:20.122  1516  2904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 01:29:20.123  1516  2904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 01:29:20.124  1516  2904 I GLSUser : [GLSUser] Extracting token using key: Auth,
,09-08 01:29:20.124  1516  2904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 01:29:20.153  3590  3922 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 01:29:20.153  3590  3922 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at jdm.a(PG:82)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at jcs.o(PG:406)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at jcn.a(PG:1379)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at jcs.i(PG:143)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at blb.a(PG:3937)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at czp.a(PG:18188)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at czp.a(PG:9081)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at czq.run(PG:1686)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 01:29:20.153  3590  3922 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at jdj.a(PG:4091)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at jdj.a(PG:1125)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at jdm.a(PG:77)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	... 12 more
09-08 01:29:20.153  3590  3922 E HttpOperation: Caused by: faj: BadAuthentication
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at fal.a(PG:38)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	at jdj.a(PG:4089)
09-08 01:29:20.153  3590  3922 E HttpOperation: 	... 14 more
,09-08 01:29:20.161  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:29:20.161  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:29:20.162  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 01:29:20.163  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 01:29:20.163  1516  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 01:29:20.163  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:20.164  1516  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 01:29:20.164  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 01:29:20.164  1516  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 01:29:20.164  1516  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
09-08 01:29:20.164  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
,09-08 01:29:20.164  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.165  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list,
,09-08 01:29:20.165  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:29:20.166  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.169  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.169  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.171  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:20.171  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:20.171  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.171  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:20.172  3846  3898 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-08 01:29:20.172  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:20.173  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:20.173  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 01:29:20.173  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.173  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.173  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:20.173  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:20.173  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.173  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.173  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:29:20.173  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.174  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:20.174  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.174  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.175  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:20.175  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:20.175  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.175  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.176  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 01:29:20.176  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:20.176  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:29:20.176  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:29:20.176  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.176  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:20.176  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.177  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:20.177  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.177  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.177  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:20.177  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:20.177  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.177  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.177  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.181  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:20.181  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:20.181  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:20.181  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.182  3846  3898 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 01:29:20.182  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:20.182  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:20.182  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:29:20.182  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.182  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.182  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.182  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:20.182  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.182  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:20.183  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:29:20.183  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.183  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:20.183  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.183  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-08 01:29:20.184  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 01:29:20.184  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:20.184  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:20.184  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:20.185  3846  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-08 01:29:20.185  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:29:20.185  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:29:20.185  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 01:29:20.185  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.185  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.185  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.185  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
,09-08 01:29:20.185  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.185  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.186  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:29:20.186  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:20.186  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:20.186  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:20.186  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:20.187  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 01:29:20.187  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 01:29:20.188  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.188  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:20.188  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 01:29:20.190  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 01:29:20.191  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 01:29:20.191  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 01:29:20.191  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 01:29:20.191  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 01:29:20.191  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 01:29:20.191  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 01:29:20.191  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 01:29:20.191  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:29:20.191  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:29:20.193  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,09-08 01:29:20.198  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.199  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:20.200  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:20.200  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
,09-08 01:29:20.200  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:20.200  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:20.200  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:20.200  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:20.200  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:20.200  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.200  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.201  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:20.201  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 01:29:20.201  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:20.201  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.205  3846  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 01:29:20.205  3846  3898 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-08 01:29:20.205  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 01:29:20.209  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 01:29:20.209  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 01:29:20.209  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 01:29:20.209  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 01:29:20.217  3846  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 01:29:20.217  3846  3898 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 01:29:20.217  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 01:29:20.217  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 01:29:20.217  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 01:29:20.217  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 01:29:20.217  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 01:29:20.217  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 01:29:20.217  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-08 01:29:20.217  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 01:29:20.218  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 01:29:20.219  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 01:29:20.219  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 01:29:20.219  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 01:29:20.219  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 01:29:20.219  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 01:29:20.219  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 01:29:20.219  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 01:29:20.219  3846  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 01:29:20.219  3846  3898 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 01:29:20.219  3846  3898 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 01:29:20.220  3846  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 01:29:20.220  3846  3898 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 01:29:20.220  3846  3898 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-08 01:29:20.220  3846  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 01:29:20.220  3846  3898 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 01:29:20.221  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 01:29:20.222  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-08 01:29:20.223  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-08 01:29:20.223  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 01:29:20.224  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 01:29:20.224  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 01:29:20.224  3846  3898 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-08 01:29:20.224  3846  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 01:29:20.224  3590  3922 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 01:29:20.224  3590  3922 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at jdm.a(PG:82)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at jcs.o(PG:406)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at jcn.a(PG:1379)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at jcs.i(PG:143)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at hec.a(PG:42)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at hee.a(PG:102)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at czr.a(PG:65)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at kka.a(PG:108)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at czp.a(PG:19176)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at czp.a(PG:9081)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at czq.run(PG:1686)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 01:29:20.224  3590  3922 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at jdj.a(PG:4091)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at jdj.a(PG:1125)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at jdm.a(PG:77)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	... 15 more
09-08 01:29:20.224  3590  3922 E HttpOperation: Caused by: faj: BadAuthentication
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at fal.a(PG:38)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	at jdj.a(PG:4089)
09-08 01:29:20.224  3590  3922 E HttpOperation: 	... 17 more
09-08 01:29:20.224  3846  3898 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 01:29:20.225  3590  3922 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 01:29:20.225  3590  3922 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at hec.a(PG:42)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at hee.a(PG:102)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at czr.a(PG:65)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at kka.a(PG:108)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 01:29:20.225  3590  3922 E Expe,rimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	... 15 more
09-08 01:29:20.225  3590  3922 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at fal.a(PG:38)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 01:29:20.225  3590  3922 E ExperimentLoader: 	... 17 more
09-08 01:29:20.225  3846  3925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 395)
09-08 01:29:20.225  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:20.225  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:20.225  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:29:20.226  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.226  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.226  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.226  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 01:29:20.227  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:20.227  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.227  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.227  3846  3925 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 01:29:20.227  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:20.227  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.227  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.227  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.227  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.228  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:20.229  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:20.229  3846  3926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 395
09-08 01:29:20.229  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.229  3846  3926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 395)
09-08 01:29:20.229  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in ,the list
09-08 01:29:20.229  3846  3926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 395)
09-08 01:29:20.229  3846  3898 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 01:29:20.230  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:20.230  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:20.230  3846  3925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 395)
09-08 01:29:20.231  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:29:20.231  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.231  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.231  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.231  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:20.231  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.231  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.231  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:20.231  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.231  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.232  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.232  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.233  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:20.233  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:20.234  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.234  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.235  3846  3898 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 01:29:20.235  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:20.235  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:20.235  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:29:20.235  3071  3920 E KeepSync: IOException
09-08 01:29:20.235  3071  3920 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 01:29:20.235  3071  3920 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 01:29:20.235  3071  3920 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 01:29:20.235  3071  3920 E KeepSync: 	... 10 more
09-08 01:29:20.235  3071  3920 W KeepSync: Sync result 2
09-08 01:29:20.235  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.236  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.236  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.236  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:20.236  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.236  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.236  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:20.236  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.236  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.236  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.236  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.238  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:20.238  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:20.238  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.238  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.239  3846  3898 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 01:29:20.239  3846  3898 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 01:29:20.239  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 01:29:20.240  3846  3898 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 01:29:20.240  3846  3898 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 01:29:20.240  3846  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 01:29:20.240  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 01:29:20.240  3846  3898 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 01:29:20.240  3846  3898 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 01:29:20.240  3846  3898 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 01:29:20.241  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 01:29:20.241  3846  3898 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 01:29:20.241  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:20.241  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:20.241  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:29:20.241  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.242  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.242  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.242  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:20.242  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.242  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.242  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:20.242  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.242  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.242   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129911, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
09-08 01:29:20.242  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.242  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.243  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:20.243  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:20.243  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.244  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.244  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:20.245  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.245  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:20.245  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:20.245  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:20.245  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:20.245  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:20.245  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:20.245  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:20.303   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129959, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-08 01:29:23.311  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:23.460  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:23.467  1516  3928 I VacuumService: Vacuum at: now=1473290963467 tag=VacuumService
,09-08 01:29:23.506  1516  2324 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 01:29:23.506  1516  2324 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 01:29:23.506  1516  2324 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 01:29:23.507  1516  2324 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 01:29:23.536  3553  3553 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 01:29:23.537  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 01:29:23.537  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-08 01:29:23.565  1516  3929 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-08 01:29:23.567  1516  3929 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 01:29:23.602  1516  3929 W Uploader:  no longer exists, so no auth token.
,09-08 01:29:24.775   872  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-08 01:29:25.246  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:25.247  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:25.247  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:25.248  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.248  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.248  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
,09-08 01:29:25.249  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:25.249  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:25.250  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:29:25.251  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:25.251  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.251  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.252  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:25.252  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:25.252  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:25.252  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:25.253  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.253  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.253  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.254  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.257  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:25.258  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:25.258  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:25.258  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:25.263  3846  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 01:29:25.265  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:29:25.267  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 01:29:25.270  3846  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 01:29:25.271  3846  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 01:29:25.271  3846  3846 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 01:29:25.271  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 01:29:25.272  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 01:29:25.273  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:25.273  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-08 01:29:25.273  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 01:29:25.273  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 01:29:25.274  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.274  3846  3936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 01:29:25.274  3846  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 01:29:25.274  3846  3846 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 01:29:25.274  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:25.275  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:25.275  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 01:29:25.275  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 01:29:25.275  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 01:29:25.276  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.277  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:25.279  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 01:29:25.280  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 01:29:25.279  3846  3936 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 01:29:25.280  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 01:29:25.280  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:25.280  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-08 01:29:25.280  3846  3936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-08 01:29:25.280  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:25.280  3846  3936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 01:29:25.280  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:29:25.280  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 01:29:25.281  3846  3846 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 01:29:25.281  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 01:29:25.281  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:25.281  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:25.282  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list,
,09-08 01:29:25.282  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:25.282  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:25.283  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:25.283  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:25.283  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.283  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.283  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.286  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:25.286  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:25.287  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:25.287  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:25.290  3846  3898 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 01:29:25.290  3846  3898 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 01:29:25.290  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 01:29:25.290  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 01:29:25.290  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 01:29:25.291  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:29:25.291  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:25.291  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 01:29:25.291  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:25.291  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.291  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:25.291  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:25.291  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:25.291  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:25.291  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:25.291  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.292  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:25.292  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:25.292  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:25.294  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 01:29:25.294  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 01:29:25.294  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:25.295  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:25.303  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,09-08 01:29:25.303  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:25.303  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-08 01:29:25.304  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 01:29:25.304  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.304  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:25.305  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:25.305  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-08 01:29:25.305  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:25.305  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:29:25.305  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.306  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.306  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.306  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.308  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:29:25.308  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:25.309  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:25.309  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:25.311  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:29:25.312  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:29:25.312  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 01:29:25.312  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:29:25.313  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:25.313  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.313  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8e7cb not in the list
09-08 01:29:25.314  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:25.314  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
09-08 01:29:25.314  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:25.314  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:25.315  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:25.315  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:25.315  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:25.317  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 01:29:25.317  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:29:25.318  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:25.318  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8cbba8 not in the list
,09-08 01:29:25.320  3846  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-08 01:29:25.320  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 01:29:25.321  3846  3898 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 01:29:25.321  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 01:29:25.321  3846  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 01:29:25.321  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 01:29:25.327  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 01:29:25.327  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-08 01:29:25.328  3846  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-08 01:29:25.329  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 01:29:25.329  3846  3898 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 01:29:25.329  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 01:29:25.329  3846  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 01:29:25.330  3846  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-08 01:29:25.331  3846  3898 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-08 01:29:25.331  3846  3898 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 01:29:25.332  3846  3898 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-08 01:29:25.333  3846  3898 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 01:29:25.333  3846  3898 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 01:29:25.333  3846  3898 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-08 01:29:25.335  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 01:29:25.335  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4a759bb added. We now have 3 listener(s)
09-08 01:29:25.336  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:29:25.339  3846  3898 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 01:29:25.340   872  1963 D WifiService: setWifiEnabled: true pid=3846, uid=10000
09-08 01:29:25.340   872  1963 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 01:29:25.356  2621  2724 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 01:29:25.356  2621  2727 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-08 01:29:25.780  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 01:29:28.663   872  1861 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 01:29:29.843  1516  3929 I art     : Waiting for a blocking GC DisableMovingGc
,09-08 01:29:29.849  1516  3929 I art     : WaitForGcToComplete blocked for 6.150ms for cause DisableMovingGc
09-08 01:29:29.849  1516  3929 I art     : Starting a blocking GC DisableMovingGc
,09-08 01:29:30.169  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:30.172  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:30.200  1516  3929 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 01:29:30.201  1516  3929 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-08 01:29:30.201  1516  3929 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 01:29:30.201  1516  3929 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 01:29:30.220  1516  3929 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 01:29:30.220  1516  3929 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 01:29:30.220  1516  3929 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 01:29:30.348  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 01:29:30.349  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a3a5ed8 added. We now have 4 listener(s)
09-08 01:29:30.349  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:29:30.365  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:30.366  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a3a5ed8 removed from the list
09-08 01:29:30.366  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:30.366  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:30.366  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:30.368  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 01:29:30.369  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d06231 added. We now have 4 listener(s)
,09-08 01:29:30.369  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 01:29:30.371  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:30.372  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d06231 removed from the list
09-08 01:29:30.372  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:29:30.372  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:30.372  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:29:30.374  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 01:29:30.374  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@78aed16 added. We now have 4 listener(s)
09-08 01:29:30.375  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:29:30.379   872  3161 D WifiService: setWifiEnabled: false pid=3846, uid=10000
,09-08 01:29:30.379   872  3161 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 01:29:30.389  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:29:30.392  2621  2650 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 01:29:30.393  2621  2650 D BluetoothAdapterProperties: Setting state to 13
,09-08 01:29:30.393  2621  2650 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 01:29:30.394  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:30.394  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:29:30.394  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.394  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.394  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:30.394  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:29:30.394  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:30.394  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:29:30.394  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:29:30.394  2621  2650 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 01:29:30.395  2621  2650 I BluetoothAdapterState: Entering PendingCommandState
09-08 01:29:30.396  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.396  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:29:30.397  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 01:29:30.400  2621  2621 D BluetoothMapService: onReceive
09-08 01:29:30.400  2621  2621 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 01:29:30.404  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.404  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:30.404  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.404  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.404  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:30.404  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:30.404  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:30.404  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:29:30.404  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:29:30.405  2621  2621 D BluetoothMapService: STATE_TURNING_OFF
,09-08 01:29:30.407  2621  2621 D BluetoothMapService: MAP Service closeService in
09-08 01:29:30.407  2621  2621 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 01:29:30.407  2621  2621 D ObexServerSockets0: shutdown(block = true)
,09-08 01:29:30.408  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:30.408  2621  2621 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 01:29:30.408  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:30.408  2621  2743 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 01:29:30.409  2621  2742 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 01:29:30.412  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 01:29:30.415   872  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 01:29:30.415   872  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 01:29:30.415   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 01:29:30.415   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 01:29:30.416  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:30.419  2621  2727 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-08 01:29:30.420  2621  2621 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 01:29:30.421  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:30.421  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:30.421  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.421  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.421  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:30.421  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:30.421  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:30.421  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:29:30.421  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 01:29:30.422  2621  2621 I BtOppRfcommListener: stopping Accept Thread
,09-08 01:29:30.423  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:30.423  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:29:30.423  2621  3458 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-08 01:29:30.424  2621  3458 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 01:29:30.427  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-08 01:29:30.427  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:30.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:30.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:30.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:30.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:29:30.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:29:30.427  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.428  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:29:30.430   872  1314 E native  : do suspend true
,09-08 01:29:30.431  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:30.439   872   885 I ActivityManager: Start proc 3946:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-08 01:29:30.440   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-08 01:29:30.440   872  1862 D DhcpClient: Clearing IP address
09-08 01:29:30.441  2621  2656 D BluetoothAdapterProperties: Scan Mode:20
09-08 01:29:30.442  2621  2650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 01:29:30.444  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:30.445   371   870 D CommandListener: Setting iface cfg
09-08 01:29:30.446  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:30.446  2621  2621 D HeadsetService: Received stop request...Stopping profile...
09-08 01:29:30.446   872  1878 D DhcpClient: Receive thread stopped
09-08 01:29:30.447  1372  1384 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:30.447   872   872 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:30.447   872   872 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:30.448   872   872 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:30.448  1947  2207 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:30.448  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:30.449  1372  1372 D HeadsetProfile: Bluetooth service disconnected
09-08 01:29:30.450  2621  2621 V BluetoothAdapterState: isTurningOff()=true
09-08 01:29:30.450  2621  2621 V BluetoothAdapterState: isTurningOn()=false
09-08 01:29:30.450  2621  2621 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:30.450  2621  2621 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:30.452  2621  2621 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 01:29:30.452  2621  2621 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 01:29:30.452  2621  2656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 01:29:30.452  2621  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:30.452  2621  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:30.452  2621  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:30.452  2621  2656 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 01:29:30.452  2621  2621 D A2dpService: Received stop request...Stopping profile...
09-08 01:29:30.453  2621  2736 D A2dpStateMachine: Exit Disconnected: -1
09-08 01:29:30.453   872  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 01:29:30.454   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 01:29:30.454   872  1314 E native  : do suspend true
09-08 01:29:30.454   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 01:29:30.454   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 01:29:30.455  1516  2157 V NativeCrypto: Read error: ssl=0xaee76c00: I/O error during system call, Connection timed out
09-08 01:29:30.457   872   872 D BluetoothA2dp: Proxy object disconnected
09-08 01:29:30.458  2621  2621 D HidService: Received stop request...Stopping profile...
09-08 01:29:30.458  2621  2621 D HidService: Stopping Bluetooth HidService
09-08 01:29:30.458  1372  1372 D BluetoothA2dp: Proxy object disconnected
09-08 01:29:30.458  1372  1372 D BluetoothInputDevice: Proxy object disconnected
09-08 01:29:30.458  1372  1372 D HidProfile: Bluetooth service disconnected
09-08 01:29:30.459  2621  2621 D HealthService: Received stop request...Stopping profile...,
09-08 01:29:30.460   872  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 01:29:30.461   397   397 E Parcel  : Reading a NULL string not supported here.
09-08 01:29:30.462  2621  2621 D PanService: Received stop request...Stopping profile...
09-08 01:29:30.463  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 01:29:30.464  1372  1372 D PanProfile: Bluetooth service disconnected
09-08 01:29:30.466  2621  2621 D BluetoothMapService: Received stop request...Stopping profile...
09-08 01:29:30.466  2621  2621 D BluetoothMapService: stop()
09-08 01:29:30.467  2621  2621 D BluetoothMapAppObserver: deinitObservers()
09-08 01:29:30.467  2621  2621 D BluetoothMapAppObserver: removeReceiver()
09-08 01:29:30.468  1372  1372 D BluetoothMap: Proxy object disconnected
09-08 01:29:30.468  1372  1372 D MapProfile: Bluetooth service disconnected
09-08 01:29:30.469  2621  2621 V BluetoothAdapterState: isTurningOff()=true
09-08 01:29:30.469  2621  2621 V BluetoothAdapterState: isTurningOn()=false
09-08 01:29:30.469  2621  2621 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:30.469  2621  2621 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:30.470  2621  2621 V BluetoothAdapterState: isTurningOff()=true
09-08 01:29:30.470  2621  2621 V BluetoothAdapterState: isTurningOn()=false
09-08 01:29:30.470  2621  2621 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:30.470  2621  2621 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:30.471  2621  2621 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 01:29:30.471  2621  2621 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 01:29:30.471  2621  2621 V BluetoothAdapterState: isTurningOff()=true
09-08 01:29:30.471  2621  2621 V BluetoothAdapterState: isTurningOn()=false
09-08 01:29:30.471  2621  2621 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:30.471  2621  2621 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:30.471  2621  2621 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 01:29:30.471  2621  2656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 01:29:30.471  2621  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:30.471  2621  2656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 01:29:30.472  2621  2656 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 01:29:30.472  2621  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:30.472  2621  2724 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 01:29:30.472  2621  2724 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 01:29:30.472  2621  2724 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 01:29:30.472  2621  2724 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 01:29:30.472  2621  2621 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 01:29:30.472  2621  2621 V BluetoothAdapterState: isTurningOff()=true
09-08 01:29:30.472  2621  2621 V BluetoothAdapterState: isTurningOn()=false
09-08 01:29:30.472  2621  2621 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:30.472  2621  2621 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:30.473  2621  2621 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 01:29:30.473  2621  2621 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 01:29:30.474  2621  2621 D BluetoothMapService: MAP Service closeService in
09-08 01:29:30.474  2621  2621 V BluetoothAdapterState: isTurningOff()=true
09-08 01:29:30.474  2621  2621 V BluetoothAdapterState: isTurningOn()=false,
09-08 01:29:30.474  2621  2621 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:30.474  2621  2621 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:30.475  2621  2650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 01:29:30.475  2621  2650 D BluetoothAdapterProperties: Setting state to 15
09-08 01:29:30.475  2621  2650 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-08 01:29:30.475  1516  2157 V NativeCrypto: SSL shutdown failed: ssl=0xaee76c00: I/O error during system call, Broken pipe
09-08 01:29:30.475   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 01:29:30.475   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 01:29:30.476  2621  2650 I BluetoothAdapterState: Entering BleOnState
09-08 01:29:30.476  1372  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 01:29:30.475  2621  2621 D BluetoothMapService: cleanup()
09-08 01:29:30.476  2621  2621 D BluetoothMapService: MAP Service closeService in
09-08 01:29:30.477   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 01:29:30.477  1372  1666 D BluetoothPan: onBluetoothStateChange on: false
,09-08 01:29:30.477   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 01:29:30.477  1372  2069 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 01:29:30.479  1372  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 01:29:30.481  1372  1384 D BluetoothMap: onBluetoothStateChange: up=false
09-08 01:29:30.482  1947  1961 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 01:29:30.482  1372  1666 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 01:29:30.482  2621  2650 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-08 01:29:30.482  2621  2650 D BluetoothAdapterProperties: Setting state to 16
09-08 01:29:30.482  2621  2650 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 01:29:30.483  2621  2650 D BluetoothAdapterProperties: onBleDisable
09-08 01:29:30.483  2621  2650 I BluetoothAdapterState: Entering PendingCommandState
09-08 01:29:30.483  2621  2652 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 01:29:30.484  2621  2656 D BluetoothAdapterProperties: Scan Mode:20
09-08 01:29:30.485  2621  2724 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-08 01:29:30.485  2621  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:30.485  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.485  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:30.485  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.485  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.485  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:30.485  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:30.485  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
09-08 01:29:30.485  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:30.485  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:30.486  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.486  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:30.488  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.488  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-08 01:29:30.488  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.488  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.488  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:30.488  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:30.488  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:30.488  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:30.488  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:30.488  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:30.489  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:30.490  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.490  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:30.490  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.490  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.490  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:30.490  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:30.490  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:30.490  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-08 01:29:30.490  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:30.491  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.491  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:30.492  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:30.493  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:30.493  1516  3929 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.209.74 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
09-08 01:29:30.494  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:30.509   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 01:29:30.526  3946  3946 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-08 01:29:30.526   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 01:29:30.528   872  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 01:29:30.528   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 01:29:30.529   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-08 01:29:30.531   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 01:29:30.531   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-08 01:29:30.536  3446  3446 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@24950c2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-08 01:29:30.536  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:30.539  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-08 01:29:30.540  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:30.543  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:30.550   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 01:29:30.553  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:30.553   872  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 01:29:30.553  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:30.553  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.553  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.553  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:30.553  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:30.553  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:30.553  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:30.553  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 01:29:30.553  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:30.553  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 01:29:30.554  2144  2312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 01:29:30.555  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:30.555  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:30.555  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.555  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.555  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:30.555  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:30.555  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:30.555  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:30.555  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 01:29:30.556  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.557  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:30.558  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.558  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:30.558  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:30.558  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:30.558  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:30.558  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:30.558  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:30.558  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:30.558  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:30.559  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:30.559  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 01:29:30.577  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 01:29:30.581  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 01:29:30.584   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15b44f2:true
,09-08 01:29:30.587   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-08 01:29:30.595   872  3122 I ActivityManager: Start proc 3966:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-08 01:29:30.606  3946  3946 D LocalBluetoothProfileManager: Adding local MAP profile
,09-08 01:29:30.609  3946  3946 D BluetoothMap: Create BluetoothMap proxy object
,09-08 01:29:30.621  3946  3946 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 01:29:30.629  3966  3966 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 01:29:30.639  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-08 01:29:30.645   872  1964 I ActivityManager: Killing 3304:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,09-08 01:29:30.689  2621  2656 I bt_hci  : shut_down
,09-08 01:29:30.695  2621  2670 D bt_hwcfg: hw_epilog_process
09-08 01:29:30.695  2621  2670 I bt_vendor: low_power_mode_cb
,09-08 01:29:30.720  2621  2670 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-08 01:29:30.720  2621  2670 I bt_vendor: epilog_cb
09-08 01:29:30.720  2621  2670 I bt_hci  : epilog_finished_callback
,09-08 01:29:30.722  2621  2656 I bt_hci_h4: hal_close
,09-08 01:29:30.722  2621  2656 I bt_userial_vendor: device fd = 51 close
,09-08 01:29:30.840  2621  2652 D bt_stack_manager: event_shut_down_stack finished.
,09-08 01:29:30.841  2621  2650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 01:29:30.846  2621  2621 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 01:29:30.846  2621  2650 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 01:29:30.847  2621  2621 D BtGatt.GattService: Received stop request...Stopping profile...
,09-08 01:29:30.847  2621  2621 D BtGatt.GattService: stop()
09-08 01:29:30.847  2621  2621 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 01:29:30.850  2621  2621 V BluetoothAdapterState: isTurningOff()=false
,09-08 01:29:30.850  2621  2621 V BluetoothAdapterState: isTurningOn()=false
,09-08 01:29:30.851  2621  2621 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:30.851  2621  2621 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 01:29:30.851  2621  2650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 01:29:30.852  2621  2650 D BluetoothAdapterProperties: Setting state to 10
,09-08 01:29:30.852  2621  2650 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 01:29:30.853  2621  2650 I BluetoothAdapterState: Entering OffState
09-08 01:29:30.855   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 01:29:30.870  2621  2621 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 01:29:30.871  2621  2621 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 01:29:30.871  2621  2621 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 01:29:30.871  2621  2652 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 01:29:30.874  2621  2652 D bt_stack_manager: event_clean_up_stack finished.
,09-08 01:29:30.881  3966  3966 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 01:29:30.881  3966  3966 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 01:29:30.881  3966  3966 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 01:29:30.881  3966  3966 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 01:29:30.881  3966  3966 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 01:29:30.881  3966  3966 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:29:30.881  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 01:29:30.882  3966  3966 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 01:29:30.8,82  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 01:29:30.882  3966  3966 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:29:30.882  3966  3966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 01:29:30.886  2621  2621 I art     : System.exit called, status: 0
,09-08 01:29:30.886  2621  2621 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-08 01:29:30.889  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 01:29:30.916  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-08 01:29:30.920   872  1385 I ActivityManager: Killing 3446:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 01:29:30.997   872   883 I ActivityManager: Process com.android.bluetooth (pid 2621) has died
,09-08 01:29:31.006  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 01:29:31.033   872  1963 I ActivityManager: Start proc 3999:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-08 01:29:31.095  3999  3999 D AdapterServiceConfig: Adding HeadsetService
,09-08 01:29:31.095  3999  3999 D AdapterServiceConfig: Adding A2dpService
09-08 01:29:31.095  3999  3999 D AdapterServiceConfig: Adding HidService
,09-08 01:29:31.095  3999  3999 D AdapterServiceConfig: Adding HealthService
09-08 01:29:31.097  3999  3999 D AdapterServiceConfig: Adding PanService
,09-08 01:29:31.097  3999  3999 D AdapterServiceConfig: Adding GattService
,09-08 01:29:31.097  3999  3999 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 01:29:31.131   872  1385 I ActivityManager: Start proc 4012:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-08 01:29:31.133   872  1385 I ActivityManager: Killing 3609:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-08 01:29:31.162  3966  3983 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 01:29:31.200   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e082452:true
,09-08 01:29:31.232  4012  4012 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-08 01:29:31.413  4012  4030 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-08 01:29:31.413  4012  4030 I Babel_SMS: MmsConfig.loadMmsSettings
,09-08 01:29:31.417  4012  4030 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-08 01:29:31.417  4012  4030 I Babel_SMS: MmsConfig.loadFromDatabase
,09-08 01:29:31.452  4012  4030 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-08 01:29:31.452  4012  4030 I Babel_SMS: MmsConfig.loadFromResources
09-08 01:29:31.457  4012  4030 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-08 01:29:31.458  4012  4030 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-08 01:29:31.486  4012  4012 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 01:29:31.489  4012  4012 I Babel_Crash: startup - clean
,09-08 01:29:31.517  4012  4012 I Babel_telephony: TeleModule.launchCompleted
,09-08 01:29:31.523   872  1964 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-08 01:29:31.528  4012  4012 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-08 01:29:31.535  4012  4012 W Babel   : BAM#gBA: invalid account id: -1
,09-08 01:29:31.535  4012  4012 W Babel   : BAM#gBA: invalid account id: -1
,09-08 01:29:31.535  4012  4012 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-08 01:29:31.544  4012  4035 I Babel   : deleted: false for 0
,09-08 01:29:31.555   872   882 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-08 01:29:31.571  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 01:29:31.575  1743  1743 D SystemUpdateService: onCreate
,09-08 01:29:31.584  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 01:29:31.607  1743  4037 I SystemUpdateService: active receiver: enabled
,09-08 01:29:31.631  1743  4037 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 01:29:31.634  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 01:29:31.638  1743  2437 I iu.UploadsManager: num queued entries: 0
,09-08 01:29:31.645  1743  4037 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-08 01:29:31.645  1743  4037 I SystemUpdateService: now status is 0 (complete)
,09-08 01:29:31.643  1743  2437 I iu.UploadsManager: num updated entries: 0
09-08 01:29:31.648  1743  2437 I iu.SyncManager: NEXT; no task
09-08 01:29:31.646  1743  4037 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 01:29:31.648  1743  4037 I SystemUpdateService: file has been verified
09-08 01:29:31.648  1743  4037 I SystemUpdateService: OTA package size = 12249756
,09-08 01:29:31.653  1743  4037 I SystemUpdateService: showing system update notification
,09-08 01:29:31.660  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 01:29:31.661  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 01:29:31.682  4012  4012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 01:29:31.683   872  1963 I ActivityManager: Start proc 4039:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 01:29:31.686  1743  1743 D SystemUpdateService: onDestroy
,09-08 01:29:31.723  4039  4039 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 01:29:31.729  4039  4039 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 01:29:31.755  4039  4039 D SprintDMHelper: simOperator: 
,09-08 01:29:31.755  4039  4039 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 01:29:31.770  4012  4012 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 01:29:31.782  4012  4012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 01:29:31.785  4012  4012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 01:29:31.792  4012  4012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 01:29:31.794   872  1965 I ActivityManager: Start proc 4051:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-08 01:29:31.804  4012  4012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 01:29:31.809   872  1992 I ActivityManager: Killing 3499:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 01:29:31.871  4012  4012 I vclib   : onServiceConnected
,09-08 01:29:31.968   872  1965 I ActivityManager: Start proc 4066:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 01:29:31.974  4012  4065 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 01:29:31.979   872  1385 I ActivityManager: Killing 3536:android.process.acore/u0a5 (adj 15): empty #17
,09-08 01:29:32.044  4066  4066 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 01:29:32.104  4066  4066 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 01:29:32.104  4066  4066 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 01:29:32.104  4066  4066 I GAv4    :   adb logcat -s GAv4
,09-08 01:29:32.124  4066  4066 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 01:29:32.132  4066  4066 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 01:29:32.159  4066  4083 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 01:29:32.274  4066  4066 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 01:29:32.318  4066  4066 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 01:29:32.328  4066  4066 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 311-315)
,09-08 01:29:32.329  4066  4066 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 01:29:32.341  4066  4066 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a9b6e72}
,09-08 01:29:32.341  4066  4066 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 01:29:32.342  4066  4066 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 01:29:32.351  4066  4066 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 01:29:32.353  4066  4066 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 01:29:32.375  4066  4066 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 01:29:32.391  4066  4066 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 01:29:32.391  4066  4066 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 01:29:32.391  4066  4066 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 01:29:32.391  4066  4066 I Adreno  : Build Date                       : 10/20/15
09-08 01:29:32.391  4066  4066 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 01:29:32.391  4066  4066 I Adreno  : Local Branch                     : M14
09-08 01:29:32.391  4066  4066 I Adreno  : Remote Branch                    : 
09-08 01:29:32.391  4066  4066 I Adreno  : Remote Branch                    : 
09-08 01:29:32.391  4066  4066 I Adreno  : Reconstruct Branch               : 
,09-08 01:29:32.462  4066  4066 I NSApplication: Starting up...
,09-08 01:29:32.468  4066  4112 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 01:29:32.501   872  1963 I ActivityManager: Start proc 4117:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 01:29:32.503   872  1963 I ActivityManager: Killing 3726:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 01:29:32.585  4117  4117 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 01:29:32.803   872  1965 I ActivityManager: Killing 3741:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 01:29:32.869   872  1700 I ActivityManager: Start proc 4131:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 01:29:32.917  4131  4131 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 01:29:32.967  4131  4131 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 01:29:32.988   872  3122 I ActivityManager: Killing 2239:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 01:29:35.402   872  1992 D WifiService: setWifiEnabled: true pid=3846, uid=10000
,09-08 01:29:35.403   872  1992 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 01:29:35.419   872  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-08 01:29:35.426  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:35.427  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:35.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:35.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:35.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:35.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:35.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:35.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:35.427  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:35.427  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:35.427  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 01:29:35.430  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:35.430  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:35.430  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:35.430  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:35.430  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:35.430  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:35.430  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:35.430  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:35.430  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:35.430  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:35.430  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:35.433  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:35.433  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:35.433  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:35.433  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:35.433  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:35.433  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:35.433  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:35.433  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:35.433  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 01:29:35.433  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:35.434  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 01:29:35.452   872  1314 D WifiConfigStore: loaded 0 passpoint configs
,09-08 01:29:35.453   872  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 01:29:35.454   872  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 01:29:35.455   872  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 01:29:35.456   872  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 01:29:35.456   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 01:29:35.456   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 01:29:35.472   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 01:29:35.472   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 01:29:35.474   371   870 D CommandListener: Setting iface cfg
,09-08 01:29:35.482   872  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 01:29:35.482   872  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 01:29:35.484   872  1314 E native  : do suspend true
,09-08 01:29:35.496   872  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 01:29:35.497   872  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 01:29:35.499   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 01:29:36.321   872  1700 I ActivityManager: Killing 3765:com.google.android.apps.docs/u0a46 (adj 15): empty #17,
,09-08 01:29:36.797   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 01:29:36.829   872  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.81 rxSuccessRate=9.19 delta 1000 -> 994
,09-08 01:29:36.831   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 01:29:36.831   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 01:29:36.844   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 01:29:36.880   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 01:29:36.886  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 01:29:37.310  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 01:29:37.374  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 01:29:37.375  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 01:29:37.383   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 01:29:37.398   872  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 01:29:37.398   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 01:29:37.399   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 01:29:37.419   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 01:29:37.439   371   870 D CommandListener: Setting iface cfg
,09-08 01:29:37.441   872  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 01:29:37.451   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 01:29:37.480   872  4166 D DhcpClient: Receive thread started
,09-08 01:29:37.567   872  1314 E native  : do suspend false
,09-08 01:29:37.588   872  1862 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 01:29:37.601   872  4166 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172647, domain null
,09-08 01:29:37.602   872  1862 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172647 seconds
,09-08 01:29:37.605   872  1862 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 01:29:37.622   872  4166 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 01:29:37.623   872  1862 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 01:29:37.628   371   870 D CommandListener: Setting iface cfg
,09-08 01:29:37.633   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 01:29:37.639   872  1314 E native  : do suspend true
,09-08 01:29:37.640   872  1862 D DhcpClient: Scheduling renewal in 86399s
,09-08 01:29:37.651   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 01:29:37.652   872  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 01:29:37.653   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 01:29:37.657   872  1316 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 01:29:37.658   872  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 01:29:37.701   872  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 01:29:37.701   872  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 01:29:37.703   872  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 01:29:37.705   872  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 01:29:37.707   872  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1],
,09-08 01:29:37.724   872  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 01:29:37.732   872  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 01:29:37.732   872  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-08 01:29:37.732   872  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 01:29:37.732   872  1316 D ConnectivityService:    accepting network in place of null
,09-08 01:29:37.732   872  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 01:29:37.733   872  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 01:29:37.735   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 01:29:37.754   872  4165 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175741, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 01:29:37.763   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 01:29:37.816   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 01:29:37.824   872  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 01:29:37.824   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 01:29:37.828   872  4164 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-08 01:29:37.832   872  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 01:29:37.836   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-08 01:29:37.843  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:37.843  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:37.843  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:37.843  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:37.843  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:37.843  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:37.843  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:37.843  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:29:37.843  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 01:29:37.843  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:37.844  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:29:37.847  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:37.847  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:37.847  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:37.847  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:37.847  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:37.847  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:37.847  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:37.847  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:29:37.847  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:29:37.847  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:37.847  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:37.850  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:37.850  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:37.850  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:37.850  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:37.850  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:29:37.850  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:37.850  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:37.850  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:29:37.850  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:29:37.850  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:37.851  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 01:29:37.859  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-08 01:29:37.863  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 01:29:37.866  1743  1743 D SystemUpdateService: onCreate
,09-08 01:29:37.869  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 01:29:37.886  1743  4175 I SystemUpdateService: active receiver: enabled
,09-08 01:29:37.887   872  4164 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 23:29:37 GMT], X-Android-Received-Millis=[1473290977887], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473290977864]}
,09-08 01:29:37.888   872  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 01:29:37.888   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-08 01:29:37.889   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 01:29:37.890   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 01:29:37.892  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 01:29:37.895  1743  2437 I iu.UploadsManager: num queued entries: 0
,09-08 01:29:37.895  1743  2437 I iu.UploadsManager: num updated entries: 0
,09-08 01:29:37.906  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 01:29:37.907  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 01:29:37.909  4039  4039 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 01:29:37.914  1743  4177 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 01:29:37.914  1743  4177 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 01:29:37.916  1743  4177 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 01:29:37.917  4039  4039 D SprintDMHelper: simOperator: 
09-08 01:29:37.918  4039  4039 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 01:29:37.928  1743  4175 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 01:29:37.934  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:37.935  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:37.961  1743  2437 I iu.SyncManager: NEXT; no task
,09-08 01:29:37.965  1743  4175 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 01:29:37.965  1743  4175 I SystemUpdateService: now status is 0 (complete)
,09-08 01:29:37.965  1743  4175 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 01:29:37.966  1743  4175 I SystemUpdateService: file has been verified
,09-08 01:29:37.972  1743  4175 I SystemUpdateService: OTA package size = 12249756
,09-08 01:29:37.993  1743  4175 I SystemUpdateService: showing system update notification
,09-08 01:29:38.046  1743  1743 D SystemUpdateService: onDestroy
,09-08 01:29:38.059  1516  2102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 01:29:38.059  1516  2102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 01:29:38.059  1516  2102 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 01:29:38.059  1516  2102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 01:29:38.068  4012  4181 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 01:29:38.079  1743  4177 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-08 01:29:38.259  1743  1743 I GCM     : Message from null null
,09-08 01:29:38.260  1743  1743 E GCM     : Dropping message from null
,09-08 01:29:38.824   872  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 01:29:40.412   872   882 D WifiService: setWifiEnabled: false pid=3846, uid=10000
,09-08 01:29:40.413   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 01:29:40.450  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 01:29:40.457   872  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 01:29:40.457   872  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 01:29:40.457   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 01:29:40.458   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 01:29:40.484   872  1314 E native  : do suspend true
,09-08 01:29:40.497   872  1862 D DhcpClient: Clearing IP address
,09-08 01:29:40.497   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-08 01:29:40.500   371   870 D CommandListener: Setting iface cfg
,09-08 01:29:40.502   872  4166 D DhcpClient: Receive thread stopped
,09-08 01:29:40.505  1516  4186 V NativeCrypto: Read error: ssl=0x9b09be00: I/O error during system call, Connection timed out
,09-08 01:29:40.509  1516  4186 V NativeCrypto: SSL shutdown failed: ssl=0x9b09be00: I/O error during system call, Broken pipe
,09-08 01:29:40.516   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 01:29:40.517   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-08 01:29:40.519   872  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
09-08 01:29:40.524   397   397 E Parcel  : Reading a NULL string not supported here.
09-08 01:29:40.528   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 01:29:40.528   872  1314 E native  : do suspend true
,09-08 01:29:40.540   872  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 01:29:40.541   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-08 01:29:40.543   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 01:29:40.562   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 01:29:40.565  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:40.565  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:40.565  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:40.565  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:40.565  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:40.565  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:40.565  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:40.565  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:40.565  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:40.566  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:40.566  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:40.567  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:40.567  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:40.567  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:40.567  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:40.567  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:40.567  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:40.567  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:40.567  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:40.567  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:40.567  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:40.567  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:40.568   872  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 01:29:40.568  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:40.568  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-08 01:29:40.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:40.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:40.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:40.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:40.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:40.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:40.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:40.568  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:40.568  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
09-08 01:29:40.568  2144  2312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 01:29:40.582   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0,
,09-08 01:29:40.614   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 01:29:40.615   872  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 01:29:40.615   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 01:29:40.620   872   889 D Tethering: MasterInitialState.processMessage what=3
09-08 01:29:40.621  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:40.622  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:40.623  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:40.630  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-08 01:29:40.634  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 01:29:40.637  1743  1743 D SystemUpdateService: onCreate
,09-08 01:29:40.642  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 01:29:40.652  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 01:29:40.655  1743  2437 I iu.UploadsManager: num queued entries: 0
,09-08 01:29:40.678  1743  4197 I SystemUpdateService: active receiver: enabled
,09-08 01:29:40.681  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 01:29:40.682  1743  4197 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 01:29:40.683  1743  2437 I iu.UploadsManager: num updated entries: 0
,09-08 01:29:40.688  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 01:29:40.690  1743  4197 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 01:29:40.691  1743  4197 I SystemUpdateService: now status is 0 (complete)
,09-08 01:29:40.691  1743  4197 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 01:29:40.691  1743  4197 I SystemUpdateService: file has been verified
,09-08 01:29:40.691  1743  4197 I SystemUpdateService: OTA package size = 12249756
09-08 01:29:40.692  4039  4039 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 01:29:40.702  4039  4039 D SprintDMHelper: simOperator: 
09-08 01:29:40.702  4039  4039 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 01:29:40.719  4012  4201 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 01:29:40.683  1743  2437 I iu.SyncManager: NEXT; no task
,09-08 01:29:40.736  1743  4197 I SystemUpdateService: showing system update notification
,09-08 01:29:40.741   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-08 01:29:40.743   872  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 01:29:40.764  1743  1743 D SystemUpdateService: onDestroy
,09-08 01:29:45.454   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5747c96:true
,09-08 01:29:45.457  3999  3999 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 01:29:45.465  3999  4204 I BluetoothAdapterState: Entering OffState
,09-08 01:29:45.465  3999  3999 I bt_bluedroid: init
,09-08 01:29:45.470  3999  4205 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 01:29:45.470  3999  4205 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 01:29:45.471  3999  4205 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 01:29:45.471  3999  4205 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 01:29:45.474  3999  3999 I bt_bluedroid: get_profile_interface socket
,09-08 01:29:45.479  3999  4208 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 01:29:45.480  3999  3999 I bt_bluedroid: get_profile_interface sdp
,09-08 01:29:45.482  3999  4208 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 01:29:45.488  3999  4010 I bt_bluedroid: config_hci_snoop_log
,09-08 01:29:45.495   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 01:29:45.502  3999  4204 D BluetoothAdapterState: Current state: OFF, message: 0
09-08 01:29:45.503  3999  4204 D BluetoothAdapterProperties: Setting state to 14
,09-08 01:29:45.503  3999  4204 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-08 01:29:45.505  3999  4204 D BluetoothBondStateMachine: make
,09-08 01:29:45.513  3999  4209 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 01:29:45.515  3999  4204 I BluetoothAdapterState: Entering PendingCommandState
,09-08 01:29:45.517  3999  3999 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 01:29:45.520  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:29:45.521  3999  3999 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 01:29:45.522  3999  3999 D BtGatt.GattService: Received start request. Starting profile...
,09-08 01:29:45.522  3999  3999 D BtGatt.GattService: start()
,09-08 01:29:45.522  3999  3999 I bt_bluedroid: get_profile_interface gatt
,09-08 01:29:45.523  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
09-08 01:29:45.523  3999  3999 D BtGatt.AdvertiseManager: advertise manager created
,09-08 01:29:45.533  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,09-08 01:29:45.533  3999  3999 V BluetoothAdapterState: isTurningOn()=false
,09-08 01:29:45.533  3999  3999 V BluetoothAdapterState: isBleTurningOn()=true
,09-08 01:29:45.533  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 01:29:45.534  3999  4204 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 01:29:45.534  3999  4204 I bt_bluedroid: enable
,09-08 01:29:45.535  3999  4205 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 01:29:45.535  3999  4205 I bt_hci  : start_up
,09-08 01:29:45.545  3999  4205 I bt_vendor: alloc value 0xb3a29189
,09-08 01:29:45.545  3999  4205 I bt_vendor: init
,09-08 01:29:45.545  3999  4205 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-08 01:29:45.545  3999  4205 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found,
,09-08 01:29:45.652  3999  4205 D bt_hci  : start_up starting async portion
,09-08 01:29:45.653  3999  4212 I bt_hci  : event_finish_startup,
,09-08 01:29:45.653  3999  4212 I bt_hci_h4: hal_open
,09-08 01:29:45.653  3999  4212 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0,
,09-08 01:29:45.666  3999  4212 I bt_userial_vendor: device fd = 51 open
,09-08 01:29:45.693  3999  4212 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 01:29:45.725  3999  4212 D bt_hwcfg: Chipset BCM4354A2
,09-08 01:29:45.725  3999  4212 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 01:29:45.726  3999  4212 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 01:29:45.738   872  1316 D ConnectivityService: handlePromptUnvalidated 101
,09-08 01:29:46.384  3999  4212 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 01:29:46.386  3999  4212 D bt_hwcfg: Settlement delay -- 100 ms
09-08 01:29:46.386  3999  4212 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 01:29:46.503  3999  4212 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 01:29:46.504  3999  4212 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 01:29:46.533  3999  4212 I bt_hwcfg: vendor lib fwcfg completed
,09-08 01:29:46.534  3999  4212 I bt_vendor: firmware callback
09-08 01:29:46.534  3999  4212 I bt_hci  : firmware_config_callback
,09-08 01:29:46.546  3999  4214 I bt_btu  : btu_task pending for preload complete event
,09-08 01:29:46.546  3999  4214 I bt_btu_task: Bluetooth chip preload is complete
,09-08 01:29:46.546  3999  4214 I bt_btu  : btu_task received preload complete event
,09-08 01:29:46.557  3999  4214 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 01:29:46.557  3999  4214 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 01:29:46.557  3999  4214 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-08 01:29:46.558  3999  4214 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 01:29:46.558  3999  4214 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 01:29:46.558  3999  4214 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 01:29:46.558  3999  4214 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 01:29:46.559  3999  4214 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 01:29:46.559  3999  4214 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 01:29:46.559  3999  4214 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 01:29:46.559  3999  4214 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 01:29:46.560  3999  4214 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 01:29:46.560  3999  4214 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 01:29:46.560  3999  4214 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 01:29:46.560  3999  4214 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 01:29:46.693  3999  4214 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a6d9d
,09-08 01:29:46.694  3999  4214 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a6d9d 
,09-08 01:29:46.716  3999  4208 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 01:29:46.718  3999  4208 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 01:29:46.719  3999  4208 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 01:29:46.723  3999  4208 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 01:29:46.726  3999  4208 D BluetoothAdapterProperties: Scan Mode:20
,09-08 01:29:46.726  3999  4208 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 01:29:46.727  3999  4208 D bt_hci  : do_postload posting postload work item
,09-08 01:29:46.727  3999  4212 I bt_hci  : event_postload
,09-08 01:29:46.727  3999  4212 I bt_vendor: sco_config_cb
09-08 01:29:46.728  3999  4212 I bt_hci  : sco_config_callback postload finished.
,09-08 01:29:46.730  3999  4208 D bt_bte_conf: Device ID record 1 : primary
,09-08 01:29:46.731  3999  4208 D bt_bte_conf:   vendorId            = 000f
09-08 01:29:46.731  3999  4208 D bt_bte_conf:   vendorIdSource      = 0001
09-08 01:29:46.731  3999  4208 D bt_bte_conf:   product             = 1200
09-08 01:29:46.731  3999  4208 D bt_bte_conf:   version             = 1436
09-08 01:29:46.731  3999  4208 D bt_bte_conf:   clientExecutableURL = 
09-08 01:29:46.731  3999  4208 D bt_bte_conf:   serviceDescription  = 
,09-08 01:29:46.732  3999  4208 D bt_bte_conf:   documentationURL    = 
09-08 01:29:46.732  3999  4208 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 01:29:46.733  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:46.732  3999  4205 D bt_stack_manager: event_start_up_stack finished
09-08 01:29:46.735  3999  4204 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 01:29:46.735  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:46.736  3999  4204 D BluetoothAdapterProperties: Setting state to 15
09-08 01:29:46.736  3999  4204 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 01:29:46.738  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:46.738  3999  4204 I BluetoothAdapterState: Entering BleOnState
09-08 01:29:46.740  3999  4212 I bt_vendor: low_power_mode_cb
,09-08 01:29:46.742  3999  4204 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 01:29:46.742  3999  4204 D BluetoothAdapterProperties: Setting state to 11
09-08 01:29:46.743  3999  4204 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 01:29:46.750  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:29:46.751  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:46.752  3999  3999 D HeadsetService: Received start request. Starting profile...
09-08 01:29:46.752  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:46.755  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:46.755  3999  3999 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 01:29:46.755  3999  3999 D HeadsetStateMachine: make
,09-08 01:29:46.769  3999  4204 I BluetoothAdapterState: Entering PendingCommandState
,09-08 01:29:46.774  3999  3999 D HeadsetStateMachine: max_hf_connections = 1
09-08 01:29:46.774  3999  3999 I bt_bluedroid: get_profile_interface handsfree
,09-08 01:29:46.774  3999  4208 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-08 01:29:46.776  3999  4208 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-08 01:29:46.777  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:29:46.778  3999  3999 D A2dpService: Received start request. Starting profile...
,09-08 01:29:46.778  3999  3999 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 01:29:46.779  3999  3999 I bt_bluedroid: get_profile_interface avrcp
,09-08 01:29:46.785  3999  3999 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 01:29:46.785  3999  3999 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-08 01:29:46.785  3999  3999 D A2dpStateMachine: make
,09-08 01:29:46.786  3999  3999 I bt_bluedroid: get_profile_interface a2dp
,09-08 01:29:46.787  3999  4208 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 01:29:46.789  3999  4223 D A2dpStateMachine: Enter Disconnected: -2
,09-08 01:29:46.792  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 01:29:46.792  3999  3999 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 01:29:46.793  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:29:46.794  3999  3999 D HidService: Received start request. Starting profile...,
09-08 01:29:46.795  3999  3999 I bt_bluedroid: get_profile_interface hidhost
09-08 01:29:46.795  3999  4208 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39883e5
,09-08 01:29:46.795  3999  4208 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 01:29:46.795  3999  3999 D HidService: setHidService(): set to: null
,09-08 01:29:46.795  3946  3946 D BluetoothInputDevice: Proxy object connected
09-08 01:29:46.795  3999  3999 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 01:29:46.796  3946  3946 D HidProfile: Bluetooth service connected
09-08 01:29:46.796  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
09-08 01:29:46.797  3999  3999 D HealthService: Received start request. Starting profile...
,09-08 01:29:46.798  3999  3999 I bt_bluedroid: get_profile_interface health
,09-08 01:29:46.799  3999  3999 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 01:29:46.800  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:29:46.801  3999  3999 D PanService: Received start request. Starting profile...
,09-08 01:29:46.801  3999  3999 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 01:29:46.801  3999  3999 I bt_bluedroid: get_profile_interface pan
,09-08 01:29:46.802  3946  3946 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 01:29:46.802  3999  4208 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 01:29:46.802  3946  3946 D PanProfile: Bluetooth service connected
,09-08 01:29:46.804  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:29:46.805  3999  3999 D BluetoothMapService: Received start request. Starting profile...,
,09-08 01:29:46.806  3999  3999 D BluetoothMapService: start()
09-08 01:29:46.806  3946  3946 D BluetoothMap: Proxy object connected
,09-08 01:29:46.806  3946  3946 D MapProfile: Bluetooth service connected
,09-08 01:29:46.807  3946  3946 D BluetoothMap: getConnectedDevices()
09-08 01:29:46.807  3946  3946 D BluetoothMap: Bluetooth is Not enabled,
09-08 01:29:46.808  3999  3999 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 01:29:46.808  3999  3999 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 01:29:46.808  3999  3999 D BluetoothMapAppObserver: createReceiver()
09-08 01:29:46.811  3999  3999 D BluetoothMapAppObserver: initObservers()
09-08 01:29:46.811  3999  3999 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 01:29:46.818  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,09-08 01:29:46.818  3999  3999 V BluetoothAdapterState: isTurningOn()=true
09-08 01:29:46.818  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:46.818  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 01:29:46.820  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,09-08 01:29:46.820  3999  3999 V BluetoothAdapterState: isTurningOn()=true
09-08 01:29:46.820  3999  4221 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 01:29:46.820  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:46.820  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 01:29:46.822  3999  3999 V BluetoothAdapterState: isTurningOff()=false
09-08 01:29:46.822  3999  3999 V BluetoothAdapterState: isTurningOn()=true
09-08 01:29:46.822  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:46.822  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:46.822  3999  3999 V BluetoothAdapterState: isTurningOff()=false
09-08 01:29:46.822  3999  3999 V BluetoothAdapterState: isTurningOn()=true
09-08 01:29:46.822  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:46.823  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:46.823  3999  3999 V BluetoothAdapterState: isTurningOff()=false
09-08 01:29:46.823  3999  3999 V BluetoothAdapterState: isTurningOn()=true
09-08 01:29:46.823  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:46.823  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:46.823  3999  3999 V BluetoothAdapterState: isTurningOff()=false
09-08 01:29:46.823  3999  3999 V BluetoothAdapterState: isTurningOn()=true
09-08 01:29:46.823  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:46.823  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:46.824  3999  4204 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 01:29:46.824  3999  4204 D BluetoothAdapterProperties: ScanMode =  20
09-08 01:29:46.824  3999  4204 D BluetoothAdapterProperties: State =  11
09-08 01:29:46.824  3999  4204 D BluetoothAdapterProperties: Setting state to 12
09-08 01:29:46.824  3999  4204 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 01:29:46.825   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 01:29:46.825   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 01:29:46.825  1372  1666 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 01:29:46.825  3999  4208 D BluetoothAdapterProperties: Scan Mode:21
09-08 01:29:46.826  3999  4208 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 01:29:46.826  3999  4204 I BluetoothAdapterState: Entering OnState
09-08 01:29:46.827  1372  1372 D BluetoothInputDevice: Proxy object connected
09-08 01:29:46.827  1372  1372 D HidProfile: Bluetooth service connected
09-08 01:29:46.827   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 01:29:46.828  1372  1384 D BluetoothPan: onBluetoothStateChange on: true
09-08 01:29:46.829  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 01:29:46.829  1372  1372 D PanProfile: Bluetooth service connected
09-08 01:29:46.829  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:46.829  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:46.829  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:46.829  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:46.829  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:29:46.829  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:46.829  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:46.829  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:46.829   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 01:29:46.829  1372  2069 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 01:29:46.830   872   872 D BluetoothA2dp: Proxy object connected
09-08 01:29:46.830  3946  3958 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 01:29:46.831  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:46.831  1372  1666 D BluetoothA2dp: onBluetoothStateChange: u,p=true
09-08 01:29:46.833  1372  1372 D BluetoothA2dp: Proxy object connected
09-08 01:29:46.833  1372  1384 D BluetoothMap: onBluetoothStateChange: up=true
09-08 01:29:46.834  1947  3527 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 01:29:46.835  3946  3956 D BluetoothMap: onBluetoothStateChange: up=true
09-08 01:29:46.835  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:46.835  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:46.835  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:46.835  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:46.835  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:29:46.835  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:46.835  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:46.835  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:46.835  1372  1372 D BluetoothMap: Proxy object connected
09-08 01:29:46.835  3946  3958 D BluetoothPan: onBluetoothStateChange on: true
09-08 01:29:46.835  1372  1372 D MapProfile: Bluetooth service connected
09-08 01:29:46.835  1372  1372 D BluetoothMap: getConnectedDevices()
09-08 01:29:46.835  3946  3956 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 01:29:46.835  1372  1383 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 01:29:46.837   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 01:29:46.838  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:46.838  3999  3999 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 01:29:46.839  3999  3999 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 01:29:46.840  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:46.840  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:46.840  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:46.840  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:46.840  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:29:46.840  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:46.840  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:46.840  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:46.841  3999  3999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 01:29:46.842  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:46.843  3946  3946 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 01:29:46.843  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:46.844  3999  3999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 01:29:46.844  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:46.845  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:46.845  3999  3999 D ObexServerSockets: Succeed to create listening sockets 
09-08 01:29:46.845  3999  3999 D ObexServerSockets0: startAccept()
09-08 01:29:46.845  3999  3999 D ObexServerSockets0: prepareForNewConnect()
,09-08 01:29:46.848  3946  3946 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 01:29:46.849  3999  4230 D ObexServerSockets0: Accepting socket connection...
09-08 01:29:46.849  3999  3999 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 01:29:46.849  3999  3999 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 01:29:46.849  3999  4231 D ObexServerSockets0: Accepting socket connection...
09-08 01:29:46.850  3999  3999 D BluetoothMapService: onReceive
09-08 01:29:46.850  3999  3999 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 01:29:46.850  3999  3999 D BluetoothMapService: STATE_ON
,09-08 01:29:46.852  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 01:29:46.854  3946  3946 D BluetoothA2dp: Proxy object connected
,09-08 01:29:46.856  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 01:29:46.860  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-08 01:29:46.864  1372  1372 D BluetoothPbap: Proxy object connected
,09-08 01:29:46.864  1372  1372 D PbapServerProfile: Bluetooth service connected
09-08 01:29:46.865  3946  3946 D BluetoothPbap: Proxy object connected
09-08 01:29:46.865  3946  3946 D PbapServerProfile: Bluetooth service connected
,09-08 01:29:46.872  3999  4235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 01:29:46.880  3999  3999 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 01:29:46.880  3999  3999 D ObexServerSockets0: prepareForNewConnect()
,09-08 01:29:46.883  3999  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 01:29:46.884  3999  4239 I BtOppRfcommListener: Accept thread started.
,09-08 01:29:46.927  1372  1383 D BluetoothHeadset: Proxy object connected
,09-08 01:29:46.928  1372  1372 D HeadsetProfile: Bluetooth service connected
09-08 01:29:46.928   872   872 D BluetoothHeadset: Proxy object connected
,09-08 01:29:46.928   872   872 D BluetoothHeadset: Proxy object connected
09-08 01:29:46.928   872   872 D BluetoothHeadset: Proxy object connected
,09-08 01:29:46.929   872   889 D BluetoothHeadset: Proxy object connected
09-08 01:29:46.929  1947  2207 D BluetoothHeadset: Proxy object connected
,09-08 01:29:46.936  1947  2137 D BluetoothHeadset: Proxy object connected
,09-08 01:29:46.936  1372  1666 D BluetoothHeadset: Proxy object connected
,09-08 01:29:46.936  1372  1372 D HeadsetProfile: Bluetooth service connected
,09-08 01:29:46.949  3946  3956 D BluetoothHeadset: Proxy object connected
,09-08 01:29:46.950  3946  3946 D HeadsetProfile: Bluetooth service connected
,09-08 01:29:48.585  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:48.601  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:48.608  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:29:48.668  1516  2904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 01:29:48.668  1516  2904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 01:29:48.668  1516  2904 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 01:29:48.669  1516  2904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 01:29:48.711  3553  3553 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 01:29:48.712  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 01:29:48.712  3553  3553 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-08 01:29:50.436  3999  4204 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 01:29:50.436  3999  4204 D BluetoothAdapterProperties: Setting state to 13
09-08 01:29:50.437  3999  4204 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 01:29:50.438  3999  4204 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 01:29:50.442  3999  4204 I BluetoothAdapterState: Entering PendingCommandState
,09-08 01:29:50.448  3999  3999 D BluetoothMapService: onReceive
09-08 01:29:50.448  3999  3999 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 01:29:50.448  3999  3999 D BluetoothMapService: STATE_TURNING_OFF
09-08 01:29:50.449  3999  3999 D BluetoothMapService: MAP Service closeService in
09-08 01:29:50.450  3999  3999 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 01:29:50.450  3999  3999 D ObexServerSockets0: shutdown(block = true)
09-08 01:29:50.451  3999  4230 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 01:29:50.454  3999  3999 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 01:29:50.455  3999  3999 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 01:29:50.455  3999  4231 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 01:29:50.456  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:50.457  3999  4216 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-08 01:29:50.457  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:50.457  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:50.457  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:50.457  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:50.457  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:50.457  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:50.457  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:50.457  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:50.458  3999  3999 I BtOppRfcommListener: stopping Accept Thread
,09-08 01:29:50.459  3999  4239 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 01:29:50.461  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:50.461  3999  4239 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 01:29:50.461  3999  4208 D BluetoothAdapterProperties: Scan Mode:20
09-08 01:29:50.461  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 01:29:50.464  3999  4204 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 01:29:50.467  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 01:29:50.467  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:50.467  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:50.467  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:50.467  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:50.467  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:50.467  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:50.467  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:50.467  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:50.468  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:50.468  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:50.469  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 01:29:50.470  3999  3999 D HeadsetService: Received stop request...Stopping profile...
09-08 01:29:50.472  1372  1384 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:50.472   872   872 D BluetoothHeadset: Proxy object disconnected
,09-08 01:29:50.472   872   872 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:50.472  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:50.472   872   872 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:50.472  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:29:50.472  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:29:50.472  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:29:50.472  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:29:50.472  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 01:29:50.472  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:29:50.472  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:29:50.472  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:29:50.473  3999  3999 D A2dpService: Received stop request...Stopping profile...
09-08 01:29:50.473  3946  3958 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:50.473  3846  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 01:29:50.473  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:29:50.474  3999  4223 D A2dpStateMachine: Exit Disconnected: -1
09-08 01:29:50.475  1947  3527 D BluetoothHeadset: Proxy object disconnected
09-08 01:29:50.476   872   872 D BluetoothA2dp: Proxy object disconnected
09-08 01:29:50.476  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:50.477  3999  3999 D HidService: Received stop request...Stopping profile...
09-08 01:29:50.477  3999  3999 D HidService: Stopping Bluetooth HidService
,09-08 01:29:50.478  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:50.480  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:50.482  3999  3999 D HealthService: Received stop request...Stopping profile...
09-08 01:29:50.483  3999  3999 V BluetoothAdapterState: isTurningOff()=true
,09-08 01:29:50.484  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-08 01:29:50.484  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:50.484  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:50.484  3999  3999 D PanService: Received stop request...Stopping profile...
,09-08 01:29:50.486  3946  3946 D HeadsetProfile: Bluetooth service disconnected
09-08 01:29:50.487  3999  3999 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 01:29:50.487  3999  3999 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 01:29:50.487  1372  1372 D HeadsetProfile: Bluetooth service disconnected
09-08 01:29:50.487  3999  4208 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 01:29:50.487  3999  4214 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:50.487  3999  4214 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 01:29:50.487  1372  1372 D BluetoothA2dp: Proxy object disconnected
09-08 01:29:50.487  3999  4214 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:50.487  3999  4208 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 01:29:50.487  1372  1372 D BluetoothInputDevice: Proxy object disconnected
09-08 01:29:50.488  1372  1372 D HidProfile: Bluetooth service disconnected
,09-08 01:29:50.488  3999  3999 D BluetoothMapService: Received stop request...Stopping profile...
09-08 01:29:50.488  3999  3999 D BluetoothMapService: stop()
09-08 01:29:50.488  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 01:29:50.488  1372  1372 D PanProfile: Bluetooth service disconnected
09-08 01:29:50.488  3999  3999 D BluetoothMapAppObserver: deinitObservers()
09-08 01:29:50.488  3946  3946 D BluetoothA2dp: Proxy object disconnected
,09-08 01:29:50.488  3999  3999 D BluetoothMapAppObserver: removeReceiver()
09-08 01:29:50.490  1372  1372 D BluetoothMap: Proxy object disconnected
09-08 01:29:50.490  1372  1372 D MapProfile: Bluetooth service disconnected
09-08 01:29:50.490  3999  3999 V BluetoothAdapterState: isTurningOff()=true
09-08 01:29:50.490  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-08 01:29:50.491  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 01:29:50.491  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:50.491  3946  3946 D DockEventReceiver: finishStartingService: stopping service
09-08 01:29:50.492  3999  4208 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 01:29:50.493  3999  4214 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:50.493  3999  3999 V BluetoothAdapterState: isTurningOff()=true
09-08 01:29:50.493  3999  3999 V BluetoothAdapterState: isTurningOn()=false
,09-08 01:29:50.493  3999  4214 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 01:29:50.493  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:50.493  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:50.493  3999  4214 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 01:29:50.493  3999  4214 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 01:29:50.493  3999  4214 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 01:29:50.493  3999  4214 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 01:29:50.495  3946  3946 D BluetoothInputDevice: Proxy object disconnected
09-08 01:29:50.495  3946  3946 D HidProfile: Bluetooth service disconnected
,09-08 01:29:50.497  3999  3999 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 01:29:50.497  3999  4208 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 01:29:50.497  3999  3999 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 01:29:50.497  3999  3999 V BluetoothAdapterState: isTurningOff()=true
,09-08 01:29:50.497  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-08 01:29:50.497  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:50.497  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:50.498  3999  3999 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 01:29:50.498  3999  4208 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-08 01:29:50.498  3999  3999 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-08 01:29:50.499  3999  3999 V BluetoothAdapterState: isTurningOff()=true
,09-08 01:29:50.499  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 01:29:50.499  3999  3999 V BluetoothAdapterState: isTurningOn()=false
,09-08 01:29:50.499  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:29:50.499  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:50.499  3999  3999 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-08 01:29:50.499  3999  3999 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 01:29:50.500  3999  3999 D BluetoothMapService: MAP Service closeService in
,09-08 01:29:50.500  3999  3999 V BluetoothAdapterState: isTurningOff()=true
,09-08 01:29:50.501  3999  3999 V BluetoothAdapterState: isTurningOn()=false
09-08 01:29:50.501  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 01:29:50.501  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:29:50.501  3999  4204 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 01:29:50.501  3999  4204 D BluetoothAdapterProperties: Setting state to 15
,09-08 01:29:50.501  3999  4204 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-08 01:29:50.501  3999  4204 I BluetoothAdapterState: Entering BleOnState
,09-08 01:29:50.502  3999  3999 D BluetoothMapService: cleanup()
09-08 01:29:50.502  3999  3999 D BluetoothMapService: MAP Service closeService in
09-08 01:29:50.502  3946  4245 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 01:29:50.502   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 01:29:50.502   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 01:29:50.502  1372  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 01:29:50.503   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 01:29:50.503  3946  3956 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 01:29:50.503  3946  3946 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 01:29:50.503  3946  3946 D PanProfile: Bluetooth service disconnected
,09-08 01:29:50.504  1372  1384 D BluetoothPan: onBluetoothStateChange on: false
09-08 01:29:50.504  1372  1372 D BluetoothPbap: Proxy object disconnected
09-08 01:29:50.504  1372  1372 D PbapServerProfile: Bluetooth service disconnected
09-08 01:29:50.504  3946  3946 D BluetoothMap: Proxy object disconnected
,09-08 01:29:50.504  3946  3946 D MapProfile: Bluetooth service disconnected
,09-08 01:29:50.504  3946  3946 D BluetoothPbap: Proxy object disconnected
09-08 01:29:50.504  3946  3946 D PbapServerProfile: Bluetooth service disconnected
09-08 01:29:50.507   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 01:29:50.508  1372  1666 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 01:29:50.509  3946  4245 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 01:29:50.511  1372  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 01:29:50.511  1372  2069 D BluetoothMap: onBluetoothStateChange: up=false
09-08 01:29:50.512  1947  2207 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 01:29:50.512  3946  3956 D BluetoothMap: onBluetoothStateChange: up=false,
09-08 01:29:50.513  3946  3958 D BluetoothPan: onBluetoothStateChange on: false
,09-08 01:29:50.513  3946  4245 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 01:29:50.514  1372  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 01:29:50.514  3999  4204 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-08 01:29:50.514  3999  4204 D BluetoothAdapterProperties: Setting state to 16
09-08 01:29:50.514  3999  4204 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 01:29:50.515  3999  4204 D BluetoothAdapterProperties: onBleDisable
09-08 01:29:50.515  3999  4204 I BluetoothAdapterState: Entering PendingCommandState
,09-08 01:29:50.515  3999  4205 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 01:29:50.517  3999  4208 D BluetoothAdapterProperties: Scan Mode:20
09-08 01:29:50.518  3999  4214 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 01:29:50.518  3999  4214 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 01:29:50.518  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:50.520  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:50.520  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 01:29:50.522  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:50.523  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:50.524  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:29:50.525  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:29:50.526  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 01:29:50.532  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-08 01:29:50.721  3999  4208 I bt_hci  : shut_down
,09-08 01:29:50.722  3999  4212 D bt_hwcfg: hw_epilog_process
,09-08 01:29:50.734  3999  4212 I bt_vendor: low_power_mode_cb
,09-08 01:29:50.764  3999  4212 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 01:29:50.765  3999  4212 I bt_vendor: epilog_cb
09-08 01:29:50.765  3999  4212 I bt_hci  : epilog_finished_callback
,09-08 01:29:50.773  3999  4208 I bt_hci_h4: hal_close
,09-08 01:29:50.775  3999  4208 I bt_userial_vendor: device fd = 51 close
,09-08 01:29:50.888  3999  4205 D bt_stack_manager: event_shut_down_stack finished.
09-08 01:29:50.889  3999  4204 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 01:29:50.896  3999  3999 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 01:29:50.896  3999  4204 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 01:29:50.897  3999  3999 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 01:29:50.897  3999  3999 D BtGatt.GattService: stop()
,09-08 01:29:50.898  3999  3999 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 01:29:50.904  3999  3999 V BluetoothAdapterState: isTurningOff()=false
09-08 01:29:50.904  3999  3999 V BluetoothAdapterState: isTurningOn()=false
,09-08 01:29:50.904  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 01:29:50.905  3999  3999 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 01:29:50.905  3999  4204 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 01:29:50.906  3999  4204 D BluetoothAdapterProperties: Setting state to 10
,09-08 01:29:50.906  3999  4204 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 01:29:50.908  3999  4204 I BluetoothAdapterState: Entering OffState
09-08 01:29:50.910   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 01:29:50.939  3999  3999 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 01:29:50.939  3999  3999 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-08 01:29:50.940  3999  4205 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 01:29:50.946  3999  4205 D bt_stack_manager: event_clean_up_stack finished.
,09-08 01:29:50.947  3999  3999 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 01:29:50.953  3999  3999 I art     : System.exit called, status: 0
,09-08 01:29:50.953  3999  3999 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 01:29:51.013   872  1700 I ActivityManager: Process com.android.bluetooth (pid 3999) has died
,09-08 01:29:55.433  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:29:55.433  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:55.439  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:29:55.439  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@78aed16 removed from the list
09-08 01:29:55.440  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:29:55.440  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:29:55.440  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:55.443  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 01:29:55.443  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2629084 added. We now have 4 listener(s)
09-08 01:29:55.444  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:29:55.446  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:29:55.447  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2629084 removed from the list
,09-08 01:29:55.448  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:29:55.449  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:29:55.449  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:29:55.454  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 01:29:55.455  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@617f06d added. We now have 4 listener(s)
09-08 01:29:55.455  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:30:00.464  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:00.513   872   889 I ActivityManager: Start proc 4251:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 01:30:00.653  4251  4251 D AdapterServiceConfig: Adding HeadsetService
,09-08 01:30:00.654  4251  4251 D AdapterServiceConfig: Adding A2dpService
09-08 01:30:00.655  4251  4251 D AdapterServiceConfig: Adding HidService
09-08 01:30:00.656  4251  4251 D AdapterServiceConfig: Adding HealthService
,09-08 01:30:00.657  4251  4251 D AdapterServiceConfig: Adding PanService
09-08 01:30:00.657  4251  4251 D AdapterServiceConfig: Adding GattService
,09-08 01:30:00.658  4251  4251 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 01:30:00.674   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30fbf65:true
09-08 01:30:00.675  4251  4251 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 01:30:00.680  4251  4251 I bt_bluedroid: init
,09-08 01:30:00.681  4251  4263 I BluetoothAdapterState: Entering OffState
,09-08 01:30:00.686  4251  4264 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 01:30:00.686  4251  4264 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 01:30:00.687  4251  4264 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 01:30:00.687  4251  4264 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 01:30:00.689  4251  4251 I bt_bluedroid: get_profile_interface socket
,09-08 01:30:00.695  4251  4251 I bt_bluedroid: get_profile_interface sdp
09-08 01:30:00.695  4251  4267 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 01:30:00.699  4251  4267 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 01:30:00.702  4251  4262 I bt_bluedroid: config_hci_snoop_log
,09-08 01:30:00.705   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 01:30:00.717  4251  4263 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 01:30:00.717  4251  4263 D BluetoothAdapterProperties: Setting state to 14
09-08 01:30:00.718  4251  4263 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 01:30:00.722  4251  4263 D BluetoothBondStateMachine: make
,09-08 01:30:00.728  4251  4268 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 01:30:00.737  4251  4263 I BluetoothAdapterState: Entering PendingCommandState
,09-08 01:30:00.742  4251  4251 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 01:30:00.753  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:30:00.758  4251  4251 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 01:30:00.758  4251  4251 D BtGatt.GattService: Received start request. Starting profile...
,09-08 01:30:00.759  4251  4251 D BtGatt.GattService: start()
09-08 01:30:00.759  4251  4251 I bt_bluedroid: get_profile_interface gatt
,09-08 01:30:00.760  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:30:00.760  4251  4251 D BtGatt.AdvertiseManager: advertise manager created
,09-08 01:30:00.770  4251  4251 V BluetoothAdapterState: isTurningOff()=false
,09-08 01:30:00.770  4251  4251 V BluetoothAdapterState: isTurningOn()=false
09-08 01:30:00.771  4251  4251 V BluetoothAdapterState: isBleTurningOn()=true
09-08 01:30:00.771  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 01:30:00.771  4251  4263 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-08 01:30:00.772  4251  4263 I bt_bluedroid: enable
09-08 01:30:00.772  4251  4264 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 01:30:00.773  4251  4264 I bt_hci  : start_up
,09-08 01:30:00.782  4251  4264 I bt_vendor: alloc value 0xb3a7e189
,09-08 01:30:00.782  4251  4264 I bt_vendor: init
09-08 01:30:00.782  4251  4264 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 01:30:00.782  4251  4264 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 01:30:00.890  4251  4264 D bt_hci  : start_up starting async portion
,09-08 01:30:00.891  4251  4271 I bt_hci  : event_finish_startup
09-08 01:30:00.891  4251  4271 I bt_hci_h4: hal_open
09-08 01:30:00.891  4251  4271 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 01:30:00.903  4251  4271 I bt_userial_vendor: device fd = 51 open
,09-08 01:30:00.934  4251  4271 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 01:30:00.966  4251  4271 D bt_hwcfg: Chipset BCM4354A2
,09-08 01:30:00.966  4251  4271 D bt_hwcfg: Target name = [BCM4354A2]
09-08 01:30:00.967  4251  4271 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 01:30:01.837  4251  4271 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 01:30:01.839  4251  4271 D bt_hwcfg: Settlement delay -- 100 ms
09-08 01:30:01.839  4251  4271 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 01:30:01.957  4251  4271 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 01:30:01.959  4251  4271 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 01:30:01.986  4251  4271 I bt_hwcfg: vendor lib fwcfg completed
,09-08 01:30:01.986  4251  4271 I bt_vendor: firmware callback
09-08 01:30:01.987  4251  4271 I bt_hci  : firmware_config_callback
,09-08 01:30:01.999  4251  4273 I bt_btu  : btu_task pending for preload complete event
,09-08 01:30:02.000  4251  4273 I bt_btu_task: Bluetooth chip preload is complete
,09-08 01:30:02.000  4251  4273 I bt_btu  : btu_task received preload complete event
,09-08 01:30:02.010  4251  4273 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 01:30:02.010  4251  4273 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 01:30:02.010  4251  4273 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
,09-08 01:30:02.010  4251  4273 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 01:30:02.011  4251  4273 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 01:30:02.011  4251  4273 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 01:30:02.011  4251  4273 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 01:30:02.011  4251  4273 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 01:30:02.012  4251  4273 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 01:30:02.012  4251  4273 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 01:30:02.012  4251  4273 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 01:30:02.012  4251  4273 I         : BTE_InitTraceLevels -- TRC_GATT
,09-08 01:30:02.013  4251  4273 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 01:30:02.013  4251  4273 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 01:30:02.013  4251  4273 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 01:30:02.156  4251  4273 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fbd9d
,09-08 01:30:02.156  4251  4273 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fbd9d 
,09-08 01:30:02.169  4251  4267 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 01:30:02.173  4251  4267 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 01:30:02.174  4251  4267 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-08 01:30:02.177  4251  4267 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 01:30:02.180  4251  4267 D BluetoothAdapterProperties: Scan Mode:20
,09-08 01:30:02.181  4251  4267 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 01:30:02.183  4251  4267 D bt_hci  : do_postload posting postload work item
09-08 01:30:02.183  4251  4271 I bt_hci  : event_postload
09-08 01:30:02.183  4251  4271 I bt_vendor: sco_config_cb
09-08 01:30:02.184  4251  4271 I bt_hci  : sco_config_callback postload finished.
,09-08 01:30:02.187  4251  4267 D bt_bte_conf: Device ID record 1 : primary
09-08 01:30:02.187  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:30:02.188  4251  4267 D bt_bte_conf:   vendorId            = 000f,
09-08 01:30:02.188  4251  4267 D bt_bte_conf:   vendorIdSource      = 0001
09-08 01:30:02.188  4251  4267 D bt_bte_conf:   product             = 1200
09-08 01:30:02.189  4251  4267 D bt_bte_conf:   version             = 1436
,09-08 01:30:02.192  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:02.192  4251  4267 D bt_bte_conf:   clientExecutableURL = 
,09-08 01:30:02.192  4251  4267 D bt_bte_conf:   serviceDescription  = 
09-08 01:30:02.193  4251  4267 D bt_bte_conf:   documentationURL    = 
09-08 01:30:02.193  4251  4267 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 01:30:02.193  4251  4264 D bt_stack_manager: event_start_up_stack finished
09-08 01:30:02.194  4251  4263 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 01:30:02.194  4251  4263 D BluetoothAdapterProperties: Setting state to 15
09-08 01:30:02.194  4251  4263 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 01:30:02.195  4251  4271 I bt_vendor: low_power_mode_cb
09-08 01:30:02.195  4251  4263 I BluetoothAdapterState: Entering BleOnState
,09-08 01:30:02.202  4251  4263 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 01:30:02.203  4251  4263 D BluetoothAdapterProperties: Setting state to 11
,09-08 01:30:02.203  4251  4263 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 01:30:02.207  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:02.209  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:02.211  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:30:02.211  4251  4251 D HeadsetService: Received start request. Starting profile...
,09-08 01:30:02.216  4251  4251 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 01:30:02.216  4251  4251 D HeadsetStateMachine: make
,09-08 01:30:02.224  4251  4263 I BluetoothAdapterState: Entering PendingCommandState
,09-08 01:30:02.225  4251  4251 D HeadsetStateMachine: max_hf_connections = 1
09-08 01:30:02.225  4251  4251 I bt_bluedroid: get_profile_interface handsfree
09-08 01:30:02.225  4251  4267 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 01:30:02.225  4251  4267 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 01:30:02.230  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:30:02.231  4251  4251 D A2dpService: Received start request. Starting profile...
09-08 01:30:02.232  4251  4251 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 01:30:02.232  4251  4251 I bt_bluedroid: get_profile_interface avrcp
,09-08 01:30:02.232  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 01:30:02.241  4251  4251 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 01:30:02.241  4251  4251 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 01:30:02.241  4251  4251 D A2dpStateMachine: make
,09-08 01:30:02.242  4251  4251 I bt_bluedroid: get_profile_interface a2dp
,09-08 01:30:02.243  4251  4267 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 01:30:02.245  4251  4282 D A2dpStateMachine: Enter Disconnected: -2
,09-08 01:30:02.246  4251  4251 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 01:30:02.247  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:30:02.247  4251  4251 D HidService: Received start request. Starting profile...
,09-08 01:30:02.247  4251  4251 I bt_bluedroid: get_profile_interface hidhost
09-08 01:30:02.247  4251  4251 D HidService: setHidService(): set to: null
09-08 01:30:02.247  4251  4267 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39dd3e5
09-08 01:30:02.248  4251  4267 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-08 01:30:02.248  4251  4251 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 01:30:02.249  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:30:02.249  4251  4251 D HealthService: Received start request. Starting profile...
,09-08 01:30:02.251  4251  4251 I bt_bluedroid: get_profile_interface health
,09-08 01:30:02.251  4251  4251 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 01:30:02.252  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:30:02.253  4251  4251 D PanService: Received start request. Starting profile...
09-08 01:30:02.253  4251  4251 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 01:30:02.253  4251  4251 I bt_bluedroid: get_profile_interface pan
,09-08 01:30:02.254  4251  4267 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 01:30:02.257  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:30:02.258  4251  4251 D BluetoothMapService: Received start request. Starting profile...
09-08 01:30:02.258  4251  4251 D BluetoothMapService: start()
,09-08 01:30:02.260  4251  4251 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 01:30:02.260  4251  4251 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 01:30:02.260  4251  4251 D BluetoothMapAppObserver: createReceiver()
,09-08 01:30:02.261  4251  4251 D BluetoothMapAppObserver: initObservers()
09-08 01:30:02.261  4251  4251 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 01:30:02.268  4251  4251 V BluetoothAdapterState: isTurningOff()=false
,09-08 01:30:02.268  4251  4251 V BluetoothAdapterState: isTurningOn()=true
09-08 01:30:02.268  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:30:02.268  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 01:30:02.270  4251  4280 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 01:30:02.273  4251  4251 V BluetoothAdapterState: isTurningOff()=false
,09-08 01:30:02.273  4251  4251 V BluetoothAdapterState: isTurningOn()=true
09-08 01:30:02.274  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:30:02.274  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 01:30:02.274  4251  4251 V BluetoothAdapterState: isTurningOff()=false
,09-08 01:30:02.274  4251  4251 V BluetoothAdapterState: isTurningOn()=true
,09-08 01:30:02.274  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:30:02.274  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:30:02.275  4251  4251 V BluetoothAdapterState: isTurningOff()=false
09-08 01:30:02.275  4251  4251 V BluetoothAdapterState: isTurningOn()=true
09-08 01:30:02.275  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:30:02.275  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:30:02.275  4251  4251 V BluetoothAdapterState: isTurningOff()=false
09-08 01:30:02.275  4251  4251 V BluetoothAdapterState: isTurningOn()=true
09-08 01:30:02.275  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:30:02.275  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:30:02.276  4251  4251 V BluetoothAdapterState: isTurningOff()=false
09-08 01:30:02.276  4251  4251 V BluetoothAdapterState: isTurningOn()=true
09-08 01:30:02.276  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
09-08 01:30:02.276  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
09-08 01:30:02.276  4251  4263 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 01:30:02.276  4251  4263 D BluetoothAdapterProperties: ScanMode =  20
09-08 01:30:02.277  4251  4263 D BluetoothAdapterProperties: State =  11
09-08 01:30:02.278  4251  4267 D BluetoothAdapterProperties: Scan Mode:21
09-08 01:30:02.278  4251  4267 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 01:30:02.278  4251  4263 D BluetoothAdapterProperties: Setting state to 12
09-08 01:30:02.279  4251  4263 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 01:30:02.280  3946  4245 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 01:30:02.280  4251  4263 I BluetoothAdapterState: Entering OnState
09-08 01:30:02.281   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 01:30:02.281   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 01:30:02.281  1372  1666 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 01:30:02.282  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:30:02.282  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:02.282  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:02.282  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:30:02.282  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:02.282  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:30:02.282  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:30:02.282  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:30:02.284  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:30:02.284  1372  1372 D BluetoothInputDevice: Proxy object connected
,09-08 01:30:02.284  1372  1372 D HidProfile: Bluetooth service connected
09-08 01:30:02.285   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 01:30:02.285  3946  3956 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 01:30:02.286   872   872 D BluetoothA2dp: Proxy object connected
09-08 01:30:02.288  4251  4251 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 01:30:02.288  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:30:02.288  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:02.288  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:02.288  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:30:02.288  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:02.288  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:30:02.288  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:30:02.288  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 01:30:02.290  4251  4251 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 01:30:02.290  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 01:30:02.291  3946  3946 D BluetoothA2dp: Proxy object connected
09-08 01:30:02.291  1372  2069 D BluetoothPan: onBluetoothStateChange on: true
,09-08 01:30:02.291  4251  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 01:30:02.293   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 01:30:02.294  1372  1384 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 01:30:02.294  4251  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 01:30:02.296  3946  4245 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 01:30:02.296  4251  4251 D ObexServerSockets: Succeed to create listening sockets 
,09-08 01:30:02.296  4251  4251 D ObexServerSockets0: startAccept()
09-08 01:30:02.296  4251  4251 D ObexServerSockets0: prepareForNewConnect()
,09-08 01:30:02.297  1372  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 01:30:02.298  4251  4251 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 01:30:02.299  4251  4251 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 01:30:02.299  4251  4289 D ObexServerSockets0: Accepting socket connection...
,09-08 01:30:02.299  1372  1372 D BluetoothA2dp: Proxy object connected
09-08 01:30:02.299  1372  2069 D BluetoothMap: onBluetoothStateChange: up=true
09-08 01:30:02.300  4251  4290 D ObexServerSockets0: Accepting socket connection...
09-08 01:30:02.301  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 01:30:02.301  1372  1372 D PanProfile: Bluetooth service connected
09-08 01:30:02.301  1947  2137 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 01:30:02.302  3946  3958 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 01:30:02.302  1372  1372 D BluetoothMap: Proxy object connected
09-08 01:30:02.302  1372  1372 D MapProfile: Bluetooth service connected
09-08 01:30:02.302  1372  1372 D BluetoothMap: getConnectedDevices()
09-08 01:30:02.304  3946  4245 D BluetoothPan: onBluetoothStateChange on: true
,09-08 01:30:02.306  3946  3958 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 01:30:02.307  3946  3946 D BluetoothMap: Proxy object connected
09-08 01:30:02.307  3946  3946 D MapProfile: Bluetooth service connected
09-08 01:30:02.307  3946  3946 D BluetoothMap: getConnectedDevices(),
09-08 01:30:02.307  1372  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 01:30:02.309  3946  3946 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 01:30:02.309  3946  3946 D PanProfile: Bluetooth service connected
09-08 01:30:02.309  3946  3946 D BluetoothInputDevice: Proxy object connected
09-08 01:30:02.309  3946  3946 D HidProfile: Bluetooth service connected
09-08 01:30:02.309   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 01:30:02.311  4251  4251 D BluetoothMapService: onReceive
,09-08 01:30:02.311  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:30:02.311  4251  4251 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 01:30:02.311  4251  4251 D BluetoothMapService: STATE_ON
,09-08 01:30:02.313  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:02.317  3946  3946 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 01:30:02.322  3946  3946 D DockEventReceiver: finishStartingService: stopping service
,09-08 01:30:02.324  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 01:30:02.330  3946  3946 D BluetoothPbap: Proxy object connected
,09-08 01:30:02.330  3946  3946 D PbapServerProfile: Bluetooth service connected
,09-08 01:30:02.337  4251  4251 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 01:30:02.338  4251  4251 D ObexServerSockets0: prepareForNewConnect()
09-08 01:30:02.339  1372  1372 D BluetoothPbap: Proxy object connected
09-08 01:30:02.339  1372  1372 D PbapServerProfile: Bluetooth service connected
,09-08 01:30:02.339  4251  4294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 01:30:02.358  4251  4298 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 01:30:02.360  4251  4298 I BtOppRfcommListener: Accept thread started.
,09-08 01:30:02.382  1372  1384 D BluetoothHeadset: Proxy object connected
,09-08 01:30:02.382   872   872 D BluetoothHeadset: Proxy object connected
,09-08 01:30:02.382   872   872 D BluetoothHeadset: Proxy object connected
,09-08 01:30:02.382   872   872 D BluetoothHeadset: Proxy object connected
09-08 01:30:02.382  1372  1372 D HeadsetProfile: Bluetooth service connected
09-08 01:30:02.383  3946  3956 D BluetoothHeadset: Proxy object connected
09-08 01:30:02.383  3946  3946 D HeadsetProfile: Bluetooth service connected
,09-08 01:30:02.383  1947  1962 D BluetoothHeadset: Proxy object connected
,09-08 01:30:02.394   872   889 D BluetoothHeadset: Proxy object connected
,09-08 01:30:02.403  1947  1961 D BluetoothHeadset: Proxy object connected
,09-08 01:30:02.408  1372  1383 D BluetoothHeadset: Proxy object connected
,09-08 01:30:02.409  1372  1372 D HeadsetProfile: Bluetooth service connected
,09-08 01:30:05.483  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:30:05.483  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:05.483  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:05.483  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 01:30:05.483  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:05.483  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:30:05.483  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:30:05.483  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 01:30:05.492  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 01:30:05.493  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:30:05.493  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@617f06d removed from the list
,09-08 01:30:05.494  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:30:05.495  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:30:05.495  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:05.502  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 01:30:05.503  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c0c4a2 added. We now have 4 listener(s)
,09-08 01:30:05.503  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:30:05.510   872  1965 D WifiService: setWifiEnabled: false pid=3846, uid=10000
,09-08 01:30:05.510   872  1965 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 01:30:10.525  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:10.526   872  1700 D WifiService: setWifiEnabled: true pid=3846, uid=10000
09-08 01:30:10.527   872  1700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 01:30:10.538   872  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-08 01:30:10.559  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:30:10.559  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:10.559  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:10.559  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:10.559  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:10.559  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:30:10.559  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:30:10.559  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:30:10.563  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 01:30:10.568  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:30:10.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:10.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:10.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:10.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:10.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 01:30:10.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 01:30:10.568  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 01:30:10.571  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 01:30:10.584   872  1314 D WifiConfigStore: loaded 0 passpoint configs
,09-08 01:30:10.585   872  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000,
09-08 01:30:10.585   872  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 01:30:10.586   872  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 01:30:10.587   872  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 01:30:10.587   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 01:30:10.587   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 01:30:10.603   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 01:30:10.603   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 01:30:10.604   371   870 D CommandListener: Setting iface cfg
,09-08 01:30:10.605   872  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-08 01:30:10.605   872  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 01:30:10.662   872  1314 E native  : do suspend true
,09-08 01:30:10.665   872  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 01:30:10.681   872  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 01:30:10.696   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 01:30:12.017   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 01:30:12.062  1882  1997 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-08 01:30:12.062  1882  1997 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 01:30:12.083  1516  1516 I ConfigService: onCreate
,09-08 01:30:12.135   872  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.62 rxSuccessRate=10.75 delta 1000 -> 994
,09-08 01:30:12.136   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 01:30:12.136   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 01:30:12.153   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 01:30:12.188   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 01:30:12.189  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 01:30:12.626  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 01:30:12.672  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 01:30:12.673  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 01:30:12.678   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 01:30:12.703   872  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 01:30:12.704   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 01:30:12.704   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 01:30:12.740   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 01:30:12.768   371   870 D CommandListener: Setting iface cfg
,09-08 01:30:12.771   872  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 01:30:12.789   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 01:30:12.802   872  4309 D DhcpClient: Receive thread started
,09-08 01:30:12.899   872  1314 E native  : do suspend false
,09-08 01:30:12.924   872  1862 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 01:30:12.940   872  4309 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-08 01:30:12.943   872  1862 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-08 01:30:12.949   872  1862 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 01:30:12.962   872  4309 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 01:30:12.963   872  1862 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 01:30:12.971   371   870 D CommandListener: Setting iface cfg
,09-08 01:30:12.983   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 01:30:12.985   872  1862 D DhcpClient: Scheduling renewal in 86399s
09-08 01:30:12.986   872  1314 E native  : do suspend true
,09-08 01:30:13.005   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 01:30:13.008   872  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 01:30:13.009   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 01:30:13.015   872  1316 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 01:30:13.016   872  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 01:30:13.052   872  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 01:30:13.052   872  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 01:30:13.055   872  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 01:30:13.058   872  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 01:30:13.062   872  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 01:30:13.075   872  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 01:30:13.079   872  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 01:30:13.080   872  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-08 01:30:13.080   872  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-08 01:30:13.080   872  1316 D ConnectivityService:    accepting network in place of null
,09-08 01:30:13.081   872  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 01:30:13.081   872  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 01:30:13.084   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 01:30:13.096   872  4308 D NetlinkSocketObserver: NeighborEvent{elapsedMs=211083, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 01:30:13.130   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 01:30:13.163   872  4307 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-08 01:30:13.172   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 01:30:13.184   872  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-08 01:30:13.185   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 01:30:13.196   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-08 01:30:13.203   872  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-08 01:30:13.215  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:30:13.215  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:13.215  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:13.215  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:13.215  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:13.215  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:13.215  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:30:13.215  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:30:13.218  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:30:13.224  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:30:13.224  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:13.224  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:13.224  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:13.224  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:13.224  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:13.224  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:30:13.224  3846  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:30:13.227  3846  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:30:13.235  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 01:30:13.228  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-08 01:30:13.243  1743  1743 D SystemUpdateService: onCreate
,09-08 01:30:13.247  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 01:30:13.271  1743  4318 I SystemUpdateService: active receiver: enabled
,09-08 01:30:13.273  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 01:30:13.278  1743  2437 I iu.UploadsManager: num queued entries: 0
09-08 01:30:13.278  1743  2437 I iu.UploadsManager: num updated entries: 0
,09-08 01:30:13.279  1743  2437 I iu.SyncManager: NEXT; no task
09-08 01:30:13.280  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 01:30:13.290  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 01:30:13.292  4039  4039 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 01:30:13.301  1743  4318 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 01:30:13.310  4039  4039 D SprintDMHelper: simOperator: 
09-08 01:30:13.310  4039  4039 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 01:30:13.313  1743  4320 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-08 01:30:13.313  1743  4320 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 01:30:13.315  1743  4320 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 01:30:13.333  1743  4318 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-08 01:30:13.333  1743  4318 I SystemUpdateService: now status is 0 (complete)
09-08 01:30:13.333  1743  4318 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 01:30:13.333  1743  4318 I SystemUpdateService: file has been verified
,09-08 01:30:13.340  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 01:30:13.342  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 01:30:13.343  1743  4318 I SystemUpdateService: OTA package size = 12249756
,09-08 01:30:13.365  1743  4318 I SystemUpdateService: showing system update notification
,09-08 01:30:13.399  1743  1743 D SystemUpdateService: onDestroy
,09-08 01:30:13.405  1516  2324 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-08 01:30:13.405  1516  2324 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 01:30:13.405  1516  2324 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 01:30:13.405  1516  2324 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 01:30:13.426  1743  4320 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-08 01:30:13.442  4012  4323 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 01:30:13.580   872  1700 D ConnectivityService: reportNetworkConnectivity(102, true) by 10011
,09-08 01:30:13.591  1516  4327 I GCM     : Ack for not saved message 139
,09-08 01:30:13.615   872  1699 D ConnectivityService: reportNetworkConnectivity(102, true) by 10011
,09-08 01:30:13.617   872  1385 D ConnectivityService: reportNetworkConnectivity(102, true) by 10011
,09-08 01:30:14.184   872  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 01:30:14.239   872  4307 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 23:30:14 GMT], X-Android-Received-Millis=[1473291014237], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473291014213]}
,09-08 01:30:14.247   872  4307 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Forcing reevaluation for UID 10011
,09-08 01:30:14.247   872  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 01:30:14.249   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-08 01:30:14.249   872  4307 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-08 01:30:14.250   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 01:30:14.257   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 01:30:14.279   872  4307 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 23:30:14 GMT], X-Android-Received-Millis=[1473291014278], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473291014255]}
,09-08 01:30:14.280   872  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 01:30:14.281   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-08 01:30:15.552  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 01:30:15.552  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:15.552  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:15.552  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:15.552  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:15.552  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:15.552  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:30:15.552  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:30:15.559  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:30:15.560  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:30:15.561  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c0c4a2 removed from the list
,09-08 01:30:15.562  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:30:15.563  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:15.564  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:15.577  3846  4330 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-08 01:30:15.577  3846  4330 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 01:30:17.136  1516  1516 I ConfigService: onDestroy
,09-08 01:30:18.585  3846  4332 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 01:30:18.587  3846  4330 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-08 01:30:18.587  3846  4332 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 01:30:18.587  3846  4330 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 01:30:18.588  3846  4332 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 01:30:18.588  3846  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 01:30:18.591  3846  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 01:30:18.591  3846  4332 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 01:30:18.595  3846  4332 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 01:30:18.595  3846  4334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
09-08 01:30:18.595  3846  4330 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 01:30:18.601  3846  4335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Sender)
,09-08 01:30:18.603  3846  4336 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Receiver)
,09-08 01:30:18.604  3846  4336 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: IncomingSocketThread/Receiver)
09-08 01:30:18.604  3846  4336 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 01:30:18.605  3846  4336 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 01:30:18.607  3846  4337 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Receiver)
,09-08 01:30:18.609  3846  4337 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: OutgoingSocketThread/Receiver)
,09-08 01:30:18.610  3846  4337 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-08 01:30:18.610  3846  4337 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 01:30:21.087   872  1316 D ConnectivityService: handlePromptUnvalidated 102
,09-08 01:30:21.584  3846  3898 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 01:30:21.586  3846  3898 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 01:30:21.595  3846  3898 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@966c6e4 Bundle[{}]
09-08 01:30:21.595  3846  3898 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 01:30:21.595  3846  3898 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-08 01:30:21.596  3846  3898 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 01:30:21.596  3846  3898 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 01:30:21.597  3846  3898 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 01:30:21.597  3846  3898 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-08 01:30:21.602  3846  3898 I System.out: Running OutgoingSocketThread
,09-08 01:30:21.605  3846  4338 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 01:30:21.606  3846  4338 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 01:30:24.616  3846  4339 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-08 01:30:24.616  3846  4339 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-08 01:30:24.617  3846  4339 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 01:30:24.617  3846  4338 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-08 01:30:24.617  3846  4338 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 01:30:24.618  3846  4338 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 01:30:24.618  3846  4339 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 01:30:24.620  3846  4338 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 01:30:24.621  3846  4339 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 01:30:24.624  3846  4341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Sender)
,09-08 01:30:24.625  3846  4342 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Sender)
09-08 01:30:24.626  3846  4338 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 01:30:24.629  3846  4343 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Receiver)
,09-08 01:30:24.630  3846  4343 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: IncomingSocketThread/Receiver)
,09-08 01:30:24.630  3846  4343 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 01:30:24.631  3846  4344 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Receiver)
,09-08 01:30:24.631  3846  4343 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 01:30:24.632  3846  4344 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: OutgoingSocketThread/Receiver)
09-08 01:30:24.633  3846  4344 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-08 01:30:24.633  3846  4344 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 01:30:27.617  3846  3898 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,09-08 01:30:27.621  3846  3898 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-08 01:30:27.621  3846  3898 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
,09-08 01:30:27.626  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 01:30:27.627  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9494533 added. We now have 3 listener(s)
,09-08 01:30:27.629  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 01:30:27.629  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 01:30:27.629  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 01:30:27.629  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 01:30:27.629  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fba30f0 added. We now have 4 listener(s)
09-08 01:30:27.629  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:30:27.630  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 01:30:27.633  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:30:27.643  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-08 01:30:27.643  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:27.643  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:27.643  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:27.643  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,09-08 01:30:27.643  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:27.643  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:30:27.643  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:30:27.649  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:27.649  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 01:30:27.651  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:30:27.651  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:30:27.651  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:30:27.652  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:30:27.652  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:27.652  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:30:27.652  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 01:30:27.653  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9494533 removed from the list
09-08 01:30:27.653  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:30:27.653  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fba30f0 removed from the list
,09-08 01:30:27.655  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:27.659  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:27.660  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:30:27.660  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:27.661  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:27.661  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:27.664  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:27.664  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:30:27.664  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:30:27.665  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fba30f0 not in the list
09-08 01:30:27.665  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:27.665  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:27.668  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:30:27.668  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:27.668  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:30:27.669  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fba30f0 not in the list
09-08 01:30:27.669  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 01:30:27.669  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:27.669  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:27.670  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9494533 not in the list
,09-08 01:30:27.672  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 01:30:27.672  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a88ee added. We now have 3 listener(s)
,09-08 01:30:27.678  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 01:30:27.678  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 01:30:27.679  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 01:30:27.680  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 01:30:27.680  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c9018f added. We now have 4 listener(s)
09-08 01:30:27.680  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 01:30:27.680  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 01:30:27.684  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:30:27.692  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:30:27.692  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:27.692  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:27.692  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:27.692  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:27.692  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:27.692  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:30:27.692  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:30:27.697  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:30:27.697  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 01:30:27.697  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 01:30:27.697  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 01:30:27.697  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 01:30:27.697  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:30:27.697  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 01:30:27.700  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:27.703  3846  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 01:30:27.703  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 01:30:27.706  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:27.711  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 01:30:27.712  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 01:30:27.712  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 01:30:27.719  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 01:30:27.719  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 01:30:27.719  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 01:30:27.720  3846  3898 D BluetoothAdapter: STATE_ON
,09-08 01:30:27.727  4251  4261 D BtGatt.GattService: registerClient() - UUID=6e2be60c-10ec-4467-a50f-a603ea39fa9c
,09-08 01:30:27.728  4251  4267 D BtGatt.GattService: onClientRegistered() - UUID=6e2be60c-10ec-4467-a50f-a603ea39fa9c, clientIf=5
,09-08 01:30:27.730  3846  3858 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 01:30:27.732  4251  4279 D BtGatt.GattService: start scan with filters
,09-08 01:30:27.740  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 01:30:27.740  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 01:30:27.740  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 01:30:27.740  4251  4270 D BtGatt.ScanManager: handling starting scan
09-08 01:30:27.741  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 01:30:27.743  4251  4270 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba5ef38
,09-08 01:30:27.751  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 01:30:27.752  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 01:30:27.752  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 01:30:27.755  4251  4267 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 01:30:27.755  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:30:27.756  4251  4270 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 01:30:27.758  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 01:30:27.767  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 01:30:27.767  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:30:27.768  4251  4270 D BtGatt.ScanManager: Starting BLE batch scan
09-08 01:30:27.768  4251  4270 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 01:30:27.769  3846  3898 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 01:30:27.769  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:30:27.770  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 01:30:27.770  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:27.770  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 01:30:27.770  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 01:30:27.770  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 01:30:27.771  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 01:30:27.771  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 01:30:27.772  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 01:30:27.772  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 01:30:27.773  3846  3898 D BluetoothAdapter: STATE_ON
,09-08 01:30:27.775  4251  4287 D BtGatt.GattService: stopScan() - queue size =1
,09-08 01:30:27.777  4251  4261 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 01:30:27.777  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 01:30:27.777  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 01:30:27.778  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 01:30:27.778  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 01:30:27.778  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 01:30:27.780  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 01:30:27.781  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 01:30:27.781  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 01:30:27.781  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 01:30:27.782  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 01:30:27.783  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:30:27.783  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:30:27.784  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 01:30:27.798  4251  4267 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 01:30:27.799  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:30:27.818  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 01:30:27.819  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:30:27.850  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 01:30:27.850  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:30:27.851  4251  4270 D BtGatt.ScanManager: stopping BLe Batch
,09-08 01:30:27.877  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 01:30:27.877  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:30:27.878  4251  4270 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:30:27.904  4251  4267 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 01:30:27.904  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:30:28.285  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 01:30:28.285  3846  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:30:28.286  3846  3846 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 01:30:30.784  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:30:30.785  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:30:30.785  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:30:30.787  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 01:30:30.787  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:30.787  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:30:30.788  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 01:30:30.788  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a88ee removed from the list
09-08 01:30:30.789  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:30:30.789  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c9018f removed from the list
09-08 01:30:30.789  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:30:30.789  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:30.791  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:30.791  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:30.795  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:30.795  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 01:30:30.795  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:30:30.796  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c9018f not in the list
09-08 01:30:30.796  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:30:30.796  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:30.800  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 01:30:30.800  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:30.800  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:30:30.801  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c9018f not in the list
09-08 01:30:30.801  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:30:30.801  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:30.801  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:30.802  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a88ee not in the list
,09-08 01:30:30.805  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 01:30:30.805  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef2e08 added. We now have 3 listener(s)
,09-08 01:30:30.810  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 01:30:30.811  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 01:30:30.811  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 01:30:30.811  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 01:30:30.812  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0d39a1 added. We now have 4 listener(s)
09-08 01:30:30.812  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:30:30.813  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 01:30:30.819  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:30:30.831  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:30:30.831  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:30.831  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:30.831  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:30.831  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:30.831  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:30.831  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:30:30.831  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:30:30.835  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:30:30.836  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK,
,09-08 01:30:30.836  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 01:30:30.839  3846  3898 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-08 01:30:30.840  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-08 01:30:30.840  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:30.844  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 01:30:30.844  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 01:30:30.845  3846  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 01:30:30.845  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 01:30:30.848  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:30:30.849  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 01:30:30.850  3846  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 01:30:30.850  3846  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 01:30:30.850  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 01:30:30.850  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 01:30:30.850  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-08 01:30:30.851  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-08 01:30:30.851  3846  3846 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 01:30:30.854  3846  4345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 01:30:30.858  3846  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 01:30:30.858  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 01:30:30.862  3846  4345 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 01:30:30.865  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 01:30:30.866  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 01:30:30.867  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 01:30:30.869  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 01:30:30.870  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 01:30:30.871  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-08 01:30:30.872  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 01:30:30.873  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 01:30:30.873  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 01:30:30.874  3846  3898 D BluetoothAdapter: STATE_ON
,09-08 01:30:30.878  4251  4279 D BtGatt.GattService: registerClient() - UUID=cf1314e3-82af-4df5-b679-9d16721b3dc4
,09-08 01:30:30.878  4251  4267 D BtGatt.GattService: onClientRegistered() - UUID=cf1314e3-82af-4df5-b679-9d16721b3dc4, clientIf=5
09-08 01:30:30.879  3846  3897 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 01:30:30.882  4251  4269 D BtGatt.AdvertiseManager: message : 0
,09-08 01:30:30.886  4251  4269 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 01:30:30.897  4251  4267 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 01:30:30.908  4251  4267 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 01:30:30.910  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 01:30:30.910  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 01:30:30.914  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 01:30:30.916  3846  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 01:30:30.917  3846  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 01:30:30.917  3846  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 01:30:30.917  3846  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 01:30:30.918  3846  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 01:30:30.918  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 01:30:30.921  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 01:30:30.926  3846  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 01:30:30.927  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 01:30:31.428  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 01:30:31.428  3846  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 01:30:31.429  3846  3846 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 01:30:33.923  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:30:33.923  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-08 01:30:33.924  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 01:30:33.924  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-08 01:30:33.924  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 01:30:33.925  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 01:30:33.925  3846  4345 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 01:30:33.925  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 01:30:33.926  3846  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 01:30:33.926  3846  4345 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 01:30:33.926  3846  4345 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 01:30:33.927  3846  3846 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 01:30:33.927  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 01:30:33.927  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 01:30:33.928  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 01:30:33.928  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 01:30:33.928  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 01:30:33.931  3846  3898 D BluetoothAdapter: STATE_ON
09-08 01:30:33.931  3846  3898 D BluetoothLeScanner: could not find callback wrapper
09-08 01:30:33.931  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 01:30:33.932  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 01:30:33.934  4251  4269 D BtGatt.AdvertiseManager: message : 1
09-08 01:30:33.936  4251  4269 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 01:30:33.945  4251  4267 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-08 01:30:33.946  4251  4267 D BtGatt.GattService: Client app is not null!
,09-08 01:30:33.948  4251  4288 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 01:30:33.949  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 01:30:33.949  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-08 01:30:33.950  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 01:30:33.950  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 01:30:33.950  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 01:30:33.952  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 01:30:33.953  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 01:30:33.953  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 01:30:33.953  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 01:30:33.955  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 01:30:33.955  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:33.955  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:30:33.955  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 01:30:33.955  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef2e08 removed from the list
09-08 01:30:33.955  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:30:33.955  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0d39a1 removed from the list
09-08 01:30:33.955  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 01:30:33.955  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:33.956  3846  3846 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 01:30:33.956  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:30:33.956  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 01:30:33.956  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 01:30:33.957  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:33.957  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-08 01:30:33.960  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:33.960  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 01:30:33.960  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:30:33.961  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0d39a1 not in the list
09-08 01:30:33.961  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:33.961  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:33.963  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:30:33.963  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:33.963  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:30:33.963  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0d39a1 not in the list
09-08 01:30:33.963  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:30:33.963  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:30:33.963  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:33.963  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef2e08 not in the list
09-08 01:30:33.965  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 01:30:33.965  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5479a52 added. We now have 3 listener(s)
09-08 01:30:33.968  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 01:30:33.968  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 01:30:33.968  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 01:30:33.968  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 01:30:33.968  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dede123 added. We now have 4 listener(s)
09-08 01:30:33.968  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 01:30:33.969  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 01:30:33.972  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:30:33.980  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:30:33.980  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:33.980  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:33.980  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:33.980  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:33.980  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:33.980  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:30:33.980  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 01:30:33.984  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:33.985  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 01:30:33.985  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 01:30:33.986  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 01:30:33.986  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 01:30:33.986  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 01:30:33.987  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 01:30:33.989  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:30:33.992  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:30:33.994  3846  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 01:30:33.995  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 01:30:33.999  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 01:30:34.000  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 01:30:34.000  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 01:30:34.006  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 01:30:34.006  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 01:30:34.006  3846  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 01:30:34.007  3846  3898 D BluetoothAdapter: STATE_ON
09-08 01:30:34.011  4251  4287 D BtGatt.GattService: registerClient() - UUID=a1aa1a3a-6f6b-4f3e-b243-06be4a8311ee
09-08 01:30:34.011  4251  4267 D BtGatt.GattService: onClientRegistered() - UUID=a1aa1a3a-6f6b-4f3e-b243-06be4a8311ee, clientIf=5
09-08 01:30:34.012  3846  3858 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 01:30:34.013  4251  4279 D BtGatt.GattService: start scan with filters
,09-08 01:30:34.018  4251  4270 D BtGatt.ScanManager: handling starting scan
09-08 01:30:34.018  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 01:30:34.018  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 01:30:34.019  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 01:30:34.019  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 01:30:34.027  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 01:30:34.027  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 01:30:34.027  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 01:30:34.029  4251  4267 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 01:30:34.030  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:30:34.030  4251  4270 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 01:30:34.033  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 01:30:34.038  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 01:30:34.039  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:30:34.039  4251  4270 D BtGatt.ScanManager: Starting BLE batch scan
09-08 01:30:34.039  4251  4270 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 01:30:34.054  4251  4267 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 01:30:34.055  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:30:34.063  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 01:30:34.063  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 01:30:34.457  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 01:30:34.527  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 01:30:34.528  3846  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 01:30:34.528  3846  3846 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 01:30:35.570  4251  4251 D BtGatt.ScanManager: awakened up at time 233557
,09-08 01:30:35.572  4251  4270 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:30:35.624  4251  4267 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-08 01:30:35.624  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:30:35.625  4251  4267 D BtGatt.GattService: current time is 233612382511
,09-08 01:30:35.626  4251  4267 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -91, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -95, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -84, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 01:30:35.631  4251  4267 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 01:30:35.633  4251  4267 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 01:30:35.633  4251  4267 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 01:30:35.634  4251  4267 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 01:30:35.635  4251  4267 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 01:30:37.049  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 01:30:37.050  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 01:30:37.050  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 01:30:37.050  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:30:37.051  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 01:30:37.051  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 01:30:37.051  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 01:30:37.051  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 01:30:37.052  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 01:30:37.052  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 01:30:37.053  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 01:30:37.055  3846  3898 D BluetoothAdapter: STATE_ON
,09-08 01:30:37.057  4251  4288 D BtGatt.GattService: stopScan() - queue size =1
,09-08 01:30:37.059  4251  4287 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 01:30:37.060  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 01:30:37.061  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 01:30:37.061  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 01:30:37.061  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 01:30:37.062  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 01:30:37.065  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 01:30:37.066  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 01:30:37.066  3846  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 01:30:37.067  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 01:30:37.069  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:30:37.070  4251  4251 D BtGatt.ScanManager: awakened up at time 235057
,09-08 01:30:37.073  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:30:37.073  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:30:37.073  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:37.073  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 01:30:37.073  3846  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 01:30:37.073  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 01:30:37.074  3846  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 01:30:37.074  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5479a52 removed from the list
09-08 01:30:37.074  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:30:37.074  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dede123 removed from the list
09-08 01:30:37.075  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:30:37.075  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:37.077  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:37.078  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:37.080  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:37.080  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:30:37.080  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 01:30:37.081  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dede123 not in the list
09-08 01:30:37.081  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:37.081  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:37.084  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 01:30:37.084  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:37.084  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 01:30:37.085  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:30:37.085  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:30:37.085  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dede123 not in the list
09-08 01:30:37.085  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 01:30:37.085  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:37.086  4251  4270 D BtGatt.ScanManager: stopping BLe Batch
09-08 01:30:37.086  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:37.086  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5479a52 not in the list
,09-08 01:30:37.088  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 01:30:37.088  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eae144c added. We now have 3 listener(s)
,09-08 01:30:37.091  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 01:30:37.091  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 01:30:37.091  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 01:30:37.092  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 01:30:37.092  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@915fc95 added. We now have 4 listener(s)
09-08 01:30:37.092  3846  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 01:30:37.092  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 01:30:37.095  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 01:30:37.097  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 01:30:37.097  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-08 01:30:37.098  4251  4270 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 01:30:37.101  3846  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 01:30:37.101  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 01:30:37.101  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 01:30:37.101  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 01:30:37.101  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 01:30:37.101  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 01:30:37.101  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 01:30:37.101  3846  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 01:30:37.103  3846  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 01:30:37.104  3846  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 01:30:37.104  3846  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 01:30:37.104  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 01:30:37.104  3846  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 01:30:37.104  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:30:37.104  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:37.104  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 01:30:37.104  3846  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 01:30:37.104  3846  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eae144c removed from the list
09-08 01:30:37.105  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:30:37.105  3846  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@915fc95 removed from the list
09-08 01:30:37.108  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 01:30:37.112  4251  4267 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-08 01:30:37.112  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 01:30:37.112  4251  4267 D BtGatt.GattService: current time is 235099701241
09-08 01:30:37.112  4251  4267 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 01:30:37.112  3846  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 01:30:37.113  4251  4267 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 01:30:37.112  3846  3898 D io.jxcore.node.ConnectivityMonitor: stop
09-08 01:30:37.113  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:37.113  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:37.113  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:37.115  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:37.115  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 01:30:37.115  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:30:37.115  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@915fc95 not in the list
09-08 01:30:37.115  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 01:30:37.115  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 01:30:37.116  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 01:30:37.116  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 01:30:37.116  3846  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 01:30:37.116  3846  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@915fc95 not in the list
09-08 01:30:37.116  3846  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 01:30:37.116  3846  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 01:30:37.117  3846  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 01:30:37.117  3846  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eae144c not in the list
09-08 01:30:37.118  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-08 01:30:37.118  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 01:30:37.118  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 01:30:37.118  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 01:30:37.118  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 01:30:37.118  3846  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 01:30:37.574  3846  3846 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 01:30:39.134  3846  4347 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,09-08 01:30:41.131  3846  3898 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 460
,09-08 01:30:41.132  3846  3898 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 460, name: My test thread name)
,09-08 01:30:41.139  3846  4348 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
,09-08 01:30:41.139  3846  4348 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: My test thread name)
,09-08 01:30:41.140  3846  4348 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 01:30:41.144  3846  3898 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 01:30:41.152  3846  4349 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: My test thread name)
,09-08 01:30:41.153  3846  4349 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 465, thread name: My test thread name): Test exception.
,09-08 01:30:41.154  3846  4349 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 465, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 01:30:41.160  3846  3898 I jxcore-log: *Native tests were executed*
09-08 01:30:41.160  3846  3898 I jxcore-log: 
,09-08 01:30:41.168  3846  3898 I jxcore-log: Unit Test app is loaded
09-08 01:30:41.168  3846  3898 I jxcore-log: 
,09-08 01:30:41.177  3846  4347 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-08 01:30:41.188  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.188  3846  3898 I jxcore-log: 
,09-08 01:30:41.195  3846  3846 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 01:30:41.200  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.200  3846  3898 I jxcore-log: 
,09-08 01:30:41.204  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.204  3846  3898 I jxcore-log: 
,09-08 01:30:41.207  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.207  3846  3898 I jxcore-log: 
,09-08 01:30:41.210  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 01:30:41.210  3846  3898 I jxcore-log: 
,09-08 01:30:41.213  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 01:30:41.213  3846  3898 I jxcore-log: 
,09-08 01:30:41.216  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.216  3846  3898 I jxcore-log: 
,09-08 01:30:41.218  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.218  3846  3898 I jxcore-log: 
,09-08 01:30:41.219  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 01:30:41.219  3846  3898 I jxcore-log: 
,09-08 01:30:41.221  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 01:30:41.221  3846  3898 I jxcore-log: 
,09-08 01:30:41.222  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 01:30:41.222  3846  3898 I jxcore-log: 
,09-08 01:30:41.223  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.223  3846  3898 I jxcore-log: 
,09-08 01:30:41.224  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.224  3846  3898 I jxcore-log: 
,09-08 01:30:41.225  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.225  3846  3898 I jxcore-log: 
,09-08 01:30:41.227  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.227  3846  3898 I jxcore-log: 
,09-08 01:30:41.228  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 01:30:41.228  3846  3898 I jxcore-log: 
,09-08 01:30:41.230  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 01:30:41.230  3846  3898 I jxcore-log: 
,09-08 01:30:41.231  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 01:30:41.231  3846  3898 I jxcore-log: 
,09-08 01:30:41.232  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.232  3846  3898 I jxcore-log: 
,09-08 01:30:41.233  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.233  3846  3898 I jxcore-log: 
,09-08 01:30:41.234  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.234  3846  3898 I jxcore-log: 
,09-08 01:30:41.235  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 01:30:41.235  3846  3898 I jxcore-log: 
09-08 01:30:41.236  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 01:30:41.236  3846  3898 I jxcore-log: 
09-08 01:30:41.237  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 01:30:41.237  3846  3898 I jxcore-log: 
09-08 01:30:41.237  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.237  3846  3898 I jxcore-log: 
09-08 01:30:41.238  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.238  3846  3898 I jxcore-log: 
09-08 01:30:41.239  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.239  3846  3898 I jxcore-log: 
,09-08 01:30:41.242  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.242  3846  3898 I jxcore-log: 
,09-08 01:30:41.244  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.244  3846  3898 I jxcore-log: 
,09-08 01:30:41.246  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.246  3846  3898 I jxcore-log: 
,09-08 01:30:41.249  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.249  3846  3898 I jxcore-log: 
,09-08 01:30:41.251  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.251  3846  3898 I jxcore-log: 
,09-08 01:30:41.253  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.253  3846  3898 I jxcore-log: 
,09-08 01:30:41.255  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.255  3846  3898 I jxcore-log: 
,09-08 01:30:41.258  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.258  3846  3898 I jxcore-log: 
,09-08 01:30:41.260  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.260  3846  3898 I jxcore-log: 
,09-08 01:30:41.260  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.260  3846  3898 I jxcore-log: 
,09-08 01:30:41.261  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.261  3846  3898 I jxcore-log: 
,09-08 01:30:41.262  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 01:30:41.262  3846  3898 I jxcore-log: 
,09-08 01:30:41.263  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 01:30:41.263  3846  3898 I jxcore-log: 
,09-08 01:30:41.264  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 01:30:41.264  3846  3898 I jxcore-log: 
09-08 01:30:41.264  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.264  3846  3898 I jxcore-log: 
,09-08 01:30:41.265  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.265  3846  3898 I jxcore-log: 
,09-08 01:30:41.266  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.266  3846  3898 I jxcore-log: 
,09-08 01:30:41.267  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.267  3846  3898 I jxcore-log: 
,09-08 01:30:41.267  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.267  3846  3898 I jxcore-log: 
,09-08 01:30:41.268  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 01:30:41.268  3846  3898 I jxcore-log: 
,09-08 01:30:41.269  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.269  3846  3898 I jxcore-log: 
09-08 01:30:41.270  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 01:30:41.270  3846  3898 I jxcore-log: 
,09-08 01:30:41.271  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.271  3846  3898 I jxcore-log: 
,09-08 01:30:41.271  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 01:30:41.271  3846  3898 I jxcore-log: 
,09-08 01:30:41.272  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 01:30:41.272  3846  3898 I jxcore-log: 
,09-08 01:30:41.273  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 01:30:41.273  3846  3898 I jxcore-log: 
,09-08 01:30:41.274  3846  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 01:30:41.274  3846  3898 I jxcore-log: 
,09-08 01:30:41.278  3846  3898 I jxcore-log: My device name is: motorola-Nexus 6
09-08 01:30:41.278  3846  3898 I jxcore-log: 
,09-08 01:30:43.614  3846  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 01:30:43.614  3846  3898 I jxcore-log: 
,09-08 01:30:43.751  3846  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 01:30:43.751  3846  3898 I jxcore-log: 
,09-08 01:30:43.774  3846  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 01:30:43.774  3846  3898 I jxcore-log: 
,09-08 01:30:45.068  3846  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 01:30:45.068  3846  3898 I jxcore-log: 
,09-08 01:30:45.267  3846  3898 I jxcore-log: ERROR runTests: 
09-08 01:30:45.267  3846  3898 I jxcore-log: 
,09-08 01:30:45.269  3846  3898 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
09-08 01:30:45.269  3846  3898 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,09-08 01:30:45.283  3846  3898 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _functionName: 'loadFile',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _lineNumber: '26',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _columnNumber: '11',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
09-08 01:30:45.283  3846  3898 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _functionName: '',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _lineNumber: '38',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _columnNumber: '7',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
09-08 01:30:45.283  3846  3898 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _functionName: '',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _lineNumber: '35',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _columnNumber: '3',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
09-08 01:30:45.283  3846  3898 I jxcore-log:   { _fileName: 'module.js',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _functionName: '$w.prototype._compile',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _lineNumber: '621',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _columnNumber: '8',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
09-08 01:30:45.283  3846  3898 I jxcore-log:   { _fileName: 'module.js',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _functionName: '$w._extensions[".js"]',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _lineNumber: '651',
09-08 01:30:45.283  3846  3898 I jxcore-log:     _columnNumber: '1',
09-08 01:30:45.283  3846  3898 I jxcore-log:    
09-08 01:30:45.284  3846  3898 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-08 01:30:45.284  3846  3898 I jxcore-log: 
,09-08 01:30:45.284  3846  3898 E jxcore-log: Error: 
09-08 01:30:45.284  3846  3898 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
09-08 01:30:45.284  3846  3898 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
09-08 01:30:45.284  3846  3898 E jxcore-log: 
,09-08 01:30:45.566   872  4308 D NetlinkSocketObserver: NeighborEvent{elapsedMs=243553, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 01:30:45.940  4350  4350 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-08 01:30:45.945  4350  4350 D AndroidRuntime: CheckJNI is OFF
,09-08 01:30:45.987  4350  4350 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-08 01:30:46.036  4350  4350 I Radio-JNI: register_android_hardware_Radio DONE
,09-08 01:30:46.058  4350  4350 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-08 01:30:46.069   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-08 01:30:46.070   872   885 I ActivityManager: Killing 3846:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-08 01:30:46.164   872  1700 D GraphicsStats: Buffer count: 2
,09-08 01:30:46.164   872   883 I WindowState: WIN DEATH: Window{d0c5003 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 01:30:46.165   872  1315 D WifiService: Client connection lost with reason: 4
,09-08 01:30:46.186   872   895 W PackageSettings: Skipping PackageSetting{f42dca5 com.example.hello/10273} due to missing metadata
,09-08 01:30:46.223   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-08 01:30:46.223   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-08 01:30:46.223   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-08 01:30:46.223   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-08 01:30:46.223   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:30:46.223   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.223   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 01:30:46.223   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-08 01:30:46.224   872   885 I ActivityManager:   Force finishing activity ActivityRecord{7f23508 u0 com.test.thalitest/.MainActivity t4}
,09-08 01:30:46.225   872   895 I art     : Starting a blocking GC Explicit
09-08 01:30:46.229   872  1700 W ActivityManager: Spurious death for ProcessRecord{eaf4b2d 0:com.test.thalitest/u0a0}, curProc for 3846: null
,09-08 01:30:46.266   872   895 I art     : Explicit concurrent mark sweep GC freed 22240(1411KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 774us total 40.715ms
,09-08 01:30:46.289   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-08 01:30:46.292  4350  4350 I art     : System.exit called, status: 0
09-08 01:30:46.292  4350  4350 I AndroidRuntime: VM exiting with result code 0.
,09-08 01:30:46.295   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-08 01:30:46.306   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-08 01:30:46.311  4251  4251 D BluetoothMapAppObserver: onReceive
09-08 01:30:46.311  4251  4251 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 01:30:46.311   872  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 01:30:46.312  1882  1882 I Keyboard.Facilitator: resetDictionaries() : en_US
09-08 01:30:46.313  2144  2293 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 01:30:46.314  3712  3712 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-08 01:30:46.330  1882  4361 I Keyboard.Facilitator.DecoderInitializer: run()
,09-08 01:30:46.342  1882  4361 I Decoder : createOrResetDecoder
,09-08 01:30:46.344   872  1992 I ActivityManager: Start proc 4363:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-08 01:30:46.347  1947  1947 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-08 01:30:46.381  4363  4363 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-08 01:30:46.385  1516  1516 I ConfigService: onCreate
,09-08 01:30:46.388   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-08 01:30:46.410   872  1964 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3846 uid 10000
,09-08 01:30:46.411  1882  1882 I Keyboard.Facilitator: onFinishInput()
,09-08 01:30:46.416  1882  4361 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-08 01:30:46.450  1882  4361 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-08 01:30:46.451  1882  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-08 01:30:46.451  1882  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-08 01:30:46.453  1882  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-08 01:30:46.453  1882  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-08 01:30:46.454  1882  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 01:30:46.454  1882  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-08 01:30:46.455  1882  4361 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-08 01:30:46.455  1882  4361 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 01:30:46.458  1882  4361 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 01:30:46.458  1882  4361 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-08 01:30:46.458  1882  4361 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-08 01:30:46.458  1882  4361 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-08 01:30:46.476  1966  2059 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-08 01:30:46.478  4363  4363 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-08 01:30:46.479   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-08 01:30:46.480   872   884 E PackageManager: Failed to write settings, restoring backup
09-08 01:30:46.480   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-08 01:30:46.480   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-08 01:30:46.480   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-08 01:30:46.480   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 01:30:46.480   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 01:30:46.480   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:30:46.480   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.480   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 01:30:46.484   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-08 01:30:46.484   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 01:30:46.484   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 01:30:46.484   872   885 E DropBoxManagerService: 	... 13 more
,09-08 01:30:46.484  4363  4379 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.484  4363  4379 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.o,penInner(SQLiteDatabase.java:806)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.485  4363  4379 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 01:30:46.491   872  1624 I ActivityManager: Start proc 4381:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-08 01:30:46.491  1966  2059 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 01:30:46.491  1966  2059 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1966
09-08 01:30:46.491  1966  2059 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.491  1966  2059 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: Can't write: system_app_crash
09-08 01:30:46.494   872  4387 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 01:30:46.494   872  4387 E DropBoxManagerService: 	... 5 more
09-08 01:30:46.494   872  3122 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 01:30:46.512  4363  4389 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-08 01:30:46.513   872  1963 I ActivityManager: Start proc 4396:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-08 01:30:46.517  1966  2059 I Process : Sending signal. PID: 1966 SIG: 9
,09-08 01:30:46.550  4396  4396 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-08 01:30:46.573  1516  1516 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-08 01:30:46.575  1516  1516 D AndroidRuntime: Shutting down VM
09-08 01:30:46.576  1516  1516 E AndroidRuntime: FATAL EXCEPTION: main
09-08 01:30:46.576  1516  1516 E AndroidRuntime: Process: com.google.process.gapps, PID: 1516
09-08 01:30:46.576  1516  1516 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 01:30:46.576  1516  1516 E AndroidRuntime: 	... 8 more
,09-08 01:30:46.580   872  4413 E DropBoxManagerService: Can't write: system_app_crash
09-08 01:30:46.580   872  4413 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 01:30:46.580   872  4413 E DropBoxManagerService: 	... 5 more
,09-08 01:30:46.581  1516  1516 I Process : Sending signal. PID: 1516 SIG: 9
,09-08 01:30:46.585   872  1965 D GraphicsStats: Buffer count: 1
,09-08 01:30:46.585   872  1992 I WindowState: WIN DEATH: Window{2839603 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-08 01:30:46.607   872  1965 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1966) has died
,09-08 01:30:46.607   872  1965 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-08 01:30:46.610   872  1965 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-08 01:30:46.628   872   885 I ActivityManager: Start proc 4414:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 01:30:46.646   872   890 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
,09-08 01:30:46.646   872   890 W DisplayManagerService: Failed to notify process 1516 that displays changed, assuming it died.
09-08 01:30:46.646   872   890 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 01:30:46.646   872   890 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-08 01:30:46.651   872  1315 D WifiService: Client connection lost with reason: 4
,09-08 01:30:46.660   872  1964 I ActivityManager: Process com.google.process.gapps (pid 1516) has died
,09-08 01:30:46.660   872  1964 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-08 01:30:46.660   872  1964 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-08 01:30:46.660   872  1964 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
,09-08 01:30:46.662  1743  1743 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-08 01:30:46.677   872  1965 I ActivityManager: Start proc 4428:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-08 01:30:46.683  4414  4414 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:30:46.683  4414  4414 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 01:30:46.683  4414  4414 D AndroidRuntime: Shutting down VM
,09-08 01:30:46.692  4414  4414 E AndroidRuntime: FATAL EXCEPTION: main
09-08 01:30:46.692  4414  4414 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4414
09-08 01:30:46.692  4414  4414 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 01:30:46.692  4414  4414 E AndroidRuntime: 	... 10 more
09-08 01:30:46.693   872  3122 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 01:30:46.694  4414  4414 I Process : Sending signal. PID: 4414 SIG: 9
09-08 01:30:46.694   872  4441 E DropBoxManagerService: Can't write: system_app_crash
09-08 01:30:46.694   872  4441 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 01:30:46.694   872  4441 E DropBoxManagerService: 	... 5 more
09-08 01:30:46.702  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-08 01:30:46.702  1743  1743 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-08 01:30:46.714  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-08 01:30:46.714  1743  1743 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-08 01:30:46.730   872  1385 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
,09-08 01:30:46.731  1743  4444 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-08 01:30:46.731   872  1385 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
09-08 01:30:46.731   872  1385 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-08 01:30:46.731   872  1385 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 01:30:46.731   872  1385 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-08 01:30:46.731   872  1385 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-08 01:30:46.731   872  1385 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-08 01:30:46.731   872  1385 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-08 01:30:46.731   872  1385 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-08 01:30:46.731   872  1385 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-08 01:30:46.731   872  1385 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-08 01:30:46.731   872  1385 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 01:30:46.742  4428  4428 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-08 01:30:46.748   872  1385 I ActivityManager: Start proc 4446:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,09-08 01:30:46.749  1743  4444 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-08 01:30:46.749  1743  4444 E AndroidRuntime: Process: com.google.android.gms, PID: 1743
09-08 01:30:46.749  1743  4444 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 01:30:46.749  1743  4444 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
09-08 01:30:46.749   872  1699 W ActivityManager: Spurious death for ProcessRecord{c160185 4446:com.google.android.googlequicksearchbox/u0a28}, curProc for 4414: null
09-08 01:30:46.750  2027  4443 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-08 01:30:46.764   872  4458 E DropBoxManagerService: Can't write: system_app_crash
09-08 01:30:46.764   872  4458 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 01:30:46,.764   872  4458 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 01:30:46.764   872  4458 E DropBoxManagerService: 	... 5 more
,09-08 01:30:46.775  1743  4444 I Process : Sending signal. PID: 1743 SIG: 9
,09-08 01:30:46.793  2027  4443 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-08 01:30:46.796   279   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
