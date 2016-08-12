#### Test 81095569a7966ce_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-12 14:11:06.662  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 14:11:06.688  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 14:11:06.697  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 14:11:06.789  1507  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 14:11:06.789  1507  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 14:11:06.789  1507  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 14:11:06.790  1507  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 14:11:06.829  3532  3532 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 14:11:06.829  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 14:11:06.830  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
08-12 14:11:07.365  3815  3815 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 14:11:07.370  3815  3815 D AndroidRuntime: CheckJNI is OFF
08-12 14:11:07.406  3815  3815 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 14:11:07.449  3815  3815 I Radio-JNI: register_android_hardware_Radio DONE
08-12 14:11:07.470  3815  3815 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 14:11:07.478   871  2002 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 14:11:07.519  1980  1990 W SearchService: Abort, client detached.
08-12 14:11:07.521  1980  1980 I HotwordDetector: Closing mic
08-12 14:11:07.522  1980  2311 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1c28238
08-12 14:11:07.523  1980  2330 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 14:11:07.535  3815  3815 D AndroidRuntime: Shutting down VM
08-12 14:11:07.568   871  3071 I ActivityManager: Start proc 3825:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 14:11:07.579   376  2333 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 14:11:07.581   376  2333 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 14:11:07.588   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 14:11:07.590  1980  2327 I MicroRecognitionRnrImpl: Detection finished
08-12 14:11:07.591  1980  2318 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 14:11:07.658  3825  3825 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 14:11:07.688  3825  3825 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 14:11:07.705  3825  3825 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 9954-9964)
08-12 14:11:07.706  3825  3825 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 14:11:07.750  3825  3825 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4c6f7bb}
08-12 14:11:07.751  3825  3825 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 14:11:07.751  3825  3825 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 14:11:07.761  3825  3825 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 14:11:07.762  3825  3825 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 14:11:07.782  3825  3825 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-12 14:11:07.798  3825  3825 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 14:11:07.798  3825  3825 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 14:11:07.799  3825  3825 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 14:11:07.799  3825  3825 I Adreno  : Build Date                       : 10/20/15
08-12 14:11:07.799  3825  3825 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 14:11:07.799  3825  3825 I Adreno  : Local Branch                     : M14
08-12 14:11:07.799  3825  3825 I Adreno  : Remote Branch                    : 
08-12 14:11:07.799  3825  3825 I Adreno  : Remote Branch                    : 
08-12 14:11:07.799  3825  3825 I Adreno  : Reconstruct Branch               : 
,08-12 14:11:07.894   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22daacb:true
,08-12 14:11:07.966  3825  3825 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 14:11:07.982  3825  3825 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-12 14:11:08.027  3825  3864 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 14:11:08.036  3825  3850 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 14:11:08.071  3825  3864 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 14:11:08.160   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +624ms
,08-12 14:11:08.165  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-12 14:11:08.240  3825  3825 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3825
,08-12 14:11:08.389   871   882 I ActivityManager: Killing 3224:com.google.android.gm/u0a78 (adj 15): empty #17
,08-12 14:11:08.438  3825  3825 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 14:11:08.445   871   882 I ActivityManager: Killing 2975:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-12 14:11:08.537   871  2077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120796, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:11:08.538  3825  3866 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1694959312
,08-12 14:11:08.542  3825  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 14:11:08.542  3825  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 14:11:08.542  3825  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 14:11:08.542  3825  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 14:11:08.542  3825  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 14:11:08.542  3825  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bd934f added. We now have 1 listener(s)
,08-12 14:11:08.546  3825  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-12 14:11:08.550  3825  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 14:11:08.551  3825  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 14:11:08.552  3825  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 14:11:08.556  3825  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ce52ba added. We now have 1 listener(s)
08-12 14:11:08.556  3825  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:08.559   871  1309 D WifiService: New client listening to asynchronous messages
,08-12 14:11:08.561  3825  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 14:11:08.561  3825  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 14:11:08.561  3825  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-12 14:11:08.562  3825  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-12 14:11:08.562  3825  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 14:11:08.565  3825  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:08.565  3825  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-12 14:11:08.574  3825  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 14:11:08.574  3825  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:08.574  3825  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:08.574  3825  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:08.574  3825  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:08.574  3825  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:08.574  3825  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:08.574  3825  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:08.574  3825  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 14:11:08.574  3825  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-12 14:11:08.574  3825  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 14:11:08.575  3825  3866 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 14:11:08.752  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:08.758  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:08.762  3825  3825 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 14:11:09.295  3825  3875 W jxcore-log: Initializing JXcore engine
08-12 14:11:09.295  3825  3875 W jxcore-log: JXcore engine is ready
,08-12 14:11:09.331  3875  3875 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8952 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 14:11:09.331  3875  3875 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10842]" dev="sockfs" ino=10842 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 14:11:09.331  3875  3875 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-12 14:11:09.331  3875  3875 W Thread-337: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[27678]" dev="sockfs" ino=27678 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 14:11:09.347  3825  3875 W jxcore-log: Starting JXcore engine
,08-12 14:11:09.427  3825  3875 W jxcore-log: Platform android
08-12 14:11:09.427  3825  3875 W jxcore-log: 
,08-12 14:11:09.427  3825  3875 W jxcore-log: Process ARCH arm
08-12 14:11:09.427  3825  3875 W jxcore-log: 
,08-12 14:11:09.594  3825  3875 I jxcore-log: JXcore Cordova bridge is ready!
08-12 14:11:09.594  3825  3875 I jxcore-log: 
,08-12 14:11:09.594  3825  3875 W jxcore-log: JXcore engine is started
,08-12 14:11:09.606  3825  3866 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 14:11:09.612  3825  3825 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 14:11:11.907   871  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 14:11:16.453  3607  3882 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 14:11:16.493  3607  3883 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 14:11:16.508  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:16.514  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:16.544  1507  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 14:11:16.544  1507  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 14:11:16.545  1507  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 14:11:16.545  1507  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 14:11:16.582  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:16.585  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:16.623  1507  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 14:11:16.623  1507  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 14:11:16.624  1507  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 14:11:16.624  1507  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 14:11:16.657  3607  3883 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 14:11:16.658  3607  3882 E BooksSync: Soft error
08-12 14:11:16.658  3607  3882 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 14:11:16.658  3607  3882 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 14:11:16.658  3607  3882 E BooksSync: Sync error
08-12 14:11:16.658  3607  3882 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 14:11:16.658  3607  3882 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 14:11:16.658  3607  3882 I BooksSync: Finished books sync
,08-12 14:11:16.666   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128648, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 14:11:19.656  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 14:11:19.656  3825  3875 I jxcore-log: 
,08-12 14:11:19.659  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 14:11:19.659  3825  3875 I jxcore-log: 
,08-12 14:11:19.671  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:19.671  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:19.671  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:19.671  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:19.671  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:19.671  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:19.671  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:19.671  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:19.677  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:19.679  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 14:11:19.679  3825  3875 I jxcore-log: 
,08-12 14:11:19.681  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 14:11:19.681  3825  3875 I jxcore-log: 
,08-12 14:11:20.003  3825  3875 D ExecuteNativeTests: Running unit tests
,08-12 14:11:20.061  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-12 14:11:20.061  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd added. We now have 2 listener(s)
,08-12 14:11:20.062  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 14:11:20.062  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 14:11:20.062  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 14:11:20.062  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 14:11:20.062  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 added. We now have 2 listener(s)
,08-12 14:11:20.062  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:20.063  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 14:11:20.065  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 14:11:20.079  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:20.079  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.079  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.079  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:20.079  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:20.079  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:20.079  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:20.079  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:20.084  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:20.085  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 14:11:20.091  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:20.093  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-12 14:11:20.093  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-12 14:11:20.093  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-12 14:11:20.097  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:20.098  3825  3875 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-12 14:11:20.099  3825  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-12 14:11:20.099  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-12 14:11:20.100  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-12 14:11:20.100  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-12 14:11:20.101  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.102  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.102  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.103  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:20.103  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.103  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:20.104  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-12 14:11:20.104  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd removed from the list
08-12 14:11:20.104  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.104  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 removed from the list
08-12 14:11:20.105  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.105  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.106  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.106  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-12 14:11:20.110  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.111  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.111  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.111  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.115  3825  3875 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-12 14:11:20.115  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 14:11:20.115  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.115  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.116  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.116  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.116  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.116  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.116  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.116  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.116  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.116  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.116  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.116  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.116  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.120  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.120  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.120  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.121  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
,08-12 14:11:20.140  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-12 14:11:20.141  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-12 14:11:20.141  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-12 14:11:20.141  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-12 14:11:20.141  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-12 14:11:20.141  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-12 14:11:20.142  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-12 14:11:20.142  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-12 14:11:20.142  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-12 14:11:20.142  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-12 14:11:20.143  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-12 14:11:20.143  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-12 14:11:20.143  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-12 14:11:20.144  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-12 14:11:20.144  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-12 14:11:20.144  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-12 14:11:20.144  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-12 14:11:20.144  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-12 14:11:20.144  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-12 14:11:20.144  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-12 14:11:20.144  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-12 14:11:20.145  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-12 14:11:20.145  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.145  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.145  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.146  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.146  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.146  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.146  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.146  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.146  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.146  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.146  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.146  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.146  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.146  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.148  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.148  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.148  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.148  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.149  3825  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-12 14:11:20.150  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:20.156  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:20.156  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.156  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.156  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:20.156  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:20.156  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:20.156  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:20.156  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 14:11:20.158  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:20.158  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 14:11:20.158  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 14:11:20.158  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 14:11:20.159  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 14:11:20.159  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:20.159  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-12 14:11:20.160  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:20.163  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 14:11:20.163  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-12 14:11:20.163  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:20.169  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-12 14:11:20.172  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 14:11:20.172  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 14:11:20.177  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-12 14:11:20.181  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-12 14:11:20.181  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 14:11:20.181  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 14:11:20.182  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 14:11:20.183  3825  3875 D BluetoothAdapter: STATE_ON
08-12 14:11:20.189  2688  2702 D BtGatt.GattService: registerClient() - UUID=fa85cdf6-9c8d-4b4d-9aa5-55edf83c71e8
08-12 14:11:20.190  2688  2740 D BtGatt.GattService: onClientRegistered() - UUID=fa85cdf6-9c8d-4b4d-9aa5-55edf83c71e8, clientIf=5
08-12 14:11:20.191  3825  3836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-12 14:11:20.192  2688  2705 D BtGatt.GattService: start scan with filters
08-12 14:11:20.197  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-12 14:11:20.197  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 14:11:20.197  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 14:11:20.197  2688  2743 D BtGatt.ScanManager: handling starting scan
08-12 14:11:20.197  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-12 14:11:20.200  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 14:11:20.201  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-12 14:11:20.201  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 14:11:20.202  2688  2743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
08-12 14:11:20.202  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-12 14:11:20.206  3825  3875 I io.jxcore.node.ConnectionHelper: start: OK
08-12 14:11:20.210  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.210  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-12 14:11:20.210  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.210  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-12 14:11:20.210  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.210  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-12 14:11:20.211  2688  2740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 14:11:20.211  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.210  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 14:11:20.211  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 14:11:20.211  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 14:11:20.211  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 14:11:20.211  2688  2743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-12 14:11:20.212  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 14:11:20.212  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 14:11:20.213  3825  3875 D BluetoothAdapter: STATE_ON
08-12 14:11:20.214  2688  2702 D BtGatt.GattService: stopScan() - queue size =1
08-12 14:11:20.214  2688  2705 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 14:11:20.215  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 14:11:20.215  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 14:11:20.215  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 14:11:20.215  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 14:11:20.215  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-12 14:11:20.218  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 14:11:20.219  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 14:11:20.219  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 14:11:20.219  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 14:11:20.220  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-12 14:11:20.221  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 14:11:20.222  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.222  2688  2743 D BtGatt.ScanManager: Starting BLE batch scan
08-12 14:11:20.222  2688  2743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-12 14:11:20.222  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.222  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.222  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 14:11:20.223  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 14:11:20.223  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 14:11:20.223  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:20.224  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.224  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.224  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
,08-12 14:11:20.224  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.224  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.225  3825  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-12 14:11:20.226  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 14:11:20.233  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:20.233  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.233  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.233  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:20.233  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:20.233  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:20.233  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:20.233  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:20.235  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:20.236  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 14:11:20.236  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 14:11:20.236  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-12 14:11:20.236  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 14:11:20.236  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:20.236  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 14:11:20.239  2688  2740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 14:11:20.239  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.240  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:20.241  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 14:11:20.241  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-12 14:11:20.243  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:20.245  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 14:11:20.245  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.246  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 14:11:20.247  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 14:11:20.247  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 14:11:20.251  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 14:11:20.251  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 14:11:20.251  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 14:11:20.252  3825  3875 D BluetoothAdapter: STATE_ON
,08-12 14:11:20.253  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 14:11:20.253  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.254  2688  2743 D BtGatt.ScanManager: stopping BLe Batch
,08-12 14:11:20.254  2688  2705 D BtGatt.GattService: registerClient() - UUID=d1d3b756-d4c1-455b-9e2b-8d40a2179ea1
,08-12 14:11:20.255  2688  2740 D BtGatt.GattService: onClientRegistered() - UUID=d1d3b756-d4c1-455b-9e2b-8d40a2179ea1, clientIf=5
,08-12 14:11:20.255  3825  3836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 14:11:20.256  2688  2702 D BtGatt.GattService: start scan with filters
,08-12 14:11:20.259  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 14:11:20.259  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-12 14:11:20.260  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,08-12 14:11:20.260  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 14:11:20.261  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 14:11:20.261  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.262  2688  2743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 14:11:20.262  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 14:11:20.263  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 14:11:20.263  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 14:11:20.264  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-12 14:11:20.267  3825  3875 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 14:11:20.269  2688  2740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 14:11:20.269  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.270  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 14:11:20.270  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-12 14:11:20.270  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.270  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-12 14:11:20.270  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.270  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-12 14:11:20.270  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-12 14:11:20.271  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-12 14:11:20.271  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-12 14:11:20.271  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-12 14:11:20.271  2688  2743 D BtGatt.ScanManager: handling starting scan
08-12 14:11:20.271  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 14:11:20.271  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 14:11:20.271  3825  3875 D BluetoothAdapter: STATE_ON
08-12 14:11:20.272  2688  2895 D BtGatt.GattService: stopScan() - queue size =1
08-12 14:11:20.273  2688  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 14:11:20.273  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 14:11:20.273  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 14:11:20.273  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 14:11:20.273  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-12 14:11:20.273  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 14:11:20.274  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 14:11:20.274  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 14:11:20.274  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-12 14:11:20.274  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-12 14:11:20.275  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:20.277  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.277  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.277  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 14:11:20.277  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-12 14:11:20.277  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 14:11:20.277  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.277  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.277  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 14:11:20.277  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.277  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.277  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.277  2688  2740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 14:11:20.278  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.278  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.278  2688  2743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 14:11:20.278  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.279  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 14:11:20.279  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.282  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.282  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
,08-12 14:11:20.282  3825  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-12 14:11:20.284  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:20.285  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 14:11:20.285  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.285  2688  2743 D BtGatt.ScanManager: Starting BLE batch scan
08-12 14:11:20.285  2688  2743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-12 14:11:20.288  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:20.288  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.288  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.288  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:20.288  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:20.288  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:20.288  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:20.288  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:20.292  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:20.292  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 14:11:20.292  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 14:11:20.292  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 14:11:20.292  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-12 14:11:20.292  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:20.293  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-12 14:11:20.294  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:20.297  2688  2740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 14:11:20.297  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.297  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 14:11:20.298  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:20.299  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 14:11:20.302  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 14:11:20.302  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.305  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 14:11:20.305  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 14:11:20.306  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 14:11:20.311  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 14:11:20.311  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 14:11:20.311  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 14:11:20.311  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 14:11:20.311  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.311  2688  2743 D BtGatt.ScanManager: stopping BLe Batch
08-12 14:11:20.311  3825  3875 D BluetoothAdapter: STATE_ON
,08-12 14:11:20.314  2688  2882 D BtGatt.GattService: registerClient() - UUID=83fd0b23-5d00-4487-847b-e3a69b1fd50f
08-12 14:11:20.314  2688  2740 D BtGatt.GattService: onClientRegistered() - UUID=83fd0b23-5d00-4487-847b-e3a69b1fd50f, clientIf=5
,08-12 14:11:20.315  3825  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 14:11:20.315  2688  2895 D BtGatt.GattService: start scan with filters
,08-12 14:11:20.318  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-12 14:11:20.318  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.319  2688  2743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-12 14:11:20.319  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-12 14:11:20.319  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 14:11:20.319  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-12 14:11:20.319  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 14:11:20.322  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 14:11:20.322  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 14:11:20.322  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 14:11:20.324  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 14:11:20.325  2688  2740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 14:11:20.325  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.327  2688  2743 D BtGatt.ScanManager: handling starting scan
08-12 14:11:20.327  3825  3875 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 14:11:20.327  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.327  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-12 14:11:20.327  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.327  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-12 14:11:20.328  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.328  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-12 14:11:20.328  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-12 14:11:20.328  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-12 14:11:20.328  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-12 14:11:20.328  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-12 14:11:20.328  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-12 14:11:20.328  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-12 14:11:20.329  3825  3875 D BluetoothAdapter: STATE_ON,
,08-12 14:11:20.330  2688  2702 D BtGatt.GattService: stopScan() - queue size =1
,08-12 14:11:20.331  2688  2882 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 14:11:20.331  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 14:11:20.331  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 14:11:20.331  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-12 14:11:20.331  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 14:11:20.331  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-12 14:11:20.332  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 14:11:20.332  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 14:11:20.333  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-12 14:11:20.333  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 14:11:20.334  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-12 14:11:20.334  2688  2740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 14:11:20.334  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.334  2688  2743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-12 14:11:20.335  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 14:11:20.335  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 14:11:20.335  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 14:11:20.336  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-12 14:11:20.336  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-12 14:11:20.336  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 14:11:20.336  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.336  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:20.336  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.337  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-12 14:11:20.337  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.337  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-12 14:11:20.337  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
,08-12 14:11:20.337  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-12 14:11:20.337  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.337  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.338  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.339  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 14:11:20.339  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-12 14:11:20.339  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-12 14:11:20.339  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.340  3825  3875 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-12 14:11:20.340  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.340  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.341  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.341  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.341  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 14:11:20.341  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.341  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.341  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.341  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.341  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.341  2688  2743 D BtGatt.ScanManager: Starting BLE batch scan
08-12 14:11:20.341  2688  2743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-12 14:11:20.341  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.341  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.341  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.341  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.342  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.342  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.344  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.344  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.344  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.344  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.345  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-12 14:11:20.345  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.345  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.346  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.34,6  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.346  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.346  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.346  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.346  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.346  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.346  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.346  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.347  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.347  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.347  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.348  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-12 14:11:20.348  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-12 14:11:20.348  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-12 14:11:20.348  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.349  3825  3875 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null,
08-12 14:11:20.349  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 14:11:20.349  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 14:11:20.349  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 14:11:20.350  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:20.350  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-12 14:11:20.351  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.351  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
,08-12 14:11:20.351  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-12 14:11:20.351  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
,08-12 14:11:20.351  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.351  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-12 14:11:20.351  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.351  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.351  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.352  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-12 14:11:20.353  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-12 14:11:20.353  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-12 14:11:20.353  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
,08-12 14:11:20.353  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted,
08-12 14:11:20.354  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 14:11:20.354  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 14:11:20.354  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 14:11:20.354  2688  2740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
08-12 14:11:20.354  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.354  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.355  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.355  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.355  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.355  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.355  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
,08-12 14:11:20.355  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.355  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.356  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.356  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.356  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-12 14:11:20.357  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.357  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.357  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.357  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list,
08-12 14:11:20.358  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-12 14:11:20.358  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-12 14:11:20.358  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-12 14:11:20.358  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-12 14:11:20.359  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-12 14:11:20.359  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-12 14:11:20.359  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.359  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.359  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 14:11:20.359  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.359  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.359  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.359  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list,
08-12 14:11:20.360  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.360  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.360  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.360  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.360  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.360  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.360  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.361  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 14:11:20.362  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.362  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 14:11:20.363  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.363  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-12 14:11:20.363  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.367  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-12 14:11:20.367  3825  3875 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55,
08-12 14:11:20.368  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-12 14:11:20.371  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 14:11:20.371  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:20.371  2688  2743 D BtGatt.ScanManager: stopping BLe Batch
08-12 14:11:20.372  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-12 14:11:20.372  3825  3875 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-12 14:11:20.372  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-12 14:11:20.372  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-12 14:11:20.373  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-12 14:11:20.374  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-12 14:11:20.375  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-12 14:11:20.375  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-12 14:11:20.375  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-12 14:11:20.375  3825  3875 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-12 14:11:20.375  3825  3875 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-12 14:11:20.375  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-12 14:11:20.376  3825  3875 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-12 14:11:20.376  3825  3875 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-12 14:11:20.376  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-12 14:11:20.376  3825  3875 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-12 14:11:20.376  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-12 14:11:20.378  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 14:11:20.378  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.379  2688  2743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-12 14:11:20.380  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-12 14:11:20.381  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-12 14:11:20.381  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-12 14:11:20.382  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-12 14:11:20.382  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-12 14:11:20.382  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-12 14:11:20.382  3825  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-12 14:11:20.383  3825  3875 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-12 14:11:20.383  3825  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
08-12 14:11:20.384  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.384  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.384  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.384  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.385  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.385  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.385  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-12 14:11:20.385  3825  3888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 14:11:20.385  2688  2740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 14:11:20.385  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:20.386  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.386  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.386  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.386  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.386  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.386  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.386  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.386  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.387  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 14:11:20.387  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.387  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.388  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.388  3825  3875 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-12 14:11:20.389  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.389  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.389  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.389  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.389  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.389  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.389  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
,08-12 14:11:20.389  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.389  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.390  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.390  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.390  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.390  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.390  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.391  3825  3889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
08-12 14:11:20.391  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.391  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.391  3825  3889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 401)
08-12 14:11:20.391  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.391  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.391  2688  2879 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-12 14:11:20.391  3825  3889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 401)
,08-12 14:11:20.392  3825  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-12 14:11:20.392  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.392  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.392  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.392  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:20.392  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.392  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.392  3825  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
08-12 14:11:20.392  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.392  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-12 14:11:20.392  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.392  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.392  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.392  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.392  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.393  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.394  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.394  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-12 14:11:20.394  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.394  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.394  3825  3875 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-12 14:11:20.394  3825  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-12 14:11:20.395  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-12 14:11:20.395  3825  3875 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-12 14:11:20.395  3825  3875 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-12 14:11:20.395  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-12 14:11:20.395  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-12 14:11:20.395  3825  3875 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-12 14:11:20.395  3825  3875 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-12 14:11:20.395  3825  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-12 14:11:20.395  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-12 14:11:20.395  3825  3875 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-12 14:11:20.395  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.395  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.395  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.396  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.396  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.396  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.396  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
,08-12 14:11:20.396  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.396  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.396  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.396  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.396  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.396  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.396  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.397  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 14:11:20.397  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.397  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.398  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.398  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:20.398  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.398  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.398  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.398  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.398  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.398  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.398  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.398  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.399  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.399  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.399  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:20.399  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.399  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.399  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.399  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.399  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.399  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.399  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.399  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:20.399  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.399  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.399  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.400  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.400  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.400  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.400  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.400  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.400  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.401  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.401  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.401  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.401  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
,08-12 14:11:20.402  3825  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-12 14:11:20.402  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:20.403  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-12 14:11:20.404  3825  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-12 14:11:20.404  3825  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-12 14:11:20.404  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-12 14:11:20.404  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 14:11:20.404  3825  3825 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-12 14:11:20.404  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:20.404  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-12 14:11:20.404  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-12 14:11:20.405  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-12 14:11:20.405  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.405  3825  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-12 14:11:20.405  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
,08-12 14:11:20.405  3825  3825 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 14:11:20.405  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.405  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 14:11:20.405  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 14:11:20.405  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 14:11:20.405  3825  3890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 14:11:20.405  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.405  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.406  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 14:11:20.406  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.406  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 14:11:20.406  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.406  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 14:11:20.406  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 14:11:20.406  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.406  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.406  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:20.406  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.407  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.407  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.407  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.407  3825  3890 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-12 14:11:20.407  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.407  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.407  3825  3890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-12 14:11:20.407  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.407  3825  3890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-12 14:11:20.407  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.407  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.407  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.407  3825  3825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-12 14:11:20.408  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.408  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.408  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.408  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.409  3825  3875 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-12 14:11:20.410  3825  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-12 14:11:20.410  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-12 14:11:20.410  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-12 14:11:20.410  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.410  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.410  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.410  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.410  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.410  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:20.410  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.410  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.410  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.411  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.411  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.411  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.411  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.411  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.412  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.412  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.412  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.412  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.415  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.415  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 14:11:20.415  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.415  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.415  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.415  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.415  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.415  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.415  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.415  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.415  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.416  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.416  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.416  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.416  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 14:11:20.416  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.416  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.417  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.417  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:20.417  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:20.417  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:20.418  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:20.418  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.418  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.418  3825  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c1cbd not in the list
08-12 14:11:20.418  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.418  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
,08-12 14:11:20.418  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:20.418  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.418  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.418  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:20.418  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:20.419  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:20.419  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:20.419  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:20.419  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5802b2 not in the list
08-12 14:11:20.420  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-12 14:11:20.420  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-12 14:11:20.420  3825  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-12 14:11:20.421  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-12 14:11:20.421  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-12 14:11:20.421  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-12 14:11:20.422  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-12 14:11:20.422  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-12 14:11:20.423  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-12 14:11:20.423  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-12 14:11:20.423  3825  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-12 14:11:20.423  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-12 14:11:20.423  3825  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-12 14:11:20.423  3825  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-12 14:11:20.424  3825  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-12 14:11:20.424  3825  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-12 14:11:20.424  3825  3875 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-12 14:11:20.425  3825  3875 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-12 14:11:20.425  3825  3875 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-12 14:11:20.425  3825  3875 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-12 14:11:20.426  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 14:11:20.426  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fa1244 added. We now have 2 listener(s)
08-12 14:11:20.426  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 14:11:20.427  3825  3875 D BluetoothAdapter: enable(): BT is already enabled..!
,08-12 14:11:20.428   871  1704 D WifiService: setWifiEnabled: true pid=3825, uid=10000
08-12 14:11:20.428   871  1704 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-12 14:11:20.428  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 14:11:20.429  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa2af2d added. We now have 3 listener(s)
08-12 14:11:20.429  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:20.433  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 14:11:20.433  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2727c62 added. We now have 4 listener(s)
08-12 14:11:20.433  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:20.434  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 14:11:20.434  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27101f3 added. We now have 5 listener(s)
08-12 14:11:20.434  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:20.436   871  1390 D WifiService: setWifiEnabled: false pid=3825, uid=10000
08-12 14:11:20.436   871  1390 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-12 14:11:20.440  2688  2736 D BluetoothAdapterState: Current state: ON, message: 23
,08-12 14:11:20.440  2688  2736 D BluetoothAdapterProperties: Setting state to 13
08-12 14:11:20.440  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 14:11:20.440  2688  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-12 14:11:20.441  2688  2736 D BluetoothAdapterProperties: onBluetoothDisable()
08-12 14:11:20.442  2688  2736 I BluetoothAdapterState: Entering PendingCommandState
,08-12 14:11:20.442  2688  2740 D BluetoothAdapterProperties: Scan Mode:20
,08-12 14:11:20.443  2688  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-12 14:11:20.443  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-12 14:11:20.443  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:20.443  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.443  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.443  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:20.443  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:20.443  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:20.443  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:20.443  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:20.444  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:20.444  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:20.444  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 14:11:20.445  2688  2688 D HeadsetService: Received stop request...Stopping profile...
08-12 14:11:20.447  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:20.447  2688  2688 V BluetoothAdapterState: isTurningOff()=true
,08-12 14:11:20.447  2688  2688 V BluetoothAdapterState: isTurningOn()=false,
08-12 14:11:20.447  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
,08-12 14:11:20.447  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:20.449  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:20.449  2688  2688 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-12 14:11:20.449  2688  2688 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-12 14:11:20.449  2688  2858 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-12 14:11:20.449  2688  2858 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-12 14:11:20.449  2688  2858 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-12 14:11:20.449  2688  2740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-12 14:11:20.450  2688  2740 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-12 14:11:20.450  2688  2688 D A2dpService: Received stop request...Stopping profile...
,08-12 14:11:20.451  2688  2888 D A2dpStateMachine: Exit Disconnected: -1
08-12 14:11:20.452  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-12 14:11:20.452  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:20.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:20.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:20.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:20.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:20.452  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:20.452  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-12 14:11:20.453  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-12 14:11:20.453  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:20.454   871  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-12 14:11:20.454   871  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-12 14:11:20.454   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-12 14:11:20.454   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-12 14:11:20.455  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:20.455  1358  1358 D BluetoothA2dp: Proxy object disconnected
,08-12 14:11:20.459  1911  1936 D BluetoothHeadset: Proxy object disconnected
08-12 14:11:20.459  1358  2007 D BluetoothHeadset: Proxy object disconnected
,08-12 14:11:20.459  1358  1358 D HeadsetProfile: Bluetooth service disconnected
,08-12 14:11:20.459   871   871 D BluetoothHeadset: Proxy object disconnected
08-12 14:11:20.460   871   871 D BluetoothHeadset: Proxy object disconnected
08-12 14:11:20.460   871   871 D BluetoothHeadset: Proxy object disconnected
08-12 14:11:20.458  2688  2688 D HidService: Received stop request...Stopping profile...
08-12 14:11:20.460   871   871 D BluetoothA2dp: Proxy object disconnected
08-12 14:11:20.460  2688  2688 D HidService: Stopping Bluetooth HidService
,08-12 14:11:20.461  1358  1358 D BluetoothInputDevice: Proxy object disconnected
08-12 14:11:20.461  1358  1358 D HidProfile: Bluetooth service disconnected
08-12 14:11:20.461  2688  2688 D HealthService: Received stop request...Stopping profile...
08-12 14:11:20.463  2688  2688 D PanService: Received stop request...Stopping profile...
08-12 14:11:20.464  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-12 14:11:20.464  2688  2688 V BluetoothAdapterState: isTurningOff()=true
08-12 14:11:20.464  2688  2688 V BluetoothAdapterState: isTurningOn()=false
,08-12 14:11:20.464  1358  1358 D PanProfile: Bluetooth service disconnected
08-12 14:11:20.464  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:20.465  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:20.465  2688  2740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-12 14:11:20.465  2688  2858 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-12 14:11:20.466  2688  2858 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-12 14:11:20.466  2688  2858 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-12 14:11:20.466  2688  2688 D BluetoothMapService: Received stop request...Stopping profile...
08-12 14:11:20.466  2688  2858 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-12 14:11:20.466  2688  2688 D BluetoothMapService: stop()
08-12 14:11:20.466  2688  2858 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-12 14:11:20.466  2688  2858 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-12 14:11:20.466  2688  2688 D BluetoothMapAppObserver: deinitObservers()
08-12 14:11:20.466  2688  2688 D BluetoothMapAppObserver: removeReceiver()
08-12 14:11:20.467  2688  2688 V BluetoothAdapterState: isTurningOff()=true
,08-12 14:11:20.467  2688  2688 V BluetoothAdapterState: isTurningOn()=false
,08-12 14:11:20.467  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:20.468  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:20.468  1358  1358 D BluetoothMap: Proxy object disconnected
08-12 14:11:20.468  1358  1358 D MapProfile: Bluetooth service disconnected
08-12 14:11:20.468   871  2078 D DhcpClient: Clearing IP address
08-12 14:11:20.468   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-12 14:11:20.469  2688  2688 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-12 14:11:20.469  2688  2740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-12 14:11:20.469  2688  2688 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-12 14:11:20.469  2688  2688 V BluetoothAdapterState: isTurningOff()=true
08-12 14:11:20.469  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-12 14:11:20.469  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:20.469  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:20.470  2688  2688 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-12 14:11:20.470  2688  2740 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-12 14:11:20.470  2688  2688 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-12 14:11:20.471  2688  2688 V BluetoothAdapterState: isTurningOff()=true
,08-12 14:11:20.471  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-12 14:11:20.471  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:20.471  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:20.471  2688  2688 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-12 14:11:20.471   372   869 D CommandListener: Setting iface cfg
08-12 14:11:20.471  2688  2688 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-12 14:11:20.472  2688  2688 D BluetoothMapService: MAP Service closeService in
,08-12 14:11:20.472  2688  2688 D BluetoothMapMasInstance0: MAP Service shutdown
08-12 14:11:20.472  2688  2688 D ObexServerSockets0: shutdown(block = true)
08-12 14:11:20.472  2688  2896 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-12 14:11:20.473  1507  2521 V NativeCrypto: Read error: ssl=0xaee3fc00: I/O error during system call, Connection timed out
08-12 14:11:20.474  1507  2521 V NativeCrypto: SSL shutdown failed: ssl=0xaee3fc00: I/O error during system call, Broken pipe
08-12 14:11:20.475   871  1390 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-12 14:11:20.476   871  2075 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-12 14:11:20.477   871  2075 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-12 14:11:20.478   871  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-12 14:11:20.478   396   396 E Parcel  : Reading a NULL string not supported here.
08-12 14:11:20.479   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-12 14:11:20.479   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-12 14:11:20.479   871  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-12 14:11:20.480   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-12 14:11:20.482   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-12 14:11:20.482   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-12 14:11:20.484   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-12 14:11:20.486   871  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-12 14:11:20.489  2688  2688 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-12 14:11:20.490  2688  2897 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-12 14:11:20.494  2688  2879 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-12 14:11:20.495  2688  2688 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-12 14:11:20.495  2688  2688 V BluetoothAdapterState: isTurningOff()=true
08-12 14:11:20.496  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-12 14:11:20.496  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:20.496  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:20.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:20.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:20.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:20.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:20.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:20.497  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:20.497  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-12 14:11:20.497  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
,08-12 14:11:20.497  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:20.499  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:20.499  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:20.499  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.499  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.499  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:20.499  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:20.499  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:20.499  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:20.499  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:20.499  2688  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-12 14:11:20.499  2688  2736 D BluetoothAdapterProperties: Setting state to 15
08-12 14:11:20.499  2688  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-12 14:11:20.500  2688  2736 I BluetoothAdapterState: Entering BleOnState
08-12 14:11:20.500  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:20.500  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-12 14:11:20.501  2688  2688 D BluetoothMapService: cleanup()
08-12 14:11:20.501  2688  2688 D BluetoothMapService: MAP Service closeService in
08-12 14:11:20.501  2688  2688 I BtOppRfcommListener: stopping Accept Thread
,08-12 14:11:20.501  2688  3440 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-12 14:11:20.501  2688  3440 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-12 14:11:20.504   871  2126 D DhcpClient: Receive thread stopped
08-12 14:11:20.515   871  3071 I ActivityManager: Start proc 3896:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-12 14:11:20.518   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-12 14:11:20.519  1358  1381 D BluetoothMap: onBluetoothStateChange: up=false
,08-12 14:11:20.523   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-12 14:11:20.527  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:20.527  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:20.527  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.527  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.527  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:20.527  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:20.527  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:20.527  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:20.527  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:20.528  1358  2007 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-12 14:11:20.528  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:20.528  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-12 14:11:20.529  1358  1379 D BluetoothPbap: onBluetoothStateChange: up=false
08-12 14:11:20.530  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:20.530  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:20.530  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:20.530  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:20.530  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:20.530  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:20.530  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:20.530  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:20.530  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-12 14:11:20.531   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-12 14:11:20.531   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-12 14:11:20.531   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-12 14:11:20.531  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:20.531  1358  1381 D BluetoothPan: onBluetoothStateChange on: false
08-12 14:11:20.531  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-12 14:11:20.532  1358  2007 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-12 14:11:20.532   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-12 14:11:20.535   871  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-12 14:11:20.536  1911  1926 D BluetoothHeadset: onBluetoothStateChange: up=false
08-12 14:11:20.537  2070  2278 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 14:11:20.537  1358  1381 D BluetoothA2dp: onBluetoothStateChange: up=false
08-12 14:11:20.537  2688  2736 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-12 14:11:20.538  2688  2736 D BluetoothAdapterProperties: Setting state to 16
08-12 14:11:20.538  2688  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-12 14:11:20.538  2688  2736 D BluetoothAdapterProperties: onBleDisable
08-12 14:11:20.538  2688  2736 I BluetoothAdapterState: Entering PendingCommandState
08-12 14:11:20.539  2688  2737 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-12 14:11:20.539  2688  2740 D BluetoothAdapterProperties: Scan Mode:20
08-12 14:11:20.540  2688  2858 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-12 14:11:20.540  2688  2858 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-12 14:11:20.540  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:20.541  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:20.542  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:20.543  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:20.563  3896  3896 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-12 14:11:20.567   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-12 14:11:20.567   871  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-12 14:11:20.568   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-12 14:11:20.571   871   888 D Tethering: MasterInitialState.processMessage what=3
08-12 14:11:20.572  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:20.573  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:20.576  3426  3426 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dbb002d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-12 14:11:20.583  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-12 14:11:20.589  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-12 14:11:20.591   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fd3ed6:true
,08-12 14:11:20.603   871  1962 I ActivityManager: Start proc 3913:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-12 14:11:20.615  3896  3896 D LocalBluetoothProfileManager: Adding local MAP profile
,08-12 14:11:20.618  3896  3896 D BluetoothMap: Create BluetoothMap proxy object
,08-12 14:11:20.622  3896  3896 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-12 14:11:20.628   372   869 E Netd    : netlink response contains error (No such file or directory)
,08-12 14:11:20.628   871  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-12 14:11:20.638  3913  3913 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-12 14:11:20.640  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,08-12 14:11:20.643   871  2002 I ActivityManager: Killing 3576:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-12 14:11:20.741  2688  2740 I bt_hci  : shut_down
,08-12 14:11:20.742  2688  2745 D bt_hwcfg: hw_epilog_process
08-12 14:11:20.742  2688  2745 I bt_vendor: low_power_mode_cb
,08-12 14:11:20.764  2688  2745 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-12 14:11:20.764  2688  2745 I bt_vendor: epilog_cb
08-12 14:11:20.765  2688  2745 I bt_hci  : epilog_finished_callback
,08-12 14:11:20.773  2688  2740 I bt_hci_h4: hal_close
08-12 14:11:20.774  2688  2740 I bt_userial_vendor: device fd = 51 close
,08-12 14:11:20.809  3913  3913 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.File.exists(File.java:361)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 14:11:20.809  3913  3913 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 14:11:20.809  3913  3913 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 14:11:20.809  3913  3913 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.e.b(PG:170)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 14:11:20.809  3913  3913 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.k.d(PG:583)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.e.b(PG:170)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 14:11:20.809  3913  3913 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.File.exists(File.java:361)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 14:11:20.809  3913  3913 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.File.exists(File.java:361)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 14:11:20.809  3913  3913 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 14:11:20.809  3913  3913 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 14:11:20.858   871  1704 I ActivityManager: Start proc 3944:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-12 14:11:20.860   871  1704 I ActivityManager: Killing 3426:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-12 14:11:20.908  3825  3825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 14:11:20.950  3944  3944 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-12 14:11:20.961  2688  2737 D bt_stack_manager: event_shut_down_stack finished.
08-12 14:11:20.962  2688  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-12 14:11:20.966  2688  2688 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-12 14:11:20.966  2688  2688 D BtGatt.GattService: Received stop request...Stopping profile...
08-12 14:11:20.966  2688  2688 D BtGatt.GattService: stop()
,08-12 14:11:20.966  2688  2688 D BtGatt.AdvertiseManager: advertise clients cleared
08-12 14:11:20.967  2688  2736 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-12 14:11:20.969  2688  2688 V BluetoothAdapterState: isTurningOff()=false
08-12 14:11:20.970  2688  2688 V BluetoothAdapterState: isTurningOn()=false
,08-12 14:11:20.970  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:20.970  2688  2688 V BluetoothAdapterState: isBleTurningOff()=true
,08-12 14:11:20.970  2688  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-12 14:11:20.971  2688  2736 D BluetoothAdapterProperties: Setting state to 10
08-12 14:11:20.971  2688  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-12 14:11:20.971  2688  2736 I BluetoothAdapterState: Entering OffState
08-12 14:11:20.972   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-12 14:11:20.983  2688  2688 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-12 14:11:20.983  2688  2688 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-12 14:11:20.983  2688  2688 I BluetoothServiceJni: cleanupNative: return from cleanup
08-12 14:11:20.984  2688  2737 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-12 14:11:20.986  2688  2737 D bt_stack_manager: event_clean_up_stack finished.
,08-12 14:11:20.993  2688  2688 I art     : System.exit called, status: 0
,08-12 14:11:20.993  2688  2688 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-12 14:11:21.033  3944  3944 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-12 14:11:21.066   871  2003 I ActivityManager: Process com.android.bluetooth (pid 2688) has died
,08-12 14:11:21.072  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-12 14:11:21.093   871   882 I ActivityManager: Start proc 3973:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-12 14:11:21.097  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,08-12 14:11:21.132  3913  3936 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-12 14:11:21.146  3973  3973 D AdapterServiceConfig: Adding HeadsetService
,08-12 14:11:21.146  3973  3973 D AdapterServiceConfig: Adding A2dpService
,08-12 14:11:21.146  3973  3973 D AdapterServiceConfig: Adding HidService
08-12 14:11:21.146  3973  3973 D AdapterServiceConfig: Adding HealthService
08-12 14:11:21.146  3973  3973 D AdapterServiceConfig: Adding PanService
,08-12 14:11:21.146  3973  3973 D AdapterServiceConfig: Adding GattService
08-12 14:11:21.147  3973  3973 D AdapterServiceConfig: Adding BluetoothMapService
,08-12 14:11:21.151   871  2002 I ActivityManager: Killing 2764:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-12 14:11:21.163   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bb14f8:true
,08-12 14:11:21.216  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-12 14:11:21.265  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-12 14:11:21.270  1730  1730 D SystemUpdateService: onCreate
,08-12 14:11:21.276  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-12 14:11:21.282  1730  3985 I SystemUpdateService: active receiver: enabled
,08-12 14:11:21.289  1730  3985 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-12 14:11:21.290  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-12 14:11:21.290  1730  3985 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-12 14:11:21.290  1730  3985 I SystemUpdateService: now status is 0 (complete)
,08-12 14:11:21.291  1730  3985 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-12 14:11:21.292  1730  3985 I SystemUpdateService: file has been verified
,08-12 14:11:21.292  1730  3985 I SystemUpdateService: OTA package size = 12249756
,08-12 14:11:21.297  1730  3985 I SystemUpdateService: showing system update notification
,08-12 14:11:21.298  1730  2497 I iu.UploadsManager: num queued entries: 0
,08-12 14:11:21.299  1730  2497 I iu.UploadsManager: num updated entries: 0
,08-12 14:11:21.305  1730  2497 I iu.SyncManager: NEXT; no task
,08-12 14:11:21.314  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-12 14:11:21.319  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-12 14:11:21.344   871  2002 I ActivityManager: Start proc 3987:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-12 14:11:21.346  1730  1730 D SystemUpdateService: onDestroy
,08-12 14:11:21.405  3987  3987 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-12 14:11:21.407  3987  3987 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-12 14:11:21.418  3987  3987 D SprintDMHelper: simOperator: 
,08-12 14:11:21.418  3987  3987 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-12 14:11:21.468   871   881 I ActivityManager: Start proc 3999:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-12 14:11:21.469   871   881 I ActivityManager: Killing 3515:android.process.acore/u0a5 (adj 15): empty #17
,08-12 14:11:21.662   871  1962 I ActivityManager: Start proc 4014:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-12 14:11:21.668  3074  4013 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-12 14:11:21.673   871  3071 I ActivityManager: Killing 3707:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-12 14:11:21.740  4014  4014 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-12 14:11:21.802  4014  4014 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-12 14:11:21.802  4014  4014 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-12 14:11:21.802  4014  4014 I GAv4    :   adb logcat -s GAv4
,08-12 14:11:21.819  4014  4014 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-12 14:11:21.829  4014  4014 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-12 14:11:21.857  4014  4032 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-12 14:11:21.960  4014  4014 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-12 14:11:21.997  4014  4014 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-12 14:11:22.015  4014  4014 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 4262-4274)
08-12 14:11:22.015  4014  4014 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 14:11:22.025  4014  4014 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1cfee3f}
,08-12 14:11:22.027  4014  4014 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 14:11:22.027  4014  4014 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 14:11:22.039  4014  4014 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-12 14:11:22.040  4014  4014 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-12 14:11:22.055  4014  4014 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-12 14:11:22.069  4014  4014 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 14:11:22.069  4014  4014 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 14:11:22.069  4014  4014 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 14:11:22.069  4014  4014 I Adreno  : Build Date                       : 10/20/15
08-12 14:11:22.069  4014  4014 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 14:11:22.069  4014  4014 I Adreno  : Local Branch                     : M14
08-12 14:11:22.069  4014  4014 I Adreno  : Remote Branch                    : 
08-12 14:11:22.069  4014  4014 I Adreno  : Remote Branch                    : 
08-12 14:11:22.069  4014  4014 I Adreno  : Reconstruct Branch               : 
,08-12 14:11:22.134  4014  4014 I NSApplication: Starting up...
,08-12 14:11:22.145  4014  4060 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-12 14:11:22.182   871  1945 I ActivityManager: Start proc 4065:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-12 14:11:22.184   871  1945 I ActivityManager: Killing 3720:com.android.musicfx/u0a18 (adj 15): empty #17
,08-12 14:11:22.254  4065  4065 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-12 14:11:22.444   871  3957 I ActivityManager: Killing 3468:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-12 14:11:23.450   871   881 D WifiService: setWifiEnabled: true pid=3825, uid=10000
,08-12 14:11:23.450   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-12 14:11:23.464   871  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-12 14:11:23.475  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:23.475  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:23.475  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:23.475  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:23.475  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:23.475  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:23.475  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:23.475  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:23.475  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:23.476  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:23.476  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-12 14:11:23.478  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:23.478  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:23.478  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:23.478  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:23.478  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:23.478  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:23.478  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:23.478  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:23.478  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-12 14:11:23.479  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:23.479  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-12 14:11:23.483   871  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-12 14:11:23.484   871  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-12 14:11:23.484   871  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-12 14:11:23.485   871  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-12 14:11:23.485   871  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-12 14:11:23.486   871  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK,
08-12 14:11:23.486   871  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-12 14:11:23.506   871  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.38 rxSuccessRate=12.88 delta 1000 -> 994
08-12 14:11:23.506   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-12 14:11:23.509   372   869 D CommandListener: Setting iface cfg
,08-12 14:11:23.510   871  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-12 14:11:23.510   871  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-12 14:11:23.516   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-12 14:11:23.516   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-12 14:11:23.526   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-12 14:11:23.556   871  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-12 14:11:23.557   871  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-12 14:11:23.598   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-12 14:11:23.601  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-12 14:11:24.016  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-12 14:11:24.071  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-12 14:11:24.073  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-12 14:11:24.076   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 14:11:24.084   871  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-12 14:11:24.085   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-12 14:11:24.085   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-12 14:11:24.101   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-12 14:11:24.112   372   869 D CommandListener: Setting iface cfg
08-12 14:11:24.113   871  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-12 14:11:24.133   871  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-12 14:11:24.138   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-12 14:11:24.152   871  4088 D DhcpClient: Receive thread started
,08-12 14:11:24.236   871  1307 E native  : do suspend false
,08-12 14:11:24.256   871  2078 D DhcpClient: Broadcasting DHCPDISCOVER
,08-12 14:11:24.269   871  4088 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172687, domain null
,08-12 14:11:24.270   871  2078 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172687 seconds
,08-12 14:11:24.275   871  2078 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-12 14:11:24.288   871  4088 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-12 14:11:24.291   871  2078 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-12 14:11:24.296   372   869 D CommandListener: Setting iface cfg
,08-12 14:11:24.307   871  2078 D DhcpClient: Scheduling renewal in 86399s
,08-12 14:11:24.311   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-12 14:11:24.333   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-12 14:11:24.336   871  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 14:11:24.337   871  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-12 14:11:24.338   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-12 14:11:24.343   871  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-12 14:11:24.359   871  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-12 14:11:24.383   871  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-12 14:11:24.385   871  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-12 14:11:24.386   871  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-12 14:11:24.388   871  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-12 14:11:24.389   871  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-12 14:11:24.397   871  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-12 14:11:24.402   871  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-12 14:11:24.403   871  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-12 14:11:24.403   871  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-12 14:11:24.403   871  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-12 14:11:24.403   871  1310 D ConnectivityService:    accepting network in place of null
08-12 14:11:24.403   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-12 14:11:24.404   871  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-12 14:11:24.410   871  4087 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136669, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:11:24.448   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-12 14:11:24.490   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-12 14:11:24.496   871  4086 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:4001:804::200e
,08-12 14:11:24.501   871  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-12 14:11:24.501   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-12 14:11:24.511   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-12 14:11:24.521   871  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-12 14:11:24.523  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:24.523  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:24.523  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:24.523  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:24.523  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:24.523  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:24.523  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:24.523  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:24.523  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 14:11:24.523  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:24.524  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:24.529  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:24.529  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:24.529  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:24.529  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:24.529  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:24.529  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:24.529  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:24.529  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:24.529  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:24.529  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:24.529  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:24.540  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-12 14:11:24.544  1730  1730 D SystemUpdateService: onCreate
,08-12 14:11:24.548  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-12 14:11:24.551  1730  4099 I SystemUpdateService: active receiver: enabled
,08-12 14:11:24.554  1730  4099 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-12 14:11:24.555   871  4086 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 12 Aug 2016 12:11:24 GMT], X-Android-Received-Millis=[1471003884554], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471003884533]}
,08-12 14:11:24.559   871  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-12 14:11:24.559   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-12 14:11:24.559   871  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-12 14:11:24.561   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-12 14:11:24.563  1730  4099 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-12 14:11:24.564  1730  4099 I SystemUpdateService: now status is 0 (complete)
08-12 14:11:24.564  1730  4099 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-12 14:11:24.564  1730  4099 I SystemUpdateService: file has been verified
08-12 14:11:24.564  1730  4099 I SystemUpdateService: OTA package size = 12249756
,08-12 14:11:24.572  1730  4099 I SystemUpdateService: showing system update notification
,08-12 14:11:24.574  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-12 14:11:24.578  1730  2497 I iu.UploadsManager: num queued entries: 0
,08-12 14:11:24.579  1730  4103 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-12 14:11:24.579  1730  4103 W BaseAppContext: Using Auth Proxy for data requests.
,08-12 14:11:24.579  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-12 14:11:24.581  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-12 14:11:24.584  1730  4103 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
08-12 14:11:24.586  3987  3987 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-12 14:11:24.588  1730  2497 I iu.UploadsManager: num updated entries: 0
,08-12 14:11:24.589  1730  2497 I iu.SyncManager: NEXT; no task
,08-12 14:11:24.590  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:24.592  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:24.600  3987  3987 D SprintDMHelper: simOperator: 
,08-12 14:11:24.600  3987  3987 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-12 14:11:24.610  1730  1730 D SystemUpdateService: onDestroy
,08-12 14:11:24.628  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-12 14:11:24.628  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-12 14:11:24.628  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 14:11:24.628  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 14:11:24.639  1730  4103 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-12 14:11:24.722  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 14:11:24.722  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 14:11:24.722  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 14:11:24.722  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 14:11:24.742  2991  4106 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 14:11:24.742  2991  4106 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at jdm.a(PG:82)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at jcs.o(PG:406)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at jcn.a(PG:1379)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at jcs.i(PG:143)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at blb.a(PG:3937)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at czp.a(PG:18188)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at czp.a(PG:9081)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at czq.run(PG:1686)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 14:11:24.742  2991  4106 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at jdj.a(PG:4091)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at jdj.a(PG:1125)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at jdm.a(PG:77)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	... 12 more
08-12 14:11:24.742  2991  4106 E HttpOperation: Caused by: faj: BadAuthentication
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at fal.a(PG:38)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	at jdj.a(PG:4089)
08-12 14:11:24.742  2991  4106 E HttpOperation: 	... 14 more
,08-12 14:11:24.761  3074  4107 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-12 14:11:24.789  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 14:11:24.789  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 14:11:24.789  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 14:11:24.789  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 14:11:24.815  2991  4106 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 14:11:24.815  2991  4106 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at jdm.a(PG:82)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at jcs.o(PG:406)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at jcn.a(PG:1379)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at jcs.i(PG:143)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at hec.a(PG:42)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at hee.a(PG:102)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at czr.a(PG:65)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at kka.a(PG:108)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at czp.a(PG:19176)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at czp.a(PG:9081)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at czq.run(PG:1686)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 14:11:24.815  2991  4106 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at jdj.a(PG:4091)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at jdj.a(PG:1125)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at jdm.a(PG:77)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	... 15 more
08-12 14:11:24.815  2991  4106 E HttpOperation: Caused by: faj: BadAuthentication
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at fal.a(PG:38)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	at jdj.a(PG:4089)
08-12 14:11:24.815  2991  4106 E HttpOperation: 	... 17 more
,08-12 14:11:24.816  2991  4106 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 14:11:24.816  2991  4106 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at hec.a(PG:42)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at hee.a(PG:102)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at czr.a(PG:65)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at kka.a(PG:108)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	... 15 more
08-12 14:11:24.816  2991  4106 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at fal.a(PG:38)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 14:11:24.816  2991  4106 E ExperimentLoader: 	... 17 more
,08-12 14:11:24.919   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129666, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 14:11:25.500   871  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-12 14:11:26.142   871  2002 I ActivityManager: Killing 3745:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-12 14:11:26.456   871  1704 D WifiService: setWifiEnabled: false pid=3825, uid=10000
,08-12 14:11:26.457   871  1704 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-12 14:11:26.492  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-12 14:11:26.499   871  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-12 14:11:26.499   871  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-12 14:11:26.499   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-12 14:11:26.500   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-12 14:11:26.515   871  2078 D DhcpClient: Clearing IP address
,08-12 14:11:26.516   372   869 D CommandListener: Clearing all IP addresses on wlan0
,08-12 14:11:26.520   372   869 D CommandListener: Setting iface cfg
,08-12 14:11:26.523  1507  4112 V NativeCrypto: Read error: ssl=0x9abf5800: I/O error during system call, Connection timed out
,08-12 14:11:26.526  1507  4112 V NativeCrypto: SSL shutdown failed: ssl=0x9abf5800: I/O error during system call, Broken pipe
,08-12 14:11:26.534   871   881 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-12 14:11:26.536   871  4086 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-12 14:11:26.544   396   396 E Parcel  : Reading a NULL string not supported here.
,08-12 14:11:26.545   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-12 14:11:26.545   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-12 14:11:26.545   871  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
08-12 14:11:26.546   871  4086 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-12 14:11:26.547   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-12 14:11:26.550   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-12 14:11:26.551   871  4088 D DhcpClient: Receive thread stopped
,08-12 14:11:26.556   871  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-12 14:11:26.561   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 14:11:26.562  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-12 14:11:26.563  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:26.563  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:26.563  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:26.563  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:26.563  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:26.563  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:26.563  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:26.563  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:26.563  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:26.563  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-12 14:11:26.564  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-12 14:11:26.564  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:26.564  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:26.564  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:26.564  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:26.564  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:26.564  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:26.564  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:26.564  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:26.564  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:26.564  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-12 14:11:26.565  2070  2278 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-12 14:11:26.568   871  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-12 14:11:26.591   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-12 14:11:26.634   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-12 14:11:26.635   871  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-12 14:11:26.635   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-12 14:11:26.637   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-12 14:11:26.648  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:26.648  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:26.651  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-12 14:11:26.656  1730  1730 D SystemUpdateService: onCreate
,08-12 14:11:26.659  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-12 14:11:26.667  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-12 14:11:26.673  1730  4127 I SystemUpdateService: active receiver: enabled,
,08-12 14:11:26.674  1730  2497 I iu.UploadsManager: num queued entries: 0
,08-12 14:11:26.674  1730  2497 I iu.UploadsManager: num updated entries: 0
08-12 14:11:26.675  1730  2497 I iu.SyncManager: NEXT; no task
,08-12 14:11:26.677  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-12 14:11:26.678  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-12 14:11:26.680  3987  3987 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-12 14:11:26.684  3987  3987 D SprintDMHelper: simOperator: 
,08-12 14:11:26.684  3987  3987 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-12 14:11:26.685  1730  4127 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-12 14:11:26.687  1730  4127 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-12 14:11:26.687  1730  4127 I SystemUpdateService: now status is 0 (complete)
08-12 14:11:26.687  1730  4127 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-12 14:11:26.687  1730  4127 I SystemUpdateService: file has been verified
,08-12 14:11:26.687  1730  4127 I SystemUpdateService: OTA package size = 12249756
,08-12 14:11:26.716  1730  4127 I SystemUpdateService: showing system update notification
,08-12 14:11:26.718  3074  4130 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-12 14:11:26.727   372   869 E Netd    : netlink response contains error (No such file or directory)
,08-12 14:11:26.728   871  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-12 14:11:26.728   871  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-12 14:11:26.730  1730  1730 D SystemUpdateService: onDestroy
,08-12 14:11:29.497   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30b1592:true
,08-12 14:11:29.498  3973  3973 D BluetoothAdapterState: make() - Creating AdapterState
,08-12 14:11:29.504  3973  3973 I bt_bluedroid: init
,08-12 14:11:29.505  3973  4134 I BluetoothAdapterState: Entering OffState
,08-12 14:11:29.511  3973  4135 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-12 14:11:29.511  3973  4135 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-12 14:11:29.511  3973  4135 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-12 14:11:29.511  3973  4135 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-12 14:11:29.512  3973  3973 I bt_bluedroid: get_profile_interface socket
,08-12 14:11:29.514  3973  3973 I bt_bluedroid: get_profile_interface sdp
,08-12 14:11:29.518  3973  3983 I bt_bluedroid: config_hci_snoop_log
,08-12 14:11:29.519   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-12 14:11:29.522  3973  4138 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-12 14:11:29.526  3973  4138 D BluetoothAdapterProperties: Name is: Nexus 6
,08-12 14:11:29.531  3973  4134 D BluetoothAdapterState: Current state: OFF, message: 0
,08-12 14:11:29.532  3973  4134 D BluetoothAdapterProperties: Setting state to 14
08-12 14:11:29.532  3973  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-12 14:11:29.535  3973  4134 D BluetoothBondStateMachine: make
08-12 14:11:29.536  3973  4139 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-12 14:11:29.540  3973  4134 I BluetoothAdapterState: Entering PendingCommandState
,08-12 14:11:29.541  3973  3973 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-12 14:11:29.544  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:29.545  3973  3973 D BtGatt.DebugUtils: handleDebugAction() action=null
08-12 14:11:29.545  3973  3973 D BtGatt.GattService: Received start request. Starting profile...
08-12 14:11:29.546  3973  3973 D BtGatt.GattService: start()
08-12 14:11:29.546  3973  3973 I bt_bluedroid: get_profile_interface gatt
08-12 14:11:29.547  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
08-12 14:11:29.547  3973  3973 D BtGatt.AdvertiseManager: advertise manager created
,08-12 14:11:29.555  3973  3973 V BluetoothAdapterState: isTurningOff()=false
,08-12 14:11:29.555  3973  3973 V BluetoothAdapterState: isTurningOn()=false
08-12 14:11:29.555  3973  3973 V BluetoothAdapterState: isBleTurningOn()=true
08-12 14:11:29.555  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
,08-12 14:11:29.556  3973  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-12 14:11:29.556  3973  4134 I bt_bluedroid: enable
08-12 14:11:29.556  3973  4135 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-12 14:11:29.557  3973  4135 I bt_hci  : start_up
,08-12 14:11:29.564  3973  4135 I bt_vendor: alloc value 0xb39b9189
,08-12 14:11:29.564  3973  4135 I bt_vendor: init
08-12 14:11:29.564  3973  4135 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-12 14:11:29.564  3973  4135 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-12 14:11:29.673  3973  4135 D bt_hci  : start_up starting async portion
,08-12 14:11:29.675  3973  4142 I bt_hci  : event_finish_startup
,08-12 14:11:29.675  3973  4142 I bt_hci_h4: hal_open
,08-12 14:11:29.675  3973  4142 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-12 14:11:29.689  3973  4142 I bt_userial_vendor: device fd = 51 open
,08-12 14:11:29.714  3973  4142 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-12 14:11:29.746  3973  4142 D bt_hwcfg: Chipset BCM4354A2
,08-12 14:11:29.747  3973  4142 D bt_hwcfg: Target name = [BCM4354A2]
08-12 14:11:29.747  3973  4142 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-12 14:11:30.416  3973  4142 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-12 14:11:30.418  3973  4142 D bt_hwcfg: Settlement delay -- 100 ms
08-12 14:11:30.418  3973  4142 I bt_hwcfg: Setting fw settlement delay to 100 
,08-12 14:11:30.535  3973  4142 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-12 14:11:30.536  3973  4142 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-12 14:11:30.565  3973  4142 I bt_hwcfg: vendor lib fwcfg completed
,08-12 14:11:30.565  3973  4142 I bt_vendor: firmware callback
08-12 14:11:30.565  3973  4142 I bt_hci  : firmware_config_callback
,08-12 14:11:30.576  3973  4144 I bt_btu  : btu_task pending for preload complete event
,08-12 14:11:30.577  3973  4144 I bt_btu_task: Bluetooth chip preload is complete
08-12 14:11:30.577  3973  4144 I bt_btu  : btu_task received preload complete event
,08-12 14:11:30.587  3973  4144 I         : BTE_InitTraceLevels -- TRC_HCI
,08-12 14:11:30.587  3973  4144 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-12 14:11:30.588  3973  4144 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-12 14:11:30.588  3973  4144 I         : BTE_InitTraceLevels -- TRC_AVDT
08-12 14:11:30.588  3973  4144 I         : BTE_InitTraceLevels -- TRC_AVRC
08-12 14:11:30.588  3973  4144 I         : BTE_InitTraceLevels -- TRC_A2D
,08-12 14:11:30.589  3973  4144 I         : BTE_InitTraceLevels -- TRC_BNEP
08-12 14:11:30.589  3973  4144 I         : BTE_InitTraceLevels -- TRC_BTM
08-12 14:11:30.589  3973  4144 I         : BTE_InitTraceLevels -- TRC_GAP
,08-12 14:11:30.589  3973  4144 I         : BTE_InitTraceLevels -- TRC_PAN
08-12 14:11:30.590  3973  4144 I         : BTE_InitTraceLevels -- TRC_SDP
08-12 14:11:30.590  3973  4144 I         : BTE_InitTraceLevels -- TRC_GATT
08-12 14:11:30.590  3973  4144 I         : BTE_InitTraceLevels -- TRC_SMP
,08-12 14:11:30.591  3973  4144 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-12 14:11:30.591  3973  4144 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-12 14:11:30.723  3973  4144 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,08-12 14:11:30.724  3973  4144 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-12 14:11:30.737  3973  4138 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-12 14:11:30.739  3973  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-12 14:11:30.740  3973  4138 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-12 14:11:30.743  3973  4138 D BluetoothAdapterProperties: Name is: Nexus 6
08-12 14:11:30.746  3973  4138 D BluetoothAdapterProperties: Scan Mode:20
,08-12 14:11:30.749  3973  4138 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-12 14:11:30.749  3973  4138 D bt_hci  : do_postload posting postload work item
08-12 14:11:30.749  3973  4142 I bt_hci  : event_postload
,08-12 14:11:30.750  3973  4142 I bt_vendor: sco_config_cb
08-12 14:11:30.750  3973  4142 I bt_hci  : sco_config_callback postload finished.
08-12 14:11:30.752  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:30.754  3973  4138 D bt_bte_conf: Device ID record 1 : primary
,08-12 14:11:30.754  3973  4138 D bt_bte_conf:   vendorId            = 000f
08-12 14:11:30.754  3973  4138 D bt_bte_conf:   vendorIdSource      = 0001
08-12 14:11:30.754  3973  4138 D bt_bte_conf:   product             = 1200
08-12 14:11:30.754  3973  4138 D bt_bte_conf:   version             = 1436
08-12 14:11:30.755  3973  4138 D bt_bte_conf:   clientExecutableURL = 
08-12 14:11:30.755  3973  4138 D bt_bte_conf:   serviceDescription  = 
08-12 14:11:30.755  3973  4138 D bt_bte_conf:   documentationURL    = 
08-12 14:11:30.756  3973  4138 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-12 14:11:30.756  3973  4135 D bt_stack_manager: event_start_up_stack finished
08-12 14:11:30.757  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:30.758  3973  4142 I bt_vendor: low_power_mode_cb
08-12 14:11:30.758  3973  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-12 14:11:30.759  3973  4134 D BluetoothAdapterProperties: Setting state to 15
08-12 14:11:30.759  3973  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-12 14:11:30.761  3973  4134 I BluetoothAdapterState: Entering BleOnState
,08-12 14:11:30.766  3973  4134 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-12 14:11:30.767  3973  4134 D BluetoothAdapterProperties: Setting state to 11
08-12 14:11:30.767  3973  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-12 14:11:30.779  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:30.780  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
08-12 14:11:30.783  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:30.784  3973  3973 D HeadsetService: Received start request. Starting profile...
08-12 14:11:30.787  3973  4134 I BluetoothAdapterState: Entering PendingCommandState
08-12 14:11:30.787  3973  3973 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-12 14:11:30.788  3973  3973 D HeadsetStateMachine: make
,08-12 14:11:30.795  3973  3973 D HeadsetStateMachine: max_hf_connections = 1
08-12 14:11:30.795  3973  3973 I bt_bluedroid: get_profile_interface handsfree
08-12 14:11:30.796  3973  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-12 14:11:30.796  3973  4138 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-12 14:11:30.803  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:30.803  3973  3973 D A2dpService: Received start request. Starting profile...
,08-12 14:11:30.804  3973  3973 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-12 14:11:30.805  3973  3973 I bt_bluedroid: get_profile_interface avrcp
,08-12 14:11:30.811  3973  3973 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-12 14:11:30.811  3973  3973 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-12 14:11:30.811  3973  3973 D A2dpStateMachine: make
,08-12 14:11:30.813  3973  3973 I bt_bluedroid: get_profile_interface a2dp
,08-12 14:11:30.813  3973  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-12 14:11:30.815  3973  4153 D A2dpStateMachine: Enter Disconnected: -2
,08-12 14:11:30.815  3973  3973 I BluetoothHidServiceJni: classInitNative: succeeds
,08-12 14:11:30.816  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:30.817  3973  3973 D HidService: Received start request. Starting profile...
,08-12 14:11:30.817  3973  3973 I bt_bluedroid: get_profile_interface hidhost
08-12 14:11:30.817  3973  4138 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-12 14:11:30.817  3973  3973 D HidService: setHidService(): set to: null
08-12 14:11:30.817  3973  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-12 14:11:30.818  3973  3973 I BluetoothHealthServiceJni: classInitNative: succeeds
08-12 14:11:30.819  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
08-12 14:11:30.819  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-12 14:11:30.819  3896  3896 D BluetoothInputDevice: Proxy object connected
,08-12 14:11:30.820  3896  3896 D HidProfile: Bluetooth service connected
08-12 14:11:30.820  3973  3973 D HealthService: Received start request. Starting profile...
,08-12 14:11:30.821  3973  3973 I bt_bluedroid: get_profile_interface health
,08-12 14:11:30.822  3973  3973 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-12 14:11:30.823  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
08-12 14:11:30.824  3973  3973 D PanService: Received start request. Starting profile...
08-12 14:11:30.824  3896  3896 D BluetoothPan: BluetoothPAN Proxy object connected
08-12 14:11:30.824  3973  3973 D BluetoothPanServiceJni: initializeNative(L110): pan
08-12 14:11:30.824  3973  3973 I bt_bluedroid: get_profile_interface pan
08-12 14:11:30.824  3896  3896 D PanProfile: Bluetooth service connected
08-12 14:11:30.824  3973  4138 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-12 14:11:30.827  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:30.828  3973  3973 D BluetoothMapService: Received start request. Starting profile...
,08-12 14:11:30.828  3896  3896 D BluetoothMap: Proxy object connected
,08-12 14:11:30.828  3973  3973 D BluetoothMapService: start()
,08-12 14:11:30.828  3896  3896 D MapProfile: Bluetooth service connected
08-12 14:11:30.829  3896  3896 D BluetoothMap: getConnectedDevices()
08-12 14:11:30.829  3896  3896 D BluetoothMap: Bluetooth is Not enabled
08-12 14:11:30.830  3973  3973 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-12 14:11:30.831  3973  3973 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-12 14:11:30.831  3973  3973 D BluetoothMapAppObserver: createReceiver()
,08-12 14:11:30.832  3973  3973 D BluetoothMapAppObserver: initObservers()
08-12 14:11:30.832  3973  3973 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-12 14:11:30.838  3973  3973 V BluetoothAdapterState: isTurningOff()=false
,08-12 14:11:30.838  3973  3973 V BluetoothAdapterState: isTurningOn()=true
08-12 14:11:30.838  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:30.838  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:30.840  3973  3973 V BluetoothAdapterState: isTurningOff()=false
08-12 14:11:30.840  3973  3973 V BluetoothAdapterState: isTurningOn()=true
08-12 14:11:30.840  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:30.840  3973  4151 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-12 14:11:30.840  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
,08-12 14:11:30.840  3973  3973 V BluetoothAdapterState: isTurningOff()=false
08-12 14:11:30.840  3973  3973 V BluetoothAdapterState: isTurningOn()=true
08-12 14:11:30.840  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:30.840  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:30.841  3973  3973 V BluetoothAdapterState: isTurningOff()=false
,08-12 14:11:30.841  3973  3973 V BluetoothAdapterState: isTurningOn()=true
,08-12 14:11:30.841  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:30.841  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:30.841  3973  3973 V BluetoothAdapterState: isTurningOff()=false
08-12 14:11:30.841  3973  3973 V BluetoothAdapterState: isTurningOn()=true
08-12 14:11:30.841  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:30.841  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:30.842  3973  3973 V BluetoothAdapterState: isTurningOff()=false
08-12 14:11:30.842  3973  3973 V BluetoothAdapterState: isTurningOn()=true
08-12 14:11:30.842  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:30.842  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:30.842  3973  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-12 14:11:30.842  3973  4134 D BluetoothAdapterProperties: ScanMode =  20
,08-12 14:11:30.843  3973  4134 D BluetoothAdapterProperties: State =  11
08-12 14:11:30.843  3973  4134 D BluetoothAdapterProperties: Setting state to 12
08-12 14:11:30.844  3973  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-12 14:11:30.844  3973  4134 I BluetoothAdapterState: Entering OnState
08-12 14:11:30.845  3896  3907 D BluetoothPan: onBluetoothStateChange on: true
08-12 14:11:30.845   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-12 14:11:30.845  3896  3906 D BluetoothMap: onBluetoothStateChange: up=true
08-12 14:11:30.846  1358  2007 D BluetoothMap: onBluetoothStateChange: up=true
08-12 14:11:30.848  3973  4138 D BluetoothAdapterProperties: Scan Mode:21
08-12 14:11:30.848  3973  4138 D BluetoothAdapterProperties: Discoverable Timeout:120
08-12 14:11:30.848  1358  1358 D BluetoothMap: Proxy object connected
08-12 14:11:30.848  1358  1358 D MapProfile: Bluetooth service connected
08-12 14:11:30.848  1358  1358 D BluetoothMap: getConnectedDevices()
,08-12 14:11:30.849  1358  1381 D BluetoothHeadset: onBluetoothStateChange: up=true
08-12 14:11:30.850  1358  2007 D BluetoothPbap: onBluetoothStateChange: up=true
08-12 14:11:30.850  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:30.850  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:30.850  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:30.850  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:30.850  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:30.850  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:30.850  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:30.850  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-12 14:11:30.852  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-12 14:11:30.852   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-12 14:11:30.854  3896  3907 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-12 14:11:30.854   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-12 14:11:30.854   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-12 14:11:30.854  1358  1379 D BluetoothPan: onBluetoothStateChange on: true
08-12 14:11:30.855   871   871 D BluetoothA2dp: Proxy object connected
08-12 14:11:30.855  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:30.855  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:30.855  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:30.855  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:30.855  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:30.855  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:30.855  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:30.855  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:30.856  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
08-12 14:11:30.856  1358  1358 D PanProfile: Bluetooth service connected
08-12 14:11:30.856  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-12 14:11:30.856  1358  2007 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-12 14:11:30.857  3973  3973 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-12 14:11:30.858  3973  3973 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-12 14:11:30.858  1358  1358 D BluetoothInputDevice: Proxy object connected
08-12 14:11:30.858  1358  1358 D HidProfile: Bluetooth service connected
08-12 14:11:30.859  3973  3973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 14:11:30.859  1911  2132 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-12 14:11:30.860  3896  3906 D BluetoothPbap: onBluetoothStateChange: up=true
08-12 14:11:30.861  3973  3973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 14:11:30.862  3973  3973 D ObexServerSockets: Succeed to create listening sockets 
,08-12 14:11:30.862  3973  3973 D ObexServerSockets0: startAccept()
08-12 14:11:30.862  3973  3973 D ObexServerSockets0: prepareForNewConnect()
08-12 14:11:30.862  1358  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-12 14:11:30.864  3973  3973 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-12 14:11:30.864  3973  3973 D BluetoothSdpJni: SDP Create record success - handle: 0
08-12 14:11:30.864  3973  4159 D ObexServerSockets0: Accepting socket connection...
08-12 14:11:30.864  1358  1358 D BluetoothA2dp: Proxy object connected
,08-12 14:11:30.864  3973  4160 D ObexServerSockets0: Accepting socket connection...
,08-12 14:11:30.866   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-12 14:11:30.867  3973  3973 D BluetoothMapService: onReceive
08-12 14:11:30.867  3973  3973 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-12 14:11:30.868  3973  3973 D BluetoothMapService: STATE_ON
,08-12 14:11:30.869  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:30.870  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:30.871  3896  3896 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-12 14:11:30.878  3896  3896 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-12 14:11:30.885  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-12 14:11:30.890  3973  3973 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-12 14:11:30.890  3973  3973 D ObexServerSockets0: prepareForNewConnect()
08-12 14:11:30.892  3896  3896 D BluetoothA2dp: Proxy object connected
,08-12 14:11:30.896  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-12 14:11:30.900  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,08-12 14:11:30.904  1358  1358 D BluetoothPbap: Proxy object connected
08-12 14:11:30.904  1358  1358 D PbapServerProfile: Bluetooth service connected
08-12 14:11:30.904  3896  3896 D BluetoothPbap: Proxy object connected
,08-12 14:11:30.905  3896  3896 D PbapServerProfile: Bluetooth service connected
,08-12 14:11:30.912  3973  4164 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 14:11:30.925  3973  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 14:11:30.926  3973  4168 I BtOppRfcommListener: Accept thread started.
,08-12 14:11:30.946  1911  1926 D BluetoothHeadset: Proxy object connected
,08-12 14:11:30.946  1358  1381 D BluetoothHeadset: Proxy object connected
08-12 14:11:30.946  1358  1358 D HeadsetProfile: Bluetooth service connected
,08-12 14:11:30.946   871   871 D BluetoothHeadset: Proxy object connected
08-12 14:11:30.946   871   871 D BluetoothHeadset: Proxy object connected
08-12 14:11:30.946   871   871 D BluetoothHeadset: Proxy object connected
,08-12 14:11:30.949  1358  1379 D BluetoothHeadset: Proxy object connected
08-12 14:11:30.949  1358  1358 D HeadsetProfile: Bluetooth service connected
,08-12 14:11:30.954   871   888 D BluetoothHeadset: Proxy object connected
,08-12 14:11:30.954   871   888 D BluetoothHeadset: Proxy object connected
,08-12 14:11:30.960  1911  2037 D BluetoothHeadset: Proxy object connected
,08-12 14:11:30.980  3896  3906 D BluetoothHeadset: Proxy object connected
,08-12 14:11:30.981  3896  3896 D HeadsetProfile: Bluetooth service connected
,08-12 14:11:32.409   871  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-12 14:11:32.479  3973  4134 D BluetoothAdapterState: Current state: ON, message: 23
,08-12 14:11:32.479  3973  4134 D BluetoothAdapterProperties: Setting state to 13
,08-12 14:11:32.480  3973  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-12 14:11:32.482  3973  4134 D BluetoothAdapterProperties: onBluetoothDisable()
08-12 14:11:32.489  3973  4134 I BluetoothAdapterState: Entering PendingCommandState
08-12 14:11:32.494  3973  3973 D BluetoothMapService: onReceive
08-12 14:11:32.494  3973  3973 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-12 14:11:32.495  3973  3973 D BluetoothMapService: STATE_TURNING_OFF
08-12 14:11:32.495  3973  3973 D BluetoothMapService: MAP Service closeService in
08-12 14:11:32.496  3973  3973 D BluetoothMapMasInstance0: MAP Service shutdown
08-12 14:11:32.496  3973  3973 D ObexServerSockets0: shutdown(block = true)
08-12 14:11:32.496  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:32.497  3973  4159 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-12 14:11:32.496  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:32.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:32.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:32.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:32.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:32.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:32.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:32.496  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:32.501  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:32.501  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-12 14:11:32.504  3973  3973 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-12 14:11:32.505  3973  4160 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-12 14:11:32.508  3973  4147 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-12 14:11:32.508  3973  4138 D BluetoothAdapterProperties: Scan Mode:20
,08-12 14:11:32.508  3973  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-12 14:11:32.509  3973  3973 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-12 14:11:32.509  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:32.509  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:32.509  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:32.509  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:32.509  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:32.509  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-12 14:11:32.509  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:32.509  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:32.509  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:32.509  3973  3973 I BtOppRfcommListener: stopping Accept Thread
08-12 14:11:32.510  3825  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-12 14:11:32.510  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-12 14:11:32.510  3973  4168 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-12 14:11:32.511  3973  4168 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-12 14:11:32.514  3973  3973 D HeadsetService: Received stop request...Stopping profile...
,08-12 14:11:32.515  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:32.515  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-12 14:11:32.516  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:32.525  1911  1936 D BluetoothHeadset: Proxy object disconnected
,08-12 14:11:32.525  3973  3973 D A2dpService: Received stop request...Stopping profile...
08-12 14:11:32.525  3973  4153 D A2dpStateMachine: Exit Disconnected: -1
08-12 14:11:32.526  1358  1379 D BluetoothHeadset: Proxy object disconnected
,08-12 14:11:32.526   871   871 D BluetoothHeadset: Proxy object disconnected
,08-12 14:11:32.526  1358  1358 D HeadsetProfile: Bluetooth service disconnected
,08-12 14:11:32.528  3896  3907 D BluetoothHeadset: Proxy object disconnected
08-12 14:11:32.529  1358  1358 D BluetoothA2dp: Proxy object disconnected
08-12 14:11:32.529   871   871 D BluetoothHeadset: Proxy object disconnected
08-12 14:11:32.529   871   871 D BluetoothHeadset: Proxy object disconnected
08-12 14:11:32.529  3896  3896 D DockEventReceiver: finishStartingService: stopping service
08-12 14:11:32.530   871   871 D BluetoothA2dp: Proxy object disconnected
,08-12 14:11:32.530  3973  3973 D HidService: Received stop request...Stopping profile...
08-12 14:11:32.530  3973  3973 D HidService: Stopping Bluetooth HidService
08-12 14:11:32.531  1358  1358 D BluetoothInputDevice: Proxy object disconnected
,08-12 14:11:32.531  1358  1358 D HidProfile: Bluetooth service disconnected
08-12 14:11:32.531  3973  3973 D HealthService: Received stop request...Stopping profile...
,08-12 14:11:32.535  3896  3896 D BluetoothA2dp: Proxy object disconnected
,08-12 14:11:32.535  3896  3896 D HeadsetProfile: Bluetooth service disconnected
08-12 14:11:32.535  3973  3973 D PanService: Received stop request...Stopping profile...
08-12 14:11:32.536  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-12 14:11:32.536  1358  1358 D PanProfile: Bluetooth service disconnected
08-12 14:11:32.536  3896  3896 D BluetoothInputDevice: Proxy object disconnected
,08-12 14:11:32.536  3896  3896 D HidProfile: Bluetooth service disconnected
08-12 14:11:32.537  3896  3896 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-12 14:11:32.537  3896  3896 D PanProfile: Bluetooth service disconnected
08-12 14:11:32.537  3973  3973 D BluetoothMapService: Received stop request...Stopping profile...
08-12 14:11:32.537  3973  3973 D BluetoothMapService: stop()
08-12 14:11:32.537  3973  3973 D BluetoothMapAppObserver: deinitObservers()
08-12 14:11:32.537  3973  3973 D BluetoothMapAppObserver: removeReceiver()
08-12 14:11:32.538  1358  1358 D BluetoothMap: Proxy object disconnected
08-12 14:11:32.538  1358  1358 D MapProfile: Bluetooth service disconnected
08-12 14:11:32.539  3896  3896 D BluetoothMap: Proxy object disconnected
08-12 14:11:32.539  3896  3896 D MapProfile: Bluetooth service disconnected
08-12 14:11:32.539  3973  3973 V BluetoothAdapterState: isTurningOff()=true
08-12 14:11:32.539  3973  3973 V BluetoothAdapterState: isTurningOn()=false
08-12 14:11:32.539  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:32.539  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
,08-12 14:11:32.541  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-12 14:11:32.544  3973  3973 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-12 14:11:32.544  3973  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-12 14:11:32.544  3973  4144 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-12 14:11:32.544  3973  3973 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-12 14:11:32.544  3973  4144 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-12 14:11:32.544  3973  4144 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-12 14:11:32.545  3973  4138 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
08-12 14:11:32.545  3973  3973 V BluetoothAdapterState: isTurningOff()=true
,08-12 14:11:32.545  3973  3973 V BluetoothAdapterState: isTurningOn()=false
08-12 14:11:32.545  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
,08-12 14:11:32.545  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:32.546  3973  4144 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-12 14:11:32.546  3973  4144 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-12 14:11:32.547  3973  4144 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-12 14:11:32.547  3973  4144 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-12 14:11:32.547  3973  4144 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-12 14:11:32.547  3973  4144 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-12 14:11:32.547  3973  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-12 14:11:32.548  3973  3973 V BluetoothAdapterState: isTurningOff()=true
08-12 14:11:32.548  3973  3973 V BluetoothAdapterState: isTurningOn()=false
,08-12 14:11:32.548  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:32.548  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:32.548  3973  3973 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-12 14:11:32.548  3973  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-12 14:11:32.549  3973  3973 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-12 14:11:32.549  3973  3973 V BluetoothAdapterState: isTurningOff()=true
,08-12 14:11:32.549  3973  3973 V BluetoothAdapterState: isTurningOn()=false
,08-12 14:11:32.549  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
,08-12 14:11:32.549  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
,08-12 14:11:32.549  3973  3973 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-12 14:11:32.550  3973  4138 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-12 14:11:32.550  3973  3973 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-12 14:11:32.550  3973  3973 V BluetoothAdapterState: isTurningOff()=true
,08-12 14:11:32.550  3973  3973 V BluetoothAdapterState: isTurningOn()=false
,08-12 14:11:32.550  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:32.551  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:32.551  3973  3973 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-12 14:11:32.551  3973  3973 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-12 14:11:32.552  3973  3973 D BluetoothMapService: MAP Service closeService in
,08-12 14:11:32.552  3973  3973 V BluetoothAdapterState: isTurningOff()=true
08-12 14:11:32.552  3973  3973 V BluetoothAdapterState: isTurningOn()=false
08-12 14:11:32.552  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
,08-12 14:11:32.552  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:32.553  3973  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-12 14:11:32.553  3973  4134 D BluetoothAdapterProperties: Setting state to 15
08-12 14:11:32.553  3973  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-12 14:11:32.553  3973  4134 I BluetoothAdapterState: Entering BleOnState
08-12 14:11:32.553  3973  3973 D BluetoothMapService: cleanup()
,08-12 14:11:32.554  3973  3973 D BluetoothMapService: MAP Service closeService in
08-12 14:11:32.554  3896  3906 D BluetoothPan: onBluetoothStateChange on: false
08-12 14:11:32.555   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-12 14:11:32.555  1358  1358 D BluetoothPbap: Proxy object disconnected
08-12 14:11:32.555  1358  1358 D PbapServerProfile: Bluetooth service disconnected
08-12 14:11:32.556  3896  4172 D BluetoothMap: onBluetoothStateChange: up=false
,08-12 14:11:32.556  1358  1379 D BluetoothMap: onBluetoothStateChange: up=false
,08-12 14:11:32.555  3896  3896 D BluetoothPbap: Proxy object disconnected
08-12 14:11:32.558  3896  3907 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-12 14:11:32.559  1358  2007 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-12 14:11:32.559  1358  1381 D BluetoothPbap: onBluetoothStateChange: up=false
08-12 14:11:32.562   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-12 14:11:32.563  3896  3906 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-12 14:11:32.563   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-12 14:11:32.563  3896  3896 D PbapServerProfile: Bluetooth service disconnected
08-12 14:11:32.563   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-12 14:11:32.563  1358  1379 D BluetoothPan: onBluetoothStateChange on: false
,08-12 14:11:32.564  1358  2007 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-12 14:11:32.564  1911  2132 D BluetoothHeadset: onBluetoothStateChange: up=false
08-12 14:11:32.565  3896  4172 D BluetoothPbap: onBluetoothStateChange: up=false
,08-12 14:11:32.565  1358  1381 D BluetoothA2dp: onBluetoothStateChange: up=false
08-12 14:11:32.566  3896  3907 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-12 14:11:32.566  3973  4134 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-12 14:11:32.566  3973  4134 D BluetoothAdapterProperties: Setting state to 16
,08-12 14:11:32.566  3973  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-12 14:11:32.567  3973  4134 D BluetoothAdapterProperties: onBleDisable
08-12 14:11:32.568  3973  4134 I BluetoothAdapterState: Entering PendingCommandState
08-12 14:11:32.568  3973  4135 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-12 14:11:32.569  3973  4144 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-12 14:11:32.569  3973  4144 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-12 14:11:32.571  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:32.571  3973  4138 D BluetoothAdapterProperties: Scan Mode:20
08-12 14:11:32.572  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-12 14:11:32.573  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:32.574  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:32.575  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:32.578  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-12 14:11:32.579  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,08-12 14:11:32.769  3973  4138 I bt_hci  : shut_down
,08-12 14:11:32.780  3973  4142 I bt_vendor: low_power_mode_cb
08-12 14:11:32.780  3973  4142 D bt_hwcfg: hw_epilog_process
,08-12 14:11:32.808  3973  4142 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-12 14:11:32.809  3973  4142 I bt_vendor: epilog_cb
08-12 14:11:32.809  3973  4142 I bt_hci  : epilog_finished_callback
,08-12 14:11:32.816  3973  4138 I bt_hci_h4: hal_close
,08-12 14:11:32.818  3973  4138 I bt_userial_vendor: device fd = 51 close
,08-12 14:11:32.934  3973  4135 D bt_stack_manager: event_shut_down_stack finished.
,08-12 14:11:32.935  3973  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-12 14:11:32.942  3973  4134 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-12 14:11:32.942  3973  3973 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-12 14:11:32.944  3973  3973 D BtGatt.GattService: Received stop request...Stopping profile...
,08-12 14:11:32.944  3973  3973 D BtGatt.GattService: stop()
,08-12 14:11:32.945  3973  3973 D BtGatt.AdvertiseManager: advertise clients cleared
,08-12 14:11:32.949  3973  3973 V BluetoothAdapterState: isTurningOff()=false
08-12 14:11:32.950  3973  3973 V BluetoothAdapterState: isTurningOn()=false
08-12 14:11:32.950  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:32.950  3973  3973 V BluetoothAdapterState: isBleTurningOff()=true
08-12 14:11:32.951  3973  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-12 14:11:32.952  3973  4134 D BluetoothAdapterProperties: Setting state to 10
08-12 14:11:32.952  3973  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-12 14:11:32.954  3973  4134 I BluetoothAdapterState: Entering OffState
08-12 14:11:32.956   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-12 14:11:32.978  3973  3973 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-12 14:11:32.978  3973  3973 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-12 14:11:32.985  3973  4135 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-12 14:11:32.985  3973  3973 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-12 14:11:32.995  3973  4135 D bt_stack_manager: event_clean_up_stack finished.
,08-12 14:11:33.001  3973  3973 I art     : System.exit called, status: 0
,08-12 14:11:33.001  3973  3973 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-12 14:11:33.065   871   881 I ActivityManager: Process com.android.bluetooth (pid 3973) has died
,08-12 14:11:34.041  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:34.052  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:34.055  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:34.088  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 14:11:34.088  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 14:11:34.088  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-12 14:11:34.088  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 14:11:34.118  3532  3532 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 14:11:34.119  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 14:11:34.119  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-12 14:11:35.476  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-12 14:11:35.476  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:38.485  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 14:11:38.485  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1281129 added. We now have 6 listener(s)
08-12 14:11:38.485  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:38.489  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 14:11:38.490  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fffcae added. We now have 7 listener(s)
,08-12 14:11:38.490  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:38.492  3825  3875 I System.out: IsBluetoothEnabled
,08-12 14:11:38.502  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:38.539   871   888 I ActivityManager: Start proc 4180:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-12 14:11:38.671  4180  4180 D AdapterServiceConfig: Adding HeadsetService
,08-12 14:11:38.671  4180  4180 D AdapterServiceConfig: Adding A2dpService
,08-12 14:11:38.671  4180  4180 D AdapterServiceConfig: Adding HidService
,08-12 14:11:38.671  4180  4180 D AdapterServiceConfig: Adding HealthService
,08-12 14:11:38.671  4180  4180 D AdapterServiceConfig: Adding PanService
,08-12 14:11:38.671  4180  4180 D AdapterServiceConfig: Adding GattService
,08-12 14:11:38.672  4180  4180 D AdapterServiceConfig: Adding BluetoothMapService
,08-12 14:11:38.686   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2501f11:true
,08-12 14:11:38.687  4180  4180 D BluetoothAdapterState: make() - Creating AdapterState
,08-12 14:11:38.691  4180  4180 I bt_bluedroid: init
,08-12 14:11:38.692  4180  4192 I BluetoothAdapterState: Entering OffState
,08-12 14:11:38.697  4180  4193 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-12 14:11:38.697  4180  4193 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-12 14:11:38.698  4180  4193 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-12 14:11:38.698  4180  4193 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-12 14:11:38.700  4180  4180 I bt_bluedroid: get_profile_interface socket
,08-12 14:11:38.702  4180  4180 I bt_bluedroid: get_profile_interface sdp
08-12 14:11:38.702  4180  4196 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-12 14:11:38.705  4180  4196 D BluetoothAdapterProperties: Name is: Nexus 6
,08-12 14:11:38.707  4180  4191 I bt_bluedroid: config_hci_snoop_log
,08-12 14:11:38.716   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-12 14:11:38.729  4180  4192 D BluetoothAdapterState: Current state: OFF, message: 0
,08-12 14:11:38.729  4180  4192 D BluetoothAdapterProperties: Setting state to 14
08-12 14:11:38.730  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-12 14:11:38.733  4180  4192 D BluetoothBondStateMachine: make
,08-12 14:11:38.739  4180  4197 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-12 14:11:38.744  4180  4192 I BluetoothAdapterState: Entering PendingCommandState
,08-12 14:11:38.747  4180  4180 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-12 14:11:38.755  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:38.757  4180  4180 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-12 14:11:38.759  4180  4180 D BtGatt.GattService: Received start request. Starting profile...
,08-12 14:11:38.759  4180  4180 D BtGatt.GattService: start()
,08-12 14:11:38.759  4180  4180 I bt_bluedroid: get_profile_interface gatt
,08-12 14:11:38.760  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:38.761  4180  4180 D BtGatt.AdvertiseManager: advertise manager created
,08-12 14:11:38.769  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-12 14:11:38.769  4180  4180 V BluetoothAdapterState: isTurningOn()=false
08-12 14:11:38.769  4180  4180 V BluetoothAdapterState: isBleTurningOn()=true
08-12 14:11:38.770  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:38.770  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-12 14:11:38.771  4180  4192 I bt_bluedroid: enable
,08-12 14:11:38.771  4180  4193 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-12 14:11:38.772  4180  4193 I bt_hci  : start_up
,08-12 14:11:38.792  4180  4193 I bt_vendor: alloc value 0xb3a25189
08-12 14:11:38.792  4180  4193 I bt_vendor: init
08-12 14:11:38.793  4180  4193 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-12 14:11:38.793  4180  4193 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-12 14:11:38.903  4180  4193 D bt_hci  : start_up starting async portion
,08-12 14:11:38.903  4180  4200 I bt_hci  : event_finish_startup
,08-12 14:11:38.905  4180  4200 I bt_hci_h4: hal_open
,08-12 14:11:38.907  4180  4200 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-12 14:11:38.917  4180  4200 I bt_userial_vendor: device fd = 51 open
,08-12 14:11:38.945  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-12 14:11:38.976  4180  4200 D bt_hwcfg: Chipset BCM4354A2
,08-12 14:11:38.977  4180  4200 D bt_hwcfg: Target name = [BCM4354A2]
08-12 14:11:38.978  4180  4200 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-12 14:11:39.662  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-12 14:11:39.664  4180  4200 D bt_hwcfg: Settlement delay -- 100 ms
08-12 14:11:39.664  4180  4200 I bt_hwcfg: Setting fw settlement delay to 100 
,08-12 14:11:39.781  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-12 14:11:39.782  4180  4200 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-12 14:11:39.811  4180  4200 I bt_hwcfg: vendor lib fwcfg completed
,08-12 14:11:39.812  4180  4200 I bt_vendor: firmware callback
08-12 14:11:39.812  4180  4200 I bt_hci  : firmware_config_callback
,08-12 14:11:39.823  4180  4202 I bt_btu  : btu_task pending for preload complete event
,08-12 14:11:39.824  4180  4202 I bt_btu_task: Bluetooth chip preload is complete
08-12 14:11:39.824  4180  4202 I bt_btu  : btu_task received preload complete event
,08-12 14:11:39.838  4180  4202 I         : BTE_InitTraceLevels -- TRC_HCI
,08-12 14:11:39.838  4180  4202 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-12 14:11:39.839  4180  4202 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-12 14:11:39.839  4180  4202 I         : BTE_InitTraceLevels -- TRC_AVDT
08-12 14:11:39.839  4180  4202 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-12 14:11:39.839  4180  4202 I         : BTE_InitTraceLevels -- TRC_A2D
08-12 14:11:39.841  4180  4202 I         : BTE_InitTraceLevels -- TRC_BNEP
08-12 14:11:39.841  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTM
,08-12 14:11:39.841  4180  4202 I         : BTE_InitTraceLevels -- TRC_GAP
08-12 14:11:39.842  4180  4202 I         : BTE_InitTraceLevels -- TRC_PAN
,08-12 14:11:39.843  4180  4202 I         : BTE_InitTraceLevels -- TRC_SDP
,08-12 14:11:39.845  4180  4202 I         : BTE_InitTraceLevels -- TRC_GATT
08-12 14:11:39.845  4180  4202 I         : BTE_InitTraceLevels -- TRC_SMP
,08-12 14:11:39.846  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-12 14:11:39.847  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-12 14:11:39.980  4180  4202 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a2d9d
08-12 14:11:39.981  4180  4202 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a2d9d 
,08-12 14:11:39.992  4180  4196 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-12 14:11:39.994  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-12 14:11:39.995  4180  4196 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-12 14:11:40.001  4180  4196 D BluetoothAdapterProperties: Name is: Nexus 6
,08-12 14:11:40.003  4180  4196 D BluetoothAdapterProperties: Scan Mode:20
,08-12 14:11:40.003  4180  4196 D BluetoothAdapterProperties: Discoverable Timeout:120
08-12 14:11:40.004  4180  4196 D bt_hci  : do_postload posting postload work item
,08-12 14:11:40.004  4180  4200 I bt_hci  : event_postload
,08-12 14:11:40.004  4180  4200 I bt_vendor: sco_config_cb
08-12 14:11:40.004  4180  4200 I bt_hci  : sco_config_callback postload finished.
,08-12 14:11:40.009  4180  4196 D bt_bte_conf: Device ID record 1 : primary
08-12 14:11:40.009  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:40.009  4180  4196 D bt_bte_conf:   vendorId            = 000f
08-12 14:11:40.010  4180  4196 D bt_bte_conf:   vendorIdSource      = 0001
08-12 14:11:40.010  4180  4196 D bt_bte_conf:   product             = 1200
08-12 14:11:40.010  4180  4196 D bt_bte_conf:   version             = 1436
08-12 14:11:40.011  4180  4196 D bt_bte_conf:   clientExecutableURL = 
,08-12 14:11:40.011  4180  4196 D bt_bte_conf:   serviceDescription  = 
08-12 14:11:40.011  4180  4196 D bt_bte_conf:   documentationURL    = 
08-12 14:11:40.011  4180  4200 I bt_vendor: low_power_mode_cb
08-12 14:11:40.012  4180  4196 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-12 14:11:40.012  4180  4193 D bt_stack_manager: event_start_up_stack finished
08-12 14:11:40.014  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-12 14:11:40.015  4180  4192 D BluetoothAdapterProperties: Setting state to 15
08-12 14:11:40.015  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-12 14:11:40.016  4180  4192 I BluetoothAdapterState: Entering BleOnState
,08-12 14:11:40.022  4180  4192 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-12 14:11:40.022  4180  4192 D BluetoothAdapterProperties: Setting state to 11
08-12 14:11:40.023  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-12 14:11:40.037  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
08-12 14:11:40.038  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:40.039  4180  4180 D HeadsetService: Received start request. Starting profile...
,08-12 14:11:40.047  4180  4180 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-12 14:11:40.047  4180  4180 D HeadsetStateMachine: make
08-12 14:11:40.048  4180  4192 I BluetoothAdapterState: Entering PendingCommandState
,08-12 14:11:40.055  4180  4180 D HeadsetStateMachine: max_hf_connections = 1
08-12 14:11:40.055  4180  4180 I bt_bluedroid: get_profile_interface handsfree
,08-12 14:11:40.055  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-12 14:11:40.055  4180  4196 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-12 14:11:40.062  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:40.064  4180  4180 D A2dpService: Received start request. Starting profile...
,08-12 14:11:40.064  4180  4180 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-12 14:11:40.065  4180  4180 I bt_bluedroid: get_profile_interface avrcp
,08-12 14:11:40.071  4180  4180 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-12 14:11:40.071  4180  4180 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-12 14:11:40.071  4180  4180 D A2dpStateMachine: make
,08-12 14:11:40.077  4180  4180 I bt_bluedroid: get_profile_interface a2dp
08-12 14:11:40.078  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-12 14:11:40.082  4180  4211 D A2dpStateMachine: Enter Disconnected: -2
08-12 14:11:40.082  4180  4180 I BluetoothHidServiceJni: classInitNative: succeeds
08-12 14:11:40.083  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
08-12 14:11:40.084  4180  4180 D HidService: Received start request. Starting profile...
,08-12 14:11:40.084  4180  4180 I bt_bluedroid: get_profile_interface hidhost
08-12 14:11:40.084  4180  4196 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39843e5
08-12 14:11:40.084  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-12 14:11:40.084  4180  4180 D HidService: setHidService(): set to: null
,08-12 14:11:40.085  4180  4180 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-12 14:11:40.086  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:40.087  4180  4180 D HealthService: Received start request. Starting profile...
,08-12 14:11:40.089  4180  4180 I bt_bluedroid: get_profile_interface health
,08-12 14:11:40.091  4180  4180 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-12 14:11:40.092  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-12 14:11:40.093  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:40.093  4180  4180 D PanService: Received start request. Starting profile...
08-12 14:11:40.094  4180  4180 D BluetoothPanServiceJni: initializeNative(L110): pan
08-12 14:11:40.094  4180  4180 I bt_bluedroid: get_profile_interface pan
,08-12 14:11:40.095  4180  4196 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-12 14:11:40.097  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
,08-12 14:11:40.098  4180  4180 D BluetoothMapService: Received start request. Starting profile...
,08-12 14:11:40.099  4180  4180 D BluetoothMapService: start()
,08-12 14:11:40.102  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-12 14:11:40.102  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-12 14:11:40.102  4180  4180 D BluetoothMapAppObserver: createReceiver()
,08-12 14:11:40.104  4180  4180 D BluetoothMapAppObserver: initObservers()
,08-12 14:11:40.104  4180  4180 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-12 14:11:40.113  4180  4209 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-12 14:11:40.114  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-12 14:11:40.114  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,08-12 14:11:40.114  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:40.114  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
,08-12 14:11:40.115  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
,08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
,08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isTurningOff()=false
08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isTurningOn()=true
08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:40.116  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:40.118  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-12 14:11:40.118  4180  4180 V BluetoothAdapterState: isTurningOn()=true
08-12 14:11:40.118  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:40.118  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:40.118  4180  4180 V BluetoothAdapterState: isTurningOff()=false
08-12 14:11:40.119  4180  4180 V BluetoothAdapterState: isTurningOn()=true
08-12 14:11:40.119  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-12 14:11:40.119  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-12 14:11:40.119  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-12 14:11:40.119  4180  4192 D BluetoothAdapterProperties: ScanMode =  20
08-12 14:11:40.119  4180  4192 D BluetoothAdapterProperties: State =  11
08-12 14:11:40.119  4180  4192 D BluetoothAdapterProperties: Setting state to 12
08-12 14:11:40.119  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-12 14:11:40.120  4180  4192 I BluetoothAdapterState: Entering OnState
08-12 14:11:40.121  3896  3907 D BluetoothPan: onBluetoothStateChange on: true
08-12 14:11:40.122  4180  4196 D BluetoothAdapterProperties: Scan Mode:21
08-12 14:11:40.122  4180  4196 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-12 14:11:40.123   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-12 14:11:40.124  3896  3906 D BluetoothMap: onBluetoothStateChange: up=true
08-12 14:11:40.126  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:40.126  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:40.126  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:40.126  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:40.126  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:40.126  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:40.126  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:40.126  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-12 14:11:40.126  1358  2007 D BluetoothMap: onBluetoothStateChange: up=true
08-12 14:11:40.127  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-12 14:11:40.127  3896  3907 D BluetoothA2dp: onBluetoothStateChange: up=true
08-12 14:11:40.128  1358  1358 D BluetoothMap: Proxy object connected
,08-12 14:11:40.128  1358  1358 D MapProfile: Bluetooth service connected
08-12 14:11:40.128  1358  1358 D BluetoothMap: getConnectedDevices()
08-12 14:11:40.129  1358  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
08-12 14:11:40.129  1358  2007 D BluetoothPbap: onBluetoothStateChange: up=true
08-12 14:11:40.131   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-12 14:11:40.131  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-12 14:11:40.131   871   871 D BluetoothA2dp: Proxy object connected
08-12 14:11:40.131  3896  3906 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-12 14:11:40.132  4180  4180 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-12 14:11:40.133   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-12 14:11:40.133   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-12 14:11:40.134  1358  1381 D BluetoothPan: onBluetoothStateChange on: true
08-12 14:11:40.134  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 14:11:40.134  3896  3896 D BluetoothPan: BluetoothPAN Proxy object connected
08-12 14:11:40.134  3896  3896 D PanProfile: Bluetooth service connected
08-12 14:11:40.134  3896  3896 D BluetoothMap: Proxy object connected
08-12 14:11:40.134  3896  3896 D MapProfile: Bluetooth service connected
08-12 14:11:40.134  3896  3896 D BluetoothMap: getConnectedDevices()
,08-12 14:11:40.135  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 14:11:40.136  4180  4180 D ObexServerSockets: Succeed to create listening sockets 
,08-12 14:11:40.136  4180  4180 D ObexServerSockets0: startAccept()
08-12 14:11:40.137  4180  4180 D ObexServerSockets0: prepareForNewConnect()
08-12 14:11:40.137  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
08-12 14:11:40.138  1358  1358 D PanProfile: Bluetooth service connected
08-12 14:11:40.138  1358  2007 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-12 14:11:40.139  4180  4180 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-12 14:11:40.139  4180  4180 D BluetoothSdpJni: SDP Create record success - handle: 0
08-12 14:11:40.140  4180  4216 D ObexServerSockets0: Accepting socket connection...
08-12 14:11:40.140  4180  4217 D ObexServerSockets0: Accepting socket connection...
08-12 14:11:40.142  1358  1358 D BluetoothInputDevice: Proxy object connected
08-12 14:11:40.142  1358  1358 D HidProfile: Bluetooth service connected
,08-12 14:11:40.142  1911  2132 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-12 14:11:40.143  3896  4172 D BluetoothPbap: onBluetoothStateChange: up=true
,08-12 14:11:40.145  1358  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-12 14:11:40.147  1358  1358 D BluetoothA2dp: Proxy object connected
,08-12 14:11:40.147  3896  3906 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-12 14:11:40.150   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-12 14:11:40.152  4180  4180 D BluetoothMapService: onReceive
,08-12 14:11:40.152  4180  4180 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-12 14:11:40.152  4180  4180 D BluetoothMapService: STATE_ON
,08-12 14:11:40.154  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:40.156  3896  3896 D BluetoothA2dp: Proxy object connected
,08-12 14:11:40.158  3896  3896 D BluetoothInputDevice: Proxy object connected
,08-12 14:11:40.158  3896  3896 D HidProfile: Bluetooth service connected
,08-12 14:11:40.164  3896  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-12 14:11:40.170  3896  3896 D DockEventReceiver: finishStartingService: stopping service
,08-12 14:11:40.171  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-12 14:11:40.180  1358  1358 D BluetoothPbap: Proxy object connected
,08-12 14:11:40.180  1358  1358 D PbapServerProfile: Bluetooth service connected
08-12 14:11:40.180  3896  3896 D BluetoothPbap: Proxy object connected
,08-12 14:11:40.180  3896  3896 D PbapServerProfile: Bluetooth service connected
08-12 14:11:40.180  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-12 14:11:40.180  4180  4180 D ObexServerSockets0: prepareForNewConnect()
,08-12 14:11:40.187  4180  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 14:11:40.212  4180  4226 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 14:11:40.213  4180  4226 I BtOppRfcommListener: Accept thread started.
,08-12 14:11:40.226  1911  1926 D BluetoothHeadset: Proxy object connected
,08-12 14:11:40.227  1358  1381 D BluetoothHeadset: Proxy object connected
,08-12 14:11:40.227   871   871 D BluetoothHeadset: Proxy object connected
08-12 14:11:40.227  1358  1358 D HeadsetProfile: Bluetooth service connected
08-12 14:11:40.227  3896  3907 D BluetoothHeadset: Proxy object connected
,08-12 14:11:40.228   871   871 D BluetoothHeadset: Proxy object connected
08-12 14:11:40.228   871   871 D BluetoothHeadset: Proxy object connected
08-12 14:11:40.228  3896  3896 D HeadsetProfile: Bluetooth service connected
,08-12 14:11:40.229  1358  2007 D BluetoothHeadset: Proxy object connected
08-12 14:11:40.231  1358  1358 D HeadsetProfile: Bluetooth service connected
,08-12 14:11:40.233   871   888 D BluetoothHeadset: Proxy object connected
08-12 14:11:40.234   871   888 D BluetoothHeadset: Proxy object connected
,08-12 14:11:40.244  1911  2037 D BluetoothHeadset: Proxy object connected
,08-12 14:11:40.248  3896  4172 D BluetoothHeadset: Proxy object connected
08-12 14:11:40.249  3896  3896 D HeadsetProfile: Bluetooth service connected
,08-12 14:11:40.523  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:40.523  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:40.523  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:40.523  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-12 14:11:40.523  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:40.523  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:40.523  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:40.523  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-12 14:11:40.530  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-12 14:11:40.533  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 14:11:40.533  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@58fca4f added. We now have 8 listener(s)
,08-12 14:11:40.534  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:40.539   871  2003 D WifiService: setWifiEnabled: false pid=3825, uid=10000
,08-12 14:11:40.539   871  2003 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-12 14:11:40.552  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:40.553   871   882 D WifiService: setWifiEnabled: true pid=3825, uid=10000
,08-12 14:11:40.553   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-12 14:11:40.566   871  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-12 14:11:40.584  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:40.584  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:40.584  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:40.584  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:40.584  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:40.584  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-12 14:11:40.584  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-12 14:11:40.584  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-12 14:11:40.589  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-12 14:11:40.613   871  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-12 14:11:40.614   871  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-12 14:11:40.615   871  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-12 14:11:40.616   871  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-12 14:11:40.616   871  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-12 14:11:40.616   871  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-12 14:11:40.616   871  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-12 14:11:40.630   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-12 14:11:40.631   871  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.20 rxSuccessRate=0.25 delta 1000 -> 1000
,08-12 14:11:40.632   372   869 D CommandListener: Setting iface cfg
,08-12 14:11:40.633   871  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-12 14:11:40.634   871  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-12 14:11:40.638   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-12 14:11:40.639   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-12 14:11:40.646   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-12 14:11:40.679   871  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-12 14:11:40.680   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-12 14:11:40.681   871  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-12 14:11:40.689  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-12 14:11:40.693   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 14:11:40.693   871   891 I Adreno  : Build Date                       : 10/20/15
08-12 14:11:40.693   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 14:11:40.693   871   891 I Adreno  : Local Branch                     : M14
08-12 14:11:40.693   871   891 I Adreno  : Remote Branch                    : 
08-12 14:11:40.693   871   891 I Adreno  : Remote Branch                    : 
08-12 14:11:40.693   871   891 I Adreno  : Reconstruct Branch               : 
,08-12 14:11:40.720   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-12 14:11:40.725  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-12 14:11:40.740   280   359 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (255 us)
,08-12 14:11:41.161  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-12 14:11:41.200  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-12 14:11:41.201  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-12 14:11:41.206   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 14:11:41.215   871  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-12 14:11:41.215   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-12 14:11:41.216   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-12 14:11:41.232   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-12 14:11:41.242   372   869 D CommandListener: Setting iface cfg
,08-12 14:11:41.244   871  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-12 14:11:41.261   871  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-12 14:11:41.262   871  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-12 14:11:41.267   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-12 14:11:41.273   871  4236 D DhcpClient: Receive thread started
,08-12 14:11:41.375   871  1307 E native  : do suspend false
,08-12 14:11:41.398   871  2078 D DhcpClient: Broadcasting DHCPDISCOVER
,08-12 14:11:41.403  3825  3825 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 14:11:41.403  3825  3825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-12 14:11:41.413   871  4236 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-12 14:11:41.459   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-12 14:11:41.459   871  2078 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-12 14:11:41.460   871  2078 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-12 14:11:41.462  3825  3825 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bbfb469 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5f765dc, 16908290=android.view.AbsSavedState$1@5f765dc}, android:focusedViewId=100}]}]
,08-12 14:11:41.462  3825  3825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-12 14:11:41.462  3825  3825 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-12 14:11:41.462  3825  3825 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-12 14:11:41.469   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-12 14:11:41.471   871  4236 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-12 14:11:41.474   871  2078 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-12 14:11:41.475   372   869 D CommandListener: Setting iface cfg
,08-12 14:11:41.475   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-12 14:11:41.476   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-12 14:11:41.476   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-12 14:11:41.478   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-12 14:11:41.483   871  2078 D DhcpClient: Scheduling renewal in 86399s
,08-12 14:11:41.493   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-12 14:11:41.493   871  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 14:11:41.494   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-12 14:11:41.496   871  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-12 14:11:41.497   871  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-12 14:11:41.520   871  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-12 14:11:41.520   871  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-12 14:11:41.521   871  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-12 14:11:41.522   871  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-12 14:11:41.525   871  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-12 14:11:41.530   871  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-12 14:11:41.534   871  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-12 14:11:41.534   871  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-12 14:11:41.534   871  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-12 14:11:41.535   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-12 14:11:41.535   871  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-12 14:11:41.535   871  1310 D ConnectivityService:    accepting network in place of null
08-12 14:11:41.536   871  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-12 14:11:41.544   871  4235 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153803, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:11:41.564   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-12 14:11:41.571  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:41.571  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:41.571  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:41.571  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:41.571  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:41.571  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:41.571  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:41.571  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:41.577  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:41.583  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-12 14:11:41.583  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-12 14:11:41.585  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bbfb469 Bundle[{}]
,08-12 14:11:41.586  3825  3875 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 14:11:41.586  3825  3875 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-12 14:11:41.586  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-12 14:11:41.587  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-12 14:11:41.587  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-12 14:11:41.588  3825  3875 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 14:11:41.592  3825  3875 I System.out: Running OutgoingSocketThread
,08-12 14:11:41.595  3825  4245 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 431)
,08-12 14:11:41.597  3825  4245 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41519
,08-12 14:11:41.597  3825  4245 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-12 14:11:41.606   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-12 14:11:41.606   871  4234 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:816::200e
,08-12 14:11:41.609   871  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-12 14:11:41.609   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-12 14:11:41.613   871  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-12 14:11:41.615   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-12 14:11:41.626  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-12 14:11:41.626  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:41.626  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:41.626  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:41.626  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:41.626  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:41.626  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:41.626  3825  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:41.628  3825  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:41.631  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-12 14:11:41.637  1730  1730 D SystemUpdateService: onCreate
,08-12 14:11:41.642  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-12 14:11:41.652  1730  4248 I SystemUpdateService: active receiver: enabled
,08-12 14:11:41.661  1730  4248 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-12 14:11:41.664  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-12 14:11:41.666  1730  2497 I iu.UploadsManager: num queued entries: 0
,08-12 14:11:41.666  1730  2497 I iu.UploadsManager: num updated entries: 0
,08-12 14:11:41.672  1730  4248 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-12 14:11:41.672  1730  4248 I SystemUpdateService: now status is 0 (complete)
08-12 14:11:41.672  1730  4248 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-12 14:11:41.673  1730  4248 I SystemUpdateService: file has been verified
08-12 14:11:41.673  1730  4248 I SystemUpdateService: OTA package size = 12249756
08-12 14:11:41.674  1730  2497 I iu.SyncManager: NEXT; no task
,08-12 14:11:41.682  1730  4248 I SystemUpdateService: showing system update notification
,08-12 14:11:41.682  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-12 14:11:41.682   871  4234 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 12 Aug 2016 12:11:41 GMT], X-Android-Received-Millis=[1471003901682], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471003901653]}
08-12 14:11:41.683  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-12 14:11:41.684   871  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-12 14:11:41.684   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-12 14:11:41.685   871  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-12 14:11:41.685  3987  3987 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-12 14:11:41.687   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-12 14:11:41.692  1730  4251 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-12 14:11:41.695   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 14:11:41.696   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-12 14:11:41.697   871  1333 D SurfaceControl: Excessive delay in setPowerMode(): 221ms
,08-12 14:11:41.698   871   891 I DreamManagerService: Entering dreamland.
08-12 14:11:41.699   871   891 I PowerManagerService: Dozing...
08-12 14:11:41.692  1730  4251 W BaseAppContext: Using Auth Proxy for data requests.
,08-12 14:11:41.700   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
08-12 14:11:41.701  1730  4251 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
08-12 14:11:41.702  3987  3987 D SprintDMHelper: simOperator: 
08-12 14:11:41.702  3987  3987 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-12 14:11:41.710  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:41.711  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 14:11:41.748  1730  1730 D SystemUpdateService: onDestroy
,08-12 14:11:41.748   376  1317 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-12 14:11:41.749   376  1317 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
08-12 14:11:41.749   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 14:11:41.753   871  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-12 14:11:41.753  1507  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-12 14:11:41.753  1507  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-12 14:11:41.753  1507  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 14:11:41.753  1507  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 14:11:41.755   871  1307 E native  : do suspend false
,08-12 14:11:41.761   871  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 14:11:41.770  1730  4251 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-12 14:11:41.779  1900  4259 D NfcService: Discovery configuration equal, not updating.
,08-12 14:11:41.789   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-12 14:11:41.790   871  1307 E native  : do suspend true
,08-12 14:11:41.839  3074  4254 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-12 14:11:41.886   376  1278 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-12 14:11:41.886   376  1278 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-12 14:11:42.254   871  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,08-12 14:11:42.595  3825  3875 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 432)
,08-12 14:11:42.596  3825  3875 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 432)
,08-12 14:11:42.606  3825  3875 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 437)
,08-12 14:11:42.608  3825  3875 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-12 14:11:42.609  3825  3875 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-12 14:11:42.612   871  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-12 14:11:42.617  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 14:11:42.617  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8796e5 added. We now have 2 listener(s)
,08-12 14:11:42.623  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 14:11:42.624  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 14:11:42.624  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 14:11:42.625  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 14:11:42.625  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d335ba added. We now have 9 listener(s)
08-12 14:11:42.625  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 14:11:42.626  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 14:11:42.629  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 14:11:42.637  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:42.637  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:42.637  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:42.637  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:42.637  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:42.637  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:42.637  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:42.637  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:42.640  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:42.641  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 14:11:42.641  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 14:11:42.641  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28303c8 added. We now have 3 listener(s)
,08-12 14:11:42.643  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 14:11:42.643  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 14:11:42.643  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 14:11:42.644  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 14:11:42.644  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19fbc61 added. We now have 10 listener(s)
,08-12 14:11:42.644  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 14:11:42.644  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 14:11:42.644  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:42.644  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:42.644  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:42.645  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.645  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:42.645  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-12 14:11:42.645  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8796e5 removed from the list
,08-12 14:11:42.645  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.645  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d335ba removed from the list
08-12 14:11:42.646  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:42.647  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:42.647  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:42.647  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.647  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:42.648  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:42.649  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:42.649  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.649  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d335ba not in the list
,08-12 14:11:42.649  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.649  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:42.659  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-12 14:11:42.660  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:42.660  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.660  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19fbc61 removed from the list
,08-12 14:11:42.660  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:42.661  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.661  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:42.661  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:42.661  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-12 14:11:42.661  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28303c8 removed from the list
,08-12 14:11:42.663  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-12 14:11:42.664  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef386 added. We now have 2 listener(s)
,08-12 14:11:42.669  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 14:11:42.669  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 14:11:42.670  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 14:11:42.670  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 14:11:42.671  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d14b447 added. We now have 9 listener(s)
,08-12 14:11:42.671  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 14:11:42.672  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 14:11:42.674  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 14:11:42.679  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:42.679  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:42.679  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:42.679  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:42.679  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:42.679  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:42.679  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:42.679  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:42.680  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:42.681  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 14:11:42.681  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 14:11:42.681  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8babd9d added. We now have 3 listener(s)
,08-12 14:11:42.683  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 14:11:42.683  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:42.683  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 14:11:42.683  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 14:11:42.684  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 14:11:42.684  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b6c212 added. We now have 10 listener(s)
08-12 14:11:42.684  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:42.684  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 14:11:42.684  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-12 14:11:42.684  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-12 14:11:42.684  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:42.684  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 14:11:42.686  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:42.688  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 14:11:42.688  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-12 14:11:42.692  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 14:11:42.692  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 14:11:42.692  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 14:11:42.696  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 14:11:42.696  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 14:11:42.696  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 14:11:42.696  3825  3875 D BluetoothAdapter: STATE_ON
,08-12 14:11:42.700  4180  4191 D BtGatt.GattService: registerClient() - UUID=1987a92b-1db5-4f9d-8255-df73efd4a07b
,08-12 14:11:42.701  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=1987a92b-1db5-4f9d-8255-df73efd4a07b, clientIf=5
,08-12 14:11:42.701  3825  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 14:11:42.702  4180  4190 D BtGatt.GattService: start scan with filters
,08-12 14:11:42.706  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 14:11:42.706  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-12 14:11:42.706  4180  4199 D BtGatt.ScanManager: handling starting scan
08-12 14:11:42.706  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-12 14:11:42.706  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 14:11:42.708  4180  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8a9e6d
08-12 14:11:42.709  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 14:11:42.709  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 14:11:42.710  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 14:11:42.711  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 14:11:42.714  3825  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-12 14:11:42.714  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:42.714  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-12 14:11:42.714  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:42.715  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 14:11:42.715  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-12 14:11:42.715  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 14:11:42.715  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-12 14:11:42.715  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-12 14:11:42.715  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-12 14:11:42.715  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 14:11:42.715  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 14:11:42.715  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.716  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-12 14:11:42.717  3825  3875 D BluetoothAdapter: STATE_ON
,08-12 14:11:42.717  4180  4190 D BtGatt.GattService: stopScan() - queue size =1
,08-12 14:11:42.718  4180  4208 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 14:11:42.718  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 14:11:42.718  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 14:11:42.718  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-12 14:11:42.719  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 14:11:42.719  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-12 14:11:42.720  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 14:11:42.720  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 14:11:42.720  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 14:11:42.720  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 14:11:42.721  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:42.722  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 14:11:42.722  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 14:11:42.722  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 14:11:42.726  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 14:11:42.727  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 14:11:42.727  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 14:11:42.727  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.727  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:42.727  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:42.728  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.728  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
,08-12 14:11:42.728  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:42.728  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 14:11:42.728  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-12 14:11:42.728  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef386 removed from the list
,08-12 14:11:42.729  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.729  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d14b447 removed from the list
,08-12 14:11:42.729  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-12 14:11:42.729  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:42.731  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.731  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:42.733  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 14:11:42.733  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:42.733  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.734  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d14b447 not in the list
08-12 14:11:42.734  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.734  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:42.736  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-12 14:11:42.736  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:42.736  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.736  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b6c212 removed from the list
08-12 14:11:42.736  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:42.737  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.737  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:42.737  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-12 14:11:42.737  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8babd9d removed from the list
08-12 14:11:42.738  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-12 14:11:42.738  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63aed5e added. We now have 2 listener(s)
,08-12 14:11:42.740  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 14:11:42.740  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.742  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 14:11:42.742  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 14:11:42.742  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 14:11:42.742  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 14:11:42.742  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de53f added. We now have 9 listener(s)
08-12 14:11:42.742  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:42.743  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 14:11:42.747  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 14:11:42.747  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.747  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 14:11:42.753  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:42.753  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:42.753  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:42.753  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:42.753  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:42.753  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:42.753  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:42.753  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:42.755  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 14:11:42.755  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.756  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
,08-12 14:11:42.756  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:42.757  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 14:11:42.757  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-12 14:11:42.757  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be50355 added. We now have 3 listener(s)
,08-12 14:11:42.760  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:42.760  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 14:11:42.760  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 14:11:42.760  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 14:11:42.761  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 14:11:42.761  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44816a added. We now have 10 listener(s)
08-12 14:11:42.761  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:42.761  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 14:11:42.762  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-12 14:11:42.762  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.762  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 14:11:42.763  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-12 14:11:42.763  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-12 14:11:42.763  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 14:11:42.763  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:42.763  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-12 14:11:42.763  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:42.768  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 14:11:42.768  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-12 14:11:42.768  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 14:11:42.768  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.772  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 14:11:42.773  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 14:11:42.773  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 14:11:42.776  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 14:11:42.776  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 14:11:42.776  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 14:11:42.777  3825  3875 D BluetoothAdapter: STATE_ON
,08-12 14:11:42.778  4180  4208 D BtGatt.GattService: registerClient() - UUID=ac64361f-7ce4-4789-be94-6522bd258240
,08-12 14:11:42.779  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=ac64361f-7ce4-4789-be94-6522bd258240, clientIf=5
08-12 14:11:42.779  3825  3837 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-12 14:11:42.779  4180  4218 D BtGatt.GattService: start scan with filters
,08-12 14:11:42.781  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 14:11:42.782  4180  4199 D BtGatt.ScanManager: handling starting scan
08-12 14:11:42.782  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 14:11:42.782  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 14:11:42.782  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 14:11:42.784  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 14:11:42.785  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 14:11:42.785  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 14:11:42.786  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 14:11:42.788  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 14:11:42.788  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.788  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-12 14:11:42.789  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 14:11:42.789  3825  3875 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-12 14:11:42.789  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 14:11:42.789  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:42.790  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 14:11:42.790  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:42.790  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.790  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-12 14:11:42.790  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-12 14:11:42.790  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63aed5e removed from the list
,08-12 14:11:42.790  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.790  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de53f removed from the list
08-12 14:11:42.790  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:42.790  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:42.791  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.791  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-12 14:11:42.791  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.791  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:42.792  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:42.792  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:42.792  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.793  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de53f not in the list
,08-12 14:11:42.793  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 14:11:42.793  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 14:11:42.793  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 14:11:42.793  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 14:11:42.793  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 14:11:42.794  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 14:11:42.794  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.794  3825  3875 D BluetoothAdapter: STATE_ON
08-12 14:11:42.794  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
08-12 14:11:42.794  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-12 14:11:42.795  4180  4191 D BtGatt.GattService: stopScan() - queue size =1
08-12 14:11:42.796  4180  4190 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 14:11:42.796  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 14:11:42.796  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 14:11:42.796  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 14:11:42.796  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 14:11:42.796  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-12 14:11:42.797  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 14:11:42.797  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 14:11:42.798  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-12 14:11:42.798  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-12 14:11:42.798  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:42.800  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 14:11:42.800  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 14:11:42.800  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:42.800  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-12 14:11:42.800  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 14:11:42.800  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-12 14:11:42.801  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44816a removed from the list
,08-12 14:11:42.801  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:42.801  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:42.801  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:42.801  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-12 14:11:42.801  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be50355 removed from the list,
,08-12 14:11:42.802  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-12 14:11:42.802  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba14a36 added. We now have 2 listener(s)
,08-12 14:11:42.804  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 14:11:42.804  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 14:11:42.804  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 14:11:42.804  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 14:11:42.804  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40d3d37 added. We now have 9 listener(s)
08-12 14:11:42.804  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 14:11:42.805  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 14:11:42.805  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 14:11:42.805  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.808  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-12 14:11:42.811  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 14:11:42.811  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.812  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:42.812  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:42.812  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:42.812  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:42.812  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:42.812  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:42.812  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:42.812  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:42.817  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 14:11:42.819  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 14:11:42.819  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 14:11:42.819  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eeb480d added. We now have 3 listener(s)
,08-12 14:11:42.821  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:42.821  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 14:11:42.822  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 14:11:42.822  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 14:11:42.822  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 14:11:42.822  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12fd3c2 added. We now have 10 listener(s)
08-12 14:11:42.822  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 14:11:42.822  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 14:11:42.822  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-12 14:11:42.822  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 14:11:42.822  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:42.822  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-12 14:11:42.824  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 14:11:42.824  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:42.824  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.824  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
08-12 14:11:42.826  3825  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 14:11:42.826  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 14:11:42.830  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 14:11:42.831  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 14:11:42.831  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 14:11:42.831  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 14:11:42.832  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.832  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 14:11:42.834  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 14:11:42.834  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 14:11:42.834  3825  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 14:11:42.835  3825  3875 D BluetoothAdapter: STATE_ON
,08-12 14:11:42.838  4180  4191 D BtGatt.GattService: registerClient() - UUID=9a7840ed-174e-463e-8e3c-807eb6b81823
08-12 14:11:42.838  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 14:11:42.838  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.838  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=9a7840ed-174e-463e-8e3c-807eb6b81823, clientIf=5
08-12 14:11:42.839  3825  3836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-12 14:11:42.839  4180  4208 D BtGatt.GattService: start scan with filters
,08-12 14:11:42.841  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 14:11:42.841  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 14:11:42.842  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 14:11:42.842  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 14:11:42.842  4180  4199 D BtGatt.ScanManager: handling starting scan
,08-12 14:11:42.845  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 14:11:42.845  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 14:11:42.845  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 14:11:42.847  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 14:11:42.850  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 14:11:42.850  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.850  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 14:11:42.852  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 14:11:42.852  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 14:11:42.853  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 14:11:42.853  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:42.853  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.853  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-12 14:11:42.853  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-12 14:11:42.853  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba14a36 removed from the list
,08-12 14:11:42.853  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.853  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40d3d37 removed from the list
08-12 14:11:42.854  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
08-12 14:11:42.854  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:42.854  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:42.854  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-12 14:11:42.855  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:42.855  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:42.856  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:42.856  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:42.856  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-12 14:11:42.856  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40d3d37 not in the list
08-12 14:11:42.856  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 14:11:42.856  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 14:11:42.856  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 14:11:42.856  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 14:11:42.856  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-12 14:11:42.856  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.856  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 14:11:42.857  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
08-12 14:11:42.857  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 14:11:42.857  3825  3875 D BluetoothAdapter: STATE_ON
08-12 14:11:42.858  4180  4208 D BtGatt.GattService: stopScan() - queue size =1
,08-12 14:11:42.858  4180  4218 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 14:11:42.859  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 14:11:42.859  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-12 14:11:42.859  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-12 14:11:42.859  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 14:11:42.859  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 14:11:42.860  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 14:11:42.860  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 14:11:42.860  3825  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-12 14:11:42.860  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-12 14:11:42.861  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:42.862  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:42.862  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:42.862  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.862  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 14:11:42.862  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12fd3c2 removed from the list
08-12 14:11:42.862  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:42.862  3825  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 14:11:42.862  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:42.862  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:42.862  3825  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 14:11:42.863  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-12 14:11:42.863  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eeb480d removed from the list
08-12 14:11:42.863  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 14:11:42.864  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72b6a0e added. We now have 2 listener(s)
,08-12 14:11:42.865  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 14:11:42.866  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 14:11:42.866  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 14:11:42.866  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 14:11:42.866  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca09c2f added. We now have 9 listener(s)
08-12 14:11:42.866  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 14:11:42.866  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 14:11:42.870  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 14:11:42.870  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 14:11:42.870  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.875  3825  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 14:11:42.875  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 14:11:42.875  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 14:11:42.875  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 14:11:42.875  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 14:11:42.875  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:42.875  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 14:11:42.875  3825  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 14:11:42.877  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 14:11:42.877  3825  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 14:11:42.877  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 14:11:42.879  3825  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 14:11:42.880  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 14:11:42.881  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e6bc5 added. We now have 3 listener(s)
08-12 14:11:42.883  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 14:11:42.884  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 14:11:42.884  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 14:11:42.884  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 14:11:42.884  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 14:11:42.885  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 14:11:42.885  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.885  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
,08-12 14:11:42.885  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a38191a added. We now have 10 listener(s)
08-12 14:11:42.885  3825  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 14:11:42.885  3825  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 14:11:42.886  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 14:11:42.886  3825  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 14:11:42.886  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-12 14:11:42.886  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:42.886  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-12 14:11:42.886  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-12 14:11:42.886  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72b6a0e removed from the list
,08-12 14:11:42.886  3825  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 14:11:42.886  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.886  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca09c2f removed from the list
08-12 14:11:42.886  3825  3875 D io.jxcore.node.ConnectivityMonitor: stop
,08-12 14:11:42.886  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:42.887  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-12 14:11:42.887  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:42.888  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 14:11:42.888  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-12 14:11:42.888  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-12 14:11:42.888  3825  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca09c2f not in the list
08-12 14:11:42.888  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.889  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 14:11:42.890  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 14:11:42.890  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-12 14:11:42.890  3825  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-12 14:11:42.890  3825  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a38191a removed from the list
08-12 14:11:42.890  3825  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-12 14:11:42.890  3825  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 14:11:42.890  3825  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-12 14:11:42.891  3825  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-12 14:11:42.891  3825  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e6bc5 removed from the list
08-12 14:11:42.892  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-12 14:11:42.892  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.892  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-12 14:11:42.893  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-12 14:11:42.893  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-12 14:11:42.893  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-12 14:11:42.893  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 14:11:42.893  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 14:11:42.893  3825  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-12 14:11:42.899  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 14:11:42.899  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 14:11:42.903  3825  4265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: My test thread name)
08-12 14:11:42.903  3825  4265 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 445, thread name: My test thread name)
08-12 14:11:42.903  3825  4265 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 445, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-12 14:11:42.906  3825  4266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: My test thread name)
,08-12 14:11:42.906  3825  4266 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: My test thread name)
08-12 14:11:42.906  3825  4266 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-12 14:11:42.909  3825  3875 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-12 14:11:42.909  3825  3875 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-12 14:11:42.909  3825  3875 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-12 14:11:42.909  3825  3875 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-12 14:11:42.909  3825  3875 D com.test.thalitest.ThaliTestRunner: Total duration: 22849 ms
,08-12 14:11:42.912  3825  3875 I jxcore-log: Total number of executed tests:  80
08-12 14:11:42.912  3825  3875 I jxcore-log: 
,08-12 14:11:42.912  3825  3875 I jxcore-log: Number of passed tests:  80
08-12 14:11:42.912  3825  3875 I jxcore-log: 
,08-12 14:11:42.913  3825  3875 I jxcore-log: Number of failed tests:  0
08-12 14:11:42.913  3825  3875 I jxcore-log: 
08-12 14:11:42.913  3825  3875 I jxcore-log: Number of ignored tests:  0
08-12 14:11:42.913  3825  3875 I jxcore-log: 
08-12 14:11:42.914  3825  3875 I jxcore-log: Total duration:  22849
08-12 14:11:42.914  3825  3875 I jxcore-log: 
,08-12 14:11:42.915  3825  3875 I jxcore-log: Is Android:  true
08-12 14:11:42.915  3825  3875 I jxcore-log: 
08-12 14:11:42.915  3825  3875 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 14:11:42.915  3825  3875 I jxcore-log: 
,08-12 14:11:42.919  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.919  3825  3875 I jxcore-log: 
08-12 14:11:42.922  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.922  3825  3875 I jxcore-log: 
08-12 14:11:42.923  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.923  3825  3875 I jxcore-log: 
08-12 14:11:42.924  3825  3825 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 14:11:42.925  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.925  3825  3875 I jxcore-log: 
08-12 14:11:42.927  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.927  3825  3875 I jxcore-log: 
08-12 14:11:42.929  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.929  3825  3875 I jxcore-log: 
08-12 14:11:42.931  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.931  3825  3875 I jxcore-log: 
,08-12 14:11:42.933  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-12 14:11:42.933  3825  3875 I jxcore-log: 
,08-12 14:11:42.935  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-12 14:11:42.935  3825  3875 I jxcore-log: 
,08-12 14:11:42.936  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.936  3825  3875 I jxcore-log: 
,08-12 14:11:42.937  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.937  3825  3875 I jxcore-log: 
,08-12 14:11:42.939  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 14:11:42.939  3825  3875 I jxcore-log: 
,08-12 14:11:42.940  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-12 14:11:42.940  3825  3875 I jxcore-log: 
,08-12 14:11:42.941  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-12 14:11:42.941  3825  3875 I jxcore-log: 
,08-12 14:11:42.942  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.942  3825  3875 I jxcore-log: 
,08-12 14:11:42.943  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.943  3825  3875 I jxcore-log: 
,08-12 14:11:42.944  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.944  3825  3875 I jxcore-log: 
08-12 14:11:42.945  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.945  3825  3875 I jxcore-log: 
,08-12 14:11:42.946  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.946  3825  3875 I jxcore-log: 
,08-12 14:11:42.948  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.948  3825  3875 I jxcore-log: 
,08-12 14:11:42.949  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.949  3825  3875 I jxcore-log: 
,08-12 14:11:42.949  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.949  3825  3875 I jxcore-log: 
,08-12 14:11:42.950  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.950  3825  3875 I jxcore-log: 
,08-12 14:11:42.951  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-12 14:11:42.951  3825  3875 I jxcore-log: 
,08-12 14:11:42.951  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-12 14:11:42.951  3825  3875 I jxcore-log: 
08-12 14:11:42.952  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.952  3825  3875 I jxcore-log: 
08-12 14:11:42.953  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.953  3825  3875 I jxcore-log: 
,08-12 14:11:42.953  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.953  3825  3875 I jxcore-log: 
08-12 14:11:42.954  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.954  3825  3875 I jxcore-log: 
08-12 14:11:42.954  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.954  3825  3875 I jxcore-log: 
,08-12 14:11:42.955  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.955  3825  3875 I jxcore-log: 
08-12 14:11:42.955  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 14:11:42.955  3825  3875 I jxcore-log: 
,08-12 14:11:43.222  3825  3825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 14:11:43.226  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 14:11:43.226  3825  3875 I jxcore-log: 
,08-12 14:11:43.301  3825  3825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 14:11:43.305  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 14:11:43.305  3825  3875 I jxcore-log: 
,08-12 14:11:43.363  3825  3825 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 14:11:43.367  3825  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 14:11:43.367  3825  3875 I jxcore-log: 
,08-12 14:11:43.583  4267  4267 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 14:11:43.588  4267  4267 D AndroidRuntime: CheckJNI is OFF
,08-12 14:11:43.631  4267  4267 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 14:11:43.679  4267  4267 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 14:11:43.701  4267  4267 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 14:11:43.712   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-12 14:11:43.713   871   884 I ActivityManager: Killing 3825:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 14:11:43.798   871   894 W PackageSettings: Skipping PackageSetting{7a028e6 com.example.hello/10273} due to missing metadata
,08-12 14:11:43.824   871  2003 D GraphicsStats: Buffer count: 2
,08-12 14:11:43.827   871  1309 D WifiService: Client connection lost with reason: 4
,08-12 14:11:43.828   871  1704 I WindowState: WIN DEATH: Window{c62dcbb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 14:11:43.832   871   894 I art     : Starting a blocking GC Explicit
,08-12 14:11:43.860   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-12 14:11:43.860   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 14:11:43.861   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-12 14:11:43.861   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-12 14:11:43.861   871   884 E ActivityManager: 	,at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-12 14:11:43.861   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:43.861   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:43.861   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 14:11:43.861   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 14:11:43.862   871   884 I ActivityManager:   Force finishing activity ActivityRecord{4b11060 u0 com.test.thalitest/.MainActivity t2}
,08-12 14:11:43.875   871  1390 W ActivityManager: Spurious death for ProcessRecord{9332a91 0:com.test.thalitest/u0a0}, curProc for 3825: null
,08-12 14:11:43.896   871   894 I art     : Explicit concurrent mark sweep GC freed 36719(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 696us total 64.190ms
,08-12 14:11:43.924   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 14:11:43.926  4267  4267 I art     : System.exit called, status: 0
,08-12 14:11:43.926  4267  4267 I AndroidRuntime: VM exiting with result code 0.
,08-12 14:11:43.930   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 14:11:43.955   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 14:11:43.959  4180  4180 D BluetoothMapAppObserver: onReceive
08-12 14:11:43.959  4180  4180 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-12 14:11:43.964   871  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 14:11:43.964  3693  3693 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-12 14:11:43.964  1853  1853 I Keyboard.Facilitator: resetDictionaries() : en_US
08-12 14:11:43.964  2070  2241 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 14:11:43.966  1853  4279 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 14:11:43.970  1853  4279 I Decoder : createOrResetDecoder
,08-12 14:11:43.990  1911  1911 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 14:11:44.001   871  1703 I ActivityManager: Start proc 4282:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-12 14:11:44.024  1507  1507 I ConfigService: onCreate
,08-12 14:11:44.050  1853  4279 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-12 14:11:44.055  4282  4282 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-12 14:11:44.055   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 14:11:44.069   871  3957 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3825 uid 10000
,08-12 14:11:44.077  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-12 14:11:44.086   871  1334 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-12 14:11:44.086   871  1334 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-12 14:11:44.086   871  1334 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-12 14:11:44.086   871  1334 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
,08-12 14:11:44.087   871  1334 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-12 14:11:44.087   871  1334 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-12 14:11:44.087   871  1334 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-12 14:11:44.087   871  1334 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-12 14:11:44.087   871  1334 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-12 14:11:44.087   871  1334 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
,08-12 14:11:44.087   871  1334 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-12 14:11:44.087   871  1334 W System.err: 	... 4 more
08-12 14:11:44.087   871  1334 D skia    : ------- write threw an exception
,08-12 14:11:44.112  1923  2004 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-12 14:11:44.112   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-12 14:11:44.113   871   883 E PackageManager: Failed to write settings, restoring backup
08-12 14:11:44.113   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
,08-12 14:11:44.113   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 14:11:44.113   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 14:11:44.113   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 14:11:44.113   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 14:11:44.113   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:11:44.113   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:44.113   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61),
,08-12 14:11:44.113  1853  4279 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-12 14:11:44.116  1853  4279 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-12 14:11:44.116  1853  4279 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-12 14:11:44.117   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-12 14:11:44.117   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 14:11:44.117   871   8,84 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 14:11:44.117   871   884 E DropBoxManagerService: 	... 13 more
08-12 14:11:44.118  1853  4279 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-12 14:11:44.118  1853  4279 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-12 14:11:44.118  1853  4279 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-12 14:11:44.118  1853  4279 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-12 14:11:44.119  1853  4279 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-12 14:11:44.119  1853  4279 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-12 14:11:44.119  1853  4279 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-12 14:11:44.119  1853  4279 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-12 14:11:44.119  1853  4279 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-12 14:11:44.119  1853  4279 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-12 14:11:44.125   871  1390 I ActivityManager: Start proc 4298:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-12 14:11:44.125  1923  2004 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 14:11:44.125  1923  2004 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1923
08-12 14:11:44.125  1923  2004 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64),
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:11:44.125  1923  2004 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 14:11:44.128   871   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-12 14:11:44.128   871  4309 E DropBoxManagerService: Can't write: system_app_crash
08-12 14:11:44.128   871  4309 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 14:11:44.128   871  4309 E DropBoxManagerService: 	... 5 more
08-12 14:11:44.131  1923  2004 I Process : Sending signal. PID: 1923 SIG: 9
,08-12 14:11:44.142  4282  4282 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-12 14:11:44.161   871  1999 I ActivityManager: Start proc 4313:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-12 14:11:44.383   871  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 16 -> obsolete
,08-12 14:11:44.440  4282  4312 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest

```
