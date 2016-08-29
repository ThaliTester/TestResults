#### Test 79763830f89c62d_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-29 14:20:52.371  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:20:52.383  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 14:20:52.385  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 14:20:52.430  1503  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 14:20:52.430  1503  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 14:20:52.431  1503  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:20:52.431  1503  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 14:20:52.477  3692  3692 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 14:20:52.477  3692  3692 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 14:20:52.477  3692  3692 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-29 14:20:52.976  3976  3976 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 14:20:52.981  3976  3976 D AndroidRuntime: CheckJNI is OFF
08-29 14:20:53.024  3976  3976 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 14:20:53.085  3976  3976 I Radio-JNI: register_android_hardware_Radio DONE
08-29 14:20:53.106  3976  3976 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 14:20:53.111   871  1674 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 14:20:53.156  2097  2414 W SearchService: Abort, client detached.
08-29 14:20:53.158  3976  3976 D AndroidRuntime: Shutting down VM
08-29 14:20:53.163  2097  2350 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@da0fe3e
08-29 14:20:53.164  2097  2362 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 14:20:53.164  2097  2097 I HotwordDetector: Closing mic
08-29 14:20:53.178   871   882 I ActivityManager: Start proc 3985:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 14:20:53.227   375  2364 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 14:20:53.228   375  2364 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 14:20:53.232   375  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 14:20:53.236  2097  2361 I MicroRecognitionRnrImpl: Detection finished
08-29 14:20:53.237  2097  2357 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 14:20:53.254  3985  3985 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 14:20:53.276  3985  3985 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 14:20:53.283  3985  3985 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2906-2908)
08-29 14:20:53.283  3985  3985 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 14:20:53.295  3985  3985 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5078a89}
08-29 14:20:53.295  3985  3985 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 14:20:53.296  3985  3985 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 14:20:53.302  3985  3985 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 14:20:53.303  3985  3985 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 14:20:53.321  3985  3985 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 14:20:53.332  3985  3985 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 14:20:53.332  3985  3985 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 14:20:53.333  3985  3985 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 14:20:53.333  3985  3985 I Adreno  : Build Date                       : 10/20/15
08-29 14:20:53.333  3985  3985 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 14:20:53.333  3985  3985 I Adreno  : Local Branch                     : M14
08-29 14:20:53.333  3985  3985 I Adreno  : Remote Branch                    : 
08-29 14:20:53.333  3985  3985 I Adreno  : Remote Branch                    : 
08-29 14:20:53.333  3985  3985 I Adreno  : Reconstruct Branch               : 
,08-29 14:20:53.403   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@220147f:true
,08-29 14:20:53.438  3985  3985 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 14:20:53.454  3985  3985 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 14:20:53.510  3985  4023 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 14:20:53.517  3985  4010 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 14:20:53.565  3985  4023 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 14:20:53.636   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +473ms
,08-29 14:20:53.641  1906  1906 I Keyboard.Facilitator: onFinishInput()
,08-29 14:20:53.727  3985  3985 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3985
,08-29 14:20:53.816  3985  3985 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 14:20:53.981  3985  4025 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1699284688
,08-29 14:20:53.986  3985  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 14:20:53.986  3985  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 14:20:53.986  3985  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 14:20:53.986  3985  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 14:20:53.986  3985  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 14:20:53.986  3985  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ca4214 added. We now have 1 listener(s)
,08-29 14:20:53.990  3985  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 14:20:53.991  3985  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:20:53.992  3985  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:20:53.992  3985  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:20:53.995   871  2029 I ActivityManager: Killing 3377:com.google.android.gm/u0a78 (adj 15): empty #17
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 14:20:53.996  3985  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4f9003 added. We now have 1 listener(s)
08-29 14:20:53.997  3985  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:20:54.001  3985  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:20:54.001  3985  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 14:20:54.001  3985  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-29 14:20:54.001  3985  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 14:20:54.001  3985  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 14:20:54.001   871  1314 D WifiService: New client listening to asynchronous messages
,08-29 14:20:54.043   871  2029 I ActivityManager: Killing 2641:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-29 14:20:54.080  3985  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:20:54.080  3985  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 14:20:54.084  3985  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 14:20:54.085  3985  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:20:54.085  3985  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:54.085  3985  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:54.085  3985  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:20:54.085  3985  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:20:54.085  3985  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:54.085  3985  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:54.085  3985  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:20:54.085  3985  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 14:20:54.085  3985  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:20:54.086  3985  4025 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 14:20:54.236  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:54.239  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:54.242  3985  3985 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 14:20:54.285   871  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 14:20:54.946  3985  4034 W jxcore-log: Initializing JXcore engine
08-29 14:20:54.946  3985  4034 W jxcore-log: JXcore engine is ready
,08-29 14:20:54.982  4034  4034 W Thread-366: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 14:20:54.982  4034  4034 W Thread-366: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11985]" dev="sockfs" ino=11985 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 14:20:54.982  4034  4034 W Thread-366: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 14:20:54.982  4034  4034 W Thread-366: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[28586]" dev="sockfs" ino=28586 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 14:20:54.998  3985  4034 W jxcore-log: Starting JXcore engine
,08-29 14:20:55.081  3985  4034 W jxcore-log: Platform android
08-29 14:20:55.081  3985  4034 W jxcore-log: 
,08-29 14:20:55.081  3985  4034 W jxcore-log: Process ARCH arm
08-29 14:20:55.081  3985  4034 W jxcore-log: 
,08-29 14:20:55.328  3985  4034 I jxcore-log: JXcore Cordova bridge is ready!
08-29 14:20:55.328  3985  4034 I jxcore-log: 
08-29 14:20:55.328  3985  4034 W jxcore-log: JXcore engine is started
,08-29 14:20:55.339  3985  4025 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 14:20:55.348  3985  3985 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 14:20:58.745   871  2105 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:20:59.769  3357  4043 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 14:20:59.789  3357  4044 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 14:20:59.798  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:20:59.800  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:20:59.838  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:20:59.838  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 14:20:59.839  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:20:59.839  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:20:59.858  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:20:59.860  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:20:59.878  1503  1947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:20:59.878  1503  1947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 14:20:59.878  1503  1947 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:20:59.878  1503  1947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:20:59.903  3357  4044 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 14:20:59.905  3357  4043 E BooksSync: Soft error
08-29 14:20:59.905  3357  4043 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:20:59.905  3357  4043 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 14:20:59.905  3357  4043 E BooksSync: Sync error
08-29 14:20:59.905  3357  4043 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:20:59.905  3357  4043 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 14:20:59.906  3357  4043 I BooksSync: Finished books sync
,08-29 14:20:59.917   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129285, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:21:05.254  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 14:21:05.254  3985  4034 I jxcore-log: 
,08-29 14:21:05.257  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 14:21:05.257  3985  4034 I jxcore-log: 
,08-29 14:21:05.268  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:05.268  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:05.268  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:05.268  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:05.268  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:05.268  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:05.268  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:05.268  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:05.273  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:05.275  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 14:21:05.275  3985  4034 I jxcore-log: 
,08-29 14:21:05.277  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 14:21:05.277  3985  4034 I jxcore-log: 
,08-29 14:21:05.777  3985  4034 D executeNativeTests: Running unit tests
,08-29 14:21:05.835  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:05.835  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d added. We now have 2 listener(s)
,08-29 14:21:05.836  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:21:05.836  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:05.836  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:05.836  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:05.836  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 added. We now have 2 listener(s)
08-29 14:21:05.837  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:05.837  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:05.845  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:05.864  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:05.864  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:05.864  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:05.864  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:05.864  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:05.864  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:05.864  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:05.864  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:05.868  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:05.869  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:05.876  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:05.879  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 14:21:05.882  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:21:05.882  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:05.882  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:21:05.887  3985  4034 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 14:21:05.888  3985  4034 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 14:21:05.888  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 14:21:05.888  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:21:05.888  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:21:05.890  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:21:05.891  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:05.891  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:05.892  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:05.892  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.892  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:05.893  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:21:05.893  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d removed from the list
,08-29 14:21:05.893  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:05.893  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 removed from the list
08-29 14:21:05.894  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:05.894  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:05.896  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.896  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:05.897  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:05.897  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:05.897  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:05.897  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:05.899  3985  4034 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 14:21:05.899  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:05.900  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:05.900  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:05.900  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:05.900  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.900  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:05.900  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:05.900  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:05.900  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:05.900  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:05.900  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.900  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:05.900  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.900  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:05.901  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:05.901  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:05.901  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:05.901  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
,08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 14:21:05.906  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-29 14:21:05.907  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 14:21:05.907  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:05.908  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:05.908  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:05.908  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:05.908  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.908  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:05.908  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:05.908  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:05.908  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:05.908  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:05.908  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.909  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:05.909  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.909  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:05.910  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:05.910  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:05.910  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:05.910  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:05.911  3985  4034 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 14:21:05.912  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:05.916  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:05.916  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:05.916  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:05.916  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:05.916  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:05.916  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:05.916  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:05.916  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:05.917  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:05.917  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:05.918  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:05.918  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:05.918  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:05.918  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:05.918  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:21:05.920  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:05.921  3985  4034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 14:21:05.921  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:21:05.923  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:05.925  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:21:05.927  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 14:21:05.927  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:21:05.928  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 14:21:05.931  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 14:21:05.931  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:21:05.931  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:21:05.932  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 14:21:05.933  3985  4034 D BluetoothAdapter: STATE_ON
,08-29 14:21:05.935  2848  2985 D BtGatt.GattService: registerClient() - UUID=73640f45-d288-45ff-a689-3bc19d890fda
,08-29 14:21:05.936  2848  2877 D BtGatt.GattService: onClientRegistered() - UUID=73640f45-d288-45ff-a689-3bc19d890fda, clientIf=5
08-29 14:21:05.937  3985  3996 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 14:21:05.937  2848  2986 D BtGatt.GattService: start scan with filters
,08-29 14:21:05.940  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 14:21:05.940  2848  2880 D BtGatt.ScanManager: handling starting scan
,08-29 14:21:05.940  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:21:05.940  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:21:05.940  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 14:21:05.941  2848  2880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:05.942  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:21:05.942  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 14:21:05.942  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:21:05.944  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:21:05.946  3985  4034 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 14:21:05.948  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:21:05.948  3985  4034 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 14:21:05.948  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:05.948  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 14:21:05.948  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.948  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:21:05.948  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 14:21:05.948  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:21:05.948  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:05.948  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:21:05.948  2848  2877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 14:21:05.948  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:05.949  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:21:05.949  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 14:21:05.949  3985  4034 D BluetoothAdapter: STATE_ON
08-29 14:21:05.949  2848  2880 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 14:21:05.949  2848  2985 D BtGatt.GattService: stopScan() - queue size =1
08-29 14:21:05.950  2848  2986 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 14:21:05.950  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:05.950  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:21:05.950  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:21:05.950  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:21:05.950  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 14:21:05.951  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:21:05.951  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:21:05.951  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:21:05.952  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:05.952  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:05.953  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:05.953  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.953  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:05.953  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:05.953  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:05.953  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:05.953  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
,08-29 14:21:05.953  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:05.953  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:05.953  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:05.953  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:05.953  3985  4034 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 14:21:05.955  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:05.955  2848  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 14:21:05.955  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:05.956  2848  2880 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:21:05.956  2848  2880 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 14:21:05.958  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:05.958  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:05.958  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:05.958  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:05.958  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:05.958  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:05.958  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:05.958  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:05.962  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:05.962  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:05.962  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:05.962  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:05.962  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:05.962  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:05.962  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:21:05.965  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:05.966  3985  4034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 14:21:05.966  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:21:05.968  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:05.969  2848  2877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 14:21:05.969  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:05.970  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 14:21:05.971  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 14:21:05.971  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:21:05.975  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:21:05.975  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:21:05.975  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 14:21:05.976  2848  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 14:21:05.976  3985  4034 D BluetoothAdapter: STATE_ON
08-29 14:21:05.976  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:05.978  2848  2863 D BtGatt.GattService: registerClient() - UUID=c429640d-c9da-43d4-9bc6-5efd077f1861
08-29 14:21:05.979  2848  2877 D BtGatt.GattService: onClientRegistered() - UUID=c429640d-c9da-43d4-9bc6-5efd077f1861, clientIf=5
,08-29 14:21:05.979  3985  3995 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 14:21:05.979  2848  2985 D BtGatt.GattService: start scan with filters
,08-29 14:21:05.981  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 14:21:05.982  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 14:21:05.982  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:21:05.982  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 14:21:05.984  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:21:05.984  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 14:21:05.984  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:21:05.985  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 14:21:05.985  2848  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 14:21:05.985  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:05.985  2848  2880 D BtGatt.ScanManager: stopping BLe Batch
08-29 14:21:05.987  3985  4034 I io.jxcore.node.ConnectionHelper: start: OK
08-29 14:21:05.989  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:21:05.989  3985  4034 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 14:21:05.989  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:05.989  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 14:21:05.989  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.989  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:21:05.989  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 14:21:05.989  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 14:21:05.989  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:05.989  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:21:05.989  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:21:05.989  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 14:21:05.990  3985  4034 D BluetoothAdapter: STATE_ON
08-29 14:21:05.990  2848  2863 D BtGatt.GattService: stopScan() - queue size =0
08-29 14:21:05.991  2848  2985 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 14:21:05.991  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:05.991  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:21:05.991  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:21:05.991  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:21:05.991  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:21:05.992  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:05.992  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:21:05.992  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 14:21:05.992  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:05.993  2848  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 14:21:05.993  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:05.993  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:05.993  2848  2880 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 14:21:05.994  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:05.994  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:05.994  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:05.994  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:05.994  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:05.994  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:05.994  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:05.994  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:05.994  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:05.994  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:05.994  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:05.994  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:05.994  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:05.995  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:05.995  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:05.995  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:05.995  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:05.996  3985  4034 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 14:21:05.998  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:06.000  2848  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 14:21:06.000  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.002  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:06.002  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.002  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:06.002  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:06.002  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:06.002  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:06.002  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:06.002  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:06.002  2848  2880 D BtGatt.ScanManager: handling starting scan
08-29 14:21:06.004  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:06.004  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:06.006  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:06.007  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:06.007  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:06.007  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 14:21:06.008  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:06.008  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:06.008  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:21:06.010  2848  2877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 14:21:06.010  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.010  2848  2880 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 14:21:06.011  3985  4034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 14:21:06.011  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:21:06.016  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:21:06.017  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 14:21:06.017  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:21:06.018  2848  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 14:21:06.018  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.019  2848  2880 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 14:21:06.019  2848  2880 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 14:21:06.020  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 14:21:06.020  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 14:21:06.020  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 14:21:06.020  3985  4034 D BluetoothAdapter: STATE_ON
08-29 14:21:06.022  2848  2985 D BtGatt.GattService: registerClient() - UUID=6661f8e8-245a-4c63-a695-4085eeb70c75
08-29 14:21:06.022  2848  2877 D BtGatt.GattService: onClientRegistered() - UUID=6661f8e8-245a-4c63-a695-4085eeb70c75, clientIf=5
,08-29 14:21:06.023  3985  3996 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 14:21:06.023  2848  2986 D BtGatt.GattService: start scan with filters
,08-29 14:21:06.026  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 14:21:06.027  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:21:06.027  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:21:06.027  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:21:06.028  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:21:06.029  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:21:06.029  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 14:21:06.030  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:21:06.030  2848  2877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 14:21:06.031  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:06.032  3985  4034 I io.jxcore.node.ConnectionHelper: start: OK
08-29 14:21:06.032  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.032  3985  4034 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 14:21:06.032  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.032  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 14:21:06.032  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.032  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:21:06.032  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 14:21:06.032  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:21:06.032  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:06.032  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 14:21:06.032  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:21:06.032  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 14:21:06.033  3985  4034 D BluetoothAdapter: STATE_ON
08-29 14:21:06.033  2848  2986 D BtGatt.GattService: stopScan() - queue size =1
08-29 14:21:06.033  2848  2863 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 14:21:06.034  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:06.034  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:21:06.034  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:21:06.034  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 14:21:06.034  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 14:21:06.036  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:06.036  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:21:06.037  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 14:21:06.037  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:06.037  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:06.037  2848  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 14:21:06.037  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.038  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:06.038  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:06.038  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:21:06.038  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.038  3985  4034 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 14:21:06.038  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.038  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.038  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.039  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.039  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:06.039  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.039  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.039  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.039  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.039  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:06.039  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.039  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.040  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.040  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.040  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.040  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
,08-29 14:21:06.040  3985  4034 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 14:21:06.041  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.041  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.041  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.041  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.041  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.043  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.043  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.043  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.043  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.043  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:21:06.043  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.043  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.043  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:06.043  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.044  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.044  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.044  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.044  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.045  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 14:21:06.045  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.045  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.045  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.045  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.045  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.045  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.046  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.046  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:06.046  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.046  2848  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 14:21:06.046  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.046  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.046  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.046  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:06.046  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.046  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:06.046  2848  2880 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:21:06.047  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.047  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:06.047  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:06.047  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.047  3985  4034 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 14:21:06.047  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.047  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:06.047  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.048  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.048  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.048  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.048  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
,08-29 14:21:06.048  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.048  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.048  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.048  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.048  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.048  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:06.048  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.049  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.049  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.049  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.049  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.049  3985  4034 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 14:21:06.049  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.049  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:06.049  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.049  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.050  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.050  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.050  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.050  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.050  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.050  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.050  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:06.050  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.050  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.050  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.051  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.051  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.051  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.051  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.051  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 14:21:06.053  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:21:06.053  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:21:06.053  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:21:06.053  2848  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 14:21:06.053  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 14:21:06.053  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:21:06.053  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.053  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.053  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.053  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.053  2848  2880 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 14:21:06.053  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:06.053  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.053  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.054  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.055  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.055  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.055  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.055  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.055  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.055  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.055  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.056  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:21:06.056  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.056  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.057  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.057  3985  4034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:21:06.058  3985  4034 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 14:21:06.058  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 14:21:06.061  2848  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 14:21:06.061  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.062  3985  4034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 14:21:06.062  3985  4034 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 14:21:06.062  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 14:21:06.062  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 14:21:06.062  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 14:21:06.062  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 14:21:06.062  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 14:21:06.062  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 14:21:06.063  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 14:21:06.064  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 14:21:06.064  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 14:21:06.064  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 14:21:06.064  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 14:21:06.064  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-29 14:21:06.064  3985  4034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 14:21:06.064  3985  4034 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:21:06.065  2848  2880 D BtGatt.ScanManager: handling starting scan
08-29 14:21:06.065  3985  4034 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 14:21:06.065  3985  4034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:21:06.065  3985  4034 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-29 14:21:06.066  3985  4034 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 14:21:06.066  3985  4034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:21:06.066  3985  4034 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:21:06.066  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 14:21:06.069  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 14:21:06.069  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-29 14:21:06.069  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 14:21:06.070  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 14:21:06.070  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 14:21:06.070  3985  4034 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 14:21:06.070  3985  4034 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 14:21:06.070  3985  4034 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 14:21:06.071  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.071  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:06.071  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.071  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.071  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.071  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.071  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 14:21:06.072  2848  2877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 14:21:06.072  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.073  2848  2880 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 14:21:06.073  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.073  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:06.073  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.073  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.073  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.073  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.073  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.073  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.073  3985  4048 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 430)
08-29 14:21:06.075  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.075  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.075  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.076  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
,08-29 14:21:06.076  3985  4034 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 14:21:06.077  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.077  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.077  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.077  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.077  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.077  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:06.077  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.077  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.077  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.077  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.077  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.077  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.077  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.077  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.077  3985  4049 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 430
,08-29 14:21:06.079  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.079  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.079  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.079  2848  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 14:21:06.079  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.079  2848  2880 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 14:21:06.079  2848  2880 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 14:21:06.079  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.080  3985  4034 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 14:21:06.080  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.080  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.080  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.080  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.080  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.080  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.080  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
,08-29 14:21:06.080  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.080  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.080  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.080  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.080  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.080  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.080  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:06.081  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.081  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.081  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.081  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.082  3985  4034 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 14:21:06.082  3985  4034 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 14:21:06.082  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:21:06.082  3985  4034 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-29 14:21:06.082  3985  4034 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 14:21:06.082  3985  4034 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 14:21:06.082  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:21:06.082  3985  4034 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 14:21:06.082  3985  4034 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 14:21:06.082  3985  4034 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 14:21:06.082  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:21:06.082  3985  4034 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 14:21:06.082  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:21:06.082  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.082  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.083  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.083  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.083  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.084  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.084  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.084  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.084  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.084  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.084  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:06.084  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.084  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.084  3985  4048 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:06.086  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.086  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.086  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.086  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.087  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:06.087  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.087  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.087  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.087  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.087  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.087  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.087  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.087  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.087  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.087  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
,08-29 14:21:06.087  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.087  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.087  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.088  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.088  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.088  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.088  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.088  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.088  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.088  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.088  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.088  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:06.088  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.089  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.089  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.089  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.089  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.089  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:06.089  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.089  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.089  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.089  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.090  3985  4034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 14:21:06.091  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:06.091  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 14:21:06.092  3985  4034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 14:21:06.092  3985  4034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 14:21:06.092  3985  3985 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 14:21:06.093  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 14:21:06.093  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 14:21:06.094  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:06.094  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 14:21:06.094  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 14:21:06.094  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 14:21:06.096  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.096  3985  4034 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 14:21:06.096  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.096  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:06.096  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:21:06.096  3985  3985 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 14:21:06.096  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:06.096  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:21:06.096  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.096  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:06.097  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:06.097  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.097  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.098  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.098  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.098  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:06.098  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.098  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.098  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.098  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.098  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.098  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.098  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.098  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.098  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:06.098  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.098  3985  4050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:06.099  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:06.099  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:06.099  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:06.099  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.099  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:06.099  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.099  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.100  3985  4034 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 14:21:06.101  3985  4034 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 14:21:06.101  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 14:21:06.101  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:21:06.101  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.101  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.101  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.102  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:06.102  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.103  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.103  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.103  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.103  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.103  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.103  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.103  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:06.103  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.103  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.104  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.104  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.104  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.104  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
,08-29 14:21:06.106  3985  4050 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-29 14:21:06.106  3985  4050 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 14:21:06.107  3985  4050 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-29 14:21:06.107  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.107  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.107  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:06.107  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:06.107  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.107  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.107  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.107  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:06.107  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.107  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.107  3985  3985 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-29 14:21:06.108  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.108  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.108  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.108  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.108  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.108  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.108  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:06.108  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.109  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:06.109  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:06.109  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:21:06.109  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:06.109  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:06.109  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.109  3985  4034 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77984d not in the list
08-29 14:21:06.109  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.109  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
08-29 14:21:06.110  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:06.110  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.110  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.110  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:06.110  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:06.110  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:06.110  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:06.110  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:06.110  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be17f02 not in the list
,08-29 14:21:06.111  3985  4034 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 14:21:06.111  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:21:06.111  3985  4034 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 14:21:06.111  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:21:06.111  3985  4034 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 14:21:06.111  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:21:06.112  2848  2877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 14:21:06.112  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:06.116  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 14:21:06.116  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-29 14:21:06.116  3985  4034 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 14:21:06.117  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-29 14:21:06.117  3985  4034 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 14:21:06.117  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 14:21:06.117  3985  4034 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 14:21:06.117  3985  4034 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left,
08-29 14:21:06.117  3985  4034 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 14:21:06.118  3985  4034 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 14:21:06.119  3985  4034 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 14:21:06.119  3985  4034 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 14:21:06.119  2848  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 14:21:06.119  3985  4034 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-29 14:21:06.119  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.119  3985  4034 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 14:21:06.120  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:06.120  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe29614 added. We now have 2 listener(s)
08-29 14:21:06.120  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:06.123  3985  4034 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 14:21:06.123   871   881 D WifiService: setWifiEnabled: true pid=3985, uid=10000
08-29 14:21:06.123   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 14:21:06.124  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:06.124  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4ac2ebd added. We now have 3 listener(s)
08-29 14:21:06.124  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:06.125  2848  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 14:21:06.125  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.125  2848  2880 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:21:06.128  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:06.128  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6bbacb2 added. We now have 4 listener(s)
08-29 14:21:06.129  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:06.130  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:06.130  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32f403 added. We now have 5 listener(s)
08-29 14:21:06.130  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:06.131   871   882 D WifiService: setWifiEnabled: false pid=3985, uid=10000
08-29 14:21:06.131   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 14:21:06.131  2848  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 14:21:06.131  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:06.132  2848  2880 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:21:06.137  2848  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 14:21:06.137  2848  2873 D BluetoothAdapterState: Current state: ON, message: 23
08-29 14:21:06.137  2848  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:06.137  2848  2873 D BluetoothAdapterProperties: Setting state to 13
08-29 14:21:06.137  2848  2873 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 14:21:06.137  2848  2873 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 14:21:06.138  2848  2873 I BluetoothAdapterState: Entering PendingCommandState
08-29 14:21:06.139  2848  2848 D BluetoothMapService: onReceive
08-29 14:21:06.139  2848  2848 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:06.139  2848  2848 D BluetoothMapService: STATE_TURNING_OFF
08-29 14:21:06.139  2848  2848 D BluetoothMapService: MAP Service closeService in
08-29 14:21:06.139  2848  2848 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 14:21:06.139  2848  2848 D ObexServerSockets0: shutdown(block = true)
08-29 14:21:06.140  2848  2848 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 14:21:06.140  2848  2987 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 14:21:06.140  2848  2848 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 14:21:06.140  2848  2963 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 14:21:06.140  2848  2988 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 14:21:06.142  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.142  2848  2848 I BtOppRfcommListener: stopping Accept Thread
08-29 14:21:06.142  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:06.142  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.142  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:06.142  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:06.142  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.142  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:06.142  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:06.142  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:06.143  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:06.143  2848  3651 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:06.143  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:06.143  2848  3651 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 14:21:06.145  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 14:21:06.147   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 14:21:06.147   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 14:21:06.147   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 14:21:06.147   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:06.153   871  2115 D DhcpClient: Clearing IP address
08-29 14:21:06.153   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-29 14:21:06.156   371   869 D CommandListener: Setting iface cfg
08-29 14:21:06.156  1503  2559 V NativeCrypto: Read error: ssl=0x9b6a8a00: I/O error during system call, Connection timed out
08-29 14:21:06.158  1503  2559 V NativeCrypto: SSL shutdown failed: ssl=0x9b6a8a00: I/O error during system call, Broken pipe
,08-29 14:21:06.160   871  1675 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-29 14:21:06.160   871  2095 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-29 14:21:06.162   871  2095 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-29 14:21:06.163   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-29 14:21:06.165   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 14:21:06.167   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 14:21:06.168   871   884 I ActivityManager: Start proc 4054:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 14:21:06.170  2848  2877 D BluetoothAdapterProperties: Scan Mode:20
,08-29 14:21:06.170  2848  2873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 14:21:06.170  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:06.171   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 14:21:06.171   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 14:21:06.172   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 14:21:06.173  2848  2848 D HeadsetService: Received stop request...Stopping profile...
08-29 14:21:06.174  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.174  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:06.174  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.174  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:06.174  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:06.174  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.174  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:06.174  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:06.174  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:06.175   871  2125 D DhcpClient: Receive thread stopped
,08-29 14:21:06.175  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:06.175  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:06.176  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:06.176  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:06.176  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.176  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:06.176  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:06.176  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.176  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:06.176  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:06.176  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:06.177   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 14:21:06.177  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:06.177  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:06.177  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:06.178   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-29 14:21:06.178   402   402 E Parcel  : Reading a NULL string not supported here.
,08-29 14:21:06.179  2848  2848 D A2dpService: Received stop request...Stopping profile...
,08-29 14:21:06.179  2848  2968 D A2dpStateMachine: Exit Disconnected: -1
,08-29 14:21:06.179   871   871 D BluetoothHeadset: Proxy object disconnected
,08-29 14:21:06.180  2010  2174 D BluetoothHeadset: Proxy object disconnected
,08-29 14:21:06.180  1369  1395 D BluetoothHeadset: Proxy object disconnected
,08-29 14:21:06.180  1369  1369 D HeadsetProfile: Bluetooth service disconnected
,08-29 14:21:06.181   871   871 D BluetoothHeadset: Proxy object disconnected
,08-29 14:21:06.181   871   871 D BluetoothHeadset: Proxy object disconnected
,08-29 14:21:06.183   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:21:06.186   871   871 D BluetoothA2dp: Proxy object disconnected
,08-29 14:21:06.186  1369  1369 D BluetoothA2dp: Proxy object disconnected
08-29 14:21:06.187  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.187  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:06.187  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.187  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:06.187  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:06.187  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.187  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:06.187  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:06.187  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:06.188  2848  2848 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:06.188  2848  2848 V BluetoothAdapterState: isTurningOn()=false
,08-29 14:21:06.188  2848  2848 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:06.188  2848  2848 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:06.189  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.189  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:06.189  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.189  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:06.189  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:06.189  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.189  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:06.189  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:06.189  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:06.190  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.190  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:06.191   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 14:21:06.191  1856  2297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.192  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.192  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:06.192  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.192  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:06.192  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:06.192  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.192  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:06.192  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:06.192  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:06.192  2848  2848 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 14:21:06.193  2848  2942 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:21:06.193  2848  2942 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 14:21:06.193  2848  2942 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:21:06.193  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.193  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:06.194  2848  2877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 14:21:06.195   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 14:21:06.197  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:06.198  2848  2877 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 14:21:06.199  2848  2848 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 14:21:06.200  2848  2848 D HidService: Received stop request...Stopping profile...
08-29 14:21:06.200  2848  2848 D HidService: Stopping Bluetooth HidService
08-29 14:21:06.202  2848  2848 D HealthService: Received stop request...Stopping profile...
,08-29 14:21:06.203  1369  1369 D BluetoothInputDevice: Proxy object disconnected
08-29 14:21:06.204  1369  1369 D HidProfile: Bluetooth service disconnected
08-29 14:21:06.204  2848  2848 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:06.204  2848  2848 V BluetoothAdapterState: isTurningOn()=false
08-29 14:21:06.204  2848  2848 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:06.205  2848  2848 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:06.205  2848  2848 D PanService: Received stop request...Stopping profile...
08-29 14:21:06.208  2848  2877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 14:21:06.208  2848  2942 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:21:06.208  2848  2942 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:21:06.208  2848  2942 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:06.208  2848  2942 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:06.208  2848  2942 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:06.208  2848  2942 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:06.208  2848  2848 D BluetoothMapService: Received stop request...Stopping profile...
08-29 14:21:06.208  2848  2848 D BluetoothMapService: stop()
08-29 14:21:06.209  2848  2848 D BluetoothMapAppObserver: deinitObservers()
08-29 14:21:06.209  2848  2848 D BluetoothMapAppObserver: removeReceiver()
08-29 14:21:06.210  2848  2848 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:06.210  2848  2848 V BluetoothAdapterState: isTurningOn()=false
08-29 14:21:06.211  2848  2848 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:06.211  2848  2848 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:06.211  2848  2848 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 14:21:06.211  2848  2877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 14:21:06.211  2848  2848 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 14:21:06.211  2848  2848 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:06.212  2848  2848 V BluetoothAdapterState: isTurningOn()=false
08-29 14:21:06.212  2848  2848 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:06.212  2848  2848 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:06.212  2848  2848 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 14:21:06.212  2848  2877 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 14:21:06.212  2848  2848 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 14:21:06.212  2848  2848 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:06.212  2848  2848 V BluetoothAdapterState: isTurningOn()=false
08-29 14:21:06.212  2848  2848 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:06.212  2848  2848 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:06.213  2848  2848 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 14:21:06.213  2848  2848 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 14:21:06.214  2848  2848 D BluetoothMapService: MAP Service closeService in
08-29 14:21:06.214  2848  2848 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:06.214  2848  2848 V BluetoothAdapterState: isTurningOn()=false
08-29 14:21:06.214  2848  2848 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:06.216  2848  2848 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:06.217  2848  2873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 14:21:06.217  2848  2873 D BluetoothAdapterProperties: Setting state to 15
08-29 14:21:06.217  2848  2873 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 14:21:06.217  1369  1395 D BluetoothInputDevice: onBluetoothState,Change: up=false
08-29 14:21:06.220  2848  2873 I BluetoothAdapterState: Entering BleOnState
08-29 14:21:06.221   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:06.221   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:06.221   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:21:06.221  1369  1392 D BluetoothMap: onBluetoothStateChange: up=false
08-29 14:21:06.221  1369  2128 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 14:21:06.222  1369  1694 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:06.222   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:06.223  1369  1395 D BluetoothPan: onBluetoothStateChange on: false
08-29 14:21:06.223  2010  2174 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:06.223  1369  1392 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:21:06.224  2848  2873 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 14:21:06.224  2848  2873 D BluetoothAdapterProperties: Setting state to 16
08-29 14:21:06.224  2848  2873 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 14:21:06.224  2848  2848 D BluetoothMapService: cleanup()
08-29 14:21:06.224  2848  2848 D BluetoothMapService: MAP Service closeService in
08-29 14:21:06.224  2848  2873 D BluetoothAdapterProperties: onBleDisable
08-29 14:21:06.225  2848  2873 I BluetoothAdapterState: Entering PendingCommandState
08-29 14:21:06.225  2848  2874 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 14:21:06.225  2848  2942 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 14:21:06.225  2848  2942 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:21:06.226  2848  2877 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:21:06.226  3985  4048 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 430)
08-29 14:21:06.229  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.229  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:06.229  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.229  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:06.229  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:06.229  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.229  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:06.229  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:06.229  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:06.230  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:06.230  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:06.230  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:06.230  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:06.230  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:06.230  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:06.230  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:06.230  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:06.230  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:06.231  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:06.232  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:06.245  4054  4054 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-29 14:21:06.246   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 14:21:06.258  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 14:21:06.262   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@594a81a:true
08-29 14:21:06.263  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:21:06.272   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 14:21:06.274   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 14:21:06.274   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 14:21:06.275   871  2051 I ActivityManager: Start proc 4070:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-29 14:21:06.277   871   888 D Tethering: MasterInitialState.processMessage what=3
08-29 14:21:06.282  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:06.283  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:06.284  3581  3581 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ab86abd and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 14:21:06.296  4054  4054 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 14:21:06.299  4054  4054 D BluetoothMap: Create BluetoothMap proxy object
08-29 14:21:06.307  4054  4054 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 14:21:06.313  4070  4070 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-29 14:21:06.321  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:06.332   871  1399 I ActivityManager: Killing 3581:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 14:21:06.339   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-29 14:21:06.341   871  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 14:21:06.341   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 14:21:06.428  2848  2877 I bt_hci  : shut_down
08-29 14:21:06.429  2848  2881 D bt_hwcfg: hw_epilog_process
,08-29 14:21:06.430  2848  2881 I bt_vendor: low_power_mode_cb
,08-29 14:21:06.457  2848  2881 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 14:21:06.458  2848  2881 I bt_vendor: epilog_cb
,08-29 14:21:06.458  2848  2881 I bt_hci  : epilog_finished_callback
,08-29 14:21:06.481  4070  4070 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 14:21:06.481  4070  4070 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:21:06.481  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 14:21:06.482  4070  4070 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:21:06.482  4070  4070 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 14:21:06.482  407,0  4070 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:21:06.482  4070  4070 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:2,1:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:21:06.482  4070  4070 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:21:06.482  4070  4070 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:21:06.482  4070  4070 D StrictMode: StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:21:06.482  4070  4070 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:21:06.499  2848  2877 I bt_hci_h4: hal_close
08-29 14:21:06.500  2848  2877 I bt_userial_vendor: device fd = 51 close
08-29 14:21:06.524  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 14:21:06.535  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:06.548  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:06.589  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 14:21:06.596  1706  1706 D SystemUpdateService: onCreate
,08-29 14:21:06.599  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 14:21:06.600  3985  3985 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 14:21:06.625  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 14:21:06.629  1706  2521 I iu.UploadsManager: num queued entries: 0
,08-29 14:21:06.629  1706  2521 I iu.UploadsManager: num updated entries: 0
,08-29 14:21:06.631  2848  2874 D bt_stack_manager: event_shut_down_stack finished.
08-29 14:21:06.632  2848  2873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 14:21:06.637  2848  2873 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 14:21:06.637  2848  2848 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 14:21:06.638  1706  4105 I SystemUpdateService: active receiver: enabled
08-29 14:21:06.638  2848  2848 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 14:21:06.639  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 14:21:06.639  2848  2848 D BtGatt.GattService: stop()
08-29 14:21:06.640  2848  2848 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 14:21:06.641  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 14:21:06.643  1706  2521 I iu.SyncManager: NEXT; no task
,08-29 14:21:06.651  1706  4105 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 14:21:06.656  1706  4105 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 14:21:06.656  1706  4105 I SystemUpdateService: now status is 0 (complete)
08-29 14:21:06.656  1706  4105 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 14:21:06.656  1706  4105 I SystemUpdateService: file has been verified
08-29 14:21:06.656  1706  4105 I SystemUpdateService: OTA package size = 12249756
,08-29 14:21:06.664  1706  4105 I SystemUpdateService: showing system update notification
,08-29 14:21:06.670   871  2047 I ActivityManager: Start proc 4108:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 14:21:06.675  2848  2848 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:21:06.675  2848  2848 V BluetoothAdapterState: isTurningOn()=false
08-29 14:21:06.675  2848  2848 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:21:06.675  2848  2848 V BluetoothAdapterState: isBleTurningOff()=true
08-29 14:21:06.676  2848  2873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 14:21:06.676  2848  2873 D BluetoothAdapterProperties: Setting state to 10
08-29 14:21:06.676  2848  2873 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 14:21:06.676   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 14:21:06.677  2848  2873 I BluetoothAdapterState: Entering OffState
,08-29 14:21:06.696  2848  2848 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 14:21:06.696  2848  2848 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 14:21:06.696  2848  2848 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 14:21:06.697  2848  2874 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 14:21:06.698  2848  2874 D bt_stack_manager: event_clean_up_stack finished.
,08-29 14:21:06.700  2848  2848 I art     : System.exit called, status: 0
08-29 14:21:06.701  2848  2848 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 14:21:06.723  1706  1706 D SystemUpdateService: onDestroy
,08-29 14:21:06.725   871  2048 I ActivityManager: Killing 3458:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 14:21:06.769   871  2047 I ActivityManager: Process com.android.bluetooth (pid 2848) has died
,08-29 14:21:06.795  4108  4108 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 14:21:06.798  4108  4108 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:06.814  4108  4108 D SprintDMHelper: simOperator: 
,08-29 14:21:06.815  4108  4108 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 14:21:06.833   871  2048 I ActivityManager: Start proc 4123:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 14:21:06.941   871  1399 I ActivityManager: Start proc 4139:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 14:21:06.943  2831  4138 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 14:21:06.946   871   881 I ActivityManager: Killing 3232:android.process.acore/u0a5 (adj 15): empty #17
,08-29 14:21:06.950  4070  4099 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 14:21:06.968   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4c89546:true
,08-29 14:21:07.041  4139  4139 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 14:21:07.098  4139  4139 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 14:21:07.098  4139  4139 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 14:21:07.098  4139  4139 I GAv4    :   adb logcat -s GAv4
,08-29 14:21:07.124  4139  4139 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 14:21:07.129  4139  4139 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 14:21:07.164  4139  4156 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 14:21:07.285  4139  4139 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 14:21:07.333  4139  4139 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 14:21:07.342  4139  4139 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6965-6967)
08-29 14:21:07.342  4139  4139 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 14:21:07.350  4139  4139 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4be7d2d}
08-29 14:21:07.350  4139  4139 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 14:21:07.351  4139  4139 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 14:21:07.356  4139  4139 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 14:21:07.357  4139  4139 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 14:21:07.373  4139  4139 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 14:21:07.384  4139  4139 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 14:21:07.384  4139  4139 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 14:21:07.384  4139  4139 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 14:21:07.384  4139  4139 I Adreno  : Build Date                       : 10/20/15
08-29 14:21:07.384  4139  4139 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 14:21:07.384  4139  4139 I Adreno  : Local Branch                     : M14
08-29 14:21:07.384  4139  4139 I Adreno  : Remote Branch                    : 
08-29 14:21:07.384  4139  4139 I Adreno  : Remote Branch                    : 
08-29 14:21:07.384  4139  4139 I Adreno  : Reconstruct Branch               : 
,08-29 14:21:07.438  4139  4139 I NSApplication: Starting up...
,08-29 14:21:07.458  4139  4185 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 14:21:07.478   871  1969 I ActivityManager: Start proc 4190:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-29 14:21:07.479   871  1969 I ActivityManager: Killing 3857:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 14:21:07.574  4190  4190 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 14:21:07.731   871  1399 I ActivityManager: Killing 3870:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 14:21:09.180   871   881 D WifiService: setWifiEnabled: true pid=3985, uid=10000
,08-29 14:21:09.180   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:21:09.193   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-29 14:21:09.200  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:09.200  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:09.200  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:09.200  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:09.200  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:09.200  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:09.200  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:09.200  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:09.200  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:09.201  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:09.201  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:09.203  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:09.203  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:09.203  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:09.203  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:09.203  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:09.203  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:09.203  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:09.203  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:09.203  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:09.203  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:09.203  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:09.217   871  1313 D WifiConfigStore: loaded 0 passpoint configs
08-29 14:21:09.217   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 14:21:09.218   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 14:21:09.220   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 14:21:09.220   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 14:21:09.220   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 14:21:09.220   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 14:21:09.231   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 14:21:09.231   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.88 rxSuccessRate=9.25 delta 1000 -> 994
08-29 14:21:09.232   371   869 D CommandListener: Setting iface cfg
08-29 14:21:09.232   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
08-29 14:21:09.233   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 14:21:09.240   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 14:21:09.240   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:09.241   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 14:21:09.246   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 14:21:09.247   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 14:21:09.300   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 14:21:09.301  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 14:21:09.728  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e,
,08-29 14:21:09.771  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 14:21:09.772  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 14:21:09.782   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:21:09.795   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 14:21:09.795   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:09.796   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 14:21:09.814   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:21:09.826   371   869 D CommandListener: Setting iface cfg
,08-29 14:21:09.827   871  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 14:21:09.841   871  1315 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 14:21:09.842   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 14:21:09.873   871  4214 D DhcpClient: Receive thread started
,08-29 14:21:09.955   871  1313 E native  : do suspend false
,08-29 14:21:09.975   871  2115 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 14:21:09.993   871  4214 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172684, domain null
,08-29 14:21:09.994   871  2115 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172684 seconds
,08-29 14:21:09.997   871  2115 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 14:21:10.020   871  4214 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 14:21:10.021   871  2115 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 14:21:10.026   371   869 D CommandListener: Setting iface cfg
,08-29 14:21:10.039   871  2115 D DhcpClient: Scheduling renewal in 86399s
,08-29 14:21:10.039   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 14:21:10.048   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 14:21:10.049   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 14:21:10.049   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 14:21:10.050   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 14:21:10.058   871  1315 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 14:21:10.058   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 14:21:10.128   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 14:21:10.129   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 14:21:10.131   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 14:21:10.133   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 14:21:10.135   871  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 14:21:10.152   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 14:21:10.158   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 14:21:10.159   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-29 14:21:10.159   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 14:21:10.159   871  1315 D ConnectivityService:    accepting network in place of null
08-29 14:21:10.159   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 14:21:10.161   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 14:21:10.161   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 14:21:10.207   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:21:10.239   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:21:10.246   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 14:21:10.246   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:10.252   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 14:21:10.258   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-29 14:21:10.269  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:10.269  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:10.269  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:10.269  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:10.269  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:10.269  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:10.269  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:10.269  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:10.269  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:10.269  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:10.269  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:10.272  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:10.272  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:10.272  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:10.272  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:10.272  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:10.272  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:10.272  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:10.272  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:10.272  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:21:10.272  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:10.272  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:10.295  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 14:21:10.299  1706  1706 D SystemUpdateService: onCreate
,08-29 14:21:10.303  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 14:21:10.306  1706  4227 I SystemUpdateService: active receiver: enabled
,08-29 14:21:10.310  1706  4227 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 14:21:10.317  1706  4227 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 14:21:10.317  1706  4227 I SystemUpdateService: now status is 0 (complete)
,08-29 14:21:10.318  1706  4227 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 14:21:10.320  1706  4227 I SystemUpdateService: file has been verified
,08-29 14:21:10.323  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 14:21:10.326  1706  4227 I SystemUpdateService: OTA package size = 12249756
,08-29 14:21:10.327  1706  2521 I iu.UploadsManager: num queued entries: 0
,08-29 14:21:10.328  1706  2521 I iu.UploadsManager: num updated entries: 0
,08-29 14:21:10.329  1706  2521 I iu.SyncManager: NEXT; no task
,08-29 14:21:10.335  1706  4227 I SystemUpdateService: showing system update notification
,08-29 14:21:10.339   871  4213 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139964, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 14:21:10.339  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 14:21:10.341  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 14:21:10.341  1706  4231 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 14:21:10.342  1706  4231 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 14:21:10.343  4108  4108 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:10.343  1706  4231 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 14:21:10.348  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 14:21:10.350  4108  4108 D SprintDMHelper: simOperator: 
08-29 14:21:10.350  4108  4108 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 14:21:10.350  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:21:10.358  1706  1706 D SystemUpdateService: onDestroy
,08-29 14:21:10.375  1503  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 14:21:10.376  1503  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 14:21:10.377  1503  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:21:10.377  1503  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:21:10.389  1706  4231 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-29 14:21:10.428  1503  1947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 14:21:10.428  1503  1947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 14:21:10.428  1503  1947 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:21:10.428  1503  1947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:21:10.434  3751  4229 V KeepSync: Connecting to GoogleApiClient
,08-29 14:21:10.435   871  2051 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 14:21:10.447  3218  4225 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 14:21:10.447  3218  4225 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at blb.a(PG:3937)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at czp.a(PG:18188)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:21:10.447  3218  4225 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	... 12 more
08-29 14:21:10.447  3218  4225 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at fal.a(PG:38)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:21:10.447  3218  4225 E HttpOperation: 	... 14 more
,08-29 14:21:10.500  1503  2319 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 14:21:10.500  1503  2319 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 14:21:10.500  1503  2319 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:21:10.500  1503  2319 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:21:10.510  1503  4234 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 14:21:10.510  1503  4234 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 14:21:10.510  1503  4234 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:21:10.510  1503  4234 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:21:10.516  3218  4225 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 14:21:10.516  3218  4225 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at hec.a(PG:42)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at hee.a(PG:102)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at czr.a(PG:65)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at kka.a(PG:108)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at czp.a(PG:19176)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:21:10.516  3218  4225 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	... 15 more
08-29 14:21:10.516  3218  4225 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at fal.a(PG:38)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:21:10.516  3218  4225 E HttpOperation: 	... 17 more
,08-29 14:21:10.516  3218  4225 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 14:21:10.516  3218  4225 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at hec.a(PG:42)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at hee.a(PG:102)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at czr.a(PG:65)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at kka.a(PG:108)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	... 15 more
08-29 14:21:10.516  3218  4225 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at fal.a(PG:38)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 14:21:10.516  3218  4225 E ExperimentLoader: 	... 17 more
,08-29 14:21:10.530  1706  4238 V BaseAuthAsyncOperation: access token request failed
,08-29 14:21:10.532  3751  4229 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 14:21:10.610  1503  1947 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 14:21:10.610  1503  1947 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 14:21:10.610  1503  1947 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:21:10.611  1503  1947 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:21:10.630   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131587, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:21:10.641  3751  4229 E KeepSync: IOException
08-29 14:21:10.641  3751  4229 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 14:21:10.641  3751  4229 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:21:10.641  3751  4229 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 14:21:10.641  3751  4229 E KeepSync: 	... 10 more
,08-29 14:21:10.642  3751  4229 W KeepSync: Sync result 2
,08-29 14:21:10.650   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 132096, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:21:10.739   871  4212 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:816::200e
,08-29 14:21:10.971  2831  4233 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 14:21:11.147   871  4212 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 12:21:10 GMT], X-Android-Received-Millis=[1472473271145], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472473270966]}
,08-29 14:21:11.152   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 14:21:11.155   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 14:21:11.155   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 14:21:11.165   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 14:21:11.244   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 14:21:12.069   871  2051 I ActivityManager: Killing 3607:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 14:21:12.189   871  1675 D WifiService: setWifiEnabled: false pid=3985, uid=10000
08-29 14:21:12.189   871  1675 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:21:12.208  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 14:21:12.212   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 14:21:12.212   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 14:21:12.212   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 14:21:12.213   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:21:12.229   871  2115 D DhcpClient: Clearing IP address
,08-29 14:21:12.230   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-29 14:21:12.236  1503  4242 V NativeCrypto: Read error: ssl=0xaee3be00: I/O error during system call, Connection timed out
,08-29 14:21:12.238   371   869 D CommandListener: Setting iface cfg
,08-29 14:21:12.240  1503  4242 V NativeCrypto: SSL shutdown failed: ssl=0xaee3be00: I/O error during system call, Broken pipe
,08-29 14:21:12.241   871  4214 D DhcpClient: Receive thread stopped
,08-29 14:21:12.246   871   882 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-29 14:21:12.247   871  4212 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-29 14:21:12.247   871  4212 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:816::200e
,08-29 14:21:12.251   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-29 14:21:12.251   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 14:21:12.252   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 14:21:12.252   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-29 14:21:12.253   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-29 14:21:12.270   402   402 E Parcel  : Reading a NULL string not supported here.
,08-29 14:21:12.276   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 14:21:12.279   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 14:21:12.279   871  4212 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:816::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-29 14:21:12.282  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:12.282  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:12.282  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:12.282  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:12.282  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:12.282  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:12.282  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:12.282  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:12.282  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:12.282  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:12.282  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:12.283   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 14:21:12.283  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:12.283  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:12.283  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:12.283  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:12.283  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:12.283  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:12.283  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:12.283  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:12.283  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:12.283  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:12.283  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:12.287  1856  2297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:21:12.312   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:21:12.335   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:21:12.336   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 14:21:12.337   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:12.341   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-29 14:21:12.346  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:12.347  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:12.351  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 14:21:12.355  1706  1706 D SystemUpdateService: onCreate
,08-29 14:21:12.358  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 14:21:12.367  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 14:21:12.370  1706  2521 I iu.UploadsManager: num queued entries: 0
,08-29 14:21:12.370  1706  2521 I iu.UploadsManager: num updated entries: 0
08-29 14:21:12.371  1706  2521 I iu.SyncManager: NEXT; no task
,08-29 14:21:12.375  1706  4253 I SystemUpdateService: active receiver: enabled
,08-29 14:21:12.378  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 14:21:12.379  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 14:21:12.381  4108  4108 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:12.385  4108  4108 D SprintDMHelper: simOperator: 
08-29 14:21:12.385  4108  4108 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 14:21:12.398  1706  4253 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 14:21:12.406  2831  4256 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 14:21:12.410  1706  4253 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 14:21:12.410  1706  4253 I SystemUpdateService: now status is 0 (complete)
08-29 14:21:12.410  1706  4253 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 14:21:12.410  1706  4253 I SystemUpdateService: file has been verified
,08-29 14:21:12.411  1706  4253 I SystemUpdateService: OTA package size = 12249756
,08-29 14:21:12.419  1706  4253 I SystemUpdateService: showing system update notification
,08-29 14:21:12.427  1706  1706 D SystemUpdateService: onDestroy
,08-29 14:21:12.431   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-29 14:21:12.433   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 14:21:15.243   871   888 I ActivityManager: Start proc 4260:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 14:21:15.373  4260  4260 D AdapterServiceConfig: Adding HeadsetService
08-29 14:21:15.373  4260  4260 D AdapterServiceConfig: Adding A2dpService
08-29 14:21:15.373  4260  4260 D AdapterServiceConfig: Adding HidService
08-29 14:21:15.373  4260  4260 D AdapterServiceConfig: Adding HealthService
08-29 14:21:15.374  4260  4260 D AdapterServiceConfig: Adding PanService
08-29 14:21:15.374  4260  4260 D AdapterServiceConfig: Adding GattService
08-29 14:21:15.374  4260  4260 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 14:21:15.388  4260  4260 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 14:21:15.388   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d108b95:true
,08-29 14:21:15.393  4260  4260 I bt_bluedroid: init
,08-29 14:21:15.393  4260  4272 I BluetoothAdapterState: Entering OffState
,08-29 14:21:15.395  4260  4273 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 14:21:15.395  4260  4273 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 14:21:15.395  4260  4273 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 14:21:15.395  4260  4273 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 14:21:15.396  4260  4260 I bt_bluedroid: get_profile_interface socket
,08-29 14:21:15.398  4260  4260 I bt_bluedroid: get_profile_interface sdp
,08-29 14:21:15.402  4260  4271 I bt_bluedroid: config_hci_snoop_log
,08-29 14:21:15.404  4260  4276 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 14:21:15.406   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 14:21:15.406  4260  4276 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 14:21:15.422  4260  4272 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 14:21:15.423  4260  4272 D BluetoothAdapterProperties: Setting state to 14,
08-29 14:21:15.423  4260  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 14:21:15.427  4260  4272 D BluetoothBondStateMachine: make
,08-29 14:21:15.431  4260  4277 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 14:21:15.439  4260  4272 I BluetoothAdapterState: Entering PendingCommandState
,08-29 14:21:15.441  4260  4260 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 14:21:15.444  4260  4260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:15.444  4260  4260 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 14:21:15.445  4260  4260 D BtGatt.GattService: Received start request. Starting profile...
,08-29 14:21:15.445  4260  4260 D BtGatt.GattService: start()
,08-29 14:21:15.445  4260  4260 I bt_bluedroid: get_profile_interface gatt
,08-29 14:21:15.446  4260  4260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
08-29 14:21:15.446  4260  4260 D BtGatt.AdvertiseManager: advertise manager created
,08-29 14:21:15.454  4260  4260 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:21:15.454  4260  4260 V BluetoothAdapterState: isTurningOn()=false
,08-29 14:21:15.454  4260  4260 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 14:21:15.454  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:15.455  4260  4272 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 14:21:15.455  4260  4272 I bt_bluedroid: enable
,08-29 14:21:15.455  4260  4273 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 14:21:15.456  4260  4273 I bt_hci  : start_up
,08-29 14:21:15.463  4260  4273 I bt_vendor: alloc value 0xb3a1c189
,08-29 14:21:15.463  4260  4273 I bt_vendor: init
08-29 14:21:15.463  4260  4273 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 14:21:15.463  4260  4273 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 14:21:15.569  4260  4273 D bt_hci  : start_up starting async portion
,08-29 14:21:15.569  4260  4280 I bt_hci  : event_finish_startup
08-29 14:21:15.569  4260  4280 I bt_hci_h4: hal_open
08-29 14:21:15.570  4260  4280 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 14:21:15.576  4260  4280 I bt_userial_vendor: device fd = 51 open
,08-29 14:21:15.611  4260  4280 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 14:21:15.643  4260  4280 D bt_hwcfg: Chipset BCM4354A2
,08-29 14:21:15.644  4260  4280 D bt_hwcfg: Target name = [BCM4354A2]
08-29 14:21:15.645  4260  4280 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 14:21:16.324  4260  4280 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 14:21:16.325  4260  4280 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 14:21:16.325  4260  4280 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 14:21:16.443  4260  4280 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 14:21:16.444  4260  4280 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 14:21:16.473  4260  4280 I bt_hwcfg: vendor lib fwcfg completed
,08-29 14:21:16.473  4260  4280 I bt_vendor: firmware callback
,08-29 14:21:16.473  4260  4280 I bt_hci  : firmware_config_callback
,08-29 14:21:16.487  4260  4282 I bt_btu  : btu_task pending for preload complete event
08-29 14:21:16.487  4260  4282 I bt_btu_task: Bluetooth chip preload is complete
,08-29 14:21:16.488  4260  4282 I bt_btu  : btu_task received preload complete event
,08-29 14:21:16.497  4260  4282 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 14:21:16.498  4260  4282 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 14:21:16.498  4260  4282 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 14:21:16.498  4260  4282 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 14:21:16.499  4260  4282 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 14:21:16.499  4260  4282 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 14:21:16.499  4260  4282 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 14:21:16.499  4260  4282 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 14:21:16.500  4260  4282 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 14:21:16.500  4260  4282 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 14:21:16.500  4260  4282 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 14:21:16.500  4260  4282 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 14:21:16.501  4260  4282 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 14:21:16.501  4260  4282 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 14:21:16.501  4260  4282 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 14:21:16.634  4260  4282 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3999d9d
,08-29 14:21:16.635  4260  4282 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3999d9d 
,08-29 14:21:16.658  4260  4276 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-29 14:21:16.659  4260  4276 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 14:21:16.660  4260  4276 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 14:21:16.664  4260  4276 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 14:21:16.667  4260  4276 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:21:16.668  4260  4276 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 14:21:16.668  4260  4276 D bt_hci  : do_postload posting postload work item
,08-29 14:21:16.669  4260  4280 I bt_hci  : event_postload
08-29 14:21:16.669  4260  4280 I bt_vendor: sco_config_cb
08-29 14:21:16.669  4260  4280 I bt_hci  : sco_config_callback postload finished.
,08-29 14:21:16.675  4260  4276 D bt_bte_conf: Device ID record 1 : primary
,08-29 14:21:16.676  4260  4276 D bt_bte_conf:   vendorId            = 000f
08-29 14:21:16.676  4260  4276 D bt_bte_conf:   vendorIdSource      = 0001
08-29 14:21:16.676  4260  4276 D bt_bte_conf:   product             = 1200
08-29 14:21:16.676  4260  4276 D bt_bte_conf:   version             = 1436
,08-29 14:21:16.676  4260  4276 D bt_bte_conf:   clientExecutableURL = 
,08-29 14:21:16.676  4260  4276 D bt_bte_conf:   serviceDescription  = 
,08-29 14:21:16.676  4260  4276 D bt_bte_conf:   documentationURL    = 
,08-29 14:21:16.676  4260  4276 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 14:21:16.676  4260  4273 D bt_stack_manager: event_start_up_stack finished
08-29 14:21:16.677  4260  4272 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 14:21:16.677  4260  4272 D BluetoothAdapterProperties: Setting state to 15
08-29 14:21:16.677  4260  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 14:21:16.679  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:16.680  4260  4272 I BluetoothAdapterState: Entering BleOnState
08-29 14:21:16.681  4260  4272 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 14:21:16.682  4260  4272 D BluetoothAdapterProperties: Setting state to 11
,08-29 14:21:16.682  4260  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 14:21:16.688  4260  4280 I bt_vendor: low_power_mode_cb
08-29 14:21:16.694  4260  4260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
08-29 14:21:16.698  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:16.699  4260  4260 D HeadsetService: Received start request. Starting profile...
,08-29 14:21:16.700  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:16.702  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:16.705  4260  4260 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 14:21:16.705  4260  4260 D HeadsetStateMachine: make
,08-29 14:21:16.723  4260  4272 I BluetoothAdapterState: Entering PendingCommandState
,08-29 14:21:16.726  4260  4260 D HeadsetStateMachine: max_hf_connections = 1
,08-29 14:21:16.726  4260  4260 I bt_bluedroid: get_profile_interface handsfree
08-29 14:21:16.726  4260  4276 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 14:21:16.726  4260  4276 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-29 14:21:16.729  4260  4260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:16.730  4260  4260 D A2dpService: Received start request. Starting profile...
08-29 14:21:16.731  4260  4260 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 14:21:16.731  4260  4260 I bt_bluedroid: get_profile_interface avrcp
,08-29 14:21:16.737  4260  4260 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 14:21:16.737  4260  4260 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 14:21:16.737  4260  4260 D A2dpStateMachine: make
,08-29 14:21:16.738  4260  4260 I bt_bluedroid: get_profile_interface a2dp
,08-29 14:21:16.739  4260  4276 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 14:21:16.741  4260  4260 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 14:21:16.741  4260  4260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
08-29 14:21:16.742  4260  4292 D A2dpStateMachine: Enter Disconnected: -2
,08-29 14:21:16.743  4260  4260 D HidService: Received start request. Starting profile...
08-29 14:21:16.743  4260  4260 I bt_bluedroid: get_profile_interface hidhost
,08-29 14:21:16.743  4260  4276 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397b3e5
,08-29 14:21:16.743  4260  4260 D HidService: setHidService(): set to: null
08-29 14:21:16.743  4260  4276 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 14:21:16.744  4054  4054 D BluetoothInputDevice: Proxy object connected
,08-29 14:21:16.745  4054  4054 D HidProfile: Bluetooth service connected
08-29 14:21:16.746  4260  4260 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 14:21:16.746  4260  4260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
08-29 14:21:16.749  4260  4260 D HealthService: Received start request. Starting profile...
,08-29 14:21:16.752  4260  4260 I bt_bluedroid: get_profile_interface health
,08-29 14:21:16.753  4260  4260 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 14:21:16.754  4260  4260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:16.755  4260  4260 D PanService: Received start request. Starting profile...
,08-29 14:21:16.755  4054  4054 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:21:16.756  4260  4260 D BluetoothPanServiceJni: initializeNative(L110): pan,
,08-29 14:21:16.756  4260  4260 I bt_bluedroid: get_profile_interface pan
,08-29 14:21:16.756  4054  4054 D PanProfile: Bluetooth service connected
,08-29 14:21:16.756  4260  4276 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 14:21:16.760  4260  4260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:16.761  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:21:16.762  4260  4260 D BluetoothMapService: Received start request. Starting profile...
,08-29 14:21:16.762  4260  4260 D BluetoothMapService: start()
,08-29 14:21:16.762  4054  4054 D BluetoothMap: Proxy object connected
08-29 14:21:16.762  4054  4054 D MapProfile: Bluetooth service connected,
08-29 14:21:16.763  4054  4054 D BluetoothMap: getConnectedDevices()
,08-29 14:21:16.763  4054  4054 D BluetoothMap: Bluetooth is Not enabled
,08-29 14:21:16.764  4260  4260 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 14:21:16.765  4260  4260 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 14:21:16.765  4260  4260 D BluetoothMapAppObserver: createReceiver()
08-29 14:21:16.766  4260  4260 D BluetoothMapAppObserver: initObservers()
,08-29 14:21:16.766  4260  4260 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 14:21:16.773  4260  4260 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:21:16.773  4260  4260 V BluetoothAdapterState: isTurningOn()=true
,08-29 14:21:16.773  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:21:16.773  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:16.775  4260  4290 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 14:21:16.775  4260  4260 V BluetoothAdapterState: isTurningOff()=false
08-29 14:21:16.775  4260  4260 V BluetoothAdapterState: isTurningOn()=true
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isTurningOn()=true
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isTurningOff()=false
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isTurningOn()=true
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isTurningOff()=false
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isTurningOn()=true
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:16.776  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:21:16.778  4260  4260 V BluetoothAdapterState: isTurningOff()=false
08-29 14:21:16.778  4260  4260 V BluetoothAdapterState: isTurningOn()=true
08-29 14:21:16.778  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:21:16.778  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:16.778  4260  4272 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 14:21:16.779  4260  4272 D BluetoothAdapterProperties: ScanMode =  20
08-29 14:21:16.779  4260  4272 D BluetoothAdapterProperties: State =  11
08-29 14:21:16.783  4260  4276 D BluetoothAdapterProperties: Scan Mode:21
08-29 14:21:16.784  4260  4276 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 14:21:16.784  4260  4272 D BluetoothAdapterProperties: Setting state to 12
,08-29 14:21:16.784  4260  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 14:21:16.784  4260  4272 I BluetoothAdapterState: Entering OnState
08-29 14:21:16.785  4054  4066 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 14:21:16.785  1369  1395 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 14:21:16.786  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:16.786  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:16.786  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:16.786  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:16.786  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:16.786  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:16.786  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:16.786  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:16.787  1369  1369 D BluetoothInputDevice: Proxy object connected
08-29 14:21:16.787  1369  1369 D HidProfile: Bluetooth service connected
,08-29 14:21:16.787   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 14:21:16.788   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:16.788   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 14:21:16.788  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:16.788  1369  1392 D BluetoothMap: onBluetoothStateChange: up=true
08-29 14:21:16.789   871   871 D BluetoothA2dp: Proxy object connected
08-29 14:21:16.790  1369  1369 D BluetoothMap: Proxy object connected
,08-29 14:21:16.790  1369  1369 D MapProfile: Bluetooth service connected
08-29 14:21:16.790  1369  1369 D BluetoothMap: getConnectedDevices()
08-29 14:21:16.790  1369  1694 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 14:21:16.791  4054  4064 D BluetoothPan: onBluetoothStateChange on: true
,08-29 14:21:16.791  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:16.791  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:16.791  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:16.791  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:16.791  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:16.791  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:16.791  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:16.791  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:16.792  1369  2128 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:16.792  4054  4066 D BluetoothMap: onBluetoothStateChange: up=true
08-29 14:21:16.792  4260  4260 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 14:21:16.793   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:16.793  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:16.793  4260  4260 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 14:21:16.793  1369  1392 D BluetoothPan: onBluetoothStateChange on: true
08-29 14:21:16.794  4260  4260 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:21:16.795  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:21:16.795  4054  4064 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 14:21:16.795  1369  1369 D PanProfile: Bluetooth service connected
08-29 14:21:16.796  2010  2110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:16.796  1369  1694 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 14:21:16.797  4260  4260 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:16.798  1369  1369 D BluetoothA2dp: Proxy object connected
,08-29 14:21:16.798   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 14:21:16.799  4260  4260 D ObexServerSockets: Succeed to create listening sockets 
08-29 14:21:16.800  4260  4260 D ObexServerSockets0: startAccept()
08-29 14:21:16.800  4260  4260 D ObexServerSockets0: prepareForNewConnect()
,08-29 14:21:16.801  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:16.802  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:16.802  4054  4054 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 14:21:16.803  4260  4260 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 14:21:16.803  4260  4260 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 14:21:16.803  4260  4298 D ObexServerSockets0: Accepting socket connection...
08-29 14:21:16.804  4260  4299 D ObexServerSockets0: Accepting socket connection...
08-29 14:21:16.804  4260  4260 D BluetoothMapService: onReceive
08-29 14:21:16.804  4260  4260 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:16.804  4260  4260 D BluetoothMapService: STATE_ON
08-29 14:21:16.806  4054  4054 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 14:21:16.810  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:21:16.812  4054  4054 D BluetoothA2dp: Proxy object connected
,08-29 14:21:16.815  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:16.819  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:16.827  1369  1369 D BluetoothPbap: Proxy object connected
08-29 14:21:16.827  1369  1369 D PbapServerProfile: Bluetooth service connected
,08-29 14:21:16.827  4054  4054 D BluetoothPbap: Proxy object connected
08-29 14:21:16.828  4054  4054 D PbapServerProfile: Bluetooth service connected
,08-29 14:21:16.832  4260  4260 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 14:21:16.832  4260  4260 D ObexServerSockets0: prepareForNewConnect()
,08-29 14:21:16.833  4260  4303 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:16.848  4260  4307 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:16.849  4260  4307 I BtOppRfcommListener: Accept thread started.
,08-29 14:21:16.889   871   871 D BluetoothHeadset: Proxy object connected
,08-29 14:21:16.889  2010  2174 D BluetoothHeadset: Proxy object connected
08-29 14:21:16.890  1369  1392 D BluetoothHeadset: Proxy object connected
08-29 14:21:16.890  1369  1369 D HeadsetProfile: Bluetooth service connected
08-29 14:21:16.890   871   871 D BluetoothHeadset: Proxy object connected
,08-29 14:21:16.890   871   871 D BluetoothHeadset: Proxy object connected
08-29 14:21:16.892  1369  1694 D BluetoothHeadset: Proxy object connected
,08-29 14:21:16.893  1369  1369 D HeadsetProfile: Bluetooth service connected
08-29 14:21:16.893   871   888 D BluetoothHeadset: Proxy object connected
,08-29 14:21:16.896  2010  2038 D BluetoothHeadset: Proxy object connected
,08-29 14:21:16.908  4054  4066 D BluetoothHeadset: Proxy object connected
,08-29 14:21:16.909  4054  4054 D HeadsetProfile: Bluetooth service connected
,08-29 14:21:18.165   871  1315 D ConnectivityService: handlePromptUnvalidated 101
,08-29 14:21:18.207  4260  4272 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 14:21:18.207  4260  4272 D BluetoothAdapterProperties: Setting state to 13
,08-29 14:21:18.208  4260  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 14:21:18.209  4260  4272 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 14:21:18.218  4260  4260 D BluetoothMapService: onReceive
08-29 14:21:18.218  4260  4260 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:18.219  4260  4260 D BluetoothMapService: STATE_TURNING_OFF
,08-29 14:21:18.219  4260  4260 D BluetoothMapService: MAP Service closeService in
08-29 14:21:18.220  4260  4260 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 14:21:18.220  4260  4260 D ObexServerSockets0: shutdown(block = true)
,08-29 14:21:18.221  4260  4298 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 14:21:18.221  4260  4272 I BluetoothAdapterState: Entering PendingCommandState
08-29 14:21:18.223  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:18.223  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:18.223  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:18.223  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:18.223  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:18.223  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:18.223  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:18.223  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:18.223  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:18.223  4260  4276 D BluetoothAdapterProperties: Scan Mode:20
,08-29 14:21:18.224  4260  4272 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 14:21:18.224  4260  4260 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 14:21:18.225  4260  4299 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 14:21:18.225  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:21:18.226  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:18.226  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:18.226  4260  4260 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 14:21:18.228  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:18.231  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:18.231  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:18.231  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:18.231  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:18.231  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:18.231  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:18.231  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:18.231  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:18.231  4260  4260 I BtOppRfcommListener: stopping Accept Thread
08-29 14:21:18.231  4260  4307 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 14:21:18.232  4260  4307 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 14:21:18.226  4260  4284 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 14:21:18.235  3985  3985 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-29 14:21:18.235  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:18.237  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:18.239  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:18.239  4260  4260 D HeadsetService: Received stop request...Stopping profile...
,08-29 14:21:18.242   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:18.243  4054  4066 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:18.244  2010  2174 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:18.244  4260  4260 D A2dpService: Received stop request...Stopping profile...
08-29 14:21:18.244  1369  2128 D BluetoothHeadset: Proxy object disconnected
,08-29 14:21:18.245  4260  4292 D A2dpStateMachine: Exit Disconnected: -1
08-29 14:21:18.245   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:18.245   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 14:21:18.246   871   871 D BluetoothA2dp: Proxy object disconnected
08-29 14:21:18.249  1369  1369 D HeadsetProfile: Bluetooth service disconnected
08-29 14:21:18.249  1369  1369 D BluetoothA2dp: Proxy object disconnected
08-29 14:21:18.251  4260  4260 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:18.251  4260  4260 V BluetoothAdapterState: isTurningOn()=false
,08-29 14:21:18.251  4054  4054 D DockEventReceiver: finishStartingService: stopping service
08-29 14:21:18.251  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:18.251  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:18.251  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:18.252  4054  4054 D HeadsetProfile: Bluetooth service disconnected
08-29 14:21:18.253  4054  4054 D BluetoothA2dp: Proxy object disconnected
08-29 14:21:18.253  4260  4260 D HidService: Received stop request...Stopping profile...
08-29 14:21:18.253  4260  4260 D HidService: Stopping Bluetooth HidService
,08-29 14:21:18.255  1369  1369 D BluetoothInputDevice: Proxy object disconnected
08-29 14:21:18.255  1369  1369 D HidProfile: Bluetooth service disconnected
,08-29 14:21:18.256  4054  4054 D BluetoothInputDevice: Proxy object disconnected
08-29 14:21:18.256  4054  4054 D HidProfile: Bluetooth service disconnected
,08-29 14:21:18.259  4260  4260 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 14:21:18.260  4260  4260 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 14:21:18.260  4260  4282 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:21:18.261  4260  4282 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:21:18.261  4260  4282 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:21:18.260  4260  4276 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 14:21:18.261  4260  4276 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-29 14:21:18.262  4260  4260 D HealthService: Received stop request...Stopping profile...
,08-29 14:21:18.264  4260  4260 V BluetoothAdapterState: isTurningOff()=true
,08-29 14:21:18.264  4260  4260 V BluetoothAdapterState: isTurningOn()=false
,08-29 14:21:18.264  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:21:18.265  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:18.266  4260  4282 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 14:21:18.266  4260  4282 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 14:21:18.266  4260  4282 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 14:21:18.266  4260  4282 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:18.267  4260  4282 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 14:21:18.267  4260  4282 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:18.267  4260  4276 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 14:21:18.267  4260  4260 D PanService: Received stop request...Stopping profile...
08-29 14:21:18.268  4054  4054 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 14:21:18.268  4054  4054 D PanProfile: Bluetooth service disconnected
,08-29 14:21:18.268  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 14:21:18.268  1369  1369 D PanProfile: Bluetooth service disconnected
08-29 14:21:18.270  1369  1369 D BluetoothPbap: Proxy object disconnected
08-29 14:21:18.270  1369  1369 D PbapServerProfile: Bluetooth service disconnected
08-29 14:21:18.270  4260  4260 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:18.270  4260  4260 V BluetoothAdapterState: isTurningOn()=false
,08-29 14:21:18.270  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:18.270  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:18.270  4260  4260 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 14:21:18.270  4260  4260 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 14:21:18.271  4260  4276 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
08-29 14:21:18.271  4260  4260 D BluetoothMapService: Received stop request...Stopping profile...
08-29 14:21:18.271  4260  4260 D BluetoothMapService: stop()
08-29 14:21:18.275  4260  4260 D BluetoothMapAppObserver: deinitObservers(),
08-29 14:21:18.276  4260  4260 D BluetoothMapAppObserver: removeReceiver()
,08-29 14:21:18.277  1369  1369 D BluetoothMap: Proxy object disconnected
,08-29 14:21:18.277  1369  1369 D MapProfile: Bluetooth service disconnected
08-29 14:21:18.277  4260  4260 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:18.277  4260  4260 V BluetoothAdapterState: isTurningOn()=false
08-29 14:21:18.277  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:18.278  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:18.278  4260  4260 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 14:21:18.278  4260  4276 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-29 14:21:18.279  4260  4260 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 14:21:18.279  4260  4260 V BluetoothAdapterState: isTurningOff()=true
,08-29 14:21:18.279  4260  4260 V BluetoothAdapterState: isTurningOn()=false
,08-29 14:21:18.279  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:18.279  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:18.270  4054  4054 D BluetoothPbap: Proxy object disconnected
,08-29 14:21:18.279  4054  4054 D PbapServerProfile: Bluetooth service disconnected
08-29 14:21:18.279  4260  4260 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 14:21:18.280  4260  4260 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 14:21:18.280  4054  4054 D BluetoothMap: Proxy object disconnected
08-29 14:21:18.280  4054  4054 D MapProfile: Bluetooth service disconnected
08-29 14:21:18.281  4260  4260 D BluetoothMapService: MAP Service closeService in
,08-29 14:21:18.281  4260  4260 V BluetoothAdapterState: isTurningOff()=true
08-29 14:21:18.281  4260  4260 V BluetoothAdapterState: isTurningOn()=false
08-29 14:21:18.281  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:21:18.281  4260  4260 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:18.281  4260  4260 D BluetoothMapService: cleanup()
08-29 14:21:18.281  4260  4260 D BluetoothMapService: MAP Service closeService in
08-29 14:21:18.282  4260  4272 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 14:21:18.282  4260  4272 D BluetoothAdapterProperties: Setting state to 15
08-29 14:21:18.282  4260  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 14:21:18.282  4260  4272 I BluetoothAdapterState: Entering BleOnState
08-29 14:21:18.282  4054  4064 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:21:18.283  4054  4066 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 14:21:18.284  1369  1392 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 14:21:18.284   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:18.284   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:18.284   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:21:18.284  1369  1395 D BluetoothMap: onBluetoothStateChange: up=false
08-29 14:21:18.285  1369  1694 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 14:21:18.285  4054  4064 D BluetoothPan: onBluetoothStateChange on: false
08-29 14:21:18.286  1369  2128 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:18.286  4054  4066 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 14:21:18.286   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 14:21:18.287  1369  1392 D BluetoothPan: onBluetoothStateChange on: false
08-29 14:21:18.287  4054  4064 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 14:21:18.287  2010  2038 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:21:18.288  1369  1395 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 14:21:18.288  4054  4066 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 14:21:18.288  4260  4272 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 14:21:18.288  4260  4272 D BluetoothAdapterProperties: Setting state to 16
08-29 14:21:18.288  4260  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 14:21:18.289  4260  4272 D BluetoothAdapterProperties: onBleDisable
08-29 14:21:18.290  4260  4273 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 14:21:18.290  4260  4272 I BluetoothAdapterState: Entering PendingCommandState
08-29 14:21:18.290  4260  4282 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 14:21:18.291  4260  4282 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:21:18.291  4260  4276 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:21:18.292  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:18.292  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 14:21:18.294  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:18.296  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:18.296  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:18.297  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:18.302  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:18.347  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:21:18.352  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:21:18.354  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:21:18.374  1503  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 14:21:18.374  1503  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 14:21:18.374  1503  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:21:18.374  1503  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:21:18.389  3692  3692 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 14:21:18.389  3692  3692 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 14:21:18.389  3692  3692 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 14:21:18.491  4260  4276 I bt_hci  : shut_down
,08-29 14:21:18.502  4260  4280 I bt_vendor: low_power_mode_cb
,08-29 14:21:18.507  4260  4280 D bt_hwcfg: hw_epilog_process
,08-29 14:21:18.515  4260  4280 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 14:21:18.515  4260  4280 I bt_vendor: epilog_cb
08-29 14:21:18.515  4260  4280 I bt_hci  : epilog_finished_callback
,08-29 14:21:18.520  4260  4276 I bt_hci_h4: hal_close
,08-29 14:21:18.521  4260  4276 I bt_userial_vendor: device fd = 51 close
,08-29 14:21:18.645  4260  4273 D bt_stack_manager: event_shut_down_stack finished.
,08-29 14:21:18.646  4260  4272 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 14:21:18.652  4260  4272 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 14:21:18.652  4260  4260 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 14:21:18.654  4260  4260 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 14:21:18.654  4260  4260 D BtGatt.GattService: stop()
,08-29 14:21:18.656  4260  4260 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 14:21:18.662  4260  4260 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:21:18.662  4260  4260 V BluetoothAdapterState: isTurningOn()=false
,08-29 14:21:18.663  4260  4260 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:18.663  4260  4260 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 14:21:18.664  4260  4272 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 14:21:18.664  4260  4272 D BluetoothAdapterProperties: Setting state to 10
08-29 14:21:18.665  4260  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 14:21:18.667  4260  4272 I BluetoothAdapterState: Entering OffState
08-29 14:21:18.668   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 14:21:18.698  4260  4260 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 14:21:18.698  4260  4260 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 14:21:18.699  4260  4273 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 14:21:18.707  4260  4273 D bt_stack_manager: event_clean_up_stack finished.,
,08-29 14:21:18.707  4260  4260 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 14:21:18.711  4260  4260 I art     : System.exit called, status: 0
08-29 14:21:18.711  4260  4260 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 14:21:18.771   871  1972 I ActivityManager: Process com.android.bluetooth (pid 4260) has died
,08-29 14:21:21.204  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:21:21.205  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:23.181   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 14:21:23.194   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 14:21:23.194   871   891 I Adreno  : Build Date                       : 10/20/15
08-29 14:21:23.194   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 14:21:23.194   871   891 I Adreno  : Local Branch                     : M14
08-29 14:21:23.194   871   891 I Adreno  : Remote Branch                    : 
08-29 14:21:23.194   871   891 I Adreno  : Remote Branch                    : 
08-29 14:21:23.194   871   891 I Adreno  : Reconstruct Branch               : 
08-29 14:21:23.210  1906  1906 I Keyboard.Facilitator: onFinishInput()
,08-29 14:21:23.242   282   464 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (326 us)
,08-29 14:21:23.876  3985  3985 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 14:21:23.876  3985  3985 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 14:21:23.909   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 14:21:23.910  3985  3985 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4bde8a7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f71f9b9, 16908290=android.view.AbsSavedState$1@f71f9b9}, android:focusedViewId=100}]}]
08-29 14:21:23.911  3985  3985 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-29 14:21:23.911  3985  3985 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 14:21:23.911  3985  3985 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 14:21:23.921   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 14:21:23.926   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 14:21:23.927   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-29 14:21:23.927   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 14:21:24.156   282   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 14:21:24.160   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 14:21:24.166   871  1339 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
08-29 14:21:24.170   871   891 I DreamManagerService: Entering dreamland.
08-29 14:21:24.171   871   891 I PowerManagerService: Dozing...
,08-29 14:21:24.173   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 14:21:24.207   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-29 14:21:24.207   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 14:21:24.209  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:24.209  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb3e1fe added. We now have 6 listener(s)
08-29 14:21:24.209  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:24.210  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:24.210  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e6cd5f added. We now have 7 listener(s)
,08-29 14:21:24.210  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:24.211  3985  4034 I System.out: IsBluetoothEnabled
,08-29 14:21:24.216  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:24.219   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:21:24.220  1998  4320 D NfcService: Discovery configuration equal, not updating.
,08-29 14:21:24.223   871  1313 E native  : do suspend false
,08-29 14:21:24.233   871   888 I ActivityManager: Start proc 4322:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 14:21:24.259   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:21:24.264   871  1313 E native  : do suspend true
,08-29 14:21:24.312  4322  4322 D AdapterServiceConfig: Adding HeadsetService
,08-29 14:21:24.312  4322  4322 D AdapterServiceConfig: Adding A2dpService
08-29 14:21:24.313  4322  4322 D AdapterServiceConfig: Adding HidService
08-29 14:21:24.313  4322  4322 D AdapterServiceConfig: Adding HealthService
,08-29 14:21:24.313  4322  4322 D AdapterServiceConfig: Adding PanService
08-29 14:21:24.313  4322  4322 D AdapterServiceConfig: Adding GattService
08-29 14:21:24.313  4322  4322 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 14:21:24.327   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@46d2427:true
,08-29 14:21:24.328  4322  4322 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 14:21:24.332  4322  4322 I bt_bluedroid: init
,08-29 14:21:24.332  4322  4334 I BluetoothAdapterState: Entering OffState
,08-29 14:21:24.337  4322  4335 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 14:21:24.338  4322  4335 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 14:21:24.338  4322  4335 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 14:21:24.338  4322  4335 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 14:21:24.340  4322  4322 I bt_bluedroid: get_profile_interface socket
,08-29 14:21:24.342  4322  4322 I bt_bluedroid: get_profile_interface sdp
,08-29 14:21:24.346  4322  4338 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 14:21:24.349   375  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 14:21:24.349   375  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
08-29 14:21:24.350  4322  4338 D BluetoothAdapterProperties: Name is: Nexus 6
08-29 14:21:24.352  4322  4333 I bt_bluedroid: config_hci_snoop_log
,08-29 14:21:24.355   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 14:21:24.366  4322  4334 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 14:21:24.367  4322  4334 D BluetoothAdapterProperties: Setting state to 14
08-29 14:21:24.367  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 14:21:24.369  4322  4334 D BluetoothBondStateMachine: make
,08-29 14:21:24.377  4322  4339 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 14:21:24.381  4322  4334 I BluetoothAdapterState: Entering PendingCommandState
,08-29 14:21:24.383  4322  4322 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 14:21:24.387  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:24.389  4322  4322 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 14:21:24.389  4322  4322 D BtGatt.GattService: Received start request. Starting profile...
,08-29 14:21:24.390  4322  4322 D BtGatt.GattService: start()
08-29 14:21:24.390  4322  4322 I bt_bluedroid: get_profile_interface gatt
,08-29 14:21:24.391  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:24.391  4322  4322 D BtGatt.AdvertiseManager: advertise manager created
,08-29 14:21:24.407  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 14:21:24.407  4322  4322 V BluetoothAdapterState: isTurningOn()=false
08-29 14:21:24.407  4322  4322 V BluetoothAdapterState: isBleTurningOn()=true
08-29 14:21:24.408  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:24.409  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 14:21:24.409  4322  4334 I bt_bluedroid: enable
08-29 14:21:24.409  4322  4335 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 14:21:24.410  4322  4335 I bt_hci  : start_up
,08-29 14:21:24.425  4322  4335 I bt_vendor: alloc value 0xb3a1c189
08-29 14:21:24.425  4322  4335 I bt_vendor: init
08-29 14:21:24.425  4322  4335 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 14:21:24.425  4322  4335 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 14:21:24.533  4322  4335 D bt_hci  : start_up starting async portion
,08-29 14:21:24.534  4322  4344 I bt_hci  : event_finish_startup
08-29 14:21:24.534  4322  4344 I bt_hci_h4: hal_open
08-29 14:21:24.534  4322  4344 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 14:21:24.546  4322  4344 I bt_userial_vendor: device fd = 51 open
,08-29 14:21:24.575  4322  4344 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 14:21:24.607  4322  4344 D bt_hwcfg: Chipset BCM4354A2
,08-29 14:21:24.607  4322  4344 D bt_hwcfg: Target name = [BCM4354A2]
08-29 14:21:24.609  4322  4344 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 14:21:25.279  4322  4344 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 14:21:25.280  4322  4344 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 14:21:25.281  4322  4344 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 14:21:25.398  4322  4344 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 14:21:25.400  4322  4344 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 14:21:25.429  4322  4344 I bt_hwcfg: vendor lib fwcfg completed
,08-29 14:21:25.429  4322  4344 I bt_vendor: firmware callback
,08-29 14:21:25.429  4322  4344 I bt_hci  : firmware_config_callback
,08-29 14:21:25.443  4322  4346 I bt_btu  : btu_task pending for preload complete event
,08-29 14:21:25.443  4322  4346 I bt_btu_task: Bluetooth chip preload is complete
08-29 14:21:25.443  4322  4346 I bt_btu  : btu_task received preload complete event
,08-29 14:21:25.455  4322  4346 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 14:21:25.455  4322  4346 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 14:21:25.455  4322  4346 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 14:21:25.456  4322  4346 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 14:21:25.456  4322  4346 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 14:21:25.456  4322  4346 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 14:21:25.457  4322  4346 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 14:21:25.457  4322  4346 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 14:21:25.457  4322  4346 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 14:21:25.457  4322  4346 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 14:21:25.458  4322  4346 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 14:21:25.458  4322  4346 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 14:21:25.458  4322  4346 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 14:21:25.458  4322  4346 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 14:21:25.459  4322  4346 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 14:21:25.594  4322  4346 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3999d9d
,08-29 14:21:25.594  4322  4346 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3999d9d 
,08-29 14:21:25.606  4322  4338 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 14:21:25.608  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 14:21:25.609  4322  4338 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-29 14:21:25.612  4322  4338 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 14:21:25.615  4322  4338 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:21:25.615  4322  4338 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 14:21:25.616  4322  4338 D bt_hci  : do_postload posting postload work item
,08-29 14:21:25.616  4322  4344 I bt_hci  : event_postload
,08-29 14:21:25.616  4322  4344 I bt_vendor: sco_config_cb
,08-29 14:21:25.617  4322  4344 I bt_hci  : sco_config_callback postload finished.
,08-29 14:21:25.619  4322  4338 D bt_bte_conf: Device ID record 1 : primary
08-29 14:21:25.620  4322  4338 D bt_bte_conf:   vendorId            = 000f
,08-29 14:21:25.620  4322  4338 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 14:21:25.620  4322  4338 D bt_bte_conf:   product             = 1200
,08-29 14:21:25.620  4322  4338 D bt_bte_conf:   version             = 1436
,08-29 14:21:25.621  4322  4338 D bt_bte_conf:   clientExecutableURL = 
08-29 14:21:25.621  4322  4338 D bt_bte_conf:   serviceDescription  = 
08-29 14:21:25.621  4322  4338 D bt_bte_conf:   documentationURL    = 
08-29 14:21:25.621  4322  4338 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 14:21:25.622  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:25.622  4322  4335 D bt_stack_manager: event_start_up_stack finished
,08-29 14:21:25.624  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 14:21:25.625  4322  4334 D BluetoothAdapterProperties: Setting state to 15
,08-29 14:21:25.625  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 14:21:25.626  4322  4334 I BluetoothAdapterState: Entering BleOnState
,08-29 14:21:25.629  4322  4344 I bt_vendor: low_power_mode_cb
08-29 14:21:25.633  4322  4334 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 14:21:25.633  4322  4334 D BluetoothAdapterProperties: Setting state to 11
08-29 14:21:25.633  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 14:21:25.638  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:25.641  4322  4322 D HeadsetService: Received start request. Starting profile...
08-29 14:21:25.643  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:25.644  4322  4322 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 14:21:25.644  4322  4322 D HeadsetStateMachine: make
08-29 14:21:25.652  4322  4334 I BluetoothAdapterState: Entering PendingCommandState
08-29 14:21:25.658  4322  4322 D HeadsetStateMachine: max_hf_connections = 1
08-29 14:21:25.658  4322  4322 I bt_bluedroid: get_profile_interface handsfree
08-29 14:21:25.658  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 14:21:25.659  4322  4338 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 14:21:25.663  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:25.663  4322  4322 D A2dpService: Received start request. Starting profile...
,08-29 14:21:25.664  4322  4322 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 14:21:25.664  4322  4322 I bt_bluedroid: get_profile_interface avrcp
,08-29 14:21:25.670  4322  4322 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 14:21:25.670  4322  4322 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 14:21:25.670  4322  4322 D A2dpStateMachine: make
,08-29 14:21:25.672  4322  4322 I bt_bluedroid: get_profile_interface a2dp
,08-29 14:21:25.672  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 14:21:25.674  4322  4355 D A2dpStateMachine: Enter Disconnected: -2
,08-29 14:21:25.675  4322  4322 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 14:21:25.676  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:25.676  4322  4322 D HidService: Received start request. Starting profile...
,08-29 14:21:25.676  4322  4322 I bt_bluedroid: get_profile_interface hidhost
08-29 14:21:25.676  4322  4322 D HidService: setHidService(): set to: null
,08-29 14:21:25.676  4322  4338 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397b3e5
08-29 14:21:25.676  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 14:21:25.677  4322  4322 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 14:21:25.678  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:25.678  4322  4322 D HealthService: Received start request. Starting profile...
,08-29 14:21:25.679  4322  4322 I bt_bluedroid: get_profile_interface health
,08-29 14:21:25.680  4322  4322 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 14:21:25.680  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
08-29 14:21:25.681  4322  4322 D PanService: Received start request. Starting profile...
,08-29 14:21:25.681  4322  4322 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 14:21:25.681  4322  4322 I bt_bluedroid: get_profile_interface pan
,08-29 14:21:25.682  4322  4338 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 14:21:25.684  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:25.685  4322  4322 D BluetoothMapService: Received start request. Starting profile...
,08-29 14:21:25.685  4322  4322 D BluetoothMapService: start()
,08-29 14:21:25.687  4322  4322 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 14:21:25.688  4322  4322 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 14:21:25.688  4322  4322 D BluetoothMapAppObserver: createReceiver()
,08-29 14:21:25.688  4322  4322 D BluetoothMapAppObserver: initObservers()
,08-29 14:21:25.689  4322  4322 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 14:21:25.696  4322  4322 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:21:25.697  4322  4322 V BluetoothAdapterState: isTurningOn()=true
08-29 14:21:25.697  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:25.697  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:21:25.697  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isTurningOn()=true
,08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:21:25.699  4322  4353 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isTurningOn()=true
,08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isTurningOn()=true
,08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:25.699  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:21:25.700  4322  4322 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:21:25.700  4322  4322 V BluetoothAdapterState: isTurningOn()=true
08-29 14:21:25.700  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:25.700  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:21:25.700  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 14:21:25.700  4322  4322 V BluetoothAdapterState: isTurningOn()=true
,08-29 14:21:25.700  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:21:25.700  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:21:25.700  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 14:21:25.701  4322  4334 D BluetoothAdapterProperties: ScanMode =  20
,08-29 14:21:25.701  4322  4334 D BluetoothAdapterProperties: State =  11
08-29 14:21:25.701  4322  4334 D BluetoothAdapterProperties: Setting state to 12
08-29 14:21:25.701  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 14:21:25.703  4054  4064 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:21:25.703  4322  4338 D BluetoothAdapterProperties: Scan Mode:21
08-29 14:21:25.703  4322  4338 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 14:21:25.704  4322  4334 I BluetoothAdapterState: Entering OnState
08-29 14:21:25.705  4054  4066 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 14:21:25.707  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:25.707  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:25.707  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:25.707  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:25.707  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:25.707  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:25.707  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:25.707  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:25.708  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:21:25.709  1369  1392 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 14:21:25.710  1369  1369 D BluetoothInputDevice: Proxy object connected
08-29 14:21:25.710  1369  1369 D HidProfile: Bluetooth service connected
,08-29 14:21:25.711   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 14:21:25.711   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:25.711   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 14:21:25.714   871   871 D BluetoothA2dp: Proxy object connected
08-29 14:21:25.714  1369  1395 D BluetoothMap: onBluetoothStateChange: up=true
08-29 14:21:25.714  4054  4054 D BluetoothA2dp: Proxy object connected
08-29 14:21:25.715  4322  4322 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 14:21:25.716  4322  4322 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 14:21:25.717  1369  2128 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 14:21:25.718  4322  4322 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:25.719  4054  4066 D BluetoothPan: onBluetoothStateChange on: true
,08-29 14:21:25.720  4322  4322 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:25.722  1369  1392 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:21:25.722  4322  4322 D ObexServerSockets: Succeed to create listening sockets 
08-29 14:21:25.722  4322  4322 D ObexServerSockets0: startAccept()
08-29 14:21:25.722  4322  4322 D ObexServerSockets0: prepareForNewConnect()
,08-29 14:21:25.722  4054  4064 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 14:21:25.724   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 14:21:25.724  1369  1694 D BluetoothPan: onBluetoothStateChange on: true
,08-29 14:21:25.724  4322  4322 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 14:21:25.725  4322  4322 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 14:21:25.725  4322  4361 D ObexServerSockets0: Accepting socket connection...
08-29 14:21:25.725  4322  4362 D ObexServerSockets0: Accepting socket connection...
08-29 14:21:25.726  1369  1369 D BluetoothMap: Proxy object connected
08-29 14:21:25.726  1369  1369 D MapProfile: Bluetooth service connected
,08-29 14:21:25.726  1369  1369 D BluetoothMap: getConnectedDevices()
,08-29 14:21:25.727  4054  4064 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 14:21:25.728  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 14:21:25.728  1369  1369 D PanProfile: Bluetooth service connected
,08-29 14:21:25.728  4054  4054 D BluetoothInputDevice: Proxy object connected
08-29 14:21:25.728  4054  4054 D HidProfile: Bluetooth service connected
08-29 14:21:25.728  2010  2174 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 14:21:25.729  1369  1392 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 14:21:25.730  1369  1369 D BluetoothA2dp: Proxy object connected
08-29 14:21:25.731  4054  4066 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 14:21:25.732  4054  4054 D BluetoothMap: Proxy object connected
,08-29 14:21:25.732  4054  4054 D MapProfile: Bluetooth service connected
,08-29 14:21:25.733   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 14:21:25.733  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:25.734  4322  4322 D BluetoothMapService: onReceive
,08-29 14:21:25.734  4322  4322 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:25.734  4322  4322 D BluetoothMapService: STATE_ON
08-29 14:21:25.734  4054  4054 D BluetoothMap: getConnectedDevices()
,08-29 14:21:25.739  4054  4054 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 14:21:25.739  4054  4054 D PanProfile: Bluetooth service connected
,08-29 14:21:25.746  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:21:25.751  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:25.752  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:25.759  4054  4054 D BluetoothPbap: Proxy object connected
,08-29 14:21:25.759  4054  4054 D PbapServerProfile: Bluetooth service connected
08-29 14:21:25.759  1369  1369 D BluetoothPbap: Proxy object connected
,08-29 14:21:25.760  1369  1369 D PbapServerProfile: Bluetooth service connected
08-29 14:21:25.760  4322  4322 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 14:21:25.760  4322  4322 D ObexServerSockets0: prepareForNewConnect()
,08-29 14:21:25.766  4322  4367 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:25.783  4322  4371 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:25.785  4322  4371 I BtOppRfcommListener: Accept thread started.
,08-29 14:21:25.812   871   871 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.813  4054  4363 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.813  4054  4054 D HeadsetProfile: Bluetooth service connected
,08-29 14:21:25.813  2010  2038 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.814  1369  1392 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.814  1369  1369 D HeadsetProfile: Bluetooth service connected
,08-29 14:21:25.814   871   871 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.815   871   871 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.822  1369  1694 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.822  1369  1369 D HeadsetProfile: Bluetooth service connected
,08-29 14:21:25.824   871   888 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.829  2010  2039 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.831  4054  4066 D BluetoothHeadset: Proxy object connected
,08-29 14:21:25.831  4054  4054 D HeadsetProfile: Bluetooth service connected
,08-29 14:21:26.237  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:26.237  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:26.237  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:26.237  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:26.237  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:26.237  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:26.237  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:26.237  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:26.243  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:26.247  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:26.248  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@55293ac added. We now have 8 listener(s)
,08-29 14:21:26.248  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:26.254   871  2048 D WifiService: setWifiEnabled: false pid=3985, uid=10000
08-29 14:21:26.254   871  2048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:21:26.266  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:26.267   871   881 D WifiService: setWifiEnabled: true pid=3985, uid=10000
,08-29 14:21:26.267   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:21:26.285   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-29 14:21:26.298  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-29 14:21:26.298  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:26.298  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:26.298  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:26.298  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:26.298  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:26.298  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:26.298  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:26.306  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:26.329   871  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-29 14:21:26.330   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 14:21:26.331   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 14:21:26.332   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 14:21:26.332   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 14:21:26.332   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 14:21:26.332   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 14:21:26.347   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 14:21:26.348   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.06 rxSuccessRate=0.05 delta 1000 -> 1000
,08-29 14:21:26.349   371   869 D CommandListener: Setting iface cfg
,08-29 14:21:26.349   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 14:21:26.349   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,08-29 14:21:26.350   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 14:21:26.361   871  1313 E native  : do suspend true
,08-29 14:21:26.370   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 14:21:26.370   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 14:21:26.378   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 14:21:26.378   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:21:26.388   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 14:21:26.466   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 14:21:26.470  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 14:21:26.896  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 14:21:26.937  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 14:21:26.938  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 14:21:26.946   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:21:26.957   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 14:21:26.957   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:26.958   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
,08-29 14:21:26.980   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:21:26.989   371   869 D CommandListener: Setting iface cfg
,08-29 14:21:26.990   871  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 14:21:27.002   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 14:21:27.020   871  4380 D DhcpClient: Receive thread started
,08-29 14:21:27.105   871  1313 E native  : do suspend false
,08-29 14:21:27.123   871  2115 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 14:21:27.146   871  4380 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-29 14:21:27.149   871  2115 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-29 14:21:27.153   871  2115 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 14:21:27.166   871  4380 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 14:21:27.167   871  2115 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 14:21:27.173   371   869 D CommandListener: Setting iface cfg
,08-29 14:21:27.185   871  2115 D DhcpClient: Scheduling renewal in 86399s
,08-29 14:21:27.184   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[],
,08-29 14:21:27.189   871  1313 E native  : do suspend true
,08-29 14:21:27.209   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 14:21:27.212   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 14:21:27.213   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 14:21:27.216   871  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 14:21:27.219   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 14:21:27.262   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 14:21:27.262   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 14:21:27.264   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 14:21:27.265   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 14:21:27.267   871  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 14:21:27.278   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 14:21:27.284  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:27.284  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:27.284  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:27.284  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:27.284  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:27.284  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:27.284  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:27.284  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:27.285   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-29 14:21:27.285   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 14:21:27.285   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 14:21:27.286   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 14:21:27.286   871  1315 D ConnectivityService:    accepting network in place of null
08-29 14:21:27.286   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 14:21:27.287  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:27.287   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 14:21:27.290  3985  4034 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 14:21:27.291  3985  4034 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 14:21:27.293  3985  4034 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4bde8a7 Bundle[{}]
,08-29 14:21:27.294  3985  4034 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 14:21:27.294  3985  4034 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 14:21:27.294  3985  4034 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 14:21:27.295  3985  4034 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 14:21:27.295  3985  4034 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 14:21:27.296  3985  4034 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 14:21:27.300  3985  4034 I System.out: Running OutgoingSocketThread
,08-29 14:21:27.302  3985  4385 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 461)
08-29 14:21:27.303  3985  4385 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49017
,08-29 14:21:27.303  3985  4385 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-29 14:21:27.304   871  4379 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156929, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 14:21:27.324   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:21:27.354   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:21:27.357   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 14:21:27.357   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:27.358   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 14:21:27.360   871   888 D Tethering: MasterInitialState.processMessage what=3
08-29 14:21:27.378  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:27.378  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:27.378  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:27.378  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:27.378  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:27.378  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:27.378  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:27.378  3985  3985 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:27.383   871  4378 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.46,2a00:1450:4001:802::200e
,08-29 14:21:27.386  3985  3985 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:27.394  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 14:21:27.398  1706  1706 D SystemUpdateService: onCreate
,08-29 14:21:27.400  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 14:21:27.421  1706  4390 I SystemUpdateService: active receiver: enabled
,08-29 14:21:27.424  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 14:21:27.426  1706  2521 I iu.UploadsManager: num queued entries: 0
,08-29 14:21:27.427  1706  2521 I iu.UploadsManager: num updated entries: 0
,08-29 14:21:27.435  1706  2521 I iu.SyncManager: NEXT; no task
,08-29 14:21:27.436  1706  4390 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 14:21:27.439  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 14:21:27.440  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 14:21:27.442  4108  4108 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:27.445  1706  4393 I MDM     : [189] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 14:21:27.445  1706  4393 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 14:21:27.449  4108  4108 D SprintDMHelper: simOperator: 
,08-29 14:21:27.449  4108  4108 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 14:21:27.456  1706  4393 V GoogleAuthProtoRequest: [189] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 14:21:27.465  1706  4390 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 14:21:27.466  1706  4390 I SystemUpdateService: now status is 0 (complete)
08-29 14:21:27.466  1706  4390 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 14:21:27.466  1706  4390 I SystemUpdateService: file has been verified
08-29 14:21:27.466  1706  4390 I SystemUpdateService: OTA package size = 12249756
08-29 14:21:27.470  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:21:27.475  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:21:27.486  1706  4390 I SystemUpdateService: showing system update notification
,08-29 14:21:27.514  1706  1706 D SystemUpdateService: onDestroy
,08-29 14:21:27.521  1503  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-29 14:21:27.521  1503  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 14:21:27.521  1503  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:21:27.522  1503  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:21:27.548  1706  4393 E MDM     : [189] SitrepService.a: Error sending sitrep.
,08-29 14:21:27.553   871  4378 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 12:21:27 GMT], X-Android-Received-Millis=[1472473287553], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472473287489]}
,08-29 14:21:27.554   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 14:21:27.555   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-29 14:21:27.555   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 14:21:27.559   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 14:21:27.632  2831  4395 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 14:21:28.303  3985  4034 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 462)
,08-29 14:21:28.304  3985  4034 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 462)
,08-29 14:21:28.313  3985  4034 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 467)
,08-29 14:21:28.316  3985  4034 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 14:21:28.316  3985  4034 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 468)
,08-29 14:21:28.320  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:21:28.320  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f7875 added. We now have 2 listener(s)
,08-29 14:21:28.322  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:21:28.322  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:28.323  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:28.323  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:28.323  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a68200a added. We now have 9 listener(s)
08-29 14:21:28.323  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:28.324  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:21:28.327  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:28.338  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:28.338  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:28.338  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:28.338  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:28.338  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:28.338  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:28.338  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:28.338  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:28.343  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:28.343  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:28.344  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:21:28.346  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:28.348  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62b3e98 added. We now have 3 listener(s)
,08-29 14:21:28.348  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:28.353  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 14:21:28.354  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 14:21:28.354  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:28.355  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:28.355  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0c26f1 added. We now have 10 listener(s)
08-29 14:21:28.355  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:28.356  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:28.356  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:28.356  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:28.357  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:28.357  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:28.357  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:28.357  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:28.358  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f7875 removed from the list
08-29 14:21:28.358  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:28.359  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a68200a removed from the list
08-29 14:21:28.359  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:28.359   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-29 14:21:28.359  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:28.360  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:28.361  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:28.363  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:28.363  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:28.363  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:28.364  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a68200a not in the list
08-29 14:21:28.364  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:28.364  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:28.366  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:28.367  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:28.367  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:28.367  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0c26f1 removed from the list
,08-29 14:21:28.367  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:28.368  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.368  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:28.368  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:28.368  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62b3e98 removed from the list
,08-29 14:21:28.370  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:28.371  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7032d6 added. We now have 2 listener(s)
,08-29 14:21:28.376  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 14:21:28.376  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:28.377  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:28.377  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:28.378  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c70957 added. We now have 9 listener(s)
,08-29 14:21:28.378  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:28.379  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:28.384  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:28.389  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:28.389  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:28.389  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:28.389  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:28.389  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:28.389  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:28.389  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:28.389  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:28.391  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:28.392  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:28.393  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:21:28.393  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52b412d added. We now have 3 listener(s)
08-29 14:21:28.394  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:28.395  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:21:28.395  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:28.395  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:28.395  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:28.395  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@714a662 added. We now have 10 listener(s)
08-29 14:21:28.395  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:28.396  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:28.396  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 14:21:28.396  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:28.396  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:28.396  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:21:28.397  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:28.400  3985  4034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 14:21:28.400  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:21:28.404  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:21:28.405  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
08-29 14:21:28.405  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:21:28.408  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:21:28.408  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 14:21:28.408  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 14:21:28.409  3985  4034 D BluetoothAdapter: STATE_ON
,08-29 14:21:28.412  4322  4360 D BtGatt.GattService: registerClient() - UUID=fb5fb017-1ba5-4e1e-99f6-dfbcff8ff68c
,08-29 14:21:28.413  4322  4338 D BtGatt.GattService: onClientRegistered() - UUID=fb5fb017-1ba5-4e1e-99f6-dfbcff8ff68c, clientIf=5
08-29 14:21:28.414  3985  4137 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 14:21:28.415  4322  4333 D BtGatt.GattService: start scan with filters
,08-29 14:21:28.420  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 14:21:28.420  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:21:28.420  4322  4343 D BtGatt.ScanManager: handling starting scan
08-29 14:21:28.420  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:21:28.420  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:21:28.422  4322  4343 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f456acb
,08-29 14:21:28.426  4322  4338 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 14:21:28.426  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:28.427  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:21:28.427  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 14:21:28.427  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:21:28.428  4322  4343 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 14:21:28.430  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:21:28.434  3985  4034 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 14:21:28.435  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:28.435  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 14:21:28.435  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:28.435  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:21:28.435  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 14:21:28.435  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:21:28.435  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:28.435  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 14:21:28.436  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:21:28.436  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 14:21:28.437  3985  4034 D BluetoothAdapter: STATE_ON
08-29 14:21:28.438  4322  4338 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 14:21:28.438  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:28.439  4322  4343 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 14:21:28.438  4322  4333 D BtGatt.GattService: stopScan() - queue size =1
08-29 14:21:28.439  4322  4343 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 14:21:28.440  4322  4360 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 14:21:28.441  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 14:21:28.441  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:21:28.441  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:21:28.441  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 14:21:28.441  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 14:21:28.442  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:28.443  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 14:21:28.443  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:21:28.443  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 14:21:28.443  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:28.447  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 14:21:28.447  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 14:21:28.448  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:21:28.451  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:21:28.451  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:28.451  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:21:28.452  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:28.452  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.452  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:28.452  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:21:28.452  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7032d6 removed from the list
08-29 14:21:28.453  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:28.453  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c70957 removed from the list
,08-29 14:21:28.453  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:21:28.453  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:28.454  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.454  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:28.455  4322  4338 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 14:21:28.455  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:28.455  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:21:28.455  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:28.456  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:28.456  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c70957 not in the list
08-29 14:21:28.456  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.456  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:28.458  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:28.458  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:28.458  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:28.458  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@714a662 removed from the list
08-29 14:21:28.458  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:28.459  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:28.459  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:28.459  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:28.459  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52b412d removed from the list
,08-29 14:21:28.461  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:28.461  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9ac6ae added. We now have 2 listener(s)
08-29 14:21:28.463  4322  4338 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 14:21:28.463  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:28.466  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:21:28.466  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 14:21:28.466  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:28.466  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:28.467  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@603cc4f added. We now have 9 listener(s)
08-29 14:21:28.467  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:28.468  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:28.472  4322  4338 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 14:21:28.472  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.472  4322  4343 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:21:28.473  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:28.478  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:28.478  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:28.478  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:28.478  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:28.478  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:28.478  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:28.478  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:28.478  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:28.480  4322  4338 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 14:21:28.480  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.480  4322  4343 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:21:28.480  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:28.480  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:28.481  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:21:28.481  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5068e5 added. We now have 3 listener(s)
08-29 14:21:28.484  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:28.485  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 14:21:28.486  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:28.486  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:28.486  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:28.487  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:28.487  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4509fba added. We now have 10 listener(s)
08-29 14:21:28.487  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:28.488  4322  4338 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 14:21:28.488  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:28.488  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.489  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:28.489  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-29 14:21:28.489  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 14:21:28.489  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:28.489  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:21:28.493  3985  4034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 14:21:28.493  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:21:28.498  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:21:28.498  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 14:21:28.498  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:21:28.502  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:21:28.502  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:21:28.502  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 14:21:28.503  3985  4034 D BluetoothAdapter: STATE_ON
,08-29 14:21:28.505  4322  4332 D BtGatt.GattService: registerClient() - UUID=66b16edd-43c5-492b-b604-94fa11d8563b
,08-29 14:21:28.505  4322  4338 D BtGatt.GattService: onClientRegistered() - UUID=66b16edd-43c5-492b-b604-94fa11d8563b, clientIf=5
,08-29 14:21:28.506  3985  4137 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 14:21:28.506  4322  4333 D BtGatt.GattService: start scan with filters
,08-29 14:21:28.509  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 14:21:28.509  4322  4343 D BtGatt.ScanManager: handling starting scan
08-29 14:21:28.509  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:21:28.509  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:21:28.509  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:21:28.512  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:21:28.513  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 14:21:28.513  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:21:28.515  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:21:28.517  4322  4338 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 14:21:28.517  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.517  4322  4343 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 14:21:28.519  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 14:21:28.519  3985  4034 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 14:21:28.520  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:28.520  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:28.520  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:21:28.520  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:28.520  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.520  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 14:21:28.520  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:21:28.521  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9ac6ae removed from the list
,08-29 14:21:28.521  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:28.521  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@603cc4f removed from the list
,08-29 14:21:28.521  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:21:28.521  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:28.522  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.522  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 14:21:28.522  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.522  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:28.523  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:21:28.523  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:28.523  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:28.523  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@603cc4f not in the list
,08-29 14:21:28.524  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 14:21:28.524  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 14:21:28.524  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 14:21:28.524  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:21:28.524  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 14:21:28.525  4322  4338 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 14:21:28.525  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:28.526  4322  4343 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:21:28.526  4322  4343 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 14:21:28.526  3985  4034 D BluetoothAdapter: STATE_ON
,08-29 14:21:28.527  4322  4360 D BtGatt.GattService: stopScan() - queue size =1
08-29 14:21:28.528  4322  4352 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 14:21:28.528  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:28.528  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 14:21:28.529  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:21:28.529  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 14:21:28.529  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:21:28.530  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:28.530  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:21:28.530  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:21:28.530  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:28.531  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:28.533  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:28.533  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:28.533  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:28.533  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:28.533  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4509fba removed from the list
08-29 14:21:28.533  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:28.533  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:28.533  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.533  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:28.534  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:28.534  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:28.534  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5068e5 removed from the list
08-29 14:21:28.535  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:28.535  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@958fd86 added. We now have 2 listener(s)
,08-29 14:21:28.538  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:21:28.538  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:28.538  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:28.538  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:28.538  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c6f647 added. We now have 9 listener(s)
,08-29 14:21:28.539  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:28.539  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:21:28.540  4322  4338 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 14:21:28.540  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.542  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:28.547  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:28.547  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:28.547  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:28.547  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:28.547  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:28.547  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:28.547  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:28.547  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:28.548  4322  4338 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 14:21:28.548  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:28.550  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:28.550  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:28.552  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:28.552  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78bcf9d added. We now have 3 listener(s)
,08-29 14:21:28.553  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:28.554  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 14:21:28.554  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:28.554  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:28.554  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:28.555  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@376c12 added. We now have 10 listener(s)
08-29 14:21:28.555  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:28.555  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:28.555  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:28.555  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:28.555  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 14:21:28.555  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:28.555  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:21:28.556  4322  4338 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 14:21:28.557  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.557  4322  4343 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:21:28.559  3985  4034 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 14:21:28.559  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:21:28.563  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-29 14:21:28.564  4322  4338 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 14:21:28.564  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.564  4322  4343 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 14:21:28.565  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 14:21:28.565  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 14:21:28.568  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 14:21:28.568  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:21:28.569  3985  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 14:21:28.570  3985  4034 D BluetoothAdapter: STATE_ON
08-29 14:21:28.570  4322  4338 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 14:21:28.570  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.572  4322  4333 D BtGatt.GattService: registerClient() - UUID=7fe5e646-aec8-4d2f-bd14-6d9f16c57ac0
08-29 14:21:28.573  4322  4338 D BtGatt.GattService: onClientRegistered() - UUID=7fe5e646-aec8-4d2f-bd14-6d9f16c57ac0, clientIf=5
08-29 14:21:28.573  3985  3996 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 14:21:28.573  4322  4332 D BtGatt.GattService: start scan with filters
,08-29 14:21:28.576  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 14:21:28.576  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:21:28.576  4322  4343 D BtGatt.ScanManager: handling starting scan
,08-29 14:21:28.576  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 14:21:28.576  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:21:28.579  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:21:28.580  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 14:21:28.580  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:21:28.582  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:21:28.582  4322  4338 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 14:21:28.583  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.583  4322  4343 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 14:21:28.589  4322  4338 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 14:21:28.589  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:28.589  4322  4343 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 14:21:28.589  4322  4343 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 14:21:28.589  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:28.590  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:28.590  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:28.590  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:28.590  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:28.590  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 14:21:28.590  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:28.590  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@958fd86 removed from the list,
,08-29 14:21:28.590  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:28.591  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c6f647 removed from the list
08-29 14:21:28.591  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:28.591  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:28.592  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:28.592  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 14:21:28.592  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.592  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:28.593  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:21:28.593  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:28.593  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:28.593  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c6f647 not in the list
,08-29 14:21:28.593  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 14:21:28.593  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:28.593  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 14:21:28.594  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 14:21:28.594  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 14:21:28.594  3985  4034 D BluetoothAdapter: STATE_ON
,08-29 14:21:28.595  4322  4332 D BtGatt.GattService: stopScan() - queue size =1
08-29 14:21:28.595  4322  4360 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 14:21:28.596  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 14:21:28.596  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:21:28.596  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:21:28.596  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:21:28.596  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:21:28.597  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:21:28.597  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:21:28.597  3985  4034 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 14:21:28.597  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:28.597  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:28.599  4322  4338 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 14:21:28.599  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.602  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:28.602  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:28.602  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:28.602  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@376c12 removed from the list
,08-29 14:21:28.602  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:28.602  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.603  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:28.603  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:28.603  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78bcf9d removed from the list,
,08-29 14:21:28.604  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:28.604  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1c375e added. We now have 2 listener(s)
,08-29 14:21:28.604  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:28.604  3985  3985 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 14:21:28.605  3985  3985 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:21:28.605  4322  4338 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 14:21:28.605  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.609  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:21:28.609  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 14:21:28.610  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:28.610  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:28.610  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e96673f added. We now have 9 listener(s)
08-29 14:21:28.610  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:28.611  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:28.613  4322  4338 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 14:21:28.614  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:28.615  4322  4343 D BtGatt.ScanManager: stopping BLe Batch,
,08-29 14:21:28.618  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:28.621  4322  4338 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 14:21:28.621  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:21:28.621  4322  4343 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:21:28.624  3985  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:28.624  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:28.624  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:28.624  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:28.624  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:28.624  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:21:28.624  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:21:28.624  3985  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:21:28.627  3985  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:21:28.627  4322  4338 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 14:21:28.627  4322  4338 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:21:28.627  3985  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:28.628  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:21:28.628  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d865555 added. We now have 3 listener(s)
,08-29 14:21:28.630  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 14:21:28.630  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:28.630  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:28.630  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:28.630  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:28.630  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f06b6a added. We now have 10 listener(s)
08-29 14:21:28.630  3985  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:28.631  3985  4034 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:28.631  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:28.631  3985  4034 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:21:28.631  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:28.631  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.631  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:28.631  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:21:28.631  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1c375e removed from the list
08-29 14:21:28.631  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:28.631  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e96673f removed from the list
08-29 14:21:28.634  3985  3985 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:28.634  3985  4034 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:28.634  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:28.635  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:28.635  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:28.636  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 14:21:28.636  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:28.636  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:28.637  3985  4034 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e96673f not in the list
08-29 14:21:28.637  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:28.637  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:28.638  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:28.638  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:28.638  3985  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:28.638  3985  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f06b6a removed from the list
08-29 14:21:28.638  3985  4034 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:28.638  3985  4034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:28.638  3985  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:28.638  3985  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:21:28.638  3985  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d865555 removed from the list
08-29 14:21:28.639  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 14:21:28.639  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 14:21:28.639  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 14:21:28.639  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-29 14:21:28.640  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 14:21:28.640  3985  4034 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:28.645  3985  4402 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 475, name: My test thread name)
,08-29 14:21:28.645  3985  4402 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 475, thread name: My test thread name)
08-29 14:21:28.645  3985  4402 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 475, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 14:21:28.647  3985  4403 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 477, name: My test thread name)
,08-29 14:21:28.647  3985  4403 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 477, thread name: My test thread name)
08-29 14:21:28.647  3985  4403 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 477, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 14:21:28.649  3985  4034 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 14:21:28.649  3985  4034 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 14:21:28.649  3985  4034 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 14:21:28.649  3985  4034 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 14:21:28.649  3985  4034 D com.test.thalitest.ThaliTestRunner: Total duration: 22815 ms
,08-29 14:21:28.650  3985  4034 I jxcore-log: *Native tests were executed*
08-29 14:21:28.650  3985  4034 I jxcore-log: 
,08-29 14:21:28.651  3985  4034 I jxcore-log: Total number of executed tests:  80
08-29 14:21:28.651  3985  4034 I jxcore-log: 
,08-29 14:21:28.651  3985  4034 I jxcore-log: Number of passed tests:  80
08-29 14:21:28.651  3985  4034 I jxcore-log: 
08-29 14:21:28.651  3985  4034 I jxcore-log: Number of failed tests:  0
08-29 14:21:28.651  3985  4034 I jxcore-log: 
08-29 14:21:28.651  3985  4034 I jxcore-log: Number of ignored tests:  0
08-29 14:21:28.651  3985  4034 I jxcore-log: 
08-29 14:21:28.652  3985  4034 I jxcore-log: Total duration:  22815
08-29 14:21:28.652  3985  4034 I jxcore-log: 
,08-29 14:21:28.652  3985  4034 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 14:21:28.652  3985  4034 I jxcore-log: 
,08-29 14:21:28.655  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.655  3985  4034 I jxcore-log: 
,08-29 14:21:28.658  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.658  3985  4034 I jxcore-log: 
,08-29 14:21:28.659  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.659  3985  4034 I jxcore-log: 
08-29 14:21:28.660  3985  3985 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 14:21:28.660  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.660  3985  4034 I jxcore-log: 
08-29 14:21:28.661  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.661  3985  4034 I jxcore-log: 
08-29 14:21:28.662  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.662  3985  4034 I jxcore-log: 
08-29 14:21:28.665  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 14:21:28.665  3985  4034 I jxcore-log: 
,08-29 14:21:28.666  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.666  3985  4034 I jxcore-log: 
08-29 14:21:28.667  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 14:21:28.667  3985  4034 I jxcore-log: 
,08-29 14:21:28.668  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.668  3985  4034 I jxcore-log: 
,08-29 14:21:28.669  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 14:21:28.669  3985  4034 I jxcore-log: 
,08-29 14:21:28.670  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 14:21:28.670  3985  4034 I jxcore-log: 
08-29 14:21:28.670  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 14:21:28.670  3985  4034 I jxcore-log: 
,08-29 14:21:28.671  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.671  3985  4034 I jxcore-log: 
,08-29 14:21:28.672  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.672  3985  4034 I jxcore-log: 
,08-29 14:21:28.672  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.672  3985  4034 I jxcore-log: 
,08-29 14:21:28.673  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.673  3985  4034 I jxcore-log: 
,08-29 14:21:28.673  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.673  3985  4034 I jxcore-log: 
,08-29 14:21:28.674  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.674  3985  4034 I jxcore-log: 
08-29 14:21:28.675  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.675  3985  4034 I jxcore-log: 
,08-29 14:21:28.675  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.675  3985  4034 I jxcore-log: 
,08-29 14:21:28.676  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.676  3985  4034 I jxcore-log: 
,08-29 14:21:28.677  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:28.677  3985  4034 I jxcore-log: 
,08-29 14:21:28.677  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:28.677  3985  4034 I jxcore-log: 
08-29 14:21:28.678  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:28.678  3985  4034 I jxcore-log: 
,08-29 14:21:28.678  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.678  3985  4034 I jxcore-log: 
,08-29 14:21:28.679  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.679  3985  4034 I jxcore-log: 
,08-29 14:21:28.680  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.680  3985  4034 I jxcore-log: 
,08-29 14:21:28.680  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.680  3985  4034 I jxcore-log: 
,08-29 14:21:28.681  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.681  3985  4034 I jxcore-log: 
08-29 14:21:28.681  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:28.681  3985  4034 I jxcore-log: 
,08-29 14:21:28.949  3985  3985 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 14:21:28.952  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 14:21:28.952  3985  4034 I jxcore-log: 
,08-29 14:21:29.034  3985  3985 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 14:21:29.037  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 14:21:29.037  3985  4034 I jxcore-log: 
,08-29 14:21:29.105  3985  3985 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 14:21:29.108  3985  4034 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 14:21:29.108  3985  4034 I jxcore-log: 
,08-29 14:21:29.256  4404  4404 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 14:21:29.261  4404  4404 D AndroidRuntime: CheckJNI is OFF
,08-29 14:21:29.304  4404  4404 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 14:21:29.351  4404  4404 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 14:21:29.374  4404  4404 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 14:21:29.385   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-29 14:21:29.385   871   884 I ActivityManager: Killing 3985:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 14:21:29.488   871   894 W PackageSettings: Skipping PackageSetting{2de0b0c com.example.hello/10273} due to missing metadata
,08-29 14:21:29.519   871  2029 D GraphicsStats: Buffer count: 2
,08-29 14:21:29.519   871  2047 I WindowState: WIN DEATH: Window{42d1b6f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 14:21:29.520   871  1314 D WifiService: Client connection lost with reason: 4
,08-29 14:21:29.526   871   894 I art     : Starting a blocking GC Explicit
,08-29 14:21:29.556   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-29 14:21:29.556   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 14:21:29.557   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-29 14:21:29.557   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 14:21:29.557   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:29.557   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:29.557   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 14:21:29.557   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 14:21:29.557   871   884 I ActivityManager:   Force finishing activity ActivityRecord{ddb1884 u0 com.test.thalitest/.MainActivity t2}
08-29 14:21:29.567   871  1675 W ActivityManager: Spurious death for ProcessRecord{7de1890 0:com.test.thalitest/u0a0}, curProc for 3985: null
08-29 14:21:29.594   871   894 I art     : Explicit concurrent mark sweep GC freed 13611(953KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 732us total 65.919ms
,08-29 14:21:29.639   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 14:21:29.642  4404  4404 I art     : System.exit called, status: 0
,08-29 14:21:29.642  4404  4404 I AndroidRuntime: VM exiting with result code 0.
,08-29 14:21:29.648   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 14:21:29.663   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 14:21:29.680   871  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 14:21:29.683  4322  4322 D BluetoothMapAppObserver: onReceive,
08-29 14:21:29.683  4322  4322 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 14:21:29.689  1856  2228 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 14:21:29.690  1906  1906 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 14:21:29.694  3843  3843 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 14:21:29.711  1906  4418 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 14:21:29.712   871  1969 I ActivityManager: Start proc 4419:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 14:21:29.720  1906  4418 I Decoder : createOrResetDecoder
,08-29 14:21:29.735  2010  2010 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 14:21:29.762  4419  4419 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 14:21:29.764   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 14:21:29.774  1503  1503 I ConfigService: onCreate
,08-29 14:21:29.779   871  2048 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3985 uid 10000
,08-29 14:21:29.781  1906  1906 I Keyboard.Facilitator: onFinishInput()
,08-29 14:21:29.787  1906  4418 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 14:21:29.793   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 14:21:29.793   871   883 E PackageManager: Failed to write settings, restoring backup
08-29 14:21:29.793   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 14:21:29.793   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 14:21:29.793   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615),
08-29 14:21:29.793   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 14:21:29.793   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
,08-29 14:21:29.793   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:29.793   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:29.793   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 14:21:29.806  2020  2127 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 14:21:29.810   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-29 14:21:29.810   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72),
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	,at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 14:21:29.810   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 14:21:29.810   871   884 E DropBoxManagerService: 	... 13 more
,08-29 14:21:29.820   871  2048 I ActivityManager: Start proc 4433:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-29 14:21:29.820  2020  2127 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 14:21:29.820  2020  2127 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2020
08-29 14:21:29.820  2020  2127 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:21:29.820  2020  2127 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 14:21:29.823   871  1972 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 14:21:29.824   871  4440 E DropBoxManagerService: Can't write: system_app_crash
08-29 14:21:29.824   871  4440 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 14:21:29.824   871  4440 E DropBoxManagerService: 	... 5 more
,08-29 14:21:29.838  2020  2127 I Process : Sending signal. PID: 2020 SIG: 9
,08-29 14:21:29.853  1906  4418 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 14:21:29.854  1906  4418 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-29 14:21:29.854  1906  4418 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 14:21:29.856  1906  4418 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 14:21:29.856  1906  4418 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 14:21:29.865  1906  4418 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-29 14:21:29.865  1906  4418 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-29 14:21:29.866  1906  4418 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-29 14:21:29.866  1906  4418 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-29 14:21:29.866  1906  4418 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-29 14:21:29.921  1906  4418 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-29 14:21:29.921  1906  4418 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-29 14:21:29.921  1906  4418 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 14:21:30.068   871  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-29 14:21:30.101  1856  2737 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 14:21:30.168   282   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
