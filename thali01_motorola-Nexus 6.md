#### Test 81095569cb9dee4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 18:34:55.152   872  1866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=114823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 18:34:55.889  3771  3771 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 18:34:55.894  3771  3771 D AndroidRuntime: CheckJNI is OFF
08-23 18:34:55.931  3771  3771 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 18:34:55.975  3771  3771 I Radio-JNI: register_android_hardware_Radio DONE
08-23 18:34:55.996  3771  3771 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 18:34:56.000   872  1971 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 18:34:56.055  1989  2393 W SearchService: Abort, client detached.
08-23 18:34:56.058  3771  3771 D AndroidRuntime: Shutting down VM
08-23 18:34:56.060  1989  1989 I HotwordDetector: Closing mic
08-23 18:34:56.060  1989  2325 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@43f986
08-23 18:34:56.061  1989  2331 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 18:34:56.076   872  1901 I ActivityManager: Start proc 3780:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 18:34:56.129   374  2333 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 18:34:56.130   374  2333 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 18:34:56.138   374  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 18:34:56.140  1989  2330 I MicroRecognitionRnrImpl: Detection finished
08-23 18:34:56.141  1989  2328 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 18:34:56.188  3780  3780 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 18:34:56.213  3780  3780 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 18:34:56.219  3780  3780 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5889-5891)
08-23 18:34:56.220  3780  3780 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 18:34:56.234  3780  3780 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {932a6e0}
08-23 18:34:56.235  3780  3780 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 18:34:56.235  3780  3780 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 18:34:56.240  3780  3780 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 18:34:56.242  3780  3780 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 18:34:56.257  3780  3780 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 18:34:56.266  3780  3780 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 18:34:56.266  3780  3780 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 18:34:56.267  3780  3780 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 18:34:56.267  3780  3780 I Adreno  : Build Date                       : 10/20/15
08-23 18:34:56.267  3780  3780 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 18:34:56.267  3780  3780 I Adreno  : Local Branch                     : M14
08-23 18:34:56.267  3780  3780 I Adreno  : Remote Branch                    : 
08-23 18:34:56.267  3780  3780 I Adreno  : Remote Branch                    : 
08-23 18:34:56.267  3780  3780 I Adreno  : Reconstruct Branch               : 
,08-23 18:34:56.337   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e112d95:true
,08-23 18:34:56.369  3780  3780 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 18:34:56.383  3780  3780 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 18:34:56.442  3780  3819 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 18:34:56.456  3780  3805 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 18:34:56.489  3780  3819 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 18:34:56.568   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +505ms
,08-23 18:34:56.582  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-23 18:34:56.616  3780  3780 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3780
,08-23 18:34:56.702  3780  3780 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 18:34:56.870  3780  3821 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1682769616
,08-23 18:34:56.876  3780  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 18:34:56.876  3780  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 18:34:56.876  3780  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 18:34:56.876  3780  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 18:34:56.876  3780  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 18:34:56.876  3780  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af117f7 added. We now have 1 listener(s)
,08-23 18:34:56.886  3780  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-23 18:34:56.886  3780  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 18:34:56.887  3780  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:34:56.887  3780  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 18:34:56.894  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 18:34:56.895  3780  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ae7d82 added. We now have 1 listener(s)
08-23 18:34:56.895  3780  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:34:56.899   872  1303 D WifiService: New client listening to asynchronous messages
,08-23 18:34:56.900  3780  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 18:34:56.900  3780  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 18:34:56.900  3780  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 18:34:56.900  3780  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 18:34:56.900  3780  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 18:34:56.904   872  1370 I ActivityManager: Killing 2954:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-23 18:34:56.955   872  1370 I ActivityManager: Killing 3190:com.google.android.gm/u0a78 (adj 15): empty #18
,08-23 18:34:57.014  3780  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:34:57.014  3780  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-23 18:34:57.037  3780  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 18:34:57.041  3780  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:34:57.041  3780  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:34:57.041  3780  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:34:57.041  3780  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:34:57.041  3780  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:34:57.041  3780  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:34:57.041  3780  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:34:57.041  3780  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:34:57.042  3780  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-23 18:34:57.042  3780  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:34:57.044  3780  3821 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 18:34:57.065  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:34:57.075  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:34:57.085  3780  3780 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 18:34:58.178  3780  3830 W jxcore-log: Initializing JXcore engine
08-23 18:34:58.178  3780  3830 W jxcore-log: JXcore engine is ready
,08-23 18:34:58.223  3830  3830 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-23 18:34:58.223  3830  3830 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10687]" dev="sockfs" ino=10687 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-23 18:34:58.223  3830  3830 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 18:34:58.223  3830  3830 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24341]" dev="sockfs" ino=24341 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 18:34:58.240  3780  3830 W jxcore-log: Starting JXcore engine
,08-23 18:34:58.335  3780  3830 W jxcore-log: Platform android
08-23 18:34:58.335  3780  3830 W jxcore-log: 
08-23 18:34:58.335  3780  3830 W jxcore-log: Process ARCH arm
08-23 18:34:58.335  3780  3830 W jxcore-log: 
,08-23 18:34:58.581  3780  3830 I jxcore-log: JXcore Cordova bridge is ready!
08-23 18:34:58.581  3780  3830 I jxcore-log: 
08-23 18:34:58.581  3780  3830 W jxcore-log: JXcore engine is started
,08-23 18:34:58.594  3780  3821 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 18:34:58.600  3780  3780 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 18:35:01.316  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:01.331  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:01.335  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:01.398  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 18:35:01.399  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 18:35:01.399  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 18:35:01.399  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:01.445  3491  3491 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 18:35:01.447  3491  3491 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-23 18:35:01.448  3491  3491 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-23 18:35:02.437   872  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-23 18:35:08.026  3591  3841 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 18:35:08.046  3591  3842 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 18:35:08.068  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:08.070  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:08.097  1496  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 18:35:08.097  1496  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 18:35:08.097  1496  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 18:35:08.097  1496  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:08.125  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:08.129  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:08.179  1496  2116 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 18:35:08.179  1496  2116 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 18:35:08.179  1496  2116 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 18:35:08.181  1496  2116 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:08.221  3591  3842 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 18:35:08.223  3591  3841 E BooksSync: Soft error
08-23 18:35:08.223  3591  3841 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 18:35:08.223  3591  3841 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 18:35:08.223  3591  3841 E BooksSync: Sync error
08-23 18:35:08.223  3591  3841 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 18:35:08.223  3591  3841 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 18:35:08.224  3591  3841 I BooksSync: Finished books sync
,08-23 18:35:08.234   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127653, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 18:35:08.664  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 18:35:08.664  3780  3830 I jxcore-log: 
,08-23 18:35:08.667  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 18:35:08.667  3780  3830 I jxcore-log: 
,08-23 18:35:08.677  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:08.677  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:08.677  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:08.677  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:08.677  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:08.677  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:08.677  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:08.677  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:08.683  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:08.689  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 18:35:08.689  3780  3830 I jxcore-log: 
,08-23 18:35:08.696  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 18:35:08.696  3780  3830 I jxcore-log: 
,08-23 18:35:09.212  3780  3830 D ExecuteNativeTests: Running unit tests
,08-23 18:35:09.270  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:35:09.270  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 added. We now have 2 listener(s)
08-23 18:35:09.271  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 18:35:09.271  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:09.271  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:09.271  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:09.271  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d added. We now have 2 listener(s)
08-23 18:35:09.272  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:09.272  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:09.275  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:09.292  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:09.292  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.292  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.292  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:09.292  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:09.292  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:09.292  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:09.292  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:09.295  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:09.295  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:35:09.298  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-23 18:35:09.298  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 18:35:09.298  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 18:35:09.299  3780  3830 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-23 18:35:09.300  3780  3830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 18:35:09.300  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 18:35:09.300  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:35:09.301  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-23 18:35:09.301  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.301  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.301  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.302  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.302  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.302  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:09.302  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:09.302  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 removed from the list
08-23 18:35:09.302  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.302  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d removed from the list
08-23 18:35:09.303  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:09.303  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.303  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:09.304  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.304  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:09.308  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:09.308  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:09.308  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:09.308  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
,08-23 18:35:09.309  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:09.310  3780  3830 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-23 18:35:09.311  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.311  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.311  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 18:35:09.311  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.311  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.311  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.311  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.311  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.311  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.311  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 18:35:09.311  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.311  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.311  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.311  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.312  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.312  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:09.312  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.312  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.316  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 18:35:09.317  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 18:35:09.318  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 18:35:09.318  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.318  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.318  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:,09.318  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.318  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.318  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.318  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.318  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.319  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.319  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.319  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.319  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.319  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.319  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.319  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.319  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.319  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.320  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.320  3780  3830 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 18:35:09.321  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:09.332  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:09.332  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.332  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.332  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:09.332  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:09.332  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:09.332  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:09.332  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:09.333  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:09.333  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:35:09.333  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 18:35:09.333  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 18:35:09.333  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:35:09.333  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:09.333  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:35:09.335  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.336  3780  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 18:35:09.336  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 18:35:09.339  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.340  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:09.342  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 18:35:09.342  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:09.343  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-23 18:35:09.347  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-23 18:35:09.347  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 18:35:09.347  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 18:35:09.348  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 18:35:09.348  3780  3830 D BluetoothAdapter: STATE_ON
08-23 18:35:09.351  2683  2879 D BtGatt.GattService: registerClient() - UUID=e9b6ce16-cf04-4ce5-a574-18637ca4c142
08-23 18:35:09.353  2683  2734 D BtGatt.GattService: onClientRegistered() - UUID=e9b6ce16-cf04-4ce5-a574-18637ca4c142, clientIf=5
08-23 18:35:09.355  3780  3792 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 18:35:09.356  2683  2697 D BtGatt.GattService: start scan with filters
08-23 18:35:09.358  2683  2739 D BtGatt.ScanManager: handling starting scan
08-23 18:35:09.360  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 18:35:09.361  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 18:35:09.361  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:09.362  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 18:35:09.365  2683  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:09.369  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:09.369  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:09.370  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 18:35:09.372  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:09.377  2683  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 18:35:09.377  3780  3830 I io.jxcore.node.ConnectionHelper: start: OK
08-23 18:35:09.377  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:09.378  2683  2739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-23 18:35:09.380  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.380  3780  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 18:35:09.380  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.380  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 18:35:09.380  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.380  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 18:35:09.380  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 18:35:09.380  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:09.380  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:09.380  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:35:09.381  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:09.381  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 18:35:09.381  3780  3830 D BluetoothAdapter: STATE_ON
,08-23 18:35:09.382  2683  2696 D BtGatt.GattService: stopScan() - queue size =1
08-23 18:35:09.382  2683  2697 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 18:35:09.382  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 18:35:09.382  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 18:35:09.382  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 18:35:09.382  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 18:35:09.382  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 18:35:09.389  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:09.390  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 18:35:09.390  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 18:35:09.390  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:35:09.391  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:09.391  2683  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 18:35:09.391  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.392  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.392  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.392  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 18:35:09.392  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:09.392  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.392  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.392  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:09.392  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.392  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.392  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.392  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:09.392  2683  2739 D BtGatt.ScanManager: Starting BLE batch scan
08-23 18:35:09.392  2683  2739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 18:35:09.392  3780  3830 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 18:35:09.393  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:09.397  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:09.397  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.397  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.397  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:09.397  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:09.397  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:09.397  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:09.397  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:09.399  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:09.400  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:09.400  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 18:35:09.401  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:09.401  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 18:35:09.401  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:09.401  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:35:09.403  2683  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 18:35:09.403  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.404  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.408  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.415  3780  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 18:35:09.415  2683  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 18:35:09.415  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 18:35:09.415  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:09.419  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:09.420  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 18:35:09.420  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:09.422  2683  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 18:35:09.422  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.422  2683  2739 D BtGatt.ScanManager: stopping BLe Batch
,08-23 18:35:09.424  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 18:35:09.424  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 18:35:09.424  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 18:35:09.425  3780  3830 D BluetoothAdapter: STATE_ON
,08-23 18:35:09.428  2683  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 18:35:09.429  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.429  2683  2739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 18:35:09.429  2683  2696 D BtGatt.GattService: registerClient() - UUID=d03e4d76-e120-4f85-8b36-692269972e9e
08-23 18:35:09.430  2683  2734 D BtGatt.GattService: onClientRegistered() - UUID=d03e4d76-e120-4f85-8b36-692269972e9e, clientIf=5
,08-23 18:35:09.430  3780  3791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 18:35:09.430  2683  2697 D BtGatt.GattService: start scan with filters
,08-23 18:35:09.435  2683  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 18:35:09.435  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:09.435  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 18:35:09.435  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 18:35:09.435  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:09.435  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 18:35:09.437  2683  2739 D BtGatt.ScanManager: handling starting scan
,08-23 18:35:09.438  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:09.438  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 18:35:09.439  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:09.441  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:09.443  2683  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 18:35:09.443  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:09.443  2683  2739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 18:35:09.445  3780  3830 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 18:35:09.447  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-23 18:35:09.447  3780  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 18:35:09.447  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-23 18:35:09.447  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-23 18:35:09.447  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.448  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 18:35:09.448  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 18:35:09.448  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:09.448  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-23 18:35:09.448  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 18:35:09.448  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:09.448  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 18:35:09.449  3780  3830 D BluetoothAdapter: STATE_ON
,08-23 18:35:09.449  2683  2879 D BtGatt.GattService: stopScan() - queue size =1
,08-23 18:35:09.450  2683  2696 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 18:35:09.450  2683  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-23 18:35:09.450  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:35:09.450  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:09.450  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 18:35:09.450  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 18:35:09.450  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 18:35:09.450  2683  2739 D BtGatt.ScanManager: Starting BLE batch scan
08-23 18:35:09.450  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 18:35:09.450  2683  2739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 18:35:09.451  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:09.451  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 18:35:09.451  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 18:35:09.451  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 18:35:09.452  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:09.452  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.452  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.452  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:09.452  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:09.453  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 18:35:09.453  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.453  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:09.453  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:09.453  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.453  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.453  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.453  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.453  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.454  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.454  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.454  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.454  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.455  3780  3830 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 18:35:09.457  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:09.460  2683  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 18:35:09.461  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.461  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:09.461  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.461  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.461  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:09.461  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:09.461  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:09.461  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:09.461  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:09.463  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:09.463  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:09.463  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:09.463  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:09.463  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:35:09.463  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:09.463  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:35:09.465  2683  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 18:35:09.465  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.466  3780  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 18:35:09.466  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 18:35:09.466  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:09.470  2683  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 18:35:09.470  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 18:35:09.470  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.470  2683  2739 D BtGatt.ScanManager: stopping BLe Batch
08-23 18:35:09.470  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 18:35:09.470  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 18:35:09.472  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.475  2683  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-23 18:35:09.475  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 18:35:09.475  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 18:35:09.475  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 18:35:09.475  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.475  2683  2739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-23 18:35:09.475  3780  3830 D BluetoothAdapter: STATE_ON
08-23 18:35:09.477  2683  2879 D BtGatt.GattService: registerClient() - UUID=8c51c967-1c08-4f0a-b5d5-babefc49c7fc
,08-23 18:35:09.478  2683  2734 D BtGatt.GattService: onClientRegistered() - UUID=8c51c967-1c08-4f0a-b5d5-babefc49c7fc, clientIf=5
08-23 18:35:09.479  3780  3792 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 18:35:09.479  2683  2696 D BtGatt.GattService: start scan with filters
08-23 18:35:09.481  2683  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 18:35:09.482  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.482  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 18:35:09.482  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 18:35:09.482  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:09.482  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 18:35:09.484  2683  2739 D BtGatt.ScanManager: handling starting scan
,08-23 18:35:09.485  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:09.485  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 18:35:09.485  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 18:35:09.486  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:09.488  2683  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 18:35:09.488  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.488  3780  3830 I io.jxcore.node.ConnectionHelper: start: OK
08-23 18:35:09.489  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.489  3780  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 18:35:09.489  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.489  2683  2739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-23 18:35:09.489  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 18:35:09.489  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.489  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 18:35:09.489  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 18:35:09.489  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:09.489  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:09.489  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 18:35:09.489  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:09.489  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 18:35:09.490  3780  3830 D BluetoothAdapter: STATE_ON
08-23 18:35:09.490  2683  2879 D BtGatt.GattService: stopScan() - queue size =1
08-23 18:35:09.491  2683  2697 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-23 18:35:09.491  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:35:09.491  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 18:35:09.491  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 18:35:09.491  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 18:35:09.491  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 18:35:09.492  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:09.493  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 18:35:09.493  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 18:35:09.493  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 18:35:09.493  2683  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-23 18:35:09.493  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:09.493  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.494  2683  2739 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 18:35:09.494  2683  2739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 18:35:09.494  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:09.495  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.495  3780  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 18:35:09.495  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.495  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.495  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.495  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 18:35:09.495  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.495  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:09.495  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.495  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:09.495  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:09.495  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
,08-23 18:35:09.495  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.495  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.496  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.496  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.496  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.496  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.496  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:09.497  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.497  3780  3830 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-23 18:35:09.497  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.498  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:35:09.498  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.498  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.498  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.498  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.498  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
,08-23 18:35:09.498  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.498  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.498  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.498  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.498  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.498  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.498  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.502  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.502  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:09.502  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.502  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.502  2683  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-23 18:35:09.503  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 18:35:09.503  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.503  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 18:35:09.503  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.503  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.503  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.503  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.503  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.503  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.503  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.503  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
,08-23 18:35:09.503  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.503  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.503  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:09.503  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.503  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.504  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:09.504  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.504  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.504  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.505  3780  3830 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-23 18:35:09.505  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.505  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.505  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.505  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.505  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.505  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.506  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.506  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.506  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.506  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.506  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.506  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:09.506  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:09.506  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.507  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:09.507  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.507  2683  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 18:35:09.507  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.507  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.507  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
,08-23 18:35:09.507  3780  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-23 18:35:09.508  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 18:35:09.508  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:35:09.508  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.508  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 18:35:09.508  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.508  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:09.508  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.508  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:09.508  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.508  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 18:35:09.509  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.509  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:09.509  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.509  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:09.510  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:09.510  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:09.510  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.510  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
,08-23 18:35:09.510  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-23 18:35:09.512  2683  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 18:35:09.512  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 18:35:09.512  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:09.512  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 18:35:09.512  2683  2739 D BtGatt.ScanManager: stopping BLe Batch
,08-23 18:35:09.512  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:35:09.512  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 18:35:09.512  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 18:35:09.513  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.513  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:35:09.513  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.513  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.513  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.513  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.513  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.513  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.513  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.514  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.514  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.514  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.514  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.514  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.515  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.515  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.515  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.515  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.516  3780  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:09.516  3780  3830 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 18:35:09.516  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 18:35:09.517  2683  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-23 18:35:09.517  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.518  2683  2739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-23 18:35:09.522  2683  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-23 18:35:09.522  2683  2734 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:09.525  3780  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:09.525  3780  3830 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 18:35:09.525  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 18:35:09.525  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: clos,eAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 18:35:09.526  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 18:35:09.527  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 18:35:09.528  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 18:35:09.528  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 18:35:09.528  3780  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-23 18:35:09.528  3780  3830 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 18:35:09.528  3780  3830 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-23 18:35:09.528  3780  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:09.528  3780  3830 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 18:35:09.528  3780  3830 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 18:35:09.529  3780  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:09.529  3780  3830 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 18:35:09.529  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-23 18:35:09.532  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-23 18:35:09.532  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 18:35:09.532  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-23 18:35:09.533  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 18:35:09.533  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 18:35:09.533  3780  3830 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 18:35:09.533  3780  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:09.533  3780  3830 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-23 18:35:09.533  3780  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-23 18:35:09.534  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.534  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.534  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.534  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.534  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.534  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.535  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-23 18:35:09.536  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.536  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.536  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.536  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.536  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.536  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.536  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.536  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.536  3780  3844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:35:09.536  3780  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-23 18:35:09.536  3780  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
08-23 18:35:09.536  3780  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
08-23 18:35:09.537  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.537  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.537  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.537  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.538  3780  3830 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-23 18:35:09.538  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.538  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.538  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.538  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.538  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.538  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.539  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.539  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.539  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.539  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.539  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.539  3780  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-23 18:35:09.539  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.539  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.539  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.540  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.540  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.540  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.540  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.540  3780  3830 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-23 18:35:09.541  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.541  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.541  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.541  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.541  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.541  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.541  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.543  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.543  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.543  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.545  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.545  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.545  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.545  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.545  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.546  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.546  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.546  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.546  3780  3830 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-23 18:35:09.546  3780  3830 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 18:35:09.546  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 18:35:09.546  3780  3830 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 18:35:09.546  3780  3830 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 18:35:09.546  3780  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 18:35:09.547  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 18:35:09.547  3780  3830 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 18:35:09.547  3780  3830 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 18:35:09.547  3780  3830 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 18:35:09.547  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 18:35:09.547  3780  3830 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 18:35:09.547  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.547  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.547  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.547  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.547  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.547  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.547  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.547  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.547  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.547  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.547  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.547  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.547  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.548  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.548  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.548  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.548  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.548  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.549  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.549  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.549  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.549  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.549  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.549  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.549  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.549  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.549  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.549  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.549  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.549  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.549  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.550  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.550  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.550  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.550  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.550  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.550  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.550  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.550  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.550  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.550  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.550  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.550  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.550  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.550  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.550  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.550  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.551  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.551  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.551  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.551  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.552  3780  3830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 18:35:09.552  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:09.553  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-23 18:35:09.553  3780  3830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 18:35:09.553  3780  3830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-23 18:35:09.554  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 18:35:09.554  3780  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 18:35:09.554  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 18:35:09.554  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.554  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-23 18:35:09.554  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 18:35:09.554  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 18:35:09.554  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.554  3780  3830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-23 18:35:09.554  3780  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 18:35:09.554  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.554  3780  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 18:35:09.554  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.554  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:09.554  3780  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 18:35:09.554  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:09.554  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:35:09.554  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.554  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.555  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:09.555  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.555  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.555  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.555  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:09.555  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.555  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.555  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:09.555  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.556  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:09.556  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.556  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.556  3780  3780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 18:35:09.556  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.556  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.556  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.556  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.556  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.556  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.556  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.557  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.557  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.557  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.557  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.558  3780  3830 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-23 18:35:09.558  3780  3830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 18:35:09.558  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 18:35:09.558  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:35:09.558  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.558  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.558  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.558  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.558  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.558  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.558  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.558  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.559  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.559  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.559  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.559  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.559  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.559  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.559  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.559  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.560  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.560  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.563  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.564  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.564  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.564  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.564  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.564  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.564  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.564  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.564  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: remove,Listener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.564  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.564  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.564  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.564  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.564  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.565  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.565  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.565  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.565  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.565  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:09.566  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:09.566  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:09.566  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:09.566  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.566  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.566  3780  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4751c34 not in the list
08-23 18:35:09.566  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.566  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.566  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:09.566  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.566  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.566  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:09.566  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:09.567  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:09.567  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:09.567  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:09.567  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ad0a5d not in the list
08-23 18:35:09.567  3780  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-23 18:35:09.567  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 18:35:09.568  3780  3830 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-23 18:35:09.568  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 18:35:09.568  3780  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 18:35:09.568  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 18:35:09.569  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 18:35:09.569  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-23 18:35:09.569  3780  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-23 18:35:09.570  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 18:35:09.570  3780  3830 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 18:35:09.570  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 18:35:09.570  3780  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-23 18:35:09.570  3780  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-23 18:35:09.570  3780  3830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-23 18:35:09.570  3780  3830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-23 18:35:09.570  3780  3830 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-23 18:35:09.571  3780  3830 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-23 18:35:09.571  3780  3830 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 18:35:09.571  3780  3830 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-23 18:35:09.571  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:09.571  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7cd3bf7 added. We now have 2 listener(s)
08-23 18:35:09.571  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:09.572  3780  3830 D BluetoothAdapter: enable(): BT is already enabled..!
08-23 18:35:09.573   872   883 D WifiService: setWifiEnabled: true pid=3780, uid=10000
08-23 18:35:09.573   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 18:35:09.573  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:09.573  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b1fa64 added. We now have 3 listener(s)
08-23 18:35:09.573  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:09.576  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:09.576  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d6a44cd added. We now have 4 listener(s)
08-23 18:35:09.576  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:09.577  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:09.577  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ac3f182 added. We now have 5 listener(s)
08-23 18:35:09.577  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:09.578   872  1922 D WifiService: setWifiEnabled: false pid=3780, uid=10000
08-23 18:35:09.579   872  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 18:35:09.581  2683  2730 D BluetoothAdapterState: Current state: ON, message: 23
08-23 18:35:09.581  2683  2730 D BluetoothAdapterProperties: Setting state to 13
08-23 18:35:09.581  2683  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 18:35:09.582  2683  2730 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 18:35:09.584  2683  2683 D BluetoothMapService: onReceive
08-23 18:35:09.584  2683  2730 I BluetoothAdapterState: Entering PendingCommandState
08-23 18:35:09.584  2683  2683 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:09.584  2683  2683 D BluetoothMapService: STATE_TURNING_OFF
08-23 18:35:09.584  2683  2683 D BluetoothMapService: MAP Service closeService in
08-23 18:35:09.584  2683  2683 D BluetoothMapMasInstance0: MAP Service shutdown
08-23 18:35:09.585  2683  2683 D ObexServerSockets0: shutdown(block = true)
08-23 18:35:09.585  2683  2683 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-23 18:35:09.585  2683  2683 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-23 18:35:09.585  2683  2888 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-23 18:35:09.586  2683  2876 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-23 18:35:09.586  2683  2887 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-23 18:35:09.586  2683  2683 I BtOppRfcommListener: stopping Accept Thread
08-23 18:35:09.588  2683  3423 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:35:09.589  2683  3423 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 18:35:09.590  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:09.593  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.593  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:09.593  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.593  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.593  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:09.593  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:09.593  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:09.593  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:09.593  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:35:09.594  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.594  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:09.594  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:09.596  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:09.596  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 18:35:09.597   872   885 I ActivityManager: Start proc 3849:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-23 18:35:09.598  2683  2734 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:35:09.598  2683  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-23 18:35:09.598   872  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-23 18:35:09.598   872  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-23 18:35:09.599   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 18:35:09.599   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:35:09.599  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.603  2683  2683 D HeadsetService: Received stop request...Stopping profile...
08-23 18:35:09.605   872   872 D BluetoothHeadset: Proxy object disconnected
08-23 18:35:09.605  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.605  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:09.605  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.605  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.605  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:09.605  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:09.605  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:09.605  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:09.605  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:35:09.605  1346  1982 D BluetoothHeadset: Proxy object disconnected
,08-23 18:35:09.605  1904  1919 D BluetoothHeadset: Proxy object disconnected
08-23 18:35:09.606  2683  2683 D A2dpService: Received stop request...Stopping profile...
08-23 18:35:09.606   872   872 D BluetoothHeadset: Proxy object disconnected
08-23 18:35:09.606   872   872 D BluetoothHeadset: Proxy object disconnected
08-23 18:35:09.606  2683  2882 D A2dpStateMachine: Exit Disconnected: -1
08-23 18:35:09.606  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:09.606  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:09.609   872   872 D BluetoothA2dp: Proxy object disconnected
,08-23 18:35:09.609  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:09.610  2683  2683 D HidService: Received stop request...Stopping profile...
,08-23 18:35:09.610  2683  2683 D HidService: Stopping Bluetooth HidService
08-23 18:35:09.610   872  1868 D DhcpClient: Clearing IP address
08-23 18:35:09.611  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:09.611   370   870 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:35:09.611  2683  2683 V BluetoothAdapterState: isTurningOn()=false
,08-23 18:35:09.611  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:09.611  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:09.612  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:09.613  2683  2683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 18:35:09.613  2683  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:09.613  2683  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:09.613  2683  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:09.613  2683  2734 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-23 18:35:09.613  2683  2734 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-23 18:35:09.613  2683  2683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 18:35:09.614  2683  2683 D HealthService: Received stop request...Stopping profile...
08-23 18:35:09.615  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:09.616   370   870 D CommandListener: Setting iface cfg
08-23 18:35:09.616  2683  2683 D PanService: Received stop request...Stopping profile...
,08-23 18:35:09.617  1496  2106 V NativeCrypto: Read error: ssl=0xaee76c00: I/O error during system call, Connection timed out
08-23 18:35:09.619  1496  2106 V NativeCrypto: SSL shutdown failed: ssl=0xaee76c00: I/O error during system call, Broken pipe
,08-23 18:35:09.620   872  1925 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-23 18:35:09.620  1346  1346 D HeadsetProfile: Bluetooth service disconnected
,08-23 18:35:09.620   872  1865 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-23 18:35:09.620  1346  1346 D BluetoothA2dp: Proxy object disconnected
08-23 18:35:09.622   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 18:35:09.623   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-23 18:35:09.626   393   393 E Parcel  : Reading a NULL string not supported here.
,08-23 18:35:09.626  2683  2683 D BluetoothMapService: Received stop request...Stopping profile...
08-23 18:35:09.626  2683  2683 D BluetoothMapService: stop()
08-23 18:35:09.627  2683  2683 D BluetoothMapAppObserver: deinitObservers()
,08-23 18:35:09.627  2683  2683 D BluetoothMapAppObserver: removeReceiver()
08-23 18:35:09.627   872  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-23 18:35:09.628  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:09.629   872  1302 D WifiStateMachine: Start Disconnecting Watchdog 1
08-23 18:35:09.629  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:09.629  1346  1346 D BluetoothInputDevice: Proxy object disconnected
,08-23 18:35:09.629  1346  1346 D HidProfile: Bluetooth service disconnected
08-23 18:35:09.629  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:09.630   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 18:35:09.630  1346  1346 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 18:35:09.630  1346  1346 D PanProfile: Bluetooth service disconnected
08-23 18:35:09.630  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:09.630  1346  1346 D BluetoothMap: Proxy object disconnected
08-23 18:35:09.630  1346  1346 D MapProfile: Bluetooth service disconnected
08-23 18:35:09.631  2683  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:09.631  2683  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-23 18:35:09.631   370   870 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:35:09.632  2683  2862 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:09.632  2683  2862 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:09.632  2683  2862 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:09.632  2683  2862 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:09.632  2683  2734 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-23 18:35:09.632   872  1865 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-23 18:35:09.634   872  1874 D DhcpClient: Receive thread stopped
08-23 18:35:09.634  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:09.635  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:09.635  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:09.635  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:09.635  2683  2683 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 18:35:09.636  2683  2683 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 18:35:09.636  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:09.636  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:09.636  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:09.636  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:09.636  2683  2683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 18:35:09.637  2683  2683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-23 18:35:09.637  2683  2734 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 18:35:09.637  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:09.637  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:09.637  2683  2734 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-23 18:35:09.637  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:09.637  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:09.637  2683  2683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 18:35:09.637  2683  2683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 18:35:09.638  2683  2683 D BluetoothMapService: MAP Service closeService in
08-23 18:35:09.638  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:09.638  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:09.638  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:09.638  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:09.638  2683  2683 D BluetoothMapService: cleanup()
08-23 18:35:09.638  2683  2683 D BluetoothMapService: MAP Service closeService in
,08-23 18:35:09.638  2683  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-23 18:35:09.638  2683  2730 D BluetoothAdapterProperties: Setting state to 15
08-23 18:35:09.638  2683  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-23 18:35:09.639   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:35:09.639   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:35:09.639   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 18:35:09.639  1346  1358 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 18:35:09.639  2683  2730 I BluetoothAdapterState: Entering BleOnState
08-23 18:35:09.640  1346  1982 D BluetoothMap: onBluetoothStateChange: up=false
,08-23 18:35:09.641  1904  2215 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:35:09.641  1346  1357 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 18:35:09.642   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:35:09.642  1346  1358 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:35:09.643  1346  1982 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 18:35:09.643  1346  1357 D BluetoothPan: onBluetoothStateChange on: false
08-23 18:35:09.644  2683  2730 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-23 18:35:09.645  2683  2730 D BluetoothAdapterProperties: Setting state to 16
08-23 18:35:09.645  2683  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-23 18:35:09.649  2683  2730 D BluetoothAdapterProperties: onBleDisable
08-23 18:35:09.649  2683  2730 I BluetoothAdapterState: Entering PendingCommandState
08-23 18:35:09.649  2683  2731 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-23 18:35:09.650  2683  2734 D BluetoothAdapterProperties: Scan Mode:20
08-23 18:35:09.650  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.650  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:09.650  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.650  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.650  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:09.650  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:09.650  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:09.650  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:09.650  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:09.650  2683  2862 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-23 18:35:09.650  2683  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:09.651  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.651  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:09.652  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.653  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:09.653  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.653  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.653  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:09.653  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:09.653  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:09.653  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:09.653  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:09.653  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.653  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:09.655  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:09.656  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.670   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 18:35:09.681  3849  3849 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-23 18:35:09.688   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 18:35:09.689   872  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-23 18:35:09.689   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:35:09.691   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
08-23 18:35:09.694   872   889 D Tethering: MasterInitialState.processMessage what=3
08-23 18:35:09.695  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.695  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:09.695  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.695  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.695  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:09.695  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:09.695  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:09.695  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:09.695  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:09.695  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.695  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:09.696   872  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-23 18:35:09.697  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.697  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:09.697  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:09.697  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:09.697  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:09.697  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:09.697  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:09.697  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:09.697  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:09.697  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:09.698  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:09.700  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.701  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:09.702  3366  3366 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dfea664 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-23 18:35:09.706  2127  2318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:35:09.711  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:09.715  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:09.725   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f1e0ca:true
,08-23 18:35:09.727   872  1971 I ActivityManager: Start proc 3870:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-23 18:35:09.736   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-23 18:35:09.737   872  1304 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-23 18:35:09.737   872  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-23 18:35:09.744  3849  3849 D LocalBluetoothProfileManager: Adding local MAP profile
,08-23 18:35:09.746  3849  3849 D BluetoothMap: Create BluetoothMap proxy object
,08-23 18:35:09.754  3849  3849 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-23 18:35:09.764  3870  3870 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-23 18:35:09.766  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:09.773   872   882 I ActivityManager: Killing 3054:com.google.android.talk/u0a61 (adj 15): empty #17
,08-23 18:35:09.854  2683  2734 I bt_hci  : shut_down
,08-23 18:35:09.855  2683  2740 D bt_hwcfg: hw_epilog_process
,08-23 18:35:09.856  2683  2740 I bt_vendor: low_power_mode_cb
,08-23 18:35:09.877  2683  2740 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-23 18:35:09.878  2683  2740 I bt_vendor: epilog_cb
,08-23 18:35:09.878  2683  2740 I bt_hci  : epilog_finished_callback
,08-23 18:35:09.884  2683  2734 I bt_hci_h4: hal_close
,08-23 18:35:09.885  2683  2734 I bt_userial_vendor: device fd = 51 close
,08-23 18:35:10.007  2683  2731 D bt_stack_manager: event_shut_down_stack finished.
,08-23 18:35:10.007  2683  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-23 18:35:10.009  2683  2730 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-23 18:35:10.010  2683  2683 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 18:35:10.011  2683  2683 D BtGatt.GattService: Received stop request...Stopping profile...
,08-23 18:35:10.012  2683  2683 D BtGatt.GattService: stop()
08-23 18:35:10.012  2683  2683 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 18:35:10.015  2683  2683 V BluetoothAdapterState: isTurningOff()=false
,08-23 18:35:10.015  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:10.016  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 18:35:10.016  2683  2683 V BluetoothAdapterState: isBleTurningOff()=true
08-23 18:35:10.016  2683  2730 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-23 18:35:10.016  2683  2730 D BluetoothAdapterProperties: Setting state to 10
,08-23 18:35:10.016  2683  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-23 18:35:10.017  2683  2730 I BluetoothAdapterState: Entering OffState
08-23 18:35:10.019   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-23 18:35:10.034  3870  3870 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 18:35:10.034  3870  3870 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:10.034  3870  3870 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:10.034  3870  3870 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:10.034  3870  3870 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.k.d(PG:583)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:10.034  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:10.035  3870  3870 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:10.035  3870  3870 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:10.035  3870  3870 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:10.035  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:10.037  2683  2683 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-23 18:35:10.037  2683  2683 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-23 18:35:10.039  2683  2731 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-23 18:35:10.039  2683  2683 I BluetoothServiceJni: cleanupNative: return from cleanup
08-23 18:35:10.041  2683  2731 D bt_stack_manager: event_clean_up_stack finished.
08-23 18:35:10.046  2683  2683 I art     : System.exit called, status: 0
08-23 18:35:10.046  2683  2683 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-23 18:35:10.055  3780  3780 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 18:35:10.146   872  1971 I ActivityManager: Start proc 3903:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-23 18:35:10.147   872  1971 I ActivityManager: Killing 3542:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-23 18:35:10.172  3870  3893 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-23 18:35:10.182   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@986d407:true
,08-23 18:35:10.186   872  1925 I ActivityManager: Process com.android.bluetooth (pid 2683) has died
,08-23 18:35:10.243  3903  3903 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-23 18:35:10.418  3903  3923 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-23 18:35:10.418  3903  3923 I Babel_SMS: MmsConfig.loadMmsSettings
08-23 18:35:10.420  3903  3923 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-23 18:35:10.420  3903  3923 I Babel_SMS: MmsConfig.loadFromDatabase
,08-23 18:35:10.461  3903  3923 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-23 18:35:10.461  3903  3923 I Babel_SMS: MmsConfig.loadFromResources
,08-23 18:35:10.463  3903  3923 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-23 18:35:10.464  3903  3923 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-23 18:35:10.480  3903  3903 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:35:10.486  3903  3903 I Babel_Crash: startup - clean
,08-23 18:35:10.509  3903  3903 I Babel_telephony: TeleModule.launchCompleted
,08-23 18:35:10.522   872   882 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-23 18:35:10.535  3903  3903 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-23 18:35:10.543  3903  3903 W Babel   : BAM#gBA: invalid account id: -1
08-23 18:35:10.543  3903  3903 W Babel   : BAM#gBA: invalid account id: -1
,08-23 18:35:10.543  3903  3903 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-23 18:35:10.546  3903  3928 I Babel   : deleted: false for 0
,08-23 18:35:10.555   872  1370 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-23 18:35:10.567  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:10.607   872  1933 I ActivityManager: Start proc 3931:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-23 18:35:10.609  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:10.621  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 18:35:10.689  3903  3903 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-23 18:35:10.703  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 18:35:10.705  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-23 18:35:10.718  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 18:35:10.730  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 18:35:10.745  3931  3931 D AdapterServiceConfig: Adding HeadsetService
,08-23 18:35:10.745  3903  3903 I vclib   : onServiceConnected
,08-23 18:35:10.751  3931  3931 D AdapterServiceConfig: Adding A2dpService
,08-23 18:35:10.751  3931  3931 D AdapterServiceConfig: Adding HidService
,08-23 18:35:10.752  3931  3931 D AdapterServiceConfig: Adding HealthService
,08-23 18:35:10.752  3931  3931 D AdapterServiceConfig: Adding PanService
,08-23 18:35:10.752  3931  3931 D AdapterServiceConfig: Adding GattService
,08-23 18:35:10.752  3931  3931 D AdapterServiceConfig: Adding BluetoothMapService
,08-23 18:35:10.755   872   882 I ActivityManager: Killing 3366:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-23 18:35:10.863  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:10.899  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 18:35:10.904  1738  1738 D SystemUpdateService: onCreate
,08-23 18:35:10.907  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 18:35:10.914  1738  3943 I SystemUpdateService: active receiver: enabled
,08-23 18:35:10.919  1738  3943 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 18:35:10.925  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-23 18:35:10.926  1738  3943 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-23 18:35:10.928  1738  3943 I SystemUpdateService: now status is 0 (complete)
,08-23 18:35:10.929  1738  3943 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-23 18:35:10.929  1738  3943 I SystemUpdateService: file has been verified
,08-23 18:35:10.929  1738  3943 I SystemUpdateService: OTA package size = 12249756
08-23 18:35:10.930  1738  2406 I iu.UploadsManager: num queued entries: 0
,08-23 18:35:10.931  1738  2406 I iu.UploadsManager: num updated entries: 0
08-23 18:35:10.932  1738  2406 I iu.SyncManager: NEXT; no task
,08-23 18:35:10.934  1738  3943 I SystemUpdateService: showing system update notification
,08-23 18:35:10.958  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 18:35:10.960  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 18:35:10.971   872  1370 I ActivityManager: Start proc 3945:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-23 18:35:10.973  1738  1738 D SystemUpdateService: onDestroy
,08-23 18:35:11.006  3945  3945 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-23 18:35:11.009  3945  3945 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:11.013  3945  3945 D SprintDMHelper: simOperator: 
08-23 18:35:11.013  3945  3945 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 18:35:11.027   872   882 I ActivityManager: Start proc 3957:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-23 18:35:11.028   872   882 I ActivityManager: Killing 2998:com.google.android.keep/u0a79 (adj 15): empty #17
,08-23 18:35:11.165   872   883 I ActivityManager: Start proc 3972:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-23 18:35:11.170  3903  3971 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-23 18:35:11.175   872  1902 I ActivityManager: Killing 3435:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-23 18:35:11.239  3972  3972 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-23 18:35:11.294  3972  3972 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-23 18:35:11.294  3972  3972 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 18:35:11.294  3972  3972 I GAv4    :   adb logcat -s GAv4
,08-23 18:35:11.309  3972  3972 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 18:35:11.315  3972  3972 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 18:35:11.341  3972  3989 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 18:35:11.451  3972  3972 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-23 18:35:11.494  3972  3972 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 18:35:11.507  3972  3972 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 1172-1179)
,08-23 18:35:11.508  3972  3972 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 18:35:11.519  3972  3972 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {48a7094}
08-23 18:35:11.520  3972  3972 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 18:35:11.520  3972  3972 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 18:35:11.530  3972  3972 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-23 18:35:11.533  3972  3972 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 18:35:11.552  3972  3972 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-23 18:35:11.567  3972  3972 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 18:35:11.568  3972  3972 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 18:35:11.568  3972  3972 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 18:35:11.568  3972  3972 I Adreno  : Build Date                       : 10/20/15
08-23 18:35:11.568  3972  3972 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 18:35:11.568  3972  3972 I Adreno  : Local Branch                     : M14
08-23 18:35:11.568  3972  3972 I Adreno  : Remote Branch                    : 
08-23 18:35:11.568  3972  3972 I Adreno  : Remote Branch                    : 
08-23 18:35:11.568  3972  3972 I Adreno  : Reconstruct Branch               : 
,08-23 18:35:11.638  3972  3972 I NSApplication: Starting up...
,08-23 18:35:11.649  3972  4018 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-23 18:35:11.678   872  1933 I ActivityManager: Start proc 4023:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-23 18:35:11.680   872  1933 I ActivityManager: Killing 3474:android.process.acore/u0a5 (adj 15): empty #17
,08-23 18:35:11.772  4023  4023 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-23 18:35:11.954   872  1925 I ActivityManager: Killing 3665:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-23 18:35:12.066   872  1901 I ActivityManager: Start proc 4037:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-23 18:35:12.111  4037  4037 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-23 18:35:12.156  4037  4037 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-23 18:35:12.200   872   883 I ActivityManager: Start proc 4060:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,08-23 18:35:12.201   872   883 I ActivityManager: Killing 3682:com.android.musicfx/u0a18 (adj 15): empty #17
,08-23 18:35:12.296  4060  4060 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,08-23 18:35:12.525   872   882 I ActivityManager: Killing 2217:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-23 18:35:12.597   872  1971 D WifiService: setWifiEnabled: true pid=3780, uid=10000
,08-23 18:35:12.597   872  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 18:35:12.606   872  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-23 18:35:12.616  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:12.617  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:12.617  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:12.617  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:12.617  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:12.617  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:12.617  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:12.617  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:12.617  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:12.617  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:12.617  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:12.619  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:12.619  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:12.619  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:12.619  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:12.619  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:12.619  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:12.619  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:12.619  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:12.619  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:12.619  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:12.619  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:12.643   872  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-23 18:35:12.644   872  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-23 18:35:12.645   872  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-23 18:35:12.646   872  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-23 18:35:12.646   872  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-23 18:35:12.646   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-23 18:35:12.646   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-23 18:35:12.660   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-23 18:35:12.660   370   870 D CommandListener: Setting iface cfg
,08-23 18:35:12.661   872  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,08-23 18:35:12.661   872  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 18:35:12.668   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 18:35:12.678   872  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-23 18:35:12.678   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 18:35:12.679   872  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-23 18:35:14.253   872  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.00 rxSuccessRate=1.34 delta 1000 -> 1000
,08-23 18:35:14.255   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-23 18:35:14.255   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 18:35:14.271   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-23 18:35:14.328   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-23 18:35:14.330  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-23 18:35:14.754  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 18:35:14.791  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-23 18:35:14.792  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-23 18:35:14.802   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 18:35:14.812   872  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 18:35:14.812   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:35:14.814   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-23 18:35:14.830   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 18:35:14.845   370   870 D CommandListener: Setting iface cfg
08-23 18:35:14.846   872  1302 D WifiStateMachine: Start Dhcp Watchdog 2
,08-23 18:35:14.861   872  1304 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-23 18:35:14.865   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-23 18:35:14.874   872  4090 D DhcpClient: Receive thread started
,08-23 18:35:14.955   872  1302 E native  : do suspend false
,08-23 18:35:14.970   872  1868 D DhcpClient: Broadcasting DHCPDISCOVER
,08-23 18:35:14.987   872  4090 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172687, domain null
,08-23 18:35:14.988   872  1868 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172687 seconds
,08-23 18:35:14.991   872  1868 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-23 18:35:15.004   872  4090 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-23 18:35:15.005   872  1868 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-23 18:35:15.009   370   870 D CommandListener: Setting iface cfg
,08-23 18:35:15.019   872  1868 D DhcpClient: Scheduling renewal in 86399s
,08-23 18:35:15.020   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-23 18:35:15.040   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-23 18:35:15.046   872  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-23 18:35:15.046   872  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 18:35:15.049   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-23 18:35:15.051   872  1304 D ConnectivityService: Adding iface wlan0 to network 101
,08-23 18:35:15.068   872  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 18:35:15.116   872  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-23 18:35:15.117   872  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-23 18:35:15.119   872  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-23 18:35:15.122   872  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-23 18:35:15.123   872  1304 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-23 18:35:15.140   872  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-23 18:35:15.146   872  1304 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-23 18:35:15.146   872  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-23 18:35:15.146   872  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-23 18:35:15.146   872  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-23 18:35:15.146   872  1304 D ConnectivityService:    accepting network in place of null
,08-23 18:35:15.147   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 18:35:15.148   872  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 18:35:15.154   872  4089 D NetlinkSocketObserver: NeighborEvent{elapsedMs=134826, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 18:35:15.200   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 18:35:15.229   872  4088 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:80f::200e
,08-23 18:35:15.262   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 18:35:15.271   872  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-23 18:35:15.271   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:15.279   872  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-23 18:35:15.284   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-23 18:35:15.288  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:15.288  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:15.288  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:15.288  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:15.288  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:15.288  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:15.288  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:15.288  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:15.288  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:35:15.288  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:15.288  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:15.291  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:15.292  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:15.292  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:15.292  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:15.292  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:15.292  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:15.292  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:15.292  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:15.292  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:35:15.292  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:15.292  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:15.295   872  4088 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 16:35:15 GMT], X-Android-Received-Millis=[1471970115295], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471970115270]}
08-23 18:35:15.297   872  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-23 18:35:15.297   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-23 18:35:15.297   872  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-23 18:35:15.299   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-23 18:35:15.307  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 18:35:15.311  1738  1738 D SystemUpdateService: onCreate
,08-23 18:35:15.318  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 18:35:15.339   872   883 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-23 18:35:15.340   872  4088 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-23 18:35:15.340   872  4088 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:80f::200e
,08-23 18:35:15.346  1738  4104 I SystemUpdateService: active receiver: enabled
,08-23 18:35:15.349  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 18:35:15.351  1738  2406 I iu.UploadsManager: num queued entries: 0
,08-23 18:35:15.352  1738  4104 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 18:35:15.355  1738  4104 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-23 18:35:15.358  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 18:35:15.357  1738  2406 I iu.UploadsManager: num updated entries: 0
,08-23 18:35:15.361  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 18:35:15.359  1738  4108 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-23 18:35:15.362  1738  4108 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 18:35:15.363  3945  3945 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:15.363  1738  4108 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
08-23 18:35:15.365   872  4088 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 16:35:15 GMT], X-Android-Received-Millis=[1471970115365], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471970115341]}
,08-23 18:35:15.359  1738  4104 I SystemUpdateService: now status is 0 (complete)
,08-23 18:35:15.366  1738  4104 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-23 18:35:15.367  3945  3945 D SprintDMHelper: simOperator: 
08-23 18:35:15.367  3945  3945 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 18:35:15.369   872  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-23 18:35:15.369   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-23 18:35:15.370  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 18:35:15.372  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:15.374  1738  4104 I SystemUpdateService: file has been verified
08-23 18:35:15.374  1738  4104 I SystemUpdateService: OTA package size = 12249756
,08-23 18:35:15.386  1738  2406 I iu.SyncManager: NEXT; no task
,08-23 18:35:15.391  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-23 18:35:15.392  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-23 18:35:15.392  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 18:35:15.392  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:15.405  1738  4104 I SystemUpdateService: showing system update notification
,08-23 18:35:15.433  1738  4108 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-23 18:35:15.455  3903  3903 I art     : Waiting for a blocking GC DisableMovingGc
,08-23 18:35:15.458  3903  3903 I art     : Starting a blocking GC DisableMovingGc
,08-23 18:35:15.462  4060  4113 V KeepSync: Connecting to GoogleApiClient
,08-23 18:35:15.462   872  1971 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 18:35:15.471  1738  1738 D SystemUpdateService: onDestroy
,08-23 18:35:15.590  1496  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 18:35:15.590  1496  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 18:35:15.590  1496  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 18:35:15.590  1496  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:15.595  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 18:35:15.595  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 18:35:15.595  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 18:35:15.595  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:15.602   872  1922 D WifiService: setWifiEnabled: false pid=3780, uid=10000
,08-23 18:35:15.602   872  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,08-23 18:35:15.608  3530  4112 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 18:35:15.608  3530  4112 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at jdm.a(PG:82)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at jcs.o(PG:406)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at jcn.a(PG:1379)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at jcs.i(PG:143)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at blb.a(PG:3937)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at czp.a(PG:18188)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at czp.a(PG:9081)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at czq.run(PG:1686)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 18:35:15.608  3530  4112 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at jdj.a(PG:4091)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at jdj.a(PG:1125)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at jdm.a(PG:77)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	... 12 more
08-23 18:35:15.608  3530  4112 E HttpOperation: Caused by: faj: BadAuthentication
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at fal.a(PG:38)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	at jdj.a(PG:4089)
08-23 18:35:15.608  3530  4112 E HttpOperation: 	... 14 more
,08-23 18:35:15.615  1738  4115 V BaseAuthAsyncOperation: access token request failed
,08-23 18:35:15.616  4060  4113 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 18:35:15.624  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-23 18:35:15.628   872  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-23 18:35:15.628   872  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-23 18:35:15.628   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 18:35:15.628   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 18:35:15.637   872  1868 D DhcpClient: Clearing IP address
,08-23 18:35:15.638   370   870 D CommandListener: Setting iface cfg
,08-23 18:35:15.640   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-23 18:35:15.643  3903  4114 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-23 18:35:15.643   872  4090 D DhcpClient: Receive thread stopped
08-23 18:35:15.645   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-23 18:35:15.646   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-23 18:35:15.646   872  1302 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-23 18:35:15.647   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 18:35:15.651   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
,08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
,08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904),
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
08-23 18:35:15.652  3903  4114 W Babel_NetworkConnectionCheckingService: 	... 21 more
,08-23 18:35:15.652  3903  4114 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-23 18:35:15.653   393   393 E Parcel  : Reading a NULL string not supported here.
,08-23 18:35:15.659   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 18:35:15.661  1496  2116 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 18:35:15.661  1496  2116 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 18:35:15.661  1496  2116 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 18:35:15.661  1496  2116 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:15.662  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:15.662  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:15.662  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:15.662  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:15.662  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:15.662  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:15.662  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:15.662  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:15.662  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:15.662  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:15.662  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:15.662   872  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-23 18:35:15.663  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:15.663  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:15.663  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:15.663  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:15.663  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:15.663  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:15.663  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:15.663  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:15.663  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:35:15.663  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:15.663  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:15.666   872  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-23 18:35:15.668  2127  2318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:35:15.679  3530  4112 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 18:35:15.679  3530  4112 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 18:35:15.679  3530  4112 E HttpOperation: ,	at jdm.a(PG:82)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at jcs.o(PG:406)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at jcn.a(PG:1379)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at jcs.i(PG:143)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at hec.a(PG:42)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at hee.a(PG:102)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at czr.a(PG:65)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at kka.a(PG:108)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at czp.a(PG:19176)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at czp.a(PG:9081)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at czq.run(PG:1686)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 18:35:15.679  3530  4112 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at jdj.a(PG:4091)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at jdj.a(PG:1125)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at jdm.a(PG:77)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	... 15 more
08-23 18:35:15.679  3530  4112 E HttpOperation: Caused by: faj: BadAuthentication
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at fal.a(PG:38)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	at jdj.a(PG:4089)
08-23 18:35:15.679  3530  4112 E HttpOperation: 	... 17 more
,08-23 18:35:15.679  3530  4112 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 18:35:15.679  3530  4112 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at hec.a(PG:42)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at hee.a(PG:102)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at czr.a(PG:65)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at kka.a(PG:108)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	... 15 more
08-23 18:35:15.679  3530  4112 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at fal.a(PG:38)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 18:35:15.679  3530  4112 E ExperimentLoader: ,	... 17 more
,08-23 18:35:15.702   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0,
,08-23 18:35:15.731   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 18:35:15.732   872  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-23 18:35:15.732   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:15.735   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-23 18:35:15.737  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:15.738  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:15.738  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:15.738  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:15.738  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:15.738  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:15.738  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:15.738  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:15.738  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:15.739  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:15.739  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:15.739  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:15.739  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:15.739  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:15.739  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:15.739  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:15.739  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:15.739  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:15.752  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 18:35:15.755  1738  1738 D SystemUpdateService: onCreate
,08-23 18:35:15.762  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 18:35:15.780  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-23 18:35:15.780   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129320, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 18:35:15.790  1738  2406 I iu.UploadsManager: num queued entries: 0
,08-23 18:35:15.796  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 18:35:15.797  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 18:35:15.800  1738  4131 I SystemUpdateService: active receiver: enabled
,08-23 18:35:15.801  3945  3945 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:15.806  3945  3945 D SprintDMHelper: simOperator: 
,08-23 18:35:15.806  3945  3945 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 18:35:15.829   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-23 18:35:15.841  1738  2406 I iu.UploadsManager: num updated entries: 0
,08-23 18:35:15.845  3903  4135 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-23 18:35:15.854  1738  4131 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 18:35:15.855  1738  2406 I iu.SyncManager: NEXT; no task
,08-23 18:35:15.856  1738  4131 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-23 18:35:15.856  1738  4131 I SystemUpdateService: now status is 0 (complete)
08-23 18:35:15.856  1738  4131 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-23 18:35:15.856  1738  4131 I SystemUpdateService: file has been verified
08-23 18:35:15.856  1738  4131 I SystemUpdateService: OTA package size = 12249756,
,08-23 18:35:15.865  1738  4131 I SystemUpdateService: showing system update notification
,08-23 18:35:15.881  1738  1738 D SystemUpdateService: onDestroy
,08-23 18:35:15.957  1496  2116 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-23 18:35:15.957  1496  2116 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 18:35:15.958  1496  2116 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 18:35:15.958  1496  2116 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:15.978  4060  4113 E KeepSync: IOException
08-23 18:35:15.978  4060  4113 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 18:35:15.978  4060  4113 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 18:35:15.978  4060  4113 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 18:35:15.978  4060  4113 E KeepSync: 	... 10 more
08-23 18:35:15.978  4060  4113 W KeepSync: Sync result 2
,08-23 18:35:15.983   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 128555, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 18:35:16.161   872  1925 I ActivityManager: Killing 3712:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-23 18:35:16.270   872  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-23 18:35:17.380  4060  4066 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@1f389b4)
,08-23 18:35:18.649   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@df7517b:true
,08-23 18:35:18.649  3931  3931 D BluetoothAdapterState: make() - Creating AdapterState
,08-23 18:35:18.655  3931  3931 I bt_bluedroid: init
,08-23 18:35:18.656  3931  4139 I BluetoothAdapterState: Entering OffState
,08-23 18:35:18.658  3931  4140 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 18:35:18.658  3931  4140 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-23 18:35:18.658  3931  4140 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 18:35:18.658  3931  4140 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-23 18:35:18.659  3931  3931 I bt_bluedroid: get_profile_interface socket
08-23 18:35:18.661  3931  3931 I bt_bluedroid: get_profile_interface sdp
,08-23 18:35:18.667  3931  4143 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-23 18:35:18.667  3931  3941 I bt_bluedroid: config_hci_snoop_log
08-23 18:35:18.669   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 18:35:18.675  3931  4139 D BluetoothAdapterState: Current state: OFF, message: 0
,08-23 18:35:18.679  3931  4143 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 18:35:18.679  3931  4139 D BluetoothAdapterProperties: Setting state to 14
,08-23 18:35:18.680  3931  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-23 18:35:18.684  3931  4139 D BluetoothBondStateMachine: make
,08-23 18:35:18.688  3931  4144 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 18:35:18.693  3931  4139 I BluetoothAdapterState: Entering PendingCommandState
,08-23 18:35:18.694  3931  3931 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-23 18:35:18.696  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
08-23 18:35:18.697  3931  3931 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 18:35:18.698  3931  3931 D BtGatt.GattService: Received start request. Starting profile...
08-23 18:35:18.698  3931  3931 D BtGatt.GattService: start()
,08-23 18:35:18.699  3931  3931 I bt_bluedroid: get_profile_interface gatt
08-23 18:35:18.700  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:18.700  3931  3931 D BtGatt.AdvertiseManager: advertise manager created
,08-23 18:35:18.708  3931  3931 V BluetoothAdapterState: isTurningOff()=false
,08-23 18:35:18.708  3931  3931 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:18.708  3931  3931 V BluetoothAdapterState: isBleTurningOn()=true
08-23 18:35:18.708  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:18.709  3931  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-23 18:35:18.709  3931  4139 I bt_bluedroid: enable
08-23 18:35:18.710  3931  4140 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-23 18:35:18.710  3931  4140 I bt_hci  : start_up
,08-23 18:35:18.715  3931  4140 I bt_vendor: alloc value 0xb39f9189
,08-23 18:35:18.715  3931  4140 I bt_vendor: init
08-23 18:35:18.715  3931  4140 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-23 18:35:18.715  3931  4140 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-23 18:35:18.823  3931  4140 D bt_hci  : start_up starting async portion
08-23 18:35:18.823  3931  4147 I bt_hci  : event_finish_startup
,08-23 18:35:18.824  3931  4147 I bt_hci_h4: hal_open
08-23 18:35:18.824  3931  4147 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-23 18:35:18.832  3931  4147 I bt_userial_vendor: device fd = 51 open
,08-23 18:35:18.865  3931  4147 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 18:35:18.897  3931  4147 D bt_hwcfg: Chipset BCM4354A2
,08-23 18:35:18.897  3931  4147 D bt_hwcfg: Target name = [BCM4354A2]
,08-23 18:35:18.898  3931  4147 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-23 18:35:19.556  3931  4147 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-23 18:35:19.558  3931  4147 D bt_hwcfg: Settlement delay -- 100 ms
,08-23 18:35:19.558  3931  4147 I bt_hwcfg: Setting fw settlement delay to 100 
,08-23 18:35:19.675  3931  4147 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 18:35:19.676  3931  4147 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-23 18:35:19.705  3931  4147 I bt_hwcfg: vendor lib fwcfg completed
,08-23 18:35:19.705  3931  4147 I bt_vendor: firmware callback
08-23 18:35:19.706  3931  4147 I bt_hci  : firmware_config_callback
,08-23 18:35:19.717  3931  4150 I bt_btu  : btu_task pending for preload complete event
,08-23 18:35:19.718  3931  4150 I bt_btu_task: Bluetooth chip preload is complete
08-23 18:35:19.718  3931  4150 I bt_btu  : btu_task received preload complete event
,08-23 18:35:19.728  3931  4150 I         : BTE_InitTraceLevels -- TRC_HCI
,08-23 18:35:19.728  3931  4150 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 18:35:19.728  3931  4150 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-23 18:35:19.729  3931  4150 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-23 18:35:19.729  3931  4150 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 18:35:19.729  3931  4150 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 18:35:19.729  3931  4150 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 18:35:19.730  3931  4150 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 18:35:19.730  3931  4150 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 18:35:19.730  3931  4150 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 18:35:19.731  3931  4150 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 18:35:19.731  3931  4150 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 18:35:19.731  3931  4150 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 18:35:19.731  3931  4150 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 18:35:19.732  3931  4150 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 18:35:19.865  3931  4150 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-23 18:35:19.865  3931  4150 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-23 18:35:19.877  3931  4143 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-23 18:35:19.878  3931  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-23 18:35:19.879  3931  4143 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 18:35:19.886  3931  4143 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 18:35:19.888  3931  4143 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:35:19.888  3931  4143 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 18:35:19.891  3931  4143 D bt_hci  : do_postload posting postload work item
,08-23 18:35:19.891  3931  4147 I bt_hci  : event_postload
08-23 18:35:19.891  3931  4147 I bt_vendor: sco_config_cb
,08-23 18:35:19.891  3931  4147 I bt_hci  : sco_config_callback postload finished.
,08-23 18:35:19.892  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:19.894  3931  4143 D bt_bte_conf: Device ID record 1 : primary
,08-23 18:35:19.894  3931  4143 D bt_bte_conf:   vendorId            = 000f
,08-23 18:35:19.895  3931  4143 D bt_bte_conf:   vendorIdSource      = 0001
,08-23 18:35:19.895  3931  4143 D bt_bte_conf:   product             = 1200
08-23 18:35:19.895  3931  4143 D bt_bte_conf:   version             = 1436
,08-23 18:35:19.895  3931  4143 D bt_bte_conf:   clientExecutableURL = 
08-23 18:35:19.896  3931  4143 D bt_bte_conf:   serviceDescription  = 
08-23 18:35:19.896  3931  4143 D bt_bte_conf:   documentationURL    = 
,08-23 18:35:19.896  3931  4147 I bt_vendor: low_power_mode_cb
08-23 18:35:19.896  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:19.896  3931  4143 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-23 18:35:19.896  3931  4140 D bt_stack_manager: event_start_up_stack finished
,08-23 18:35:19.897  3931  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-23 18:35:19.898  3931  4139 D BluetoothAdapterProperties: Setting state to 15
,08-23 18:35:19.898  3931  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-23 18:35:19.899  3931  4139 I BluetoothAdapterState: Entering BleOnState
08-23 18:35:19.904  3931  4139 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-23 18:35:19.904  3931  4139 D BluetoothAdapterProperties: Setting state to 11
08-23 18:35:19.905  3931  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-23 18:35:19.911  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:19.913  3931  3931 D HeadsetService: Received start request. Starting profile...
,08-23 18:35:19.916  3931  3931 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 18:35:19.917  3931  3931 D HeadsetStateMachine: make
08-23 18:35:19.918  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:19.922  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:19.931  3931  3931 D HeadsetStateMachine: max_hf_connections = 1
,08-23 18:35:19.932  3931  3931 I bt_bluedroid: get_profile_interface handsfree
,08-23 18:35:19.932  3931  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-23 18:35:19.932  3931  4143 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-23 18:35:19.938  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:19.939  3931  3931 D A2dpService: Received start request. Starting profile...
,08-23 18:35:19.940  3931  4139 I BluetoothAdapterState: Entering PendingCommandState
08-23 18:35:19.940  3931  3931 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-23 18:35:19.940  3931  3931 I bt_bluedroid: get_profile_interface avrcp
,08-23 18:35:19.946  3931  3931 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 18:35:19.946  3931  3931 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 18:35:19.946  3931  3931 D A2dpStateMachine: make
,08-23 18:35:19.947  3931  3931 I bt_bluedroid: get_profile_interface a2dp
,08-23 18:35:19.948  3931  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-23 18:35:19.949  3931  4159 D A2dpStateMachine: Enter Disconnected: -2
,08-23 18:35:19.952  3931  3931 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 18:35:19.953  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:19.953  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:19.954  3849  3849 D BluetoothInputDevice: Proxy object connected
08-23 18:35:19.954  3849  3849 D HidProfile: Bluetooth service connected
,08-23 18:35:19.954  3931  3931 D HidService: Received start request. Starting profile...
08-23 18:35:19.955  3931  3931 I bt_bluedroid: get_profile_interface hidhost
08-23 18:35:19.955  3931  4143 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-23 18:35:19.955  3931  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-23 18:35:19.955  3931  3931 D HidService: setHidService(): set to: null
,08-23 18:35:19.956  3931  3931 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 18:35:19.957  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:19.957  3931  3931 D HealthService: Received start request. Starting profile...
,08-23 18:35:19.958  3931  3931 I bt_bluedroid: get_profile_interface health
,08-23 18:35:19.959  3931  3931 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 18:35:19.960  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:19.961  3849  3849 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 18:35:19.961  3931  3931 D PanService: Received start request. Starting profile...
08-23 18:35:19.961  3849  3849 D PanProfile: Bluetooth service connected
08-23 18:35:19.962  3931  3931 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 18:35:19.962  3931  3931 I bt_bluedroid: get_profile_interface pan
08-23 18:35:19.962  3931  4143 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-23 18:35:19.963  3931  3931 V BluetoothAdapterState: isTurningOff()=false
08-23 18:35:19.963  3931  3931 V BluetoothAdapterState: isTurningOn()=true
,08-23 18:35:19.963  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:19.963  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:19.965  3931  4157 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-23 18:35:19.967  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:19.968  3849  3849 D BluetoothMap: Proxy object connected
08-23 18:35:19.968  3931  3931 D BluetoothMapService: Received start request. Starting profile...
,08-23 18:35:19.968  3931  3931 D BluetoothMapService: start()
08-23 18:35:19.968  3849  3849 D MapProfile: Bluetooth service connected
08-23 18:35:19.968  3849  3849 D BluetoothMap: getConnectedDevices()
08-23 18:35:19.969  3849  3849 D BluetoothMap: Bluetooth is Not enabled
08-23 18:35:19.970  3931  3931 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-23 18:35:19.970  3931  3931 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-23 18:35:19.971  3931  3931 D BluetoothMapAppObserver: createReceiver()
08-23 18:35:19.971  3931  3931 D BluetoothMapAppObserver: initObservers()
08-23 18:35:19.972  3931  3931 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-23 18:35:19.978  3931  3931 V BluetoothAdapterState: isTurningOff()=false
,08-23 18:35:19.978  3931  3931 V BluetoothAdapterState: isTurningOn()=true
08-23 18:35:19.978  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:19.978  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:19.978  3931  3931 V BluetoothAdapterState: isTurningOff()=false
,08-23 18:35:19.978  3931  3931 V BluetoothAdapterState: isTurningOn()=true
08-23 18:35:19.978  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 18:35:19.978  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:19.981  3931  3931 V BluetoothAdapterState: isTurningOff()=false
,08-23 18:35:19.981  3931  3931 V BluetoothAdapterState: isTurningOn()=true
08-23 18:35:19.981  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:19.981  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:19.981  3931  3931 V BluetoothAdapterState: isTurningOff()=false
08-23 18:35:19.981  3931  3931 V BluetoothAdapterState: isTurningOn()=true
08-23 18:35:19.982  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:19.982  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:19.982  3931  3931 V BluetoothAdapterState: isTurningOff()=false
,08-23 18:35:19.982  3931  3931 V BluetoothAdapterState: isTurningOn()=true
,08-23 18:35:19.982  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 18:35:19.982  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:19.982  3931  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-23 18:35:19.982  3931  4139 D BluetoothAdapterProperties: ScanMode =  20
,08-23 18:35:19.982  3931  4139 D BluetoothAdapterProperties: State =  11
08-23 18:35:19.985  3931  4139 D BluetoothAdapterProperties: Setting state to 12
,08-23 18:35:19.985  3931  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-23 18:35:19.985   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 18:35:19.985   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 18:35:19.985  3849  3861 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 18:35:19.986  3931  4139 I BluetoothAdapterState: Entering OnState
08-23 18:35:19.986   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 18:35:19.986  3931  4143 D BluetoothAdapterProperties: Scan Mode:21
08-23 18:35:19.987  3849  3862 D BluetoothPan: onBluetoothStateChange on: true
08-23 18:35:19.988   872   872 D BluetoothA2dp: Proxy object connected
,08-23 18:35:19.988  1346  1357 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 18:35:19.988  3931  4143 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 18:35:19.990  1346  1346 D BluetoothA2dp: Proxy object connected
,08-23 18:35:19.990  1346  1982 D BluetoothMap: onBluetoothStateChange: up=true
08-23 18:35:19.990  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:19.990  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:19.990  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:19.990  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:19.990  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:19.990  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:19.990  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:19.990  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:19.993  1346  1346 D BluetoothMap: Proxy object connected
,08-23 18:35:19.993  1346  1346 D MapProfile: Bluetooth service connected
08-23 18:35:19.993  1346  1346 D BluetoothMap: getConnectedDevices()
08-23 18:35:19.993  3849  3861 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 18:35:19.993  1904  2077 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:35:19.994  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:19.994  1346  1357 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 18:35:19.996   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 18:35:19.996  3849  3862 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 18:35:19.996  1346  1346 D BluetoothInputDevice: Proxy object connected
08-23 18:35:19.996  1346  1346 D HidProfile: Bluetooth service connected
08-23 18:35:19.998  1346  1358 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:35:19.998  1346  1982 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 18:35:19.998  3931  3931 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 18:35:19.998  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:19.998  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:19.998  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:19.998  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:19.998  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:19.998  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:19.998  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:19.998  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:19.999  3931  3931 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-23 18:35:20.000  1346  1357 D BluetoothPan: onBluetoothStateChange on: true
08-23 18:35:20.001  3931  3931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:35:20.002  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:20.002  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 18:35:20.003  3931  3931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:20.003  1346  1346 D PanProfile: Bluetooth service connected
08-23 18:35:20.004   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-23 18:35:20.006  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:20.007  3849  3849 D LocalBluetoothProfileManager: Adding local A2DP profile
08-23 18:35:20.008  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:20.008  3931  3931 D ObexServerSockets: Succeed to create listening sockets ,
08-23 18:35:20.008  3931  3931 D ObexServerSockets0: startAccept()
08-23 18:35:20.008  3931  3931 D ObexServerSockets0: prepareForNewConnect()
,08-23 18:35:20.011  3931  3931 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-23 18:35:20.011  3931  3931 D BluetoothSdpJni: SDP Create record success - handle: 0
08-23 18:35:20.011  3931  4165 D ObexServerSockets0: Accepting socket connection...
,08-23 18:35:20.012  3931  4166 D ObexServerSockets0: Accepting socket connection...
08-23 18:35:20.011  3849  3849 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-23 18:35:20.012  3931  3931 D BluetoothMapService: onReceive
,08-23 18:35:20.012  3931  3931 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:20.013  3931  3931 D BluetoothMapService: STATE_ON
08-23 18:35:20.019  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:20.024  3849  3849 D BluetoothA2dp: Proxy object connected
08-23 18:35:20.029  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 18:35:20.030  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:20.039  1346  1346 D BluetoothPbap: Proxy object connected,
08-23 18:35:20.039  3849  3849 D BluetoothPbap: Proxy object connected
08-23 18:35:20.039  1346  1346 D PbapServerProfile: Bluetooth service connected
08-23 18:35:20.039  3849  3849 D PbapServerProfile: Bluetooth service connected
,08-23 18:35:20.044  3931  3931 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-23 18:35:20.044  3931  3931 D ObexServerSockets0: prepareForNewConnect()
,08-23 18:35:20.047  3931  4170 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:20.060  3931  4174 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:20.063  3931  4174 I BtOppRfcommListener: Accept thread started.
,08-23 18:35:20.086   872   872 D BluetoothHeadset: Proxy object connected
,08-23 18:35:20.087  1346  1358 D BluetoothHeadset: Proxy object connected
,08-23 18:35:20.087  1346  1346 D HeadsetProfile: Bluetooth service connected
,08-23 18:35:20.087  1904  2215 D BluetoothHeadset: Proxy object connected
,08-23 18:35:20.087   872   872 D BluetoothHeadset: Proxy object connected
,08-23 18:35:20.087   872   872 D BluetoothHeadset: Proxy object connected
,08-23 18:35:20.094  1904  1919 D BluetoothHeadset: Proxy object connected
,08-23 18:35:20.095   872   889 D BluetoothHeadset: Proxy object connected
,08-23 18:35:20.098  1346  1982 D BluetoothHeadset: Proxy object connected
,08-23 18:35:20.099  1346  1346 D HeadsetProfile: Bluetooth service connected
,08-23 18:35:20.115  3849  3861 D BluetoothHeadset: Proxy object connected
,08-23 18:35:20.116  3849  3849 D HeadsetProfile: Bluetooth service connected
,08-23 18:35:21.619  3931  4139 D BluetoothAdapterState: Current state: ON, message: 23
,08-23 18:35:21.620  3931  4139 D BluetoothAdapterProperties: Setting state to 13
,08-23 18:35:21.620  3931  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-23 18:35:21.622  3931  4139 D BluetoothAdapterProperties: onBluetoothDisable()
,08-23 18:35:21.624  3931  4139 I BluetoothAdapterState: Entering PendingCommandState
,08-23 18:35:21.635  3931  3931 D BluetoothMapService: onReceive
,08-23 18:35:21.636  3931  3931 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:21.636  3931  3931 D BluetoothMapService: STATE_TURNING_OFF
08-23 18:35:21.637  3931  3931 D BluetoothMapService: MAP Service closeService in
08-23 18:35:21.637  3931  3931 D BluetoothMapMasInstance0: MAP Service shutdown
,08-23 18:35:21.637  3931  3931 D ObexServerSockets0: shutdown(block = true)
08-23 18:35:21.638  3931  4165 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-23 18:35:21.640  3931  4143 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:35:21.640  3931  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-23 18:35:21.641  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:21.642  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:21.642  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:21.642  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:21.642  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:21.642  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:21.642  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:21.642  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:21.642  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:21.642  3931  3931 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-23 18:35:21.643  3931  4153 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-23 18:35:21.643  3931  3931 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-23 18:35:21.644  3931  4166 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-23 18:35:21.645  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:21.642  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 18:35:21.645  3931  3931 I BtOppRfcommListener: stopping Accept Thread
08-23 18:35:21.647  3931  4174 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-23 18:35:21.647  3931  4174 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 18:35:21.645  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:21.652  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:21.652  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:21.652  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:21.652  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:21.652  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:21.652  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:21.652  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:21.652  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:21.652  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:21.655  3780  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:21.655  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:21.655  3931  3931 D HeadsetService: Received stop request...Stopping profile...
08-23 18:35:21.657  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:21.659   872   872 D BluetoothHeadset: Proxy object disconnected
,08-23 18:35:21.659  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:21.661  1346  1982 D BluetoothHeadset: Proxy object disconnected
,08-23 18:35:21.661  1346  1346 D HeadsetProfile: Bluetooth service disconnected
08-23 18:35:21.661  1904  1920 D BluetoothHeadset: Proxy object disconnected
08-23 18:35:21.662   872   872 D BluetoothHeadset: Proxy object disconnected
08-23 18:35:21.662  3849  3861 D BluetoothHeadset: Proxy object disconnected
,08-23 18:35:21.662   872   872 D BluetoothHeadset: Proxy object disconnected
08-23 18:35:21.662  3931  3931 D A2dpService: Received stop request...Stopping profile...
08-23 18:35:21.663  3931  4159 D A2dpStateMachine: Exit Disconnected: -1
,08-23 18:35:21.668   872   872 D BluetoothA2dp: Proxy object disconnected
,08-23 18:35:21.669  1346  1346 D BluetoothA2dp: Proxy object disconnected
08-23 18:35:21.669  3931  3931 D HidService: Received stop request...Stopping profile...,
08-23 18:35:21.669  3931  3931 D HidService: Stopping Bluetooth HidService
,08-23 18:35:21.670  1346  1346 D BluetoothInputDevice: Proxy object disconnected
,08-23 18:35:21.670  1346  1346 D HidProfile: Bluetooth service disconnected
08-23 18:35:21.671  3931  3931 D HealthService: Received stop request...Stopping profile...
,08-23 18:35:21.673  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:21.674  3931  3931 D PanService: Received stop request...Stopping profile...
,08-23 18:35:21.674  3849  3849 D HeadsetProfile: Bluetooth service disconnected
08-23 18:35:21.675  1346  1346 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-23 18:35:21.675  1346  1346 D PanProfile: Bluetooth service disconnected
08-23 18:35:21.674  3849  3849 D BluetoothA2dp: Proxy object disconnected
08-23 18:35:21.675  3931  3931 D BluetoothMapService: Received stop request...Stopping profile...
08-23 18:35:21.675  3849  3849 D BluetoothInputDevice: Proxy object disconnected
08-23 18:35:21.675  3849  3849 D HidProfile: Bluetooth service disconnected
,08-23 18:35:21.675  3931  3931 D BluetoothMapService: stop()
08-23 18:35:21.676  3931  3931 D BluetoothMapAppObserver: deinitObservers()
08-23 18:35:21.676  3931  3931 D BluetoothMapAppObserver: removeReceiver()
08-23 18:35:21.677  3849  3849 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 18:35:21.678  1346  1346 D BluetoothMap: Proxy object disconnected
08-23 18:35:21.678  1346  1346 D MapProfile: Bluetooth service disconnected
,08-23 18:35:21.678  3849  3849 D PanProfile: Bluetooth service disconnected
08-23 18:35:21.682  3849  3849 D BluetoothMap: Proxy object disconnected
08-23 18:35:21.683  3849  3849 D MapProfile: Bluetooth service disconnected
,08-23 18:35:21.686  3931  3931 V BluetoothAdapterState: isTurningOff()=true
,08-23 18:35:21.686  3931  3931 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:21.686  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:21.686  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:21.687  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 18:35:21.687  3931  3931 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 18:35:21.687  3931  3931 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 18:35:21.687  3931  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-23 18:35:21.688  3931  3931 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:21.688  3931  3931 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:21.688  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:21.688  3931  4150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:21.688  3931  4150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:21.688  3931  4150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:21.689  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:21.690  3931  4143 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-23 18:35:21.691  3931  3931 V BluetoothAdapterState: isTurningOff()=true
,08-23 18:35:21.691  3931  4150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:21.692  3931  3931 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:21.692  3931  4150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:21.692  3931  4150 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 18:35:21.692  3931  4150 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:21.693  3931  4150 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:21.693  3931  4150 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:21.693  3931  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-23 18:35:21.692  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 18:35:21.695  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:21.695  3931  3931 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-23 18:35:21.695  3931  3931 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-23 18:35:21.696  3931  3931 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:21.696  3931  3931 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:21.696  3931  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 18:35:21.696  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:21.696  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:21.696  3931  3931 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 18:35:21.696  3931  4143 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-23 18:35:21.697  3931  3931 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 18:35:21.697  3931  3931 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:21.697  3931  3931 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:21.697  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:21.697  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:21.697  3931  3931 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 18:35:21.698  3931  3931 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 18:35:21.698  3931  3931 D BluetoothMapService: MAP Service closeService in
08-23 18:35:21.698  3931  3931 V BluetoothAdapterState: isTurningOff()=true
08-23 18:35:21.699  3931  3931 V BluetoothAdapterState: isTurningOn()=false
,08-23 18:35:21.699  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 18:35:21.699  3931  3931 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:21.699  3931  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-23 18:35:21.699  3931  4139 D BluetoothAdapterProperties: Setting state to 15
08-23 18:35:21.699  3931  3931 D BluetoothMapService: cleanup()
08-23 18:35:21.699  3931  3931 D BluetoothMapService: MAP Service closeService in
,08-23 18:35:21.699  3931  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-23 18:35:21.700   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:35:21.700  3849  3862 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 18:35:21.700   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 18:35:21.700  3931  4139 I BluetoothAdapterState: Entering BleOnState
,08-23 18:35:21.700  3849  3861 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 18:35:21.701  3849  3862 D BluetoothMap: onBluetoothStateChange: up=false
08-23 18:35:21.702  1346  1346 D BluetoothPbap: Proxy object disconnected
08-23 18:35:21.702  1346  1346 D PbapServerProfile: Bluetooth service disconnected
,08-23 18:35:21.702   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 18:35:21.702  3849  3861 D BluetoothPan: onBluetoothStateChange on: false
08-23 18:35:21.703  1346  4092 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 18:35:21.705  1346  1358 D BluetoothMap: onBluetoothStateChange: up=false
08-23 18:35:21.706  3849  3862 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-23 18:35:21.706  1904  2077 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:35:21.706  1346  1982 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 18:35:21.707   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:35:21.707  3849  3861 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 18:35:21.707  1346  1357 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 18:35:21.708  1346  4092 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 18:35:21.709  1346  1358 D BluetoothPan: onBluetoothStateChange on: false
08-23 18:35:21.709  3931  4139 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-23 18:35:21.709  3931  4139 D BluetoothAdapterProperties: Setting state to 16
08-23 18:35:21.709  3931  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-23 18:35:21.710  3931  4139 D BluetoothAdapterProperties: onBleDisable
08-23 18:35:21.710  3931  4139 I BluetoothAdapterState: Entering PendingCommandState
,08-23 18:35:21.710  3931  4140 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-23 18:35:21.713  3931  4143 D BluetoothAdapterProperties: Scan Mode:20
08-23 18:35:21.714  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 18:35:21.714  3931  4150 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-23 18:35:21.714  3931  4150 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 18:35:21.717  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:21.721  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:21.722  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 18:35:21.722  3849  3849 D DockEventReceiver: finishStartingService: stopping service
08-23 18:35:21.727  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:21.729  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:21.915  3931  4143 I bt_hci  : shut_down
,08-23 18:35:21.915  3931  4147 D bt_hwcfg: hw_epilog_process
,08-23 18:35:21.928  3931  4147 I bt_vendor: low_power_mode_cb
,08-23 18:35:21.948  3931  4147 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-23 18:35:21.949  3931  4147 I bt_vendor: epilog_cb
08-23 18:35:21.949  3931  4147 I bt_hci  : epilog_finished_callback
,08-23 18:35:21.957  3931  4143 I bt_hci_h4: hal_close
,08-23 18:35:21.959  3931  4143 I bt_userial_vendor: device fd = 51 close
,08-23 18:35:22.076  3931  4140 D bt_stack_manager: event_shut_down_stack finished.
,08-23 18:35:22.076  3931  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-23 18:35:22.081  3931  3931 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 18:35:22.081  3931  4139 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-23 18:35:22.082  3931  3931 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 18:35:22.082  3931  3931 D BtGatt.GattService: stop()
08-23 18:35:22.082  3931  3931 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 18:35:22.086  3931  3931 V BluetoothAdapterState: isTurningOff()=false
08-23 18:35:22.086  3931  3931 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:22.086  3931  3931 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:22.087  3931  3931 V BluetoothAdapterState: isBleTurningOff()=true
,08-23 18:35:22.087  3931  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-23 18:35:22.088  3931  4139 D BluetoothAdapterProperties: Setting state to 10
08-23 18:35:22.088  3931  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-23 18:35:22.089  3931  4139 I BluetoothAdapterState: Entering OffState
08-23 18:35:22.089   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-23 18:35:22.103  3931  3931 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-23 18:35:22.103  3931  3931 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-23 18:35:22.103  3931  4140 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-23 18:35:22.106  3931  4140 D bt_stack_manager: event_clean_up_stack finished.
08-23 18:35:22.106  3931  3931 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-23 18:35:22.108  3931  3931 I art     : System.exit called, status: 0
08-23 18:35:22.108  3931  3931 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 18:35:22.171   872   882 I ActivityManager: Process com.android.bluetooth (pid 3931) has died
,08-23 18:35:22.226  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:22.237  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:22.242  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:22.265  1496  2116 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 18:35:22.266  1496  2116 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 18:35:22.266  1496  2116 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 18:35:22.266  1496  2116 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:22.294  3491  3491 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 18:35:22.294  3491  3491 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-23 18:35:22.295  3491  3491 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-23 18:35:23.154   872  1304 D ConnectivityService: handlePromptUnvalidated 101
,08-23 18:35:24.616  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:24.616  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:27.624  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:27.625  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c658d0 added. We now have 6 listener(s)
08-23 18:35:27.625  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:27.629  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:27.629  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@56360c9 added. We now have 7 listener(s)
08-23 18:35:27.629  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:27.631  3780  3830 I System.out: IsBluetoothEnabled
,08-23 18:35:27.642  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:27.692   872   889 I ActivityManager: Start proc 4186:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-23 18:35:27.809  4186  4186 D AdapterServiceConfig: Adding HeadsetService
,08-23 18:35:27.809  4186  4186 D AdapterServiceConfig: Adding A2dpService
08-23 18:35:27.809  4186  4186 D AdapterServiceConfig: Adding HidService
08-23 18:35:27.809  4186  4186 D AdapterServiceConfig: Adding HealthService
,08-23 18:35:27.810  4186  4186 D AdapterServiceConfig: Adding PanService
08-23 18:35:27.810  4186  4186 D AdapterServiceConfig: Adding GattService
,08-23 18:35:27.810  4186  4186 D AdapterServiceConfig: Adding BluetoothMapService
,08-23 18:35:27.826   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@668566e:true
08-23 18:35:27.826  4186  4186 D BluetoothAdapterState: make() - Creating AdapterState
,08-23 18:35:27.832  4186  4186 I bt_bluedroid: init
,08-23 18:35:27.833  4186  4198 I BluetoothAdapterState: Entering OffState
,08-23 18:35:27.840  4186  4199 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-23 18:35:27.840  4186  4199 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-23 18:35:27.841  4186  4199 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 18:35:27.841  4186  4199 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 18:35:27.843  4186  4186 I bt_bluedroid: get_profile_interface socket
,08-23 18:35:27.846  4186  4186 I bt_bluedroid: get_profile_interface sdp
,08-23 18:35:27.849  4186  4202 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 18:35:27.852  4186  4197 I bt_bluedroid: config_hci_snoop_log
,08-23 18:35:27.852  4186  4202 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 18:35:27.856   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 18:35:27.865  4186  4198 D BluetoothAdapterState: Current state: OFF, message: 0
,08-23 18:35:27.866  4186  4198 D BluetoothAdapterProperties: Setting state to 14
,08-23 18:35:27.866  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-23 18:35:27.873  4186  4198 D BluetoothBondStateMachine: make
,08-23 18:35:27.877  4186  4203 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 18:35:27.886  4186  4198 I BluetoothAdapterState: Entering PendingCommandState
,08-23 18:35:27.890  4186  4186 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-23 18:35:27.904  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:27.906  4186  4186 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 18:35:27.909  4186  4186 D BtGatt.GattService: Received start request. Starting profile...
08-23 18:35:27.909  4186  4186 D BtGatt.GattService: start()
08-23 18:35:27.909  4186  4186 I bt_bluedroid: get_profile_interface gatt
,08-23 18:35:27.912  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:27.912  4186  4186 D BtGatt.AdvertiseManager: advertise manager created
,08-23 18:35:27.925  4186  4186 V BluetoothAdapterState: isTurningOff()=false
,08-23 18:35:27.926  4186  4186 V BluetoothAdapterState: isTurningOn()=false
08-23 18:35:27.926  4186  4186 V BluetoothAdapterState: isBleTurningOn()=true
08-23 18:35:27.927  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:27.928  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-23 18:35:27.929  4186  4198 I bt_bluedroid: enable
,08-23 18:35:27.930  4186  4199 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-23 18:35:27.930  4186  4199 I bt_hci  : start_up
,08-23 18:35:27.949  4186  4199 I bt_vendor: alloc value 0xb3a71189
,08-23 18:35:27.949  4186  4199 I bt_vendor: init
08-23 18:35:27.949  4186  4199 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-23 18:35:27.950  4186  4199 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-23 18:35:28.056  4186  4199 D bt_hci  : start_up starting async portion
,08-23 18:35:28.057  4186  4206 I bt_hci  : event_finish_startup
,08-23 18:35:28.057  4186  4206 I bt_hci_h4: hal_open
08-23 18:35:28.057  4186  4206 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-23 18:35:28.068  4186  4206 I bt_userial_vendor: device fd = 51 open
,08-23 18:35:28.100  4186  4206 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 18:35:28.131  4186  4206 D bt_hwcfg: Chipset BCM4354A2
,08-23 18:35:28.131  4186  4206 D bt_hwcfg: Target name = [BCM4354A2]
,08-23 18:35:28.132  4186  4206 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-23 18:35:28.805  4186  4206 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-23 18:35:28.806  4186  4206 D bt_hwcfg: Settlement delay -- 100 ms
08-23 18:35:28.806  4186  4206 I bt_hwcfg: Setting fw settlement delay to 100 
,08-23 18:35:28.923  4186  4206 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 18:35:28.924  4186  4206 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-23 18:35:28.954  4186  4206 I bt_hwcfg: vendor lib fwcfg completed
08-23 18:35:28.954  4186  4206 I bt_vendor: firmware callback
,08-23 18:35:28.955  4186  4206 I bt_hci  : firmware_config_callback
,08-23 18:35:28.968  4186  4209 I bt_btu  : btu_task pending for preload complete event
,08-23 18:35:28.968  4186  4209 I bt_btu_task: Bluetooth chip preload is complete
,08-23 18:35:28.968  4186  4209 I bt_btu  : btu_task received preload complete event
,08-23 18:35:28.979  4186  4209 I         : BTE_InitTraceLevels -- TRC_HCI
,08-23 18:35:28.979  4186  4209 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-23 18:35:28.980  4186  4209 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-23 18:35:28.980  4186  4209 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-23 18:35:28.980  4186  4209 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-23 18:35:28.980  4186  4209 I         : BTE_InitTraceLevels -- TRC_A2D
,08-23 18:35:28.981  4186  4209 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 18:35:28.981  4186  4209 I         : BTE_InitTraceLevels -- TRC_BTM
,08-23 18:35:28.982  4186  4209 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 18:35:28.982  4186  4209 I         : BTE_InitTraceLevels -- TRC_PAN
,08-23 18:35:28.982  4186  4209 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 18:35:28.983  4186  4209 I         : BTE_InitTraceLevels -- TRC_GATT
,08-23 18:35:28.983  4186  4209 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 18:35:28.983  4186  4209 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-23 18:35:28.984  4186  4209 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 18:35:29.120  4186  4209 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39eed9d
,08-23 18:35:29.120  4186  4209 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39eed9d 
,08-23 18:35:29.134  4186  4202 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-23 18:35:29.137  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-23 18:35:29.138  4186  4202 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 18:35:29.142  4186  4202 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 18:35:29.146  4186  4202 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:35:29.148  4186  4202 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 18:35:29.148  4186  4202 D bt_hci  : do_postload posting postload work item
08-23 18:35:29.149  4186  4206 I bt_hci  : event_postload
08-23 18:35:29.149  4186  4206 I bt_vendor: sco_config_cb
,08-23 18:35:29.149  4186  4206 I bt_hci  : sco_config_callback postload finished.
,08-23 18:35:29.150  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:29.152  4186  4202 D bt_bte_conf: Device ID record 1 : primary
,08-23 18:35:29.152  4186  4202 D bt_bte_conf:   vendorId            = 000f
,08-23 18:35:29.152  4186  4202 D bt_bte_conf:   vendorIdSource      = 0001
,08-23 18:35:29.152  4186  4202 D bt_bte_conf:   product             = 1200
,08-23 18:35:29.153  4186  4202 D bt_bte_conf:   version             = 1436
08-23 18:35:29.153  4186  4202 D bt_bte_conf:   clientExecutableURL = 
08-23 18:35:29.153  4186  4202 D bt_bte_conf:   serviceDescription  = 
,08-23 18:35:29.153  4186  4202 D bt_bte_conf:   documentationURL    = 
08-23 18:35:29.153  4186  4202 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-23 18:35:29.154  4186  4199 D bt_stack_manager: event_start_up_stack finished
,08-23 18:35:29.156  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-23 18:35:29.156  4186  4198 D BluetoothAdapterProperties: Setting state to 15
,08-23 18:35:29.157  4186  4206 I bt_vendor: low_power_mode_cb
08-23 18:35:29.156  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-23 18:35:29.161  4186  4198 I BluetoothAdapterState: Entering BleOnState
08-23 18:35:29.163  4186  4198 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-23 18:35:29.164  4186  4198 D BluetoothAdapterProperties: Setting state to 11
08-23 18:35:29.164  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-23 18:35:29.170  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:29.175  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
08-23 18:35:29.176  4186  4186 D HeadsetService: Received start request. Starting profile...
08-23 18:35:29.179  4186  4186 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 18:35:29.180  4186  4186 D HeadsetStateMachine: make
,08-23 18:35:29.197  4186  4186 D HeadsetStateMachine: max_hf_connections = 1
08-23 18:35:29.199  4186  4198 I BluetoothAdapterState: Entering PendingCommandState
,08-23 18:35:29.200  4186  4186 I bt_bluedroid: get_profile_interface handsfree
,08-23 18:35:29.200  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-23 18:35:29.201  4186  4202 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-23 18:35:29.205  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:29.205  4186  4186 D A2dpService: Received start request. Starting profile...
08-23 18:35:29.206  4186  4186 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-23 18:35:29.206  4186  4186 I bt_bluedroid: get_profile_interface avrcp
,08-23 18:35:29.211  4186  4186 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 18:35:29.211  4186  4186 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 18:35:29.211  4186  4186 D A2dpStateMachine: make
,08-23 18:35:29.212  4186  4186 I bt_bluedroid: get_profile_interface a2dp
,08-23 18:35:29.213  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-23 18:35:29.214  4186  4218 D A2dpStateMachine: Enter Disconnected: -2
,08-23 18:35:29.214  4186  4186 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 18:35:29.215  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:29.216  4186  4186 D HidService: Received start request. Starting profile...
,08-23 18:35:29.216  4186  4186 I bt_bluedroid: get_profile_interface hidhost
08-23 18:35:29.216  4186  4186 D HidService: setHidService(): set to: null
,08-23 18:35:29.216  4186  4202 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d03e5
08-23 18:35:29.216  4186  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-23 18:35:29.218  4186  4186 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 18:35:29.219  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:29.219  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:29.219  4186  4186 D HealthService: Received start request. Starting profile...
,08-23 18:35:29.221  4186  4186 I bt_bluedroid: get_profile_interface health
,08-23 18:35:29.222  4186  4186 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-23 18:35:29.223  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
08-23 18:35:29.224  4186  4186 D PanService: Received start request. Starting profile...
,08-23 18:35:29.224  4186  4186 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 18:35:29.224  4186  4186 I bt_bluedroid: get_profile_interface pan
08-23 18:35:29.226  4186  4202 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 18:35:29.231  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:29.231  4186  4186 D BluetoothMapService: Received start request. Starting profile...
,08-23 18:35:29.231  4186  4186 D BluetoothMapService: start()
,08-23 18:35:29.235  4186  4186 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-23 18:35:29.237  4186  4186 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-23 18:35:29.237  4186  4186 D BluetoothMapAppObserver: createReceiver()
08-23 18:35:29.238  4186  4186 D BluetoothMapAppObserver: initObservers()
,08-23 18:35:29.238  4186  4186 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-23 18:35:29.244  4186  4186 V BluetoothAdapterState: isTurningOff()=false
08-23 18:35:29.244  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-23 18:35:29.244  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 18:35:29.245  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:29.247  4186  4216 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 18:35:29.248  4186  4186 V BluetoothAdapterState: isTurningOff()=false
,08-23 18:35:29.248  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-23 18:35:29.248  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 18:35:29.248  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:29.248  4186  4186 V BluetoothAdapterState: isTurningOff()=false
08-23 18:35:29.248  4186  4186 V BluetoothAdapterState: isTurningOn()=true
,08-23 18:35:29.248  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:29.248  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:29.251  4186  4186 V BluetoothAdapterState: isTurningOff()=false
,08-23 18:35:29.251  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-23 18:35:29.251  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 18:35:29.251  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:29.251  4186  4186 V BluetoothAdapterState: isTurningOff()=false
08-23 18:35:29.252  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-23 18:35:29.252  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:29.252  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 18:35:29.252  4186  4186 V BluetoothAdapterState: isTurningOff()=false
08-23 18:35:29.252  4186  4186 V BluetoothAdapterState: isTurningOn()=true
08-23 18:35:29.252  4186  4186 V BluetoothAdapterState: isBleTurningOn()=false
08-23 18:35:29.252  4186  4186 V BluetoothAdapterState: isBleTurningOff()=false
08-23 18:35:29.252  4186  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-23 18:35:29.252  4186  4198 D BluetoothAdapterProperties: ScanMode =  20
08-23 18:35:29.253  4186  4198 D BluetoothAdapterProperties: State =  11
08-23 18:35:29.255  4186  4202 D BluetoothAdapterProperties: Scan Mode:21
08-23 18:35:29.256  4186  4198 D BluetoothAdapterProperties: Setting state to 12
,08-23 18:35:29.256  4186  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 18:35:29.256  4186  4202 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 18:35:29.256   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:35:29.256  4186  4198 I BluetoothAdapterState: Entering OnState
,08-23 18:35:29.256  3849  4179 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:35:29.257   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:35:29.257  3849  3862 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 18:35:29.259  3849  3861 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 18:35:29.259  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:29.259  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:29.259  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:29.259  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:29.259  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:29.259  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:29.259  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:29.259  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:29.260  3849  3849 D BluetoothA2dp: Proxy object connected
,08-23 18:35:29.261  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:29.263   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 18:35:29.263   872   872 D BluetoothA2dp: Proxy object connected
08-23 18:35:29.263  3849  3861 D BluetoothPan: onBluetoothStateChange on: true
,08-23 18:35:29.264  3849  3849 D BluetoothMap: Proxy object connected
08-23 18:35:29.264  3849  3849 D MapProfile: Bluetooth service connected
,08-23 18:35:29.264  3849  3849 D BluetoothMap: getConnectedDevices()
08-23 18:35:29.265  1346  4092 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 18:35:29.266  4186  4186 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-23 18:35:29.266  4186  4186 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-23 18:35:29.268  1346  1346 D BluetoothA2dp: Proxy object connected
,08-23 18:35:29.268  4186  4186 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:35:29.269  1346  1982 D BluetoothMap: onBluetoothStateChange: up=true
08-23 18:35:29.271  1346  1346 D BluetoothMap: Proxy object connected
,08-23 18:35:29.271  1346  1346 D MapProfile: Bluetooth service connected
08-23 18:35:29.271  1346  1346 D BluetoothMap: getConnectedDevices()
08-23 18:35:29.271  4186  4186 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
08-23 18:35:29.271  3849  4179 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 18:35:29.273  4186  4186 D ObexServerSockets: Succeed to create listening sockets 
08-23 18:35:29.273  4186  4186 D ObexServerSockets0: startAccept()
08-23 18:35:29.273  4186  4186 D ObexServerSockets0: prepareForNewConnect()
,08-23 18:35:29.275  1904  2077 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:35:29.275  1346  1358 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 18:35:29.276  4186  4186 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-23 18:35:29.276  4186  4186 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-23 18:35:29.277  4186  4224 D ObexServerSockets0: Accepting socket connection...
08-23 18:35:29.277  3849  3849 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 18:35:29.277   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:35:29.278  3849  3861 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 18:35:29.279  4186  4225 D ObexServerSockets0: Accepting socket connection...
08-23 18:35:29.278  1346  1346 D BluetoothInputDevice: Proxy object connected
,08-23 18:35:29.280  1346  1346 D HidProfile: Bluetooth service connected
08-23 18:35:29.278  3849  3849 D PanProfile: Bluetooth service connected
08-23 18:35:29.280  3849  3849 D BluetoothInputDevice: Proxy object connected
,08-23 18:35:29.280  3849  3849 D HidProfile: Bluetooth service connected
08-23 18:35:29.281  1346  1357 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:35:29.282  1346  1982 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 18:35:29.283  1346  1358 D BluetoothPan: onBluetoothStateChange on: true
,08-23 18:35:29.285  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 18:35:29.285  1346  1346 D PanProfile: Bluetooth service connected
,08-23 18:35:29.286   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-23 18:35:29.287  4186  4186 D BluetoothMapService: onReceive
,08-23 18:35:29.287  4186  4186 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:29.287  4186  4186 D BluetoothMapService: STATE_ON
,08-23 18:35:29.289  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:29.291  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:29.296  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:29.298  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:29.308  3849  3849 D BluetoothPbap: Proxy object connected
,08-23 18:35:29.308  1346  1346 D BluetoothPbap: Proxy object connected
08-23 18:35:29.308  3849  3849 D PbapServerProfile: Bluetooth service connected
08-23 18:35:29.308  1346  1346 D PbapServerProfile: Bluetooth service connected
,08-23 18:35:29.314  4186  4186 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-23 18:35:29.314  4186  4186 D ObexServerSockets0: prepareForNewConnect()
08-23 18:35:29.316  4186  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:29.330  4186  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:29.331  4186  4233 I BtOppRfcommListener: Accept thread started.
,08-23 18:35:29.357   872   872 D BluetoothHeadset: Proxy object connected
,08-23 18:35:29.358  1346  1358 D BluetoothHeadset: Proxy object connected
08-23 18:35:29.358   872   889 D BluetoothHeadset: Proxy object connected
,08-23 18:35:29.358  1346  1346 D HeadsetProfile: Bluetooth service connected
,08-23 18:35:29.358  1904  2215 D BluetoothHeadset: Proxy object connected
08-23 18:35:29.358   872   872 D BluetoothHeadset: Proxy object connected
08-23 18:35:29.359  3849  3862 D BluetoothHeadset: Proxy object connected
08-23 18:35:29.359   872   872 D BluetoothHeadset: Proxy object connected
08-23 18:35:29.359  3849  3849 D HeadsetProfile: Bluetooth service connected
,08-23 18:35:29.375  1904  1919 D BluetoothHeadset: Proxy object connected
,08-23 18:35:29.378   872   889 D BluetoothHeadset: Proxy object connected
,08-23 18:35:29.381  1346  1982 D BluetoothHeadset: Proxy object connected
,08-23 18:35:29.382  1346  1346 D HeadsetProfile: Bluetooth service connected
,08-23 18:35:29.668  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:29.668  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:29.668  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:29.668  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:29.668  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:29.668  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:29.668  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:29.668  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:29.675  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:29.678  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:29.679  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@743a3ce added. We now have 8 listener(s)
,08-23 18:35:29.679  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:29.685   872   882 D WifiService: setWifiEnabled: false pid=3780, uid=10000
08-23 18:35:29.685   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 18:35:29.698  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:29.699   872  1931 D WifiService: setWifiEnabled: true pid=3780, uid=10000
,08-23 18:35:29.699   872  1931 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 18:35:29.711   872  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-23 18:35:29.731  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:29.731  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:29.731  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:29.731  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:29.731  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:29.731  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:29.731  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:29.731  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:29.734  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:29.755   872  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-23 18:35:29.756   872  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-23 18:35:29.756   872  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-23 18:35:29.757   872  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-23 18:35:29.757   872  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-23 18:35:29.757   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-23 18:35:29.758   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-23 18:35:29.771   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-23 18:35:29.771   872  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.66 rxSuccessRate=0.78 delta 1000 -> 1000
,08-23 18:35:29.772   370   870 D CommandListener: Setting iface cfg
,08-23 18:35:29.773   872  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
,08-23 18:35:29.773   872  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 18:35:29.785   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-23 18:35:29.786   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 18:35:29.795   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-23 18:35:29.825   872  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-23 18:35:29.826   872  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-23 18:35:29.855   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-23 18:35:29.857  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-23 18:35:30.391  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 18:35:30.439  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 18:35:30.439  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-23 18:35:30.448   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 18:35:30.461   872  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 18:35:30.462   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-23 18:35:30.462   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 18:35:30.480   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 18:35:30.497   370   870 D CommandListener: Setting iface cfg
,08-23 18:35:30.500   872  1302 D WifiStateMachine: Start Dhcp Watchdog 3
,08-23 18:35:30.524   872  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-23 18:35:30.524   872  1304 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-23 18:35:30.526   872  4241 D DhcpClient: Receive thread started
,08-23 18:35:30.527   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-23 18:35:30.618   872  1302 E native  : do suspend false
,08-23 18:35:30.639   872  1868 D DhcpClient: Broadcasting DHCPDISCOVER
,08-23 18:35:30.654   872  4241 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172784, domain null
,08-23 18:35:30.655   872  1868 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172784 seconds
,08-23 18:35:30.660   872  1868 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-23 18:35:30.673   872  4241 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-23 18:35:30.674   872  1868 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-23 18:35:30.679   370   870 D CommandListener: Setting iface cfg
,08-23 18:35:30.692   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-23 18:35:30.693   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-23 18:35:30.693   872  1868 D DhcpClient: Scheduling renewal in 86399s
,08-23 18:35:30.710   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 18:35:30.710   872   892 I Adreno  : Build Date                       : 10/20/15
08-23 18:35:30.710   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 18:35:30.710   872   892 I Adreno  : Local Branch                     : M14
08-23 18:35:30.710   872   892 I Adreno  : Remote Branch                    : 
08-23 18:35:30.710   872   892 I Adreno  : Remote Branch                    : 
08-23 18:35:30.710   872   892 I Adreno  : Reconstruct Branch               : 
,08-23 18:35:30.714   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-23 18:35:30.716  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-23 18:35:30.720  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:30.720  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:30.720  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:30.720  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:30.720  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:30.720  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:30.720  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:30.720  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:30.722  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:30.722   872  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 18:35:30.723   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-23 18:35:30.727   872  1304 D ConnectivityService: Adding iface wlan0 to network 102
,08-23 18:35:30.726  3780  3830 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-23 18:35:30.737   872  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-23 18:35:30.739  3780  3830 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-23 18:35:30.743  3780  3830 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@57446d1 Bundle[{}]
,08-23 18:35:30.748  3780  3830 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 18:35:30.750  3780  3830 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 18:35:30.752  3780  3830 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 18:35:30.752  3780  3830 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 18:35:30.753  3780  3830 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 18:35:30.754  3780  3830 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 18:35:30.760  3780  3830 I System.out: Running OutgoingSocketThread
,08-23 18:35:30.766  3780  4245 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
08-23 18:35:30.768  3780  4245 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40358
,08-23 18:35:30.768  3780  4245 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-23 18:35:30.770   280   368 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (137 us)
08-23 18:35:30.772   872  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 18:35:30.772   872  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-23 18:35:30.773   872  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-23 18:35:30.776   872  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-23 18:35:30.778   872  1304 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-23 18:35:30.789   872  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-23 18:35:30.796   872  1304 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-23 18:35:30.796   872  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-23 18:35:30.796   872  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-23 18:35:30.797   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 18:35:30.797   872  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-23 18:35:30.797   872  1304 D ConnectivityService:    accepting network in place of null
,08-23 18:35:30.799   872  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 18:35:30.804   872  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=150476, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 18:35:30.837   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 18:35:30.871   872  4239 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:80a::200e
,08-23 18:35:30.872   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 18:35:30.876   872  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-23 18:35:30.876   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:35:30.877   872  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-23 18:35:30.884   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-23 18:35:30.900  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:30.900  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:30.900  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:30.900  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:30.900  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:30.900  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:30.900  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:30.900  3780  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:30.902  3780  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:30.907  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 18:35:30.915  1738  1738 D SystemUpdateService: onCreate
,08-23 18:35:30.919  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 18:35:30.935  1738  4253 I SystemUpdateService: active receiver: enabled
,08-23 18:35:30.945  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 18:35:30.951  1738  2406 I iu.UploadsManager: num queued entries: 0
08-23 18:35:30.951   872  4239 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 16:35:30 GMT], X-Android-Received-Millis=[1471970130950], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471970130929]}
08-23 18:35:30.951  1738  2406 I iu.UploadsManager: num updated entries: 0
08-23 18:35:30.951   872  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-23 18:35:30.951   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-23 18:35:30.952   872  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-23 18:35:30.952   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-23 18:35:30.958  1738  4253 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 18:35:30.960  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-23 18:35:30.960  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-23 18:35:30.962  3945  3945 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:30.968  1738  4256 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-23 18:35:30.968  1738  4256 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 18:35:30.968  3945  3945 D SprintDMHelper: simOperator: 
,08-23 18:35:30.968  3945  3945 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 18:35:30.979  1738  4256 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 18:35:31.000  1738  4253 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-23 18:35:31.002  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:31.005  1738  4253 I SystemUpdateService: now status is 0 (complete)
,08-23 18:35:31.005  1738  4253 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-23 18:35:31.005  1738  4253 I SystemUpdateService: file has been verified
,08-23 18:35:31.005  1738  4253 I SystemUpdateService: OTA package size = 12249756
,08-23 18:35:31.006  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 18:35:31.008  1738  2406 I iu.SyncManager: NEXT; no task
,08-23 18:35:31.022  1738  4253 I SystemUpdateService: showing system update notification
,08-23 18:35:31.034  1738  1738 D SystemUpdateService: onDestroy,
,08-23 18:35:31.036  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-23 18:35:31.036  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-23 18:35:31.036  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 18:35:31.036  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 18:35:31.050  1738  4256 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-23 18:35:31.117  3903  4259 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-23 18:35:31.364  3780  3780 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 18:35:31.364  3780  3780 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 18:35:31.404   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-23 18:35:31.411  3780  3780 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@57446d1 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@309b2ef, 16908290=android.view.AbsSavedState$1@309b2ef}, android:focusedViewId=100}]}]
,08-23 18:35:31.411  3780  3780 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 18:35:31.412  3780  3780 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 18:35:31.412  3780  3780 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 18:35:31.415   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-23 18:35:31.423   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-23 18:35:31.423   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-23 18:35:31.424   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-23 18:35:31.651   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-23 18:35:31.654   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-23 18:35:31.661   872  1326 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,08-23 18:35:31.667   872   892 I DreamManagerService: Entering dreamland.
,08-23 18:35:31.668   872   892 I PowerManagerService: Dozing...
08-23 18:35:31.669   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-23 18:35:31.718   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-23 18:35:31.718   374   374 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-23 18:35:31.724   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 18:35:31.737  1895  4266 D NfcService: Discovery configuration equal, not updating.
08-23 18:35:31.738   872  1302 E native  : do suspend false
,08-23 18:35:31.753   872  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 18:35:31.770  3780  3830 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,08-23 18:35:31.771  3780  3830 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,08-23 18:35:31.776   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 18:35:31.779  3780  3830 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,08-23 18:35:31.781  3780  3830 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-23 18:35:31.782  3780  3830 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-23 18:35:31.783   872  1302 E native  : do suspend true
,08-23 18:35:31.789  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:35:31.789  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38031fc added. We now have 2 listener(s)
,08-23 18:35:31.797  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 18:35:31.797  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 18:35:31.797  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 18:35:31.799  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:31.799  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b84085 added. We now have 9 listener(s)
08-23 18:35:31.800  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:31.801  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:31.804  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:31.813  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:31.813  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:31.813  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:31.813  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:31.813  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:31.813  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:31.813  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:31.813  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:31.816  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:31.817  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:35:31.818  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:35:31.819  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d688f0b added. We now have 3 listener(s)
,08-23 18:35:31.819  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:31.823  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:31.825  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 18:35:31.826  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 18:35:31.826  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 18:35:31.826  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:31.827  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9c71e8 added. We now have 10 listener(s)
08-23 18:35:31.827  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:31.827  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:31.828  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:31.828  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:31.828  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 18:35:31.828  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:31.829  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:31.829  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 18:35:31.829  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38031fc removed from the list
,08-23 18:35:31.829  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:31.830  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b84085 removed from the list
,08-23 18:35:31.830  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 18:35:31.830  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:31.831  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:31.831  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:31.834  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:31.834  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:31.834  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:31.835  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b84085 not in the list
,08-23 18:35:31.835  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:31.835  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:31.838  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:31.839  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:31.839  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:31.839  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9c71e8 removed from the list
,08-23 18:35:31.839  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:31.839  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:31.839  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:31.839  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 18:35:31.840  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d688f0b removed from the list
,08-23 18:35:31.841  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:31.841  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c16001 added. We now have 2 listener(s)
08-23 18:35:31.845  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 18:35:31.845  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 18:35:31.845  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:31.845  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:31.846  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c5ea6 added. We now have 9 listener(s)
,08-23 18:35:31.846  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:31.847  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:31.851  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:31.856   374  1310 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-23 18:35:31.856   374  1310 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-23 18:35:31.860  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:31.860  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:31.860  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:31.860  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:31.860  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:31.860  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:31.860  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:31.860  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:31.863  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:31.864  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:31.864  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:35:31.865  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bac494 added. We now have 3 listener(s)
,08-23 18:35:31.869  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:31.873  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 18:35:31.873  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:31.873  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 18:35:31.874  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:31.874  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e2fb3d added. We now have 10 listener(s)
,08-23 18:35:31.875  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:31.875  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-23 18:35:31.875  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:31.875  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 18:35:31.875  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 18:35:31.875  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:31.875  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:35:31.883  3780  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 18:35:31.884  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 18:35:31.889  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:31.890  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 18:35:31.890  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 18:35:31.894  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 18:35:31.895  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 18:35:31.895  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 18:35:31.896  3780  3830 D BluetoothAdapter: STATE_ON
08-23 18:35:31.901  4186  4196 D BtGatt.GattService: registerClient() - UUID=bb90c24d-2499-4183-9243-d1a1715a01b1
,08-23 18:35:31.902  4186  4202 D BtGatt.GattService: onClientRegistered() - UUID=bb90c24d-2499-4183-9243-d1a1715a01b1, clientIf=5
,08-23 18:35:31.904  3780  3791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 18:35:31.905  4186  4214 D BtGatt.GattService: start scan with filters
,08-23 18:35:31.909  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 18:35:31.909  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 18:35:31.909  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:31.910  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 18:35:31.910  4186  4205 D BtGatt.ScanManager: handling starting scan
,08-23 18:35:31.913  4186  4205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3998c6a
,08-23 18:35:31.917  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:31.917  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:31.918  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 18:35:31.920  4186  4202 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
08-23 18:35:31.920  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:31.922  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:31.922  4186  4205 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 18:35:31.926  3780  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 18:35:31.926  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:35:31.926  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 18:35:31.926  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:31.926  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 18:35:31.926  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 18:35:31.926  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 18:35:31.927  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:31.927  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:35:31.927  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:31.927  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 18:35:31.928  3780  3830 D BluetoothAdapter: STATE_ON
08-23 18:35:31.929  4186  4197 D BtGatt.GattService: stopScan() - queue size =1
,08-23 18:35:31.930  4186  4223 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 18:35:31.930  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:35:31.930  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 18:35:31.931  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 18:35:31.931  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 18:35:31.931  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 18:35:31.932  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:31.932  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 18:35:31.933  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 18:35:31.933  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:35:31.933  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:31.934  4186  4202 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 18:35:31.934  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:31.935  4186  4205 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 18:35:31.935  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 18:35:31.935  4186  4205 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 18:35:31.935  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:31.935  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:31.938  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 18:35:31.938  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:31.938  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:31.938  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:31.938  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:31.939  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:31.939  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:31.939  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c16001 removed from the list
08-23 18:35:31.939  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:31.939  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c5ea6 removed from the list
08-23 18:35:31.939  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:31.939  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:31.940  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:31.940  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:31.941  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:31.942  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:31.942  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:31.942  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c5ea6 not in the list
08-23 18:35:31.942  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:31.942  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:31.943  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:31.943  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:31.943  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:31.943  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e2fb3d removed from the list
,08-23 18:35:31.943  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 18:35:31.943  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:31.944  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:31.944  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 18:35:31.944  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bac494 removed from the list
08-23 18:35:31.945  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:31.945  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c890e39 added. We now have 2 listener(s)
08-23 18:35:31.946  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 18:35:31.946  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:31.947  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:31.947  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:31.947  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c69c7e added. We now have 9 listener(s)
,08-23 18:35:31.947  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:31.947  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:31.948  4186  4202 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 18:35:31.948  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:31.950  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:31.955  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:31.955  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:31.955  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:31.955  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:31.955  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:31.955  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:31.955  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:31.955  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:31.956  4186  4202 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 18:35:31.956  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:31.958  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:31.958  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:31.960  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:31.960  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c32122c added. We now have 3 listener(s)
08-23 18:35:31.961  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:31.962  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 18:35:31.964  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:31.963  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:31.964  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:31.964  4186  4202 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 18:35:31.964  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:31.964  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:31.964  4186  4205 D BtGatt.ScanManager: stopping BLe Batch
08-23 18:35:31.964  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce354f5 added. We now have 10 listener(s)
08-23 18:35:31.964  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:31.965  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:31.966  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:31.966  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:31.966  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:35:31.966  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:31.966  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:35:31.970  3780  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 18:35:31.970  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 18:35:31.974  4186  4202 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 18:35:31.974  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:31.974  4186  4205 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 18:35:31.976  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:31.977  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 18:35:31.977  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:31.981  4186  4202 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 18:35:31.981  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:31.981  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 18:35:31.982  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 18:35:31.982  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 18:35:31.982  3780  3830 D BluetoothAdapter: STATE_ON
,08-23 18:35:31.985  4186  4214 D BtGatt.GattService: registerClient() - UUID=7340d76c-2333-448e-9fc5-d59c661a91e1
,08-23 18:35:31.985  4186  4202 D BtGatt.GattService: onClientRegistered() - UUID=7340d76c-2333-448e-9fc5-d59c661a91e1, clientIf=5
08-23 18:35:31.985  3780  3791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 18:35:31.986  4186  4197 D BtGatt.GattService: start scan with filters
,08-23 18:35:31.988  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 18:35:31.988  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 18:35:31.988  4186  4205 D BtGatt.ScanManager: handling starting scan
08-23 18:35:31.988  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 18:35:31.988  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 18:35:31.991  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 18:35:31.991  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 18:35:31.991  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 18:35:31.993  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:31.994  4186  4202 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 18:35:31.994  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:31.994  4186  4205 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 18:35:31.996  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 18:35:31.996  3780  3830 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-23 18:35:31.996  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:31.997  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:31.997  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 18:35:31.997  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:31.997  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:31.997  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 18:35:31.997  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:31.997  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c890e39 removed from the list
,08-23 18:35:31.997  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:31.998  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c69c7e removed from the list
,08-23 18:35:31.998  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:31.998  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:31.998  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:31.998  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-23 18:35:31.998  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:31.998  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:31.999  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:32.000  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:32.000  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:32.000  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c69c7e not in the list
08-23 18:35:32.000  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:32.000  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:32.000  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:35:32.000  4186  4202 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-23 18:35:32.000  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:32.000  4186  4205 D BtGatt.ScanManager: Starting BLE batch scan
08-23 18:35:32.000  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:32.000  4186  4205 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 18:35:32.000  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 18:35:32.001  3780  3830 D BluetoothAdapter: STATE_ON
,08-23 18:35:32.002  4186  4196 D BtGatt.GattService: stopScan() - queue size =1
08-23 18:35:32.002  4186  4223 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 18:35:32.003  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:35:32.003  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 18:35:32.003  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 18:35:32.003  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 18:35:32.003  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 18:35:32.004  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:32.004  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 18:35:32.005  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 18:35:32.005  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 18:35:32.005  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:32.006  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:32.006  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:32.007  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:32.007  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:32.007  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:32.007  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:32.007  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce354f5 removed from the list
08-23 18:35:32.007  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:32.007  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:32.007  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:32.007  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:32.007  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c32122c removed from the list
08-23 18:35:32.008  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:32.008  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c614b71 added. We now have 2 listener(s)
,08-23 18:35:32.010  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 18:35:32.010  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:32.011  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 18:35:32.011  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:32.011  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cfbd56 added. We now have 9 listener(s)
08-23 18:35:32.011  4186  4202 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 18:35:32.011  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:32.011  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:32.012  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:32.014  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:32.017  4186  4202 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 18:35:32.017  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:32.018  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-23 18:35:32.018  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:32.018  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:32.018  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:32.018  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:32.018  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:32.018  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:32.018  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:32.020  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:32.021  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:35:32.022  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:35:32.022  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1627ac4 added. We now have 3 listener(s)
,08-23 18:35:32.023  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:32.024  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 18:35:32.024  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 18:35:32.024  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:32.025  4186  4202 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 18:35:32.025  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:32.025  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fee2dad added. We now have 10 listener(s)
08-23 18:35:32.025  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:32.025  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:32.025  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 18:35:32.025  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:32.025  4186  4205 D BtGatt.ScanManager: stopping BLe Batch
,08-23 18:35:32.025  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 18:35:32.026  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:32.025  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:32.026  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:35:32.028  3780  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 18:35:32.028  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 18:35:32.032  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:32.032  4186  4202 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-23 18:35:32.032  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:32.033  4186  4205 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-23 18:35:32.033  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 18:35:32.033  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:32.035  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 18:35:32.035  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 18:35:32.036  3780  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 18:35:32.036  3780  3830 D BluetoothAdapter: STATE_ON
,08-23 18:35:32.038  4186  4202 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-23 18:35:32.038  4186  4214 D BtGatt.GattService: registerClient() - UUID=6f6fb530-2418-4ecb-be41-f2a6c7757bc0
,08-23 18:35:32.038  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:32.039  4186  4202 D BtGatt.GattService: onClientRegistered() - UUID=6f6fb530-2418-4ecb-be41-f2a6c7757bc0, clientIf=5
08-23 18:35:32.039  3780  3792 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 18:35:32.040  4186  4223 D BtGatt.GattService: start scan with filters
,08-23 18:35:32.042  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 18:35:32.042  4186  4205 D BtGatt.ScanManager: handling starting scan
08-23 18:35:32.042  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 18:35:32.042  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:32.042  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 18:35:32.044  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:32.044  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 18:35:32.044  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:32.046  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:32.047  4186  4202 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 18:35:32.047  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:32.048  4186  4205 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 18:35:32.049  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 18:35:32.050  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:32.050  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:32.050  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:32.050  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:32.050  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 18:35:32.050  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:32.050  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c614b71 removed from the list
08-23 18:35:32.050  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:32.050  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cfbd56 removed from the list
08-23 18:35:32.050  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:32.050  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:32.051  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:32.051  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-23 18:35:32.051  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:32.051  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:32.052  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:32.052  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:32.052  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:32.052  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cfbd56 not in the list
,08-23 18:35:32.052  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:32.052  4186  4202 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 18:35:32.052  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-23 18:35:32.053  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:35:32.053  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 18:35:32.053  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:32.053  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 18:35:32.053  4186  4205 D BtGatt.ScanManager: Starting BLE batch scan
08-23 18:35:32.053  4186  4205 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 18:35:32.053  3780  3830 D BluetoothAdapter: STATE_ON
08-23 18:35:32.054  4186  4223 D BtGatt.GattService: stopScan() - queue size =1
,08-23 18:35:32.054  4186  4197 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 18:35:32.055  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 18:35:32.055  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 18:35:32.055  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 18:35:32.055  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 18:35:32.055  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 18:35:32.056  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:32.056  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-23 18:35:32.056  3780  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 18:35:32.056  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:35:32.057  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:32.057  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-23 18:35:32.058  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:32.058  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:32.058  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:32.058  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fee2dad removed from the list
08-23 18:35:32.058  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:32.058  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:32.058  3780  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:32.058  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:32.058  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:32.058  3780  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:32.058  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1627ac4 removed from the list
08-23 18:35:32.059  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:35:32.059  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ecf7a9 added. We now have 2 listener(s)
08-23 18:35:32.060  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 18:35:32.060  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:32.060  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 18:35:32.060  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:32.061  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f11212e added. We now have 9 listener(s)
08-23 18:35:32.061  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:32.061  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:32.062  4186  4202 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 18:35:32.062  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-23 18:35:32.063  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:32.066  3780  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:32.066  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:32.066  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:32.066  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:32.066  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:32.066  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:32.066  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:32.066  3780  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:32.067  4186  4202 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 18:35:32.067  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:32.068  3780  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:32.068  3780  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:35:32.068  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:32.068  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af45e5c added. We now have 3 listener(s)
08-23 18:35:32.070  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:32.071  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 18:35:32.071  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:32.071  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:32.071  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-23 18:35:32.071  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f46565 added. We now have 10 listener(s)
08-23 18:35:32.071  3780  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:32.071  3780  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:32.072  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:32.072  3780  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:32.072  3780  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:32.072  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:32.072  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:32.072  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:32.072  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:32.072  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ecf7a9 removed from the list
08-23 18:35:32.072  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:32.073  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f11212e removed from the list
,08-23 18:35:32.073  3780  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:32.073  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:32.073  4186  4202 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 18:35:32.073  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:32.073  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:32.073  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:32.073  4186  4205 D BtGatt.ScanManager: stopping BLe Batch
,08-23 18:35:32.074  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:32.074  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:32.074  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-23 18:35:32.074  3780  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f11212e not in the list
08-23 18:35:32.074  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:32.074  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:32.075  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:32.075  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:32.075  3780  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:32.075  3780  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f46565 removed from the list
08-23 18:35:32.075  3780  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 18:35:32.075  3780  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:32.075  3780  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:32.075  3780  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:32.075  3780  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af45e5c removed from the list
08-23 18:35:32.076  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
08-23 18:35:32.076  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-23 18:35:32.076  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-23 18:35:32.077  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:32.077  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-23 18:35:32.077  3780  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:32.079  4186  4202 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 18:35:32.079  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:32.080  4186  4205 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 18:35:32.083  3780  4270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
,08-23 18:35:32.083  3780  4270 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
08-23 18:35:32.083  3780  4270 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 18:35:32.085  4186  4202 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 18:35:32.085  4186  4202 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 18:35:32.086  3780  4271 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name),
08-23 18:35:32.086  3780  4271 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
08-23 18:35:32.086  3780  4271 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-23 18:35:32.088  3780  3830 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-23 18:35:32.088  3780  3830 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-23 18:35:32.088  3780  3830 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-23 18:35:32.089  3780  3830 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-23 18:35:32.089  3780  3830 D com.test.thalitest.ThaliTestRunner: Total duration: 22820 ms
08-23 18:35:32.090  3780  3830 I jxcore-log: Total number of executed tests:  80
08-23 18:35:32.090  3780  3830 I jxcore-log: 
,08-23 18:35:32.090  3780  3830 I jxcore-log: Number of passed tests:  80
08-23 18:35:32.090  3780  3830 I jxcore-log: 
08-23 18:35:32.091  3780  3830 I jxcore-log: Number of failed tests:  0
08-23 18:35:32.091  3780  3830 I jxcore-log: 
08-23 18:35:32.091  3780  3830 I jxcore-log: Number of ignored tests:  0
08-23 18:35:32.091  3780  3830 I jxcore-log: 
08-23 18:35:32.091  3780  3830 I jxcore-log: Total duration:  22820,
08-23 18:35:32.091  3780  3830 I jxcore-log: 
08-23 18:35:32.092  3780  3830 I jxcore-log: Is Android:  true
08-23 18:35:32.092  3780  3830 I jxcore-log: 
08-23 18:35:32.092  3780  3830 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
08-23 18:35:32.092  3780  3830 I jxcore-log: 
08-23 18:35:32.096  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.096  3780  3830 I jxcore-log: 
08-23 18:35:32.100  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.100  3780  3830 I jxcore-log: 
08-23 18:35:32.101  3780  3780 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 18:35:32.102  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.102  3780  3830 I jxcore-log: 
08-23 18:35:32.103  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.103  3780  3830 I jxcore-log: 
08-23 18:35:32.104  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.104  3780  3830 I jxcore-log: 
,08-23 18:35:32.106  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.106  3780  3830 I jxcore-log: 
,08-23 18:35:32.109  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.109  3780  3830 I jxcore-log: 
,08-23 18:35:32.111  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:35:32.111  3780  3830 I jxcore-log: 
,08-23 18:35:32.112  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:35:32.112  3780  3830 I jxcore-log: 
,08-23 18:35:32.113  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.113  3780  3830 I jxcore-log: 
08-23 18:35:32.114  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.114  3780  3830 I jxcore-log: 
,08-23 18:35:32.116  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 18:35:32.116  3780  3830 I jxcore-log: 
,08-23 18:35:32.117  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:35:32.117  3780  3830 I jxcore-log: 
,08-23 18:35:32.118  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:35:32.118  3780  3830 I jxcore-log: 
,08-23 18:35:32.119  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.119  3780  3830 I jxcore-log: 
,08-23 18:35:32.120  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.120  3780  3830 I jxcore-log: 
,08-23 18:35:32.121  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.121  3780  3830 I jxcore-log: 
08-23 18:35:32.121  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.121  3780  3830 I jxcore-log: 
,08-23 18:35:32.122  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.122  3780  3830 I jxcore-log: 
,08-23 18:35:32.123  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.123  3780  3830 I jxcore-log: 
,08-23 18:35:32.124  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.124  3780  3830 I jxcore-log: 
,08-23 18:35:32.124  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.124  3780  3830 I jxcore-log: 
,08-23 18:35:32.125  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.125  3780  3830 I jxcore-log: 
,08-23 18:35:32.127  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:35:32.127  3780  3830 I jxcore-log: 
,08-23 18:35:32.127  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-23 18:35:32.127  3780  3830 I jxcore-log: 
,08-23 18:35:32.128  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 18:35:32.128  3780  3830 I jxcore-log: 
,08-23 18:35:32.129  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-23 18:35:32.129  3780  3830 I jxcore-log: 
,08-23 18:35:32.131  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-23 18:35:32.131  3780  3830 I jxcore-log: 
,08-23 18:35:32.132  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.132  3780  3830 I jxcore-log: 
,08-23 18:35:32.133  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.133  3780  3830 I jxcore-log: ,
,08-23 18:35:32.134  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.134  3780  3830 I jxcore-log: 
,08-23 18:35:32.135  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:32.135  3780  3830 I jxcore-log: 
,08-23 18:35:32.436  3780  3780 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 18:35:32.438  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 18:35:32.438  3780  3830 I jxcore-log: 
,08-23 18:35:32.506  3780  3780 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 18:35:32.510  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 18:35:32.510  3780  3830 I jxcore-log: 
,08-23 18:35:32.558  3780  3780 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 18:35:32.562  3780  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 18:35:32.562  3780  3830 I jxcore-log: 
,08-23 18:35:32.825  4272  4272 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 18:35:32.830  4272  4272 D AndroidRuntime: CheckJNI is OFF
,08-23 18:35:32.872  4272  4272 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 18:35:32.919  4272  4272 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 18:35:32.942  4272  4272 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 18:35:32.953   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-23 18:35:32.954   872   885 I ActivityManager: Killing 3780:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-23 18:35:33.078   872   895 W PackageSettings: Skipping PackageSetting{46333cf com.example.hello/10273} due to missing metadata
,08-23 18:35:33.092   872  1303 D WifiService: Client connection lost with reason: 4
,08-23 18:35:33.092   872  1933 D GraphicsStats: Buffer count: 2
08-23 18:35:33.093   872   883 I WindowState: WIN DEATH: Window{319a605 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 18:35:33.115   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-23 18:35:33.116   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-23 18:35:33.116   872   895 I art     : Starting a blocking GC Explicit
,08-23 18:35:33.122   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-23 18:35:33.122   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-23 18:35:33.122   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.122   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.122   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 18:35:33.122   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-23 18:35:33.122   872   885 I ActivityManager:   Force finishing activity ActivityRecord{a9ec1a2 u0 com.test.thalitest/.MainActivity t2}
,08-23 18:35:33.135   872  1901 W ActivityManager: Spurious death for ProcessRecord{2e2abee 0:com.test.thalitest/u0a0}, curProc for 3780: null
,08-23 18:35:33.196   872   895 I art     : Explicit concurrent mark sweep GC freed 21092(1278KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 738us total 79.011ms
,08-23 18:35:33.241   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 18:35:33.247  4272  4272 I art     : System.exit called, status: 0
,08-23 18:35:33.247  4272  4272 I AndroidRuntime: VM exiting with result code 0.
,08-23 18:35:33.252   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-23 18:35:33.300   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-23 18:35:33.306  4186  4186 D BluetoothMapAppObserver: onReceive
08-23 18:35:33.306  4186  4186 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-23 18:35:33.310   872  1292 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 18:35:33.311  2127  2265 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 18:35:33.317  3651  3651 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-23 18:35:33.319  1851  1851 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-23 18:35:33.336  1851  4286 I Keyboard.Facilitator.DecoderInitializer: run()
,08-23 18:35:33.338  1851  4286 I Decoder : createOrResetDecoder
,08-23 18:35:33.353   872  1902 I ActivityManager: Start proc 4287:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-23 18:35:33.358  1496  1496 I ConfigService: onCreate
,08-23 18:35:33.365  1904  1904 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 18:35:33.399  1851  4286 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-23 18:35:33.420  4287  4287 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-23 18:35:33.421   872  1901 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3780 uid 10000
,08-23 18:35:33.422  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-23 18:35:33.423   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 18:35:33.437  1926  2010 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-23 18:35:33.442   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-23 18:35:33.442   872   884 E PackageManager: Failed to write settings, restoring backup
08-23 18:35:33.442   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 18:35:33.442   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 18:35:33.442   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 18:35:33.442   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 18:35:33.442   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 18:35:33.442   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.442   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.442   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 18:35:33.446   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-23 18:35:33.446   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 18:35:33.446   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 18:35:33.446   872   885 E DropBoxManagerService: 	... 13 more
,08-23 18:35:33.454   872  1901 I ActivityManager: Start proc 4301:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-23 18:35:33.454  1926  2010 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 18:35:33.454  1926  2010 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1926
08-23 18:35:33.454  1926  2010 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.454  1926  2010 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 18:35:33.456   872   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 18:35:33.461   872  4307 E DropBoxManagerService: Can't write: system_app_crash
08-23 18:35:33.461   872  4307 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 18:35:33.461   872  4307 E DropBoxManagerService: 	... 5 more
,08-23 18:35:33.461  1926  2010 I Process : Sending signal. PID: 1926 SIG: 9
08-23 18:35:33.464  1851  4286 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-23 18:35:33.470  1851  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-23 18:35:33.470  1851  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-23 18:35:33.475  1851  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-23 18:35:33.475  1851  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-23 18:35:33.476  1851  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-23 18:35:33.476  1851  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-23 18:35:33.482  1851  4286 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-23 18:35:33.482  1851  4286 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-23 18:35:33.482  1851  4286 I Keyboard.Facilitator.Delight2FileSweeper: run(),
08-23 18:35:33.483  1851  4286 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-23 18:35:33.483  1851  4286 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-23 18:35:33.483  1851  4286 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-23 18:35:33.488   872  1327 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-23 18:35:33.488   872  1327 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-23 18:35:33.488   872  1327 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,08-23 18:35:33.488   872  1327 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-23 18:35:33.488   872  1327 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
,08-23 18:35:33.488   872  1327 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-23 18:35:33.488   872  1327 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-23 18:35:33.489   872  1327 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
,08-23 18:35:33.489   872  1327 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-23 18:35:33.489   872  1327 W System.err: ,	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-23 18:35:33.489   872  1327 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-23 18:35:33.489   872  1327 W System.err: 	,... 4 more
08-23 18:35:33.489   872  1327 D skia    : ------- write threw an exception
,08-23 18:35:33.506  4287  4287 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-23 18:35:33.523   872  1933 I ActivityManager: Start proc 4318:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-23 18:35:33.525  4287  4320 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 18:35:33.534   872  1922 D GraphicsStats: Buffer count: 1
,08-23 18:35:33.534   872  1902 I WindowState: WIN DEATH: Window{d1b664b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-23 18:35:33.545   872   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1926) has died
,08-23 18:35:33.547   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-23 18:35:33.548   872   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-23 18:35:33.561  4287  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.561  4287  4320 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 18:35:33.566   872  1370 I ActivityManager: Start proc 4332:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 18:35:33.562  4287  4320 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-23 18:35:33.562  4287  4320 E AndroidRuntime: Process: android.process.acore, PID: 4287
08-23 18:35:33.562  4287  4320 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.562  4287  4320 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 18:35:33.595  4318  4318 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-23 18:35:33.597  4287  4320 I Process : Sending signal. PID: 4287 SIG: 9
,08-23 18:35:33.597   872  4345 E DropBoxManagerService: Can't write: system_app_crash
08-23 18:35:33.597   872  4345 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 18:35:33.597   872  4345 E DropBoxManagerService: 	... 5 more
,08-23 18:35:33.611  1496  1496 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-23 18:35:33.611  1496  1496 D AndroidRuntime: Shutting down VM
,08-23 18:35:33.612  1496  1496 E AndroidRuntime: FATAL EXCEPTION: main
08-23 18:35:33.612  1496  1496 E AndroidRuntime: Process: com.google.process.gapps, PID: 1496
08-23 18:35:33.612  1496  1496 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-23 18:35:33.612  1496  1496 E AndroidRuntime: 	... 8 more
,08-23 18:35:33.616  1496  1496 I Process : Sending signal. PID: 1496 SIG: 9
,08-23 18:35:33.616   872  4348 E DropBoxManagerService: Can't write: system_app_crash
08-23 18:35:33.616   872  4348 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 18:35:33.616   872  4348 E DropBoxManagerService: 	... 5 more
,08-23 18:35:33.616  4332  4332 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	,at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:33.616  4332  4332 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:33.617  4332  4332 D AndroidRuntime: Shutting down VM
,08-23 18:35:33.624  4332  4332 E AndroidRuntime: FATAL EXCEPTION: main
08-23 18:35:33.624  4332  4332 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4332
08-23 18:35:33.624  4332  4332 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 18:35:33.624  4332  4332 E AndroidRuntime: 	... 10 more
,08-23 18:35:33.626   872  1925 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 18:35:33.626  4332  4332 I Process : Sending signal. PID: 4332 SIG: 9
08-23 18:35:33.627   872  4349 E DropBoxManagerService: Can't write: system_app_crash
08-23 18:35:33.627   872  4349 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
,08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 18:35:33.627   872  4349 E DropBoxManagerService: 	... 5 more
,08-23 18:35:33.631   278   278 E lowmemorykiller: Error writing /proc/4287/oom_score_adj; errno=22
,08-23 18:35:33.640   278   278 E lowmemorykiller: Error writing /proc/4287/oom_score_adj; errno=22
,08-23 18:35:33.658   872  1971 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4332) has died
,08-23 18:35:33.660   872  1971 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-23 18:35:33.660   872  1303 D WifiService: Client connection lost with reason: 4
,08-23 18:35:33.661  1738  4344 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@f8be7e
,08-23 18:35:33.663   872  1370 I ActivityManager: Process com.google.process.gapps (pid 1496) has died
,08-23 18:35:33.663   872  1370 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-23 18:35:33.663   872  1370 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-23 18:35:33.663   872  1370 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-23 18:35:33.663   872  1370 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
,08-23 18:35:33.684   872   885 I ActivityManager: Start proc 4353:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 18:35:33.684   872  1933 I ActivityManager: Process android.process.acore (pid 4287) has died
,08-23 18:35:33.685   872  1933 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40979ms
08-23 18:35:33.693  1738  1738 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-23 18:35:33.700   872  1902 I ActivityManager: Start proc 4364:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-23 18:35:33.731  4364  4364 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-23 18:35:33.735  4353  4353 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:33.735  4353  4353 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 18:35:33.735  4353  4353 D AndroidRuntime: Shutting down VM
,08-23 18:35:33.737  4364  4364 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:33.739  4364  4364 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:33.739  4364  4364 D AndroidRuntime: Shutting down VM
,08-23 18:35:33.739  4364  4364 E AndroidRuntime: FATAL EXCEPTION: main
08-23 18:35:33.739  4364  4364 E AndroidRuntime: Process: com.google.process.gapps, PID: 4364
08-23 18:35:33.739  4364  4364 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
,08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 18:35:33.739  4364  4364 E AndroidRuntime: 	... 10 more
,08-23 18:35:33.745   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
