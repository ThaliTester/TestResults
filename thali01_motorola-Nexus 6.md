#### Test 82914073a7b15c1_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-29 18:39:51.708   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
08-29 18:39:52.800  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 18:39:52.807  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 18:39:52.809  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 18:39:52.842  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 18:39:52.842  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 18:39:52.842  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 18:39:52.842  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 18:39:52.866  3545  3545 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 18:39:52.867  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 18:39:52.868  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-29 18:39:53.590  3814  3814 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 18:39:53.596  3814  3814 D AndroidRuntime: CheckJNI is OFF
08-29 18:39:53.640  3814  3814 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 18:39:53.692  3814  3814 I Radio-JNI: register_android_hardware_Radio DONE
08-29 18:39:53.715  3814  3814 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 18:39:53.724   874  1383 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 18:39:53.778  2060  2415 W SearchService: Abort, client detached.
08-29 18:39:53.781  2060  2060 I HotwordDetector: Closing mic
08-29 18:39:53.782  2060  2349 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@930624
08-29 18:39:53.782  2060  2358 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 18:39:53.796  3814  3814 D AndroidRuntime: Shutting down VM
08-29 18:39:53.812   874  2242 I ActivityManager: Start proc 3825:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 18:39:53.841   376  2360 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 18:39:53.842   376  2360 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 18:39:53.847   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 18:39:53.849  2060  2357 I MicroRecognitionRnrImpl: Detection finished
08-29 18:39:53.849  2060  2353 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 18:39:53.898  3825  3825 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 18:39:53.926  3825  3825 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 18:39:53.934  3825  3825 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9877-9880)
08-29 18:39:53.935  3825  3825 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 18:39:53.950  3825  3825 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {88daae1}
08-29 18:39:53.951  3825  3825 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 18:39:53.951  3825  3825 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 18:39:53.957  3825  3825 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 18:39:53.959  3825  3825 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 18:39:53.979  3825  3825 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 18:39:53.990  3825  3825 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 18:39:53.990  3825  3825 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 18:39:53.990  3825  3825 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 18:39:53.990  3825  3825 I Adreno  : Build Date                       : 10/20/15
08-29 18:39:53.990  3825  3825 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 18:39:53.990  3825  3825 I Adreno  : Local Branch                     : M14
08-29 18:39:53.990  3825  3825 I Adreno  : Remote Branch                    : 
08-29 18:39:53.990  3825  3825 I Adreno  : Remote Branch                    : 
08-29 18:39:53.990  3825  3825 I Adreno  : Reconstruct Branch               : 
,08-29 18:39:54.070   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c69c142:true
,08-29 18:39:54.097  3825  3825 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 18:39:54.112  3825  3825 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 18:39:54.195  3825  3863 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 18:39:54.216  3825  3850 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 18:39:54.278  3825  3863 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 18:39:54.280   874  2099 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120226, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 18:39:54.352   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +554ms
,08-29 18:39:54.355  1878  1878 I Keyboard.Facilitator: onFinishInput()
,08-29 18:39:54.406  3825  3825 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3825
,08-29 18:39:54.537  3825  3825 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 18:39:54.619   874  1966 I ActivityManager: Killing 3245:com.google.android.gm/u0a78 (adj 15): empty #17
,08-29 18:39:54.682   874  1966 I ActivityManager: Killing 3150:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-29 18:39:54.728   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 18:39:54.794  3825  3867 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1687156432
,08-29 18:39:54.801  3825  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 18:39:54.801  3825  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 18:39:54.801  3825  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 18:39:54.801  3825  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 18:39:54.801  3825  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 18:39:54.801  3825  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b85b395 added. We now have 1 listener(s)
,08-29 18:39:54.804  3825  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 18:39:54.806  3825  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 18:39:54.806  3825  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 18:39:54.806  3825  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 18:39:54.809  3825  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2e8c38 added. We now have 1 listener(s)
,08-29 18:39:54.810  3825  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:39:54.819   874  1310 D WifiService: New client listening to asynchronous messages
,08-29 18:39:54.823  3825  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:39:54.823  3825  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 18:39:54.824  3825  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 18:39:54.825  3825  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 18:39:54.825  3825  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 18:39:54.832  3825  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:39:54.832  3825  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 18:39:54.845  3825  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 18:39:54.846  3825  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:39:54.846  3825  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:54.846  3825  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:54.846  3825  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:54.846  3825  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:39:54.846  3825  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:54.846  3825  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:54.846  3825  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:39:54.846  3825  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-29 18:39:54.846  3825  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:39:54.847  3825  3867 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 18:39:54.848  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:54.850  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:54.875  3825  3825 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 18:39:55.715  3825  3875 W jxcore-log: Initializing JXcore engine
08-29 18:39:55.716  3825  3875 W jxcore-log: JXcore engine is ready
,08-29 18:39:55.754  3875  3875 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8791 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 18:39:55.754  3875  3875 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10542]" dev="sockfs" ino=10542 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 18:39:55.754  3875  3875 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 18:39:55.754  3875  3875 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24117]" dev="sockfs" ino=24117 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 18:39:55.773  3825  3875 W jxcore-log: Starting JXcore engine
,08-29 18:39:55.860  3825  3875 W jxcore-log: Platform android
08-29 18:39:55.860  3825  3875 W jxcore-log: 
08-29 18:39:55.860  3825  3875 W jxcore-log: Process ARCH arm
08-29 18:39:55.860  3825  3875 W jxcore-log: 
,08-29 18:39:56.117  3825  3875 I jxcore-log: JXcore Cordova bridge is ready!
08-29 18:39:56.117  3825  3875 I jxcore-log: 
08-29 18:39:56.118  3825  3875 W jxcore-log: JXcore engine is started
,08-29 18:39:56.126  3825  3867 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 18:39:56.130  3825  3825 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 18:39:58.100   874  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 18:39:59.730   874  2099 D NetlinkSocketObserver: NeighborEvent{elapsedMs=125676, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 18:40:03.359  3612  3881 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 18:40:03.393  3612  3882 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 18:40:03.410  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 18:40:03.415  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 18:40:03.452  1500  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 18:40:03.452  1500  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 18:40:03.453  1500  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 18:40:03.453  1500  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 18:40:03.500  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 18:40:03.506  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 18:40:03.555  1500  2087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 18:40:03.555  1500  2087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 18:40:03.556  1500  2087 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 18:40:03.556  1500  2087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 18:40:03.594  3612  3882 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 18:40:03.597  3612  3881 E BooksSync: Soft error
08-29 18:40:03.597  3612  3881 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 18:40:03.597  3612  3881 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 18:40:03.598  3612  3881 E BooksSync: Sync error
08-29 18:40:03.598  3612  3881 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 18:40:03.598  3612  3881 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 18:40:03.598  3612  3881 I BooksSync: Finished books sync
,08-29 18:40:03.607   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129020, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,08-29 18:40:06.354  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 18:40:06.354  3825  3875 I jxcore-log: 
08-29 18:40:06.356  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 18:40:06.356  3825  3875 I jxcore-log: 
,08-29 18:40:06.365  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:06.365  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:06.365  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:06.365  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:06.365  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:06.365  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:06.365  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:06.365  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:06.370  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:06.378  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 18:40:06.378  3825  3875 I jxcore-log: 
,08-29 18:40:06.385  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 18:40:06.385  3825  3875 I jxcore-log: 
,08-29 18:40:06.911  3825  3875 D executeNativeTests: Running unit tests
,08-29 18:40:06.970  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 18:40:06.970  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 added. We now have 2 listener(s)
08-29 18:40:06.971  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 18:40:06.971  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:06.971  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:06.972  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:06.972  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa added. We now have 2 listener(s)
,08-29 18:40:06.972  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:06.973  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 18:40:06.985  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:06.998  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:06.998  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:06.998  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:06.998  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:06.998  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:06.998  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:06.998  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:06.998  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:07.003  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:07.003  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:40:07.007  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 18:40:07.009  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 18:40:07.009  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 18:40:07.011  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.012  3825  3875 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 18:40:07.012  3825  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 18:40:07.012  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 18:40:07.013  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 18:40:07.013  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:40:07.014  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:07.015  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:40:07.015  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:40:07.015  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:07.016  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.016  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:07.016  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:07.016  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 removed from the list
,08-29 18:40:07.016  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.016  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa removed from the list
08-29 18:40:07.019  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.019  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 18:40:07.019  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.023  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.023  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.026  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.026  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 18:40:07.027  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.027  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
,08-29 18:40:07.031  3825  3875 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 18:40:07.035  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:07.036  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.036  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:40:07.036  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.037  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:07.037  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.038  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.039  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:07.039  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.039  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 18:40:07.039  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.040  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.040  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.040  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.042  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:07.042  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.043  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:07.043  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
,08-29 18:40:07.056  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 18:40:07.056  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 18:40:07.056  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 18:40:07.056  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-29 18:40:07.056  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 18:40:07.056  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 18:40:07.056  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 18:40:07.056  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 18:40:07.056  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110],
08-29 18:40:07.057  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 18:40:07.058  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 18:40:07.058  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 18:40:07.058  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 18:40:07.058  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 18:40:07.058  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 18:40:07.058  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 18:40:07.058  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-29 18:40:07.058  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.058  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.058  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.058  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:07.058  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.058  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.058  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.058  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.059  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
,08-29 18:40:07.059  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 18:40:07.059  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.059  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.059  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.059  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.060  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.060  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 18:40:07.060  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.060  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.061  3825  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 18:40:07.063  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:07.069  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:07.069  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.069  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:07.069  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:07.069  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:07.069  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:07.069  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:07.069  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:07.072  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:07.072  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:07.072  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 18:40:07.072  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:07.072  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:07.072  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:07.072  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:40:07.076  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.078  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.078  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 18:40:07.078  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 18:40:07.091  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:40:07.094  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 18:40:07.095  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 18:40:07.099  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 18:40:07.104  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 18:40:07.105  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 18:40:07.105  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 18:40:07.106  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 18:40:07.108  3825  3875 D BluetoothAdapter: STATE_ON
,08-29 18:40:07.116  2713  2908 D BtGatt.GattService: registerClient() - UUID=ce473634-d101-4848-881d-4987d0647682
,08-29 18:40:07.118  2713  2767 D BtGatt.GattService: onClientRegistered() - UUID=ce473634-d101-4848-881d-4987d0647682, clientIf=5
,08-29 18:40:07.119  3825  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 18:40:07.120  2713  2726 D BtGatt.GattService: start scan with filters
,08-29 18:40:07.126  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 18:40:07.126  2713  2771 D BtGatt.ScanManager: handling starting scan
,08-29 18:40:07.127  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 18:40:07.127  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 18:40:07.127  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:40:07.128  2713  2771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:07.130  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:07.130  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 18:40:07.131  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:07.132  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:40:07.135  3825  3875 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 18:40:07.137  2713  2767 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 18:40:07.137  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.138  2713  2771 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 18:40:07.139  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:07.140  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 18:40:07.140  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:40:07.140  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 18:40:07.140  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:07.140  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 18:40:07.141  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 18:40:07.141  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 18:40:07.141  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 18:40:07.141  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:40:07.142  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 18:40:07.142  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 18:40:07.144  3825  3875 D BluetoothAdapter: STATE_ON
,08-29 18:40:07.145  2713  2767 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 18:40:07.145  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.146  2713  2771 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 18:40:07.146  2713  2771 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 18:40:07.146  2713  2908 D BtGatt.GattService: stopScan() - queue size =1
,08-29 18:40:07.147  2713  2726 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 18:40:07.148  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 18:40:07.148  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:40:07.148  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 18:40:07.149  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 18:40:07.149  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 18:40:07.151  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:07.152  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 18:40:07.153  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:40:07.154  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 18:40:07.155  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:07.157  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:07.157  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:07.157  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.157  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:07.157  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
,08-29 18:40:07.157  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:07.157  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.157  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.158  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.157  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:07.158  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.158  3825  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 18:40:07.160  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:07.160  2713  2767 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 18:40:07.160  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:07.164  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:07.164  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.164  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:07.164  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:07.164  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:07.164  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:07.164  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:07.164  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:07.166  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:07.166  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:07.166  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:07.166  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:07.166  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:07.166  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:07.167  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 18:40:07.168  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.169  2713  2767 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 18:40:07.169  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.170  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 18:40:07.170  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 18:40:07.170  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.174  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:40:07.175  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 18:40:07.175  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 18:40:07.176  2713  2767 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 18:40:07.176  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:07.176  2713  2771 D BtGatt.ScanManager: stopping BLe Batch
,08-29 18:40:07.179  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 18:40:07.179  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 18:40:07.179  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 18:40:07.179  3825  3875 D BluetoothAdapter: STATE_ON
,08-29 18:40:07.182  2713  2726 D BtGatt.GattService: registerClient() - UUID=293d9abc-a68c-4cd6-ae6f-681d436e9128
,08-29 18:40:07.183  2713  2767 D BtGatt.GattService: onClientRegistered() - UUID=293d9abc-a68c-4cd6-ae6f-681d436e9128, clientIf=5
08-29 18:40:07.183  2713  2767 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 18:40:07.183  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:07.183  3825  3836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 18:40:07.184  2713  2771 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 18:40:07.184  2713  2727 D BtGatt.GattService: start scan with filters
,08-29 18:40:07.187  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 18:40:07.187  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 18:40:07.187  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 18:40:07.187  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:40:07.189  2713  2767 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 18:40:07.189  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:07.191  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:07.191  2713  2771 D BtGatt.ScanManager: handling starting scan
,08-29 18:40:07.191  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 18:40:07.191  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 18:40:07.193  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:40:07.195  3825  3875 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 18:40:07.199  2713  2767 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 18:40:07.199  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.199  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:07.199  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 18:40:07.199  2713  2771 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 18:40:07.199  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.199  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 18:40:07.200  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.200  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 18:40:07.200  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 18:40:07.201  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 18:40:07.201  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:40:07.201  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:40:07.201  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 18:40:07.201  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 18:40:07.202  3825  3875 D BluetoothAdapter: STATE_ON
08-29 18:40:07.202  2713  2726 D BtGatt.GattService: stopScan() - queue size =1
08-29 18:40:07.203  2713  2908 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 18:40:07.203  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:07.203  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:40:07.204  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 18:40:07.204  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:40:07.204  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 18:40:07.205  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:07.205  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 18:40:07.205  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:40:07.205  2713  2767 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 18:40:07.205  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.205  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:07.206  2713  2771 D BtGatt.ScanManager: Starting BLE batch scan
08-29 18:40:07.206  2713  2771 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 18:40:07.206  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:07.207  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:07.207  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:07.208  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:07.208  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.208  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.208  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:07.208  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.208  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.208  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.208  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.208  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.209  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.209  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.210  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.210  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.210  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.210  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.211  3825  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 18:40:07.213  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:07.219  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:07.219  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.219  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:07.219  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:07.219  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:07.219  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:07.219  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:07.219  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:07.219  2713  2767 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 18:40:07.219  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:07.224  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:07.224  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:07.224  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 18:40:07.225  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:07.225  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 18:40:07.225  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:07.225  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:40:07.226  2713  2767 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 18:40:07.226  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.228  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.229  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 18:40:07.230  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 18:40:07.230  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.235  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:40:07.235  2713  2767 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 18:40:07.235  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 18:40:07.235  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.235  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 18:40:07.236  2713  2771 D BtGatt.ScanManager: stopping BLe Batch
,08-29 18:40:07.241  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 18:40:07.241  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 18:40:07.241  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 18:40:07.242  3825  3875 D BluetoothAdapter: STATE_ON
,08-29 18:40:07.243  2713  2767 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 18:40:07.243  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:07.244  2713  2771 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 18:40:07.245  2713  2727 D BtGatt.GattService: registerClient() - UUID=90cedbd3-232c-4974-a339-2108dfcd1206
,08-29 18:40:07.246  2713  2767 D BtGatt.GattService: onClientRegistered() - UUID=90cedbd3-232c-4974-a339-2108dfcd1206, clientIf=5
,08-29 18:40:07.247  3825  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 18:40:07.247  2713  2901 D BtGatt.GattService: start scan with filters
,08-29 18:40:07.250  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 18:40:07.250  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 18:40:07.250  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 18:40:07.250  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:40:07.250  2713  2767 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 18:40:07.252  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:07.254  2713  2771 D BtGatt.ScanManager: handling starting scan
,08-29 18:40:07.259  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:07.259  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 18:40:07.260  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:07.266  2713  2767 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 18:40:07.266  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.266  2713  2771 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 18:40:07.267  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:40:07.272  3825  3875 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 18:40:07.272  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.272  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 18:40:07.272  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.272  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 18:40:07.272  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.273  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 18:40:07.273  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 18:40:07.273  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 18:40:07.274  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 18:40:07.274  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:40:07.274  2713  2767 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 18:40:07.275  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:07.275  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 18:40:07.275  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 18:40:07.275  2713  2771 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 18:40:07.275  2713  2771 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 18:40:07.276  3825  3875 D BluetoothAdapter: STATE_ON
,08-29 18:40:07.278  2713  2901 D BtGatt.GattService: stopScan() - queue size =1
,08-29 18:40:07.279  2713  2908 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 18:40:07.280  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 18:40:07.280  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:40:07.280  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 18:40:07.280  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 18:40:07.281  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 18:40:07.283  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:40:07.283  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 18:40:07.284  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 18:40:07.284  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:07.285  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:07.287  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:40:07.287  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:40:07.287  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:40:07.288  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:07.288  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 18:40:07.289  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:40:07.289  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:40:07.289  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:07.290  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.290  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:07.290  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.290  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:07.290  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.291  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 18:40:07.291  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.292  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.292  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.292  2713  2767 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 18:40:07.292  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.294  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:07.294  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.294  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:07.294  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.295  3825  3875 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 18:40:07.296  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:07.302  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:40:07.302  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:40:07.302  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:07.302  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:07.302  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.303  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
,08-29 18:40:07.303  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:07.303  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
,08-29 18:40:07.303  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.303  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:07.303  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.303  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.304  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.305  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:07.305  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 18:40:07.305  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.305  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list,
08-29 18:40:07.306  2713  2767 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 18:40:07.306  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:07.307  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 18:40:07.307  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 18:40:07.308  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:40:07.308  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:40:07.308  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.308  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:07.308  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.309  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
,08-29 18:40:07.309  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.309  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.309  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.309  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.309  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.309  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.309  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.311  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.311  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.311  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.311  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
,08-29 18:40:07.312  3825  3875 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 18:40:07.313  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.313  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.313  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.314  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.314  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.314  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.314  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.314  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:07.314  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.314  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.314  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:07.314  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.314  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:07.314  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.315  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.315  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.315  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.316  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
,08-29 18:40:07.316  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 18:40:07.316  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.316  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.317  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.317  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.317  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:07.317  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.317  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.317  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.317  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
,08-29 18:40:07.317  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.318  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.318  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.318  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:07.318  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:07.319  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:07.319  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 18:40:07.319  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:07.319  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.319  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 18:40:07.321  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 18:40:07.321  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 18:40:07.321  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:40:07.321  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 18:40:07.322  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 18:40:07.322  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.322  2713  2767 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 18:40:07.322  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.322  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.322  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:40:07.322  2713  2771 D BtGatt.ScanManager: stopping BLe Batch
08-29 18:40:07.322  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.322  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.322  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.322  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.322  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.322  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.322  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.323  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.323  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.323  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.323  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.326  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.326  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.326  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.326  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.327  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:07.328  3825  3875 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 18:40:07.328  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 18:40:07.330  2713  2767 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 18:40:07.330  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.330  2713  2771 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 18:40:07.333  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:07.334  3825  3875 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 18:40:07.334  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 18:40:07.335  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 18:40:07.335  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 18:40:07.335  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 18:40:07.335  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 18:40:07.335  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 18:40:07.335  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 18:40:07.335  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 18:40:07.335  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 18:40:07.336  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 18:40:07.336  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 18:40:07.336  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 18:40:07.336  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 18:40:07.336  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 18:40:07.336  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 18:40:07.336  2713  2767 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 18:40:07.336  2713  2767 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:07.337  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 18:40:07.338  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 18:40:07.339  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 18:40:07.339  3825  3875 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 18:40:07.339  3825  3875 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 18:40:07.339  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:07.340  3825  3875 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 18:40:07.340  3825  3875 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 18:40:07.340  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:07.340  3825  3875 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 18:40:07.340  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 18:40:07.344  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 18:40:07.345  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 18:40:07.345  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 18:40:07.346  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 18:40:07.346  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 18:40:07.346  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 18:40:07.346  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:40:07.346  3825  3875 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 18:40:07.346  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.347  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.347  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.347  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.347  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.347  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.347  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 18:40:07.351  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.351  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.351  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.351  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.351  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.351  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.351  3825  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-29 18:40:07.351  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.351  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.352  3825  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-29 18:40:07.352  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.352  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.352  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.352  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.353  3825  3875 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 18:40:07.353  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.353  3825  3886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:07.353  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.354  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.354  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.354  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.354  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.354  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.354  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.354  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.354  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.354  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.354  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.354  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.354  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.355  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.355  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.355  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.355  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.356  3825  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 18:40:07.357  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.358  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.358  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.358  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.358  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.358  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.358  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.358  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.358  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.358  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.358  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.358  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.358  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.359  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.360  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.360  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.360  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.360  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.361  3825  3875 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 18:40:07.361  3825  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 18:40:07.361  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 18:40:07.361  3825  3875 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 18:40:07.361  3825  3875 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 18:40:07.361  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 18:40:07.362  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 18:40:07.362  3825  3875 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 18:40:07.362  3825  3875 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 18:40:07.362  3825  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 18:40:07.362  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 18:40:07.362  3825  3875 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 18:40:07.362  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.362  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.362  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.362  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.362  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.363  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.363  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.363  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.363  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.363  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.363  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.363  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.363  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.363  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.364  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.364  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.364  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.364  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.365  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.365  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.366  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.366  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.366  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.366  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.366  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.366  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.366  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.367  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.367  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.367  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.367  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.367  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.368  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.368  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.368  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.368  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.368  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.369  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.369  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.369  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.369  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.369  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.369  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.369  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.369  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.370  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.370  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.371  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.371  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.371  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.371  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.373  3825  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 18:40:07.373  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:07.374  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 18:40:07.375  3825  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 18:40:07.375  3825  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 18:40:07.375  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 18:40:07.375  3825  3825 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 18:40:07.375  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 18:40:07.376  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.376  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 18:40:07.376  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 18:40:07.376  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 18:40:07.376  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.376  3825  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 18:40:07.376  3825  3825 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 18:40:07.376  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.376  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.376  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 18:40:07.377  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:40:07.377  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:40:07.377  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.377  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.377  3825  3888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:07.378  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:07.378  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.378  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:07.378  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.378  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:07.378  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.378  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.378  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:07.378  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.378  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.378  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.379  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.379  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.379  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.379  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.379  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.379  3825  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 18:40:07.379  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.379  3825  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 18:40:07.379  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.379  3825  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 18:40:07.379  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.379  3825  3825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 18:40:07.380  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.380  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.380  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.381  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.382  3825  3875 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 18:40:07.382  3825  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 18:40:07.382  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 18:40:07.382  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:40:07.382  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.382  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.382  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.382  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.382  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.382  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.382  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.383  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.383  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.383  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.383  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.383  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.383  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.383  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.384  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.384  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.384  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.384  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.387  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.388  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.388  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.388  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.388  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.388  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.388  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.388  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.388  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.388  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.388  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.388  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.388  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.388  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.389  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.389  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.389  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.389  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.390  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:07.390  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:07.390  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:07.390  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:07.390  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.390  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.391  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dcfb25 not in the list
08-29 18:40:07.391  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.391  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.391  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:07.391  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.391  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.391  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:07.391  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:07.392  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:07.392  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:07.392  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:07.392  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a64fa not in the list
08-29 18:40:07.393  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 18:40:07.393  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 18:40:07.393  3825  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 18:40:07.393  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 18:40:07.393  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 18:40:07.393  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 18:40:07.395  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 18:40:07.395  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 18:40:07.396  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incomin,g connection thread with ID 1
08-29 18:40:07.396  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 18:40:07.396  3825  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 18:40:07.396  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 18:40:07.396  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 18:40:07.396  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 18:40:07.397  3825  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 18:40:07.397  3825  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 18:40:07.397  3825  3875 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 18:40:07.397  3825  3875 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 18:40:07.397  3825  3875 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 18:40:07.397  3825  3875 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 18:40:07.398  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:07.398  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a531b4c added. We now have 2 listener(s)
08-29 18:40:07.398  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:07.401  3825  3875 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 18:40:07.401   874  1383 D WifiService: setWifiEnabled: true pid=3825, uid=10000
08-29 18:40:07.401   874  1383 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 18:40:07.402  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:07.402  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7bf795 added. We now have 3 listener(s)
08-29 18:40:07.402  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:07.408  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:07.408  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7600aa added. We now have 4 listener(s)
08-29 18:40:07.408  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:07.410  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:07.410  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fee449b added. We now have 5 listener(s)
08-29 18:40:07.410  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:07.412   874  2002 D WifiService: setWifiEnabled: false pid=3825, uid=10000
08-29 18:40:07.412   874  2002 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 18:40:07.417  2713  2761 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 18:40:07.417  2713  2761 D BluetoothAdapterProperties: Setting state to 13
08-29 18:40:07.417  2713  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 18:40:07.417  2713  2761 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 18:40:07.417  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:07.418  2713  2761 I BluetoothAdapterState: Entering PendingCommandState
,08-29 18:40:07.420  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:07.420  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:07.420  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.420  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:07.420  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:07.420  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:07.420  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:07.420  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:07.420  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:07.421  2713  2713 D BluetoothMapService: onReceive
08-29 18:40:07.421  2713  2713 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:07.421  2713  2713 D BluetoothMapService: STATE_TURNING_OFF
08-29 18:40:07.421  2713  2713 D BluetoothMapService: MAP Service closeService in
08-29 18:40:07.421  2713  2713 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 18:40:07.421  2713  2713 D ObexServerSockets0: shutdown(block = true)
,08-29 18:40:07.422  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 18:40:07.422  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 18:40:07.422  2713  2918 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 18:40:07.422  2713  2897 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 18:40:07.422  2713  2920 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 18:40:07.423  2713  2713 I BtOppRfcommListener: stopping Accept Thread
08-29 18:40:07.423  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:07.423  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:07.423  2713  3451 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:07.423  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:40:07.423  2713  3451 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 18:40:07.428  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 18:40:07.430   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 18:40:07.430   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 18:40:07.430   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 18:40:07.430   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:40:07.430  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.433  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.436  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:07.437  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:07.437  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.437  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:07.437  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:07.437  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:07.437  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:07.437  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:07.437  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:07.437  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:07.437  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:07.439   874  2102 D DhcpClient: Clearing IP address
,08-29 18:40:07.439   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:07.440  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.442   372   872 D CommandListener: Setting iface cfg
,08-29 18:40:07.444   874   887 I ActivityManager: Start proc 3891:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 18:40:07.445  2713  2767 D BluetoothAdapterProperties: Scan Mode:20
,08-29 18:40:07.445  1500  2556 V NativeCrypto: Read error: ssl=0x9a7fc800: I/O error during system call, Connection timed out
08-29 18:40:07.445  2713  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 18:40:07.448  1500  2556 V NativeCrypto: SSL shutdown failed: ssl=0x9a7fc800: I/O error during system call, Broken pipe
,08-29 18:40:07.449  2713  2713 D HeadsetService: Received stop request...Stopping profile...
08-29 18:40:07.450  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:07.451  1982  2175 D BluetoothHeadset: Proxy object disconnected
,08-29 18:40:07.451   874   874 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:07.451   874   874 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:07.451  1363  1384 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:07.452  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-29 18:40:07.452  2713  2713 D A2dpService: Received stop request...Stopping profile...
,08-29 18:40:07.452   874   874 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:07.452  2713  2903 D A2dpStateMachine: Exit Disconnected: -1
08-29 18:40:07.453   874   885 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-29 18:40:07.453   874  2093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-29 18:40:07.455  1363  1363 D BluetoothA2dp: Proxy object disconnected
,08-29 18:40:07.455   874   874 D BluetoothA2dp: Proxy object disconnected
08-29 18:40:07.455  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:07.456  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:07.456  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:07.456  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:07.458   395   395 E Parcel  : Reading a NULL string not supported here.
08-29 18:40:07.458  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:07.458  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:07.458  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.458  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:07.458  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:07.458  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:07.458  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:07.458  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:07.458  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:07.459  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 18:40:07.459  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:07.459  2713  2767 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 18:40:07.459  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:07.459  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 18:40:07.459  2713  2891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 18:40:07.459  2713  2891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 18:40:07.459  2713  2891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 18:40:07.459  2713  2767 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 18:40:07.460   874  2093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-29 18:40:07.460  2713  2713 D HidService: Received stop request...Stopping profile...
08-29 18:40:07.460  2713  2713 D HidService: Stopping Bluetooth HidService
,08-29 18:40:07.460   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 18:40:07.460   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-29 18:40:07.462  2713  2713 D HealthService: Received stop request...Stopping profile...
,08-29 18:40:07.466   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-29 18:40:07.467   874  2104 D DhcpClient: Receive thread stopped
,08-29 18:40:07.468  2713  2713 D PanService: Received stop request...Stopping profile...
,08-29 18:40:07.467   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 18:40:07.468   874  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-29 18:40:07.470  2713  2713 V BluetoothAdapterState: isTurningOff()=true
,08-29 18:40:07.470   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:07.470  2713  2713 V BluetoothAdapterState: isTurningOn()=false
,08-29 18:40:07.470  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 18:40:07.470  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:07.470  2713  2713 D BluetoothMapService: Received stop request...Stopping profile...
08-29 18:40:07.470  2713  2713 D BluetoothMapService: stop()
08-29 18:40:07.471  2713  2713 D BluetoothMapAppObserver: deinitObservers()
08-29 18:40:07.471  1363  1363 D BluetoothInputDevice: Proxy object disconnected
,08-29 18:40:07.471  1363  1363 D HidProfile: Bluetooth service disconnected
08-29 18:40:07.471  2713  2713 D BluetoothMapAppObserver: removeReceiver()
08-29 18:40:07.471  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 18:40:07.471  1363  1363 D PanProfile: Bluetooth service disconnected
08-29 18:40:07.473  1363  1363 D BluetoothMap: Proxy object disconnected
08-29 18:40:07.473  1363  1363 D MapProfile: Bluetooth service disconnected
08-29 18:40:07.474  2713  2767 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 18:40:07.474  2713  2891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 18:40:07.474  2713  2891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 18:40:07.474  2713  2891 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:07.474  2713  2891 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:07.474  2713  2891 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:07.474  2713  2891 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:07.474  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:07.474  2713  2713 V BluetoothAdapterState: isTurningOn()=false
,08-29 18:40:07.474  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:07.474  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:07.474  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 18:40:07.475  2713  2767 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 18:40:07.475  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 18:40:07.476  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:07.476  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:07.476  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:07.476  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:07.476  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 18:40:07.477  2713  2767 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 18:40:07.477  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 18:40:07.477  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:07.477  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:07.477  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:07.477  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:07.478  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...,
08-29 18:40:07.478  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 18:40:07.479  2713  2713 D BluetoothMapService: MAP Service closeService in
08-29 18:40:07.479  2713  2713 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:07.479  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:07.479  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:07.479  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:07.479  2713  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 18:40:07.479  2713  2761 D BluetoothAdapterProperties: Setting state to 15
08-29 18:40:07.479  2713  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-29 18:40:07.479  2713  2713 D BluetoothMapService: cleanup()
08-29 18:40:07.479  2713  2713 D BluetoothMapService: MAP Service closeService in
08-29 18:40:07.480   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:07.481  1363  1684 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 18:40:07.481  1363  3824 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 18:40:07.481  2713  2761 I BluetoothAdapterState: Entering BleOnState
08-29 18:40:07.482  1363  2082 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:07.482  1363  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 18:40:07.483   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:07.483   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:07.483  1982  1993 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-29 18:40:07.483  1363  1384 D BluetoothMap: onBluetoothStateChange: up=false
08-29 18:40:07.484   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 18:40:07.484  1363  1684 D BluetoothPan: onBluetoothStateChange on: false
08-29 18:40:07.484  2713  2761 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 18:40:07.484  2713  2761 D BluetoothAdapterProperties: Setting state to 16
08-29 18:40:07.485  2713  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16,
08-29 18:40:07.485  2713  2761 D BluetoothAdapterProperties: onBleDisable
08-29 18:40:07.489  2713  2761 I BluetoothAdapterState: Entering PendingCommandState
08-29 18:40:07.489  2713  2763 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 18:40:07.489  2713  2767 D BluetoothAdapterProperties: Scan Mode:20
08-29 18:40:07.489  2713  2891 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 18:40:07.490  2713  2891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 18:40:07.490  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:07.490  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:07.490  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.490  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-29 18:40:07.490  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:07.490  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:07.490  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:07.490  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:07.490  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:07.490  3825  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-29 18:40:07.491  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-29 18:40:07.491  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:07.493  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:07.497  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:07.497  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.497  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:07.497  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-29 18:40:07.497  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:07.497  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:07.497  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:07.497  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:07.498  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:07.498  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:07.514   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 18:40:07.528  3891  3891 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 18:40:07.534   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 18:40:07.535   874  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-29 18:40:07.535   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:07.537   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 18:40:07.540   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-29 18:40:07.543  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:07.543  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:07.543  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.543  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:07.543  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:07.543  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:07.543  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:07.543  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:07.543  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:07.543   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 18:40:07.543  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:07.543  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:07.545  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:07.545  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:07.545  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:07.545  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:07.545  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:07.545  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:07.545  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:07.545  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:07.545  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:07.545  3437  3437 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@abf1023 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 18:40:07.546  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:07.546  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:07.547  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:07.548  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:07.554  1907  2305 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:07.558  3891  3891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 18:40:07.565  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:07.578   874  2002 I ActivityManager: Start proc 3912:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 18:40:07.585   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@335a880:true
08-29 18:40:07.591   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-29 18:40:07.593   874  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 18:40:07.593   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 18:40:07.611  3891  3891 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 18:40:07.616  3891  3891 D BluetoothMap: Create BluetoothMap proxy object
,08-29 18:40:07.621  3912  3912 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 18:40:07.623  3891  3891 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 18:40:07.638  3891  3891 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:07.640   874  1919 I ActivityManager: Killing 2987:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-29 18:40:07.691  2713  2767 I bt_hci  : shut_down
08-29 18:40:07.691  2713  2774 D bt_hwcfg: hw_epilog_process
,08-29 18:40:07.708  2713  2774 I bt_vendor: low_power_mode_cb
,08-29 18:40:07.730  2713  2774 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 18:40:07.730  2713  2774 I bt_vendor: epilog_cb
08-29 18:40:07.730  2713  2774 I bt_hci  : epilog_finished_callback
,08-29 18:40:07.734  2713  2767 I bt_hci_h4: hal_close
,08-29 18:40:07.734  2713  2767 I bt_userial_vendor: device fd = 51 close
,08-29 18:40:07.859  2713  2763 D bt_stack_manager: event_shut_down_stack finished.
,08-29 18:40:07.860  2713  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 18:40:07.865  2713  2713 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 18:40:07.865  2713  2761 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 18:40:07.865  2713  2713 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 18:40:07.865  2713  2713 D BtGatt.GattService: stop()
08-29 18:40:07.865  2713  2713 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 18:40:07.869  2713  2713 V BluetoothAdapterState: isTurningOff()=false
08-29 18:40:07.869  2713  2713 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:07.869  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:07.869  2713  2713 V BluetoothAdapterState: isBleTurningOff()=true
08-29 18:40:07.870  2713  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 18:40:07.871  2713  2761 D BluetoothAdapterProperties: Setting state to 10
08-29 18:40:07.871  2713  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 18:40:07.872  2713  2761 I BluetoothAdapterState: Entering OffState
,08-29 18:40:07.874   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 18:40:07.880  3825  3825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 18:40:07.886  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 18:40:07.886  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 18:40:07.886  2713  2763 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 18:40:07.889  2713  2763 D bt_stack_manager: event_clean_up_stack finished.
,08-29 18:40:07.888  2713  2713 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 18:40:07.892  2713  2713 I art     : System.exit called, status: 0
,08-29 18:40:07.892  2713  2713 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 18:40:07.916  3912  3912 D StrictMode: StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 18:40:07.916  3912  3912 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 18:40:07.916  3912  3912 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531),
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:07.916  3912  3912 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-2,9 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:07.916  3912  3912 D StrictMode: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:07.916  3912  3912 D StrictMode: 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:07.916  3912  3912 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
,08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63),
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.k.c(PG:18147),
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 18:40:07.916  3912  3912 D StrictMode: 	,at com.google.w.a.a.do.<init>(PG:40)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:07.916  3912  3912 D StrictMode: 	,at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616),
08-29 18:40:07.916  3912  3912 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
,08-29 18:40:07.916  3912  3912 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.File.doAccess(File.java:281)
,08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 18:40:07.916  3912  3912 D StrictMode: 	,at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 18:40:07.916  3912  3912 D StrictMode: ,	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:07.916  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:07.916  3912  3912 D StrictMode: 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:07.919  3912  3912 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2,
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
,08-29 18:40:07.919  3912  3912 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at java.io.File.exists(File.java:361)
,08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
,08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:07.919  3912  3912 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:07.919  3912  3912 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:07.919  3912  3912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:07.930  3891  3891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.andr,oid.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 18:40:07.935   874  1919 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
08-29 18:40:07.938   874  1919 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
08-29 18:40:07.940   874  1919 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
08-29 18:40:07.940   874  1919 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-29 18:40:07.940   874  1919 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 18:40:07.940   874  1919 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-29 18:40:07.940   874  1919 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-29 18:40:07.940   874  1919 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-29 18:40:07.940   874  1919 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-29 18:40:07.940   874  1919 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-29 18:40:07.940   874  1919 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-29 18:40:07.940   874  1919 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-29 18:40:07.940   874  1919 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,08-29 18:40:08.016   874  1919 I ActivityManager: Start proc 3944:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 18:40:08.020  3891  3891 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:08.020   874  2174 W ActivityManager: Spurious death for ProcessRecord{e209fab 3944:com.android.bluetooth/1002}, curProc for 2713: null
,08-29 18:40:08.021   874   884 I ActivityManager: Killing 3437:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 18:40:08.052  3912  3937 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 18:40:08.077   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b9640ba:true
,08-29 18:40:08.136  3944  3944 D AdapterServiceConfig: Adding HeadsetService
,08-29 18:40:08.136  3944  3944 D AdapterServiceConfig: Adding A2dpService
,08-29 18:40:08.136  3944  3944 D AdapterServiceConfig: Adding HidService
08-29 18:40:08.136  3944  3944 D AdapterServiceConfig: Adding HealthService
08-29 18:40:08.136  3944  3944 D AdapterServiceConfig: Adding PanService
,08-29 18:40:08.138  3944  3944 D AdapterServiceConfig: Adding GattService
,08-29 18:40:08.138  3944  3944 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 18:40:08.144  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:08.160  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 18:40:08.163  1727  1727 D SystemUpdateService: onCreate
,08-29 18:40:08.169  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 18:40:08.175  1727  3958 I SystemUpdateService: active receiver: enabled
,08-29 18:40:08.180  1727  3958 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 18:40:08.183  1727  3958 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 18:40:08.183  1727  3958 I SystemUpdateService: now status is 0 (complete)
08-29 18:40:08.183  1727  3958 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 18:40:08.183  1727  3958 I SystemUpdateService: file has been verified
08-29 18:40:08.184  1727  3958 I SystemUpdateService: OTA package size = 12249756
,08-29 18:40:08.188  1727  3958 I SystemUpdateService: showing system update notification
08-29 18:40:08.189  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 18:40:08.192  1727  2513 I iu.UploadsManager: num queued entries: 0
,08-29 18:40:08.193  1727  2513 I iu.UploadsManager: num updated entries: 0
,08-29 18:40:08.196  1727  2513 I iu.SyncManager: NEXT; no task
,08-29 18:40:08.201  1727  1727 D SystemUpdateService: onDestroy
,08-29 18:40:08.208  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 18:40:08.209  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 18:40:08.224   874   885 I ActivityManager: Start proc 3960:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 18:40:08.283  3960  3960 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 18:40:08.286  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:08.294  3960  3960 D SprintDMHelper: simOperator: 
08-29 18:40:08.294  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 18:40:08.311   874  2242 I ActivityManager: Start proc 3972:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-29 18:40:08.312   874  2242 I ActivityManager: Killing 3502:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 18:40:08.429   874  1920 I ActivityManager: Start proc 3987:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 18:40:08.433  3092  3986 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 18:40:08.438   874  1513 I ActivityManager: Killing 1688:android.process.acore/u0a5 (adj 15): empty #17
,08-29 18:40:08.509  3987  3987 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 18:40:08.570  3987  3987 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 18:40:08.570  3987  3987 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 18:40:08.570  3987  3987 I GAv4    :   adb logcat -s GAv4
,08-29 18:40:08.587  3987  3987 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 18:40:08.597  3987  3987 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 18:40:08.635  3987  4005 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 18:40:08.738  3987  3987 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 18:40:08.785  3987  3987 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 18:40:08.798  3987  3987 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 4736-4744)
,08-29 18:40:08.798  3987  3987 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 18:40:08.807  3987  3987 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1bbac05}
,08-29 18:40:08.808  3987  3987 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 18:40:08.808  3987  3987 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 18:40:08.817  3987  3987 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 18:40:08.819  3987  3987 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 18:40:08.836  3987  3987 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 18:40:08.849  3987  3987 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,08-29 18:40:08.849  3987  3987 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 18:40:08.850  3987  3987 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 18:40:08.850  3987  3987 I Adreno  : Build Date                       : 10/20/15
08-29 18:40:08.850  3987  3987 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 18:40:08.850  3987  3987 I Adreno  : Local Branch                     : M14
08-29 18:40:08.850  3987  3987 I Adreno  : Remote Branch                    : ,
08-29 18:40:08.850  3987  3987 I Adreno  : Remote Branch                    : 
08-29 18:40:08.850  3987  3987 I Adreno  : Reconstruct Branch               : 
,08-29 18:40:08.929  3987  3987 I NSApplication: Starting up...
,08-29 18:40:08.951  3987  4033 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 18:40:08.957   874  2242 I ActivityManager: Start proc 4038:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 18:40:08.959   874  2242 I ActivityManager: Killing 3683:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 18:40:09.061  4038  4038 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 18:40:09.233   874  1974 I ActivityManager: Killing 3700:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 18:40:09.319   874  2242 I ActivityManager: Start proc 4052:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 18:40:09.415  4052  4052 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 18:40:09.476  4052  4052 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 18:40:09.538   874  1920 I ActivityManager: Killing 3482:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 18:40:10.427   874  2242 D WifiService: setWifiEnabled: true pid=3825, uid=10000
08-29 18:40:10.427   874  2242 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 18:40:10.441   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-29 18:40:10.451  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:10.452  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:10.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:10.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:10.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:10.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:10.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:10.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:10.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:10.452  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:10.453  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:10.456  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:10.457  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:10.457  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:10.457  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:10.457  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:10.457  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:10.457  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:10.457  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:10.457  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:10.457  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:10.458  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:10.473   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-29 18:40:10.474   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 18:40:10.475   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 18:40:10.476   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 18:40:10.476   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 18:40:10.476   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 18:40:10.476   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 18:40:10.493   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.88 rxSuccessRate=8.75 delta 1000 -> 994
,08-29 18:40:10.493   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 18:40:10.495   372   872 D CommandListener: Setting iface cfg
,08-29 18:40:10.496   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
,08-29 18:40:10.496   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 18:40:10.503   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 18:40:10.503   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 18:40:10.512   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 18:40:10.514   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 18:40:10.544   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 18:40:10.564   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 18:40:10.590  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 18:40:11.014  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 18:40:11.054  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 18:40:11.054  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 18:40:11.064   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 18:40:11.074   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 18:40:11.075   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 18:40:11.075   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 18:40:11.104   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 18:40:11.125   372   872 D CommandListener: Setting iface cfg
,08-29 18:40:11.126   874  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 18:40:11.139   874  1312 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 18:40:11.144   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 18:40:11.202   874  4085 D DhcpClient: Receive thread started
,08-29 18:40:11.290   874  1308 E native  : do suspend false
,08-29 18:40:11.313   874  2102 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 18:40:11.328   874  4085 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172687, domain null
,08-29 18:40:11.329   874  2102 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172687 seconds
,08-29 18:40:11.333   874  2102 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 18:40:11.348   874  4085 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 18:40:11.349   874  2102 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 18:40:11.354   372   872 D CommandListener: Setting iface cfg
,08-29 18:40:11.365   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 18:40:11.367   874  2102 D DhcpClient: Scheduling renewal in 86399s
,08-29 18:40:11.381   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 18:40:11.385   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 18:40:11.386   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 18:40:11.387   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 18:40:11.389   874  1312 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 18:40:11.406   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 18:40:11.443   874  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 18:40:11.444   874  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 18:40:11.445   874  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 18:40:11.446   874  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 18:40:11.447   874  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 18:40:11.453   874  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 18:40:11.458   874  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 18:40:11.458   874  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 18:40:11.458   874  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 18:40:11.458   874  1312 D ConnectivityService:    accepting network in place of null
,08-29 18:40:11.462   874  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 18:40:11.463   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 18:40:11.464   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 18:40:11.484   874  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137430, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 18:40:11.524   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 18:40:11.559   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 18:40:11.568   874  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 18:40:11.570   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:11.573   874  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:816::200e
,08-29 18:40:11.576   874  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 18:40:11.579   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-29 18:40:11.588  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:11.589  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:11.589  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:11.589  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:11.589  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:11.589  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:11.589  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:11.589  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:11.589  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:11.589  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:11.589  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:11.596  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:11.596  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:11.596  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:11.596  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:11.596  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:11.596  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:11.596  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:11.596  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:11.596  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:11.596  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:11.597  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:11.603  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 18:40:11.607  1727  1727 D SystemUpdateService: onCreate
,08-29 18:40:11.611  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 18:40:11.614  1727  4095 I SystemUpdateService: active receiver: enabled
,08-29 18:40:11.621  1727  4095 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 18:40:11.623  1727  4095 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 18:40:11.623  1727  4095 I SystemUpdateService: now status is 0 (complete)
08-29 18:40:11.623  1727  4095 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 18:40:11.623  1727  4095 I SystemUpdateService: file has been verified
08-29 18:40:11.624  1727  4095 I SystemUpdateService: OTA package size = 12249756
,08-29 18:40:11.630  1727  4095 I SystemUpdateService: showing system update notification
,08-29 18:40:11.634  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 18:40:11.637  1727  2513 I iu.UploadsManager: num queued entries: 0
08-29 18:40:11.638  1727  4099 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 18:40:11.638  1727  4099 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 18:40:11.639  1727  2513 I iu.UploadsManager: num updated entries: 0
,08-29 18:40:11.640  1727  4099 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
08-29 18:40:11.640  1727  2513 I iu.SyncManager: NEXT; no task
08-29 18:40:11.640  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 18:40:11.642  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 18:40:11.645  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 18:40:11.647  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 18:40:11.648  1727  1727 D SystemUpdateService: onDestroy
,08-29 18:40:11.654  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:11.659  3960  3960 D SprintDMHelper: simOperator: 
08-29 18:40:11.659  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 18:40:11.674  1500  2088 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-29 18:40:11.674  1500  2088 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 18:40:11.674  1500  2088 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 18:40:11.674  1500  2088 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 18:40:11.680   874  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 16:40:11 GMT], X-Android-Received-Millis=[1472488811679], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472488811639]}
,08-29 18:40:11.681   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 18:40:11.681   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 18:40:11.681   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 18:40:11.683   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 18:40:11.697  1727  4099 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-29 18:40:11.834  3092  4101 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 18:40:11.837  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 18:40:11.838  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 18:40:11.838  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 18:40:11.838  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 18:40:11.859  3008  4105 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 18:40:11.859  3008  4105 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at jdm.a(PG:82)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at jcs.o(PG:406)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at jcn.a(PG:1379)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at jcs.i(PG:143)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at blb.a(PG:3937)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at czp.a(PG:18188)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at czp.a(PG:9081)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at czq.run(PG:1686)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 18:40:11.859  3008  4105 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at jdj.a(PG:4091)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at jdj.a(PG:1125)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at jdm.a(PG:77)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	... 12 more
08-29 18:40:11.859  3008  4105 E HttpOperation: Caused by: faj: BadAuthentication
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at fal.a(PG:38)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	at jdj.a(PG:4089)
08-29 18:40:11.859  3008  4105 E HttpOperation: 	... 14 more
,08-29 18:40:11.910  1500  2088 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 18:40:11.910  1500  2088 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 18:40:11.910  1500  2088 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 18:40:11.910  1500  2088 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 18:40:11.939  3008  4105 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 18:40:11.939  3008  4105 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at jdm.a(PG:82)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at jcs.o(PG:406)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at jcn.a(PG:1379)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at jcs.i(PG:143)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at hec.a(PG:42)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at hee.a(PG:102)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at czr.a(PG:65)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at kka.a(PG:108)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at czp.a(PG:19176)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at czp.a(PG:9081)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at czq.run(PG:1686)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 18:40:11.939  3008  4105 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at jdj.a(PG:4091)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at jdj.a(PG:1125)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at jdm.a(PG:77)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	... 15 more
08-29 18:40:11.939  3008  4105 E HttpOperation: Caused by: faj: BadAuthentication
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at fal.a(PG:38)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	at jdj.a(PG:4089)
08-29 18:40:11.939  3008  4105 E HttpOperation: 	... 17 more
08-29 18:40:11.939  3008  4105 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 18:40:11.939  3008  4105 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at hec.a(PG:42)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at hee.a(PG:102)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at czr.a(PG:65)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at kka.a(PG:108)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	... 15 more
08-29 18:40:11.939  3008  4105 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at fal.a(PG:38)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 18:40:11.939  3008  4105 E ExperimentLoader: 	... 17 more
,08-29 18:40:12.058   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 132157, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-29 18:40:12.566   874  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 18:40:13.092  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 18:40:13.160  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 18:40:13.161  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 18:40:13.161  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 18:40:13.162  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 18:40:13.216  3545  3545 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 18:40:13.216  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 18:40:13.219  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 18:40:13.238   874   884 I ActivityManager: Killing 3722:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 18:40:13.435   874  2174 D WifiService: setWifiEnabled: false pid=3825, uid=10000
,08-29 18:40:13.435   874  2174 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 18:40:13.455  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 18:40:13.460   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 18:40:13.460   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 18:40:13.460   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 18:40:13.460   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 18:40:13.481   874  2102 D DhcpClient: Clearing IP address
,08-29 18:40:13.481   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-29 18:40:13.486   372   872 D CommandListener: Setting iface cfg
,08-29 18:40:13.489  1500  4109 V NativeCrypto: Read error: ssl=0x9abb8200: I/O error during system call, Connection timed out
,08-29 18:40:13.491  1500  4109 V NativeCrypto: SSL shutdown failed: ssl=0x9abb8200: I/O error during system call, Broken pipe
,08-29 18:40:13.492   874  4085 D DhcpClient: Receive thread stopped
,08-29 18:40:13.495   874  1383 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-29 18:40:13.496   874  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-29 18:40:13.497   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 18:40:13.497   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 18:40:13.500   874  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:816::200e
,08-29 18:40:13.503   395   395 E Parcel  : Reading a NULL string not supported here.
08-29 18:40:13.504   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-29 18:40:13.506   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 18:40:13.508   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:13.519   874  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101],
08-29 18:40:13.521   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 18:40:13.525   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 18:40:13.525   874  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:816::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-29 18:40:13.535  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:13.535  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:13.535  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:13.535  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:13.535  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:13.535  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:13.535  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:13.535  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:13.535  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:13.535  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:13.535  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-29 18:40:13.536  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:13.536  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:13.536  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:13.536  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:13.536  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:13.536  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:13.536  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:13.536  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:13.536  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:13.536  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:13.536  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:13.540  1907  2305 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:13.564   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 18:40:13.595   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 18:40:13.596   874  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 18:40:13.596   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:13.598   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-29 18:40:13.601  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:13.602  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:13.611  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 18:40:13.615  1727  1727 D SystemUpdateService: onCreate
,08-29 18:40:13.617  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 18:40:13.620  1727  4121 I SystemUpdateService: active receiver: enabled
,08-29 18:40:13.630  1727  4121 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 18:40:13.634  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 18:40:13.636  1727  2513 I iu.UploadsManager: num queued entries: 0
08-29 18:40:13.636  1727  2513 I iu.UploadsManager: num updated entries: 0
,08-29 18:40:13.640  1727  4121 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 18:40:13.640  1727  4121 I SystemUpdateService: now status is 0 (complete)
08-29 18:40:13.641  1727  4121 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 18:40:13.641  1727  4121 I SystemUpdateService: file has been verified
08-29 18:40:13.641  1727  4121 I SystemUpdateService: OTA package size = 12249756
08-29 18:40:13.642  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 18:40:13.643  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-29 18:40:13.645  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 18:40:13.651  3960  3960 D SprintDMHelper: simOperator: 
08-29 18:40:13.651  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 18:40:13.661  1727  2513 I iu.SyncManager: NEXT; no task
,08-29 18:40:13.662  1727  4121 I SystemUpdateService: showing system update notification
,08-29 18:40:13.677  3092  4125 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 18:40:13.694  1727  1727 D SystemUpdateService: onDestroy
,08-29 18:40:13.697   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-29 18:40:13.698   874  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 18:40:13.698   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 18:40:16.488   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a2dd919:true
08-29 18:40:16.489  3944  3944 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 18:40:16.494  3944  3944 I bt_bluedroid: init
,08-29 18:40:16.494  3944  4130 I BluetoothAdapterState: Entering OffState
,08-29 18:40:16.499  3944  4131 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 18:40:16.500  3944  4131 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 18:40:16.500  3944  4131 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 18:40:16.500  3944  4131 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 18:40:16.502  3944  3944 I bt_bluedroid: get_profile_interface socket
08-29 18:40:16.504  3944  3944 I bt_bluedroid: get_profile_interface sdp
,08-29 18:40:16.508  3944  3956 I bt_bluedroid: config_hci_snoop_log
08-29 18:40:16.509  3944  4134 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-29 18:40:16.510   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-29 18:40:16.511  3944  4134 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 18:40:16.517  3944  4130 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 18:40:16.518  3944  4130 D BluetoothAdapterProperties: Setting state to 14
,08-29 18:40:16.518  3944  4130 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 18:40:16.522  3944  4130 D BluetoothBondStateMachine: make
,08-29 18:40:16.528  3944  4135 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 18:40:16.533  3944  4130 I BluetoothAdapterState: Entering PendingCommandState
,08-29 18:40:16.534  3944  3944 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-29 18:40:16.537  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863,
08-29 18:40:16.538  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 18:40:16.538  3944  3944 D BtGatt.GattService: Received start request. Starting profile...
,08-29 18:40:16.538  3944  3944 D BtGatt.GattService: start()
08-29 18:40:16.538  3944  3944 I bt_bluedroid: get_profile_interface gatt
08-29 18:40:16.539  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
08-29 18:40:16.539  3944  3944 D BtGatt.AdvertiseManager: advertise manager created
,08-29 18:40:16.549  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-29 18:40:16.549  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:16.549  3944  3944 V BluetoothAdapterState: isBleTurningOn()=true
08-29 18:40:16.549  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:16.550  3944  4130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 18:40:16.550  3944  4130 I bt_bluedroid: enable
08-29 18:40:16.551  3944  4131 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 18:40:16.552  3944  4131 I bt_hci  : start_up
,08-29 18:40:16.570  3944  4131 I bt_vendor: alloc value 0xb3939189
,08-29 18:40:16.571  3944  4131 I bt_vendor: init
,08-29 18:40:16.571  3944  4131 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 18:40:16.571  3944  4131 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 18:40:16.679  3944  4131 D bt_hci  : start_up starting async portion
,08-29 18:40:16.680  3944  4138 I bt_hci  : event_finish_startup
,08-29 18:40:16.680  3944  4138 I bt_hci_h4: hal_open
,08-29 18:40:16.681  3944  4138 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 18:40:16.690  3944  4138 I bt_userial_vendor: device fd = 51 open
,08-29 18:40:16.720  3944  4138 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 18:40:16.753  3944  4138 D bt_hwcfg: Chipset BCM4354A2
,08-29 18:40:16.753  3944  4138 D bt_hwcfg: Target name = [BCM4354A2]
08-29 18:40:16.754  3944  4138 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 18:40:17.418  3944  4138 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 18:40:17.420  3944  4138 D bt_hwcfg: Settlement delay -- 100 ms
08-29 18:40:17.420  3944  4138 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 18:40:17.537  3944  4138 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 18:40:17.538  3944  4138 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 18:40:17.568  3944  4138 I bt_hwcfg: vendor lib fwcfg completed
,08-29 18:40:17.568  3944  4138 I bt_vendor: firmware callback
08-29 18:40:17.569  3944  4138 I bt_hci  : firmware_config_callback
,08-29 18:40:17.582  3944  4140 I bt_btu  : btu_task pending for preload complete event
,08-29 18:40:17.582  3944  4140 I bt_btu_task: Bluetooth chip preload is complete
,08-29 18:40:17.582  3944  4140 I bt_btu  : btu_task received preload complete event
,08-29 18:40:17.595  3944  4140 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 18:40:17.595  3944  4140 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 18:40:17.595  3944  4140 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 18:40:17.596  3944  4140 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 18:40:17.596  3944  4140 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 18:40:17.596  3944  4140 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 18:40:17.596  3944  4140 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 18:40:17.597  3944  4140 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 18:40:17.597  3944  4140 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 18:40:17.597  3944  4140 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 18:40:17.598  3944  4140 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 18:40:17.598  3944  4140 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 18:40:17.598  3944  4140 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 18:40:17.599  3944  4140 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 18:40:17.599  3944  4140 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 18:40:17.736  3944  4140 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
08-29 18:40:17.736  3944  4140 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-29 18:40:17.748  3944  4134 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 18:40:17.749  3944  4134 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 18:40:17.750  3944  4134 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 18:40:17.754  3944  4134 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 18:40:17.758  3944  4134 D BluetoothAdapterProperties: Scan Mode:20
,08-29 18:40:17.759  3944  4134 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 18:40:17.759  3944  4134 D bt_hci  : do_postload posting postload work item
,08-29 18:40:17.762  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:17.763  3944  4138 I bt_hci  : event_postload
,08-29 18:40:17.763  3944  4138 I bt_vendor: sco_config_cb
,08-29 18:40:17.763  3944  4138 I bt_hci  : sco_config_callback postload finished.
08-29 18:40:17.765  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:17.768  3944  4134 D bt_bte_conf: Device ID record 1 : primary
,08-29 18:40:17.769  3944  4134 D bt_bte_conf:   vendorId            = 000f
,08-29 18:40:17.769  3944  4134 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 18:40:17.770  3944  4134 D bt_bte_conf:   product             = 1200
,08-29 18:40:17.771  3944  4134 D bt_bte_conf:   version             = 1436
,08-29 18:40:17.771  3944  4134 D bt_bte_conf:   clientExecutableURL = 
,08-29 18:40:17.771  3944  4134 D bt_bte_conf:   serviceDescription  = ,
08-29 18:40:17.771  3944  4134 D bt_bte_conf:   documentationURL    = 
,08-29 18:40:17.772  3944  4138 I bt_vendor: low_power_mode_cb
,08-29 18:40:17.772  3944  4134 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 18:40:17.772  3944  4131 D bt_stack_manager: event_start_up_stack finished
,08-29 18:40:17.773  3944  4130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 18:40:17.773  3944  4130 D BluetoothAdapterProperties: Setting state to 15
08-29 18:40:17.774  3944  4130 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 18:40:17.775  3944  4130 I BluetoothAdapterState: Entering BleOnState
08-29 18:40:17.778  3944  4130 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 18:40:17.779  3944  4130 D BluetoothAdapterProperties: Setting state to 11
08-29 18:40:17.779  3944  4130 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 18:40:17.784  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:17.786  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:17.788  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863,
08-29 18:40:17.789  3944  3944 D HeadsetService: Received start request. Starting profile...
08-29 18:40:17.793  3944  3944 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 18:40:17.793  3944  3944 D HeadsetStateMachine: make
08-29 18:40:17.800  3944  4130 I BluetoothAdapterState: Entering PendingCommandState,
,08-29 18:40:17.804  3944  3944 D HeadsetStateMachine: max_hf_connections = 1
08-29 18:40:17.804  3944  3944 I bt_bluedroid: get_profile_interface handsfree
08-29 18:40:17.807  3944  4134 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 18:40:17.807  3944  4134 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 18:40:17.809  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:17.809  3944  3944 D A2dpService: Received start request. Starting profile...
,08-29 18:40:17.810  3944  3944 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 18:40:17.811  3944  3944 I bt_bluedroid: get_profile_interface avrcp
08-29 18:40:17.812  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 18:40:17.816  3944  3944 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 18:40:17.816  3944  3944 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 18:40:17.816  3944  3944 D A2dpStateMachine: make
,08-29 18:40:17.817  3944  3944 I bt_bluedroid: get_profile_interface a2dp
,08-29 18:40:17.818  3944  4134 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 18:40:17.820  3944  3944 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 18:40:17.820  3944  4150 D A2dpStateMachine: Enter Disconnected: -2
,08-29 18:40:17.821  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:17.822  3944  3944 D HidService: Received start request. Starting profile...
,08-29 18:40:17.822  3891  3891 D BluetoothInputDevice: Proxy object connected
08-29 18:40:17.822  3944  3944 I bt_bluedroid: get_profile_interface hidhost
08-29 18:40:17.822  3944  4134 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
,08-29 18:40:17.822  3944  4134 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 18:40:17.822  3944  3944 D HidService: setHidService(): set to: null
08-29 18:40:17.823  3891  3891 D HidProfile: Bluetooth service connected
08-29 18:40:17.823  3944  3944 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 18:40:17.824  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
08-29 18:40:17.824  3944  3944 D HealthService: Received start request. Starting profile...
,08-29 18:40:17.825  3944  3944 I bt_bluedroid: get_profile_interface health
08-29 18:40:17.826  3944  3944 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 18:40:17.827  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:17.828  3944  3944 D PanService: Received start request. Starting profile...
08-29 18:40:17.828  3944  3944 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 18:40:17.828  3944  3944 I bt_bluedroid: get_profile_interface pan
,08-29 18:40:17.829  3944  4134 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 18:40:17.830  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:17.831  3891  3891 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 18:40:17.831  3944  3944 D BluetoothMapService: Received start request. Starting profile...
,08-29 18:40:17.831  3891  3891 D PanProfile: Bluetooth service connected
,08-29 18:40:17.831  3944  3944 D BluetoothMapService: start()
08-29 18:40:17.832  3891  3891 D BluetoothMap: Proxy object connected
08-29 18:40:17.832  3891  3891 D MapProfile: Bluetooth service connected
08-29 18:40:17.832  3891  3891 D BluetoothMap: getConnectedDevices()
08-29 18:40:17.833  3891  3891 D BluetoothMap: Bluetooth is Not enabled
08-29 18:40:17.833  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 18:40:17.833  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 18:40:17.834  3944  3944 D BluetoothMapAppObserver: createReceiver()
,08-29 18:40:17.834  3944  3944 D BluetoothMapAppObserver: initObservers()
08-29 18:40:17.834  3944  3944 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 18:40:17.847  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-29 18:40:17.847  3944  4148 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 18:40:17.847  3944  3944 V BluetoothAdapterState: isTurningOn()=true
,08-29 18:40:17.847  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:17.847  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:17.848  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-29 18:40:17.848  3944  3944 V BluetoothAdapterState: isTurningOn()=true
,08-29 18:40:17.848  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 18:40:17.849  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:17.849  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-29 18:40:17.849  3944  3944 V BluetoothAdapterState: isTurningOn()=true
,08-29 18:40:17.849  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 18:40:17.849  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:17.849  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-29 18:40:17.849  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-29 18:40:17.849  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:17.849  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:17.850  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-29 18:40:17.850  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-29 18:40:17.850  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 18:40:17.850  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:17.850  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-29 18:40:17.850  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-29 18:40:17.850  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 18:40:17.850  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:17.851  3944  4130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 18:40:17.851  3944  4130 D BluetoothAdapterProperties: ScanMode =  20
08-29 18:40:17.851  3944  4130 D BluetoothAdapterProperties: State =  11
08-29 18:40:17.851  3944  4130 D BluetoothAdapterProperties: Setting state to 12
08-29 18:40:17.851  3944  4130 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 18:40:17.852   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:17.852  3891  3903 D BluetoothMap: onBluetoothStateChange: up=true
08-29 18:40:17.853  1363  3824 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 18:40:17.853  3944  4134 D BluetoothAdapterProperties: Scan Mode:21
,08-29 18:40:17.853  3944  4134 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 18:40:17.853  3944  4130 I BluetoothAdapterState: Entering OnState
08-29 18:40:17.854  1363  1684 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 18:40:17.855  1363  1363 D BluetoothA2dp: Proxy object connected
08-29 18:40:17.856  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:17.856  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:17.856  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:17.856  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:17.856  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:17.856  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:17.856  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:17.856  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:17.856  3891  3904 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 18:40:17.857  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:17.858  1363  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 18:40:17.858  1363  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 18:40:17.859  1363  1363 D BluetoothInputDevice: Proxy object connected
,08-29 18:40:17.859  1363  1363 D HidProfile: Bluetooth service connected
08-29 18:40:17.859  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:17.859  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:17.859  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:17.859  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:17.859  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:17.859  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:17.859  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:17.859  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:17.860   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:17.860  3891  3903 D BluetoothPan: onBluetoothStateChange on: true
08-29 18:40:17.860   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:17.860  1982  2297 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:17.861  1363  1684 D BluetoothMap: onBluetoothStateChange: up=true
08-29 18:40:17.861  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:17.862  1363  1363 D BluetoothMap: Proxy object connected
08-29 18:40:17.862  1363  1363 D MapProfile: Bluetooth service connected
08-29 18:40:17.862  3891  3904 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 18:40:17.862  1363  1363 D BluetoothMap: getConnectedDevices()
08-29 18:40:17.862   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 18:40:17.862   874   874 D BluetoothA2dp: Proxy object connected
08-29 18:40:17.862  1363  2082 D BluetoothPan: onBluetoothStateChange on: true
08-29 18:40:17.863  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 18:40:17.863  1363  1363 D PanProfile: Bluetooth service connected
08-29 18:40:17.866  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 18:40:17.866  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:17.866  3944  3944 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 18:40:17.866   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 18:40:17.867  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:17.867  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:17.869  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:17.869  3891  3891 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 18:40:17.870  3944  3944 D ObexServerSockets: Succeed to create listening sockets 
08-29 18:40:17.870  3944  3944 D ObexServerSockets0: startAccept(),
08-29 18:40:17.870  3944  3944 D ObexServerSockets0: prepareForNewConnect()
08-29 18:40:17.872  3944  3944 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 18:40:17.872  3944  3944 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 18:40:17.872  3944  4155 D ObexServerSockets0: Accepting socket connection...
,08-29 18:40:17.872  3944  3944 D BluetoothMapService: onReceive
08-29 18:40:17.872  3944  4156 D ObexServerSockets0: Accepting socket connection...
,08-29 18:40:17.872  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:17.872  3944  3944 D BluetoothMapService: STATE_ON
08-29 18:40:17.874  3891  3891 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 18:40:17.881  3891  3891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 18:40:17.884  3891  3891 D BluetoothA2dp: Proxy object connected
,08-29 18:40:17.887  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:17.891  3891  3891 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:17.894  3891  3891 D BluetoothPbap: Proxy object connected
,08-29 18:40:17.894  1363  1363 D BluetoothPbap: Proxy object connected
08-29 18:40:17.894  1363  1363 D PbapServerProfile: Bluetooth service connected
08-29 18:40:17.894  3891  3891 D PbapServerProfile: Bluetooth service connected
,08-29 18:40:17.898  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 18:40:17.898  3944  3944 D ObexServerSockets0: prepareForNewConnect()
,08-29 18:40:17.900  3944  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:17.910  3944  4164 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:17.911  3944  4164 I BtOppRfcommListener: Accept thread started.
,08-29 18:40:17.952  1982  1993 D BluetoothHeadset: Proxy object connected
,08-29 18:40:17.953   874   874 D BluetoothHeadset: Proxy object connected
,08-29 18:40:17.953   874   874 D BluetoothHeadset: Proxy object connected
08-29 18:40:17.953  1363  1384 D BluetoothHeadset: Proxy object connected
08-29 18:40:17.953  1363  1363 D HeadsetProfile: Bluetooth service connected
08-29 18:40:17.953   874   874 D BluetoothHeadset: Proxy object connected
,08-29 18:40:17.958  1363  1684 D BluetoothHeadset: Proxy object connected
,08-29 18:40:17.958  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-29 18:40:17.959   874   891 D BluetoothHeadset: Proxy object connected
,08-29 18:40:17.959   874   891 D BluetoothHeadset: Proxy object connected
,08-29 18:40:17.961  1982  2175 D BluetoothHeadset: Proxy object connected
,08-29 18:40:17.977  3891  3903 D BluetoothHeadset: Proxy object connected
,08-29 18:40:17.978  3891  3891 D HeadsetProfile: Bluetooth service connected
,08-29 18:40:19.452  3944  4130 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 18:40:19.452  3944  4130 D BluetoothAdapterProperties: Setting state to 13
,08-29 18:40:19.453  3944  4130 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 18:40:19.455  3944  4130 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 18:40:19.463  3944  3944 D BluetoothMapService: onReceive
,08-29 18:40:19.464  3944  4130 I BluetoothAdapterState: Entering PendingCommandState
08-29 18:40:19.464  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:19.464   874  1312 D ConnectivityService: handlePromptUnvalidated 101
,08-29 18:40:19.464  3944  3944 D BluetoothMapService: STATE_TURNING_OFF
,08-29 18:40:19.466  3944  3944 D BluetoothMapService: MAP Service closeService in
08-29 18:40:19.466  3944  3944 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 18:40:19.466  3944  3944 D ObexServerSockets0: shutdown(block = true)
,08-29 18:40:19.467  3944  4155 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 18:40:19.471  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:19.471  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:19.471  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:19.471  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:19.471  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:19.471  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:19.471  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:19.471  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:19.471  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:19.469  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 18:40:19.474  3944  4134 D BluetoothAdapterProperties: Scan Mode:20
08-29 18:40:19.474  3944  4143 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 18:40:19.475  3944  4156 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 18:40:19.475  3944  4130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 18:40:19.477  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:19.478  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:19.478  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 18:40:19.482  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:19.482  3944  3944 I BtOppRfcommListener: stopping Accept Thread
08-29 18:40:19.482  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:19.482  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:19.482  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:19.482  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:19.482  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:19.482  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:19.482  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:19.482  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:19.482  3944  4164 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:40:19.483  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:19.483  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:19.484  3891  3891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 18:40:19.485  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:19.485  3944  4164 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 18:40:19.491  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:19.491  3944  3944 D HeadsetService: Received stop request...Stopping profile...
08-29 18:40:19.495  1982  2003 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:19.496  3944  3944 D A2dpService: Received stop request...Stopping profile...
08-29 18:40:19.496   874   874 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:19.496  3944  4150 D A2dpStateMachine: Exit Disconnected: -1
,08-29 18:40:19.496   874   874 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:19.496  1363  1384 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:19.497  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-29 18:40:19.497  3891  3904 D BluetoothHeadset: Proxy object disconnected
08-29 18:40:19.497   874   874 D BluetoothHeadset: Proxy object disconnected
,08-29 18:40:19.498   874   874 D BluetoothA2dp: Proxy object disconnected
,08-29 18:40:19.498  1363  1363 D BluetoothA2dp: Proxy object disconnected
,08-29 18:40:19.499  3944  3944 D HidService: Received stop request...Stopping profile...
08-29 18:40:19.499  3891  3891 D DockEventReceiver: finishStartingService: stopping service
08-29 18:40:19.499  3944  3944 D HidService: Stopping Bluetooth HidService
08-29 18:40:19.500  1363  1363 D BluetoothInputDevice: Proxy object disconnected
08-29 18:40:19.500  1363  1363 D HidProfile: Bluetooth service disconnected
08-29 18:40:19.501  3944  3944 D HealthService: Received stop request...Stopping profile...
08-29 18:40:19.501  3891  3891 D HeadsetProfile: Bluetooth service disconnected
08-29 18:40:19.501  3891  3891 D BluetoothA2dp: Proxy object disconnected
08-29 18:40:19.502  3891  3891 D BluetoothInputDevice: Proxy object disconnected
08-29 18:40:19.502  3891  3891 D HidProfile: Bluetooth service disconnected
,08-29 18:40:19.506  3944  3944 D PanService: Received stop request...Stopping profile...
,08-29 18:40:19.507  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 18:40:19.507  1363  1363 D PanProfile: Bluetooth service disconnected
08-29 18:40:19.507  3891  3891 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 18:40:19.507  3891  3891 D PanProfile: Bluetooth service disconnected
,08-29 18:40:19.508  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:19.508  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:19.508  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:19.508  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:19.510  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:19.510  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 18:40:19.511  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 18:40:19.511  3944  4134 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 18:40:19.511  3944  4140 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 18:40:19.511  3944  4140 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 18:40:19.512  3944  4140 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 18:40:19.512  3944  4134 E bt_btif : btif_hf_upstreams_evt: Invalid index 30574
,08-29 18:40:19.512  3944  3944 D BluetoothMapService: Received stop request...Stopping profile...
08-29 18:40:19.512  3944  3944 D BluetoothMapService: stop()
08-29 18:40:19.513  3944  3944 D BluetoothMapAppObserver: deinitObservers()
,08-29 18:40:19.513  3944  3944 D BluetoothMapAppObserver: removeReceiver()
,08-29 18:40:19.514  1363  1363 D BluetoothMap: Proxy object disconnected
08-29 18:40:19.514  1363  1363 D MapProfile: Bluetooth service disconnected
08-29 18:40:19.515  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:19.514  3891  3891 D BluetoothMap: Proxy object disconnected
08-29 18:40:19.515  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-29 18:40:19.515  3891  3891 D MapProfile: Bluetooth service disconnected
08-29 18:40:19.515  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:19.515  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:19.516  3944  4140 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 18:40:19.516  3944  4134 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 18:40:19.516  3944  4140 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 18:40:19.516  3944  4140 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 18:40:19.516  3944  4140 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 18:40:19.516  3944  4140 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:19.516  3944  4140 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 18:40:19.517  3944  3944 V BluetoothAdapterState: isTurningOff()=true
,08-29 18:40:19.517  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-29 18:40:19.517  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false,
08-29 18:40:19.517  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:19.518  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 18:40:19.518  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 18:40:19.518  3944  4134 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 18:40:19.518  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:19.518  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:19.518  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:19.518  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:19.519  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 18:40:19.519  3944  4134 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-29 18:40:19.521  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 18:40:19.521  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:19.521  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:19.521  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:19.523  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:19.524  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 18:40:19.524  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 18:40:19.527  1363  1363 D BluetoothPbap: Proxy object disconnected
,08-29 18:40:19.527  1363  1363 D PbapServerProfile: Bluetooth service disconnected
08-29 18:40:19.527  3891  3891 D BluetoothPbap: Proxy object disconnected
,08-29 18:40:19.528  3891  3891 D PbapServerProfile: Bluetooth service disconnected
,08-29 18:40:19.529  3944  3944 D BluetoothMapService: MAP Service closeService in
,08-29 18:40:19.529  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-29 18:40:19.529  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-29 18:40:19.529  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:19.529  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:19.529  3944  4130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 18:40:19.530  3944  4130 D BluetoothAdapterProperties: Setting state to 15
08-29 18:40:19.530  3944  4130 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 18:40:19.530  3944  4130 I BluetoothAdapterState: Entering BleOnState
08-29 18:40:19.530  3944  3944 D BluetoothMapService: cleanup()
08-29 18:40:19.530  3944  3944 D BluetoothMapService: MAP Service closeService in
,08-29 18:40:19.532   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:19.533  3891  3904 D BluetoothMap: onBluetoothStateChange: up=false
08-29 18:40:19.533  1363  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 18:40:19.534  1363  2082 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 18:40:19.535  3891  3903 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 18:40:19.535  3891  3904 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 18:40:19.536  1363  3824 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:19.536  1363  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 18:40:19.536   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 18:40:19.537  3891  3903 D BluetoothPan: onBluetoothStateChange on: false
08-29 18:40:19.537   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 18:40:19.537  1982  2297 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 18:40:19.537  1363  1684 D BluetoothMap: onBluetoothStateChange: up=false
08-29 18:40:19.538  3891  3904 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 18:40:19.538   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 18:40:19.539  1363  1385 D BluetoothPan: onBluetoothStateChange on: false
,08-29 18:40:19.539  3891  3903 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 18:40:19.540  3944  4130 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 18:40:19.540  3944  4130 D BluetoothAdapterProperties: Setting state to 16
08-29 18:40:19.540  3944  4130 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16,
08-29 18:40:19.541  3944  4130 D BluetoothAdapterProperties: onBleDisable
,08-29 18:40:19.541  3944  4130 I BluetoothAdapterState: Entering PendingCommandState
08-29 18:40:19.541  3944  4131 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 18:40:19.542  3944  4140 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 18:40:19.542  3944  4140 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 18:40:19.545  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:19.545  3944  4134 D BluetoothAdapterProperties: Scan Mode:20
08-29 18:40:19.545  3891  3891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 18:40:19.546  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:19.548  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:19.549  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:19.552  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:19.556  3891  3891 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:19.746  3944  4134 I bt_hci  : shut_down
,08-29 18:40:19.764  3944  4138 I bt_vendor: low_power_mode_cb
,08-29 18:40:19.777  3944  4138 D bt_hwcfg: hw_epilog_process
,08-29 18:40:19.787  3944  4138 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 18:40:19.787  3944  4138 I bt_vendor: epilog_cb
,08-29 18:40:19.787  3944  4138 I bt_hci  : epilog_finished_callback
,08-29 18:40:19.794  3944  4134 I bt_hci_h4: hal_close
,08-29 18:40:19.795  3944  4134 I bt_userial_vendor: device fd = 51 close
,08-29 18:40:19.915  3944  4131 D bt_stack_manager: event_shut_down_stack finished.
,08-29 18:40:19.916  3944  4130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 18:40:19.921  3944  4130 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 18:40:19.922  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 18:40:19.923  3944  3944 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 18:40:19.924  3944  3944 D BtGatt.GattService: stop()
,08-29 18:40:19.925  3944  3944 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 18:40:19.930  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-29 18:40:19.930  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-29 18:40:19.931  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:19.931  3944  3944 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 18:40:19.932  3944  4130 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 18:40:19.933  3944  4130 D BluetoothAdapterProperties: Setting state to 10
,08-29 18:40:19.934  3944  4130 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 18:40:19.936  3944  4130 I BluetoothAdapterState: Entering OffState
08-29 18:40:19.937   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 18:40:19.967  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 18:40:19.967  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 18:40:19.968  3944  4131 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 18:40:19.978  3944  4131 D bt_stack_manager: event_clean_up_stack finished.
,08-29 18:40:19.979  3944  3944 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 18:40:19.986  3944  3944 I art     : System.exit called, status: 0
,08-29 18:40:19.986  3944  3944 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 18:40:20.028   874  1383 I ActivityManager: Process com.android.bluetooth (pid 3944) has died
,08-29 18:40:22.449  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 18:40:22.449  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:25.457  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.457  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f17811 added. We now have 6 listener(s)
,08-29 18:40:25.458  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:25.462  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:25.462  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48b7d76 added. We now have 7 listener(s)
08-29 18:40:25.462  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:25.464  3825  3875 I System.out: IsBluetoothEnabled
,08-29 18:40:25.476  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:25.527   874   891 I ActivityManager: Start proc 4177:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 18:40:25.670  4177  4177 D AdapterServiceConfig: Adding HeadsetService
,08-29 18:40:25.670  4177  4177 D AdapterServiceConfig: Adding A2dpService
08-29 18:40:25.671  4177  4177 D AdapterServiceConfig: Adding HidService
08-29 18:40:25.671  4177  4177 D AdapterServiceConfig: Adding HealthService
,08-29 18:40:25.672  4177  4177 D AdapterServiceConfig: Adding PanService
08-29 18:40:25.672  4177  4177 D AdapterServiceConfig: Adding GattService
,08-29 18:40:25.672  4177  4177 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 18:40:25.689   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@65069dd:true
,08-29 18:40:25.691  4177  4177 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 18:40:25.700  4177  4177 I bt_bluedroid: init
,08-29 18:40:25.701  4177  4189 I BluetoothAdapterState: Entering OffState
,08-29 18:40:25.705  4177  4190 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 18:40:25.705  4177  4190 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 18:40:25.705  4177  4190 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 18:40:25.706  4177  4190 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 18:40:25.707  4177  4177 I bt_bluedroid: get_profile_interface socket
,08-29 18:40:25.712  4177  4177 I bt_bluedroid: get_profile_interface sdp
,08-29 18:40:25.712  4177  4193 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 18:40:25.716  4177  4193 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 18:40:25.719  4177  4188 I bt_bluedroid: config_hci_snoop_log
,08-29 18:40:25.721   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 18:40:25.729  4177  4189 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 18:40:25.729  4177  4189 D BluetoothAdapterProperties: Setting state to 14
,08-29 18:40:25.730  4177  4189 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 18:40:25.734  4177  4189 D BluetoothBondStateMachine: make
,08-29 18:40:25.739  4177  4194 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 18:40:25.746  4177  4189 I BluetoothAdapterState: Entering PendingCommandState
,08-29 18:40:25.750  4177  4177 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 18:40:25.759  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:25.761  4177  4177 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 18:40:25.763  4177  4177 D BtGatt.GattService: Received start request. Starting profile...
,08-29 18:40:25.763  4177  4177 D BtGatt.GattService: start()
,08-29 18:40:25.764  4177  4177 I bt_bluedroid: get_profile_interface gatt
,08-29 18:40:25.766  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:25.767  4177  4177 D BtGatt.AdvertiseManager: advertise manager created
,08-29 18:40:25.781  4177  4177 V BluetoothAdapterState: isTurningOff()=false
,08-29 18:40:25.781  4177  4177 V BluetoothAdapterState: isTurningOn()=false
,08-29 18:40:25.781  4177  4177 V BluetoothAdapterState: isBleTurningOn()=true
08-29 18:40:25.782  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:25.783  4177  4189 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 18:40:25.784  4177  4189 I bt_bluedroid: enable
08-29 18:40:25.785  4177  4190 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 18:40:25.786  4177  4190 I bt_hci  : start_up
,08-29 18:40:25.808  4177  4190 I bt_vendor: alloc value 0xb399d189
,08-29 18:40:25.809  4177  4190 I bt_vendor: init
08-29 18:40:25.809  4177  4190 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 18:40:25.809  4177  4190 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 18:40:25.918  4177  4190 D bt_hci  : start_up starting async portion
,08-29 18:40:25.919  4177  4197 I bt_hci  : event_finish_startup
08-29 18:40:25.919  4177  4197 I bt_hci_h4: hal_open
08-29 18:40:25.919  4177  4197 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 18:40:25.929  4177  4197 I bt_userial_vendor: device fd = 51 open
,08-29 18:40:25.961  4177  4197 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 18:40:25.992  4177  4197 D bt_hwcfg: Chipset BCM4354A2
,08-29 18:40:25.993  4177  4197 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 18:40:25.994  4177  4197 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 18:40:26.666  4177  4197 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 18:40:26.667  4177  4197 D bt_hwcfg: Settlement delay -- 100 ms
08-29 18:40:26.668  4177  4197 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 18:40:26.784  4177  4197 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 18:40:26.786  4177  4197 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 18:40:26.816  4177  4197 I bt_hwcfg: vendor lib fwcfg completed
08-29 18:40:26.816  4177  4197 I bt_vendor: firmware callback
,08-29 18:40:26.816  4177  4197 I bt_hci  : firmware_config_callback
,08-29 18:40:26.827  4177  4199 I bt_btu  : btu_task pending for preload complete event
,08-29 18:40:26.827  4177  4199 I bt_btu_task: Bluetooth chip preload is complete
08-29 18:40:26.827  4177  4199 I bt_btu  : btu_task received preload complete event
,08-29 18:40:26.838  4177  4199 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 18:40:26.838  4177  4199 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 18:40:26.839  4177  4199 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 18:40:26.839  4177  4199 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 18:40:26.839  4177  4199 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 18:40:26.839  4177  4199 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 18:40:26.840  4177  4199 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 18:40:26.840  4177  4199 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 18:40:26.840  4177  4199 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 18:40:26.841  4177  4199 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 18:40:26.841  4177  4199 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 18:40:26.841  4177  4199 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 18:40:26.841  4177  4199 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 18:40:26.841  4177  4199 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 18:40:26.842  4177  4199 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 18:40:26.977  4177  4199 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391ad9d
,08-29 18:40:26.977  4177  4199 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391ad9d 
,08-29 18:40:27.000  4177  4193 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 18:40:27.001  4177  4193 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 18:40:27.002  4177  4193 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 18:40:27.006  4177  4193 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 18:40:27.009  4177  4193 D BluetoothAdapterProperties: Scan Mode:20
,08-29 18:40:27.010  4177  4193 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 18:40:27.011  4177  4193 D bt_hci  : do_postload posting postload work item
08-29 18:40:27.012  4177  4197 I bt_hci  : event_postload
,08-29 18:40:27.012  4177  4197 I bt_vendor: sco_config_cb
08-29 18:40:27.012  4177  4197 I bt_hci  : sco_config_callback postload finished.
,08-29 18:40:27.015  4177  4193 D bt_bte_conf: Device ID record 1 : primary
08-29 18:40:27.015  4177  4193 D bt_bte_conf:   vendorId            = 000f
08-29 18:40:27.015  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:27.015  4177  4193 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 18:40:27.015  4177  4193 D bt_bte_conf:   product             = 1200
,08-29 18:40:27.015  4177  4193 D bt_bte_conf:   version             = 1436
08-29 18:40:27.016  4177  4193 D bt_bte_conf:   clientExecutableURL = 
08-29 18:40:27.016  4177  4193 D bt_bte_conf:   serviceDescription  = 
,08-29 18:40:27.016  4177  4193 D bt_bte_conf:   documentationURL    = 
08-29 18:40:27.016  4177  4193 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 18:40:27.017  4177  4190 D bt_stack_manager: event_start_up_stack finished
08-29 18:40:27.020  4177  4197 I bt_vendor: low_power_mode_cb
,08-29 18:40:27.021  4177  4189 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 18:40:27.024  4177  4189 D BluetoothAdapterProperties: Setting state to 15
08-29 18:40:27.024  4177  4189 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 18:40:27.030  4177  4189 I BluetoothAdapterState: Entering BleOnState
,08-29 18:40:27.032  4177  4189 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 18:40:27.032  4177  4189 D BluetoothAdapterProperties: Setting state to 11
08-29 18:40:27.032  4177  4189 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 18:40:27.037  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:27.038  4177  4177 D HeadsetService: Received start request. Starting profile...
,08-29 18:40:27.044  4177  4177 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 18:40:27.045  4177  4177 D HeadsetStateMachine: make
,08-29 18:40:27.050  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:27.052  4177  4189 I BluetoothAdapterState: Entering PendingCommandState
,08-29 18:40:27.062  4177  4177 D HeadsetStateMachine: max_hf_connections = 1
,08-29 18:40:27.063  4177  4177 I bt_bluedroid: get_profile_interface handsfree
08-29 18:40:27.063  4177  4193 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 18:40:27.064  4177  4193 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 18:40:27.071  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:27.074  4177  4177 D A2dpService: Received start request. Starting profile...
,08-29 18:40:27.075  4177  4177 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 18:40:27.076  4177  4177 I bt_bluedroid: get_profile_interface avrcp
,08-29 18:40:27.082  4177  4177 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 18:40:27.082  4177  4177 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 18:40:27.083  4177  4177 D A2dpStateMachine: make
,08-29 18:40:27.084  4177  4177 I bt_bluedroid: get_profile_interface a2dp
,08-29 18:40:27.084  4177  4193 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 18:40:27.088  4177  4208 D A2dpStateMachine: Enter Disconnected: -2
,08-29 18:40:27.088  4177  4177 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 18:40:27.091  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:27.091  4177  4177 D HidService: Received start request. Starting profile...
08-29 18:40:27.091  4177  4177 I bt_bluedroid: get_profile_interface hidhost
,08-29 18:40:27.091  4177  4193 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fc3e5
08-29 18:40:27.092  4177  4193 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 18:40:27.092  4177  4177 D HidService: setHidService(): set to: null
,08-29 18:40:27.093  4177  4177 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 18:40:27.094  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
08-29 18:40:27.095  4177  4177 D HealthService: Received start request. Starting profile...
,08-29 18:40:27.096  4177  4177 I bt_bluedroid: get_profile_interface health
,08-29 18:40:27.097  4177  4177 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 18:40:27.098  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:27.099  4177  4177 D PanService: Received start request. Starting profile...
08-29 18:40:27.099  4177  4177 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 18:40:27.099  4177  4177 I bt_bluedroid: get_profile_interface pan
,08-29 18:40:27.100  4177  4193 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 18:40:27.103  4177  4177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:27.103  4177  4177 D BluetoothMapService: Received start request. Starting profile...
08-29 18:40:27.104  4177  4177 D BluetoothMapService: start()
,08-29 18:40:27.106  4177  4177 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 18:40:27.107  4177  4177 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 18:40:27.107  4177  4177 D BluetoothMapAppObserver: createReceiver(),
08-29 18:40:27.108  4177  4177 D BluetoothMapAppObserver: initObservers()
,08-29 18:40:27.108  4177  4177 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 18:40:27.118  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:27.119  4177  4177 V BluetoothAdapterState: isTurningOff()=false
,08-29 18:40:27.120  4177  4177 V BluetoothAdapterState: isTurningOn()=true
,08-29 18:40:27.120  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:27.120  4177  4205 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5,
08-29 18:40:27.120  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:27.121  4177  4177 V BluetoothAdapterState: isTurningOff()=false
,08-29 18:40:27.122  4177  4177 V BluetoothAdapterState: isTurningOn()=true
08-29 18:40:27.122  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 18:40:27.122  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:27.122  4177  4177 V BluetoothAdapterState: isTurningOff()=false
,08-29 18:40:27.122  4177  4177 V BluetoothAdapterState: isTurningOn()=true
,08-29 18:40:27.122  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 18:40:27.122  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 18:40:27.123  4177  4177 V BluetoothAdapterState: isTurningOff()=false
,08-29 18:40:27.123  4177  4177 V BluetoothAdapterState: isTurningOn()=true
08-29 18:40:27.123  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
08-29 18:40:27.123  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:27.123  4177  4177 V BluetoothAdapterState: isTurningOff()=false
08-29 18:40:27.123  4177  4177 V BluetoothAdapterState: isTurningOn()=true
08-29 18:40:27.123  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 18:40:27.123  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:27.124  4177  4177 V BluetoothAdapterState: isTurningOff()=false
08-29 18:40:27.124  4177  4177 V BluetoothAdapterState: isTurningOn()=true
08-29 18:40:27.124  4177  4177 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 18:40:27.124  4177  4177 V BluetoothAdapterState: isBleTurningOff()=false
08-29 18:40:27.124  4177  4189 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 18:40:27.124  4177  4189 D BluetoothAdapterProperties: ScanMode =  20
08-29 18:40:27.124  4177  4189 D BluetoothAdapterProperties: State =  11
08-29 18:40:27.126  4177  4193 D BluetoothAdapterProperties: Scan Mode:21
,08-29 18:40:27.127  4177  4193 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 18:40:27.127  4177  4189 D BluetoothAdapterProperties: Setting state to 12
08-29 18:40:27.127  4177  4189 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 18:40:27.128   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:27.128  4177  4189 I BluetoothAdapterState: Entering OnState
08-29 18:40:27.129  3891  3904 D BluetoothMap: onBluetoothStateChange: up=true
08-29 18:40:27.129  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:27.129  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:27.129  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:27.129  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:27.129  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:27.129  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:27.129  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:27.129  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:27.131  1363  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 18:40:27.131  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:27.133  1363  2082 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 18:40:27.133  1363  1363 D BluetoothA2dp: Proxy object connected
08-29 18:40:27.133  3891  3891 D BluetoothMap: Proxy object connected
08-29 18:40:27.134  3891  3891 D MapProfile: Bluetooth service connected
08-29 18:40:27.134  3891  3891 D BluetoothMap: getConnectedDevices()
08-29 18:40:27.134  4177  4177 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 18:40:27.134  4177  4177 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 18:40:27.135  3891  3904 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:27.136  3891  3903 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 18:40:27.136  4177  4177 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:40:27.138  1363  1684 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 18:40:27.138  4177  4177 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:27.139  1363  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 18:40:27.139  4177  4177 D ObexServerSockets: Succeed to create listening sockets 
08-29 18:40:27.139  4177  4177 D ObexServerSockets0: startAccept()
08-29 18:40:27.139  4177  4177 D ObexServerSockets0: prepareForNewConnect()
08-29 18:40:27.141   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 18:40:27.142  4177  4177 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 18:40:27.142  3891  3904 D BluetoothPan: onBluetoothStateChange on: true
,08-29 18:40:27.142  4177  4177 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 18:40:27.142  4177  4214 D ObexServerSockets0: Accepting socket connection...
08-29 18:40:27.143  4177  4215 D ObexServerSockets0: Accepting socket connection...
08-29 18:40:27.143  1363  1363 D BluetoothInputDevice: Proxy object connected
,08-29 18:40:27.143  1363  1363 D HidProfile: Bluetooth service connected
08-29 18:40:27.144   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 18:40:27.144  1982  2297 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 18:40:27.145  1363  3824 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 18:40:27.147  1363  1363 D BluetoothMap: Proxy object connected
08-29 18:40:27.147  1363  1363 D MapProfile: Bluetooth service connected
,08-29 18:40:27.147  3891  3904 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 18:40:27.147  1363  1363 D BluetoothMap: getConnectedDevices()
,08-29 18:40:27.149   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 18:40:27.148  3891  3891 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 18:40:27.149  3891  3891 D PanProfile: Bluetooth service connected
08-29 18:40:27.149   874   874 D BluetoothA2dp: Proxy object connected
08-29 18:40:27.149  3891  3891 D BluetoothInputDevice: Proxy object connected
08-29 18:40:27.149  1363  1684 D BluetoothPan: onBluetoothStateChange on: true
08-29 18:40:27.149  3891  3891 D HidProfile: Bluetooth service connected
08-29 18:40:27.151  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 18:40:27.151  1363  1363 D PanProfile: Bluetooth service connected
08-29 18:40:27.151  3891  3904 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 18:40:27.154  3891  3891 D BluetoothA2dp: Proxy object connected
,08-29 18:40:27.154   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 18:40:27.155  4177  4177 D BluetoothMapService: onReceive
08-29 18:40:27.155  4177  4177 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:27.155  4177  4177 D BluetoothMapService: STATE_ON
,08-29 18:40:27.157  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:27.160  3891  3891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 18:40:27.166  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:27.167  3891  3891 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:27.176  3891  3891 D BluetoothPbap: Proxy object connected
,08-29 18:40:27.176  1363  1363 D BluetoothPbap: Proxy object connected
08-29 18:40:27.176  1363  1363 D PbapServerProfile: Bluetooth service connected
08-29 18:40:27.176  3891  3891 D PbapServerProfile: Bluetooth service connected
,08-29 18:40:27.182  4177  4177 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 18:40:27.182  4177  4177 D ObexServerSockets0: prepareForNewConnect()
,08-29 18:40:27.188   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 18:40:27.190  4177  4220 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:27.191  1878  1878 I Keyboard.Facilitator: onFinishInput()
,08-29 18:40:27.201   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 18:40:27.201   874   894 I Adreno  : Build Date                       : 10/20/15
08-29 18:40:27.201   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 18:40:27.201   874   894 I Adreno  : Local Branch                     : M14
08-29 18:40:27.201   874   894 I Adreno  : Remote Branch                    : 
08-29 18:40:27.201   874   894 I Adreno  : Remote Branch                    : 
08-29 18:40:27.201   874   894 I Adreno  : Reconstruct Branch               : 
,08-29 18:40:27.205  4177  4224 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:27.211  4177  4224 I BtOppRfcommListener: Accept thread started.
,08-29 18:40:27.223   280   348 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (141 us)
,08-29 18:40:27.229  1982  1993 D BluetoothHeadset: Proxy object connected
,08-29 18:40:27.234   874   874 D BluetoothHeadset: Proxy object connected
,08-29 18:40:27.236   874   874 D BluetoothHeadset: Proxy object connected
08-29 18:40:27.236  3891  3903 D BluetoothHeadset: Proxy object connected
,08-29 18:40:27.236  1363  1384 D BluetoothHeadset: Proxy object connected
08-29 18:40:27.237  1363  1363 D HeadsetProfile: Bluetooth service connected
08-29 18:40:27.237  3891  3904 D BluetoothHeadset: Proxy object connected
08-29 18:40:27.237  3891  3891 D HeadsetProfile: Bluetooth service connected
,08-29 18:40:27.237   874   874 D BluetoothHeadset: Proxy object connected
08-29 18:40:27.239  1363  3824 D BluetoothHeadset: Proxy object connected
08-29 18:40:27.240  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-29 18:40:27.240  3891  3891 D HeadsetProfile: Bluetooth service connected
08-29 18:40:27.241   874   891 D BluetoothHeadset: Proxy object connected
,08-29 18:40:27.245   874   891 D BluetoothHeadset: Proxy object connected
08-29 18:40:27.245  1982  2175 D BluetoothHeadset: Proxy object connected
,08-29 18:40:27.506  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:27.506  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:27.506  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:27.506  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:27.506  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:27.506  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:27.506  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:27.506  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:27.514  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:27.518  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:27.518  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee28f77 added. We now have 8 listener(s)
,08-29 18:40:27.519  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:27.525   874  1976 D WifiService: setWifiEnabled: false pid=3825, uid=10000
,08-29 18:40:27.525   874  1976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 18:40:27.535  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:27.536   874  1920 D WifiService: setWifiEnabled: true pid=3825, uid=10000
,08-29 18:40:27.536   874  1920 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 18:40:27.552   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-29 18:40:27.559  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:27.559  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:27.559  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:27.559  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:27.559  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:27.559  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:27.559  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:27.559  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:27.563  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:27.563  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:27.563  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:27.563  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:27.563  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:27.563  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:27.563  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:27.563  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:27.565  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:27.568  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:27.573  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 18:40:27.574  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 18:40:27.576  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a4989de Bundle[{}]
08-29 18:40:27.577  3825  3875 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 18:40:27.577  3825  3875 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 18:40:27.578  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 18:40:27.578  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 18:40:27.579  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 18:40:27.580  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 18:40:27.584  3825  3875 I System.out: Running OutgoingSocketThread
08-29 18:40:27.585  3825  4231 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
08-29 18:40:27.586  3825  4231 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43341
08-29 18:40:27.586  3825  4231 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-29 18:40:27.593   874  1308 D WifiConfigStore: loaded 0 passpoint configs
08-29 18:40:27.594   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 18:40:27.595   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 18:40:27.596   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 18:40:27.597   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 18:40:27.597   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 18:40:27.597   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-29 18:40:27.610   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 18:40:27.611   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.21 rxSuccessRate=0.18 delta 1000 -> 1000
08-29 18:40:27.611   372   872 D CommandListener: Setting iface cfg
08-29 18:40:27.611   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
08-29 18:40:27.612   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 18:40:27.614   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
08-29 18:40:27.619   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-29 18:40:27.620   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 18:40:27.620   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:40:27.628   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 18:40:27.699   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 18:40:27.701  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 18:40:27.805  3825  3825 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 18:40:27.805  3825  3825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 18:40:27.845   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 18:40:27.846  3825  3825 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a4989de Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@b3787e4, 16908290=android.view.AbsSavedState$1@b3787e4}, android:focusedViewId=100}]}]
,08-29 18:40:27.846  3825  3825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-29 18:40:27.846  3825  3825 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 18:40:27.846  3825  3825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 18:40:27.860   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 18:40:27.867   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-29 18:40:27.867   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 18:40:27.868   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 18:40:28.096   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0,
,08-29 18:40:28.100   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 18:40:28.101   874  1335 D SurfaceControl: Excessive delay in setPowerMode(): 237ms
08-29 18:40:28.105   874   894 I DreamManagerService: Entering dreamland.
08-29 18:40:28.106   874   894 I PowerManagerService: Dozing...
08-29 18:40:28.108   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 18:40:28.173   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 18:40:28.173   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 18:40:28.183   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 18:40:28.183  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e,
,08-29 18:40:28.190   874  1308 E native  : do suspend false
,08-29 18:40:28.196  1967  4233 D NfcService: Discovery configuration equal, not updating.
,08-29 18:40:28.205   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 18:40:28.211  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 18:40:28.211  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 18:40:28.229   874  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 18:40:28.230  1464  1464 E wpa_supplicant: PNO: In assoc process
,08-29 18:40:28.231   874  1308 E WifiStateMachine:  Fail to set up pno, want true now false
,08-29 18:40:28.234   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 18:40:28.238   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 18:40:28.238   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:40:28.238   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 18:40:28.247   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 18:40:28.255   372   872 D CommandListener: Setting iface cfg
,08-29 18:40:28.255   874  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 18:40:28.261   874  1308 E native  : do suspend true
,08-29 18:40:28.273   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 18:40:28.312   376  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 18:40:28.313   376  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 18:40:28.316   874  4238 D DhcpClient: Receive thread started
,08-29 18:40:28.410   874  1308 E native  : do suspend false
,08-29 18:40:28.432   874  2102 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 18:40:28.448   874  4238 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-29 18:40:28.449   874  2102 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-29 18:40:28.452   874  2102 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 18:40:28.472   874  4238 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 18:40:28.473   874  2102 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 18:40:28.478   372   872 D CommandListener: Setting iface cfg
,08-29 18:40:28.489   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 18:40:28.490   874  2102 D DhcpClient: Scheduling renewal in 86399s
08-29 18:40:28.491   874  1308 E native  : do suspend true
,08-29 18:40:28.509   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 18:40:28.509   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 18:40:28.510   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 18:40:28.512   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 18:40:28.513   874  1312 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 18:40:28.586  3825  3875 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,08-29 18:40:28.586   874  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 18:40:28.587  3825  3875 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,08-29 18:40:28.587   874  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 18:40:28.591   874  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 18:40:28.594   874  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 18:40:28.594  3825  3875 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,08-29 18:40:28.596  3825  3875 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 18:40:28.596  3825  3875 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-29 18:40:28.597   874  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 18:40:28.602  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 18:40:28.603  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64844d added. We now have 2 listener(s)
,08-29 18:40:28.609  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 18:40:28.609  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 18:40:28.609  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 18:40:28.610  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:28.610  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba9fb02 added. We now have 9 listener(s)
08-29 18:40:28.610  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-29 18:40:28.612  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:28.614   874  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 18:40:28.617  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:28.621  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:28.621  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:28.621  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:28.621  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:28.621  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:28.621  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:28.621  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:28.621  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:28.621   874  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-29 18:40:28.621   874  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-29 18:40:28.622   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 18:40:28.622   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
08-29 18:40:28.623  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:28.623   874  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 18:40:28.623   874  1312 D ConnectivityService:    accepting network in place of null
,08-29 18:40:28.623  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:28.624  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 18:40:28.624  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d73e50 added. We now have 3 listener(s)
,08-29 18:40:28.624   874  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 18:40:28.626  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 18:40:28.626  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 18:40:28.626  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:28.627  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:28.627  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a821849 added. We now have 10 listener(s)
,08-29 18:40:28.627  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:28.627  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:28.627  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:40:28.627  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:28.627  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:28.627  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:28.628  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:28.628  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 18:40:28.628  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64844d removed from the list
,08-29 18:40:28.628  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:28.628  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba9fb02 removed from the list
,08-29 18:40:28.628  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:28.628  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:28.628  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:28.628  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:28.628  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:28.628  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:28.628  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:28.628  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:28.630  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:28.631  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 18:40:28.631  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.631  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.632  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:28.633  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:28.633  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:28.633  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.633  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba9fb02 not in the list
,08-29 18:40:28.633  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:28.633  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:28.634  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:28.634  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:28.634  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:28.634  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:28.634  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a821849 removed from the list
08-29 18:40:28.634  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:28.634  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.634  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:28.634  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 18:40:28.635  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d73e50 removed from the list
,08-29 18:40:28.635  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 18:40:28.635  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e40c54e added. We now have 2 listener(s)
,08-29 18:40:28.637  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 18:40:28.637  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:28.637  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 18:40:28.637  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:28.638  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f66f added. We now have 9 listener(s)
,08-29 18:40:28.638  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:28.638  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 18:40:28.641  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:28.645  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:28.645  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:28.645  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:28.645  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:28.645  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:28.645  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:28.645  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:28.645  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:28.647  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:28.647  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:28.647  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:28.647  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2caf005 added. We now have 3 listener(s)
08-29 18:40:28.649  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 18:40:28.649  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:28.649  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:28.649  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:28.649  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:28.649  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e67e85a added. We now have 10 listener(s)
08-29 18:40:28.649  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:28.649  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:28.649  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:28.649  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:28.649  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:28.650  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:40:28.651  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:28.653  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 18:40:28.653  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 18:40:28.656  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 18:40:28.657  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 18:40:28.657  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 18:40:28.658   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 18:40:28.659  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 18:40:28.659  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 18:40:28.659  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 18:40:28.660  3825  3875 D BluetoothAdapter: STATE_ON
08-29 18:40:28.662  4177  4188 D BtGatt.GattService: registerClient() - UUID=6c1ca8a4-2820-4f17-bb73-67a878df6c5e
,08-29 18:40:28.663  4177  4193 D BtGatt.GattService: onClientRegistered() - UUID=6c1ca8a4-2820-4f17-bb73-67a878df6c5e, clientIf=5
08-29 18:40:28.663  3825  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 18:40:28.664  4177  4213 D BtGatt.GattService: start scan with filters
,08-29 18:40:28.666  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 18:40:28.666  4177  4196 D BtGatt.ScanManager: handling starting scan
08-29 18:40:28.667  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 18:40:28.667  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 18:40:28.667  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:40:28.668  4177  4196 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@558c863
,08-29 18:40:28.669  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 18:40:28.669  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 18:40:28.669  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 18:40:28.669  4177  4193 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 18:40:28.669  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.670  4177  4196 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 18:40:28.671  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:40:28.671  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 18:40:28.671  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.672  4177  4196 D BtGatt.ScanManager: Starting BLE batch scan
08-29 18:40:28.672  4177  4196 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 18:40:28.673  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 18:40:28.673  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:28.673  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 18:40:28.673  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:28.673  4177  4193 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 18:40:28.673  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 18:40:28.673  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.673  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 18:40:28.673  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 18:40:28.674  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:40:28.674  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:40:28.674  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 18:40:28.674  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 18:40:28.674  3825  3875 D BluetoothAdapter: STATE_ON
08-29 18:40:28.675  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 18:40:28.675  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.675  4177  4213 D BtGatt.GattService: stopScan() - queue size =1
,08-29 18:40:28.676  4177  4187 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 18:40:28.676  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 18:40:28.676  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:40:28.676  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 18:40:28.676  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:40:28.676  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 18:40:28.677  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:40:28.677  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 18:40:28.677  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:40:28.677  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:28.677  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 18:40:28.678  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:28.678  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:28.678  4177  4196 D BtGatt.ScanManager: stopping BLe Batch
,08-29 18:40:28.680  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 18:40:28.680  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:28.680  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.680  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:40:28.680  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:28.680  4177  4196 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 18:40:28.681  4177  4193 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 18:40:28.681  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:28.683  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:28.683  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:28.683  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:28.683  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:28.683  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.683  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:28.683  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:28.683  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e40c54e removed from the list
08-29 18:40:28.683  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.683  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f66f removed from the list
08-29 18:40:28.683  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:28.684  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:28.684  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.684  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.685  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:28.685  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 18:40:28.685  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.685  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@605f66f not in the list
08-29 18:40:28.685  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.685  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:28.686  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:28.686  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:28.686  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.686  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e67e85a removed from the list
08-29 18:40:28.686  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:28.686  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.686  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:28.686  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:28.686  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2caf005 removed from the list
08-29 18:40:28.687  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:28.687  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ac3026 added. We now have 2 listener(s)
,08-29 18:40:28.688  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 18:40:28.689  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:28.689  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:28.689  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:28.689  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4604467 added. We now have 9 listener(s)
08-29 18:40:28.689  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:28.689  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:28.689   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,08-29 18:40:28.691   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 18:40:28.691  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:28.693   874  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154639, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 18:40:28.695  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:28.695  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:28.695  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:28.695  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:28.695  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:28.695  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:28.695  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:28.695  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:28.695   874  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 18:40:28.695   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:28.698   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-29 18:40:28.702   874  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 18:40:28.703  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:28.703  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:28.703  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:28.704  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac1abd added. We now have 3 listener(s)
08-29 18:40:28.706  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 18:40:28.707  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 18:40:28.707  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:28.707  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:28.707  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79b28b2 added. We now have 10 listener(s)
08-29 18:40:28.707  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:28.707  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 18:40:28.710  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:28.710  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:28.710  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:28.710  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:28.710  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 18:40:28.711  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:28.713  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:28.714  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 18:40:28.714  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 18:40:28.718  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:40:28.719  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 18:40:28.719  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 18:40:28.719  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:28.719  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:28.719  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:28.719  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:28.719  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:28.719  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:28.719  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:28.719  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:28.721  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 18:40:28.722  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:28.722  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 18:40:28.722  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 18:40:28.722  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 18:40:28.723  3825  3875 D BluetoothAdapter: STATE_ON
08-29 18:40:28.724  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:28.725  4177  4187 D BtGatt.GattService: registerClient() - UUID=ecfb5e8c-b4a3-4608-a962-ec78941f024d
08-29 18:40:28.725  4177  4193 D BtGatt.GattService: onClientRegistered() - UUID=ecfb5e8c-b4a3-4608-a962-ec78941f024d, clientIf=5
,08-29 18:40:28.725  3825  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 18:40:28.726  4177  4206 D BtGatt.GattService: start scan with filters
08-29 18:40:28.726  1727  1727 D SystemUpdateService: onCreate
,08-29 18:40:28.728  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 18:40:28.728  4177  4196 D BtGatt.ScanManager: handling starting scan
08-29 18:40:28.728  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 18:40:28.728  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 18:40:28.728  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:40:28.729  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 18:40:28.730  4177  4193 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 18:40:28.730  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.730  4177  4196 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 18:40:28.730  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 18:40:28.730  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 18:40:28.730  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 18:40:28.731  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 18:40:28.731  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:28.731  4177  4196 D BtGatt.ScanManager: Starting BLE batch scan
08-29 18:40:28.731  4177  4196 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 18:40:28.732  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 18:40:28.733  4177  4193 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 18:40:28.733  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.735  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 18:40:28.735  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.735  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:28.735  3825  3875 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 18:40:28.735  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:28.735  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:28.735  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:28.736  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:28.736  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.736  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 18:40:28.736  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 18:40:28.736  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ac3026 removed from the list
08-29 18:40:28.736  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.736  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4604467 removed from the list
,08-29 18:40:28.736  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:28.736  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:28.737  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.737  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 18:40:28.737  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.737  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:28.738  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:28.738  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:28.738  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:28.738  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4604467 not in the list
08-29 18:40:28.738  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 18:40:28.738  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 18:40:28.738  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:40:28.738  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 18:40:28.738  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 18:40:28.739  3825  3875 D BluetoothAdapter: STATE_ON
08-29 18:40:28.739  4177  4188 D BtGatt.GattService: stopScan() - queue size =1
08-29 18:40:28.740  4177  4213 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 18:40:28.740  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:28.740  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 18:40:28.740  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 18:40:28.740  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:40:28.740  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 18:40:28.741  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 18:40:28.741  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.741  4177  4196 D BtGatt.ScanManager: stopping BLe Batch
08-29 18:40:28.741  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:40:28.741  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 18:40:28.741  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:40:28.741  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:28.741  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.742  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:40:28.742  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:28.742  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:28.743  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:28.743  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:28.743  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.743  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 18:40:28.743  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:28.743  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79b28b2 removed from the list
08-29 18:40:28.743  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:28.743  4177  4196 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 18:40:28.743  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.743  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.743  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:28.743  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac1abd removed from the list
08-29 18:40:28.744  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 18:40:28.744  4177  4193 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 18:40:28.744  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10f1dfe added. We now have 2 listener(s)
08-29 18:40:28.744  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:28.745  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 18:40:28.745  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:28.745  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 18:40:28.746  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:28.746  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f07595f added. We now have 9 listener(s)
08-29 18:40:28.746  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:28.746  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:28.747  1727  4249 I SystemUpdateService: active receiver: enabled
,08-29 18:40:28.748  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:28.749  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-29 18:40:28.751  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:28.751  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:28.751  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:28.751  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:28.751  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:28.751  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:28.751  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:28.751  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:40:28.753  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:28.753  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:28.754  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:28.754  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c0e475 added. We now have 3 listener(s)
08-29 18:40:28.754  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:28.756  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:28.756  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 18:40:28.757  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:28.757  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 18:40:28.757  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:28.757  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1c0a added. We now have 10 listener(s)
08-29 18:40:28.757  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:28.757  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:28.757  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:28.757  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:28.757  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-29 18:40:28.757  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 18:40:28.759  1727  2513 I iu.UploadsManager: num queued entries: 0,
08-29 18:40:28.759  1727  2513 I iu.UploadsManager: num updated entries: 0
08-29 18:40:28.760  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 18:40:28.760  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 18:40:28.763  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:40:28.763  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 18:40:28.763  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 18:40:28.764  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 18:40:28.765  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 18:40:28.766  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 18:40:28.766  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 18:40:28.767  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 18:40:28.767  3825  3875 D BluetoothAdapter: STATE_ON
08-29 18:40:28.767  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:28.769  4177  4188 D BtGatt.GattService: registerClient() - UUID=b1785600-1ca2-45f4-b3f2-1cc233823cbb
,08-29 18:40:28.769  4177  4193 D BtGatt.GattService: onClientRegistered() - UUID=b1785600-1ca2-45f4-b3f2-1cc233823cbb, clientIf=5
08-29 18:40:28.769  3825  3836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 18:40:28.769  4177  4213 D BtGatt.GattService: start scan with filters
,08-29 18:40:28.771  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 18:40:28.772  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 18:40:28.772  4177  4196 D BtGatt.ScanManager: handling starting scan
,08-29 18:40:28.772  3960  3960 D SprintDMHelper: simOperator: 
08-29 18:40:28.772  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 18:40:28.772  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 18:40:28.772  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:40:28.773  4177  4193 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 18:40:28.774  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.774  4177  4196 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 18:40:28.774  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 18:40:28.774  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 18:40:28.774  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 18:40:28.775  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 18:40:28.775  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.775  4177  4196 D BtGatt.ScanManager: Starting BLE batch scan
08-29 18:40:28.775  4177  4196 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
08-29 18:40:28.776  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:40:28.778  4177  4193 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 18:40:28.778  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:28.779  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 18:40:28.779  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:28.780  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:28.780  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:28.780  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:28.780  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:28.780  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.781  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 18:40:28.781  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:28.781  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10f1dfe removed from the list
08-29 18:40:28.781  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:28.781  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f07595f removed from the list
08-29 18:40:28.781  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:28.781  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:28.782  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.782  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 18:40:28.782  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.782  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:28.784  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:28.784  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:28.784  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.784  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f07595f not in the list
08-29 18:40:28.784  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 18:40:28.784  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:40:28.784  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:40:28.784  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 18:40:28.784  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 18:40:28.784  3825  3875 D BluetoothAdapter: STATE_ON
08-29 18:40:28.785  4177  4206 D BtGatt.GattService: stopScan() - queue size =1
08-29 18:40:28.786  4177  4187 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 18:40:28.786  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:28.786  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:40:28.786  4177  4193 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 18:40:28.786  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 18:40:28.786  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.786  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:40:28.787  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 18:40:28.787  4177  4196 D BtGatt.ScanManager: stopping BLe Batch
08-29 18:40:28.787  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:28.787  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 18:40:28.787  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:40:28.787  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 18:40:28.788  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.789  4177  4193 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 18:40:28.789  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:40:28.789  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:28.789  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 18:40:28.789  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:28.789  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:28.789  4177  4196 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 18:40:28.789  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:28.789  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.789  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1c0a removed from the list
,08-29 18:40:28.789  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:28.789  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.789  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.789  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:28.789  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c0e475 removed from the list
08-29 18:40:28.790  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:28.790  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@176eed6 added. We now have 2 listener(s)
08-29 18:40:28.790  4177  4193 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 18:40:28.790  4177  4193 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 18:40:28.793  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 18:40:28.793  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:28.793  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:28.793  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:28.793  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bed1557 added. We now have 9 listener(s)
08-29 18:40:28.793  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:28.795  1727  4252 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 18:40:28.795  1727  4252 W BaseAppContext: Using Auth Proxy for data requests.
08-29 18:40:28.797  1727  4252 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
08-29 18:40:28.797  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:28.798  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:28.802  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:28.802  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:28.802  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:28.802  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:28.802  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:28.802  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:40:28.802  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:40:28.802  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:40:28.803  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:40:28.803  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:28.804  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:28.804  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fe2d2d added. We now have 3 listener(s)
08-29 18:40:28.804   874  4236 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:816::200e
,08-29 18:40:28.805  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:28.806  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 18:40:28.806  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:28.806  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:28.806  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:28.806  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccb2262 added. We now have 10 listener(s)
08-29 18:40:28.807  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:28.807  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:28.807  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:28.807  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:28.807  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:28.807  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:28.807  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.807  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:28.807  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:28.808  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@176eed6 removed from the list
08-29 18:40:28.808  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.808  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 18:40:28.808  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bed1557 removed from the list
,08-29 18:40:28.808  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:28.808  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.808  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.809  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.809  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 18:40:28.810  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:28.810  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:28.810  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.810  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bed1557 not in the list
08-29 18:40:28.810  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.811  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.812  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:28.812  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:28.812  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:28.812  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccb2262 removed from the list
08-29 18:40:28.812  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:28.812  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:28.812  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:28.812  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:28.812  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fe2d2d removed from the list
08-29 18:40:28.813  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 18:40:28.813  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 18:40:28.813  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 18:40:28.813  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:28.813  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 18:40:28.813  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:40:28.819  3825  4257 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
,08-29 18:40:28.819  3825  4257 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
08-29 18:40:28.819  1727  4249 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-29 18:40:28.819  3825  4257 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 18:40:28.821  3825  4258 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
,08-29 18:40:28.821  3825  4258 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
08-29 18:40:28.821  3825  4258 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 18:40:28.823  3825  3875 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 18:40:28.823  3825  3875 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 18:40:28.823  3825  3875 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 18:40:28.823  3825  3875 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 18:40:28.823  3825  3875 D com.test.thalitest.ThaliTestRunner: Total duration: 21854 ms
,08-29 18:40:28.824  3825  3875 I jxcore-log: *Native tests were executed*
08-29 18:40:28.824  3825  3875 I jxcore-log: 
08-29 18:40:28.824  3825  3875 I jxcore-log: Total number of executed tests:  80
08-29 18:40:28.824  3825  3875 I jxcore-log: 
08-29 18:40:28.825  3825  3875 I jxcore-log: Number of passed tests:  80
08-29 18:40:28.825  3825  3875 I jxcore-log: 
08-29 18:40:28.825  3825  3875 I jxcore-log: Number of failed tests:  0
08-29 18:40:28.825  3825  3875 I jxcore-log: 
,08-29 18:40:28.825  3825  3875 I jxcore-log: Number of ignored tests:  0
08-29 18:40:28.825  3825  3875 I jxcore-log: 
,08-29 18:40:28.825  3825  3875 I jxcore-log: Total duration:  21854
08-29 18:40:28.825  3825  3875 I jxcore-log: 
08-29 18:40:28.826  3825  3875 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 18:40:28.826  3825  3875 I jxcore-log: 
,08-29 18:40:28.827  1727  2513 I iu.SyncManager: NEXT; no task
08-29 18:40:28.828  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.828  3825  3875 I jxcore-log: 
08-29 18:40:28.830  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.830  3825  3875 I jxcore-log: 
08-29 18:40:28.832  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.832  3825  3875 I jxcore-log: 
08-29 18:40:28.833  1727  4249 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 18:40:28.833  1727  4249 I SystemUpdateService: now status is 0 (complete)
08-29 18:40:28.833  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.833  3825  3875 I jxcore-log: 
08-29 18:40:28.834  3825  3825 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 18:40:28.834  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.834  3825  3875 I jxcore-log: 
08-29 18:40:28.833  1727  4249 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 18:40:28.837  1727  4249 I SystemUpdateService: file has been verified
08-29 18:40:28.837  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.837  3825  3875 I jxcore-log: 
,08-29 18:40:28.839  1727  4249 I SystemUpdateService: OTA package size = 12249756
08-29 18:40:28.840  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.840  3825  3875 I jxcore-log: 
08-29 18:40:28.842  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:28.842  3825  3875 I jxcore-log: 
08-29 18:40:28.844  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:28.844  3825  3875 I jxcore-log: 
,08-29 18:40:28.847  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.847  3825  3875 I jxcore-log: 
,08-29 18:40:28.849  1500  2087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 18:40:28.849  1500  2087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 18:40:28.849  1500  2087 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 18:40:28.849  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.849  3825  3875 I jxcore-log: 
08-29 18:40:28.849  1500  2087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 18:40:28.850  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 18:40:28.850  3825  3875 I jxcore-log: 
,08-29 18:40:28.852  1727  4249 I SystemUpdateService: showing system update notification
08-29 18:40:28.852  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:28.852  3825  3875 I jxcore-log: 
,08-29 18:40:28.853  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:28.853  3825  3875 I jxcore-log: 
,08-29 18:40:28.854  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.854  3825  3875 I jxcore-log: 
,08-29 18:40:28.855  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.855  3825  3875 I jxcore-log: 
,08-29 18:40:28.856  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.856  3825  3875 I jxcore-log: 
,08-29 18:40:28.858  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.858  3825  3875 I jxcore-log: 
,08-29 18:40:28.859  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.859  3825  3875 I jxcore-log: 
,08-29 18:40:28.859  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.859  3825  3875 I jxcore-log: 
,08-29 18:40:28.860  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.860  3825  3875 I jxcore-log: 
,08-29 18:40:28.862  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.862  3825  3875 I jxcore-log: 
,08-29 18:40:28.863  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.863  3825  3875 I jxcore-log: 
,08-29 18:40:28.864  1727  4252 E MDM     : [183] SitrepService.a: Error sending sitrep.
08-29 18:40:28.864  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:28.864  3825  3875 I jxcore-log: 
,08-29 18:40:28.865  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:28.865  3825  3875 I jxcore-log: 
,08-29 18:40:28.866  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:28.866  3825  3875 I jxcore-log: 
,08-29 18:40:28.867  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.867  3825  3875 I jxcore-log: 
,08-29 18:40:28.868  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:28.868  3825  3875 I jxcore-log: 
,08-29 18:40:28.868  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.868  3825  3875 I jxcore-log: 
,08-29 18:40:28.869  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.869  3825  3875 I jxcore-log: 
,08-29 18:40:28.870  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.870  3825  3875 I jxcore-log: 
,08-29 18:40:28.871  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.871  3825  3875 I jxcore-log: 
08-29 18:40:28.871  1727  1727 D SystemUpdateService: onDestroy
08-29 18:40:28.872  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:28.872  3825  3875 I jxcore-log: 
,08-29 18:40:28.908   874  4236 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 16:40:28 GMT], X-Android-Received-Millis=[1472488828908], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472488828857]}
,08-29 18:40:28.909   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 18:40:28.909   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-29 18:40:28.909   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 18:40:28.911   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 18:40:28.959  3092  4254 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 18:40:29.181  3825  3825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 18:40:29.183  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 18:40:29.183  3825  3875 I jxcore-log: 
,08-29 18:40:29.243  3825  3825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 18:40:29.245  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 18:40:29.245  3825  3875 I jxcore-log: 
,08-29 18:40:29.289  3825  3825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 18:40:29.292  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 18:40:29.292  3825  3875 I jxcore-log: 
,08-29 18:40:29.511  4260  4260 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 18:40:29.516  4260  4260 D AndroidRuntime: CheckJNI is OFF
,08-29 18:40:29.559  4260  4260 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 18:40:29.607  4260  4260 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 18:40:29.630  4260  4260 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 18:40:29.639   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 18:40:29.640   874   887 I ActivityManager: Killing 3825:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 18:40:29.697   874  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 18:40:29.738   874  1919 D GraphicsStats: Buffer count: 2
,08-29 18:40:29.739   874  1920 I WindowState: WIN DEATH: Window{ff8fef2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 18:40:29.740   874  1310 D WifiService: Client connection lost with reason: 4
,08-29 18:40:29.764   874   897 W PackageSettings: Skipping PackageSetting{f5b44 com.example.hello/10273} due to missing metadata
,08-29 18:40:29.797   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 18:40:29.797   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 18:40:29.797   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-29 18:40:29.797   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 18:40:29.797   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:29.797   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:29.797   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 18:40:29.797   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 18:40:29.798   874   887 I ActivityManager:   Force finishing activity ActivityRecord{3e68beb u0 com.test.thalitest/.MainActivity t2}
,08-29 18:40:29.799   874   897 I art     : Starting a blocking GC Explicit
,08-29 18:40:29.805   874  1966 W ActivityManager: Spurious death for ProcessRecord{61acd5d 0:com.test.thalitest/u0a0}, curProc for 3825: null
,08-29 18:40:29.864   874   897 I art     : Explicit concurrent mark sweep GC freed 41554(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 1.109ms total 63.018ms
,08-29 18:40:29.899   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 18:40:29.903  4260  4260 I art     : System.exit called, status: 0
,08-29 18:40:29.903  4260  4260 I AndroidRuntime: VM exiting with result code 0.
,08-29 18:40:29.909   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 18:40:29.941   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 18:40:29.950  4177  4177 D BluetoothMapAppObserver: onReceive
,08-29 18:40:29.950  4177  4177 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 18:40:29.951  1907  2268 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 18:40:29.953  1878  1878 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 18:40:29.955  3669  3669 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 18:40:29.962  1878  4276 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 18:40:29.977   874  2174 I ActivityManager: Start proc 4277:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 18:40:29.982   874  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 18:40:29.991  1878  4276 I Decoder : createOrResetDecoder
,08-29 18:40:30.026  1982  1982 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 18:40:30.034  4277  4277 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 18:40:30.036  1500  1500 I ConfigService: onCreate
,08-29 18:40:30.050  1878  4276 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 18:40:30.060   874  1974 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3825 uid 10000
,08-29 18:40:30.061  1878  1878 I Keyboard.Facilitator: onFinishInput()
,08-29 18:40:30.078   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 18:40:30.087   874  1336 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
08-29 18:40:30.088   874  1336 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-29 18:40:30.088   874  1336 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,08-29 18:40:30.088   874  1336 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-29 18:40:30.088   874  1336 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-29 18:40:30.088   874  1336 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-29 18:40:30.088   874  1336 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-29 18:40:30.088   874  1336 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-29 18:40:30.088   874  1336 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-29 18:40:30.088   874  1336 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-29 18:40:30.088   874  1336 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-29 18:40:30.088   874  1336 W System.err: 	... 4 more
08-29 18:40:30.088   874  1336 D skia    : ------- write threw an exception
,08-29 18:40:30.095  1878  4276 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 18:40:30.097  1878  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-29 18:40:30.097  1878  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 18:40:30.099  1878  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 18:40:30.099  1878  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 18:40:30.100  1878  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-29 18:40:30.101  1878  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-29 18:40:30.101  1996  2089 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-29 18:40:30.102   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 18:40:30.102   874   886 E PackageManager: Failed to write settings, restoring backup
08-29 18:40:30.102   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 18:40:30.102   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 18:40:30.102   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 18:40:30.102   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 18:40:30.102   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 18:40:30.102   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.102   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.102   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 18:40:30.106   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-29 18:40:30.106   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 18:40:30.106   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 18:40:30.106   874   887 E DropBoxManagerService: 	... 13 more
08-29 18:40:30.106  1878  4276 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-29 18:40:30.106  1878  4276 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 18:40:30.106  1878  4276 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 18:40:30.106  1878  4276 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 18:40:30.106  1878  4276 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-29 18:40:30.106  1878  4276 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-29 18:40:30.114   874   885 I ActivityManager: Start proc 4295:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-29 18:40:30.114  1996  2089 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 18:40:30.114  1996  2089 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1996
08-29 18:40:30.114  1996  2089 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.114  1996  2089 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 18:40:30.116   874  1965 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 18:40:30.116   874  4300 E DropBoxManagerService: Can't write: system_app_crash
08-29 18:40:30.116   874  4300 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 18:40:30.116   874  4300 E DropBoxManagerService: 	... 5 more
08-29 18:40:30.119  1996  2089 I Process : Sending signal. PID: 1996 SIG: 9
08-29 18:40:30.127  4277  4277 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 18:40:30.149   874  1976 I ActivityManager: Start proc 4310:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-29 18:40:30.162  4277  4309 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 18:40:30.184  4310  4310 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 18:40:30.198   874  1966 D GraphicsStats: Buffer count: 1
,08-29 18:40:30.198   874  2001 I WindowState: WIN DEATH: Window{8dce7fa u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-29 18:40:30.203  1500  1500 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-29 18:40:30.205  1500  1500 D AndroidRuntime: Shutting down VM
,08-29 18:40:30.206  1500  1500 E AndroidRuntime: FATAL EXCEPTION: main
08-29 18:40:30.206  1500  1500 E AndroidRuntime: Process: com.google.process.gapps, PID: 1500
08-29 18:40:30.206  1500  1500 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 18:40:30.206  1500  1500 E AndroidRuntime: 	... 8 more
,08-29 18:40:30.210   874  2002 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1996) has died
,08-29 18:40:30.212   874  2002 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-29 18:40:30.214   874  2002 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 18:40:30.228  4277  4293 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.228  4277  4293 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.228  4277  4293 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 18:40:30.235   874   887 I ActivityManager: Start proc 4327:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 18:40:30.242  1500  1500 I Process : Sending signal. PID: 1500 SIG: 9
,08-29 18:40:30.242   874  4335 E DropBoxManagerService: Can't write: system_app_crash
08-29 18:40:30.242   874  4335 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 18:40:30.242   874  4335 E DropBoxManagerService: 	... 5 more
,08-29 18:40:30.262  1727  4333 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,08-29 18:40:30.262  1727  4333 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@b238
08-29 18:40:30.263   874  1974 I ActivityManager: Process com.google.process.gapps (pid 1500) early provider death
,08-29 18:40:30.271   874  1310 D WifiService: Client connection lost with reason: 4
,08-29 18:40:30.273   874  1974 I ActivityManager: Process com.google.process.gapps (pid 1500) has died
,08-29 18:40:30.274   874  1974 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-29 18:40:30.274   874  1974 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-29 18:40:30.274   874  1974 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
08-29 18:40:30.274   874  1974 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
08-29 18:40:30.276   874  2174 W ActivityManager: Spurious death for ProcessRecord{2e0c54d 0:com.google.process.gapps/u0a11}, curProc for 1500: null
,08-29 18:40:30.289   874  1966 I ActivityManager: Start proc 4341:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-29 18:40:30.290  4327  4327 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:30.290  4327  4327 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:30.290  4327  4327 D AndroidRuntime: Shutting down VM
,08-29 18:40:30.297  1727  1727 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-29 18:40:30.307  4327  4327 E AndroidRuntime: FATAL EXCEPTION: main
08-29 18:40:30.307  4327  4327 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4327
08-29 18:40:30.307  4327  4327 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 18:40:30.307  4327  4327 E AndroidRuntime: 	... 10 more
08-29 18:40:30.308   874  1383 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 18:40:30.311   874  4354 E DropBoxManagerService: Can't write: system_app_crash
08-29 18:40:30.311   874  4354 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 18:40:30.311   874  4354 E DropBoxManagerService: 	... 5 more
08-29 18:40:30.315  4327  4327 I Process : Sending signal. PID: 4327 SIG: 9
08-29 18:40:30.323  4277  4293 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-29 18:40:30.323  4341  4341 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-29 18:40:30.328  4341  4341 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:30.330  4341  4341 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:30.330  4341  4341 D AndroidRuntime: Shutting down VM
08-29 18:40:30.331  4341  4341 E AndroidRuntime: FATAL EXCEPTION: main
08-29 18:40:30.331  4341  4341 E AndroidRuntime: Process: com.google.process.gapps, PID: 4341
08-29 18:40:30.331  4341  4341 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 18:40:30.331  4341  4341 E AndroidRuntime: 	... 10 more
08-29 18:40:30.334   874  4356 E DropBoxManagerService: Can't write: system_app_crash
08-29 18:40:30.334   874  4356 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 18:40:30.334   874  4356 E DropBoxManagerService: 	... 5 more
08-29 18:40:30.335  4341  4341 I Process : Sending signal. PID: 4341 SIG: 9
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.337  4277  4309 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 18:40:30.337  4277  4309 E AndroidRuntime: Process: android.process.acore, PID: 4277
08-29 18:40:30.337  4277  4309 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 18:40:30.337  4277  4309 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: Can't write: system_app_crash
08-29 18:40:30.339   874  4357 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 18:40:30.339   874  4357 E DropBoxManagerService: 	... 5 more
08-29 18:40:30.340  4277  4309 I Process : Sending signal. PID: 4277 SIG: 9
08-29 18:40:30.341  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-29 18:40:30.341  1727  1727 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 18:40:30.345   874   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4327) has died
08-29 18:40:30.347  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 18:40:30.347  1727  1727 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 18:40:30.347   874   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 18:40:30.353  1727  4358 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-29 18:40:30.363   874   887 I ActivityManager: Start proc 4359:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 18:40:30.368   874  1965 I ActivityManager: Process com.google.process.gapps (pid 4341) has died
08-29 18:40:30.368   874  1965 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{633f7f5 u0 com.google.android.gms/.config.ConfigService}
08-29 18:40:30.368   874  1965 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{40fcec4 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-29 18:40:30.369   874  1965 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{3fdc49c u0 com.google.android.gms/.auth.GetToken}
08-29 18:40:30.369   874  1965 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{184802a u0 com.google.android.gms/.gcm.GcmService}
08-29 18:40:30.381  1727  4358 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-29 18:40:30.381  1727  4358 E AndroidRuntime: Process: com.google.android.gms, PID: 1727
08-29 18:40:30.381  1727  4358 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 18:40:30.381  1727  4358 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-29 18:40:30.381   874  1965 I ActivityManager: Start proc 4373:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-29 18:40:30.384   278   278 E lowmemorykiller: Error writing /proc/4277/oom_score_adj; errno=22
08-29 18:40:30.384   874  4379 E DropBoxManagerService: Can't write: system_app_crash
08-29 18:40:30.384   874  4379 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 18:40:30.384   874  4379 E DropBoxManagerService: 	... 5 more
08-29 18:40:30.390   278   278 E lowmemorykiller: Error writing /proc/4277/oom_score_adj; errno=22
08-29 18:40:30.395  1727  4358 I Process : Sending signal. PID: 1727 SIG: 9
08-29 18:40:30.399   278   278 E lowmemorykiller: Error writing /proc/4277/oom_score_adj; errno=22
08-29 18:40:30.402  2060  4366 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE

```
