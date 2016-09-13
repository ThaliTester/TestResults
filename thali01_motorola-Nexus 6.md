#### Test 84618637dc3f7e6_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-13 08:49:14.514   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-13 08:49:15.207  3929  3929 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 08:49:15.211  3929  3929 D AndroidRuntime: CheckJNI is OFF
09-13 08:49:15.254  3929  3929 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 08:49:15.303  3929  3929 I Radio-JNI: register_android_hardware_Radio DONE
09-13 08:49:15.325  3929  3929 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 08:49:15.329   872  1378 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 08:49:15.362  2043  2054 W SearchService: Abort, client detached.
09-13 08:49:15.367  3929  3929 D AndroidRuntime: Shutting down VM
09-13 08:49:15.370  2043  2043 I HotwordDetector: Closing mic
09-13 08:49:15.370  2043  2337 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7301c21
09-13 08:49:15.370  2043  2355 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 08:49:15.385   872  1976 I ActivityManager: Start proc 3939:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 08:49:15.430   376  2357 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 08:49:15.431   376  2357 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 08:49:15.438   376  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 08:49:15.441  2043  2345 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 08:49:15.441  2043  2354 I MicroRecognitionRnrImpl: Detection finished
09-13 08:49:15.460  3939  3939 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 08:49:15.480  3939  3939 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 08:49:15.487  3939  3939 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8909-8911)
09-13 08:49:15.487  3939  3939 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 08:49:15.499  3939  3939 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6b012b8}
09-13 08:49:15.500  3939  3939 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 08:49:15.500  3939  3939 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 08:49:15.507  3939  3939 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 08:49:15.508  3939  3939 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 08:49:15.520  3939  3939 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 08:49:15.530  3939  3939 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 08:49:15.530  3939  3939 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 08:49:15.530  3939  3939 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 08:49:15.530  3939  3939 I Adreno  : Build Date                       : 10/20/15
09-13 08:49:15.530  3939  3939 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 08:49:15.530  3939  3939 I Adreno  : Local Branch                     : M14
09-13 08:49:15.530  3939  3939 I Adreno  : Remote Branch                    : 
09-13 08:49:15.530  3939  3939 I Adreno  : Remote Branch                    : 
09-13 08:49:15.530  3939  3939 I Adreno  : Reconstruct Branch               : 
09-13 08:49:15.582   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eb513b8:true
,09-13 08:49:15.615  3939  3939 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 08:49:15.626  3939  3939 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 08:49:15.670  3939  3978 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 08:49:15.677  3939  3965 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 08:49:15.696  3939  3978 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 08:49:15.714  1868  1868 I Keyboard.Facilitator: onFinishInput()
,09-13 08:49:15.746   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +376ms
,09-13 08:49:15.823  3939  3939 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3939
,09-13 08:49:15.932  3939  3939 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 08:49:16.123  3939  3980 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1694500560
,09-13 08:49:16.130  3939  3980 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 08:49:16.130  3939  3980 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 08:49:16.130  3939  3980 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 08:49:16.130  3939  3980 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 08:49:16.130  3939  3980 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 08:49:16.130  3939  3980 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a97aeaf added. We now have 1 listener(s)
,09-13 08:49:16.134  3939  3980 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-13 08:49:16.135  3939  3980 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 08:49:16.136  3939  3980 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 08:49:16.136  3939  3980 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 08:49:16.140  3939  3980 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43a86cb added. We now have 1 listener(s)
,09-13 08:49:16.140  3939  3980 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:49:16.143   872  1304 D WifiService: New client listening to asynchronous messages
,09-13 08:49:16.145  3939  3980 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 08:49:16.145  3939  3980 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 08:49:16.145  3939  3980 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-13 08:49:16.145  3939  3980 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 08:49:16.145  3939  3980 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 08:49:16.148  3939  3980 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 08:49:16.149  3939  3980 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 08:49:16.158  3939  3980 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 08:49:16.159  3939  3980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:49:16.159  3939  3980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:49:16.159  3939  3980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:49:16.159  3939  3980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:49:16.159  3939  3980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:49:16.159  3939  3980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:49:16.159  3939  3980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:49:16.159  3939  3980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:49:16.159  3939  3980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-13 08:49:16.159  3939  3980 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 08:49:16.161  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:49:16.163  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:49:16.165  3939  3980 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 08:49:16.197   872  2012 I ActivityManager: Killing 3164:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,09-13 08:49:16.239   872  2012 I ActivityManager: Killing 3121:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-13 08:49:16.404  3939  3939 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 08:49:17.067  3939  3989 W jxcore-log: Initializing JXcore engine
09-13 08:49:17.067  3939  3989 W jxcore-log: JXcore engine is ready
,09-13 08:49:17.104  3989  3989 W Thread-357: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 08:49:17.104  3989  3989 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12027]" dev="sockfs" ino=12027 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 08:49:17.104  3989  3989 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-13 08:49:17.107  3989  3989 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27113]" dev="sockfs" ino=27113 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 08:49:17.118  3939  3989 W jxcore-log: Starting JXcore engine
,09-13 08:49:17.235  3939  3989 W jxcore-log: Platform android
09-13 08:49:17.235  3939  3989 W jxcore-log: 
,09-13 08:49:17.235  3939  3989 W jxcore-log: Process ARCH arm
09-13 08:49:17.235  3939  3989 W jxcore-log: 
,09-13 08:49:17.453  3939  3989 I jxcore-log: JXcore Cordova bridge is ready!
09-13 08:49:17.453  3939  3989 I jxcore-log: 
,09-13 08:49:17.454  3939  3989 W jxcore-log: JXcore engine is started
,09-13 08:49:17.460  3939  3980 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 08:49:17.466  3939  3939 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 08:49:17.540   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 08:49:20.846   872  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 08:49:21.785   872  2240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=125210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 08:49:23.593   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 08:49:25.600  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:49:25.607  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:49:25.610  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:49:25.632  1500  2066 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 08:49:25.632  1500  2066 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 08:49:25.632  1500  2066 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:49:25.632  1500  2066 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:49:25.659  3663  3663 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 08:49:25.666  3663  3663 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 08:49:25.666  3663  3663 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 08:49:26.632   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 08:49:26.724  3301  4002 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 08:49:26.741  3301  4003 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 08:49:26.778  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 08:49:26.779  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 08:49:26.779  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:49:26.779  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:49:26.858  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 08:49:26.858  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 08:49:26.859  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:49:26.859  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:49:26.892  3301  4003 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 08:49:26.893  3301  4002 E BooksSync: Soft error
09-13 08:49:26.893  3301  4002 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:49:26.893  3301  4002 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 08:49:26.894  3301  4002 E BooksSync: Sync error
09-13 08:49:26.894  3301  4002 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:49:26.894  3301  4002 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 08:49:26.894  3301  4002 I BooksSync: Finished books sync
,09-13 08:49:26.904   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 130037, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:49:31.741  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 08:49:31.741  3939  3989 I jxcore-log: 
,09-13 08:49:31.744  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 08:49:31.744  3939  3989 I jxcore-log: 
,09-13 08:49:31.752  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:49:31.752  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:49:31.752  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:49:31.752  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:49:31.752  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:49:31.752  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:49:31.752  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:49:31.752  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:49:31.758  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:49:31.760  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 08:49:31.760  3939  3989 I jxcore-log: 
,09-13 08:49:31.762  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 08:49:31.762  3939  3989 I jxcore-log: 
,09-13 08:49:32.112  3939  3989 I jxcore-log: Running unit tests
09-13 08:49:32.112  3939  3989 I jxcore-log: 
09-13 08:49:32.113  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 08:49:32.113  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b0ab3c added. We now have 2 listener(s)
,09-13 08:49:32.114  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 08:49:32.114  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 08:49:32.114  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 08:49:32.114  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 08:49:32.114  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cd60c5 added. We now have 2 listener(s)
09-13 08:49:32.114  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 08:49:32.115  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 08:49:32.117  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:49:32.130  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:49:32.130  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:49:32.130  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:49:32.130  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:49:32.130  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:49:32.130  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:49:32.130  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:49:32.130  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:49:32.138  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:49:32.139  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 08:49:32.139  3939  3989 D executeNativeTests: Running unit tests
,09-13 08:49:32.156  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:49:32.165  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:49:32.212  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 08:49:32.212  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b added. We now have 3 listener(s)
,09-13 08:49:32.213  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 08:49:32.213  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 08:49:32.213  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 08:49:32.214  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 08:49:32.214  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 added. We now have 3 listener(s)
,09-13 08:49:32.214  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:49:32.214  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,09-13 08:49:32.218  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:49:32.237  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:49:32.237  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:49:32.237  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:49:32.237  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:49:32.237  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:49:32.237  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:49:32.237  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:49:32.237  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:49:32.242  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:49:32.242  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 08:49:32.245  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 08:49:32.247  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 08:49:32.247  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:49:32.247  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 08:49:32.248  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 08:49:32.249  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:49:32.252  3939  3989 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 08:49:32.253  3939  3989 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 08:49:32.254  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 08:49:32.254  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 08:49:32.254  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 08:49:32.255  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 08:49:32.256  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:32.257  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:32.257  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 08:49:32.258  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 08:49:32.259  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:32.259  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 08:49:32.259  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 08:49:32.260  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b removed from the list
,09-13 08:49:32.260  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:32.260  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 removed from the list
09-13 08:49:32.260  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:32.260  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:32.262  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:32.263  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:32.267  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:49:32.267  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:32.267  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:32.268  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:32.272  3939  3989 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 08:49:32.273  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:32.273  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:49:32.273  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 08:49:32.273  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:32.273  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:32.273  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:32.273  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:32.273  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:32.273  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:32.274  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:49:32.274  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:32.274  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:32.274  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:32.274  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:32.275  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:49:32.275  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 08:49:32.275  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:32.278  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 08:49:32.283  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 08:49:32.284  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 08:49:32.285  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 08:49:32.285  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:32.285  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:49:32.285  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:32.285  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:32.285  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:32.285  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:32.285  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list,
09-13 08:49:32.285  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:32.285  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:32.285  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:49:32.285  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:32.285  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:32.285  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:32.285  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:32.287  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:49:32.287  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 08:49:32.287  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:32.287  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:32.288  3939  3989 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 08:49:32.289  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:49:32.298  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:49:32.298  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:49:32.298  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:49:32.298  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:49:32.298  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:49:32.298  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:49:32.298  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:49:32.298  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:49:32.301  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:49:32.301  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 08:49:32.301  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 08:49:32.301  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 08:49:32.302  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 08:49:32.302  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 08:49:32.302  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 08:49:32.304  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:49:32.305  3939  3989 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 08:49:32.305  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 08:49:32.306  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:49:32.310  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 08:49:32.312  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 08:49:32.312  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 08:49:32.314  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 08:49:32.317  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-13 08:49:32.317  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 08:49:32.317  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 08:49:32.318  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 08:49:32.319  3939  3989 D BluetoothAdapter: STATE_ON
09-13 08:49:32.324  2658  2748 D BtGatt.GattService: registerClient() - UUID=3c1dad17-7ed1-4dd7-bea7-dc71bf352f04
09-13 08:49:32.325  2658  2678 D BtGatt.GattService: onClientRegistered() - UUID=3c1dad17-7ed1-4dd7-bea7-dc71bf352f04, clientIf=5
09-13 08:49:32.325  3939  3950 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 08:49:32.326  2658  2670 D BtGatt.GattService: start scan with filters
,09-13 08:49:32.329  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 08:49:32.329  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 08:49:32.329  2658  2681 D BtGatt.ScanManager: handling starting scan
,09-13 08:49:32.329  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 08:49:32.330  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 08:49:32.331  2658  2681 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
09-13 08:49:32.333  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 08:49:32.333  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 08:49:32.334  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 08:49:32.335  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 08:49:32.338  2658  2678 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 08:49:32.339  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:49:32.339  3939  3989 I io.jxcore.node.ConnectionHelper: start: OK
09-13 08:49:32.339  2658  2681 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 08:49:32.348  2658  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 08:49:32.348  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:49:32.349  2658  2681 D BtGatt.ScanManager: Starting BLE batch scan
09-13 08:49:32.349  2658  2681 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 08:49:32.361  2658  2678 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 08:49:32.361  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:32.369  2658  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 08:49:32.370  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:32.836  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-13 08:49:32.837  3939  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 08:49:32.837  3939  3939 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 08:49:33.877  2658  2658 D BtGatt.ScanManager: awakened up at time 137302
,09-13 08:49:33.881  2658  2681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:49:33.932  2658  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-13 08:49:33.932  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:33.933  2658  2678 D BtGatt.GattService: current time is 137358287911
,09-13 08:49:33.936  2658  2678 D BtGatt.GattService: Batch record : [94, -15, 90, -35, -8, -1, 1, -128, -105, 26, 0, 31, 2, 1, 6, 27, -1, 87, 1, 0, -74, -34, 70, 14, -63, -81, -114, -9, -112, 75, 117, -105, 85, -31, 30, 9, 2, -1, -8, -35, 90, -15, 94, 17, 10, 9, 77, 73, 32, 66, 97, 110, 100, 32, 50, 5, 2, -32, -2, -25, -2, 116, -43, -111, -91, -20, -29, 1, -128, -100, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -92, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -105, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 08:49:33.943  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 27, -1, 87, 1, 0, -74, -34, 70, 14, -63, -81, -114, -9, -112, 75, 117, -105, 85, -31, 30, 9, 2, -1, -8, -35, 90, -15, 94, 10, 9, 77, 73, 32, 66, 97, 110, 100, 32, 50, 5, 2, -32, -2, -25, -2]
,09-13 08:49:33.946  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 08:49:33.947  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 08:49:33.950  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 08:49:33.951  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 08:49:33.953  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 08:49:35.434  2658  2658 D BtGatt.ScanManager: awakened up at time 138859
,09-13 08:49:35.438  2658  2681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:49:35.447  2658  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 08:49:35.447  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:36.949  2658  2658 D BtGatt.ScanManager: awakened up at time 140374
,09-13 08:49:36.952  2658  2681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:49:36.999  2658  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
09-13 08:49:36.999  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:36.999  2658  2678 D BtGatt.GattService: current time is 140424616811
,09-13 08:49:37.000  2658  2678 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -87, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -93, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -88, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 08:49:37.001  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 08:49:37.001  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 08:49:37.002  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-13 08:49:37.003  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 08:49:37.349  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 08:49:37.350  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:49:37.350  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 08:49:37.351  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:37.351  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 08:49:37.351  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 08:49:37.352  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 08:49:37.352  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 08:49:37.353  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 08:49:37.355  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 08:49:37.355  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 08:49:37.359  3939  3989 D BluetoothAdapter: STATE_ON
09-13 08:49:37.360  2658  2670 D BtGatt.GattService: stopScan() - queue size =1
09-13 08:49:37.364  2658  2671 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 08:49:37.365  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 08:49:37.366  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 08:49:37.366  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 08:49:37.366  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 08:49:37.367  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 08:49:37.370  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 08:49:37.372  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 08:49:37.373  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 08:49:37.373  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 08:49:37.375  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 08:49:37.378  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 08:49:37.378  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 08:49:37.379  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:49:37.379  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 08:49:37.379  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:37.380  2658  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 08:49:37.380  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:49:37.380  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 08:49:37.382  2658  2681 D BtGatt.ScanManager: stopping BLe Batch
,09-13 08:49:37.381  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:37.383  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:37.383  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:37.383  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:37.383  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:37.392  2658  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 08:49:37.392  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:49:37.392  2658  2681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:49:37.419  2658  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
09-13 08:49:37.419  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:49:37.419  2658  2678 D BtGatt.GattService: current time is 140844165654
09-13 08:49:37.419  2658  2678 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -87, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 08:49:37.419  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 08:49:37.420  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 08:49:37.880  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 08:49:42.385  3939  3989 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 08:49:42.391  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:49:42.407  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:49:42.407  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:49:42.407  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:49:42.407  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:49:42.407  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:49:42.407  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:49:42.407  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:49:42.407  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:49:42.410  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:49:42.410  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 08:49:42.410  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 08:49:42.411  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
,09-13 08:49:42.411  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 08:49:42.411  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:49:42.411  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 08:49:42.416  3939  3989 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
09-13 08:49:42.416  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 08:49:42.418  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:49:42.423  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 08:49:42.424  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:49:42.425  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 08:49:42.425  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 08:49:42.435  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 08:49:42.435  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 08:49:42.436  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 08:49:42.437  3939  3989 D BluetoothAdapter: STATE_ON
,09-13 08:49:42.443  2658  2670 D BtGatt.GattService: registerClient() - UUID=052c0ace-ab3e-4ca5-99eb-95d1e54ed5a9
09-13 08:49:42.443  2658  2678 D BtGatt.GattService: onClientRegistered() - UUID=052c0ace-ab3e-4ca5-99eb-95d1e54ed5a9, clientIf=5
,09-13 08:49:42.444  3939  3950 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 08:49:42.445  2658  2748 D BtGatt.GattService: start scan with filters
,09-13 08:49:42.452  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 08:49:42.452  2658  2681 D BtGatt.ScanManager: handling starting scan
09-13 08:49:42.452  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 08:49:42.452  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 08:49:42.453  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 08:49:42.456  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 08:49:42.457  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 08:49:42.457  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 08:49:42.458  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 08:49:42.462  3939  3989 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 08:49:42.467  2658  2678 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 08:49:42.467  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.467  2658  2681 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 08:49:42.468  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:42.469  3939  3989 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 08:49:42.469  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:42.469  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 08:49:42.469  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:42.470  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 08:49:42.470  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 08:49:42.470  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 08:49:42.470  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 08:49:42.470  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 08:49:42.471  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 08:49:42.471  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 08:49:42.472  3939  3989 D BluetoothAdapter: STATE_ON
09-13 08:49:42.472  2658  2670 D BtGatt.GattService: stopScan() - queue size =1
,09-13 08:49:42.476  2658  2748 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 08:49:42.476  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 08:49:42.476  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 08:49:42.476  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 08:49:42.476  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-13 08:49:42.476  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 08:49:42.478  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:49:42.478  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 08:49:42.478  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 08:49:42.478  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 08:49:42.479  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 08:49:42.482  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 08:49:42.482  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:42.482  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:49:42.482  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 08:49:42.482  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:42.482  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:49:42.483  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:49:42.482  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:42.483  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:42.483  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:42.483  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:42.484  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:42.484  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:42.485  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:49:42.486  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:42.486  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:42.486  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:42.486  3939  3989 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 08:49:42.487  2658  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 08:49:42.488  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.488  2658  2681 D BtGatt.ScanManager: Starting BLE batch scan
09-13 08:49:42.488  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 08:49:42.488  2658  2681 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 08:49:42.496  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:49:42.496  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:49:42.496  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:49:42.496  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:49:42.496  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:49:42.496  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:49:42.496  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:49:42.496  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:49:42.498  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:49:42.499  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 08:49:42.499  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 08:49:42.499  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 08:49:42.499  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 08:49:42.499  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 08:49:42.499  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 08:49:42.503  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:49:42.507  3939  3989 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 08:49:42.507  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 08:49:42.507  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:49:42.510  2658  2678 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 08:49:42.510  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.516  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 08:49:42.517  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 08:49:42.517  2658  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 08:49:42.517  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 08:49:42.517  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.523  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 08:49:42.523  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 08:49:42.523  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 08:49:42.524  3939  3989 D BluetoothAdapter: STATE_ON
,09-13 08:49:42.527  2658  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 08:49:42.527  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.528  2658  2681 D BtGatt.ScanManager: stopping BLe Batch
,09-13 08:49:42.529  2658  2768 D BtGatt.GattService: registerClient() - UUID=3c91e24d-6610-474c-8b71-1d67de27ebc1
,09-13 08:49:42.531  2658  2678 D BtGatt.GattService: onClientRegistered() - UUID=3c91e24d-6610-474c-8b71-1d67de27ebc1, clientIf=5
,09-13 08:49:42.531  3939  3950 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 08:49:42.532  2658  2670 D BtGatt.GattService: start scan with filters
,09-13 08:49:42.535  2658  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 08:49:42.535  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.535  2658  2681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:49:42.538  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 08:49:42.538  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 08:49:42.538  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 08:49:42.538  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 08:49:42.543  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 08:49:42.545  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 08:49:42.545  2658  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 08:49:42.545  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.545  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 08:49:42.548  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 08:49:42.549  2658  2681 D BtGatt.ScanManager: handling starting scan
,09-13 08:49:42.553  3939  3989 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 08:49:42.558  2658  2678 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 08:49:42.558  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.559  2658  2681 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 08:49:42.567  2658  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 08:49:42.568  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.568  2658  2681 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 08:49:42.568  2658  2681 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 08:49:42.580  2658  2678 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 08:49:42.580  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:42.589  2658  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 08:49:42.590  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:43.046  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 08:49:43.047  3939  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 08:49:43.047  3939  3939 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 08:49:44.098  2658  2658 D BtGatt.ScanManager: awakened up at time 147522
,09-13 08:49:44.100  2658  2681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:49:44.147  2658  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-13 08:49:44.147  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:44.147  2658  2678 D BtGatt.GattService: current time is 147572510960
,09-13 08:49:44.148  2658  2678 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -93, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -102, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 08:49:44.148  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 08:49:44.148  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 08:49:44.149  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 08:49:44.149  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 08:49:44.149  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 08:49:44.149  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 08:49:45.652  2658  2658 D BtGatt.ScanManager: awakened up at time 149077
,09-13 08:49:45.656  2658  2681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:49:45.666  2658  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 08:49:45.666  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:46.412   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 08:49:46.426  1868  1868 I Keyboard.Facilitator: onFinishInput()
,09-13 08:49:46.441   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 08:49:46.441   872   892 I Adreno  : Build Date                       : 10/20/15
09-13 08:49:46.441   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 08:49:46.441   872   892 I Adreno  : Local Branch                     : M14
09-13 08:49:46.441   872   892 I Adreno  : Remote Branch                    : 
09-13 08:49:46.441   872   892 I Adreno  : Remote Branch                    : 
09-13 08:49:46.441   872   892 I Adreno  : Reconstruct Branch               : 
,09-13 08:49:46.479   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (201 us)
,09-13 08:49:47.072  3939  3939 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 08:49:47.072  3939  3939 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 08:49:47.115   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 08:49:47.120  3939  3939 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@140bce Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@49ea5a5, 16908290=android.view.AbsSavedState$1@49ea5a5}, android:focusedViewId=100}]}]
,09-13 08:49:47.121  3939  3939 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 08:49:47.123  3939  3939 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 08:49:47.123  3939  3939 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 08:49:47.133   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 08:49:47.137   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-13 08:49:47.137   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-13 08:49:47.137   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 08:49:47.165  2658  2658 D BtGatt.ScanManager: awakened up at time 150590
09-13 08:49:47.165  2658  2681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:49:47.187  2658  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-13 08:49:47.187  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:47.188  2658  2678 D BtGatt.GattService: current time is 150612770430
,09-13 08:49:47.188  2658  2678 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -93, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -81, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -88, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -88, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 08:49:47.188  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 08:49:47.188  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 08:49:47.188  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 08:49:47.188  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 08:49:47.188  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 08:49:47.189  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 08:49:47.364   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 08:49:47.366   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 08:49:47.372   872  1331 D SurfaceControl: Excessive delay in setPowerMode(): 234ms
,09-13 08:49:47.375   872   892 I DreamManagerService: Entering dreamland.
09-13 08:49:47.376   872   892 I PowerManagerService: Dozing...
,09-13 08:49:47.377   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 08:49:47.387  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:49:47.399  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:49:47.402  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:49:47.420   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-13 08:49:47.420   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 08:49:47.426   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 08:49:47.434   872  1303 E native  : do suspend false
,09-13 08:49:47.438  1944  4009 D NfcService: Discovery configuration equal, not updating.
,09-13 08:49:47.440  1500  3132 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 08:49:47.441  1500  3132 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 08:49:47.441  1500  3132 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:49:47.442  1500  3132 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:49:47.446   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 08:49:47.460   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 08:49:47.464   872  1303 E native  : do suspend true
,09-13 08:49:47.466  3663  3663 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 08:49:47.467  3663  3663 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 08:49:47.468  3663  3663 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 08:49:47.554  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 08:49:47.554  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:49:47.555  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 08:49:47.555  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:47.555  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 08:49:47.556  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 08:49:47.556  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 08:49:47.556  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 08:49:47.556  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 08:49:47.557  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 08:49:47.558  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 08:49:47.560  3939  3989 D BluetoothAdapter: STATE_ON
,09-13 08:49:47.561   376  2061 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-13 08:49:47.562   376  2061 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
09-13 08:49:47.562  2658  2670 D BtGatt.GattService: stopScan() - queue size =1
09-13 08:49:47.564  2658  2768 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 08:49:47.566  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 08:49:47.567  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 08:49:47.567  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 08:49:47.567  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 08:49:47.567  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 08:49:47.573  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:49:47.573  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 08:49:47.573  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 08:49:47.573  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 08:49:47.574  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 08:49:47.576  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:49:47.578  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:49:47.578  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 08:49:47.587  2658  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 08:49:47.587  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:49:47.588  2658  2681 D BtGatt.ScanManager: stopping BLe Batch
,09-13 08:49:47.605  2658  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 08:49:47.605  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:49:47.606  2658  2681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:49:47.622  2658  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-13 08:49:47.622  2658  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:49:47.622  2658  2678 D BtGatt.GattService: current time is 151047107765
,09-13 08:49:47.622  2658  2678 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -91, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 08:49:47.622  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 08:49:47.623  2658  2678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 08:49:47.879   872  2240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=151303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 08:49:47.931   872  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-13 08:49:48.079  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 08:49:48.080  3939  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:48.080  3939  3939 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 08:49:52.577  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 08:49:52.578  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:49:52.578  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 08:49:52.578  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 08:49:52.579  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.579  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 08:49:52.579  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
,09-13 08:49:52.580  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:52.580  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:52.580  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:52.581  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-13 08:49:52.583  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.583  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.587  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-13 08:49:52.587  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 08:49:52.587  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.588  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:52.590  3939  3989 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 08:49:52.592  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-13 08:49:52.592  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:49:52.593  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:52.593  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.593  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.593  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:52.594  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:52.594  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:52.594  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.595  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:49:52.596  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.596  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-13 08:49:52.597  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.597  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.598  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:49:52.598  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:52.598  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:52.598  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:52.599  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 08:49:52.599  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-13 08:49:52.599  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:52.599  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-13 08:49:52.600  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.600  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 08:49:52.600  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.600  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list,
09-13 08:49:52.600  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:52.600  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.600  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:49:52.600  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.600  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:52.600  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.600  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:52.602  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:52.602  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 08:49:52.602  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:52.603  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.603  3939  3989 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-13 08:49:52.603  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:52.604  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-13 08:49:52.604  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 08:49:52.604  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.604  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.604  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:52.604  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:52.604  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:52.604  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:52.604  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 08:49:52.604  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.604  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:52.604  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.605  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:52.606  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:49:52.606  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:52.606  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.607  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:52.607  3939  3989 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 08:49:52.607  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:52.607  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:52.608  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:52.608  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.608  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.608  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.608  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
,09-13 08:49:52.608  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:52.608  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:52.608  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:52.608  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.608  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.608  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.609  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.610  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:49:52.611  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:52.611  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.611  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:52.611  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 08:49:52.612  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 08:49:52.612  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 08:49:52.612  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 08:49:52.612  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 08:49:52.612  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 08:49:52.612  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 08:49:52.612  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 08:49:52.612  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 08:49:52.613  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:52.613  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:52.613  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:52.613  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.613  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:52.613  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.613  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:52.613  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.613  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.613  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:49:52.613  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.614  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.614  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.614  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.615  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:52.616  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:52.616  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.616  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.617  3939  3989 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 08:49:52.617  3939  3989 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 08:49:52.617  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 08:49:52.622  3939  3989 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 08:49:52.622  3939  3989 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 08:49:52.622  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 08:49:52.622  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 08:49:52.623  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: ,[<no peer name> 24:1410:1410:1410:1410:1410]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 08:49:52.624  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 08:49:52.625  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 08:49:52.625  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 08:49:52.625  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 08:49:52.625  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 08:49:52.625  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 08:49:52.625  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 08:49:52.625  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 08:49:52.625  3939  3989 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 08:49:52.626  3939  3989 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 08:49:52.626  3939  3989 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 08:49:52.626  3939  3989 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 08:49:52.626  3939  3989 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 08:49:52.626  3939  3989 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 08:49:52.627  3939  3989 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 08:49:52.627  3939  3989 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 08:49:52.627  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 08:49:52.631  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 08:49:52.632  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 08:49:52.632  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 08:49:52.633  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 08:49:52.633  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 08:49:52.633  3939  3989 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 08:49:52.633  3939  3989 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 08:49:52.634  3939  3989 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 08:49:52.634  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:52.634  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:52.635  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:52.635  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.635  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.635  3939  4014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 421)
09-13 08:49:52.636  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.636  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 08:49:52.636  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:52.636  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.636  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.637  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:52.637  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.637  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.637  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.637  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.638  3939  4015 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 421
09-13 08:49:52.642  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:52.642  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:52.642  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.642  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.643  3939  3989 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 08:49:52.643  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:52.643  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:52.643  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:52.643  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.643  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.643  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.644  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:52.644  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.644  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.644  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:52.644  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.644  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.644  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.644  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.645  3939  4014 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 08:49:52.646  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:52.646  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:52.646  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.646  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.646  3939  3989 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 08:49:52.647  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:52.647  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:52.647  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:52.648  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.648  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.648  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.648  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:52.649  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.650  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.650  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:52.650  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.651  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.651  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.651  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.652  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:52.652  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:52.653  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.653  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.653  3939  3989 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 08:49:52.653  3939  3989 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 08:49:52.653  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 08:49:52.654  3939  3989 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 08:49:52.654  3939  3989 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 08:49:52.654  3939  3989 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 08:49:52.654  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 08:49:52.654  3939  3989 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 08:49:52.654  3939  3989 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 08:49:52.654  3939  3989 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 08:49:52.654  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 08:49:52.654  3939  3989 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 08:49:52.654  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:52.654  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:52.654  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:52.655  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.655  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.655  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.655  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:52.655  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.655  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.655  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:52.655  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.655  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.655  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.655  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.656  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:52.656  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:52.656  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.656  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.657  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:52.657  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.657  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:52.657  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:52.657  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:52.657  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:52.657  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:52.657  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:52.657  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:55.248  2129  2521 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 08:49:57.150  3747  4016 V KeepSync: Connecting to GoogleApiClient
,09-13 08:49:57.151   872  1998 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 08:49:57.252  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:49:57.256  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:49:57.299  1500  2066 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:49:57.299  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 08:49:57.300  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 08:49:57.300  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-13 08:49:57.300  1500  2066 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 08:49:57.300  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 08:49:57.300  1500  2066 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:49:57.300  1500  2066 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:49:57.325  1740  4019 V BaseAuthAsyncOperation: access token request failed
,09-13 08:49:57.327  3747  4016 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 08:49:57.333  3702  4018 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 08:49:57.333  3702  4018 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at blb.a(PG:3937)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at czp.a(PG:18188)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:49:57.333  3702  4018 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	... 12 more
09-13 08:49:57.333  3702  4018 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at fal.a(PG:38)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:49:57.333  3702  4018 E HttpOperation: 	... 14 more
,09-13 08:49:57.397  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:49:57.398  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 08:49:57.398  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:49:57.398  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:49:57.426  3702  4018 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 08:49:57.426  3702  4018 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at hec.a(PG:42)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at hee.a(PG:102)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at czr.a(PG:65)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at kka.a(PG:108)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at czp.a(PG:19176)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:49:57.426  3702  4018 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	... 15 more
09-13 08:49:57.426  3702  4018 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at fal.a(PG:38)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:49:57.426  3702  4018 E HttpOperation: 	... 17 more
,09-13 08:49:57.427  3702  4018 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 08:49:57.427  3702  4018 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at hec.a(PG:42)
,09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at hee.a(PG:102)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at czr.a(PG:65)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at kka.a(PG:108)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	... 15 more
09-13 08:49:57.427  3702  4018 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at fal.a(PG:38)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 08:49:57.427  3702  4018 E ExperimentLoader: 	... 17 more
,09-13 08:49:57.433  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-13 08:49:57.433  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 08:49:57.434  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:49:57.434  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:49:57.464  3747  4016 E KeepSync: IOException
09-13 08:49:57.464  3747  4016 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410),
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 08:49:57.464  3747  4016 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:49:57.464  3747  4016 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 08:49:57.464  3747  4016 E KeepSync: 	... 10 more
09-13 08:49:57.464  3747  4016 W KeepSync: Sync result 2
,09-13 08:49:57.473   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 132020, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:49:57.546   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 133707, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:49:57.658  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:57.659  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:57.659  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 08:49:57.659  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.659  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:57.660  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
,09-13 08:49:57.660  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 08:49:57.660  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:49:57.661  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 08:49:57.662  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:57.662  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:57.662  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.663  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:57.663  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:57.663  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:57.664  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:57.664  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:57.664  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.664  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.665  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:57.668  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:57.669  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:57.669  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:57.669  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:57.674  3939  3989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 08:49:57.676  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 08:49:57.677  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 08:49:57.678  3939  3989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 08:49:57.678  3939  3989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 08:49:57.679  3939  3939 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 08:49:57.679  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 08:49:57.679  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 08:49:57.679  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:57.679  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 08:49:57.680  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 08:49:57.680  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 08:49:57.680  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.680  3939  3989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 08:49:57.680  3939  3939 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 08:49:57.680  3939  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 08:49:57.680  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
,09-13 08:49:57.680  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:57.680  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 08:49:57.680  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 08:49:57.681  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 08:49:57.680  3939  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 08:49:57.682  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.682  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:57.683  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:49:57.683  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:49:57.684  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:49:57.684  3939  3939 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 08:49:57.684  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 08:49:57.684  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:57.684  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:57.684  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:57.684  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:57.684  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 08:49:57.685  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 08:49:57.685  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.685  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
,09-13 08:49:57.685  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:57.685  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:57.685  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:57.685  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:57.685  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.685  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:57.685  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.687  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:49:57.687  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:57.687  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:57.687  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:57.689  3939  3989 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 08:49:57.689  3939  3989 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 08:49:57.689  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 08:49:57.691  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 08:49:57.691  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 08:49:57.692  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:57.692  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:57.692  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:57.692  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:57.692  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.692  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.692  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
,09-13 08:49:57.692  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:57.693  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:57.693  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:57.693  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.693  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.693  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.693  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.694  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:57.694  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:57.694  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:57.694  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:57.699  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:57.699  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:49:57.699  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 08:49:57.699  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:57.699  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.699  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:57.700  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
09-13 08:49:57.700  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:49:57.700  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:57.700  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:49:57.700  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:57.700  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:49:57.700  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.700  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.701  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:57.701  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:57.701  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:57.701  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
,09-13 08:49:57.703  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:49:57.703  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:49:57.703  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:49:57.703  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:49:57.703  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.703  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.703  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b931b3b not in the list
,09-13 08:49:57.704  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:57.704  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:57.704  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:49:57.704  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:49:57.704  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.704  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:49:57.704  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:49:57.706  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:49:57.706  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:49:57.706  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:49:57.706  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a90c258 not in the list
09-13 08:49:57.707  3939  3989 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-13 08:49:57.707  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 08:49:57.707  3939  3989 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 08:49:57.708  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 08:49:57.708  3939  3989 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 08:49:57.708  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 08:49:57.711  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 08:49:57.711  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-13 08:49:57.712  3939  3989 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 08:49:57.712  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 08:49:57.712  3939  3989 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 08:49:57.712  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 08:49:57.712  3939  3989 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 08:49:57.712  3939  3989 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 08:49:57.713  3939  3989 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 08:49:57.713  3939  3989 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 08:49:57.714  3939  3989 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 08:49:57.714  3939  3989 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 08:49:57.714  3939  3989 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 08:49:57.714  3939  3989 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 08:49:57.716  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 08:49:57.716  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4fd492b added. We now have 3 listener(s)
09-13 08:49:57.716  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:49:57.718  3939  3989 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 08:49:57.718   872  1376 D WifiService: setWifiEnabled: true pid=3939, uid=10000
,09-13 08:49:57.719   872  1376 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 08:49:57.776  2658  2737 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-13 08:49:57.777  2658  2745 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-13 08:49:57.781  3939  4014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 421)
,09-13 08:49:58.185  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 08:50:00.864   872  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-13 08:50:02.726  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 08:50:02.727  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e657188 added. We now have 4 listener(s)
,09-13 08:50:02.727  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:50:02.743  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:50:02.744  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e657188 removed from the list
,09-13 08:50:02.744  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:50:02.744  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:50:02.745  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:50:02.747  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 08:50:02.748  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8f721 added. We now have 4 listener(s)
09-13 08:50:02.748  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:50:02.752  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:50:02.752  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8f721 removed from the list
09-13 08:50:02.752  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:50:02.752  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:50:02.753  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:50:02.755  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 08:50:02.756  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d37746 added. We now have 4 listener(s)
,09-13 08:50:02.756  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:50:02.764   872   883 D WifiService: setWifiEnabled: false pid=3939, uid=10000
09-13 08:50:02.765   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 08:50:02.776  2658  2674 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 08:50:02.776  2658  2674 D BluetoothAdapterProperties: Setting state to 13
09-13 08:50:02.776  2658  2674 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 08:50:02.777  2658  2674 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 08:50:02.778  2658  2674 I BluetoothAdapterState: Entering PendingCommandState
09-13 08:50:02.784  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:50:02.788  2658  2658 D BluetoothMapService: onReceive
09-13 08:50:02.789  2658  2658 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 08:50:02.789  2658  2658 D BluetoothMapService: STATE_TURNING_OFF
09-13 08:50:02.790  2658  2658 D BluetoothMapService: MAP Service closeService in
09-13 08:50:02.790  2658  2658 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 08:50:02.791  2658  2658 D ObexServerSockets0: shutdown(block = true)
,09-13 08:50:02.791  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 08:50:02.792  2658  2769 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 08:50:02.794  2658  2658 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 08:50:02.794  2658  2770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-13 08:50:02.795  2658  2745 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 08:50:02.795  2658  2658 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 08:50:02.795   872  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 08:50:02.795   872  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 08:50:02.795  2658  2658 I BtOppRfcommListener: stopping Accept Thread
09-13 08:50:02.795   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 08:50:02.796   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 08:50:02.796  2658  3566 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 08:50:02.797  2658  3566 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 08:50:02.798  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.798  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:50:02.798  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:02.798  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:02.798  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:02.798  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:02.798  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:02.798  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:50:02.798  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 08:50:02.799  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.799  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:02.799  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 08:50:02.803  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:02.804   872  1303 E native  : do suspend true
09-13 08:50:02.805  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:02.809  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.809  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:02.809  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:02.809  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:02.809  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:02.809  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:02.809  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:02.809  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:50:02.809  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 08:50:02.810  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Ca,nnot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.810  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:50:02.813  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:02.813  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:02.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:02.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:02.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:02.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:02.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:02.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:50:02.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 08:50:02.814  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:02.814  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:02.814   872   885 I ActivityManager: Start proc 4025:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-13 08:50:02.815  2658  2678 D BluetoothAdapterProperties: Scan Mode:20
,09-13 08:50:02.815  2658  2674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 08:50:02.817  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:02.818   372   870 D CommandListener: Clearing all IP addresses on wlan0
,09-13 08:50:02.819   872  2241 D DhcpClient: Clearing IP address
,09-13 08:50:02.819  2658  2658 D HeadsetService: Received stop request...Stopping profile...
,09-13 08:50:02.820   872   872 D BluetoothHeadset: Proxy object disconnected
,09-13 08:50:02.821  1363  1704 D BluetoothHeadset: Proxy object disconnected
,09-13 08:50:02.821  1960  2102 D BluetoothHeadset: Proxy object disconnected
09-13 08:50:02.821   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 08:50:02.822   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 08:50:02.823  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:02.824  2658  2658 D A2dpService: Received stop request...Stopping profile...
09-13 08:50:02.825   372   870 D CommandListener: Setting iface cfg
09-13 08:50:02.825  2658  2751 D A2dpStateMachine: Exit Disconnected: -1
,09-13 08:50:02.826  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:02.826   872   872 D BluetoothA2dp: Proxy object disconnected
09-13 08:50:02.827  2658  2658 V BluetoothAdapterState: isTurningOff()=true
09-13 08:50:02.827  2658  2658 V BluetoothAdapterState: isTurningOn()=false
,09-13 08:50:02.827  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:02.827  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:02.828  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:02.829  1363  1363 D HeadsetProfile: Bluetooth service disconnected
,09-13 08:50:02.829  2658  2658 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 08:50:02.829  1363  1363 D BluetoothA2dp: Proxy object disconnected
,09-13 08:50:02.829  2658  2678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 08:50:02.829  2658  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 08:50:02.829  2658  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 08:50:02.829  2658  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 08:50:02.830  1500  2577 V NativeCrypto: Read error: ssl=0x9a0d1000: I/O error during system call, Connection timed out
,09-13 08:50:02.830   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 08:50:02.831   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-13 08:50:02.831  2658  2678 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-13 08:50:02.831  2658  2658 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 08:50:02.832   872  2242 D DhcpClient: Receive thread stopped
,09-13 08:50:02.834   872  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-13 08:50:02.835   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 08:50:02.835   872  1303 E native  : do suspend true
,09-13 08:50:02.837  1500  2577 V NativeCrypto: SSL shutdown failed: ssl=0x9a0d1000: I/O error during system call, Broken pipe
09-13 08:50:02.838   397   397 E Parcel  : Reading a NULL string not supported here.
09-13 08:50:02.839   872  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 08:50:02.843  2658  2658 D HidService: Received stop request...Stopping profile...
,09-13 08:50:02.843  2658  2658 D HidService: Stopping Bluetooth HidService
09-13 08:50:02.844  1363  1363 D BluetoothInputDevice: Proxy object disconnected
,09-13 08:50:02.844  1363  1363 D HidProfile: Bluetooth service disconnected
09-13 08:50:02.845  2658  2658 D HealthService: Received stop request...Stopping profile...
09-13 08:50:02.847  2658  2658 D PanService: Received stop request...Stopping profile...
09-13 08:50:02.848  2658  2658 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 08:50:02.849  2658  2658 D BluetoothMapService: stop()
09-13 08:50:02.849  2658  2658 D BluetoothMapAppObserver: deinitObservers()
,09-13 08:50:02.849  2658  2658 D BluetoothMapAppObserver: removeReceiver()
09-13 08:50:02.850  2658  2658 V BluetoothAdapterState: isTurningOff()=true
,09-13 08:50:02.850  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:02.850  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 08:50:02.850  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:02.851  2658  2678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 08:50:02.851  2658  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 08:50:02.851  2658  2658 V BluetoothAdapterState: isTurningOff()=true
09-13 08:50:02.851  2658  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 08:50:02.851  2658  2658 V BluetoothAdapterState: isTurningOn()=false
,09-13 08:50:02.851  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 08:50:02.851  2658  2737 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 08:50:02.851  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:02.851  2658  2737 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 08:50:02.851  2658  2737 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 08:50:02.851  2658  2737 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 08:50:02.851  2658  2658 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-13 08:50:02.852  2658  2658 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 08:50:02.852  2658  2658 V BluetoothAdapterState: isTurningOff()=true
,09-13 08:50:02.852  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:02.852  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:02.852  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:02.852  2658  2678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 08:50:02.852  2658  2658 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 08:50:02.852  2658  2678 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 08:50:02.852  2658  2658 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-13 08:50:02.852  2658  2658 V BluetoothAdapterState: isTurningOff()=true
09-13 08:50:02.852  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:02.853  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:02.853  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:02.853  2658  2658 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-13 08:50:02.853  2658  2658 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 08:50:02.854  2658  2658 D BluetoothMapService: MAP Service closeService in
09-13 08:50:02.854  2658  2658 V BluetoothAdapterState: isTurningOff()=true
09-13 08:50:02.854  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:02.854  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:02.854  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:02.854  2658  2658 D BluetoothMapService: cleanup()
09-13 08:50:02.854  2658  2658 D BluetoothMapService: MAP Service closeService in
09-13 08:50:02.855  2658  2674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 08:50:02.855  2658  2674 D BluetoothAdapterProperties: Setting state to 15
09-13 08:50:02.855  2658  2674 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-13 08:50:02.855  2658  2674 I BluetoothAdapterState: Entering BleOnState
09-13 08:50:02.856  1363  3938 D BluetoothMap: onBluetoothStateChange: up=false
09-13 08:50:02.856  1363  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 08:50:02.857   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 08:50:02.857   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 08:50:02.857  1363  1704 D BluetoothPan: onBluetoothStateChange on: false
09-13 08:50:02.857   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 08:50:02.857  1363  1372 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 08:50:02.859  1363  3938 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 08:50:02.859  1363  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 08:50:02.859   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 08:50:02.859  1960  2102 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 08:50:02.860  2658  2674 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 08:50:02.860  2658  2674 D BluetoothAdapterProperties: Setting state to 16
09-13 08:50:02.860  2658  2674 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 08:50:02.860  2658  2674 D BluetoothAdapterProperties: onBleDisable
09-13 08:50:02.860  2658  2674 I BluetoothAdapterState: Entering PendingCommandState
,09-13 08:50:02.861  2658  2675 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 08:50:02.861  2658  2737 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 08:50:02.861  2658  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 08:50:02.864  2658  2678 D BluetoothAdapterProperties: Scan Mode:20
09-13 08:50:02.867  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.867  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:02.867  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:02.867  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:02.867  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:02.867  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:02.867  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:02.867  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:02.867  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:02.868  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.868  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:02.869  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.869  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:02.869  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:02.869  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:02.869  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:02.869  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:02.869  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:02.869  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:02.869  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:02.870  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.870  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:02.871  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:02.871  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:02.871  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:02.871  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:02.871  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:02.871  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:02.871  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:02.871  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:02.871  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:02.872  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.872  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:02.873  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:02.873  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:02.874  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:02.879   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 08:50:02.902   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 08:50:02.903   872  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-13 08:50:02.903   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 08:50:02.904   372   870 D CommandListener: Clearing all IP addresses on wlan0
,09-13 08:50:02.907   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-13 08:50:02.908  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:02.908  3570  3570 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@428e2bc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-13 08:50:02.909  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:02.913  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:02.917  4025  4025 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-13 08:50:02.925  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 08:50:02.930  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 08:50:02.933   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40a3de5:true
,09-13 08:50:02.944   872  1976 I ActivityManager: Start proc 4044:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 08:50:02.959   372   870 E Netd    : netlink response contains error (No such file or directory)
,09-13 08:50:02.960   872  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-13 08:50:02.961   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 08:50:02.968  4025  4025 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 08:50:02.970  4025  4025 D BluetoothMap: Create BluetoothMap proxy object
,09-13 08:50:02.975   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 08:50:02.977  2129  2329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 08:50:02.978  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:02.978  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:02.978  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:02.978  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:02.978  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:02.978  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:02.978  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:02.978  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:02.978  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 08:50:02.978   872  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 08:50:02.979  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.979  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:02.980  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.980  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:02.980  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:02.980  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:02.980  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:02.980  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:02.980  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:02.980  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:02.980  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:02.980  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:02.981  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:02.981  4025  4025 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-13 08:50:02.982  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:02.982  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:02.982  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:02.982  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:02.982  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:02.982  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:02.982  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:02.982  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:02.982  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:02.982  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:02.982  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:02.989  4044  4044 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 08:50:02.998  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,09-13 08:50:03.008   872  1378 I ActivityManager: Killing 3363:com.google.android.gm/u0a78 (adj 15): empty #17
,09-13 08:50:03.069  2658  2678 I bt_hci  : shut_down
,09-13 08:50:03.127  2658  2682 D bt_hwcfg: hw_epilog_process
,09-13 08:50:03.128  2658  2682 I bt_vendor: low_power_mode_cb
,09-13 08:50:03.152  2658  2682 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 08:50:03.152  2658  2682 I bt_vendor: epilog_cb
,09-13 08:50:03.152  2658  2682 I bt_hci  : epilog_finished_callback
,09-13 08:50:03.158  2658  2678 I bt_hci_h4: hal_close
,09-13 08:50:03.159  2658  2678 I bt_userial_vendor: device fd = 51 close
,09-13 08:50:03.272  4044  4044 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 08:50:03.272  4044  4044 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 08:50:03.272  4044  4044 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 08:50:03.272  4044  4044 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 08:50:03.272  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 08:50:03.273  4044  4044 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 08:50:03.273  4044  4044 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 08:50:03.273  4044  4044 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 08:50:03.2,73  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 08:50:03.273  4044  4044 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 08:50:03.273  4044  4044 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 08:50:03.287  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 08:50:03.289  2658  2675 D bt_stack_manager: event_shut_down_stack finished.
,09-13 08:50:03.290  2658  2674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-13 08:50:03.292  2658  2658 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 08:50:03.292  2658  2674 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-13 08:50:03.293  2658  2658 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 08:50:03.293  2658  2658 D BtGatt.GattService: stop()
09-13 08:50:03.293  2658  2658 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 08:50:03.295  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 08:50:03.297  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,09-13 08:50:03.307   872  1976 I ActivityManager: Killing 3570:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 08:50:03.356  2658  2658 V BluetoothAdapterState: isTurningOff()=false
09-13 08:50:03.356  2658  2658 V BluetoothAdapterState: isTurningOn()=false
,09-13 08:50:03.356  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:03.356  2658  2658 V BluetoothAdapterState: isBleTurningOff()=true
09-13 08:50:03.356  2658  2674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-13 08:50:03.357  2658  2674 D BluetoothAdapterProperties: Setting state to 10
09-13 08:50:03.357  2658  2674 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-13 08:50:03.358   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-13 08:50:03.358  2658  2674 I BluetoothAdapterState: Entering OffState
,09-13 08:50:03.375  4044  4063 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 08:50:03.379  2658  2658 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-13 08:50:03.380  2658  2658 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-13 08:50:03.380  2658  2658 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 08:50:03.381  2658  2675 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 08:50:03.383  2658  2675 D bt_stack_manager: event_clean_up_stack finished.
,09-13 08:50:03.385  2658  2658 I art     : System.exit called, status: 0
,09-13 08:50:03.385  2658  2658 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 08:50:03.389  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 08:50:03.399  1740  1740 D SystemUpdateService: onCreate
,09-13 08:50:03.409  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 08:50:03.415  1740  4079 I SystemUpdateService: active receiver: enabled
,09-13 08:50:03.421  1740  4079 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 08:50:03.426  1740  4079 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 08:50:03.427  1740  4079 I SystemUpdateService: now status is 0 (complete)
09-13 08:50:03.427  1740  4079 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 08:50:03.427  1740  4079 I SystemUpdateService: file has been verified
09-13 08:50:03.427  1740  4079 I SystemUpdateService: OTA package size = 12249756
09-13 08:50:03.427  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 08:50:03.429  1740  2546 I iu.UploadsManager: num queued entries: 0
09-13 08:50:03.429  1740  2546 I iu.UploadsManager: num updated entries: 0
09-13 08:50:03.430  1740  2546 I iu.SyncManager: NEXT; no task
,09-13 08:50:03.439  1740  4079 I SystemUpdateService: showing system update notification
,09-13 08:50:03.446   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b2c9641:true
,09-13 08:50:03.448  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 08:50:03.449  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 08:50:03.481   872  1972 I ActivityManager: Start proc 4082:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 08:50:03.483   872  1959 I ActivityManager: Process com.android.bluetooth (pid 2658) has died
,09-13 08:50:03.486  1740  1740 D SystemUpdateService: onDestroy
,09-13 08:50:03.516  4082  4082 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 08:50:03.518  4082  4082 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 08:50:03.527  4082  4082 D SprintDMHelper: simOperator: 
09-13 08:50:03.527  4082  4082 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 08:50:03.548   872  2001 I ActivityManager: Start proc 4094:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 08:50:03.666   872  1707 I ActivityManager: Start proc 4109:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 08:50:03.669   872  1707 I ActivityManager: Killing 2708:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 08:50:03.723  4109  4109 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 08:50:03.774  4109  4109 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 08:50:03.774  4109  4109 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 08:50:03.774  4109  4109 I GAv4    :   adb logcat -s GAv4
,09-13 08:50:03.788  4109  4109 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 08:50:03.794  4109  4109 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 08:50:03.822  4109  4126 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 08:50:03.929  4109  4109 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 08:50:03.970  4109  4109 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 08:50:03.983  4109  4109 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 7400-7407)
,09-13 08:50:03.983  4109  4109 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 08:50:03.992  4109  4109 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7c872ec}
,09-13 08:50:03.992  4109  4109 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 08:50:03.992  4109  4109 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 08:50:04.001  4109  4109 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 08:50:04.002  4109  4109 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 08:50:04.021  4109  4109 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 08:50:04.037  4109  4109 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 08:50:04.037  4109  4109 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 08:50:04.037  4109  4109 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 08:50:04.037  4109  4109 I Adreno  : Build Date                       : 10/20/15
09-13 08:50:04.037  4109  4109 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 08:50:04.037  4109  4109 I Adreno  : Local Branch                     : M14
09-13 08:50:04.037  4109  4109 I Adreno  : Remote Branch                    : 
09-13 08:50:04.037  4109  4109 I Adreno  : Remote Branch                    : 
09-13 08:50:04.037  4109  4109 I Adreno  : Reconstruct Branch               : 
,09-13 08:50:04.099  4109  4109 I NSApplication: Starting up...
,09-13 08:50:04.111  4109  4155 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 08:50:04.142   872  1707 I ActivityManager: Start proc 4160:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-13 08:50:04.144   872  1707 I ActivityManager: Killing 3196:android.process.acore/u0a5 (adj 15): empty #17
,09-13 08:50:04.218  4160  4160 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 08:50:04.428   872  1976 I ActivityManager: Killing 3820:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 08:50:04.492   872  3378 I ActivityManager: Start proc 4174:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 08:50:04.551  4174  4174 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 08:50:04.599  4174  4174 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 08:50:04.666   872  1952 I ActivityManager: Killing 3835:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 08:50:07.801   872   882 D WifiService: setWifiEnabled: true pid=3939, uid=10000
,09-13 08:50:07.801   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 08:50:07.807   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-13 08:50:07.813  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:07.813  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:07.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:07.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:07.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:07.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:07.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:07.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:07.813  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:07.813  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:07.813  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:07.816  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:07.816  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:07.816  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:07.816  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:07.816  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:07.816  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:07.816  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:07.816  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:07.816  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:07.817  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:07.817  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:07.818  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:07.818  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:07.818  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:07.818  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:07.818  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:07.818  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:07.818  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:07.818  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:07.818  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:07.818  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:07.818  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:07.834   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-13 08:50:07.835   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 08:50:07.837   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 08:50:07.838   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 08:50:07.838   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 08:50:07.839   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 08:50:07.839   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 08:50:07.859   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 08:50:07.860   372   870 D CommandListener: Setting iface cfg
,09-13 08:50:07.860   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-13 08:50:07.860   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-13 08:50:07.860   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 08:50:07.871   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 08:50:07.871   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-13 08:50:07.871   872  1303 E native  : do suspend true
,09-13 08:50:07.897   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 08:50:07.948  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:50:07.956  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:50:07.958  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:50:07.978  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 08:50:07.978  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 08:50:07.978  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:50:07.978  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:50:07.998  3663  3663 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 08:50:07.998  3663  3663 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 08:50:07.999  3663  3663 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-13 08:50:08.578   872  3377 I ActivityManager: Killing 3599:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 08:50:09.178   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 08:50:09.250   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.62 rxSuccessRate=7.88 delta 1000 -> 1000
,09-13 08:50:09.252   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-13 08:50:09.252   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 08:50:09.268   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 08:50:09.332   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 08:50:09.334  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 08:50:09.759  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 08:50:09.800  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 08:50:09.801  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 08:50:09.804   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 08:50:09.819   872  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 08:50:09.819   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 08:50:09.820   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 08:50:09.845   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 08:50:09.864   372   870 D CommandListener: Setting iface cfg
,09-13 08:50:09.867   872  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 08:50:09.883   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 08:50:09.906   872  4209 D DhcpClient: Receive thread started
,09-13 08:50:09.994   872  1303 E native  : do suspend false
,09-13 08:50:10.017   872  2241 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 08:50:10.076   872  4209 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172651, domain null
,09-13 08:50:10.077   872  2241 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172651 seconds
,09-13 08:50:10.080   872  2241 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 08:50:10.100   872  4209 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 08:50:10.101   872  2241 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 08:50:10.106   372   870 D CommandListener: Setting iface cfg
,09-13 08:50:10.118   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 08:50:10.118   872  2241 D DhcpClient: Scheduling renewal in 86399s
,09-13 08:50:10.124   872  1303 E native  : do suspend true
,09-13 08:50:10.149   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 08:50:10.153   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 08:50:10.155   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 08:50:10.158   872  1305 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 08:50:10.168   872  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 08:50:10.214   872  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 08:50:10.214   872  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 08:50:10.216   872  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 08:50:10.218   872  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-13 08:50:10.219   872  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 08:50:10.235   872  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 08:50:10.242   872  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 08:50:10.242   872  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-13 08:50:10.243   872  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-13 08:50:10.243   872  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 08:50:10.243   872  1305 D ConnectivityService:    accepting network in place of null
09-13 08:50:10.243   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 08:50:10.244   872  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 08:50:10.258   872  4208 D NetlinkSocketObserver: NeighborEvent{elapsedMs=173682, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 08:50:10.275   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 08:50:10.322   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 08:50:10.329   872  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 08:50:10.329   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 08:50:10.331   872  4207 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-13 08:50:10.337   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-13 08:50:10.344  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:10.344  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:10.344  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:10.344  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:10.344  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:10.344  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:10.344  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:10.344  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:50:10.344  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 08:50:10.345  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:10.345  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:50:10.336   872  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-13 08:50:10.352  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:10.353  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:10.353  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:10.353  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:10.353  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:10.353  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:10.353  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:10.353  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:50:10.353  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:50:10.353  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:10.353  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:10.355  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:10.355  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:10.355  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:10.355  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:10.355  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:10.355  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:10.355  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:10.355  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:50:10.355  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 08:50:10.355  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:10.356  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:50:10.369  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 08:50:10.377  1740  1740 D SystemUpdateService: onCreate
,09-13 08:50:10.391  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 08:50:10.403  1740  4219 I SystemUpdateService: active receiver: enabled
,09-13 08:50:10.408   872  4207 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 06:50:10 GMT], X-Android-Received-Millis=[1473749410407], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473749410372]}
,09-13 08:50:10.409   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 08:50:10.409   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-13 08:50:10.409   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 08:50:10.410   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 08:50:10.421  1740  4219 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 08:50:10.446  1740  4219 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 08:50:10.446  1740  4219 I SystemUpdateService: now status is 0 (complete)
09-13 08:50:10.446  1740  4219 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 08:50:10.446  1740  4219 I SystemUpdateService: file has been verified
09-13 08:50:10.446  1740  4219 I SystemUpdateService: OTA package size = 12249756
,09-13 08:50:10.449  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:50:10.454  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 08:50:10.455  1740  2546 I iu.UploadsManager: num queued entries: 0
,09-13 08:50:10.455  1740  2546 I iu.UploadsManager: num updated entries: 0
09-13 08:50:10.456  1740  2546 I iu.SyncManager: NEXT; no task
,09-13 08:50:10.475  1740  4219 I SystemUpdateService: showing system update notification
,09-13 08:50:10.478  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 08:50:10.486  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 08:50:10.487  1740  4225 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-13 08:50:10.487  1740  4225 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 08:50:10.493  1740  4225 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 08:50:10.498  4082  4082 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 08:50:10.505  4082  4082 D SprintDMHelper: simOperator: 
,09-13 08:50:10.505  4082  4082 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 08:50:10.569  1740  1740 D SystemUpdateService: onDestroy
,09-13 08:50:10.664  2411  4228 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 08:50:10.703  1500  4235 I VacuumService: Vacuum at: now=1473749410703 tag=VacuumService
,09-13 08:50:10.769  1500  2066 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 08:50:10.769  1500  2066 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 08:50:10.769  1500  2066 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:50:10.769  1500  2066 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:50:10.818  1740  4225 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-13 08:50:10.877  1500  4237 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-13 08:50:10.879  1500  4237 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 08:50:10.926  1500  4237 W Uploader:  no longer exists, so no auth token.
,09-13 08:50:11.328   872  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 08:50:12.059  1500  4237 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 08:50:12.059  1500  4237 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 08:50:12.059  1500  4237 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:50:12.059  1500  4237 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:50:12.073  1500  4237 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 08:50:12.073  1500  4237 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 08:50:12.073  1500  4237 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 08:50:12.404  1500  4237 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 08:50:12.404  1500  4237 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 08:50:12.405  1500  4237 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:50:12.405  1500  4237 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:50:12.422  1500  4237 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 08:50:12.422  1500  4237 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 08:50:12.422  1500  4237 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 08:50:12.810   872  3378 D WifiService: setWifiEnabled: false pid=3939, uid=10000
,09-13 08:50:12.811   872  3378 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 08:50:12.839  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 08:50:12.847   872  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 08:50:12.847   872  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 08:50:12.847   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 08:50:12.848   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 08:50:12.885   872  1303 E native  : do suspend true
,09-13 08:50:12.892   872  2241 D DhcpClient: Clearing IP address
,09-13 08:50:12.892   372   870 D CommandListener: Clearing all IP addresses on wlan0
,09-13 08:50:12.895   372   870 D CommandListener: Setting iface cfg
09-13 08:50:12.900  1500  4232 V NativeCrypto: Read error: ssl=0x9b643400: I/O error during system call, Connection timed out
,09-13 08:50:12.902  1500  4232 V NativeCrypto: SSL shutdown failed: ssl=0x9b643400: I/O error during system call, Broken pipe
,09-13 08:50:12.906   872  3377 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-13 08:50:12.907   872  4207 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-13 08:50:12.908   872  4207 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-13 08:50:12.909   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-13 08:50:12.909   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 08:50:12.910   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 08:50:12.915   872  4209 D DhcpClient: Receive thread stopped
,09-13 08:50:12.918   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 08:50:12.919   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-13 08:50:12.921   872  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-13 08:50:12.923   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 08:50:12.923   872  1303 E native  : do suspend true
,09-13 08:50:12.926   872  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-13 08:50:12.928   397   397 E Parcel  : Reading a NULL string not supported here.
,09-13 08:50:12.943  1500  4237 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.209.170 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,09-13 08:50:12.951   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 08:50:12.977   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 08:50:12.977   372   870 D CommandListener: Clearing all IP addresses on wlan0
09-13 08:50:12.977   872  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 08:50:12.978   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 08:50:12.981  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:12.981  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:12.981  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:12.981  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:12.981  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:12.981  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:12.981  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:12.981  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:12.981  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:12.981  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:12.981  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:12.986  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:12.986  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:12.986  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:12.986  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:12.986  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:12.986  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:12.986  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:12.986  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:12.986  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:12.986  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:12.986  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:12.982   872   889 D Tethering: MasterInitialState.processMessage what=3
09-13 08:50:12.987  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:12.987  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:12.987  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:12.987  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:12.987  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:12.987  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:12.987  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:12.987  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:12.987  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:12.988  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:12.988  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:12.988   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 08:50:12.990  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-13 08:50:12.994  1740  1740 D SystemUpdateService: onCreate
09-13 08:50:12.998  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 08:50:13.004   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 08:50:13.006  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:13.006  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:13.006  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:13.006  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:13.006  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:13.006  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:13.006  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:13.006  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:13.006  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:13.006  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:13.007  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:13.007  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:13.007  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:13.007  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:13.007  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:13.007  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:13.007  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:13.007  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:13.007  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:13.007  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:13.007  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:13.007  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:13.009  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:13.009  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:13.009  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:13.009  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:13.009  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:13.009  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:13.009  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:13.009  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:13.009  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:13.009  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:13.009  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:13.009  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-13 08:50:13.010  2129  2329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 08:50:13.011   872  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 08:50:13.011  1740  2546 I iu.UploadsManager: num queued entries: 0
,09-13 08:50:13.017  1740  2546 I iu.UploadsManager: num updated entries: 0
09-13 08:50:13.017  1740  2546 I iu.SyncManager: NEXT; no task
09-13 08:50:13.018  1740  4257 I SystemUpdateService: active receiver: enabled
09-13 08:50:13.020  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-13 08:50:13.021  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-13 08:50:13.023  4082  4082 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE,
09-13 08:50:13.026  4082  4082 D SprintDMHelper: simOperator: 
09-13 08:50:13.026  4082  4082 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 08:50:13.054  1740  4257 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 08:50:13.055  2411  4261 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 08:50:13.067   372   870 E Netd    : netlink response contains error (No such file or directory)
,09-13 08:50:13.070   872  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-13 08:50:13.070   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 08:50:13.078  1740  4257 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 08:50:13.078  1740  4257 I SystemUpdateService: now status is 0 (complete)
09-13 08:50:13.078  1740  4257 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 08:50:13.078  1740  4257 I SystemUpdateService: file has been verified
09-13 08:50:13.079  1740  4257 I SystemUpdateService: OTA package size = 12249756
,09-13 08:50:13.085  1740  4257 I SystemUpdateService: showing system update notification
,09-13 08:50:13.094  1740  1740 D SystemUpdateService: onDestroy
,09-13 08:50:17.861   872   889 I ActivityManager: Start proc 4268:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 08:50:17.979  4268  4268 D AdapterServiceConfig: Adding HeadsetService
09-13 08:50:17.980  4268  4268 D AdapterServiceConfig: Adding A2dpService
09-13 08:50:17.980  4268  4268 D AdapterServiceConfig: Adding HidService
09-13 08:50:17.980  4268  4268 D AdapterServiceConfig: Adding HealthService
,09-13 08:50:17.980  4268  4268 D AdapterServiceConfig: Adding PanService
09-13 08:50:17.981  4268  4268 D AdapterServiceConfig: Adding GattService
09-13 08:50:17.981  4268  4268 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 08:50:17.996   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@49459f:true
,09-13 08:50:17.996  4268  4268 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 08:50:18.000  4268  4268 I bt_bluedroid: init
,09-13 08:50:18.001  4268  4280 I BluetoothAdapterState: Entering OffState
,09-13 08:50:18.007  4268  4281 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 08:50:18.007  4268  4281 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 08:50:18.008  4268  4281 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 08:50:18.008  4268  4281 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 08:50:18.010  4268  4268 I bt_bluedroid: get_profile_interface socket
,09-13 08:50:18.013  4268  4268 I bt_bluedroid: get_profile_interface sdp
,09-13 08:50:18.016  4268  4284 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 08:50:18.017  4268  4279 I bt_bluedroid: config_hci_snoop_log
09-13 08:50:18.019  4268  4284 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 08:50:18.022   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 08:50:18.032  4268  4280 D BluetoothAdapterState: Current state: OFF, message: 0
09-13 08:50:18.033  4268  4280 D BluetoothAdapterProperties: Setting state to 14
,09-13 08:50:18.033  4268  4280 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 08:50:18.038  4268  4280 D BluetoothBondStateMachine: make
,09-13 08:50:18.043  4268  4285 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 08:50:18.050  4268  4280 I BluetoothAdapterState: Entering PendingCommandState
,09-13 08:50:18.054  4268  4268 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 08:50:18.060  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:50:18.061  4268  4268 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 08:50:18.063  4268  4268 D BtGatt.GattService: Received start request. Starting profile...
,09-13 08:50:18.063  4268  4268 D BtGatt.GattService: start()
09-13 08:50:18.063  4268  4268 I bt_bluedroid: get_profile_interface gatt
,09-13 08:50:18.066  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:50:18.066  4268  4268 D BtGatt.AdvertiseManager: advertise manager created
,09-13 08:50:18.081  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-13 08:50:18.082  4268  4268 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:18.082  4268  4268 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 08:50:18.082  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:18.083  4268  4280 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 08:50:18.084  4268  4280 I bt_bluedroid: enable
,09-13 08:50:18.084  4268  4281 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 08:50:18.086  4268  4281 I bt_hci  : start_up
,09-13 08:50:18.109  4268  4281 I bt_vendor: alloc value 0xb3a7f189
,09-13 08:50:18.109  4268  4281 I bt_vendor: init
,09-13 08:50:18.109  4268  4281 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 08:50:18.110  4268  4281 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 08:50:18.216  4268  4281 D bt_hci  : start_up starting async portion
,09-13 08:50:18.216  4268  4288 I bt_hci  : event_finish_startup
09-13 08:50:18.217  4268  4288 I bt_hci_h4: hal_open
,09-13 08:50:18.217  4268  4288 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 08:50:18.226  4268  4288 I bt_userial_vendor: device fd = 51 open
,09-13 08:50:18.247   872  1305 D ConnectivityService: handlePromptUnvalidated 101
,09-13 08:50:18.259  4268  4288 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 08:50:18.291  4268  4288 D bt_hwcfg: Chipset BCM4354A2
09-13 08:50:18.291  4268  4288 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 08:50:18.292  4268  4288 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 08:50:18.950  4268  4288 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 08:50:18.952  4268  4288 D bt_hwcfg: Settlement delay -- 100 ms
09-13 08:50:18.952  4268  4288 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 08:50:19.069  4268  4288 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 08:50:19.070  4268  4288 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 08:50:19.099  4268  4288 I bt_hwcfg: vendor lib fwcfg completed
09-13 08:50:19.099  4268  4288 I bt_vendor: firmware callback
09-13 08:50:19.100  4268  4288 I bt_hci  : firmware_config_callback
,09-13 08:50:19.111  4268  4290 I bt_btu  : btu_task pending for preload complete event
,09-13 08:50:19.111  4268  4290 I bt_btu_task: Bluetooth chip preload is complete
,09-13 08:50:19.111  4268  4290 I bt_btu  : btu_task received preload complete event,
,09-13 08:50:19.124  4268  4290 I         : BTE_InitTraceLevels -- TRC_HCI,
,09-13 08:50:19.124  4268  4290 I         : BTE_InitTraceLevels -- TRC_L2CAP,
,09-13 08:50:19.125  4268  4290 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
,09-13 08:50:19.125  4268  4290 I         : BTE_InitTraceLevels -- TRC_AVDT,
,09-13 08:50:19.125  4268  4290 I         : BTE_InitTraceLevels -- TRC_AVRC,
,09-13 08:50:19.126  4268  4290 I         : BTE_InitTraceLevels -- TRC_A2D
,09-13 08:50:19.126  4268  4290 I         : BTE_InitTraceLevels -- TRC_BNEP,
,09-13 08:50:19.126  4268  4290 I         : BTE_InitTraceLevels -- TRC_BTM,
,09-13 08:50:19.126  4268  4290 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 08:50:19.127  4268  4290 I         : BTE_InitTraceLevels -- TRC_PAN
,09-13 08:50:19.127  4268  4290 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 08:50:19.127  4268  4290 I         : BTE_InitTraceLevels -- TRC_GATT
,09-13 08:50:19.127  4268  4290 I         : BTE_InitTraceLevels -- TRC_SMP
,09-13 08:50:19.128  4268  4290 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 08:50:19.128  4268  4290 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 08:50:19.252  4268  4290 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fcd9d
,09-13 08:50:19.252  4268  4290 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fcd9d 
,09-13 08:50:19.259  4268  4284 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 08:50:19.261  4268  4284 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 08:50:19.261  4268  4284 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 08:50:19.263  4268  4284 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 08:50:19.264  4268  4284 D BluetoothAdapterProperties: Scan Mode:20
09-13 08:50:19.264  4268  4284 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 08:50:19.264  4268  4284 D bt_hci  : do_postload posting postload work item
09-13 08:50:19.264  4268  4288 I bt_hci  : event_postload
09-13 08:50:19.264  4268  4288 I bt_vendor: sco_config_cb
09-13 08:50:19.265  4268  4288 I bt_hci  : sco_config_callback postload finished.
,09-13 08:50:19.267  4268  4284 D bt_bte_conf: Device ID record 1 : primary
09-13 08:50:19.267  4268  4284 D bt_bte_conf:   vendorId            = 000f
09-13 08:50:19.267  4268  4284 D bt_bte_conf:   vendorIdSource      = 0001
09-13 08:50:19.267  4268  4284 D bt_bte_conf:   product             = 1200
09-13 08:50:19.267  4268  4284 D bt_bte_conf:   version             = 1436
09-13 08:50:19.268  4268  4284 D bt_bte_conf:   clientExecutableURL = 
09-13 08:50:19.268  4268  4284 D bt_bte_conf:   serviceDescription  = 
09-13 08:50:19.268  4268  4284 D bt_bte_conf:   documentationURL    = 
09-13 08:50:19.268  4268  4284 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 08:50:19.269  4268  4281 D bt_stack_manager: event_start_up_stack finished
09-13 08:50:19.270  4268  4280 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 08:50:19.270  4268  4280 D BluetoothAdapterProperties: Setting state to 15
,09-13 08:50:19.271  4268  4280 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 08:50:19.273  4268  4288 I bt_vendor: low_power_mode_cb
09-13 08:50:19.274  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:19.275  4268  4280 I BluetoothAdapterState: Entering BleOnState
,09-13 08:50:19.278  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:19.280  4268  4280 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 08:50:19.280  4268  4280 D BluetoothAdapterProperties: Setting state to 11
09-13 08:50:19.280  4268  4280 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 08:50:19.282  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:19.284  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
09-13 08:50:19.286  4268  4268 D HeadsetService: Received start request. Starting profile...
,09-13 08:50:19.289  4268  4268 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 08:50:19.289  4268  4268 D HeadsetStateMachine: make
,09-13 08:50:19.293  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:19.294  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:19.296  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:19.307  4268  4280 I BluetoothAdapterState: Entering PendingCommandState
,09-13 08:50:19.308  4268  4268 D HeadsetStateMachine: max_hf_connections = 1
09-13 08:50:19.308  4268  4268 I bt_bluedroid: get_profile_interface handsfree
,09-13 08:50:19.309  4268  4284 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-13 08:50:19.309  4268  4284 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 08:50:19.316  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:50:19.316  4268  4268 D A2dpService: Received start request. Starting profile...
,09-13 08:50:19.317  4268  4268 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-13 08:50:19.317  4268  4268 I bt_bluedroid: get_profile_interface avrcp
,09-13 08:50:19.323  4268  4268 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 08:50:19.323  4268  4268 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-13 08:50:19.323  4268  4268 D A2dpStateMachine: make
,09-13 08:50:19.325  4268  4268 I bt_bluedroid: get_profile_interface a2dp
,09-13 08:50:19.325  4268  4284 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 08:50:19.326  4268  4300 D A2dpStateMachine: Enter Disconnected: -2
,09-13 08:50:19.327  4268  4268 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 08:50:19.328  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:50:19.330  4268  4268 D HidService: Received start request. Starting profile...
,09-13 08:50:19.330  4268  4268 I bt_bluedroid: get_profile_interface hidhost
09-13 08:50:19.330  4268  4268 D HidService: setHidService(): set to: null
09-13 08:50:19.330  4268  4284 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39de3e5
09-13 08:50:19.330  4268  4284 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 08:50:19.331  4268  4268 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 08:50:19.331  4025  4025 D BluetoothInputDevice: Proxy object connected
09-13 08:50:19.332  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:50:19.332  4268  4268 D HealthService: Received start request. Starting profile...
09-13 08:50:19.333  4025  4025 D HidProfile: Bluetooth service connected
,09-13 08:50:19.334  4268  4268 I bt_bluedroid: get_profile_interface health
,09-13 08:50:19.335  4268  4268 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 08:50:19.336  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:50:19.337  4268  4268 D PanService: Received start request. Starting profile...
,09-13 08:50:19.337  4025  4025 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 08:50:19.337  4268  4268 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 08:50:19.337  4268  4268 I bt_bluedroid: get_profile_interface pan
,09-13 08:50:19.338  4025  4025 D PanProfile: Bluetooth service connected
09-13 08:50:19.338  4268  4284 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 08:50:19.342  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 08:50:19.343  4268  4268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
09-13 08:50:19.344  4025  4025 D BluetoothMap: Proxy object connected
09-13 08:50:19.345  4268  4268 D BluetoothMapService: Received start request. Starting profile...
09-13 08:50:19.345  4268  4268 D BluetoothMapService: start()
09-13 08:50:19.345  4025  4025 D MapProfile: Bluetooth service connected
09-13 08:50:19.345  4025  4025 D BluetoothMap: getConnectedDevices()
09-13 08:50:19.346  4025  4025 D BluetoothMap: Bluetooth is Not enabled
,09-13 08:50:19.347  4268  4268 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 08:50:19.348  4268  4268 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 08:50:19.348  4268  4268 D BluetoothMapAppObserver: createReceiver()
,09-13 08:50:19.349  4268  4268 D BluetoothMapAppObserver: initObservers()
09-13 08:50:19.349  4268  4268 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 08:50:19.356  4268  4268 V BluetoothAdapterState: isTurningOff()=false
09-13 08:50:19.356  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:19.356  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:19.356  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:19.358  4268  4297 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isTurningOff()=false
09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isTurningOff()=false
09-13 08:50:19.358  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:19.359  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:19.359  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:19.359  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-13 08:50:19.359  4268  4268 V BluetoothAdapterState: isTurningOn()=true
,09-13 08:50:19.359  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:19.359  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:19.360  4268  4268 V BluetoothAdapterState: isTurningOff()=false
09-13 08:50:19.360  4268  4268 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:19.360  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 08:50:19.360  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:19.360  4268  4280 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 08:50:19.360  4268  4280 D BluetoothAdapterProperties: ScanMode =  20
,09-13 08:50:19.361  4268  4280 D BluetoothAdapterProperties: State =  11
,09-13 08:50:19.364  4268  4284 D BluetoothAdapterProperties: Scan Mode:21
,09-13 08:50:19.364  4268  4280 D BluetoothAdapterProperties: Setting state to 12
09-13 08:50:19.364  4268  4280 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 08:50:19.364  4268  4284 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 08:50:19.365  1363  1704 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 08:50:19.367  4268  4280 I BluetoothAdapterState: Entering OnState
,09-13 08:50:19.368  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:19.368  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:19.368  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:19.368  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:19.368  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:19.368  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:19.368  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:19.368  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:19.370  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:19.370  1363  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 08:50:19.371  1363  1363 D BluetoothMap: Proxy object connected
,09-13 08:50:19.371  1363  1363 D MapProfile: Bluetooth service connected
09-13 08:50:19.371  1363  1363 D BluetoothMap: getConnectedDevices()
09-13 08:50:19.372   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 08:50:19.373   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 08:50:19.373  1363  1704 D BluetoothPan: onBluetoothStateChange on: true
,09-13 08:50:19.374  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:19.374  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:19.374  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:19.374  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:19.374  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:19.374  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:19.374  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:19.374  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 08:50:19.374   872   872 D BluetoothA2dp: Proxy object connected
09-13 08:50:19.375  1363  1363 D BluetoothInputDevice: Proxy object connected
09-13 08:50:19.375  1363  1363 D HidProfile: Bluetooth service connected
09-13 08:50:19.376  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:19.377  4268  4268 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 08:50:19.378  4268  4268 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 08:50:19.380  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 08:50:19.380  1363  1363 D PanProfile: Bluetooth service connected
,09-13 08:50:19.381  4268  4268 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 08:50:19.381  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:19.381  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:19.381  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:19.381  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:19.381  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:19.381  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:19.381  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:19.381  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:19.381   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 08:50:19.382  4025  4036 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 08:50:19.384  4268  4268 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 08:50:19.384  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:19.384  4025  4037 D BluetoothPan: onBluetoothStateChange on: true
09-13 08:50:19.385  1363  1372 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 08:50:19.385  4268  4268 D ObexServerSockets: Succeed to create listening sockets 
,09-13 08:50:19.385  4268  4268 D ObexServerSockets0: startAccept()
09-13 08:50:19.385  4268  4268 D ObexServerSockets0: prepareForNewConnect()
,09-13 08:50:19.387  4268  4268 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-13 08:50:19.388  1363  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 08:50:19.388  4268  4268 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 08:50:19.389  4268  4306 D ObexServerSockets0: Accepting socket connection...
09-13 08:50:19.389  4268  4307 D ObexServerSockets0: Accepting socket connection...
09-13 08:50:19.390  1363  1363 D BluetoothA2dp: Proxy object connected
09-13 08:50:19.390  4025  4036 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 08:50:19.390  1363  1704 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 08:50:19.391   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 08:50:19.391  4025  4037 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 08:50:19.391  1960  1973 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 08:50:19.393   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 08:50:19.394  4268  4268 D BluetoothMapService: onReceive
09-13 08:50:19.394  4268  4268 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 08:50:19.394  4268  4268 D BluetoothMapService: STATE_ON
,09-13 08:50:19.396  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:19.398  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:19.399  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:19.399  4025  4025 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-13 08:50:19.402  4025  4025 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 08:50:19.407  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 08:50:19.409  4025  4025 D BluetoothA2dp: Proxy object connected
,09-13 08:50:19.413  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 08:50:19.416  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,09-13 08:50:19.423  4025  4025 D BluetoothPbap: Proxy object connected
,09-13 08:50:19.423  1363  1363 D BluetoothPbap: Proxy object connected
09-13 08:50:19.423  1363  1363 D PbapServerProfile: Bluetooth service connected
09-13 08:50:19.423  4025  4025 D PbapServerProfile: Bluetooth service connected
09-13 08:50:19.423  4268  4268 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 08:50:19.423  4268  4268 D ObexServerSockets0: prepareForNewConnect()
,09-13 08:50:19.434  4268  4311 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 08:50:19.455  4268  4315 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 08:50:19.458  4268  4315 I BtOppRfcommListener: Accept thread started.,
,09-13 08:50:19.475   872   872 D BluetoothHeadset: Proxy object connected
,09-13 08:50:19.476  1363  1704 D BluetoothHeadset: Proxy object connected
,09-13 08:50:19.476  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-13 08:50:19.477  1960  1977 D BluetoothHeadset: Proxy object connected
09-13 08:50:19.477   872   872 D BluetoothHeadset: Proxy object connected
09-13 08:50:19.477   872   872 D BluetoothHeadset: Proxy object connected
,09-13 08:50:19.481   872   889 D BluetoothHeadset: Proxy object connected
,09-13 08:50:19.490  1363  1372 D BluetoothHeadset: Proxy object connected
,09-13 08:50:19.491  1363  1363 D HeadsetProfile: Bluetooth service connected
09-13 08:50:19.491   872   889 D BluetoothHeadset: Proxy object connected
,09-13 08:50:19.492  1960  2102 D BluetoothHeadset: Proxy object connected
,09-13 08:50:19.505  4025  4036 D BluetoothHeadset: Proxy object connected
,09-13 08:50:19.505  4025  4025 D HeadsetProfile: Bluetooth service connected
,09-13 08:50:22.832  4268  4280 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 08:50:22.832  4268  4280 D BluetoothAdapterProperties: Setting state to 13
09-13 08:50:22.833  4268  4280 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 08:50:22.834  4268  4280 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 08:50:22.838  4268  4280 I BluetoothAdapterState: Entering PendingCommandState
,09-13 08:50:22.843  4268  4284 D BluetoothAdapterProperties: Scan Mode:20
,09-13 08:50:22.845  4268  4268 D BluetoothMapService: onReceive
,09-13 08:50:22.846  4268  4268 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 08:50:22.846  4268  4268 D BluetoothMapService: STATE_TURNING_OFF
09-13 08:50:22.846  4268  4268 D BluetoothMapService: MAP Service closeService in
09-13 08:50:22.847  4268  4268 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 08:50:22.847  4268  4268 D ObexServerSockets0: shutdown(block = true)
,09-13 08:50:22.848  4268  4306 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-13 08:50:22.848  4268  4280 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 08:50:22.849  4268  4268 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 08:50:22.850  4268  4292 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 08:50:22.850  4268  4307 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-13 08:50:22.850  4268  4268 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 08:50:22.852  4268  4268 I BtOppRfcommListener: stopping Accept Thread
,09-13 08:50:22.853  4268  4315 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-13 08:50:22.855  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 08:50:22.855  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:22.855  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:22.855  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:22.855  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:22.855  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:22.855  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:22.855  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:22.855  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:22.855  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:22.856  4268  4315 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 08:50:22.856  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:22.857  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:22.859  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:22.860  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:22.860  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:22.860  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:22.860  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:22.860  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:22.860  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:22.860  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:22.860  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 08:50:22.861  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:22.861  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:22.862  4268  4268 D HeadsetService: Received stop request...Stopping profile...
09-13 08:50:22.863  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 08:50:22.864  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:22.864  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:22.864  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:22.864  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:22.864  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 08:50:22.864  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:22.864  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:22.864  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:22.864  3939  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 08:50:22.864  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:22.866   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 08:50:22.866  1363  3938 D BluetoothHeadset: Proxy object disconnected
09-13 08:50:22.867  1363  1363 D HeadsetProfile: Bluetooth service disconnected
09-13 08:50:22.867  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:22.867  4025  4036 D BluetoothHeadset: Proxy object disconnected
,09-13 08:50:22.868  1960  1977 D BluetoothHeadset: Proxy object disconnected
,09-13 08:50:22.868   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 08:50:22.869   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 08:50:22.869  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:22.869  4268  4268 D A2dpService: Received stop request...Stopping profile...
09-13 08:50:22.869  4268  4300 D A2dpStateMachine: Exit Disconnected: -1
09-13 08:50:22.870  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:22.872  1363  1363 D BluetoothA2dp: Proxy object disconnected
09-13 08:50:22.872   872   872 D BluetoothA2dp: Proxy object disconnected
09-13 08:50:22.873  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,09-13 08:50:22.874  4268  4268 D HidService: Received stop request...Stopping profile...
09-13 08:50:22.874  4268  4268 D HidService: Stopping Bluetooth HidService
09-13 08:50:22.874  4025  4025 D HeadsetProfile: Bluetooth service disconnected
09-13 08:50:22.874  4025  4025 D BluetoothA2dp: Proxy object disconnected
09-13 08:50:22.875  1363  1363 D BluetoothInputDevice: Proxy object disconnected
09-13 08:50:22.875  1363  1363 D HidProfile: Bluetooth service disconnected
09-13 08:50:22.876  4268  4268 D HealthService: Received stop request...Stopping profile...
09-13 08:50:22.877  4025  4025 D BluetoothInputDevice: Proxy object disconnected
09-13 08:50:22.877  4025  4025 D HidProfile: Bluetooth service disconnected
09-13 08:50:22.878  4268  4268 V BluetoothAdapterState: isTurningOff()=true
09-13 08:50:22.878  4268  4268 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:22.878  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 08:50:22.878  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:22.879  4268  4268 D PanService: Received stop request...Stopping profile...
09-13 08:50:22.880  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 08:50:22.880  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 08:50:22.880  1363  1363 D PanProfile: Bluetooth service disconnected
,09-13 08:50:22.883  4268  4268 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-13 08:50:22.883  4268  4268 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 08:50:22.883  4025  4025 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 08:50:22.884  4025  4025 D PanProfile: Bluetooth service disconnected
09-13 08:50:22.884  4268  4290 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 08:50:22.884  4268  4290 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 08:50:22.884  4268  4290 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 08:50:22.884  4268  4284 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 08:50:22.884  4268  4284 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 08:50:22.884  4268  4268 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 08:50:22.885  4268  4268 D BluetoothMapService: stop()
,09-13 08:50:22.885  4268  4268 D BluetoothMapAppObserver: deinitObservers()
,09-13 08:50:22.886  4268  4268 D BluetoothMapAppObserver: removeReceiver()
,09-13 08:50:22.887  1363  1363 D BluetoothMap: Proxy object disconnected
,09-13 08:50:22.887  1363  1363 D MapProfile: Bluetooth service disconnected
09-13 08:50:22.887  4025  4025 D BluetoothMap: Proxy object disconnected
09-13 08:50:22.887  4025  4025 D MapProfile: Bluetooth service disconnected
09-13 08:50:22.887  4268  4268 V BluetoothAdapterState: isTurningOff()=true
09-13 08:50:22.887  4268  4268 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:22.888  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 08:50:22.888  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:22.889  4268  4290 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 08:50:22.889  4268  4290 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 08:50:22.889  4268  4268 V BluetoothAdapterState: isTurningOff()=true
,09-13 08:50:22.889  4268  4268 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:22.889  4268  4290 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 08:50:22.889  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:22.889  4268  4290 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 08:50:22.889  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:22.890  4268  4290 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 08:50:22.890  4268  4290 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 08:50:22.890  4268  4284 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 08:50:22.890  4268  4268 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 08:50:22.890  4268  4268 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 08:50:22.890  4268  4284 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 08:50:22.890  4268  4268 V BluetoothAdapterState: isTurningOff()=true
09-13 08:50:22.890  4268  4268 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:22.890  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:22.890  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:22.891  4268  4268 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 08:50:22.891  4268  4284 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-13 08:50:22.891  4268  4268 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 08:50:22.893  1363  1363 D BluetoothPbap: Proxy object disconnected
09-13 08:50:22.893  1363  1363 D PbapServerProfile: Bluetooth service disconnected
,09-13 08:50:22.893  4268  4268 V BluetoothAdapterState: isTurningOff()=true
09-13 08:50:22.893  4268  4268 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:22.893  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:22.893  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:22.894  4268  4268 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-13 08:50:22.893  4025  4025 D BluetoothPbap: Proxy object disconnected
09-13 08:50:22.894  4268  4268 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 08:50:22.894  4025  4025 D PbapServerProfile: Bluetooth service disconnected
,09-13 08:50:22.897  4268  4268 D BluetoothMapService: MAP Service closeService in
,09-13 08:50:22.897  4268  4268 V BluetoothAdapterState: isTurningOff()=true
09-13 08:50:22.897  4268  4268 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:22.897  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 08:50:22.897  4268  4268 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:22.897  4268  4280 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 08:50:22.897  4268  4280 D BluetoothAdapterProperties: Setting state to 15
09-13 08:50:22.898  4268  4280 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-13 08:50:22.898  4268  4280 I BluetoothAdapterState: Entering BleOnState
,09-13 08:50:22.898  4268  4268 D BluetoothMapService: cleanup()
09-13 08:50:22.898  1363  1372 D BluetoothMap: onBluetoothStateChange: up=false
09-13 08:50:22.898  4268  4268 D BluetoothMapService: MAP Service closeService in
09-13 08:50:22.899  1363  3938 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 08:50:22.900   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 08:50:22.900   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 08:50:22.900  1363  1375 D BluetoothPan: onBluetoothStateChange on: false
09-13 08:50:22.900  4025  4037 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 08:50:22.901   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 08:50:22.901  4025  4036 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 08:50:22.902  4025  4037 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 08:50:22.902  4025  4036 D BluetoothPan: onBluetoothStateChange on: false
,09-13 08:50:22.903  1363  1704 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 08:50:22.904  1363  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 08:50:22.904  4025  4037 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 08:50:22.905  1363  3938 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 08:50:22.905   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 08:50:22.905  4025  4036 D BluetoothMap: onBluetoothStateChange: up=false
09-13 08:50:22.906  1960  2102 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 08:50:22.906  4268  4280 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 08:50:22.906  4268  4280 D BluetoothAdapterProperties: Setting state to 16
,09-13 08:50:22.906  4268  4280 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-13 08:50:22.907  4268  4280 D BluetoothAdapterProperties: onBleDisable
,09-13 08:50:22.910  4268  4280 I BluetoothAdapterState: Entering PendingCommandState
,09-13 08:50:22.910  4268  4281 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 08:50:22.911  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:22.911  4268  4290 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 08:50:22.912  4268  4290 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 08:50:22.913  4268  4284 D BluetoothAdapterProperties: Scan Mode:20
,09-13 08:50:22.913  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:22.914  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:22.915  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 08:50:22.915  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:22.917  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:22.918  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:22.920  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 08:50:22.927  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,09-13 08:50:23.118  4268  4284 I bt_hci  : shut_down
,09-13 08:50:23.119  4268  4288 D bt_hwcfg: hw_epilog_process
,09-13 08:50:23.139  4268  4288 I bt_vendor: low_power_mode_cb
,09-13 08:50:23.146  4268  4288 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 08:50:23.146  4268  4288 I bt_vendor: epilog_cb
09-13 08:50:23.146  4268  4288 I bt_hci  : epilog_finished_callback
,09-13 08:50:23.151  4268  4284 I bt_hci_h4: hal_close
,09-13 08:50:23.152  4268  4284 I bt_userial_vendor: device fd = 51 close
,09-13 08:50:23.285  4268  4281 D bt_stack_manager: event_shut_down_stack finished.
,09-13 08:50:23.287  4268  4280 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 08:50:23.292  4268  4280 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 08:50:23.293  4268  4268 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 08:50:23.294  4268  4268 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 08:50:23.295  4268  4268 D BtGatt.GattService: stop()
,09-13 08:50:23.295  4268  4268 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 08:50:23.301  4268  4268 V BluetoothAdapterState: isTurningOff()=false
,09-13 08:50:23.301  4268  4268 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:23.302  4268  4268 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:23.302  4268  4268 V BluetoothAdapterState: isBleTurningOff()=true
09-13 08:50:23.303  4268  4280 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 08:50:23.304  4268  4280 D BluetoothAdapterProperties: Setting state to 10
09-13 08:50:23.304  4268  4280 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 08:50:23.305  4268  4280 I BluetoothAdapterState: Entering OffState
09-13 08:50:23.308   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 08:50:23.330  4268  4268 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 08:50:23.331  4268  4268 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 08:50:23.331  4268  4281 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 08:50:23.342  4268  4281 D bt_stack_manager: event_clean_up_stack finished.
,09-13 08:50:23.342  4268  4268 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 08:50:23.348  4268  4268 I art     : System.exit called, status: 0
,09-13 08:50:23.348  4268  4268 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 08:50:23.445   872  1952 I ActivityManager: Process com.android.bluetooth (pid 4268) has died
,09-13 08:50:27.829  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:50:27.829  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:50:27.834  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:50:27.834  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d37746 removed from the list
09-13 08:50:27.834  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:50:27.834  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:50:27.835  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:50:27.838  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 08:50:27.838  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a41e34 added. We now have 4 listener(s)
,09-13 08:50:27.838  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:50:27.840  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:50:27.840  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a41e34 removed from the list
09-13 08:50:27.841  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:50:27.841  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:50:27.841  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:50:27.843  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 08:50:27.844  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24ce45d added. We now have 4 listener(s)
09-13 08:50:27.844  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:50:28.303  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:50:28.318  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:50:28.323  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:50:28.404  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 08:50:28.404  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 08:50:28.405  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:50:28.406  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:50:28.470  3663  3663 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 08:50:28.472  3663  3663 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 08:50:28.474  3663  3663 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-13 08:50:32.857  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:32.908   872   889 I ActivityManager: Start proc 4327:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 08:50:33.037  4327  4327 D AdapterServiceConfig: Adding HeadsetService
,09-13 08:50:33.038  4327  4327 D AdapterServiceConfig: Adding A2dpService
09-13 08:50:33.039  4327  4327 D AdapterServiceConfig: Adding HidService
,09-13 08:50:33.040  4327  4327 D AdapterServiceConfig: Adding HealthService
09-13 08:50:33.040  4327  4327 D AdapterServiceConfig: Adding PanService
09-13 08:50:33.041  4327  4327 D AdapterServiceConfig: Adding GattService
,09-13 08:50:33.042  4327  4327 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 08:50:33.061   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d193262:true
,09-13 08:50:33.062  4327  4327 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 08:50:33.066  4327  4327 I bt_bluedroid: init
,09-13 08:50:33.068  4327  4339 I BluetoothAdapterState: Entering OffState
,09-13 08:50:33.075  4327  4340 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 08:50:33.075  4327  4340 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 08:50:33.076  4327  4340 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 08:50:33.076  4327  4340 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 08:50:33.079  4327  4327 I bt_bluedroid: get_profile_interface socket
,09-13 08:50:33.082  4327  4327 I bt_bluedroid: get_profile_interface sdp
,09-13 08:50:33.082  4327  4343 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 08:50:33.089  4327  4343 D BluetoothAdapterProperties: Name is: Nexus 6
09-13 08:50:33.091  4327  4338 I bt_bluedroid: config_hci_snoop_log
,09-13 08:50:33.094   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 08:50:33.106  4327  4339 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 08:50:33.106  4327  4339 D BluetoothAdapterProperties: Setting state to 14
,09-13 08:50:33.107  4327  4339 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-13 08:50:33.112  4327  4339 D BluetoothBondStateMachine: make
,09-13 08:50:33.119  4327  4344 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 08:50:33.130  4327  4339 I BluetoothAdapterState: Entering PendingCommandState
,09-13 08:50:33.130  4327  4327 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 08:50:33.139  4327  4327 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:50:33.141  4327  4327 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 08:50:33.142  4327  4327 D BtGatt.GattService: Received start request. Starting profile...
09-13 08:50:33.142  4327  4327 D BtGatt.GattService: start()
,09-13 08:50:33.143  4327  4327 I bt_bluedroid: get_profile_interface gatt
,09-13 08:50:33.145  4327  4327 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
09-13 08:50:33.145  4327  4327 D BtGatt.AdvertiseManager: advertise manager created
,09-13 08:50:33.159  4327  4327 V BluetoothAdapterState: isTurningOff()=false
,09-13 08:50:33.160  4327  4327 V BluetoothAdapterState: isTurningOn()=false
09-13 08:50:33.160  4327  4327 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 08:50:33.160  4327  4327 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:33.161  4327  4339 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 08:50:33.162  4327  4339 I bt_bluedroid: enable
09-13 08:50:33.163  4327  4340 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 08:50:33.164  4327  4340 I bt_hci  : start_up
,09-13 08:50:33.189  4327  4340 I bt_vendor: alloc value 0xb3a7f189
09-13 08:50:33.189  4327  4340 I bt_vendor: init
,09-13 08:50:33.189  4327  4340 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 08:50:33.190  4327  4340 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 08:50:33.296  4327  4340 D bt_hci  : start_up starting async portion
,09-13 08:50:33.297  4327  4347 I bt_hci  : event_finish_startup
,09-13 08:50:33.297  4327  4347 I bt_hci_h4: hal_open
09-13 08:50:33.297  4327  4347 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 08:50:33.307  4327  4347 I bt_userial_vendor: device fd = 51 open
,09-13 08:50:33.339  4327  4347 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 08:50:33.371  4327  4347 D bt_hwcfg: Chipset BCM4354A2
,09-13 08:50:33.371  4327  4347 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 08:50:33.372  4327  4347 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 08:50:34.016  4327  4347 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 08:50:34.018  4327  4347 D bt_hwcfg: Settlement delay -- 100 ms
09-13 08:50:34.018  4327  4347 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 08:50:34.134  4327  4347 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 08:50:34.136  4327  4347 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 08:50:34.165  4327  4347 I bt_hwcfg: vendor lib fwcfg completed
,09-13 08:50:34.166  4327  4347 I bt_vendor: firmware callback
09-13 08:50:34.166  4327  4347 I bt_hci  : firmware_config_callback
,09-13 08:50:34.177  4327  4349 I bt_btu  : btu_task pending for preload complete event
,09-13 08:50:34.177  4327  4349 I bt_btu_task: Bluetooth chip preload is complete
,09-13 08:50:34.177  4327  4349 I bt_btu  : btu_task received preload complete event
,09-13 08:50:34.187  4327  4349 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 08:50:34.188  4327  4349 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 08:50:34.188  4327  4349 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 08:50:34.188  4327  4349 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 08:50:34.189  4327  4349 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 08:50:34.189  4327  4349 I         : BTE_InitTraceLevels -- TRC_A2D
,09-13 08:50:34.189  4327  4349 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 08:50:34.189  4327  4349 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 08:50:34.190  4327  4349 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 08:50:34.190  4327  4349 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 08:50:34.190  4327  4349 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 08:50:34.190  4327  4349 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 08:50:34.191  4327  4349 I         : BTE_InitTraceLevels -- TRC_SMP
,09-13 08:50:34.191  4327  4349 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 08:50:34.191  4327  4349 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 08:50:34.326  4327  4349 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fcd9d
,09-13 08:50:34.327  4327  4349 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fcd9d 
,09-13 08:50:34.338  4327  4343 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 08:50:34.340  4327  4343 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 08:50:34.341  4327  4343 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 08:50:34.344  4327  4343 D BluetoothAdapterProperties: Name is: Nexus 6
09-13 08:50:34.347  4327  4343 D BluetoothAdapterProperties: Scan Mode:20
,09-13 08:50:34.347  4327  4343 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 08:50:34.348  4327  4343 D bt_hci  : do_postload posting postload work item
09-13 08:50:34.348  4327  4347 I bt_hci  : event_postload
,09-13 08:50:34.348  4327  4347 I bt_vendor: sco_config_cb
09-13 08:50:34.348  4327  4347 I bt_hci  : sco_config_callback postload finished.
,09-13 08:50:34.352  4327  4343 D bt_bte_conf: Device ID record 1 : primary
,09-13 08:50:34.353  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:34.353  4327  4343 D bt_bte_conf:   vendorId            = 000f
09-13 08:50:34.353  4327  4343 D bt_bte_conf:   vendorIdSource      = 0001
,09-13 08:50:34.353  4327  4343 D bt_bte_conf:   product             = 1200
09-13 08:50:34.354  4327  4343 D bt_bte_conf:   version             = 1436
09-13 08:50:34.354  4327  4343 D bt_bte_conf:   clientExecutableURL = 
09-13 08:50:34.354  4327  4343 D bt_bte_conf:   serviceDescription  = 
09-13 08:50:34.354  4327  4343 D bt_bte_conf:   documentationURL    = 
,09-13 08:50:34.355  4327  4343 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 08:50:34.355  4327  4340 D bt_stack_manager: event_start_up_stack finished
09-13 08:50:34.357  4327  4347 I bt_vendor: low_power_mode_cb
09-13 08:50:34.359  4327  4339 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 08:50:34.359  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:34.359  4327  4339 D BluetoothAdapterProperties: Setting state to 15
09-13 08:50:34.360  4327  4339 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 08:50:34.361  4327  4339 I BluetoothAdapterState: Entering BleOnState
,09-13 08:50:34.369  4327  4339 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 08:50:34.369  4327  4339 D BluetoothAdapterProperties: Setting state to 11
09-13 08:50:34.369  4327  4339 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 08:50:34.374  4327  4327 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
09-13 08:50:34.375  4327  4327 D HeadsetService: Received start request. Starting profile...
09-13 08:50:34.378  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:34.379  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:50:34.379  4327  4327 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 08:50:34.380  4327  4327 D HeadsetStateMachine: make
,09-13 08:50:34.390  4327  4327 D HeadsetStateMachine: max_hf_connections = 1
09-13 08:50:34.390  4327  4327 I bt_bluedroid: get_profile_interface handsfree
09-13 08:50:34.390  4327  4343 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 08:50:34.390  4327  4343 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 08:50:34.393  4327  4339 I BluetoothAdapterState: Entering PendingCommandState
09-13 08:50:34.395  4327  4327 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
09-13 08:50:34.395  4327  4327 D A2dpService: Received start request. Starting profile...
09-13 08:50:34.396  4327  4327 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 08:50:34.396  4327  4327 I bt_bluedroid: get_profile_interface avrcp
,09-13 08:50:34.401  4327  4327 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 08:50:34.401  4327  4327 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 08:50:34.401  4327  4327 D A2dpStateMachine: make
,09-13 08:50:34.403  4327  4327 I bt_bluedroid: get_profile_interface a2dp
,09-13 08:50:34.403  4327  4343 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 08:50:34.405  4327  4359 D A2dpStateMachine: Enter Disconnected: -2
,09-13 08:50:34.406  4327  4327 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 08:50:34.407  4327  4327 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:50:34.408  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 08:50:34.408  4327  4327 D HidService: Received start request. Starting profile...
09-13 08:50:34.408  4327  4327 I bt_bluedroid: get_profile_interface hidhost
09-13 08:50:34.408  4327  4327 D HidService: setHidService(): set to: null
09-13 08:50:34.408  4327  4343 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39de3e5
09-13 08:50:34.408  4327  4343 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 08:50:34.409  4327  4327 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 08:50:34.410  4327  4327 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
09-13 08:50:34.411  4327  4327 D HealthService: Received start request. Starting profile...
,09-13 08:50:34.413  4327  4327 I bt_bluedroid: get_profile_interface health
09-13 08:50:34.413  4327  4327 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 08:50:34.414  4327  4327 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
09-13 08:50:34.415  4327  4327 D PanService: Received start request. Starting profile...
09-13 08:50:34.415  4327  4327 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 08:50:34.415  4327  4327 I bt_bluedroid: get_profile_interface pan
09-13 08:50:34.415  4327  4343 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 08:50:34.418  4327  4327 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:50:34.419  4327  4327 D BluetoothMapService: Received start request. Starting profile...
,09-13 08:50:34.419  4327  4327 D BluetoothMapService: start()
09-13 08:50:34.421  4327  4327 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 08:50:34.422  4327  4327 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 08:50:34.422  4327  4327 D BluetoothMapAppObserver: createReceiver()
,09-13 08:50:34.423  4327  4327 D BluetoothMapAppObserver: initObservers()
,09-13 08:50:34.424  4327  4327 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 08:50:34.430  4327  4327 V BluetoothAdapterState: isTurningOff()=false
,09-13 08:50:34.430  4327  4327 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:34.430  4327  4327 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:34.430  4327  4327 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:34.432  4327  4327 V BluetoothAdapterState: isTurningOff()=false
,09-13 08:50:34.432  4327  4327 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:34.432  4327  4327 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 08:50:34.432  4327  4357 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 08:50:34.432  4327  4327 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:34.432  4327  4327 V BluetoothAdapterState: isTurningOff()=false
09-13 08:50:34.432  4327  4327 V BluetoothAdapterState: isTurningOn()=true
,09-13 08:50:34.432  4327  4327 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:34.433  4327  4327 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:34.433  4327  4327 V BluetoothAdapterState: isTurningOff()=false
09-13 08:50:34.434  4327  4327 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:34.434  4327  4327 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:34.434  4327  4327 V BluetoothAdapterState: isBleTurningOff()=false
09-13 08:50:34.434  4327  4327 V BluetoothAdapterState: isTurningOff()=false
09-13 08:50:34.434  4327  4327 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:34.434  4327  4327 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:34.435  4327  4327 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:34.435  4327  4327 V BluetoothAdapterState: isTurningOff()=false
09-13 08:50:34.435  4327  4327 V BluetoothAdapterState: isTurningOn()=true
09-13 08:50:34.435  4327  4327 V BluetoothAdapterState: isBleTurningOn()=false
09-13 08:50:34.435  4327  4327 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 08:50:34.436  4327  4339 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 08:50:34.436  4327  4339 D BluetoothAdapterProperties: ScanMode =  20
09-13 08:50:34.436  4327  4339 D BluetoothAdapterProperties: State =  11
,09-13 08:50:34.440  4327  4343 D BluetoothAdapterProperties: Scan Mode:21
,09-13 08:50:34.440  4327  4343 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 08:50:34.441  4327  4339 D BluetoothAdapterProperties: Setting state to 12
09-13 08:50:34.441  4327  4339 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 08:50:34.441  1363  1704 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 08:50:34.442  4327  4339 I BluetoothAdapterState: Entering OnState
,09-13 08:50:34.444  1363  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 08:50:34.445  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:34.445  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:34.445  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:34.445  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:34.445  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:34.445  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:34.445  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:34.445  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:34.446  1363  1363 D BluetoothMap: Proxy object connected
09-13 08:50:34.446  1363  1363 D MapProfile: Bluetooth service connected
09-13 08:50:34.446  1363  1363 D BluetoothMap: getConnectedDevices()
,09-13 08:50:34.447  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 08:50:34.448   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 08:50:34.449   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 08:50:34.450  1363  1363 D BluetoothInputDevice: Proxy object connected
09-13 08:50:34.450  1363  1704 D BluetoothPan: onBluetoothStateChange on: true
09-13 08:50:34.450  1363  1363 D HidProfile: Bluetooth service connected
09-13 08:50:34.450  4327  4327 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 08:50:34.451  4327  4327 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 08:50:34.454  4327  4327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 08:50:34.454  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:34.454  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:34.454  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:34.454  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:34.454  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:34.454  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:34.454  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:34.454  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:34.455  4025  4037 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 08:50:34.456  4327  4327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 08:50:34.456   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 08:50:34.456  4025  4320 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 08:50:34.458  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:34.458  4327  4327 D ObexServerSockets: Succeed to create listening sockets 
09-13 08:50:34.458  4327  4327 D ObexServerSockets0: startAccept()
09-13 08:50:34.459  4327  4327 D ObexServerSockets0: prepareForNewConnect()
09-13 08:50:34.459  4025  4036 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 08:50:34.460  4025  4037 D BluetoothPan: onBluetoothStateChange on: true
09-13 08:50:34.461  4327  4327 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 08:50:34.461  4327  4327 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-13 08:50:34.462   872   872 D BluetoothA2dp: Proxy object connected
,09-13 08:50:34.463  4025  4025 D BluetoothA2dp: Proxy object connected
09-13 08:50:34.463  1363  3938 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 08:50:34.463  4327  4365 D ObexServerSockets0: Accepting socket connection...
09-13 08:50:34.463  4327  4364 D ObexServerSockets0: Accepting socket connection...
09-13 08:50:34.464  1363  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 08:50:34.465  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 08:50:34.465  1363  1363 D PanProfile: Bluetooth service connected
09-13 08:50:34.465  4025  4025 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 08:50:34.465  4025  4025 D PanProfile: Bluetooth service connected
09-13 08:50:34.466  1363  1363 D BluetoothA2dp: Proxy object connected
,09-13 08:50:34.467  4025  4320 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 08:50:34.469  1363  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 08:50:34.470   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 08:50:34.470  4025  4036 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 08:50:34.472  4025  4025 D BluetoothInputDevice: Proxy object connected
,09-13 08:50:34.472  1960  2102 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 08:50:34.472  4025  4025 D HidProfile: Bluetooth service connected
,09-13 08:50:34.473   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-13 08:50:34.474  4327  4327 D BluetoothMapService: onReceive
,09-13 08:50:34.474  4327  4327 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 08:50:34.474  4327  4327 D BluetoothMapService: STATE_ON
09-13 08:50:34.475  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:34.475  4025  4025 D BluetoothMap: Proxy object connected
,09-13 08:50:34.476  4025  4025 D MapProfile: Bluetooth service connected
,09-13 08:50:34.476  4025  4025 D BluetoothMap: getConnectedDevices()
,09-13 08:50:34.477  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:34.483  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 08:50:34.489  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,09-13 08:50:34.490  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 08:50:34.501  1363  1363 D BluetoothPbap: Proxy object connected
09-13 08:50:34.501  4025  4025 D BluetoothPbap: Proxy object connected
,09-13 08:50:34.501  4025  4025 D PbapServerProfile: Bluetooth service connected
09-13 08:50:34.501  1363  1363 D PbapServerProfile: Bluetooth service connected
09-13 08:50:34.502  4327  4327 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 08:50:34.502  4327  4327 D ObexServerSockets0: prepareForNewConnect()
,09-13 08:50:34.510  4327  4371 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 08:50:34.533  4327  4375 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 08:50:34.534  4327  4375 I BtOppRfcommListener: Accept thread started.
,09-13 08:50:34.551   872   872 D BluetoothHeadset: Proxy object connected
,09-13 08:50:34.551  1363  1372 D BluetoothHeadset: Proxy object connected
09-13 08:50:34.552  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-13 08:50:34.556  4025  4037 D BluetoothHeadset: Proxy object connected
,09-13 08:50:34.556  1960  2099 D BluetoothHeadset: Proxy object connected
09-13 08:50:34.556  4025  4036 D BluetoothHeadset: Proxy object connected
,09-13 08:50:34.556   872   872 D BluetoothHeadset: Proxy object connected
09-13 08:50:34.556   872   889 D BluetoothHeadset: Proxy object connected
09-13 08:50:34.556   872   872 D BluetoothHeadset: Proxy object connected
,09-13 08:50:34.557  4025  4025 D HeadsetProfile: Bluetooth service connected
09-13 08:50:34.558  4025  4025 D HeadsetProfile: Bluetooth service connected
,09-13 08:50:34.570  1363  1704 D BluetoothHeadset: Proxy object connected
09-13 08:50:34.570  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-13 08:50:34.570   872   889 D BluetoothHeadset: Proxy object connected
,09-13 08:50:34.573  1960  1973 D BluetoothHeadset: Proxy object connected
,09-13 08:50:37.877  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:37.877  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:37.877  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:37.877  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 08:50:37.877  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:37.877  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:37.877  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:37.877  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 08:50:37.886  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:37.887  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:50:37.888  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24ce45d removed from the list
09-13 08:50:37.888  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:50:37.888  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:50:37.889  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:50:37.891  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 08:50:37.892  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@53fc1d2 added. We now have 4 listener(s)
09-13 08:50:37.892  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:50:37.896   872  1376 D WifiService: setWifiEnabled: false pid=3939, uid=10000
,09-13 08:50:37.896   872  1376 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 08:50:42.911  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:50:42.912   872  2001 D WifiService: setWifiEnabled: true pid=3939, uid=10000
09-13 08:50:42.912   872  2001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 08:50:42.925   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-13 08:50:42.944  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:42.944  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:42.944  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:42.944  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:42.944  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:42.944  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:42.944  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:42.944  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 08:50:42.950  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:42.957   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-13 08:50:42.958   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-13 08:50:42.958  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:42.958  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:42.958  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:42.958  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:42.958  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:42.958  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 08:50:42.958  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 08:50:42.958  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 08:50:42.959   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 08:50:42.960   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 08:50:42.960   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 08:50:42.960   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 08:50:42.960   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-13 08:50:42.962  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 08:50:42.974   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 08:50:42.974   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 08:50:42.976   372   870 D CommandListener: Setting iface cfg
,09-13 08:50:43.024   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-13 08:50:43.025   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 08:50:43.028   872  1303 E native  : do suspend true
,09-13 08:50:43.039   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
09-13 08:50:43.040   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 08:50:43.054   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 08:50:44.359   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 08:50:44.504   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.56 rxSuccessRate=10.12 delta 1000 -> 994
,09-13 08:50:44.506   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 08:50:44.506   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 08:50:44.526   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 08:50:44.602   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 08:50:44.604  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 08:50:45.113  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 08:50:45.187  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 08:50:45.188  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 08:50:45.199   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 08:50:45.215   872  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 08:50:45.216   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 08:50:45.216   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 08:50:45.245   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 08:50:45.260   372   870 D CommandListener: Setting iface cfg
,09-13 08:50:45.261   872  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,09-13 08:50:45.281   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 08:50:45.324   872  4384 D DhcpClient: Receive thread started
,09-13 08:50:45.425   872  1303 E native  : do suspend false
,09-13 08:50:45.454   872  2241 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 08:50:45.467   872  4384 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-13 08:50:45.468   872  2241 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-13 08:50:45.472   872  2241 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 08:50:45.485   872  4384 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 08:50:45.486   872  2241 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 08:50:45.492   372   870 D CommandListener: Setting iface cfg
,09-13 08:50:45.504   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-13 08:50:45.506   872  2241 D DhcpClient: Scheduling renewal in 86399s
,09-13 08:50:45.510   872  1303 E native  : do suspend true
,09-13 08:50:45.537   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 08:50:45.540   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 08:50:45.541   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 08:50:45.542   872  1305 D ConnectivityService: Adding iface wlan0 to network 102
,09-13 08:50:45.549   872  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 08:50:45.610   872  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 08:50:45.611   872  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 08:50:45.618   872  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 08:50:45.625   872  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 08:50:45.627   872  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 08:50:45.649   872  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 08:50:45.655   872  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-13 08:50:45.655   872  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-13 08:50:45.655   872  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-13 08:50:45.655   872  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 08:50:45.655   872  1305 D ConnectivityService:    accepting network in place of null
09-13 08:50:45.656   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 08:50:45.657   872  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 08:50:45.681   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209105, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 08:50:45.685   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 08:50:45.744   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 08:50:45.749   872  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-13 08:50:45.749   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 08:50:45.751   872  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 08:50:45.752   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-13 08:50:45.769  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:45.769  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:45.769  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:45.769  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:45.769  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:45.769  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:45.769  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:50:45.769  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:50:45.772  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:50:45.777  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:45.777  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:45.777  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:45.777  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:45.777  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:45.777  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:45.777  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:50:45.777  3939  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:50:45.779  3939  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:50:45.784  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 08:50:45.788  1740  1740 D SystemUpdateService: onCreate
,09-13 08:50:45.792  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 08:50:45.812  1740  4393 I SystemUpdateService: active receiver: enabled
,09-13 08:50:45.816   872  4382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-13 08:50:45.818  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 08:50:45.823  1740  2546 I iu.UploadsManager: num queued entries: 0
,09-13 08:50:45.823  1740  2546 I iu.UploadsManager: num updated entries: 0
09-13 08:50:45.824  1740  2546 I iu.SyncManager: NEXT; no task
,09-13 08:50:45.828  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 08:50:45.829  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 08:50:45.830  4082  4082 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 08:50:45.835  1740  4396 I MDM     : [189] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 08:50:45.835  1740  4396 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 08:50:45.836  4082  4082 D SprintDMHelper: simOperator: 
,09-13 08:50:45.836  4082  4082 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 08:50:45.837  1740  4396 V GoogleAuthProtoRequest: [189] a.<init>: mAccountName set to: thalitester@gmail.com
09-13 08:50:45.838  1740  4393 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 08:50:45.850  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:50:45.860  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:50:45.869  1740  4393 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 08:50:45.869  1740  4393 I SystemUpdateService: now status is 0 (complete)
09-13 08:50:45.869  1740  4393 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-13 08:50:45.869  1740  4393 I SystemUpdateService: file has been verified
09-13 08:50:45.869  1740  4393 I SystemUpdateService: OTA package size = 12249756
,09-13 08:50:45.873   872  4382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 06:50:45 GMT], X-Android-Received-Millis=[1473749445872], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473749445849]}
,09-13 08:50:45.874   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 08:50:45.875   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-13 08:50:45.875   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 08:50:45.882   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 08:50:45.901  1740  4393 I SystemUpdateService: showing system update notification
,09-13 08:50:45.916  1740  1740 D SystemUpdateService: onDestroy
,09-13 08:50:45.920  1500  3132 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 08:50:45.920  1500  3132 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-13 08:50:45.920  1500  3132 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:50:45.920  1500  3132 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:50:45.937  1740  4396 E MDM     : [189] SitrepService.a: Error sending sitrep.
,09-13 08:50:45.988  2411  4398 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 08:50:46.490  1868  1912 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-13 08:50:46.490  1868  1912 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-13 08:50:46.514  1500  1500 I ConfigService: onCreate
,09-13 08:50:46.750   872  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 08:50:47.939  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 08:50:47.939  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:50:47.939  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:50:47.939  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:50:47.939  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:50:47.939  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:50:47.939  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:50:47.939  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:50:47.946  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:50:47.947  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:50:47.948  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@53fc1d2 removed from the list
09-13 08:50:47.948  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:50:47.948  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:50:47.948  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:50:47.961  3939  4407 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 08:50:47.961  3939  4407 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 08:50:50.968  3939  4408 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-13 08:50:50.969  3939  4407 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 08:50:50.969  3939  4408 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 08:50:50.970  3939  4407 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 08:50:50.971  3939  4408 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 08:50:50.971  3939  4407 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 08:50:50.972  3939  4407 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 08:50:50.972  3939  4408 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 08:50:50.976  3939  4407 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 08:50:50.978  3939  4408 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 08:50:50.979  3939  4410 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: OutgoingSocketThread/Sender)
,09-13 08:50:50.985  3939  4412 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: OutgoingSocketThread/Receiver)
,09-13 08:50:50.987  3939  4412 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 454, thread name: OutgoingSocketThread/Receiver)
,09-13 08:50:50.988  3939  4412 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 08:50:50.988  3939  4413 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: IncomingSocketThread/Receiver)
09-13 08:50:50.989  3939  4412 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 08:50:50.988  3939  4411 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 453, name: IncomingSocketThread/Sender)
09-13 08:50:50.990  3939  4413 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 455, thread name: IncomingSocketThread/Receiver)
,09-13 08:50:50.991  3939  4413 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 08:50:50.991  3939  4413 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 08:50:51.585  1500  1500 I ConfigService: onDestroy
,09-13 08:50:53.663   872  1305 D ConnectivityService: handlePromptUnvalidated 102
,09-13 08:50:53.968  3939  3989 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 08:50:53.970  3939  3989 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 08:50:53.977  3939  3989 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@140bce Bundle[{}]
,09-13 08:50:53.978  3939  3989 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 08:50:53.978  3939  3989 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 08:50:53.979  3939  3989 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 08:50:53.979  3939  3989 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 08:50:53.979  3939  3989 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 08:50:53.980  3939  3989 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 08:50:53.984  3939  3989 I System.out: Running OutgoingSocketThread
,09-13 08:50:53.988  3939  4415 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-13 08:50:53.989  3939  4415 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 08:50:56.996  3939  4416 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 08:50:56.997  3939  4416 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 08:50:56.997  3939  4416 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 08:50:56.998  3939  4415 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 08:50:56.998  3939  4415 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 08:50:56.999  3939  4416 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 08:50:56.999  3939  4415 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 08:50:57.001  3939  4418 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: IncomingSocketThread/Sender)
09-13 08:50:57.003  3939  4416 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 08:50:57.007  3939  4415 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 08:50:57.009  3939  4419 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: IncomingSocketThread/Receiver)
,09-13 08:50:57.010  3939  4419 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 465, thread name: IncomingSocketThread/Receiver)
09-13 08:50:57.011  3939  4419 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 08:50:57.011  3939  4419 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 465, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 08:50:57.012  3939  4415 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 08:50:57.013  3939  4420 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: OutgoingSocketThread/Sender)
09-13 08:50:57.015  3939  4421 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: OutgoingSocketThread/Receiver)
,09-13 08:50:57.017  3939  4421 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 467, thread name: OutgoingSocketThread/Receiver)
09-13 08:50:57.017  3939  4421 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 08:50:57.018  3939  4421 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 08:51:00.000  3939  3989 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 476)
,09-13 08:51:00.002  3939  3989 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 08:51:00.003  3939  3989 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 477)
,09-13 08:51:00.008  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 08:51:00.008  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39fb2a3 added. We now have 3 listener(s)
,09-13 08:51:00.010  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 08:51:00.010  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 08:51:00.010  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 08:51:00.010  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 08:51:00.011  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ee9a0 added. We now have 4 listener(s)
09-13 08:51:00.011  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 08:51:00.011  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 08:51:00.019  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:51:00.033  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:51:00.033  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:51:00.033  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:51:00.033  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:51:00.033  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:51:00.033  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:51:00.033  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:51:00.033  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:51:00.040  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:51:00.041  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 08:51:00.042  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 08:51:00.043  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:51:00.043  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:51:00.043  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:51:00.044  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:00.044  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 08:51:00.044  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 08:51:00.044  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39fb2a3 removed from the list
09-13 08:51:00.045  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:51:00.045  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ee9a0 removed from the list
,09-13 08:51:00.047  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:51:00.048  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:51:00.048  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:00.050  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:00.051  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:51:00.054  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:51:00.054  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:51:00.054  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:51:00.055  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ee9a0 not in the list
09-13 08:51:00.055  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:00.055  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:00.058  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 08:51:00.058  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:51:00.059  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:51:00.059  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ee9a0 not in the list
09-13 08:51:00.059  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:51:00.059  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:51:00.059  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:00.060  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:00.060  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39fb2a3 not in the list
09-13 08:51:00.063  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 08:51:00.063  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b4291e added. We now have 3 listener(s)
,09-13 08:51:00.068  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 08:51:00.068  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 08:51:00.068  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 08:51:00.069  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 08:51:00.069  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@770d5ff added. We now have 4 listener(s)
09-13 08:51:00.069  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 08:51:00.070  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 08:51:00.076  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:51:00.092  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:51:00.092  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:51:00.092  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:51:00.092  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:51:00.092  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:51:00.092  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:51:00.092  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:51:00.092  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:51:00.098  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:51:00.099  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 08:51:00.099  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 08:51:00.099  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 08:51:00.100  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 08:51:00.100  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 08:51:00.100  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 08:51:00.107  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:51:00.110  3939  3989 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 08:51:00.111  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 08:51:00.115  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:51:00.122  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 08:51:00.124  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 08:51:00.124  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 08:51:00.135  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 08:51:00.135  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 08:51:00.135  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 08:51:00.137  3939  3989 D BluetoothAdapter: STATE_ON
,09-13 08:51:00.146  4327  4355 D BtGatt.GattService: registerClient() - UUID=7deded70-d807-40bb-b484-3a645fb4a552
,09-13 08:51:00.147  4327  4343 D BtGatt.GattService: onClientRegistered() - UUID=7deded70-d807-40bb-b484-3a645fb4a552, clientIf=5
,09-13 08:51:00.149  3939  3951 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 08:51:00.151  4327  4366 D BtGatt.GattService: start scan with filters
,09-13 08:51:00.162  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 08:51:00.163  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 08:51:00.163  4327  4346 D BtGatt.ScanManager: handling starting scan
09-13 08:51:00.163  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 08:51:00.163  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 08:51:00.169  4327  4346 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ddd982
,09-13 08:51:00.171  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 08:51:00.172  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 08:51:00.173  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 08:51:00.178  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 08:51:00.187  4327  4343 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 08:51:00.187  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:51:00.188  3939  3989 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 08:51:00.189  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:51:00.189  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 08:51:00.189  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:51:00.189  4327  4346 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,09-13 08:51:00.189  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 08:51:00.190  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 08:51:00.190  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 08:51:00.190  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 08:51:00.190  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 08:51:00.191  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 08:51:00.191  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 08:51:00.193  3939  3989 D BluetoothAdapter: STATE_ON
09-13 08:51:00.195  4327  4367 D BtGatt.GattService: stopScan() - queue size =1
09-13 08:51:00.197  4327  4338 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 08:51:00.198  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 08:51:00.199  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 08:51:00.199  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 08:51:00.199  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 08:51:00.200  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 08:51:00.202  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:51:00.202  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 08:51:00.202  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 08:51:00.203  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 08:51:00.204  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 08:51:00.206  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:51:00.206  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:51:00.206  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:51:00.208  4327  4343 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 08:51:00.209  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:51:00.210  4327  4346 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 08:51:00.210  4327  4346 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 08:51:00.234  4327  4343 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 08:51:00.235  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:51:00.245  4327  4343 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 08:51:00.245  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:51:00.263  4327  4343 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 08:51:00.263  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:51:00.264  4327  4346 D BtGatt.ScanManager: stopping BLe Batch
,09-13 08:51:00.277  4327  4343 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 08:51:00.277  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:51:00.278  4327  4346 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:51:00.293  4327  4343 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 08:51:00.294  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:51:00.707  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 08:51:00.708  3939  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:51:00.708  3939  3939 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 08:51:03.207  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 08:51:03.208  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:51:03.209  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:51:03.210  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:51:03.210  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:51:03.210  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 08:51:03.211  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 08:51:03.211  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b4291e removed from the list
09-13 08:51:03.211  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:51:03.212  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@770d5ff removed from the list
09-13 08:51:03.212  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:51:03.212  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:03.214  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:51:03.215  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:03.218  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:51:03.219  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:51:03.219  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:51:03.219  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@770d5ff not in the list
,09-13 08:51:03.220  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:03.220  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:51:03.223  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:51:03.223  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:51:03.224  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:51:03.224  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@770d5ff not in the list
09-13 08:51:03.224  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:51:03.224  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:03.225  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:03.225  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b4291e not in the list
09-13 08:51:03.227  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 08:51:03.228  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1c4cb8 added. We now have 3 listener(s)
,09-13 08:51:03.234  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 08:51:03.234  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 08:51:03.235  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 08:51:03.235  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 08:51:03.236  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbcea91 added. We now have 4 listener(s)
09-13 08:51:03.236  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 08:51:03.237  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 08:51:03.242  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:51:03.252  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:51:03.252  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:51:03.252  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:51:03.252  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:51:03.252  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:51:03.252  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:51:03.252  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:51:03.252  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:51:03.257  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:51:03.257  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 08:51:03.258  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 08:51:03.259  3939  3989 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-13 08:51:03.259  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 08:51:03.259  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 08:51:03.259  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 08:51:03.259  3939  3989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
09-13 08:51:03.259  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 08:51:03.263  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 08:51:03.263  3939  3989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 08:51:03.263  3939  3989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 08:51:03.264  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 08:51:03.264  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 08:51:03.264  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 08:51:03.264  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 08:51:03.267  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:51:03.275  3939  3989 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 08:51:03.275  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 08:51:03.276  3939  4422 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 08:51:03.278  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:51:03.279  3939  3939 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 08:51:03.282  3939  4422 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 08:51:03.289  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 08:51:03.291  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 08:51:03.291  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 08:51:03.297  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 08:51:03.298  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 08:51:03.299  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-13 08:51:03.302  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 08:51:03.302  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 08:51:03.302  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 08:51:03.304  3939  3989 D BluetoothAdapter: STATE_ON
,09-13 08:51:03.310  4327  4367 D BtGatt.GattService: registerClient() - UUID=c87a468e-f0a6-435a-951a-9b3a44d662d9
,09-13 08:51:03.311  4327  4343 D BtGatt.GattService: onClientRegistered() - UUID=c87a468e-f0a6-435a-951a-9b3a44d662d9, clientIf=5
09-13 08:51:03.311  3939  3950 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 08:51:03.318  4327  4345 D BtGatt.AdvertiseManager: message : 0
,09-13 08:51:03.324  4327  4345 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 08:51:03.348  4327  4343 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 08:51:03.366  4327  4343 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 08:51:03.369  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 08:51:03.370  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 08:51:03.377  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 08:51:03.380  3939  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 08:51:03.381  3939  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 08:51:03.381  3939  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 08:51:03.381  3939  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 08:51:03.382  3939  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 08:51:03.382  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 08:51:03.387  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 08:51:03.393  3939  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 08:51:03.394  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 08:51:03.895  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 08:51:03.896  3939  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 08:51:03.896  3939  3939 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 08:51:06.388  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 08:51:06.389  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 08:51:06.389  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 08:51:06.390  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 08:51:06.390  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 08:51:06.390  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 08:51:06.392  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 08:51:06.392  3939  4422 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 08:51:06.392  3939  4422 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 08:51:06.392  3939  3989 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 08:51:06.393  3939  4422 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 08:51:06.393  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 08:51:06.393  3939  3939 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 08:51:06.393  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 08:51:06.393  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 08:51:06.394  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 08:51:06.394  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 08:51:06.396  3939  3989 D BluetoothAdapter: STATE_ON
09-13 08:51:06.397  3939  3989 D BluetoothLeScanner: could not find callback wrapper
09-13 08:51:06.397  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 08:51:06.398  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 08:51:06.401  4327  4345 D BtGatt.AdvertiseManager: message : 1
09-13 08:51:06.403  4327  4345 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 08:51:06.414  4327  4343 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 08:51:06.414  4327  4343 D BtGatt.GattService: Client app is not null!
,09-13 08:51:06.416  4327  4356 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 08:51:06.418  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 08:51:06.418  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 08:51:06.419  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 08:51:06.420  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 08:51:06.420  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 08:51:06.424  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 08:51:06.424  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 08:51:06.424  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 08:51:06.426  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 08:51:06.428  3939  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:51:06.429  3939  3939 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 08:51:06.429  3939  3939 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 08:51:06.430  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:51:06.430  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:51:06.430  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:51:06.431  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:51:06.431  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:51:06.431  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 08:51:06.431  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 08:51:06.432  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1c4cb8 removed from the list
09-13 08:51:06.432  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:51:06.432  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbcea91 removed from the list
09-13 08:51:06.433  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:51:06.433  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:06.434  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:06.434  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:51:06.436  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:51:06.436  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:51:06.437  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:51:06.437  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbcea91 not in the list
09-13 08:51:06.437  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:06.437  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:51:06.440  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 08:51:06.440  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:51:06.440  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:51:06.440  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbcea91 not in the list
09-13 08:51:06.440  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:51:06.441  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:51:06.441  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:06.441  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1c4cb8 not in the list
09-13 08:51:06.442  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 08:51:06.443  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd84382 added. We now have 3 listener(s)
,09-13 08:51:06.447  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 08:51:06.447  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 08:51:06.448  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 08:51:06.448  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 08:51:06.448  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8328a93 added. We now have 4 listener(s)
,09-13 08:51:06.449  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 08:51:06.449  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 08:51:06.454  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:51:06.462  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:51:06.462  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:51:06.462  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:51:06.462  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:51:06.462  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:51:06.462  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:51:06.462  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:51:06.462  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:51:06.466  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:51:06.467  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 08:51:06.467  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 08:51:06.467  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 08:51:06.468  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 08:51:06.468  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 08:51:06.468  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 08:51:06.473  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:51:06.475  3939  3989 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 08:51:06.476  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 08:51:06.479  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 08:51:06.485  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 08:51:06.487  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 08:51:06.487  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 08:51:06.495  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 08:51:06.496  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 08:51:06.496  3939  3989 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 08:51:06.498  3939  3989 D BluetoothAdapter: STATE_ON
,09-13 08:51:06.503  4327  4338 D BtGatt.GattService: registerClient() - UUID=5a032831-3997-4550-b817-f72ccb724705
,09-13 08:51:06.504  4327  4343 D BtGatt.GattService: onClientRegistered() - UUID=5a032831-3997-4550-b817-f72ccb724705, clientIf=5
,09-13 08:51:06.505  3939  3950 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 08:51:06.505  4327  4356 D BtGatt.GattService: start scan with filters
,09-13 08:51:06.512  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 08:51:06.512  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 08:51:06.512  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 08:51:06.512  4327  4346 D BtGatt.ScanManager: handling starting scan
,09-13 08:51:06.512  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 08:51:06.520  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 08:51:06.520  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 08:51:06.520  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 08:51:06.525  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 08:51:06.530  4327  4343 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 08:51:06.530  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:51:06.530  4327  4346 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,09-13 08:51:06.545  4327  4343 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 08:51:06.546  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:51:06.546  4327  4346 D BtGatt.ScanManager: Starting BLE batch scan
09-13 08:51:06.546  4327  4346 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 08:51:06.573  4327  4343 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 08:51:06.573  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:51:06.594  4327  4343 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 08:51:06.595  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 08:51:06.932  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 08:51:07.021  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 08:51:07.021  3939  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 08:51:07.022  3939  3939 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 08:51:08.100  4327  4327 D BtGatt.ScanManager: awakened up at time 231525
,09-13 08:51:08.103  4327  4346 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:51:08.135  4327  4343 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-13 08:51:08.136  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:51:08.136  4327  4343 D BtGatt.GattService: current time is 231561087257
,09-13 08:51:08.136  4327  4343 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -97, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -98, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 08:51:08.138  4327  4343 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 08:51:08.139  4327  4343 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 08:51:08.139  4327  4343 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 08:51:08.139  4327  4343 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 08:51:08.139  4327  4343 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 08:51:09.542  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 08:51:09.542  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 08:51:09.543  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 08:51:09.543  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:51:09.543  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 08:51:09.545  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 08:51:09.545  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 08:51:09.545  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 08:51:09.546  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 08:51:09.550  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 08:51:09.550  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 08:51:09.554  3939  3989 D BluetoothAdapter: STATE_ON
,09-13 08:51:09.556  4327  4355 D BtGatt.GattService: stopScan() - queue size =1
,09-13 08:51:09.559  4327  4367 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 08:51:09.560  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 08:51:09.560  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 08:51:09.560  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 08:51:09.561  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-13 08:51:09.561  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 08:51:09.565  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:51:09.565  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 08:51:09.565  3939  3989 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,09-13 08:51:09.567  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 08:51:09.567  4327  4327 D BtGatt.ScanManager: awakened up at time 232992
,09-13 08:51:09.571  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 08:51:09.574  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 08:51:09.574  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:51:09.574  3939  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 08:51:09.574  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:51:09.575  3939  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 08:51:09.575  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 08:51:09.575  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 08:51:09.575  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd84382 removed from the list
09-13 08:51:09.576  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:51:09.576  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8328a93 removed from the list
09-13 08:51:09.576  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
09-13 08:51:09.577  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:51:09.578  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:09.579  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:51:09.582  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:51:09.583  4327  4343 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 08:51:09.583  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 08:51:09.583  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:51:09.583  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 08:51:09.584  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8328a93 not in the list
09-13 08:51:09.584  4327  4346 D BtGatt.ScanManager: stopping BLe Batch
09-13 08:51:09.584  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:09.584  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:09.587  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:51:09.587  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:51:09.587  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-13 08:51:09.588  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8328a93 not in the list
09-13 08:51:09.588  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 08:51:09.588  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:51:09.588  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:09.589  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd84382 not in the list
09-13 08:51:09.590  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 08:51:09.591  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21f3fc added. We now have 3 listener(s)
09-13 08:51:09.596  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 08:51:09.596  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 08:51:09.596  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 08:51:09.597  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 08:51:09.597  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b3da85 added. We now have 4 listener(s)
09-13 08:51:09.597  3939  3989 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 08:51:09.598  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 08:51:09.598  4327  4343 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 08:51:09.598  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:51:09.599  4327  4346 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 08:51:09.604  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 08:51:09.612  3939  3989 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 08:51:09.612  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 08:51:09.612  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 08:51:09.612  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 08:51:09.612  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 08:51:09.612  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 08:51:09.612  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 08:51:09.612  3939  3989 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 08:51:09.614  4327  4343 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-13 08:51:09.614  4327  4343 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 08:51:09.615  4327  4343 D BtGatt.GattService: current time is 233039869787
09-13 08:51:09.615  4327  4343 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -91, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 08:51:09.615  4327  4343 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 08:51:09.615  4327  4343 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 08:51:09.617  3939  3989 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 08:51:09.617  3939  3989 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 08:51:09.617  3939  3989 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 08:51:09.618  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 08:51:09.618  3939  3989 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 08:51:09.618  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:51:09.618  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:09.618  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 08:51:09.618  3939  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 08:51:09.618  3939  3989 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21f3fc removed from the list
09-13 08:51:09.618  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:51:09.618  3939  3989 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b3da85 removed from the list
,09-13 08:51:09.621  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:51:09.621  3939  3989 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 08:51:09.621  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 08:51:09.622  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:09.623  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:51:09.625  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 08:51:09.626  3939  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 08:51:09.626  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 08:51:09.626  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:51:09.626  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b3da85 not in the list
09-13 08:51:09.626  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 08:51:09.626  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:51:09.628  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 08:51:09.628  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 08:51:09.628  3939  3989 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 08:51:09.629  3939  3989 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b3da85 not in the list
09-13 08:51:09.629  3939  3989 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 08:51:09.629  3939  3989 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 08:51:09.629  3939  3989 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 08:51:09.629  3939  3989 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21f3fc not in the list
09-13 08:51:09.631  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-13 08:51:09.632  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 08:51:09.632  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 08:51:09.632  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 08:51:09.632  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 08:51:09.633  3939  3989 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 08:51:10.076  3939  3939 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 08:51:11.653  3939  4424 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 486, name: My test thread name)
,09-13 08:51:12.326   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=235750, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 08:51:13.650  3939  3989 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 486
,09-13 08:51:13.651  3939  3989 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 486, name: My test thread name)
,09-13 08:51:13.657  3939  4425 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 487, name: My test thread name)
09-13 08:51:13.657  3939  4425 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 487, thread name: My test thread name)
,09-13 08:51:13.658  3939  4425 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 487, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 08:51:13.662  3939  3989 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 08:51:13.670  3939  4426 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 491, name: My test thread name)
,09-13 08:51:13.671  3939  4426 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 491, thread name: My test thread name): Test exception.
,09-13 08:51:13.672  3939  4426 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 491, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 08:51:13.679  3939  3989 I jxcore-log: Total number of executed tests:  82
09-13 08:51:13.679  3939  3989 I jxcore-log: 
,09-13 08:51:13.680  3939  3989 I jxcore-log: Number of passed tests:  82
09-13 08:51:13.680  3939  3989 I jxcore-log: 
,09-13 08:51:13.681  3939  3989 I jxcore-log: Number of failed tests:  0
09-13 08:51:13.681  3939  3989 I jxcore-log: 
09-13 08:51:13.682  3939  3989 I jxcore-log: Number of ignored tests:  0
09-13 08:51:13.682  3939  3989 I jxcore-log: 
09-13 08:51:13.682  3939  3989 I jxcore-log: Total duration:  101464
09-13 08:51:13.682  3939  3989 I jxcore-log: 
,09-13 08:51:13.692  3939  3989 I jxcore-log: Unit Test app is loaded
09-13 08:51:13.692  3939  3989 I jxcore-log: 
,09-13 08:51:13.694  3939  4424 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 486, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-13 08:51:13.703  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.703  3939  3989 I jxcore-log: 
,09-13 08:51:13.708  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.708  3939  3989 I jxcore-log: 
,09-13 08:51:13.710  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.710  3939  3989 I jxcore-log: 
,09-13 08:51:13.711  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-13 08:51:13.711  3939  3989 I jxcore-log: 
,09-13 08:51:13.713  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 08:51:13.713  3939  3989 I jxcore-log: 
,09-13 08:51:13.715  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 08:51:13.715  3939  3989 I jxcore-log: 
,09-13 08:51:13.716  3939  3939 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 08:51:13.718  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.718  3939  3989 I jxcore-log: 
,09-13 08:51:13.721  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.721  3939  3989 I jxcore-log: 
09-13 08:51:13.722  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 08:51:13.722  3939  3989 I jxcore-log: 
,09-13 08:51:13.723  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 08:51:13.723  3939  3989 I jxcore-log: 
09-13 08:51:13.724  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 08:51:13.724  3939  3989 I jxcore-log: 
,09-13 08:51:13.725  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.725  3939  3989 I jxcore-log: 
09-13 08:51:13.726  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.726  3939  3989 I jxcore-log: 
09-13 08:51:13.726  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.726  3939  3989 I jxcore-log: 
,09-13 08:51:13.727  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.727  3939  3989 I jxcore-log: 
09-13 08:51:13.728  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.728  3939  3989 I jxcore-log: 
,09-13 08:51:13.729  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.729  3939  3989 I jxcore-log: 
09-13 08:51:13.730  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.730  3939  3989 I jxcore-log: 
,09-13 08:51:13.731  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.731  3939  3989 I jxcore-log: 
09-13 08:51:13.732  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.732  3939  3989 I jxcore-log: 
,09-13 08:51:13.733  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.733  3939  3989 I jxcore-log: 
09-13 08:51:13.734  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.734  3939  3989 I jxcore-log: 
,09-13 08:51:13.734  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.734  3939  3989 I jxcore-log: 
09-13 08:51:13.736  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.736  3939  3989 I jxcore-log: 
,09-13 08:51:13.736  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.736  3939  3989 I jxcore-log: 
09-13 08:51:13.737  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.737  3939  3989 I jxcore-log: 
,09-13 08:51:13.738  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.738  3939  3989 I jxcore-log: 
09-13 08:51:13.738  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.738  3939  3989 I jxcore-log: 
09-13 08:51:13.739  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.739  3939  3989 I jxcore-log: 
,09-13 08:51:13.739  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.739  3939  3989 I jxcore-log: 
09-13 08:51:13.740  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.740  3939  3989 I jxcore-log: 
09-13 08:51:13.740  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.740  3939  3989 I jxcore-log: 
,09-13 08:51:13.741  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.741  3939  3989 I jxcore-log: 
09-13 08:51:13.741  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.741  3939  3989 I jxcore-log: 
09-13 08:51:13.742  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.742  3939  3989 I jxcore-log: 
,09-13 08:51:13.742  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.742  3939  3989 I jxcore-log: 
09-13 08:51:13.743  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.743  3939  3989 I jxcore-log: 
09-13 08:51:13.743  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.743  3939  3989 I jxcore-log: 
,09-13 08:51:13.744  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.744  3939  3989 I jxcore-log: 
09-13 08:51:13.744  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.744  3939  3989 I jxcore-log: 
09-13 08:51:13.745  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 08:51:13.745  3939  3989 I jxcore-log: 
,09-13 08:51:13.745  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.745  3939  3989 I jxcore-log: 
09-13 08:51:13.746  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 08:51:13.746  3939  3989 I jxcore-log: 
09-13 08:51:13.746  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.746  3939  3989 I jxcore-log: 
,09-13 08:51:13.747  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.747  3939  3989 I jxcore-log: 
09-13 08:51:13.747  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.747  3939  3989 I jxcore-log: 
09-13 08:51:13.748  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.748  3939  3989 I jxcore-log: 
09-13 08:51:13.748  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.748  3939  3989 I jxcore-log: 
09-13 08:51:13.749  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 08:51:13.749  3939  3989 I jxcore-log: 
09-13 08:51:13.749  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.749  3939  3989 I jxcore-log: 
,09-13 08:51:13.750  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 08:51:13.750  3939  3989 I jxcore-log: 
09-13 08:51:13.750  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.750  3939  3989 I jxcore-log: 
09-13 08:51:13.751  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 08:51:13.751  3939  3989 I jxcore-log: 
09-13 08:51:13.751  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 08:51:13.751  3939  3989 I jxcore-log: 
,09-13 08:51:13.752  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 08:51:13.752  3939  3989 I jxcore-log: 
09-13 08:51:13.753  3939  3989 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 08:51:13.753  3939  3989 I jxcore-log: 
,09-13 08:51:13.757  3939  3989 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-13 08:51:13.757  3939  3989 I jxcore-log:   bluetooth: 'on',
09-13 08:51:13.757  3939  3989 I jxcore-log:   wifi: 'on',
09-13 08:51:13.757  3939  3989 I jxcore-log:   cellular: 'doNotCare',
09-13 08:51:13.757  3939  3989 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 08:51:13.757  3939  3989 I jxcore-log: 
,09-13 08:51:13.762  3939  3989 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-13 08:51:13.762  3939  3989 I jxcore-log:   bluetooth: 'on',
09-13 08:51:13.762  3939  3989 I jxcore-log:   wifi: 'on',
09-13 08:51:13.762  3939  3989 I jxcore-log:   cellular: 'doNotCare',
09-13 08:51:13.762  3939  3989 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 08:51:13.762  3939  3989 I jxcore-log: 
,09-13 08:51:13.763  3939  3989 I jxcore-log: My device name is: motorola-Nexus 6
09-13 08:51:13.763  3939  3989 I jxcore-log: 
,09-13 08:51:13.764  3939  3989 I jxcore-log: Running for WIFI network type
09-13 08:51:13.764  3939  3989 I jxcore-log: 
,09-13 08:51:16.221  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-13 08:51:16.221  3939  3989 I jxcore-log: 
,09-13 08:51:16.673  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-13 08:51:16.673  3939  3989 I jxcore-log: 
,09-13 08:51:16.705  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-13 08:51:16.705  3939  3989 I jxcore-log: 
,09-13 08:51:18.073  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-13 08:51:18.073  3939  3989 I jxcore-log: 
,09-13 08:51:18.309  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-13 08:51:18.309  3939  3989 I jxcore-log: 
,09-13 08:51:18.314  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-13 08:51:18.314  3939  3989 I jxcore-log: 
,09-13 08:51:18.320  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-13 08:51:18.320  3939  3989 I jxcore-log: 
,09-13 08:51:18.398  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-13 08:51:18.398  3939  3989 I jxcore-log: 
,09-13 08:51:18.417  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-13 08:51:18.417  3939  3989 I jxcore-log: 
,09-13 08:51:18.422  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-13 08:51:18.422  3939  3989 I jxcore-log: 
,09-13 08:51:19.364  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-13 08:51:19.364  3939  3989 I jxcore-log: 
,09-13 08:51:19.532  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-13 08:51:19.532  3939  3989 I jxcore-log: 
,09-13 08:51:19.863  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-13 08:51:19.863  3939  3989 I jxcore-log: 
,09-13 08:51:19.873  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-13 08:51:19.873  3939  3989 I jxcore-log: 
,09-13 08:51:19.881  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-13 08:51:19.881  3939  3989 I jxcore-log: 
,09-13 08:51:19.888  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-13 08:51:19.888  3939  3989 I jxcore-log: 
,09-13 08:51:19.928  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-13 08:51:19.928  3939  3989 I jxcore-log: 
,09-13 08:51:19.976  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-13 08:51:19.976  3939  3989 I jxcore-log: 
,09-13 08:51:19.983  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-13 08:51:19.983  3939  3989 I jxcore-log: 
,09-13 08:51:19.991  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-13 08:51:19.991  3939  3989 I jxcore-log: 
,09-13 08:51:20.011  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-13 08:51:20.011  3939  3989 I jxcore-log: 
,09-13 08:51:20.016  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-13 08:51:20.016  3939  3989 I jxcore-log: 
,09-13 08:51:20.022  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-13 08:51:20.022  3939  3989 I jxcore-log: 
,09-13 08:51:20.039  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-13 08:51:20.039  3939  3989 I jxcore-log: 
,09-13 08:51:20.066  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-13 08:51:20.066  3939  3989 I jxcore-log: 
,09-13 08:51:20.077  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-13 08:51:20.077  3939  3989 I jxcore-log: 
,09-13 08:51:20.091  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-13 08:51:20.091  3939  3989 I jxcore-log: 
,09-13 08:51:20.102  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-13 08:51:20.102  3939  3989 I jxcore-log: 
,09-13 08:51:20.119  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-13 08:51:20.119  3939  3989 I jxcore-log: 
,09-13 08:51:20.130  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-13 08:51:20.130  3939  3989 I jxcore-log: 
,09-13 08:51:20.135  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-13 08:51:20.135  3939  3989 I jxcore-log: 
,09-13 08:51:20.166  3939  3989 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-13 08:51:20.166  3939  3989 I jxcore-log: 
,09-13 08:51:20.178  3939  3989 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-13 08:51:20.179  3939  3989 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-13 08:51:20.179  3939  3989 I jxcore-log: 
,09-13 08:51:20.182  3939  3989 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-13 08:51:20.182  3939  3989 I jxcore-log: 
,09-13 08:51:20.182  3939  3989 I jxcore-log: ThaliTape :: Started ThaliTape
09-13 08:51:20.182  3939  3989 I jxcore-log: 
,09-13 08:51:20.187  3939  3989 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-13 08:51:20.187  3939  3989 I jxcore-log: 
,09-13 08:51:20.296  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:20.296  3939  3989 I jxcore-log: 
,09-13 08:51:20.297  3939  3989 I jxcore-log: websocket error
09-13 08:51:20.297  3939  3989 I jxcore-log: 
09-13 08:51:20.297  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:51:20.297  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:20.297  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:51:20.297  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:20.297  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:51:20.297  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:20.297  3939  3989 I jxcore-log: 
,09-13 08:51:20.966  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:20.966  3939  3989 I jxcore-log: 
,09-13 08:51:20.967  3939  3989 I jxcore-log: websocket error
09-13 08:51:20.967  3939  3989 I jxcore-log: 
,09-13 08:51:20.967  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:51:20.967  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:20.967  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:51:20.967  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:20.967  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
,09-13 08:51:20.967  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:20.967  3939  3989 I jxcore-log: 
,09-13 08:51:23.225  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:23.225  3939  3989 I jxcore-log: 
09-13 08:51:23.226  3939  3989 I jxcore-log: websocket error
09-13 08:51:23.226  3939  3989 I jxcore-log: 
,09-13 08:51:23.227  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:51:23.227  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:23.227  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:51:23.227  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:23.227  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:51:23.227  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:23.227  3939  3989 I jxcore-log: 
,09-13 08:51:25.239   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=248663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 08:51:27.968  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:27.968  3939  3989 I jxcore-log: 
,09-13 08:51:27.968  3939  3989 I jxcore-log: websocket error
09-13 08:51:27.968  3939  3989 I jxcore-log: 
09-13 08:51:27.969  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:51:27.969  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:27.969  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:51:27.969  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:27.969  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:51:27.969  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:27.969  3939  3989 I jxcore-log: 
,09-13 08:51:29.982  3301  4428 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 08:51:30.026  3301  4429 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 08:51:30.054  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:51:30.059  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:51:30.116  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 08:51:30.116  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 08:51:30.117  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:51:30.117  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:51:30.185  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:51:30.192  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:51:30.258  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-13 08:51:30.259  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 08:51:30.259  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:51:30.260  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:51:30.291  3301  4429 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 08:51:30.291  3301  4428 E BooksSync: Soft error
09-13 08:51:30.291  3301  4428 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:51:30.291  3301  4428 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 08:51:30.292  3301  4428 E BooksSync: Sync error
09-13 08:51:30.292  3301  4428 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:51:30.292  3301  4428 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 08:51:30.292  3301  4428 I BooksSync: Finished books sync
,09-13 08:51:30.309   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 253273, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:51:33.047  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:33.047  3939  3989 I jxcore-log: 
,09-13 08:51:33.048  3939  3989 I jxcore-log: websocket error
09-13 08:51:33.048  3939  3989 I jxcore-log: 
09-13 08:51:33.048  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:51:33.048  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:33.048  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
,09-13 08:51:33.048  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:33.048  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:51:33.048  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:33.048  3939  3989 I jxcore-log: 
,09-13 08:51:38.119  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:38.119  3939  3989 I jxcore-log: 
,09-13 08:51:38.120  3939  3989 I jxcore-log: websocket error
09-13 08:51:38.120  3939  3989 I jxcore-log: 
,09-13 08:51:38.120  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13,
09-13 08:51:38.120  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:38.120  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:51:38.120  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:38.120  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:51:38.120  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:38.120  3939  3989 I jxcore-log: 
,09-13 08:51:43.185  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:43.185  3939  3989 I jxcore-log: 
,09-13 08:51:43.186  3939  3989 I jxcore-log: websocket error
09-13 08:51:43.186  3939  3989 I jxcore-log: 
,09-13 08:51:43.186  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:51:43.186  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:43.186  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:51:43.186  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:43.186  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:51:43.186  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:43.186  3939  3989 I jxcore-log: 
,09-13 08:51:48.254  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:48.254  3939  3989 I jxcore-log: 
,09-13 08:51:48.255  3939  3989 I jxcore-log: websocket error
09-13 08:51:48.255  3939  3989 I jxcore-log: 
09-13 08:51:48.256  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:51:48.256  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:48.256  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:51:48.256  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:48.256  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:51:48.256  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:48.256  3939  3989 I jxcore-log: 
,09-13 08:51:51.399   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=274824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 08:51:53.339  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:53.339  3939  3989 I jxcore-log: 
,09-13 08:51:53.340  3939  3989 I jxcore-log: websocket error
09-13 08:51:53.340  3939  3989 I jxcore-log: 
,09-13 08:51:53.341  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:51:53.341  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:53.341  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:51:53.341  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:53.341  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:51:53.341  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:53.341  3939  3989 I jxcore-log: 
,09-13 08:51:58.306   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=281731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 08:51:58.404  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:51:58.404  3939  3989 I jxcore-log: 
,09-13 08:51:58.404  3939  3989 I jxcore-log: websocket error
09-13 08:51:58.404  3939  3989 I jxcore-log: 
09-13 08:51:58.404  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:51:58.404  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:51:58.404  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:51:58.404  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:58.404  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:51:58.404  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:51:58.404  3939  3989 I jxcore-log: 
,09-13 08:52:02.255  3301  4431 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 08:52:02.280  3301  4432 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 08:52:02.296  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:02.301  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:02.335  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 08:52:02.335  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 08:52:02.335  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:52:02.335  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:52:02.362  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:02.366  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:02.397  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 08:52:02.397  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 08:52:02.397  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:52:02.397  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:52:02.430  3301  4432 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 08:52:02.431  3301  4431 E BooksSync: Soft error
09-13 08:52:02.431  3301  4431 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:52:02.431  3301  4431 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 08:52:02.431  3301  4431 E BooksSync: Sync error
09-13 08:52:02.431  3301  4431 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:52:02.431  3301  4431 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 08:52:02.431  3301  4431 I BooksSync: Finished books sync
,09-13 08:52:02.437   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 285522, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:52:03.494  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:52:03.494  3939  3989 I jxcore-log: 
,09-13 08:52:03.494  3939  3989 I jxcore-log: websocket error
09-13 08:52:03.494  3939  3989 I jxcore-log: 
09-13 08:52:03.494  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:52:03.494  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:52:03.494  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:52:03.494  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:03.494  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:52:03.494  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:03.494  3939  3989 I jxcore-log: 
,09-13 08:52:08.566  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:52:08.566  3939  3989 I jxcore-log: 
09-13 08:52:08.566  3939  3989 I jxcore-log: websocket error
09-13 08:52:08.566  3939  3989 I jxcore-log: 
09-13 08:52:08.566  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:52:08.566  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:52:08.566  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:52:08.566  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:08.566  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:52:08.566  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:08.566  3939  3989 I jxcore-log: 
,09-13 08:52:13.630  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:52:13.630  3939  3989 I jxcore-log: 
09-13 08:52:13.631  3939  3989 I jxcore-log: websocket error
09-13 08:52:13.631  3939  3989 I jxcore-log: 
09-13 08:52:13.631  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:52:13.631  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:52:13.631  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:52:13.631  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:13.631  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:52:13.631  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:13.631  3939  3989 I jxcore-log: 
,09-13 08:52:18.685  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:52:18.685  3939  3989 I jxcore-log: 
09-13 08:52:18.685  3939  3989 I jxcore-log: websocket error
09-13 08:52:18.685  3939  3989 I jxcore-log: 
,09-13 08:52:18.685  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:52:18.685  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:52:18.685  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:52:18.685  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:18.685  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:52:18.685  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:18.685  3939  3989 I jxcore-log: 
,09-13 08:52:23.741  3939  3989 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 08:52:23.741  3939  3989 I jxcore-log: 
,09-13 08:52:23.742  3939  3989 I jxcore-log: websocket error
09-13 08:52:23.742  3939  3989 I jxcore-log: 
09-13 08:52:23.743  3939  3989 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 08:52:23.743  3939  3989 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 08:52:23.743  3939  3989 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 08:52:23.743  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:23.743  3939  3989 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 08:52:23.743  3939  3989 I jxcore-log: emit@events.js:82:1
09-13 08:52:23.743  3939  3989 I jxcore-log: 
,09-13 08:52:24.466   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 08:52:28.877  3939  3989 I jxcore-log: ThaliTape :: Reconnected to the test server
09-13 08:52:28.877  3939  3989 I jxcore-log: 
,09-13 08:52:28.892  3939  3989 I jxcore-log: ThaliTape :: Connected to the test server
09-13 08:52:28.892  3939  3989 I jxcore-log: 
,09-13 08:52:32.878  3747  4447 V KeepSync: Connecting to GoogleApiClient
09-13 08:52:32.878   872  1952 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 08:52:32.919  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:32.925  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:32.982  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:52:32.982  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 08:52:32.982  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:52:32.982  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:52:33.022  3702  4449 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 08:52:33.022  3702  4449 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at blb.a(PG:3937)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at czp.a(PG:18188)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:52:33.022  3702  4449 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	... 12 more
09-13 08:52:33.022  3702  4449 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at fal.a(PG:38)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:52:33.022  3702  4449 E HttpOperation: 	... 14 more
,09-13 08:52:33.029  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 08:52:33.029  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 08:52:33.029  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:52:33.029  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:52:33.058  1740  4450 V BaseAuthAsyncOperation: access token request failed
,09-13 08:52:33.058  3747  4447 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 08:52:33.082  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:52:33.082  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 08:52:33.082  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:52:33.082  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:52:33.120  3702  4449 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 08:52:33.120  3702  4449 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at hec.a(PG:42)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at hee.a(PG:102)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at czr.a(PG:65)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at kka.a(PG:108)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at czp.a(PG:19176)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:52:33.120  3702  4449 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	... 15 more
09-13 08:52:33.120  3702  4449 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at fal.a(PG:38)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:52:33.120  3702  4449 E HttpOperation: 	... 17 more
,09-13 08:52:33.120  3702  4449 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 08:52:33.120  3702  4449 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at hec.a(PG:42)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at hee.a(PG:102)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at czr.a(PG:65)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at kka.a(PG:108)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	... 15 more
09-13 08:52:33.120  3702  4449 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at fal.a(PG:38)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 08:52:33.120  3702  4449 E ExperimentLoader: 	... 17 more
,09-13 08:52:33.227  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 08:52:33.228  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 08:52:33.228  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:52:33.228  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:52:33.248  3747  4447 E KeepSync: IOException
09-13 08:52:33.248  3747  4447 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 08:52:33.248  3747  4447 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:52:33.248  3747  4447 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 08:52:33.248  3747  4447 E KeepSync: 	... 10 more
09-13 08:52:33.248  3747  4447 W KeepSync: Sync result 2
,09-13 08:52:33.257   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 291558, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:52:33.285   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 287642, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:52:33.773   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=317197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 08:52:56.945  1740  1740 V CheckinService: unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,09-13 08:52:57.013  1740  4455 I CheckinService: Checking schedule, now: 1473749577013 next: 1473749513471
09-13 08:52:57.013  1740  4455 I CheckinService: active receiver: enabled
,09-13 08:52:57.016  1740  4455 I CheckinService: Preparing to send checkin request
,09-13 08:52:57.016  1740  4455 I EventLogService: Accumulating logs since 1473748949852
,09-13 08:52:57.028  1740  4455 I EventLogService: Opted in for usage reporting
,09-13 08:52:57.065  1740  4455 W EventLogAggregator: Unknown tag: snet_gcore
,09-13 08:52:57.066  1740  4455 W EventLogAggregator: Unknown tag: snet_launch_service
,09-13 08:52:57.106  1740  4455 I CheckinRequestBuilder: Checkin reason type: 11 attempt count: 1
,09-13 08:52:57.122   872  1952 I ActivityManager: Start proc 4457:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,09-13 08:52:57.123   872  1304 D WifiService: New client listening to asynchronous messages
,09-13 08:52:57.132  1740  4455 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-13 08:52:57.175  4457  4457 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,09-13 08:52:57.274  4457  4470 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-13 08:52:57.439  4457  4470 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-13 08:52:57.507  4457  4470 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 08:52:57.543  4457  4457 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,09-13 08:52:57.585  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:57.587  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:57.685  1500  3132 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,09-13 08:52:57.686  1500  3132 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
09-13 08:52:57.686  1500  3132 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:52:57.686  1500  3132 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:52:57.755  1740  4455 W CheckinRequestBuilder: awaiting user notification for token
,09-13 08:52:57.825  4457  4457 W InstanceID/Rpc: Found 10011
,09-13 08:52:57.980   872  1952 I ActivityManager: Start proc 4534:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,09-13 08:52:57.981  4491  4491 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1221828704.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1221828704.dex
,09-13 08:52:58.024  4491  4491 I dex2oat : dex2oat took 45.045ms (threads: 4) arena alloc=287KB java alloc=33KB native alloc=1514KB free=1557KB
,09-13 08:52:58.077  4534  4534 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-13 08:52:58.094  4534  4534 I MultiDex: VM with version 2.1.0 has multidex support
,09-13 08:52:58.094  4534  4534 I MultiDex: install
09-13 08:52:58.094  4534  4534 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 08:52:58.148  4534  4534 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-13 08:52:58.179  4534  4534 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 08:52:58.187  1500  2506 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-13 08:52:58.199  1500  1500 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-13 08:52:58.239  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:58.259  1740  1740 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-13 08:52:58.345   872  3377 I ActivityManager: Start proc 4557:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,09-13 08:52:58.376  4534  4549 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 08:52:58.383   376  2061 D WVCdm   : Instantiating CDM.
,09-13 08:52:58.383   376   376 I WVCdm   : CdmEngine::OpenSession
09-13 08:52:58.383   376   376 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-13 08:52:58.388   376   376 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-13 08:52:58.397  4557  4557 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-13 08:52:58.408  4557  4557 I MultiDex: VM with version 2.1.0 has multidex support
,09-13 08:52:58.408  4557  4557 I MultiDex: install
09-13 08:52:58.408  4557  4557 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 08:52:58.411   376   376 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,09-13 08:52:58.411   376   376 D DrmWidevineDash: Service_Initialize: starts!
09-13 08:52:58.411   376   376 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-13 08:52:58.412   376   376 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 08:52:58.412  1740  4570 D LocationInitializer: Restart initialization of location
,09-13 08:52:58.432  2129  2210 W GCoreFlp: No location to return for getLastLocation()
,09-13 08:52:58.432  1500  4573 W FusedLocationProvider: location=null
,09-13 08:52:58.443  4534  4554 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,09-13 08:52:58.458  4557  4557 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-13 08:52:58.480  4557  4557 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 08:52:58.487  1500  1500 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-13 08:52:58.491  4557  4557 D WearableService: callingUid 10011, callindPid: 4557
09-13 08:52:58.486  1500  2513 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-13 08:52:58.508  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:52:58.509  1740  1740 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-13 08:52:58.520  4557  4576 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
09-13 08:52:58.526  2129  2234 E MDM     : [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
09-13 08:52:58.532  2129  2234 E MDM     : [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-13 08:52:58.536  1740  4579 D LocationInitializer: Restart initialization of location
,09-13 08:52:58.552  2129  2210 W GCoreFlp: No location to return for getLastLocation()
,09-13 08:52:58.553  1500  4580 W FusedLocationProvider: location=null
,09-13 08:52:58.638   376   376 D QSEECOMAPI: : Loaded image: APP id = 3
,09-13 08:52:58.639   376   376 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-13 08:52:58.640   376   376 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1b97000
09-13 08:52:58.640   376   376 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1b97000
,09-13 08:52:58.646   339   344 D DrmLibTime: got the req here! ret=0
,09-13 08:52:58.646   339   344 D DrmLibTime: command id, time_cmd_id = 770
,09-13 08:52:58.646   339   344 D DrmLibTime: time_getutcsec starts!
09-13 08:52:58.647   339   344 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-13 08:52:58.647   339   344 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-13 08:52:58.647   339   344 D DrmLibTime: QSEE Time Listener: seconds: 1473749578
09-13 08:52:58.647   339   344 D DrmLibTime: QSEE Time Listener: nano seconds: 647502058
09-13 08:52:58.647   339   344 D DrmLibTime: time_getutcsec returns 0, sec = 1473749578; nsec = 647502058
09-13 08:52:58.648   339   344 D DrmLibTime: time_getutcsec finished! 
09-13 08:52:58.648   339   344 D DrmLibTime: iotcl_continue_command finished! and return 0 
,09-13 08:52:58.649   339   344 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-13 08:52:58.653   376   376 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-13 08:52:58.653   376   376 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-13 08:52:58.654   376   376 D DrmWidevineDash: hlos api version =  10
09-13 08:52:58.654   376   376 D DrmWidevineDash: tz api version =  10
09-13 08:52:58.654   376   376 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-13 08:52:58.654   376   376 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-13 08:52:58.680   376   376 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-13 08:52:58.680   376   376 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-13 08:52:58.680   376   376 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbefd0214
09-13 08:52:58.680   376   376 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-13 08:52:58.681   376   376 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-13 08:52:58.681   376   376 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb604d4b8, dataLength=8
09-13 08:52:58.681   376   376 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-13 08:52:58.688   376   376 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb607e200, wrapped_rsa_key_length=1280
,09-13 08:52:58.694   376   376 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,09-13 08:52:58.694   376   376 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-13 08:52:58.696   376  1312 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-13 08:52:58.696   376  1312 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-13 08:52:58.696   376  1312 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-13 08:52:58.696   376  1312 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb460f700, idLength=0xb2d81f2c
,09-13 08:52:58.709   376  1312 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-13 08:52:58.709   376  1312 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-13 08:52:58.709   376  1312 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,09-13 08:52:58.710   376  1312 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-13 08:52:58.710   376  1312 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
09-13 08:52:58.710   376  1312 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,09-13 08:52:58.711   376  1312 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
09-13 08:52:58.711   376  1312 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-13 08:52:58.711   376  1312 D DrmWidevineDash: hlos api version =  10
,09-13 08:52:58.712   376  1312 D DrmWidevineDash: tz api version =  10
09-13 08:52:58.712   376  1312 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-13 08:52:58.712   376  1312 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,09-13 08:52:58.713   376  1312 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
09-13 08:52:58.713   376  1312 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-13 08:52:58.713   376  1312 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,09-13 08:52:58.713   376  1312 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-13 08:52:58.713   376  1312 D WVCdm   : PrepareKeyRequest: nonce=687393417
09-13 08:52:58.714   376  1312 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb165f000
,09-13 08:52:58.714   376  1312 D DrmWidevineDash: message_length=1624, signature=0xb3a9aa00, signature_length=3000508420
,09-13 08:52:58.821   376  1312 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-13 08:52:58.822   376  1275 I WVCdm   : CdmEngine::CloseSession
,09-13 08:52:58.823   376  1275 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-13 08:52:58.823   376  1275 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-13 08:52:58.823   376  1275 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-13 08:52:58.824   376  1275 D DrmWidevineDash: Service_Uninitialize: starts!
09-13 08:52:58.824   376  1275 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-13 08:52:58.824   376  1275 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
09-13 08:52:58.825   376  1275 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-13 08:52:58.825   376  1275 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-13 08:52:59.082  4587  4587 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,09-13 08:52:59.131  4587  4587 I dex2oat : dex2oat took 49.748ms (threads: 4) arena alloc=274KB java alloc=63KB native alloc=1669KB free=1914KB
,09-13 08:52:59.135  4534  4549 W System  : ClassLoader referenced unknown path: 
,09-13 08:52:59.154  4534  4549 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 08:52:59.154  4534  4549 I Adreno  : Build Date                       : 10/20/15
09-13 08:52:59.154  4534  4549 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 08:52:59.154  4534  4549 I Adreno  : Local Branch                     : M14
09-13 08:52:59.154  4534  4549 I Adreno  : Remote Branch                    : 
09-13 08:52:59.154  4534  4549 I Adreno  : Remote Branch                    : 
09-13 08:52:59.154  4534  4549 I Adreno  : Reconstruct Branch               : 
,09-13 08:52:59.246  4534  4549 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 08:52:59.246  4534  4549 I Adreno  : Build Date                       : 10/20/15
09-13 08:52:59.246  4534  4549 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 08:52:59.246  4534  4549 I Adreno  : Local Branch                     : M14
09-13 08:52:59.246  4534  4549 I Adreno  : Remote Branch                    : 
09-13 08:52:59.246  4534  4549 I Adreno  : Remote Branch                    : 
09-13 08:52:59.246  4534  4549 I Adreno  : Reconstruct Branch               : 
,09-13 08:52:59.314   376  2061 I WVCdm   : CdmEngine::OpenSession
,09-13 08:52:59.314   376  2061 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-13 08:52:59.316   376  2061 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
09-13 08:52:59.317   376  2061 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,09-13 08:52:59.317   376  2061 D DrmWidevineDash: Service_Initialize: starts!
09-13 08:52:59.317   376  2061 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-13 08:52:59.317   376  2061 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 08:52:59.527   376  2061 D QSEECOMAPI: : Loaded image: APP id = 3
,09-13 08:52:59.529   376  2061 D DrmWidevineDash: Service_Initialize: ends! returns 0
09-13 08:52:59.529   376  2061 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1b97000
,09-13 08:52:59.529   376  2061 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1b97000
,09-13 08:52:59.536   339   344 D DrmLibTime: got the req here! ret=0
,09-13 08:52:59.536   339   344 D DrmLibTime: command id, time_cmd_id = 770
,09-13 08:52:59.536   339   344 D DrmLibTime: time_getutcsec starts!
09-13 08:52:59.536   339   344 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-13 08:52:59.536   339   344 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-13 08:52:59.537   339   344 D DrmLibTime: QSEE Time Listener: seconds: 1473749579
,09-13 08:52:59.537   339   344 D DrmLibTime: QSEE Time Listener: nano seconds: 537114699
09-13 08:52:59.537   339   344 D DrmLibTime: time_getutcsec returns 0, sec = 1473749579; nsec = 537114699
09-13 08:52:59.537   339   344 D DrmLibTime: time_getutcsec finished! 
09-13 08:52:59.538   339   344 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-13 08:52:59.538   339   344 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-13 08:52:59.540   376  2061 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-13 08:52:59.540   376  2061 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-13 08:52:59.541   376  2061 D DrmWidevineDash: hlos api version =  10
09-13 08:52:59.541   376  2061 D DrmWidevineDash: tz api version =  10
09-13 08:52:59.541   376  2061 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,09-13 08:52:59.541   376  2061 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-13 08:52:59.559   376  2061 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-13 08:52:59.559   376  2061 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-13 08:52:59.559   376  2061 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2abf134
,09-13 08:52:59.564   376  2061 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,09-13 08:52:59.564   376  2061 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-13 08:52:59.564   376  2061 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb604d668, dataLength=8
09-13 08:52:59.567   376  2061 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
09-13 08:52:59.569   376  2061 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb6008800, wrapped_rsa_key_length=1280
,09-13 08:52:59.577   376  2061 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-13 08:52:59.577   376  2061 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-13 08:52:59.581   376  1275 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-13 08:52:59.582   376  1275 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
,09-13 08:52:59.582   376  1275 I WVCdm   : CdmEngine::GenerateKeyRequest
09-13 08:52:59.582   376  1275 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb460f780, idLength=0xb307ff2c
,09-13 08:52:59.603   376  1275 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-13 08:52:59.603   376  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-13 08:52:59.603   376  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-13 08:52:59.603   376  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
,09-13 08:52:59.603   376  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
09-13 08:52:59.603   376  1275 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
09-13 08:52:59.604   376  1275 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
09-13 08:52:59.604   376  1275 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-13 08:52:59.605   376  1275 D DrmWidevineDash: hlos api version =  10
09-13 08:52:59.605   376  1275 D DrmWidevineDash: tz api version =  10
09-13 08:52:59.605   376  1275 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-13 08:52:59.605   376  1275 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
09-13 08:52:59.605   376  1275 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,09-13 08:52:59.605   376  1275 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-13 08:52:59.606   376  1275 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
09-13 08:52:59.606   376  1275 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-13 08:52:59.606   376  1275 D WVCdm   : PrepareKeyRequest: nonce=423437029
09-13 08:52:59.606   376  1275 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb165f700
09-13 08:52:59.606   376  1275 D DrmWidevineDash: message_length=1655, signature=0xb3a9a500, signature_length=3003645956
,09-13 08:52:59.665   376  1275 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-13 08:52:59.667   376  1312 I WVCdm   : CdmEngine::CloseSession
,09-13 08:52:59.668   376  1312 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,09-13 08:52:59.670   376  1312 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,09-13 08:52:59.671   376  1312 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,09-13 08:52:59.673   376  1312 D DrmWidevineDash: Service_Uninitialize: starts!
09-13 08:52:59.674   376  1312 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-13 08:52:59.674   376  1312 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,09-13 08:52:59.676   376  1312 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-13 08:52:59.677   376  1312 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-13 08:52:59.710  4549  4549 W Binder_2: type=1400 audit(0.0:8): avc: denied { read } for name="/" dev="tmpfs" ino=10241 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
,09-13 08:52:59.970  1740  4455 I CheckinRequestBuilder: Classify the device as Phone.
,09-13 08:52:59.984  1740  4455 I EventLogService: Opted in for usage reporting
,09-13 08:53:00.354  1740  4455 I CheckinTask: Sending checkin request (10154 bytes)
,09-13 08:53:00.783  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:00.838  1500  2066 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 08:53:00.838  1500  2066 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 08:53:00.838  1500  2066 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:53:00.838  1500  2066 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:00.869  1500  2066 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 08:53:00.869  1500  2066 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 08:53:00.869  1500  2066 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 08:53:00.869  1500  2066 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-13 08:53:00.869  1500  2066 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-13 08:53:00.869  1500  2066 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-13 08:53:00.869  1500  2066 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 08:53:00.873  3663  3694 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 08:53:00.873  3663  3694 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-13 08:53:00.873  3663  3694 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-13 08:53:00.873  3663  3694 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-13 08:53:00.873  3663  3694 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-13 08:53:00.873  3663  3694 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-13 08:53:00.873  3663  3694 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 08:53:00.930  1740  4455 I CheckinResponseProcessor: From server: 2 gservices updates and 0 deletes
,09-13 08:53:01.036  1500  2207 I GservicesProvider: main difference update completed
,09-13 08:53:01.064   872   885 I ActivityManager: Start proc 4604:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,09-13 08:53:01.067  1740  4455 I CheckinRequestBuilder: Checkin reason type: 11 attempt count: 1
,09-13 08:53:01.069  1740  4455 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-13 08:53:01.109   872  1378 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-13 08:53:01.110  2411  2411 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-13 08:53:01.110  2411  2411 W Babel   : BAM#gBA: invalid account id: -1
09-13 08:53:01.110  2411  2411 W Babel   : BAM#gBA: invalid account id: -1
09-13 08:53:01.110  2411  2411 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-13 08:53:01.116  4604  4604 W System  : ClassLoader referenced unknown path: /system/priv-app/ConfigUpdater/lib/arm
,09-13 08:53:01.138  4604  4604 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION intent_firewall: null null
,09-13 08:53:01.146  4604  4604 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION apn_db: null null
,09-13 08:53:01.149  4604  4604 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION tzdata: null null
,09-13 08:53:01.153  4604  4604 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION selinux: null null
,09-13 08:53:01.157  4604  4604 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION carrier_provisioning_urls: null null
,09-13 08:53:01.174  4174  4174 W InstanceID/Rpc: Found 10011
,09-13 08:53:01.191  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,09-13 08:53:01.192  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
09-13 08:53:01.192  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:53:01.192  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:01.199   872  3377 I ActivityManager: Start proc 4630:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,09-13 08:53:01.201   872  3377 I ActivityManager: Killing 3858:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-13 08:53:01.302  4630  4630 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,09-13 08:53:01.330  1740  4455 W CheckinRequestBuilder: awaiting user notification for token
,09-13 08:53:01.357  1740  4455 I CheckinRequestBuilder: Classify the device as Phone.
,09-13 08:53:01.391   872   882 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,09-13 08:53:01.399  1740  4455 I EventLogService: Opted in for usage reporting
,09-13 08:53:01.419  1740  4455 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-13 08:53:01.435  1740  1740 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,09-13 08:53:01.438  1740  1740 D SystemUpdateService: onCreate
,09-13 08:53:01.441  1740  4455 I CheckinService: Checking schedule, now: 1473749581441 next: 1473790724420
,09-13 08:53:01.441  1740  4455 I CheckinService: active receiver: disabled
,09-13 08:53:01.444  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 08:53:01.458  1740  1740 D OcrModelManager: Updating downloaded model state (gservices changed)
,09-13 08:53:01.464  1740  1740 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,09-13 08:53:01.465  1740  1740 I OcrUtils: Updating ocr activity enabled=false
09-13 08:53:01.468  1500  3097 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,09-13 08:53:01.472  1740  4657 I CheckinService: Checking schedule, now: 1473749581472 next: 1473790724420
,09-13 08:53:01.472  1740  4657 I CheckinService: active receiver: disabled
,09-13 08:53:01.478  1740  4656 I SystemUpdateService: active receiver: enabled
,09-13 08:53:01.488  2129  2129 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,09-13 08:53:01.502  2129  2129 I GCoreUlr: DispatchingService.onCreate()
,09-13 08:53:01.516   872  1978 I ActivityManager: Killing 3784:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-13 08:53:01.556  1740  4656 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 08:53:01.562  1740  4656 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 08:53:01.562  1740  4656 I SystemUpdateService: now status is 0 (complete)
09-13 08:53:01.562  1740  4656 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 08:53:01.563  1740  4656 I SystemUpdateService: file has been verified
,09-13 08:53:01.563  1740  4656 I SystemUpdateService: OTA package size = 12249756
,09-13 08:53:01.587  1740  4656 I SystemUpdateService: showing system update notification
,09-13 08:53:01.604  2129  4662 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,09-13 08:53:01.676  2129  4662 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,09-13 08:53:01.681  2129  4662 I GCoreUlr: Unbound from all location providers
,09-13 08:53:01.701  2129  2129 I GCoreUlr: DispatchingService.onDestroy()
,09-13 08:53:01.701  2129  2129 I GCoreUlr: Stopping handler for UlrDispSvcFast
,09-13 08:53:01.704  2129  2129 I GCoreUlr: Unbound from all location providers
,09-13 08:53:01.801  1740  1740 D SystemUpdateService: onDestroy
,09-13 08:53:01.943  2043  3992 I GservicesUpdateTask: Updating Gservices keys
,09-13 08:53:01.996  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 08:53:02.004  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 08:53:02.007  1500  1929 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-13 08:53:03.550   872  3378 I ActivityManager: Killing 3663:com.android.vending/u0a19 (adj 15): empty #17
,09-13 08:53:04.982   872  3377 I ActivityManager: Killing 4025:com.android.settings/1000 (adj 15): empty #17
,09-13 08:53:06.663   872  3377 I ActivityManager: Killing 4044:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,09-13 08:53:07.102   872  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 08:53:07.142   872  2001 I ActivityManager: Start proc 4676:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-13 08:53:07.190  4676  4676 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-13 08:53:07.232  4676  4676 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-13 08:53:07.232  2129  2129 V GmsNetworkLocationProvi: DISABLE
,09-13 08:53:07.240  2129  2129 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-13 08:53:07.258   872   883 I ActivityManager: Start proc 4694:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,09-13 08:53:07.270  4676  4691 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,09-13 08:53:07.331  4694  4694 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,09-13 08:53:07.434  4694  4694 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-13 08:53:07.501  4694  4694 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,09-13 08:53:07.518  4694  4694 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 08:53:07.521  4694  4694 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 08:53:07.601  4694  4727 D Ads     : Skipping gmscore version check
,09-13 08:53:07.612  4694  4694 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
09-13 08:53:07.613  4694  4694 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,09-13 08:53:07.621  1740  4728 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-13 08:53:07.624  4694  4727 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-13 08:53:07.643  2043  4729 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-13 08:53:07.649  1740  4728 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-13 08:53:07.691  1740  2372 I Icing   : updateResources: need to parse f{com.google.android.gms}
,09-13 08:53:07.701  2043  4729 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 59 ms] updated apps [took 59 ms] 
,09-13 08:53:07.768  4694  4694 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-13 08:53:07.786  4694  4694 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-13 08:53:07.820  4676  4691 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,09-13 08:53:07.820  4676  4691 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,09-13 08:53:07.843   872  1707 I ActivityManager: Start proc 4735:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,09-13 08:53:07.887   872  1978 I ActivityManager: Killing 4082:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-13 08:53:07.929  4735  4735 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,09-13 08:53:07.985   872  3377 I ActivityManager: Start proc 4747:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,09-13 08:53:08.010   872  2012 I ActivityManager: Start proc 4757:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,09-13 08:53:08.041   872  3378 I ActivityManager: Killing 4094:com.android.chrome/u0a40 (adj 15): empty #17
,09-13 08:53:08.082   872  1976 I ActivityManager: Killing 4109:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,09-13 08:53:08.101  4747  4747 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,09-13 08:53:08.183  4747  4773 I Gmail   : getAccountsCursor
,09-13 08:53:08.246  4747  4774 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,09-13 08:53:08.265  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:08.284  4757  4757 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,09-13 08:53:08.328  4757  4757 I GoogleHttpClient: GMS http client unavailable, use old client
,09-13 08:53:08.350  4747  4747 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-13 08:53:08.373  4676  4691 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,09-13 08:53:08.402  4747  4787 E Gmail   : Error finding the version of the Email provider.....
09-13 08:53:08.402  4747  4787 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
09-13 08:53:08.402  4747  4787 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
09-13 08:53:08.402  4747  4787 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
09-13 08:53:08.402  4747  4787 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
09-13 08:53:08.402  4747  4787 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 08:53:08.402  4747  4787 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 08:53:08.402  4747  4787 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
09-13 08:53:08.402  4747  4787 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 08:53:08.405  4747  4787 W EmailMigration: We do not support migrating this version of the Email provider.
,09-13 08:53:08.411  4676  4691 I ContactDirectoryManager: Discovered 0 contact directories in 832ms
09-13 08:53:08.426  4747  4789 I Gmail   : getAccountsCursor
,09-13 08:53:08.436  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:08.527  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:08.541   872  1952 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,09-13 08:53:08.591  4735  4735 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-13 08:53:08.646  4735  4735 I Exchange: EasService.onCreate
,09-13 08:53:08.659  4747  4796 I Gmail   : Observing account changes for notifications
,09-13 08:53:08.672  4735  4799 I Exchange: RestartPingTask
,09-13 08:53:08.706  4735  4735 I Exchange: RestartPingsTask did not start any pings.
09-13 08:53:08.706  4735  4735 I Exchange: PSS stopIfIdle
09-13 08:53:08.706  4735  4735 I Exchange: PSS has no active accounts; stopping service.
09-13 08:53:08.707  4735  4735 I Exchange: onDestroy
,09-13 08:53:08.727  4747  4795 I Gmail   : notifyAccountChanged
,09-13 08:53:08.730  4747  4785 I Gmail   : getAccountsCursor
,09-13 08:53:08.739  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:08.744  4747  4795 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,09-13 08:53:08.753  4747  4795 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,09-13 08:53:08.760  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:08.762  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:08.765  4747  4795 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-13 08:53:08.769  4747  4795 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-13 08:53:08.878  4747  4789 I Gmail   : getAccountsCursor
,09-13 08:53:08.886  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:11.463   872   896 W PackageSettings: Skipping PackageSetting{d948587 com.example.hello/10273} due to missing metadata
,09-13 08:53:12.223   872  1378 I ActivityManager: Killing 3301:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-13 08:53:12.354   872  1959 I ActivityManager: Killing 3747:com.google.android.keep/u0a79 (adj 15): empty #17
,09-13 08:53:12.522  4694  4694 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-13 08:53:12.579  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:12.643  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 08:53:12.644  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 08:53:12.644  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:53:12.644  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:12.691  4694  4694 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-13 08:53:12.717  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:12.786  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 08:53:12.787  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-13 08:53:12.787  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:53:12.788  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:12.899  4694  4803 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-13 08:53:12.903  4694  4694 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,09-13 08:53:12.903  4694  4694 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,09-13 08:53:12.914  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:12.962  1500  3132 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 08:53:12.962  1500  3132 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 08:53:12.962  1500  3132 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:53:12.962  1500  3132 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:12.985  4694  4694 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-13 08:53:13.190  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:13.217  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 08:53:13.218  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-13 08:53:13.218  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:53:13.218  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:13.249  4694  4694 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-13 08:53:13.250  4694  4694 D Finsky  : [1] WearSupportService.startHygiene: disabled
,09-13 08:53:13.252  4694  4694 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-13 08:53:13.257  4694  4694 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,09-13 08:53:13.269  4694  4805 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-13 08:53:13.434  4747  4780 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-13 08:53:13.627  4735  4798 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-13 08:53:28.174  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:28.182  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:28.183  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:28.213  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 08:53:28.213  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 08:53:28.213  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:53:28.213  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:28.254  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 08:53:28.254  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 08:53:28.255  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-13 08:53:32.157   872   884 I ActivityManager: Start proc 4812:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,09-13 08:53:32.241  4812  4812 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-13 08:53:32.400  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:53:32.401  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 08:53:32.401  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:53:32.401  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:32.417  3702  4825 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 08:53:32.417  3702  4825 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at blb.a(PG:3937)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at czp.a(PG:18188)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:53:32.417  3702  4825 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	... 12 more
09-13 08:53:32.417  3702  4825 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at fal.a(PG:38)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:53:32.417  3702  4825 E HttpOperation: 	... 14 more
,09-13 08:53:32.483  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:53:32.483  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 08:53:32.483  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:53:32.483  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:32.505  3702  4825 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 08:53:32.505  3702  4825 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at hec.a(PG:42)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at hee.a(PG:102)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at czr.a(PG:65)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at kka.a(PG:108)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at czp.a(PG:19176)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:53:32.505  3702  4825 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	... 15 more
09-13 08:53:32.505  3702  4825 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at fal.a(PG:38)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:53:32.505  3702  4825 E HttpOperation: 	... 17 more
,09-13 08:53:32.505  3702  4825 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 08:53:32.505  3702  4825 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at hec.a(PG:42)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at hee.a(PG:102)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at czr.a(PG:65)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at kka.a(PG:108)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	... 15 more
09-13 08:53:32.505  3702  4825 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at fal.a(PG:38)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 08:53:32.505  3702  4825 E ExperimentLoader: 	... 17 more
,09-13 08:53:32.567  4812  4830 V KeepSync: Connecting to GoogleApiClient
09-13 08:53:32.568   872  3377 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 08:53:32.640  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 08:53:32.640  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-13 08:53:32.640  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:53:32.640  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:32.658  1740  4836 V BaseAuthAsyncOperation: access token request failed
,09-13 08:53:32.660  4812  4830 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 08:53:32.685   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 348658, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:53:32.757   872   884 I ActivityManager: Start proc 4837:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-13 08:53:32.777  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 08:53:32.777  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 08:53:32.777  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:53:32.777  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:32.783  4837  4837 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-13 08:53:32.793  4812  4830 E KeepSync: IOException
09-13 08:53:32.793  4812  4830 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 08:53:32.793  4812  4830 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:53:32.793  4812  4830 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 08:53:32.793  4812  4830 E KeepSync: 	... 10 more
,09-13 08:53:32.793  4812  4830 W KeepSync: Sync result 2
09-13 08:53:32.806   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 347201, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:53:32.876  4837  4837 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-13 08:53:32.890  4837  4837 I BooksApp: Created application version: 3.6.9 (30609)
,09-13 08:53:32.999  4837  4855 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 08:53:33.132  4837  4861 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 08:53:33.184  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 08:53:33.184  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 08:53:33.184  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:53:33.184  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:33.236  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-13 08:53:33.236  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 08:53:33.236  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:53:33.236  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:33.253  4837  4861 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 08:53:33.256  4837  4855 E BooksSync: Soft error
09-13 08:53:33.256  4837  4855 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:53:33.256  4837  4855 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 08:53:33.256  4837  4855 E BooksSync: Sync error
09-13 08:53:33.256  4837  4855 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:53:33.256  4837  4855 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 08:53:33.256  4837  4855 I BooksSync: Finished books sync
,09-13 08:53:33.262   872  3377 I ActivityManager: Killing 4604:com.google.android.configupdater/u0a42 (adj 15): empty #17
,09-13 08:53:33.264   279   279 E lowmemorykiller: Error writing /proc/4604/oom_score_adj; errno=22
,09-13 08:53:33.266   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 349439, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:53:33.305   872  3377 I ActivityManager: Killing 4457:com.google.android.youtube/u0a86 (adj 15): empty #18
,09-13 08:53:37.286  4812  4819 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@6f20674)
,09-13 08:53:37.877  4837  4853 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-13 08:53:42.977  4694  4705 D Finsky  : [397] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-13 08:53:43.003  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:43.016  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:43.022  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:43.072  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 08:53:43.072  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-13 08:53:43.072  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:53:43.073  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-13 08:53:43.113  4694  4705 D Finsky  : [397] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-13 08:53:48.609  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:48.621  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:48.626  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:53:48.679  1500  2066 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 08:53:48.679  1500  2066 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 08:53:48.680  1500  2066 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:53:48.680  1500  2066 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:53:48.725  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 08:53:48.726  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 08:53:48.727  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-13 08:54:08.931  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:54:08.939  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:54:08.941  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:54:08.963  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 08:54:08.963  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 08:54:08.964  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:54:08.964  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:54:08.987  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 08:54:08.987  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 08:54:08.988  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 08:54:29.228  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:54:29.242  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:54:29.251  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:54:29.320  1500  2066 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 08:54:29.321  1500  2066 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 08:54:29.321  1500  2066 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:54:29.322  1500  2066 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:54:29.381  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 08:54:29.382  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 08:54:29.383  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 08:54:33.061  1500  2145 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 08:54:33.936  4812  4869 V KeepSync: Connecting to GoogleApiClient
,09-13 08:54:33.936   872  2001 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 08:54:34.010  1500  3132 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 08:54:34.010  1500  3132 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-13 08:54:34.010  1500  3132 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:54:34.010  1500  3132 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:54:34.035  1740  4870 V BaseAuthAsyncOperation: access token request failed
,09-13 08:54:34.037  4812  4869 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 08:54:34.097  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-13 08:54:34.097  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 08:54:34.098  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:54:34.098  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:54:34.123  4812  4869 E KeepSync: IOException
09-13 08:54:34.123  4812  4869 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 08:54:34.123  4812  4869 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:54:34.123  4812  4869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 08:54:34.123  4812  4869 E KeepSync: 	... 10 more
09-13 08:54:34.124  4812  4869 W KeepSync: Sync result 2
,09-13 08:54:34.136   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 437213, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:54:38.442  3939  3989 I jxcore-log: TAP version 13
09-13 08:54:38.442  3939  3989 I jxcore-log: 
,09-13 08:54:38.451  3939  3989 I jxcore-log: # setup
09-13 08:54:38.451  3939  3989 I jxcore-log: 
,09-13 08:54:38.634  3939  3989 I jxcore-log: # 1. calling createNativeListener directly rejects
09-13 08:54:38.634  3939  3989 I jxcore-log: 
,09-13 08:54:39.082  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:39.082  3939  3989 I jxcore-log: 
,09-13 08:54:39.095  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 38300
09-13 08:54:39.095  3939  3989 I jxcore-log: 
,09-13 08:54:39.103  3939  3989 I jxcore-log: ok 1 Should throw
09-13 08:54:39.103  3939  3989 I jxcore-log: 
,09-13 08:54:39.106  3939  3989 I jxcore-log: # teardown
09-13 08:54:39.106  3939  3989 I jxcore-log: 
,09-13 08:54:39.998  3939  3989 I jxcore-log: # setup
09-13 08:54:39.998  3939  3989 I jxcore-log: 
,09-13 08:54:41.267  3939  3989 I jxcore-log: # 2. emits incomingConnectionState
09-13 08:54:41.267  3939  3989 I jxcore-log: 
,09-13 08:54:41.496  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:41.496  3939  3989 I jxcore-log: 
,09-13 08:54:41.504  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 41291
09-13 08:54:41.504  3939  3989 I jxcore-log: 
,09-13 08:54:41.521  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:41.521  3939  3989 I jxcore-log: 
,09-13 08:54:41.527  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:41.527  3939  3989 I jxcore-log: 
,09-13 08:54:41.542  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:41.542  3939  3989 I jxcore-log: 
,09-13 08:54:41.549  3939  3989 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-13 08:54:41.549  3939  3989 I jxcore-log: 
,09-13 08:54:41.570  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:41.570  3939  3989 I jxcore-log: 
,09-13 08:54:41.572  3939  3989 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-13 08:54:41.572  3939  3989 I jxcore-log: 
,09-13 08:54:41.585  3939  3989 I jxcore-log: # teardown
09-13 08:54:41.585  3939  3989 I jxcore-log: 
,09-13 08:54:42.551  3939  3989 I jxcore-log: # setup
09-13 08:54:42.551  3939  3989 I jxcore-log: 
,09-13 08:54:43.371  3939  3989 I jxcore-log: # 3. emits routerPortConnectionFailed
09-13 08:54:43.371  3939  3989 I jxcore-log: 
,09-13 08:54:43.774  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:43.774  3939  3989 I jxcore-log: 
,09-13 08:54:43.781  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 41723
09-13 08:54:43.781  3939  3989 I jxcore-log: 
,09-13 08:54:43.789  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:43.789  3939  3989 I jxcore-log: 
,09-13 08:54:43.790  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:43.790  3939  3989 I jxcore-log: 
,09-13 08:54:43.792  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:43.792  3939  3989 I jxcore-log: 
,09-13 08:54:43.822  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:43.822  3939  3989 I jxcore-log: 
,09-13 08:54:43.826  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:43.826  3939  3989 I jxcore-log: 
,09-13 08:54:43.832  3939  3989 I jxcore-log: DEBUG createNativeListener: 
09-13 08:54:43.832  3939  3989 I jxcore-log: 
,09-13 08:54:43.833  3939  3989 I jxcore-log: ok 4 tried to connect to right port
09-13 08:54:43.833  3939  3989 I jxcore-log: 
,09-13 08:54:43.834  3939  3989 I jxcore-log: ok 5 failed due to refused connection
09-13 08:54:43.834  3939  3989 I jxcore-log: 
09-13 08:54:43.835  3939  3989 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-13 08:54:43.835  3939  3989 I jxcore-log: 
,09-13 08:54:43.838  3939  3989 I jxcore-log: # teardown
09-13 08:54:43.838  3939  3989 I jxcore-log: 
,09-13 08:54:43.840  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:43.840  3939  3989 I jxcore-log: 
,09-13 08:54:44.728  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:44.728  3939  3989 I jxcore-log: 
,09-13 08:54:44.733  3939  3989 I jxcore-log: # setup
09-13 08:54:44.733  3939  3989 I jxcore-log: 
09-13 08:54:44.734  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:44.734  3939  3989 I jxcore-log: 
,09-13 08:54:46.067  3939  3989 I jxcore-log: # 4. native server connections all up
09-13 08:54:46.067  3939  3989 I jxcore-log: 
,09-13 08:54:46.942  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:46.942  3939  3989 I jxcore-log: 
,09-13 08:54:46.950  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 40393
09-13 08:54:46.950  3939  3989 I jxcore-log: 
,09-13 08:54:46.964  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:46.964  3939  3989 I jxcore-log: 
,09-13 08:54:46.967  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:46.967  3939  3989 I jxcore-log: 
,09-13 08:54:46.969  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:46.969  3939  3989 I jxcore-log: 
,09-13 08:54:47.001  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:47.001  3939  3989 I jxcore-log: 
,09-13 08:54:47.004  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:47.004  3939  3989 I jxcore-log: 
,09-13 08:54:47.008  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:47.008  3939  3989 I jxcore-log: 
,09-13 08:54:47.010  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:47.010  3939  3989 I jxcore-log: 
,09-13 08:54:47.033  3939  3989 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-13 08:54:47.033  3939  3989 I jxcore-log: 
,09-13 08:54:47.033  3939  3989 I jxcore-log: ok 8 Send/recvd #1 should be same
09-13 08:54:47.033  3939  3989 I jxcore-log: 
,09-13 08:54:47.036  3939  3989 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-13 08:54:47.036  3939  3989 I jxcore-log: 
,09-13 08:54:47.037  3939  3989 I jxcore-log: ok 10 Send/recvd #2 should be same
09-13 08:54:47.037  3939  3989 I jxcore-log: 
,09-13 08:54:47.040  3939  3989 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-13 08:54:47.040  3939  3989 I jxcore-log: 
,09-13 08:54:47.046  3939  3989 I jxcore-log: # teardown
09-13 08:54:47.046  3939  3989 I jxcore-log: 
,09-13 08:54:47.670  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:47.670  3939  3989 I jxcore-log: 
,09-13 08:54:47.678  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:47.678  3939  3989 I jxcore-log: 
,09-13 08:54:47.680  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:47.680  3939  3989 I jxcore-log: 
,09-13 08:54:47.684  3939  3989 I jxcore-log: # setup
09-13 08:54:47.684  3939  3989 I jxcore-log: 
,09-13 08:54:47.686  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:47.686  3939  3989 I jxcore-log: 
,09-13 08:54:48.490  3939  3989 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-13 08:54:48.490  3939  3989 I jxcore-log: 
,09-13 08:54:48.714  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:48.714  3939  3989 I jxcore-log: 
,09-13 08:54:48.724  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 41913
09-13 08:54:48.724  3939  3989 I jxcore-log: 
,09-13 08:54:48.739  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:48.739  3939  3989 I jxcore-log: 
,09-13 08:54:48.740  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:48.740  3939  3989 I jxcore-log: 
,09-13 08:54:48.742  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:48.742  3939  3989 I jxcore-log: 
,09-13 08:54:48.757  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:48.757  3939  3989 I jxcore-log: 
,09-13 08:54:48.760  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:48.760  3939  3989 I jxcore-log: 
,09-13 08:54:48.774  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:48.774  3939  3989 I jxcore-log: 
,09-13 08:54:48.788  3939  3989 I jxcore-log: ok 12 socket shouldn't close until after stream
09-13 08:54:48.788  3939  3989 I jxcore-log: 
,09-13 08:54:48.788  3939  3989 I jxcore-log: ok 13 incoming remains open
09-13 08:54:48.788  3939  3989 I jxcore-log: 
,09-13 08:54:48.792  3939  3989 I jxcore-log: # teardown
09-13 08:54:48.792  3939  3989 I jxcore-log: 
,09-13 08:54:49.203  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:49.203  3939  3989 I jxcore-log: 
,09-13 08:54:49.219  3939  3989 I jxcore-log: # setup
09-13 08:54:49.219  3939  3989 I jxcore-log: 
,09-13 08:54:49.220  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:49.220  3939  3989 I jxcore-log: 
,09-13 08:54:49.703  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:54:49.721  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:54:49.729  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:54:49.812  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 08:54:49.813  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 08:54:49.813  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:54:49.814  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:54:49.885  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 08:54:49.886  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 08:54:49.902  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-13 08:54:50.231  3939  3989 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-13 08:54:50.231  3939  3989 I jxcore-log: 
,09-13 08:54:50.403  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:50.403  3939  3989 I jxcore-log: 
,09-13 08:54:50.410  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 43264
09-13 08:54:50.410  3939  3989 I jxcore-log: 
,09-13 08:54:50.418  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:50.418  3939  3989 I jxcore-log: 
,09-13 08:54:50.419  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:50.419  3939  3989 I jxcore-log: 
,09-13 08:54:50.421  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:50.421  3939  3989 I jxcore-log: 
,09-13 08:54:50.432  3939  3989 I jxcore-log: ok 14 we should not have gotten an error
09-13 08:54:50.432  3939  3989 I jxcore-log: 
,09-13 08:54:50.441  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:50.441  3939  3989 I jxcore-log: 
,09-13 08:54:50.444  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:50.444  3939  3989 I jxcore-log: 
,09-13 08:54:50.455  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:50.455  3939  3989 I jxcore-log: 
,09-13 08:54:50.458  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:50.458  3939  3989 I jxcore-log: 
,09-13 08:54:50.467  3939  3989 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-13 08:54:50.467  3939  3989 I jxcore-log: 
09-13 08:54:50.468  3939  3989 I jxcore-log: ok 16 incoming is cleaned up
09-13 08:54:50.468  3939  3989 I jxcore-log: 
,09-13 08:54:50.472  3939  3989 I jxcore-log: # teardown
09-13 08:54:50.472  3939  3989 I jxcore-log: 
,09-13 08:54:51.673  3939  3989 I jxcore-log: # setup
09-13 08:54:51.673  3939  3989 I jxcore-log: 
,09-13 08:54:51.889  3939  3989 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-13 08:54:51.889  3939  3989 I jxcore-log: 
,09-13 08:54:52.878  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:52.878  3939  3989 I jxcore-log: 
,09-13 08:54:52.887  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 39866
09-13 08:54:52.887  3939  3989 I jxcore-log: 
,09-13 08:54:52.898  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:52.898  3939  3989 I jxcore-log: 
,09-13 08:54:52.900  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:52.900  3939  3989 I jxcore-log: 
,09-13 08:54:52.903  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:52.903  3939  3989 I jxcore-log: 
,09-13 08:54:52.918  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:52.918  3939  3989 I jxcore-log: 
,09-13 08:54:52.923  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:52.923  3939  3989 I jxcore-log: 
,09-13 08:54:52.952  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:52.952  3939  3989 I jxcore-log: 
,09-13 08:54:52.961  3939  3989 I jxcore-log: ok 17 stream was closed
09-13 08:54:52.961  3939  3989 I jxcore-log: 
,09-13 08:54:52.962  3939  3989 I jxcore-log: ok 18 incoming should survive
09-13 08:54:52.962  3939  3989 I jxcore-log: 
,09-13 08:54:52.962  3939  3989 I jxcore-log: ok 19 mux should have no streams
09-13 08:54:52.962  3939  3989 I jxcore-log: 
,09-13 08:54:52.967  3939  3989 I jxcore-log: # teardown
09-13 08:54:52.967  3939  3989 I jxcore-log: 
,09-13 08:54:53.129  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:53.129  3939  3989 I jxcore-log: 
,09-13 08:54:53.144  3939  3989 I jxcore-log: # setup
09-13 08:54:53.144  3939  3989 I jxcore-log: 
,09-13 08:54:53.147  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:53.147  3939  3989 I jxcore-log: 
,09-13 08:54:54.225  3939  3989 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-13 08:54:54.225  3939  3989 I jxcore-log: 
,09-13 08:54:54.390  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:54.390  3939  3989 I jxcore-log: 
,09-13 08:54:54.399  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 48929
09-13 08:54:54.399  3939  3989 I jxcore-log: 
,09-13 08:54:54.410  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:54.410  3939  3989 I jxcore-log: 
,09-13 08:54:54.412  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:54.412  3939  3989 I jxcore-log: 
,09-13 08:54:54.413  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:54.413  3939  3989 I jxcore-log: 
,09-13 08:54:54.423  3939  3989 I jxcore-log: ok 20 we should not have gotten an error
09-13 08:54:54.423  3939  3989 I jxcore-log: 
,09-13 08:54:54.434  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:54.434  3939  3989 I jxcore-log: 
,09-13 08:54:54.437  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:54.437  3939  3989 I jxcore-log: 
,09-13 08:54:54.446  3939  3989 I jxcore-log: ok 21 Buffers are identical
09-13 08:54:54.446  3939  3989 I jxcore-log: 
,09-13 08:54:54.449  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:54.449  3939  3989 I jxcore-log: 
,09-13 08:54:54.452  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:54.452  3939  3989 I jxcore-log: 
,09-13 08:54:54.455  3939  3989 I jxcore-log: ok 22 native server is nulled out
09-13 08:54:54.455  3939  3989 I jxcore-log: 
09-13 08:54:54.455  3939  3989 I jxcore-log: ok 23 native server should be closed
09-13 08:54:54.455  3939  3989 I jxcore-log: 
09-13 08:54:54.456  3939  3989 I jxcore-log: ok 24 incoming has been removed
09-13 08:54:54.456  3939  3989 I jxcore-log: 
,09-13 08:54:54.456  3939  3989 I jxcore-log: ok 25 Incoming should be done
09-13 08:54:54.456  3939  3989 I jxcore-log: 
09-13 08:54:54.456  3939  3989 I jxcore-log: ok 26 The mux object should be closed
09-13 08:54:54.456  3939  3989 I jxcore-log: 
,09-13 08:54:54.457  3939  3989 I jxcore-log: ok 27 The mux stream should be closed
09-13 08:54:54.457  3939  3989 I jxcore-log: 
09-13 08:54:54.458  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:54.458  3939  3989 I jxcore-log: 
,09-13 08:54:54.472  3939  3989 I jxcore-log: # teardown
09-13 08:54:54.472  3939  3989 I jxcore-log: 
,09-13 08:54:55.646  3939  3989 I jxcore-log: # setup
09-13 08:54:55.646  3939  3989 I jxcore-log: 
,09-13 08:54:55.732  3939  3989 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-13 08:54:55.732  3939  3989 I jxcore-log: 
,09-13 08:54:55.836  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:55.836  3939  3989 I jxcore-log: 
,09-13 08:54:55.844  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 46497
09-13 08:54:55.844  3939  3989 I jxcore-log: 
,09-13 08:54:55.870  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.870  3939  3989 I jxcore-log: 
,09-13 08:54:55.871  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.871  3939  3989 I jxcore-log: 
,09-13 08:54:55.872  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.872  3939  3989 I jxcore-log: 
,09-13 08:54:55.876  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.876  3939  3989 I jxcore-log: 
,09-13 08:54:55.876  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.876  3939  3989 I jxcore-log: 
,09-13 08:54:55.878  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.878  3939  3989 I jxcore-log: 
,09-13 08:54:55.881  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.881  3939  3989 I jxcore-log: 
,09-13 08:54:55.881  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.881  3939  3989 I jxcore-log: 
,09-13 08:54:55.883  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.883  3939  3989 I jxcore-log: 
,09-13 08:54:55.887  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.887  3939  3989 I jxcore-log: 
,09-13 08:54:55.887  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.887  3939  3989 I jxcore-log: 
,09-13 08:54:55.888  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.888  3939  3989 I jxcore-log: 
,09-13 08:54:55.891  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.891  3939  3989 I jxcore-log: 
,09-13 08:54:55.892  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.892  3939  3989 I jxcore-log: 
,09-13 08:54:55.893  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.893  3939  3989 I jxcore-log: 
,09-13 08:54:55.895  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.895  3939  3989 I jxcore-log: 
09-13 08:54:55.896  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.896  3939  3989 I jxcore-log: 
,09-13 08:54:55.897  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.897  3939  3989 I jxcore-log: 
,09-13 08:54:55.904  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.904  3939  3989 I jxcore-log: 
,09-13 08:54:55.905  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.905  3939  3989 I jxcore-log: 
,09-13 08:54:55.907  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.907  3939  3989 I jxcore-log: 
,09-13 08:54:55.911  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.911  3939  3989 I jxcore-log: 
,09-13 08:54:55.911  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.911  3939  3989 I jxcore-log: 
09-13 08:54:55.912  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.912  3939  3989 I jxcore-log: 
,09-13 08:54:55.914  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.914  3939  3989 I jxcore-log: 
,09-13 08:54:55.914  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.914  3939  3989 I jxcore-log: 
09-13 08:54:55.915  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.915  3939  3989 I jxcore-log: 
,09-13 08:54:55.916  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:55.916  3939  3989 I jxcore-log: 
,09-13 08:54:55.917  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:55.917  3939  3989 I jxcore-log: 
09-13 08:54:55.918  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:55.918  3939  3989 I jxcore-log: 
,09-13 08:54:55.996  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:55.996  3939  3989 I jxcore-log: 
,09-13 08:54:55.999  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:55.999  3939  3989 I jxcore-log: 
,09-13 08:54:56.002  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.002  3939  3989 I jxcore-log: 
,09-13 08:54:56.004  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.004  3939  3989 I jxcore-log: 
,09-13 08:54:56.006  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.006  3939  3989 I jxcore-log: 
,09-13 08:54:56.008  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.008  3939  3989 I jxcore-log: 
,09-13 08:54:56.009  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.009  3939  3989 I jxcore-log: 
,09-13 08:54:56.011  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.011  3939  3989 I jxcore-log: 
,09-13 08:54:56.014  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.014  3939  3989 I jxcore-log: 
,09-13 08:54:56.016  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.016  3939  3989 I jxcore-log: 
,09-13 08:54:56.017  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.017  3939  3989 I jxcore-log: 
,09-13 08:54:56.019  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.019  3939  3989 I jxcore-log: 
,09-13 08:54:56.020  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.020  3939  3989 I jxcore-log: 
,09-13 08:54:56.021  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.021  3939  3989 I jxcore-log: 
,09-13 08:54:56.023  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.023  3939  3989 I jxcore-log: 
,09-13 08:54:56.024  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.024  3939  3989 I jxcore-log: 
,09-13 08:54:56.027  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.027  3939  3989 I jxcore-log: 
,09-13 08:54:56.028  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.028  3939  3989 I jxcore-log: 
,09-13 08:54:56.030  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.030  3939  3989 I jxcore-log: 
,09-13 08:54:56.031  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.031  3939  3989 I jxcore-log: 
,09-13 08:54:56.032  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.032  3939  3989 I jxcore-log: 
,09-13 08:54:56.034  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.034  3939  3989 I jxcore-log: 
,09-13 08:54:56.035  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.035  3939  3989 I jxcore-log: 
,09-13 08:54:56.037  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.037  3939  3989 I jxcore-log: 
,09-13 08:54:56.039  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.039  3939  3989 I jxcore-log: 
,09-13 08:54:56.041  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.041  3939  3989 I jxcore-log: 
,09-13 08:54:56.042  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.042  3939  3989 I jxcore-log: 
,09-13 08:54:56.043  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.043  3939  3989 I jxcore-log: 
,09-13 08:54:56.045  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.045  3939  3989 I jxcore-log: 
,09-13 08:54:56.046  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.046  3939  3989 I jxcore-log: 
09-13 08:54:56.047  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.047  3939  3989 I jxcore-log: 
,09-13 08:54:56.049  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.049  3939  3989 I jxcore-log: 
,09-13 08:54:56.051  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.051  3939  3989 I jxcore-log: 
,09-13 08:54:56.053  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.053  3939  3989 I jxcore-log: 
,09-13 08:54:56.054  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.054  3939  3989 I jxcore-log: 
,09-13 08:54:56.055  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.055  3939  3989 I jxcore-log: 
,09-13 08:54:56.056  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.056  3939  3989 I jxcore-log: 
,09-13 08:54:56.058  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.058  3939  3989 I jxcore-log: 
,09-13 08:54:56.065  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.065  3939  3989 I jxcore-log: 
,09-13 08:54:56.067  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.067  3939  3989 I jxcore-log: 
,09-13 08:54:56.069  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.069  3939  3989 I jxcore-log: 
,09-13 08:54:56.070  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.070  3939  3989 I jxcore-log: 
,09-13 08:54:56.072  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.072  3939  3989 I jxcore-log: 
,09-13 08:54:56.073  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.073  3939  3989 I jxcore-log: 
,09-13 08:54:56.074  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.074  3939  3989 I jxcore-log: 
,09-13 08:54:56.075  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.075  3939  3989 I jxcore-log: 
,09-13 08:54:56.077  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.077  3939  3989 I jxcore-log: 
,09-13 08:54:56.078  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.078  3939  3989 I jxcore-log: 
,09-13 08:54:56.080  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.080  3939  3989 I jxcore-log: 
,09-13 08:54:56.081  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.081  3939  3989 I jxcore-log: 
,09-13 08:54:56.082  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.082  3939  3989 I jxcore-log: 
,09-13 08:54:56.084  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.084  3939  3989 I jxcore-log: 
09-13 08:54:56.085  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.085  3939  3989 I jxcore-log: 
,09-13 08:54:56.086  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.086  3939  3989 I jxcore-log: 
,09-13 08:54:56.087  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.087  3939  3989 I jxcore-log: 
,09-13 08:54:56.089  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.089  3939  3989 I jxcore-log: 
,09-13 08:54:56.094  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.094  3939  3989 I jxcore-log: 
,09-13 08:54:56.096  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.096  3939  3989 I jxcore-log: 
,09-13 08:54:56.097  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.097  3939  3989 I jxcore-log: 
,09-13 08:54:56.098  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.098  3939  3989 I jxcore-log: 
,09-13 08:54:56.099  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.099  3939  3989 I jxcore-log: 
,09-13 08:54:56.100  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.100  3939  3989 I jxcore-log: 
,09-13 08:54:56.102  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.102  3939  3989 I jxcore-log: 
,09-13 08:54:56.103  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.103  3939  3989 I jxcore-log: 
,09-13 08:54:56.105  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.105  3939  3989 I jxcore-log: 
,09-13 08:54:56.106  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.106  3939  3989 I jxcore-log: 
,09-13 08:54:56.107  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.107  3939  3989 I jxcore-log: 
09-13 08:54:56.109  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.109  3939  3989 I jxcore-log: 
09-13 08:54:56.110  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.110  3939  3989 I jxcore-log: 
,09-13 08:54:56.111  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.111  3939  3989 I jxcore-log: 
09-13 08:54:56.112  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.112  3939  3989 I jxcore-log: 
,09-13 08:54:56.114  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.114  3939  3989 I jxcore-log: 
,09-13 08:54:56.116  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.116  3939  3989 I jxcore-log: 
,09-13 08:54:56.117  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.117  3939  3989 I jxcore-log: 
,09-13 08:54:56.119  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.119  3939  3989 I jxcore-log: 
,09-13 08:54:56.120  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.120  3939  3989 I jxcore-log: 
,09-13 08:54:56.121  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.121  3939  3989 I jxcore-log: 
,09-13 08:54:56.122  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.122  3939  3989 I jxcore-log: 
09-13 08:54:56.123  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:56.123  3939  3989 I jxcore-log: 
,09-13 08:54:56.125  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:56.125  3939  3989 I jxcore-log: 
,09-13 08:54:56.213  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.213  3939  3989 I jxcore-log: 
,09-13 08:54:56.215  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.215  3939  3989 I jxcore-log: 
,09-13 08:54:56.217  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.217  3939  3989 I jxcore-log: 
,09-13 08:54:56.218  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.218  3939  3989 I jxcore-log: 
,09-13 08:54:56.219  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.219  3939  3989 I jxcore-log: 
,09-13 08:54:56.221  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.221  3939  3989 I jxcore-log: 
,09-13 08:54:56.222  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.222  3939  3989 I jxcore-log: 
09-13 08:54:56.223  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.223  3939  3989 I jxcore-log: 
,09-13 08:54:56.224  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.224  3939  3989 I jxcore-log: 
,09-13 08:54:56.225  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.225  3939  3989 I jxcore-log: 
,09-13 08:54:56.226  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.226  3939  3989 I jxcore-log: 
,09-13 08:54:56.229  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.229  3939  3989 I jxcore-log: 
,09-13 08:54:56.230  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.230  3939  3989 I jxcore-log: 
,09-13 08:54:56.231  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.231  3939  3989 I jxcore-log: 
,09-13 08:54:56.233  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.233  3939  3989 I jxcore-log: 
,09-13 08:54:56.238  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.238  3939  3989 I jxcore-log: 
,09-13 08:54:56.239  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.239  3939  3989 I jxcore-log: 
,09-13 08:54:56.240  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.240  3939  3989 I jxcore-log: 
09-13 08:54:56.241  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.241  3939  3989 I jxcore-log: 
,09-13 08:54:56.242  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.242  3939  3989 I jxcore-log: 
,09-13 08:54:56.243  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.243  3939  3989 I jxcore-log: 
09-13 08:54:56.245  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.245  3939  3989 I jxcore-log: 
,09-13 08:54:56.246  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.246  3939  3989 I jxcore-log: 
,09-13 08:54:56.247  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.247  3939  3989 I jxcore-log: 
09-13 08:54:56.248  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.248  3939  3989 I jxcore-log: 
,09-13 08:54:56.249  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.249  3939  3989 I jxcore-log: 
,09-13 08:54:56.250  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.250  3939  3989 I jxcore-log: 
09-13 08:54:56.252  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.252  3939  3989 I jxcore-log: 
,09-13 08:54:56.253  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.253  3939  3989 I jxcore-log: 
,09-13 08:54:56.254  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.254  3939  3989 I jxcore-log: 
09-13 08:54:56.255  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.255  3939  3989 I jxcore-log: 
,09-13 08:54:56.256  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.256  3939  3989 I jxcore-log: 
,09-13 08:54:56.257  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.257  3939  3989 I jxcore-log: 
09-13 08:54:56.258  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.258  3939  3989 I jxcore-log: 
,09-13 08:54:56.259  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.259  3939  3989 I jxcore-log: 
09-13 08:54:56.260  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.260  3939  3989 I jxcore-log: 
,09-13 08:54:56.261  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.261  3939  3989 I jxcore-log: 
09-13 08:54:56.262  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.262  3939  3989 I jxcore-log: 
,09-13 08:54:56.267  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.267  3939  3989 I jxcore-log: 
,09-13 08:54:56.268  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.268  3939  3989 I jxcore-log: 
,09-13 08:54:56.269  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.269  3939  3989 I jxcore-log: 
09-13 08:54:56.270  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.270  3939  3989 I jxcore-log: 
,09-13 08:54:56.271  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.271  3939  3989 I jxcore-log: 
,09-13 08:54:56.272  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.272  3939  3989 I jxcore-log: 
,09-13 08:54:56.274  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.274  3939  3989 I jxcore-log: 
09-13 08:54:56.275  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.275  3939  3989 I jxcore-log: 
,09-13 08:54:56.276  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.276  3939  3989 I jxcore-log: 
,09-13 08:54:56.277  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.277  3939  3989 I jxcore-log: 
09-13 08:54:56.278  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:56.278  3939  3989 I jxcore-log: 
,09-13 08:54:56.279  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:56.279  3939  3989 I jxcore-log: 
,09-13 08:54:56.282  3939  3989 I jxcore-log: ok 28 native server is nulled out
09-13 08:54:56.282  3939  3989 I jxcore-log: 
,09-13 08:54:56.283  3939  3989 I jxcore-log: ok 29 native server should be closed
09-13 08:54:56.283  3939  3989 I jxcore-log: 
09-13 08:54:56.283  3939  3989 I jxcore-log: ok 30 incoming has been removed
09-13 08:54:56.283  3939  3989 I jxcore-log: 
09-13 08:54:56.284  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.284  3939  3989 I jxcore-log: 
,09-13 08:54:56.285  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.285  3939  3989 I jxcore-log: 
09-13 08:54:56.285  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.285  3939  3989 I jxcore-log: 
,09-13 08:54:56.286  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.286  3939  3989 I jxcore-log: 
09-13 08:54:56.287  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.287  3939  3989 I jxcore-log: 
,09-13 08:54:56.287  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.287  3939  3989 I jxcore-log: 
09-13 08:54:56.287  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.287  3939  3989 I jxcore-log: 
09-13 08:54:56.288  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.288  3939  3989 I jxcore-log: 
,09-13 08:54:56.288  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.288  3939  3989 I jxcore-log: 
09-13 08:54:56.289  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:56.289  3939  3989 I jxcore-log: 
,09-13 08:54:56.397  3939  3989 I jxcore-log: # teardown
09-13 08:54:56.397  3939  3989 I jxcore-log: 
,09-13 08:54:56.608  3939  3989 I jxcore-log: # setup
09-13 08:54:56.608  3939  3989 I jxcore-log: 
,09-13 08:54:57.798  3939  3989 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-13 08:54:57.798  3939  3989 I jxcore-log: 
,09-13 08:54:58.624  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:58.624  3939  3989 I jxcore-log: 
,09-13 08:54:58.630  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 47153
09-13 08:54:58.630  3939  3989 I jxcore-log: 
,09-13 08:54:58.643  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:58.643  3939  3989 I jxcore-log: 
,09-13 08:54:58.644  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:58.644  3939  3989 I jxcore-log: 
,09-13 08:54:58.646  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:58.646  3939  3989 I jxcore-log: 
,09-13 08:54:58.653  3939  3989 I jxcore-log: ok 31 we should not have gotten an error
09-13 08:54:58.653  3939  3989 I jxcore-log: 
,09-13 08:54:58.660  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:58.660  3939  3989 I jxcore-log: 
,09-13 08:54:58.662  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:58.662  3939  3989 I jxcore-log: 
,09-13 08:54:58.669  3939  3989 I jxcore-log: ok 32 Buffers are identical
09-13 08:54:58.669  3939  3989 I jxcore-log: 
,09-13 08:54:58.670  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:58.670  3939  3989 I jxcore-log: 
,09-13 08:54:58.673  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:58.673  3939  3989 I jxcore-log: 
,09-13 08:54:58.689  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:58.689  3939  3989 I jxcore-log: 
,09-13 08:54:58.690  3939  3989 I jxcore-log: ok 33 server should be fine
09-13 08:54:58.690  3939  3989 I jxcore-log: 
,09-13 08:54:58.690  3939  3989 I jxcore-log: ok 34 server should be open
09-13 08:54:58.690  3939  3989 I jxcore-log: 
09-13 08:54:58.691  3939  3989 I jxcore-log: ok 35 incoming has been removed
09-13 08:54:58.691  3939  3989 I jxcore-log: 
,09-13 08:54:58.691  3939  3989 I jxcore-log: ok 36 The mux object should be closed
09-13 08:54:58.691  3939  3989 I jxcore-log: 
09-13 08:54:58.692  3939  3989 I jxcore-log: ok 37 The mux stream should be closed
09-13 08:54:58.692  3939  3989 I jxcore-log: 
,09-13 08:54:58.696  3939  3989 I jxcore-log: # teardown
09-13 08:54:58.696  3939  3989 I jxcore-log: 
,09-13 08:54:58.900  3939  3989 I jxcore-log: # setup
09-13 08:54:58.900  3939  3989 I jxcore-log: 
,09-13 08:54:59.016  3939  3989 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-13 08:54:59.016  3939  3989 I jxcore-log: 
,09-13 08:54:59.110  3939  3989 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 08:54:59.110  3939  3989 I jxcore-log: 
,09-13 08:54:59.119  3939  3989 I jxcore-log: DEBUG createNativeListener: listening 42933
09-13 08:54:59.119  3939  3989 I jxcore-log: 
,09-13 08:54:59.127  3939  3989 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 08:54:59.127  3939  3989 I jxcore-log: 
,09-13 08:54:59.128  3939  3989 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 08:54:59.128  3939  3989 I jxcore-log: 
,09-13 08:54:59.130  3939  3989 I jxcore-log: DEBUG createNativeListener: new mux
09-13 08:54:59.130  3939  3989 I jxcore-log: 
,09-13 08:54:59.136  3939  3989 I jxcore-log: ok 38 we should not have gotten an error
09-13 08:54:59.136  3939  3989 I jxcore-log: 
,09-13 08:54:59.143  3939  3989 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 08:54:59.143  3939  3989 I jxcore-log: 
,09-13 08:54:59.148  3939  3989 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 08:54:59.148  3939  3989 I jxcore-log: 
,09-13 08:54:59.162  3939  3989 I jxcore-log: ok 39 Buffers are identical
09-13 08:54:59.162  3939  3989 I jxcore-log: 
,09-13 08:54:59.173  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-13 08:54:59.173  3939  3989 I jxcore-log: 
,09-13 08:54:59.176  3939  3989 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 08:54:59.176  3939  3989 I jxcore-log: 
,09-13 08:54:59.181  3939  3989 I jxcore-log: DEBUG createNativeListener: mux close
09-13 08:54:59.181  3939  3989 I jxcore-log: 
,09-13 08:54:59.188  3939  3989 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 08:54:59.188  3939  3989 I jxcore-log: 
,09-13 08:54:59.189  3939  3989 I jxcore-log: ok 40 server should be fine
09-13 08:54:59.189  3939  3989 I jxcore-log: 
,09-13 08:54:59.189  3939  3989 I jxcore-log: ok 41 server should be open
09-13 08:54:59.189  3939  3989 I jxcore-log: 
,09-13 08:54:59.190  3939  3989 I jxcore-log: ok 42 incoming has been removed
09-13 08:54:59.190  3939  3989 I jxcore-log: 
,09-13 08:54:59.190  3939  3989 I jxcore-log: ok 43 The mux object should be closed
09-13 08:54:59.190  3939  3989 I jxcore-log: 
,09-13 08:54:59.190  3939  3989 I jxcore-log: ok 44 The mux stream should be closed
09-13 08:54:59.190  3939  3989 I jxcore-log: 
,09-13 08:54:59.197  3939  3989 I jxcore-log: # teardown
09-13 08:54:59.197  3939  3989 I jxcore-log: 
,09-13 08:54:59.344  3939  3989 I jxcore-log: # setup
09-13 08:54:59.344  3939  3989 I jxcore-log: 
,09-13 08:54:59.434  3939  3989 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
09-13 08:54:59.434  3939  3989 I jxcore-log: 
,09-13 08:54:59.634  3939  3989 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
09-13 08:54:59.634  3939  3989 I jxcore-log: 
,09-13 08:54:59.635  3939  3989 I jxcore-log: ok 45 Got right error
09-13 08:54:59.635  3939  3989 I jxcore-log: 
,09-13 08:54:59.640  3939  3989 I jxcore-log: # teardown
09-13 08:54:59.640  3939  3989 I jxcore-log: 
,09-13 08:54:59.791  3939  3989 I jxcore-log: # setup
09-13 08:54:59.791  3939  3989 I jxcore-log: 
,09-13 08:54:59.873  3939  3989 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
09-13 08:54:59.873  3939  3989 I jxcore-log: 
,09-13 08:55:00.053  3939  3989 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
09-13 08:55:00.053  3939  3989 I jxcore-log: 
,09-13 08:55:00.055  3939  3989 I jxcore-log: ok 46 Got socket hang up
09-13 08:55:00.055  3939  3989 I jxcore-log: 
,09-13 08:55:00.059  3939  3989 I jxcore-log: # teardown
09-13 08:55:00.059  3939  3989 I jxcore-log: 
,09-13 08:55:00.153  3939  3989 I jxcore-log: # setup
09-13 08:55:00.153  3939  3989 I jxcore-log: 
,09-13 08:55:00.209  3939  3989 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
09-13 08:55:00.209  3939  3989 I jxcore-log: 
,09-13 08:55:00.409  3939  3989 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq []
09-13 08:55:00.409  3939  3989 I jxcore-log: 
,09-13 08:55:00.410  3939  3989 I jxcore-log: ok 47 Got 500 as expected
09-13 08:55:00.410  3939  3989 I jxcore-log: 
,09-13 08:55:00.413  3939  3989 I jxcore-log: # teardown
09-13 08:55:00.413  3939  3989 I jxcore-log: 
,09-13 08:55:00.580  3939  3989 I jxcore-log: # setup
09-13 08:55:00.580  3939  3989 I jxcore-log: 
,09-13 08:55:00.649  3939  3989 I jxcore-log: # 15. #_doImmediateSeqUpdate - create new seq doc
09-13 08:55:00.649  3939  3989 I jxcore-log: 
,09-13 08:55:02.903  3939  3989 I jxcore-log: ok 48 should be equal
09-13 08:55:02.903  3939  3989 I jxcore-log: 
,09-13 08:55:02.904  3939  3989 I jxcore-log: ok 49 revs are equal
09-13 08:55:02.904  3939  3989 I jxcore-log: 
,09-13 08:55:02.908  3939  3989 I jxcore-log: # teardown
09-13 08:55:02.908  3939  3989 I jxcore-log: 
,09-13 08:55:04.412  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:55:04.416  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:55:04.444  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:55:04.445  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 08:55:04.445  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:55:04.445  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:55:04.467  3702  4873 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 08:55:04.467  3702  4873 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at blb.a(PG:3937)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at czp.a(PG:18188)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:55:04.467  3702  4873 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	... 12 more
09-13 08:55:04.467  3702  4873 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at fal.a(PG:38)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:55:04.467  3702  4873 E HttpOperation: 	... 14 more
,09-13 08:55:04.511  1500  2066 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:55:04.511  1500  2066 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 08:55:04.511  1500  2066 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:55:04.511  1500  2066 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:55:04.550  3702  4873 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 08:55:04.550  3702  4873 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at hec.a(PG:42)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at hee.a(PG:102)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at czr.a(PG:65)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at kka.a(PG:108)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at czp.a(PG:19176)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:55:04.550  3702  4873 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	... 15 more
09-13 08:55:04.550  3702  4873 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at fal.a(PG:38)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:55:04.550  3702  4873 E HttpOperation: 	... 17 more
,09-13 08:55:04.551  3702  4873 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 08:55:04.551  3702  4873 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at hec.a(PG:42)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at hee.a(PG:102)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at czr.a(PG:65)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at kka.a(PG:108)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	... 15 more
09-13 08:55:04.551  3702  4873 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at fal.a(PG:38)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 08:55:04.551  3702  4873 E ExperimentLoader: 	... 17 more
,09-13 08:55:04.638   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 440062, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:55:10.231  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:55:10.242  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:55:10.245  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:55:10.304  1500  2066 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 08:55:10.305  1500  2066 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 08:55:10.305  1500  2066 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:55:10.305  1500  2066 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:55:10.359  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 08:55:10.360  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 08:55:10.360  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-13 08:55:40.514  4837  4877 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 08:55:40.571  4837  4878 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 08:55:40.588  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:55:40.594  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:55:40.636  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 08:55:40.637  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 08:55:40.637  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:55:40.637  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:55:40.683  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:55:40.691  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:55:40.738  1500  3132 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 08:55:40.738  1500  3132 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 08:55:40.738  1500  3132 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:55:40.739  1500  3132 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:55:40.774  4837  4878 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 08:55:40.776  4837  4877 E BooksSync: Soft error
09-13 08:55:40.776  4837  4877 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:55:40.776  4837  4877 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 08:55:40.777  4837  4877 E BooksSync: Sync error
09-13 08:55:40.777  4837  4877 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 08:55:40.777  4837  4877 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 08:55:40.777  4837  4877 I BooksSync: Finished books sync
,09-13 08:55:40.792   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 503843, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:56:36.195  4812  4881 V KeepSync: Connecting to GoogleApiClient
,09-13 08:56:36.196   872  1972 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 08:56:36.259  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:56:36.265  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:56:36.313  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 08:56:36.314  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 08:56:36.314  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:56:36.314  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:56:36.335  1740  4882 V BaseAuthAsyncOperation: access token request failed
,09-13 08:56:36.337  4812  4881 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 08:56:36.392  1500  2066 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 08:56:36.392  1500  2066 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 08:56:36.392  1500  2066 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:56:36.393  1500  2066 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:56:36.413  4812  4881 E KeepSync: IOException
09-13 08:56:36.413  4812  4881 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 08:56:36.413  4812  4881 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 08:56:36.413  4812  4881 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 08:56:36.413  4812  4881 E KeepSync: 	... 10 more
09-13 08:56:36.413  4812  4881 W KeepSync: Sync result 2
,09-13 08:56:36.426   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 559525, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:57:12.951  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:57:12.956  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:57:12.985  1500  3132 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:57:12.986  1500  3132 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 08:57:12.986  1500  3132 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:57:12.986  1500  3132 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:57:13.004  3702  4885 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 08:57:13.004  3702  4885 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at blb.a(PG:3937)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at czp.a(PG:18188)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:57:13.004  3702  4885 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	... 12 more
09-13 08:57:13.004  3702  4885 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at fal.a(PG:38)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:57:13.004  3702  4885 E HttpOperation: 	... 14 more
,09-13 08:57:13.072  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 08:57:13.072  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 08:57:13.073  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 08:57:13.073  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:57:13.093  3702  4885 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 08:57:13.093  3702  4885 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at jdm.a(PG:82)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at jcs.o(PG:406)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at jcn.a(PG:1379)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at jcs.i(PG:143)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at hec.a(PG:42)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at hee.a(PG:102)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at czr.a(PG:65)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at kka.a(PG:108)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at czp.a(PG:19176)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at czp.a(PG:9081)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at czq.run(PG:1686)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:57:13.093  3702  4885 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at jdj.a(PG:4091)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at jdj.a(PG:1125)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at jdm.a(PG:77)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	... 15 more
09-13 08:57:13.093  3702  4885 E HttpOperation: Caused by: faj: BadAuthentication
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at fal.a(PG:38)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	at jdj.a(PG:4089)
09-13 08:57:13.093  3702  4885 E HttpOperation: 	... 17 more
,09-13 08:57:13.094  3702  4885 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 08:57:13.094  3702  4885 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at hec.a(PG:42)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at hee.a(PG:102)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at czr.a(PG:65)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at kka.a(PG:108)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	... 15 more
09-13 08:57:13.094  3702  4885 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at fal.a(PG:38)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 08:57:13.094  3702  4885 E ExperimentLoader: 	... 17 more
,09-13 08:57:13.217   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 595967, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-13 08:58:07.609  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:58:07.632  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:58:07.641  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 08:58:07.737  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-13 08:58:07.737  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-13 08:58:07.738  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 08:58:07.738  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 08:58:07.789  1500  3133 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 08:58:07.789  1500  3133 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 08:58:07.789  1500  3133 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 08:58:07.789  1500  3133 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-13 08:58:07.789  1500  3133 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-13 08:58:07.789  1500  3133 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-13 08:58:07.789  1500  3133 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 08:58:07.804  4694  4723 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 08:58:07.804  4694  4723 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-13 08:58:07.804  4694  4723 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-13 08:58:07.804  4694  4723 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-13 08:58:07.804  4694  4723 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-13 08:58:07.804  4694  4723 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-13 08:58:07.804  4694  4723 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 09:02:26.706   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=910131, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:02:35.719   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=919144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:02:51.773   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=935197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:03:00.786   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=944210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:03:16.839   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=960264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:03:25.839   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=969263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:03:41.959   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=985384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:03:50.946   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=994370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:04:07.026   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1010450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:04:16.013   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1019437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:04:32.093   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1035517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:04:41.093   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1044517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:04:57.160   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1060584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:05:06.159   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1069584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:05:22.226   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1085650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:05:31.239   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1094663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:05:34.410   872   882 I ActivityManager: Start proc 4916:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-13 09:05:34.483  4916  4916 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-13 09:05:34.513  4916  4916 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-13 09:05:34.513  4916  4916 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 09:05:34.513  4916  4916 I GAv4    :   adb logcat -s GAv4
,09-13 09:05:34.529  4916  4916 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 09:05:34.536  4916  4916 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 09:05:34.547  4916  4931 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 09:05:34.645   872  3377 I ActivityManager: Killing 4174:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,09-13 09:05:46.182  4694  4694 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-13 09:05:46.212  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:05:46.224  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:05:46.227  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:05:46.274  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 09:05:46.274  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-13 09:05:46.274  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 09:05:46.275  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:05:46.309  4694  4694 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-13 09:05:46.320  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:05:46.365  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 09:05:46.365  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 09:05:46.366  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:05:46.366  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:05:46.424  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:05:46.499  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 09:05:46.500  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 09:05:46.500  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 09:05:46.500  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:05:46.559  4694  4694 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-13 09:05:46.899  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:05:46.937  1500  3133 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 09:05:46.938  1500  3133 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 09:05:46.938  1500  3133 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 09:05:46.938  1500  3133 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:05:46.977  4694  4694 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-13 09:05:46.977  4694  4694 D Finsky  : [1] WearSupportService.startHygiene: disabled
09-13 09:05:46.978  4694  4694 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-13 09:05:46.986  4694  4803 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-13 09:05:46.988  4694  4694 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,09-13 09:06:01.902  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:06:01.911  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:06:01.917  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:06:01.964  1500  2207 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 09:06:01.964  1500  2207 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 09:06:01.964  1500  2207 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 09:06:01.965  1500  2207 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:06:02.018  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 09:06:02.019  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 09:06:02.021  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-13 09:06:12.346   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1135770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:06:21.359   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1144783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:06:22.325  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:06:22.336  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:06:22.341  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:06:22.373  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 09:06:22.373  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 09:06:22.373  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 09:06:22.374  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:06:22.405  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 09:06:22.405  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 09:06:22.406  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-13 09:06:37.479   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1160904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:06:42.561  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:06:42.569  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:06:42.572  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:06:42.604  1500  3132 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 09:06:42.604  1500  3132 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 09:06:42.604  1500  3132 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:06:42.604  1500  3132 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:06:42.623  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 09:06:42.623  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 09:06:42.623  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 09:06:46.466   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1169890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:07:02.546   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1185970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:07:02.856  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:07:02.864  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:07:02.866  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:07:02.920  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 09:07:02.920  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 09:07:02.920  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:07:02.920  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:07:02.965  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 09:07:02.965  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 09:07:02.966  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 09:07:11.533   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1194957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:07:20.360   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1203784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:07:23.229  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:07:23.240  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:07:23.244  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:07:23.304  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 09:07:23.305  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 09:07:23.305  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 09:07:23.306  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:07:23.362  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 09:07:23.363  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 09:07:23.367  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-13 09:07:35.393   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,09-13 09:07:36.599   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1220024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:07:43.587  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:07:43.595  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:07:43.599  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 09:07:43.636  1500  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 09:07:43.636  1500  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 09:07:43.637  1500  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 09:07:43.637  1500  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 09:07:43.675  4694  4694 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 09:07:43.676  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 09:07:43.678  4694  4694 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-13 09:07:45.426   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1228850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:08:01.693   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1245117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:08:10.519   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1253944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:08:26.813   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1270237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:08:35.639   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1279063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:08:51.880   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1295304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:09:00.706   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1304130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:09:16.946   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:09:25.772   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1329197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:09:42.053   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1345477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:09:50.866   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1354290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:10:07.132   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1370556, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:10:15.959   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1379384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:10:32.213   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1395637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:10:41.026   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1404450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:10:57.306   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1420731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:11:06.119   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1429544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:11:22.373   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1445797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:11:31.186   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1454610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:11:47.452   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1470876, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:11:56.332   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1479756, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:12:12.573   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1495997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 09:12:29.053   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1512477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 09:12:37.640   872  4383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1521064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms),09-13 09:12:46.243  4954  4954 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 09:12:46.247  4954  4954 D AndroidRuntime: CheckJNI is OFF
09-13 09:12:46.283  4954  4954 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 09:12:46.325  4954  4954 I Radio-JNI: register_android_hardware_Radio DONE
09-13 09:12:46.346  4954  4954 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-13 09:12:46.359   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-13 09:12:46.360   872   885 I ActivityManager: Killing 3939:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-13 09:12:46.487   872  1294 W InputDispatcher: channel 'c70dae8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-13 09:12:46.487   872  1294 E InputDispatcher: channel 'c70dae8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
09-13 09:12:46.501   872  2001 I WindowState: WIN DEATH: Window{c70dae8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 09:12:46.502   872  2001 W InputDispatcher: Attempted to unregister already unregistered input channel 'c70dae8 com.test.thalitest/com.test.thalitest.MainActivity (server)'
09-13 09:12:46.502   872  1304 D WifiService: Client connection lost with reason: 4
09-13 09:12:46.502   872  1978 D GraphicsStats: Buffer count: 2
09-13 09:12:46.519   872   896 W PackageSettings: Skipping PackageSetting{d948587 com.example.hello/10273} due to missing metadata
09-13 09:12:46.547   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-13 09:12:46.547   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-13 09:12:46.548   872   896 I art     : Starting a blocking GC Explicit
09-13 09:12:46.553   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-13 09:12:46.553   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 09:12:46.553   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:12:46.553   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:12:46.553   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 09:12:46.553   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 09:12:46.554   872   885 I ActivityManager:   Force finishing activity ActivityRecord{894ee9 u0 com.test.thalitest/.MainActivity t4}
09-13 09:12:46.594   872   896 I art     : Explicit concurrent mark sweep GC freed 50694(4MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 760us total 44.111ms
09-13 09:12:46.612   872   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-13 09:12:46.618  4954  4954 I art     : System.exit called, status: 0
09-13 09:12:46.618  4954  4954 I AndroidRuntime: VM exiting with result code 0.
09-13 09:12:46.627   872   896 I ActivityManager: Start proc 4965:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-13 09:12:46.628   872   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-13 09:12:46.638   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-13 09:12:46.642  4327  4327 D BluetoothMapAppObserver: onReceive
09-13 09:12:46.642  4327  4327 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-13 09:12:46.643   872  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 09:12:46.644  1868  1868 I Keyboard.Facilitator: resetDictionaries() : en_US
09-13 09:12:46.655  2129  2307 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 09:12:46.658  3806  3806 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-13 09:12:46.684  1868  4971 I Keyboard.Facilitator.DecoderInitializer: run()
09-13 09:12:46.698  1960  1960 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-13 09:12:46.708  1868  4971 I Decoder : createOrResetDecoder
09-13 09:12:46.710   872  2001 I ActivityManager: Start proc 4980:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-13 09:12:46.748   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 09:12:46.750  4676  4691 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
09-13 09:12:46.751  4676  4691 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-13 09:12:46.751  4676  4691 E AndroidRuntime: Process: android.process.acore, PID: 4676
09-13 09:12:46.751  4676  4691 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:12:46.751  4676  4691 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: Can't write: system_app_crash
09-13 09:12:46.755   872  4995 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:12:46.755   872  4995 E DropBoxManagerService: 	... 5 more
09-13 09:12:46.757  1500  1500 I ConfigService: onCreate
09-13 09:12:46.759  4676  4983 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 09:12:46.760   872  1378 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3939 uid 10000
09-13 09:12:46.762  1868  1868 I Keyboard.Facilitator: onFinishInput()
09-13 09:12:46.769  4980  4980 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-13 09:12:46.774  1500  4996 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-13 09:12:46.774  1500  4996 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-13 09:12:46.782  1500  4996 W SQLiteOpenHelper: Opened config.db in read-only mode
09-13 09:12:46.781  4676  4983 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-13 09:12:46.785  4676  4983 I Process : Sending signal. PID: 4676 SIG: 9
09-13 09:12:46.791   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-13 09:12:46.791  1980  2067 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-13 09:12:46.791   872   884 E PackageManager: Failed to write settings, restoring backup
09-13 09:12:46.791   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 09:12:46.791   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 09:12:46.791   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 09:12:46.791   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 09:12:46.791   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 09:12:46.791   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:12:46.791   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:12:46.791   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 09:12:46.793   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-13 09:12:46.793   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 09:12:46.793   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:12:46.793   872   885 E DropBoxManagerService: 	... 13 more
09-13 09:12:46.804   872  3378 I ActivityManager: Start proc 4998:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-13 09:12:46.804  1980  2067 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 09:12:46.804  1980  2067 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1980
09-13 09:12:46.804  1980  2067 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:12:46.804  1980  2067 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 09:12:46.805   872  1378 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 09:12:46.806   872  5005 E DropBoxManagerService: Can't write: system_app_crash
09-13 09:12:46.806   872  5005 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:12:46.806   872  5005 E DropBoxManagerService: 	... 5 more
09-13 09:12:46.807   279   279 E lowmemorykiller: Error writing /proc/4676/oom_score_adj; errno=22
09-13 09:12:46.818   279   279 E lowmemorykiller: Error writing /proc/4676/oom_score_adj; errno=22
09-13 09:12:46.811  1980  2067 I Process : Sending signal. PID: 1980 SIG: 9
09-13 09:12:46.829  1868  4971 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-13 09:12:46.838   872  3377 I ActivityManager: Killing 4630:com.google.android.partnersetup/u0a16 (adj 15): empty #17
09-13 09:12:46.858  1500  1500 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-13 09:12:46.859  1500  1500 D AndroidRuntime: Shutting down VM
09-13 09:12:46.860  1500  1500 E AndroidRuntime: FATAL EXCEPTION: main
09-13 09:12:46.860  1500  1500 E AndroidRuntime: Process: com.google.process.gapps, PID: 1500
09-13 09:12:46.860  1500  1500 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 09:12:46.860  1500  1500 E AndroidRuntime: 	... 8 more
09-13 09:12:46.876  1868  4971 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-13 09:12:46.878  1868  4971 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-13 09:12:46.878  1868  4971 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-13 09:12:46.880  1868  4971 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-13 09:12:46.880  1868  4971 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-13 09:12:46.881  1868  4971 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-13 09:12:46.881  1868  4971 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-13 09:12:46.882  1868  4971 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-13 09:12:46.882  1868  4971 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 09:12:46.882  1868  4971 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-13 09:12:46.883  1868  4971 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 09:12:46.883  1868  4971 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 09:12:46.883  1868  4971 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-13 09:12:46.912   872  1972 D GraphicsStats: Buffer count: 1
09-13 09:12:46.912   872  3378 I WindowState: WIN DEATH: Window{814ca7a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-13 09:12:46.924   872  1972 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1980) has died
09-13 09:12:46.924   872  1972 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-13 09:12:46.926   872  1972 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-13 09:12:46.944   872   885 I ActivityManager: Start proc 5014:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 09:12:46.948  1500  1500 I Process : Sending signal. PID: 1500 SIG: 9
09-13 09:12:46.948   872  1976 I ActivityManager: Process android.process.acore (pid 4676) has died
09-13 09:12:46.949   872  1976 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-13 09:12:46.950   872  5020 E DropBoxManagerService: Can't write: system_app_crash
09-13 09:12:46.950   872  5020 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:12:46.950   872  5020 E DropBoxManagerService: 	... 5 more
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:12:47.000  5014  5014 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 09:12:47.000  5014  5014 D AndroidRuntime: Shutting down VM
09-13 09:12:47.008  5014  5014 E AndroidRuntime: FATAL EXCEPTION: main
09-13 09:12:47.008  5014  5014 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5014
09-13 09:12:47.008  5014  5014 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 09:12:47.008  5014  5014 E AndroidRuntime: 	... 10 more
09-13 09:12:47.009  1740  5029 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
09-13 09:12:47.009  1740  5029 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@526b088
09-13 09:12:47.009   872  1959 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 09:12:47.011   872   882 I ActivityManager: Process com.google.process.gapps (pid 1500) early provider death
09-13 09:12:47.011  5014  5014 I Process : Sending signal. PID: 5014 SIG: 9
09-13 09:12:47.012   872  5030 E DropBoxManagerService: Can't write: system_app_crash
09-13 09:12:47.012   872  5030 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 09:12:47.012   872  5030 E DropBoxManagerService: 	... 5 more
09-13 09:12:47.016   872  1304 D WifiService: Client connection lost with reason: 4
09-13 09:12:47.022   872   882 I ActivityManager: Process com.google.process.gapps (pid 1500) has died
09-13 09:12:47.022   872   882 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-13 09:12:47.023   872   882 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-13 09:12:47.023   872   882 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-13 09:12:47.027   872  1378 W ActivityManager: Spurious death for ProcessRecord{82111e0 0:com.google.process.gapps/u0a11}, curProc for 1500: null
09-13 09:12:47.032  1740  1740 W RocketImpressions: ClearcutLogger connection suspended: 1
09-13 09:12:47.039   872  1976 I ActivityManager: Start proc 5031:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
09-13 09:12:47.042   872  3378 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5014) has died
09-13 09:12:47.044   872  3378 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-13 09:12:47.060   872   885 I ActivityManager: Start proc 5044:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 09:12:47.086  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-13 09:12:47.087  1740  1740 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-13 09:12:47.089  5031  5031 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-13 09:12:47.090  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-13 09:12:47.090  1740  1740 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-13 09:12:47.101  1740  5058 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-13 09:12:47.105  2043  5057 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-13 09:12:47.105  5031  5031 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 09:12:47.118  5044  5044 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 09:12:47.118  5044  5044 D AndroidRuntime: Shutting down VM
09-13 09:12:47.122   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
