#### Test 84618637840569c_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-09 13:04:25.252   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-09 13:04:25.895  3947  3947 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 13:04:25.899  3947  3947 D AndroidRuntime: CheckJNI is OFF
09-09 13:04:25.935  3947  3947 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 13:04:25.978  3947  3947 I Radio-JNI: register_android_hardware_Radio DONE
09-09 13:04:25.999  3947  3947 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 13:04:26.004   872  2013 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 13:04:26.046  2034  3934 W SearchService: Abort, client detached.
09-09 13:04:26.050  3947  3947 D AndroidRuntime: Shutting down VM
09-09 13:04:26.061  2034  2350 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@eb0d98d
09-09 13:04:26.062  2034  2356 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 13:04:26.063  2034  2034 I HotwordDetector: Closing mic
09-09 13:04:26.071   872  2016 I ActivityManager: Start proc 3956:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 13:04:26.118   375  2358 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 13:04:26.123   375  2358 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 13:04:26.131   375  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 13:04:26.134  2034  2354 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 13:04:26.136  2034  2355 I MicroRecognitionRnrImpl: Detection finished
09-09 13:04:26.185  3956  3956 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 13:04:26.209  3956  3956 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 13:04:26.218  3956  3956 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 8201-8206)
09-09 13:04:26.218  3956  3956 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:04:26.231  3956  3956 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a5e4048}
09-09 13:04:26.231  3956  3956 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:04:26.232  3956  3956 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:04:26.237  3956  3956 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 13:04:26.238  3956  3956 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:04:26.254  3956  3956 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 13:04:26.263  3956  3956 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:04:26.263  3956  3956 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:04:26.263  3956  3956 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:04:26.263  3956  3956 I Adreno  : Build Date                       : 10/20/15
09-09 13:04:26.263  3956  3956 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:04:26.263  3956  3956 I Adreno  : Local Branch                     : M14
09-09 13:04:26.263  3956  3956 I Adreno  : Remote Branch                    : 
09-09 13:04:26.263  3956  3956 I Adreno  : Remote Branch                    : 
09-09 13:04:26.263  3956  3956 I Adreno  : Reconstruct Branch               : 
,09-09 13:04:26.327   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5404256:true
,09-09 13:04:26.356  3956  3956 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 13:04:26.367  3956  3956 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 13:04:26.429  3956  3995 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 13:04:26.440  3956  3981 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 13:04:26.485  3956  3995 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 13:04:26.535   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +483ms
,09-09 13:04:26.556  1887  1887 I Keyboard.Facilitator: onFinishInput()
,09-09 13:04:26.595  3956  3956 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3956
,09-09 13:04:26.694  3956  3956 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:04:26.866  3956  3997 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1679886032
,09-09 13:04:26.875  3956  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:04:26.875  3956  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:04:26.875  3956  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:04:26.875  3956  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:04:26.875  3956  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 13:04:26.875  3956  3997 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6ff7f added. We now have 1 listener(s)
,09-09 13:04:26.878  3956  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 13:04:26.879  3956  3997 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:04:26.879  3956  3997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:04:26.879  3956  3997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 13:04:26.884  3956  3997 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fb10aa added. We now have 1 listener(s)
,09-09 13:04:26.885  3956  3997 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:04:26.888   872  1315 D WifiService: New client listening to asynchronous messages
09-09 13:04:26.889  3956  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:04:26.890  3956  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 13:04:26.890  3956  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 13:04:26.890  3956  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:04:26.890  3956  3997 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 13:04:26.893  3956  3997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:04:26.893  3956  3997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 13:04:26.900  3956  3997 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 13:04:26.900  3956  3997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:04:26.900  3956  3997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:04:26.900  3956  3997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:04:26.900  3956  3997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:04:26.900  3956  3997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:04:26.900  3956  3997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:04:26.900  3956  3997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:04:26.900  3956  3997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:04:26.900  3956  3997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-09 13:04:26.900  3956  3997 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:04:26.902  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:04:26.903  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:04:26.905  3956  3997 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:04:26.924   872  1679 I ActivityManager: Killing 3201:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,09-09 13:04:26.932  3956  3956 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:04:26.960   872  1679 I ActivityManager: Killing 3161:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-09 13:04:27.911  3956  4005 W jxcore-log: Initializing JXcore engine
,09-09 13:04:27.911  3956  4005 W jxcore-log: JXcore engine is ready
,09-09 13:04:27.948  4005  4005 W Thread-361: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 13:04:27.948  4005  4005 W Thread-361: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11910]" dev="sockfs" ino=11910 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-09 13:04:27.948  4005  4005 W Thread-361: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 13:04:27.948  4005  4005 W Thread-361: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26155]" dev="sockfs" ino=26155 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 13:04:27.961  3956  4005 W jxcore-log: Starting JXcore engine
,09-09 13:04:28.042  3956  4005 W jxcore-log: Platform android
09-09 13:04:28.042  3956  4005 W jxcore-log: 
,09-09 13:04:28.042  3956  4005 W jxcore-log: Process ARCH arm
09-09 13:04:28.042  3956  4005 W jxcore-log: 
,09-09 13:04:28.257  3956  4005 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:04:28.257  3956  4005 I jxcore-log: 
09-09 13:04:28.257  3956  4005 W jxcore-log: JXcore engine is started
,09-09 13:04:28.266  3956  3997 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 13:04:28.272  3956  3956 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:04:28.286   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 13:04:31.683   872  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 13:04:36.295  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:04:36.299  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:04:36.300  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:04:36.317  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 13:04:36.317  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 13:04:36.317  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:04:36.317  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:04:36.329  3705  3705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 13:04:36.329  3705  3705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 13:04:36.329  3705  3705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-09 13:04:38.714  3348  4018 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:04:38.756  3348  4019 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:04:38.807  1514  3150 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 13:04:38.807  1514  3150 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:04:38.808  1514  3150 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:04:38.808  1514  3150 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:04:38.856  1514  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 13:04:38.857  1514  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:04:38.857  1514  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:04:38.857  1514  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:04:38.873  3348  4019 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:04:38.876  3348  4018 E BooksSync: Soft error
09-09 13:04:38.876  3348  4018 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:04:38.876  3348  4018 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:04:38.876  3348  4018 E BooksSync: Sync error
09-09 13:04:38.876  3348  4018 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:04:38.876  3348  4018 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:04:38.877  3348  4018 I BooksSync: Finished books sync
,09-09 13:04:38.882   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 130609, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:04:42.746  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:04:42.746  3956  4005 I jxcore-log: 
,09-09 13:04:42.750  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:04:42.750  3956  4005 I jxcore-log: 
,09-09 13:04:42.762  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:04:42.762  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:04:42.762  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:04:42.762  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:04:42.762  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:04:42.762  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:04:42.762  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:04:42.762  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:04:42.768  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:04:42.774  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:04:42.774  3956  4005 I jxcore-log: 
,09-09 13:04:42.782  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:04:42.782  3956  4005 I jxcore-log: 
,09-09 13:04:43.161  3956  4005 I jxcore-log: Running unit tests
09-09 13:04:43.161  3956  4005 I jxcore-log: 
,09-09 13:04:43.162  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:04:43.162  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ced3cc added. We now have 2 listener(s)
,09-09 13:04:43.163  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:04:43.163  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:04:43.164  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:04:43.164  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:04:43.164  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2608615 added. We now have 2 listener(s)
09-09 13:04:43.164  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:04:43.164  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:04:43.168  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:04:43.181  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:04:43.181  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:04:43.181  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:04:43.181  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:04:43.181  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:04:43.181  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:04:43.181  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:04:43.181  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:04:43.184  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:04:43.184  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:04:43.184  3956  4005 D executeNativeTests: Running unit tests
,09-09 13:04:43.191  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:04:43.198  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:04:43.246  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:04:43.246  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b added. We now have 3 listener(s)
,09-09 13:04:43.247  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:04:43.247  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:04:43.247  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:04:43.247  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:04:43.248  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 added. We now have 3 listener(s)
09-09 13:04:43.248  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:04:43.248  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:04:43.251  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:04:43.261  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:04:43.261  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:04:43.261  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:04:43.261  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:04:43.261  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:04:43.261  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:04:43.261  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:04:43.261  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:04:43.264  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:04:43.264  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:04:43.266  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:04:43.266  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:04:43.267  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:04:43.267  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:04:43.268  3956  4005 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 13:04:43.268  3956  4005 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 13:04:43.268  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 13:04:43.268  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:04:43.268  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:04:43.268  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:04:43.272  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:04:43.272  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:04:43.275  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:04:43.275  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:04:43.275  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:04:43.275  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:04:43.275  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:04:43.275  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:04:43.276  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b removed from the list
09-09 13:04:43.276  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:04:43.276  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 removed from the list
09-09 13:04:43.280  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:04:43.280  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:04:43.280  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:04:43.281  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:04:43.282  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:04:43.282  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:04:43.282  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:04:43.282  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:04:43.282  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:04:43.284  3956  4005 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 13:04:43.284  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:04:43.285  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:04:43.285  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:04:43.285  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:04:43.285  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:04:43.285  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:04:43.285  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:04:43.285  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:04:43.285  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:04:43.285  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:04:43.285  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:04:43.285  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:04:43.285  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:04:43.285  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:04:43.286  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:04:43.286  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:04:43.286  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:04:43.286  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list,
09-09 13:04:43.290  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:04:43.290  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-09 13:04:43.290  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:04:43.290  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:04:43.290  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-09 13:04:43.290  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:04:43.290  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:04:43.291  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-09 13:04:43.292  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:04:43.292  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:04:43.292  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-09 13:04:43.292  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:04:43.292  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:04:43.292  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:04:43.292  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:04:43.292  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:04:43.292  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:04:43.292  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:04:43.292  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:04:43.292  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:04:43.292  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:04:43.292  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:04:43.292  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:04:43.292  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:04:43.292  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:04:43.292  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:04:43.293  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:04:43.294  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:04:43.294  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:04:43.294  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:04:43.294  3956  4005 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:04:43.295  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:04:43.300  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:04:43.300  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:04:43.300  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:04:43.300  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:04:43.300  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:04:43.300  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:04:43.300  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:04:43.300  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:04:43.302  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:04:43.302  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:04:43.302  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:04:43.302  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:04:43.303  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:04:43.303  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:04:43.303  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:04:43.309  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:04:43.309  3956  4005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:04:43.309  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:04:43.310  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:04:43.316  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:04:43.318  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:04:43.318  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:04:43.321  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-09 13:04:43.323  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 13:04:43.323  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 13:04:43.323  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 13:04:43.324  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:04:43.324  3956  4005 D BluetoothAdapter: STATE_ON
09-09 13:04:43.328  2639  2780 D BtGatt.GattService: registerClient() - UUID=0d02668f-21ba-49f6-b59c-f449e81eeea8
09-09 13:04:43.329  2639  2659 D BtGatt.GattService: onClientRegistered() - UUID=0d02668f-21ba-49f6-b59c-f449e81eeea8, clientIf=5
09-09 13:04:43.330  3956  3967 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 13:04:43.331  2639  2650 D BtGatt.GattService: start scan with filters
09-09 13:04:43.334  2639  2663 D BtGatt.ScanManager: handling starting scan
09-09 13:04:43.335  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 13:04:43.335  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:04:43.335  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 13:04:43.335  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 13:04:43.337  2639  2663 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
09-09 13:04:43.338  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 13:04:43.338  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:04:43.339  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 13:04:43.339  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 13:04:43.341  3956  4005 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:04:43.346  2639  2659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 13:04:43.346  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:43.348  2639  2663 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 13:04:43.354  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 13:04:43.354  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:43.355  2639  2663 D BtGatt.ScanManager: Starting BLE batch scan
09-09 13:04:43.355  2639  2663 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 13:04:43.365  2639  2659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 13:04:43.365  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:43.370  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 13:04:43.370  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:04:43.840  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 13:04:43.841  3956  3956 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:04:43.841  3956  3956 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:04:44.878  2639  2639 D BtGatt.ScanManager: awakened up at time 136867
,09-09 13:04:44.880  2639  2663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:04:44.936  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-09 13:04:44.937  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:04:44.937  2639  2659 D BtGatt.GattService: current time is 136926231721
,09-09 13:04:44.939  2639  2659 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -91, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 13:04:44.944  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:04:44.947  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 13:04:44.947  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 13:04:44.948  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 13:04:44.949  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 13:04:44.950  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 13:04:46.441  2639  2639 D BtGatt.ScanManager: awakened up at time 138429
,09-09 13:04:46.443  2639  2663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:04:46.456  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:04:46.457  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:04:47.958  2639  2639 D BtGatt.ScanManager: awakened up at time 139946
,09-09 13:04:47.960  2639  2663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:04:47.987  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-09 13:04:47.987  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:47.987  2639  2659 D BtGatt.GattService: current time is 139976423380
,09-09 13:04:47.988  2639  2659 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -79, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 13:04:47.988  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 13:04:47.988  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 13:04:48.354  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:04:48.354  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:04:48.355  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:04:48.355  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:04:48.355  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:04:48.356  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:04:48.356  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:04:48.356  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:04:48.357  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:04:48.359  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:04:48.360  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 13:04:48.363  3956  4005 D BluetoothAdapter: STATE_ON
,09-09 13:04:48.365  2639  2650 D BtGatt.GattService: stopScan() - queue size =1
,09-09 13:04:48.367  2639  2781 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:04:48.368  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:04:48.368  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:04:48.369  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 13:04:48.369  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 13:04:48.369  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 13:04:48.373  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:04:48.375  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:04:48.375  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:04:48.377  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:04:48.378  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:04:48.383  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:04:48.383  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:04:48.383  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:04:48.384  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:04:48.385  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:04:48.385  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:04:48.385  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:04:48.385  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:04:48.385  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:04:48.386  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:04:48.386  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:04:48.388  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 13:04:48.388  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:48.389  2639  2663 D BtGatt.ScanManager: stopping BLe Batch
,09-09 13:04:48.405  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 13:04:48.405  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:48.405  2639  2663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:04:48.433  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-09 13:04:48.433  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:04:48.433  2639  2659 D BtGatt.GattService: current time is 140422253997
,09-09 13:04:48.434  2639  2659 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,09-09 13:04:48.434  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-09 13:04:48.885  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:04:53.387  3956  4005 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 13:04:53.395  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:04:53.415  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:04:53.415  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:04:53.415  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:04:53.415  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:04:53.415  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:04:53.415  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:04:53.415  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:04:53.415  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:04:53.425  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:04:53.426  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:04:53.427  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:04:53.427  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 13:04:53.428  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 13:04:53.429  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:04:53.431  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:04:53.436  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:04:53.446  3956  4005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:04:53.447  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:04:53.448  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:04:53.461  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:04:53.463  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:04:53.463  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:04:53.474  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 13:04:53.475  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 13:04:53.475  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:04:53.477  3956  4005 D BluetoothAdapter: STATE_ON
,09-09 13:04:53.484  2639  2780 D BtGatt.GattService: registerClient() - UUID=de702083-143f-4014-b289-e1889d8aaa59
,09-09 13:04:53.485  2639  2659 D BtGatt.GattService: onClientRegistered() - UUID=de702083-143f-4014-b289-e1889d8aaa59, clientIf=5
09-09 13:04:53.486  3956  3968 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 13:04:53.486  2639  2650 D BtGatt.GattService: start scan with filters
,09-09 13:04:53.495  2639  2663 D BtGatt.ScanManager: handling starting scan
,09-09 13:04:53.496  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 13:04:53.496  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:04:53.496  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 13:04:53.497  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 13:04:53.508  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:04:53.509  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 13:04:53.510  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:04:53.514  2639  2659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 13:04:53.515  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:53.515  2639  2663 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 13:04:53.517  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:04:53.527  3956  4005 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:04:53.534  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:04:53.534  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 13:04:53.534  3956  4005 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:04:53.535  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:53.535  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:04:53.535  2639  2663 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 13:04:53.535  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:04:53.538  2639  2663 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 13:04:53.538  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:04:53.538  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:04:53.538  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:04:53.539  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:04:53.539  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:04:53.539  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:04:53.540  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:04:53.540  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 13:04:53.542  3956  4005 D BluetoothAdapter: STATE_ON
,09-09 13:04:53.548  2639  2780 D BtGatt.GattService: stopScan() - queue size =1
,09-09 13:04:53.552  2639  2652 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:04:53.553  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:04:53.553  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:04:53.555  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 13:04:53.555  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 13:04:53.555  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 13:04:53.557  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:04:53.558  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:04:53.558  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:04:53.558  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:04:53.559  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:04:53.559  2639  2659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 13:04:53.560  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:04:53.561  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:04:53.561  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:04:53.561  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:04:53.561  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:04:53.561  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:04:53.561  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:04:53.561  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:04:53.561  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:04:53.561  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:04:53.561  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:04:53.561  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:04:53.562  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:04:53.562  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:04:53.563  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:04:53.563  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:04:53.563  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:04:53.563  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:04:53.564  3956  4005 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:04:53.566  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:04:53.568  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 13:04:53.569  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:53.573  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:04:53.573  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:04:53.573  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:04:53.573  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:04:53.573  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:04:53.573  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:04:53.573  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:04:53.573  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:04:53.578  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:04:53.578  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:04:53.578  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:04:53.578  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 13:04:53.578  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:04:53.578  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:04:53.579  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:04:53.579  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 13:04:53.579  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:53.580  2639  2663 D BtGatt.ScanManager: stopping BLe Batch
09-09 13:04:53.581  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:04:53.584  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:04:53.587  3956  4005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 13:04:53.587  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:04:53.588  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 13:04:53.588  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:04:53.589  2639  2663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 13:04:53.590  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:04:53.591  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:04:53.591  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:04:53.595  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 13:04:53.595  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 13:04:53.595  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 13:04:53.595  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:53.595  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:04:53.596  3956  4005 D BluetoothAdapter: STATE_ON
,09-09 13:04:53.597  2639  2780 D BtGatt.GattService: registerClient() - UUID=b56cf6e3-42e4-48f7-a44d-50048495f023
,09-09 13:04:53.598  2639  2659 D BtGatt.GattService: onClientRegistered() - UUID=b56cf6e3-42e4-48f7-a44d-50048495f023, clientIf=5
09-09 13:04:53.598  3956  4020 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 13:04:53.599  2639  2781 D BtGatt.GattService: start scan with filters
,09-09 13:04:53.601  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 13:04:53.601  2639  2663 D BtGatt.ScanManager: handling starting scan
09-09 13:04:53.601  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:04:53.602  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 13:04:53.602  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 13:04:53.604  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:04:53.605  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 13:04:53.605  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:04:53.607  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:04:53.608  2639  2659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 13:04:53.608  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:04:53.608  2639  2663 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 13:04:53.610  3956  4005 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:04:53.615  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 13:04:53.615  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:53.615  2639  2663 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 13:04:53.615  2639  2663 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 13:04:53.627  2639  2659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 13:04:53.627  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:04:53.634  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 13:04:53.634  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:04:54.106  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 13:04:54.106  3956  3956 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:04:54.107  3956  3956 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:04:55.141  2639  2639 D BtGatt.ScanManager: awakened up at time 147129
,09-09 13:04:55.143  2639  2663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:04:55.185  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-09 13:04:55.186  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:55.186  2639  2659 D BtGatt.GattService: current time is 147175021753
09-09 13:04:55.187  2639  2659 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -95, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 13:04:55.188  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 13:04:55.189  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 13:04:55.189  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 13:04:55.190  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 13:04:55.191  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 13:04:56.690  2639  2639 D BtGatt.ScanManager: awakened up at time 148678
,09-09 13:04:56.693  2639  2663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:04:56.706  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:04:56.706  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-09 13:04:57.872   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 13:04:57.882  1887  1887 I Keyboard.Facilitator: onFinishInput()
,09-09 13:04:57.895   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:04:57.895   872   892 I Adreno  : Build Date                       : 10/20/15
09-09 13:04:57.895   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:04:57.895   872   892 I Adreno  : Local Branch                     : M14
09-09 13:04:57.895   872   892 I Adreno  : Remote Branch                    : 
09-09 13:04:57.895   872   892 I Adreno  : Remote Branch                    : 
09-09 13:04:57.895   872   892 I Adreno  : Reconstruct Branch               : 
,09-09 13:04:57.940   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (212 us)
,09-09 13:04:58.223  2639  2639 D BtGatt.ScanManager: awakened up at time 150211
09-09 13:04:58.226  2639  2663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:04:58.279  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-09 13:04:58.279  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:58.280  2639  2659 D BtGatt.GattService: current time is 150268455134
,09-09 13:04:58.280  2639  2659 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -91, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:04:58.280  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 13:04:58.280  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 13:04:58.280  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:04:58.543  3956  3956 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:04:58.543  3956  3956 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 13:04:58.576   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 13:04:58.580   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 13:04:58.585  3956  3956 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8c54dde Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@eb2f5, 16908290=android.view.AbsSavedState$1@eb2f5}, android:focusedViewId=100}]}]
,09-09 13:04:58.585  3956  3956 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 13:04:58.587   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 13:04:58.587  3956  3956 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 13:04:58.588  3956  3956 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 13:04:58.590   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-09 13:04:58.590   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-09 13:04:58.590   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-09 13:04:58.607  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:04:58.611  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:04:58.611  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 13:04:58.612  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:04:58.612  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:04:58.612  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:04:58.612  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:04:58.612  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:04:58.613  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:04:58.613  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:04:58.613  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:04:58.613  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 13:04:58.615  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 13:04:58.615  3956  4005 D BluetoothAdapter: STATE_ON
,09-09 13:04:58.621  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:04:58.622  2639  2652 D BtGatt.GattService: stopScan() - queue size =1
,09-09 13:04:58.625  2639  2650 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:04:58.625  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:04:58.625  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 13:04:58.625  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 13:04:58.625  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 13:04:58.625  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 13:04:58.626  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:04:58.626  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:04:58.626  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:04:58.626  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:04:58.627  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:04:58.629  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:04:58.630  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:04:58.630  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:04:58.630  2639  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 13:04:58.630  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:58.630  2639  2663 D BtGatt.ScanManager: stopping BLe Batch
,09-09 13:04:58.639  2639  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 13:04:58.639  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:58.639  2639  2663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:04:58.647  2639  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-09 13:04:58.647  2639  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:04:58.647  2639  2659 D BtGatt.GattService: current time is 150635903243
09-09 13:04:58.647  2639  2659 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -89, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 13:04:58.647  2639  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:04:58.649  1514  3150 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 13:04:58.649  1514  3150 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 13:04:58.649  1514  3150 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:04:58.649  1514  3150 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:04:58.659  3705  3705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 13:04:58.659  3705  3705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 13:04:58.659  3705  3705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 13:04:58.827   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 13:04:58.831   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 13:04:58.836   872  1341 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
,09-09 13:04:58.839   872   892 I DreamManagerService: Entering dreamland.
,09-09 13:04:58.840   872   892 I PowerManagerService: Dozing...
,09-09 13:04:58.842   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 13:04:58.909   375  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-09 13:04:58.910   375  1322 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 13:04:58.929   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:04:58.948   872  1314 E native  : do suspend false
,09-09 13:04:58.953  1943  4027 D NfcService: Discovery configuration equal, not updating.
,09-09 13:04:58.971   872  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 13:04:58.994   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:04:58.998   872  1314 E native  : do suspend true
,09-09 13:04:59.038   375  1287 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 13:04:59.038   375  1287 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 13:04:59.130  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:04:59.131  3956  3956 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:04:59.131  3956  3956 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:04:59.437   872  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-09 13:05:03.632  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:05:03.632  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:05:03.632  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:03.633  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.634  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.634  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:05:03.635  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
,09-09 13:05:03.635  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.636  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:03.636  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.636  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:03.638  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:03.638  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:03.642  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:03.643  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:05:03.643  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.643  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:03.645  3956  4005 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 13:05:03.647  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:05:03.649  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:03.649  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:03.650  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.650  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.650  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.650  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:03.650  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.651  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.651  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.651  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.651  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.652  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.652  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.654  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:03.654  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:03.654  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.654  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.656  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:05:03.656  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:05:03.657  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:03.657  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:03.658  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.658  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.658  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.658  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:03.658  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.659  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Di,scoveryManager@66467e8 not in the list
09-09 13:05:03.659  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.659  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.659  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.659  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.660  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:03.663  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:03.663  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:05:03.664  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:05:03.664  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.667  3956  4005 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-09 13:05:03.668  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:05:03.668  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:05:03.669  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:03.669  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.669  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.669  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.669  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
,09-09 13:05:03.669  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.669  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.669  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.669  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:03.670  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.670  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.670  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:03.673  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:03.673  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:05:03.673  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.673  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:03.675  3956  4005 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:05:03.675  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:05:03.675  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:03.676  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:05:03.676  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.676  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.677  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:03.677  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:03.677  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:05:03.677  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.677  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.678  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.678  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:03.678  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.678  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:03.680  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 13:05:03.680  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:03.681  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.681  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:03.682  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:05:03.684  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:05:03.685  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:05:03.685  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:05:03.685  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:05:03.685  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:05:03.686  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:05:03.686  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:05:03.687  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:05:03.687  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:05:03.687  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:05:03.688  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:03.689  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.689  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.689  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.689  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:03.689  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.690  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:03.690  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.690  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.690  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.690  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.690  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:03.691  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:03.691  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:03.691  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.692  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:03.693  3956  4005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 13:05:03.694  3956  4005 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-09 13:05:03.694  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 13:05:03.699  3956  4005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:05:03.700  3956  4005 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-09 13:05:03.700  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:05:03.700  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:05:03.700  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:05:03.700  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-09 13:05:03.700  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-09 13:05:03.700  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:05:03.701  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:05:03.701  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:05:03.701  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:05:03.701  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-09 13:05:03.701  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:05:03.701  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:05:03.701  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:05:03.701  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 13:05:03.702  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:05:03.702  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-09 13:05:03.702  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-09 13:05:03.702  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:05:03.702  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:05:03.702  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:05:03.703  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:05:03.703  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-09 13:05:03.703  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:05:03.703  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:05:03.703  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:05:03.703  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:05:03.703  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-09 13:05:03.703  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:05:03.704  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:05:03.704  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:05:03.704  3956  4005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:05:03.705  3956  4005 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:05:03.705  3956  4005 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:05:03.705  3956  4005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:05:03.705  3956  4005 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:05:03.705  3956  4005 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:05:03.705  3956  4005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:05:03.706  3956  4005 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:05:03.706  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:05:03.710  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:05:03.711  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:05:03.712  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:05:03.713  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:05:03.713  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:05:03.713  3956  4005 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:05:03.713  3956  4005 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:05:03.713  3956  4005 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:05:03.715  3956  4032 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 426)
09-09 13:05:03.715  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:05:03.715  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:03.715  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:03.715  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.715  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.716  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.716  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:05:03.717  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:03.717  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.717  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.717  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.717  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.718  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.718  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.718  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.720  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:03.720  3956  4033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 426
09-09 13:05:03.720  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:03.721  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.721  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.721  3956  4032 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:05:03.722  3956  4005 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:05:03.723  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:05:03.723  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:03.723  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:03.724  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.724  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.724  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.724  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:03.724  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.724  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.724  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.724  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.725  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.725  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.725  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.727  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:03.729  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:03.729  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.729  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.730  3956  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:05:03.730  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:05:03.730  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:03.730  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:03.730  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.730  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.730  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.731  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:03.731  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.731  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.731  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.731  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.731  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.731  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.731  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.732  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:03.732  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:03.732  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.732  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.733  3956  4005 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:05:03.733  3956  4005 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:05:03.733  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:05:03.733  3956  4005 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:05:03.734  3956  4005 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:05:03.734  3956  4005 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:05:03.734  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:05:03.734  3956  4005 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:05:03.734  3956  4005 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:05:03.734  3956  4005 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:05:03.734  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:05:03.734  3956  4005 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:05:03.734  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:05:03.735  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:03.735  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:03.735  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.735  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.735  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.735  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:03.735  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.735  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.735  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.735  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.735  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.735  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.735  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:03.737  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:03.737  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:03.737  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.737  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.738  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:03.738  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.738  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:03.738  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:03.738  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:03.738  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:03.738  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:03.738  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:03.738  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:08.357  1903  2782 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 13:05:08.739  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:05:08.740  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:08.740  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:05:08.740  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:08.741  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:08.741  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
,09-09 13:05:08.742  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:05:08.742  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:05:08.742  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:05:08.743  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:08.743  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:08.743  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:08.744  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
,09-09 13:05:08.744  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:05:08.744  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:08.744  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:05:08.745  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:08.745  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.745  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:08.746  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:08.749  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:08.749  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:08.749  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:08.750  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:08.755  3956  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:05:08.756  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:05:08.758  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:05:08.760  3956  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:05:08.760  3956  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:05:08.761  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-09 13:05:08.762  3956  3956 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:05:08.762  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:05:08.763  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:08.763  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:05:08.763  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:05:08.763  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:05:08.764  3956  4034 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:05:08.764  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.764  3956  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 13:05:08.764  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:08.764  3956  3956 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:05:08.765  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:08.765  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:05:08.765  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:05:08.765  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:05:08.766  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:08.766  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:08.768  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:05:08.768  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:08.768  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:05:08.768  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:05:08.768  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:05:08.768  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:05:08.768  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:05:08.768  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:08.768  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:05:08.768  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:08.769  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.768  3956  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,09-09 13:05:08.769  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
09-09 13:05:08.769  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:05:08.769  3956  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:05:08.769  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:08.769  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:05:08.769  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:08.769  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:08.769  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:08.769  3956  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:05:08.769  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:08.770  3956  3956 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:05:08.771  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:08.771  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:05:08.771  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:08.771  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:08.773  3956  4005 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:05:08.773  3956  4005 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 13:05:08.773  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:05:08.773  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:05:08.773  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:05:08.773  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:05:08.774  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:08.774  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:08.774  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:08.774  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:08.774  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:08.774  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
,09-09 13:05:08.774  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:08.774  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:08.774  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:05:08.775  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:08.775  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.775  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:08.775  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.777  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 13:05:08.777  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:08.777  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:08.777  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:08.782  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:05:08.783  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:08.783  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:08.783  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:08.783  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:08.783  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.783  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list,
09-09 13:05:08.783  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:08.783  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:08.783  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:08.783  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:08.784  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.784  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:08.784  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.785  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:08.785  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:08.785  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:08.785  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
,09-09 13:05:08.786  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:05:08.786  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:05:08.786  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:05:08.787  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:05:08.787  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:08.787  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.787  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e9d0b not in the list
,09-09 13:05:08.787  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:08.787  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:08.787  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:08.787  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:08.787  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.787  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:08.787  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:08.789  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:05:08.789  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:05:08.789  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:08.789  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66467e8 not in the list
09-09 13:05:08.790  3956  4005 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:05:08.790  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-09 13:05:08.790  3956  4005 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:05:08.791  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:05:08.791  3956  4005 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:05:08.791  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:05:08.794  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:05:08.794  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 13:05:08.795  3956  4005 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:05:08.795  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:05:08.795  3956  4005 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:05:08.796  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:05:08.796  3956  4005 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:05:08.796  3956  4005 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 13:05:08.797  3956  4005 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-09 13:05:08.797  3956  4005 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 13:05:08.797  3956  4005 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:05:08.798  3956  4005 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 13:05:08.798  3956  4005 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:05:08.798  3956  4005 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 13:05:08.799  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:05:08.799  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a94defb added. We now have 3 listener(s)
09-09 13:05:08.799  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:05:08.802  3956  4005 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 13:05:08.803   872  2018 D WifiService: setWifiEnabled: true pid=3956, uid=10000
09-09 13:05:08.803   872  2018 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:05:08.858  2639  2743 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-09 13:05:08.859  2639  2765 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-09 13:05:08.860  3956  4032 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 426)
,09-09 13:05:09.142  3765  4037 V KeepSync: Connecting to GoogleApiClient
,09-09 13:05:09.142   872  1404 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:05:09.180  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:09.182  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:09.220  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:05:09.220  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 13:05:09.220  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:05:09.220  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 13:05:09.221  1514  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 13:05:09.221  1514  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 13:05:09.222  1514  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:05:09.222  1514  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:05:09.239  3181  4038 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:05:09.239  3181  4038 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:05:09.239  3181  4038 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	... 12 more
09-09 13:05:09.239  3181  4038 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at fal.a(PG:38)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:05:09.239  3181  4038 E HttpOperation: 	... 14 more
,09-09 13:05:09.244  1743  4039 V BaseAuthAsyncOperation: access token request failed
,09-09 13:05:09.245  3765  4037 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:05:09.269  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:05:09.283  1514  3150 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:05:09.283  1514  3150 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 13:05:09.283  1514  3150 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:05:09.284  1514  3150 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:05:09.297  1514  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 13:05:09.297  1514  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 13:05:09.297  1514  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:05:09.297  1514  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:05:09.300  3181  4038 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:05:09.300  3181  4038 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at hec.a(PG:42)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at hee.a(PG:102)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at czr.a(PG:65)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at kka.a(PG:108)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:05:09.300  3181  4038 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	... 15 more
09-09 13:05:09.300  3181  4038 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at fal.a(PG:38)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:05:09.300  3181  4038 E HttpOperation: 	... 17 more
,09-09 13:05:09.300  3181  4038 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:05:09.300  3181  4038 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	... 15 more
09-09 13:05:09.300  3181  4038 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:05:09.300  3181  4038 E ExperimentLoader: 	... 17 more
,09-09 13:05:09.332  3765  4037 E KeepSync: IOException
09-09 13:05:09.332  3765  4037 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:05:09.332  3765  4037 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:05:09.332  3765  4037 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:05:09.332  3765  4037 E KeepSync: 	... 10 more
,09-09 13:05:09.332  3765  4037 W KeepSync: Sync result 2
,09-09 13:05:09.340   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 131464, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:05:09.399   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131399, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:05:11.700   872  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-09 13:05:13.815  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:05:13.815  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e759b18 added. We now have 4 listener(s)
09-09 13:05:13.815  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:05:13.832  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:05:13.833  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e759b18 removed from the list
09-09 13:05:13.833  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:13.833  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:13.834  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:13.836  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:05:13.836  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9e48971 added. We now have 4 listener(s)
09-09 13:05:13.837  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:05:13.841  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:05:13.842  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9e48971 removed from the list
09-09 13:05:13.842  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:13.842  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:13.842  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:13.845  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:05:13.845  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6952356 added. We now have 4 listener(s)
,09-09 13:05:13.846  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:05:13.853   872   883 D WifiService: setWifiEnabled: false pid=3956, uid=10000
09-09 13:05:13.854   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:05:13.867  2639  2654 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 13:05:13.867  2639  2654 D BluetoothAdapterProperties: Setting state to 13
09-09 13:05:13.867  2639  2654 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:05:13.867  2639  2654 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 13:05:13.868  2639  2654 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:05:13.869  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:05:13.873  2639  2659 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:05:13.873  2639  2654 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 13:05:13.879  2639  2639 D HeadsetService: Received stop request...Stopping profile...
,09-09 13:05:13.880  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:05:13.884   872  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 13:05:13.884   872  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 13:05:13.885   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:05:13.885   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:05:13.887  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.887  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:05:13.887  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:13.887  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:13.887  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:13.887  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:13.887  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:13.887  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:05:13.887  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:05:13.888  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.889  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:13.889  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:05:13.891   872  1314 E native  : do suspend true
,09-09 13:05:13.893  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:13.895  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:13.899  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.899  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:13.899  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:13.899  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:13.899  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:13.899  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:13.899  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:13.899  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:05:13.899  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:05:13.899  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.900  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:05:13.903  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:13.903  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:13.903  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:13.903  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:13.903  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:13.903  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:13.903  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:13.903  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:05:13.903  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:05:13.903   872   885 I ActivityManager: Start proc 4043:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-09 13:05:13.904  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.904  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:13.905   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:05:13.907   872  2094 D DhcpClient: Clearing IP address
,09-09 13:05:13.907  1361  1696 D BluetoothHeadset: Proxy object disconnected
,09-09 13:05:13.907  2639  2639 D BluetoothMapService: onReceive
,09-09 13:05:13.907  2639  2639 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:05:13.907  2639  2639 D BluetoothMapService: STATE_TURNING_OFF
09-09 13:05:13.907  1956  2168 D BluetoothHeadset: Proxy object disconnected
09-09 13:05:13.907  2639  2639 V BluetoothAdapterState: isTurningOff()=true
,09-09 13:05:13.907  2639  2639 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:13.907  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:13.908   872   872 D BluetoothHeadset: Proxy object disconnected
,09-09 13:05:13.908  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:13.908   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 13:05:13.908   872   872 D BluetoothHeadset: Proxy object disconnected
,09-09 13:05:13.908  2639  2639 D A2dpService: Received stop request...Stopping profile...
09-09 13:05:13.909  2639  2773 D A2dpStateMachine: Exit Disconnected: -1
,09-09 13:05:13.909   371   870 D CommandListener: Setting iface cfg
09-09 13:05:13.912  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:13.912   872   872 D BluetoothA2dp: Proxy object disconnected
09-09 13:05:13.913  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,09-09 13:05:13.914  1361  1361 D BluetoothA2dp: Proxy object disconnected
09-09 13:05:13.914  2639  2639 D HidService: Received stop request...Stopping profile...
,09-09 13:05:13.914  2639  2639 D HidService: Stopping Bluetooth HidService
,09-09 13:05:13.914  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:13.915  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-09 13:05:13.915  1361  1361 D HidProfile: Bluetooth service disconnected
09-09 13:05:13.916  2639  2639 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:05:13.916  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:13.916  2639  2659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-09 13:05:13.917  2639  2639 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 13:05:13.917  2639  2743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:05:13.917  2639  2743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:05:13.917  2639  2743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
,09-09 13:05:13.917  2639  2659 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-09 13:05:13.917  2639  2639 D BluetoothMapService: MAP Service closeService in
09-09 13:05:13.917  2639  2639 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 13:05:13.917  2639  2639 D ObexServerSockets0: shutdown(block = true)
09-09 13:05:13.917  2639  2793 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-09 13:05:13.918  2639  2639 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:05:13.918  2639  2794 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 13:05:13.919  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:13.919  2639  2765 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 13:05:13.919  2639  2639 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:05:13.919  2639  2639 I BtOppRfcommListener: stopping Accept Thread
09-09 13:05:13.919  2639  3604 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:05:13.920  2639  3604 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 13:05:13.921   872  2104 D DhcpClient: Receive thread stopped
,09-09 13:05:13.922  2639  2639 D HealthService: Received stop request...Stopping profile...
09-09 13:05:13.924  2639  2639 D PanService: Received stop request...Stopping profile...
09-09 13:05:13.925  2639  2639 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:13.925  2639  2639 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:13.925  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false,
09-09 13:05:13.925  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:13.926   872  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 13:05:13.926   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 13:05:13.926   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 13:05:13.927   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:05:13.927   872  1314 E native  : do suspend true
09-09 13:05:13.927  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:05:13.927  1361  1361 D PanProfile: Bluetooth service disconnected
,09-09 13:05:13.931  2639  2659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-09 13:05:13.931  2639  2743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:05:13.931  2639  2743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:05:13.931   394   394 E Parcel  : Reading a NULL string not supported here.
,09-09 13:05:13.931  2639  2743 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:05:13.931  2639  2743 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 13:05:13.931  2639  2743 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:05:13.931  2639  2743 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:05:13.932  2639  2639 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:05:13.932  2639  2639 D BluetoothMapService: stop()
09-09 13:05:13.932   872  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 13:05:13.933  2639  2639 D BluetoothMapAppObserver: deinitObservers()
09-09 13:05:13.933  2639  2639 D BluetoothMapAppObserver: removeReceiver()
09-09 13:05:13.934  1514  2548 V NativeCrypto: Read error: ssl=0x9b66d000: I/O error during system call, Connection timed out
09-09 13:05:13.934  1361  1361 D BluetoothMap: Proxy object disconnected
09-09 13:05:13.934  1361  1361 D MapProfile: Bluetooth service disconnected
09-09 13:05:13.934  2639  2639 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:13.935  2639  2639 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:13.935  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:13.935  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:13.935  2639  2639 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:05:13.936  2639  2659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 13:05:13.936  2639  2639 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:05:13.937  2639  2639 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:13.937  2639  2639 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:13.937  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:13.937  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:13.937  2639  2639 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:05:13.938  2639  2659 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 13:05:13.939  2639  2639 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:05:13.940  2639  2639 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:13.940  2639  2639 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:05:13.940  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:13.940  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:13.940  2639  2639 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:05:13.940  2639  2639 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:05:13.941  2639  2639 D BluetoothMapService: MAP Service closeService in
09-09 13:05:13.941  2639  2639 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:13.941  2639  2639 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:05:13.942  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:13.942  2639  2639 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:13.942  2639  2654 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 13:05:13.942  2639  2654 D BluetoothAdapterProperties: Setting state to 15
09-09 13:05:13.942  2639  2654 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 13:05:13.942  2639  2654 I BluetoothAdapterState: Entering BleOnState
,09-09 13:05:13.943  2639  2639 D BluetoothMapService: cleanup()
09-09 13:05:13.943   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:13.943  2639  2639 D BluetoothMapService: MAP Service closeService in
09-09 13:05:13.943  1361  1696 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:05:13.944   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:05:13.944   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:13.944  1361  1372 D BluetoothPan: onBluetoothStateChange on: false
,09-09 13:05:13.945  1361  1373 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:05:13.945   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:13.945  1361  1696 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:05:13.946  1956  1967 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:13.946  1361  1372 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:05:13.947  1361  1373 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 13:05:13.947  2639  2654 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 13:05:13.948  2639  2654 D BluetoothAdapterProperties: Setting state to 16
09-09 13:05:13.948  2639  2654 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 13:05:13.948  2639  2654 D BluetoothAdapterProperties: onBleDisable
09-09 13:05:13.949  2639  2654 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:05:13.949  2639  2655 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 13:05:13.950  2639  2743 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-09 13:05:13.950  2639  2743 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:05:13.951  2639  2659 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:05:13.953  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.954  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:13.954  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:13.954  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:13.954  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:13.954  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:13.954  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:13.954  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:13.954  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:13.954  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:13.954  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:13.956  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.956  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:13.956  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:13.956  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:13.956  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:13.956  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:13.956  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:13.956  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:13.956  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:13.956  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.959  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:13.960  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.960  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-09 13:05:13.960  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:13.960  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:13.960  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:13.960  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:13.960  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:13.960  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:13.960  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:13.962  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:13.962  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:13.964  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:13.965  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:13.966  1514  2548 V NativeCrypto: SSL shutdown failed: ssl=0x9b66d000: I/O error during system call, Broken pipe
09-09 13:05:13.966  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:13.972   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:05:13.983  4043  4043 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 13:05:13.991  4043  4043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:05:13.993   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:05:13.993   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:05:13.994   872  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-09 13:05:13.994   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:05:13.994   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 13:05:13.996   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:05:13.998  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:14.000  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:14.000  3607  3607 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@96dab4c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-09 13:05:14.001  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:05:14.003  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:14.008   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@951a81a:true
,09-09 13:05:14.013   872   883 I ActivityManager: Start proc 4060:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 13:05:14.015   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:05:14.017  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:14.017  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:14.017  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:14.017  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:14.017  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:14.017  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:14.017  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:14.017  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:14.017  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:14.017  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:14.017   872  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:05:14.017  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:14.018  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:14.019  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:14.019  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:14.019  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:14.019  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:14.019  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:14.019  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:14.019  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:14.019  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:14.019  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:14.019  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:14.020  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:14.020  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:14.020  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:14.020  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:14.020  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:14.020  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:14.020  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:14.020  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:14.020  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:14.021  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:14.021  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:14.022  1903  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:05:14.032  4043  4043 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 13:05:14.034  4043  4043 D BluetoothMap: Create BluetoothMap proxy object
,09-09 13:05:14.047  4060  4060 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 13:05:14.049  4043  4043 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 13:05:14.055   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-09 13:05:14.059  4043  4043 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:05:14.069   872  2019 I ActivityManager: Killing 3377:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 13:05:14.153  2639  2659 I bt_hci  : shut_down
,09-09 13:05:14.168  2639  2664 D bt_hwcfg: hw_epilog_process
,09-09 13:05:14.168  2639  2664 I bt_vendor: low_power_mode_cb
,09-09 13:05:14.195  2639  2664 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 13:05:14.195  2639  2664 I bt_vendor: epilog_cb
,09-09 13:05:14.195  2639  2664 I bt_hci  : epilog_finished_callback
,09-09 13:05:14.201  4060  4060 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:05:14.201  4060  4060 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
,09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:05:14.201  4060  4060 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:05:14.201  4060  4060 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:05:14.201  2639  2659 I bt_hci_h4: hal_close
09-09 13:05:14.201  4060  4060 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:05:14.201  4060  4060 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:05:14.201  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:05:14.209  4060  4060 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:05:14.209,  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:05:14.202  2639  2659 I bt_userial_vendor: device fd = 51 close
09-09 13:05:14.209  4060  4060 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:05:14.209  4060  4060 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:05:14.214  4043  4043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:05:14.222  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:05:14.223  4043  4043 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:05:14.242   872  1679 I ActivityManager: Killing 3607:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 13:05:14.383  2639  2655 D bt_stack_manager: event_shut_down_stack finished.
,09-09 13:05:14.384  2639  2654 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 13:05:14.397  2639  2639 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:05:14.402  2639  2654 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 13:05:14.409  2639  2639 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 13:05:14.409  2639  2639 D BtGatt.GattService: stop()
09-09 13:05:14.409  2639  2639 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 13:05:14.416  2639  2639 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:05:14.417  2639  2639 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:14.417  2639  2639 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:14.417  2639  2639 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 13:05:14.417  2639  2654 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 13:05:14.417  2639  2654 D BluetoothAdapterProperties: Setting state to 10
09-09 13:05:14.417  2639  2654 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 13:05:14.418  2639  2654 I BluetoothAdapterState: Entering OffState
09-09 13:05:14.419  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 13:05:14.421   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-09 13:05:14.423  1743  1743 D SystemUpdateService: onCreate
,09-09 13:05:14.431  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 13:05:14.434  2639  2639 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 13:05:14.434  1743  4096 I SystemUpdateService: active receiver: enabled
09-09 13:05:14.434  2639  2639 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-09 13:05:14.435  2639  2655 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 13:05:14.438  2639  2655 D bt_stack_manager: event_clean_up_stack finished.
,09-09 13:05:14.438  1743  4096 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:05:14.434  2639  2639 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 13:05:14.439  1743  4096 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 13:05:14.439  1743  4096 I SystemUpdateService: now status is 0 (complete)
,09-09 13:05:14.440  1743  4096 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 13:05:14.440  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:05:14.440  1743  4096 I SystemUpdateService: file has been verified
09-09 13:05:14.441  1743  4096 I SystemUpdateService: OTA package size = 12249756
,09-09 13:05:14.443  1743  4096 I SystemUpdateService: showing system update notification
09-09 13:05:14.444  1743  2526 I iu.UploadsManager: num queued entries: 0
09-09 13:05:14.444  1743  2526 I iu.UploadsManager: num updated entries: 0
,09-09 13:05:14.445  2639  2639 I art     : System.exit called, status: 0
09-09 13:05:14.445  2639  2639 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 13:05:14.446  1743  2526 I iu.SyncManager: NEXT; no task
,09-09 13:05:14.453  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:05:14.454  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 13:05:14.463  4060  4082 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 13:05:14.468   872  2016 I ActivityManager: Start proc 4099:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 13:05:14.470  1743  1743 D SystemUpdateService: onDestroy
,09-09 13:05:14.484   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d59546:true
,09-09 13:05:14.488   872  1391 I ActivityManager: Process com.android.bluetooth (pid 2639) has died
,09-09 13:05:14.504  4099  4099 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 13:05:14.507  4099  4099 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:05:14.515  4099  4099 D SprintDMHelper: simOperator: 
09-09 13:05:14.515  4099  4099 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:05:14.529   872  2018 I ActivityManager: Start proc 4111:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 13:05:14.643   872   882 I ActivityManager: Start proc 4126:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 13:05:14.646  2872  4125 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 13:05:14.650   872  2013 I ActivityManager: Killing 2967:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 13:05:14.709  4126  4126 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 13:05:14.773  4126  4126 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:05:14.773  4126  4126 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:05:14.773  4126  4126 I GAv4    :   adb logcat -s GAv4
,09-09 13:05:14.793  4126  4126 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:05:14.799  4126  4126 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:05:14.825  4126  4143 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:05:14.927  4126  4126 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 13:05:14.967  4126  4126 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 13:05:14.976  4126  4126 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6961-6964)
09-09 13:05:14.976  4126  4126 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:05:14.990  4126  4126 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d587f7c}
09-09 13:05:14.990  4126  4126 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:05:14.990  4126  4126 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:05:15.000  4126  4126 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:05:15.001  4126  4126 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 13:05:15.017  4126  4126 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 13:05:15.032  4126  4126 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:05:15.032  4126  4126 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:05:15.032  4126  4126 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:05:15.032  4126  4126 I Adreno  : Build Date                       : 10/20/15
09-09 13:05:15.032  4126  4126 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:05:15.032  4126  4126 I Adreno  : Local Branch                     : M14
09-09 13:05:15.032  4126  4126 I Adreno  : Remote Branch                    : 
09-09 13:05:15.032  4126  4126 I Adreno  : Remote Branch                    : 
09-09 13:05:15.032  4126  4126 I Adreno  : Reconstruct Branch               : 
,09-09 13:05:15.092  4126  4126 I NSApplication: Starting up...
,09-09 13:05:15.105  4126  4172 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 13:05:15.133   872  1921 I ActivityManager: Start proc 4177:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 13:05:15.135   872  1921 I ActivityManager: Killing 3232:android.process.acore/u0a5 (adj 15): empty #17
,09-09 13:05:15.218  4177  4177 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 13:05:15.398   872  3305 I ActivityManager: Killing 3839:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 13:05:15.508   872  1679 I ActivityManager: Start proc 4191:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 13:05:15.611  4191  4191 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 13:05:15.676  4191  4191 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 13:05:15.733   872  2015 I ActivityManager: Killing 3856:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 13:05:18.892   872  2016 D WifiService: setWifiEnabled: true pid=3956, uid=10000
,09-09 13:05:18.892   872  2016 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:05:18.920  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:18.920  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:18.920  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:18.920  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:18.920  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:18.920  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:18.920  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:18.920  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:18.920  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:18.920  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:18.920  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:18.923   872  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:05:18.923  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:18.923  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:18.923  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:18.923  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:18.923  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:18.923  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:18.923  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:18.923  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-09 13:05:18.923  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:18.923  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:18.923  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:18.925  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-09 13:05:18.925  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:18.925  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:18.925  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:18.925  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:18.925  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:18.925  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:18.925  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
09-09 13:05:18.925  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:18.925  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:18.925  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:05:18.940   872  1314 D WifiConfigStore: loaded 0 passpoint configs
,09-09 13:05:18.941   872  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 13:05:18.942   872  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 13:05:18.942   872  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:05:18.943   872  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 13:05:18.943   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 13:05:18.943   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 13:05:18.951   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 13:05:18.951   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 13:05:18.952   371   870 D CommandListener: Setting iface cfg
,09-09 13:05:19.000   872  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-09 13:05:19.001   872  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:05:19.006   872  1314 E native  : do suspend true
,09-09 13:05:19.022   872  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 13:05:19.024   872  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 13:05:19.041   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:05:19.588   872  1921 I ActivityManager: Killing 3633:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 13:05:20.332   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 13:05:20.385   872  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.44 rxSuccessRate=7.12 delta 1000 -> 1000
,09-09 13:05:20.388   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-09 13:05:20.388   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:05:20.404   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 13:05:20.450   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 13:05:20.455  1475  1475 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 13:05:20.983  1475  1475 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 13:05:21.039  1475  1475 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:05:21.040  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 13:05:21.048   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:05:21.064   872  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:05:21.064   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 13:05:21.064   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:05:21.080   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:05:21.090   371   870 D CommandListener: Setting iface cfg
,09-09 13:05:21.092   872  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 13:05:21.102   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 13:05:21.115   872  4226 D DhcpClient: Receive thread started
,09-09 13:05:21.201   872  1314 E native  : do suspend false
,09-09 13:05:21.224   872  2094 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 13:05:21.246   872  4226 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172650, domain null
,09-09 13:05:21.247   872  2094 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172650 seconds
,09-09 13:05:21.250   872  2094 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 13:05:21.271   872  4226 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 13:05:21.272   872  2094 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 13:05:21.277   371   870 D CommandListener: Setting iface cfg
,09-09 13:05:21.288   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 13:05:21.290   872  2094 D DhcpClient: Scheduling renewal in 86399s
,09-09 13:05:21.290   872  1314 E native  : do suspend true
,09-09 13:05:21.316   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 13:05:21.319   872  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 13:05:21.320   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 13:05:21.323   872  1316 D ConnectivityService: Adding iface wlan0 to network 101
09-09 13:05:21.330   872  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:05:21.397   872  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 13:05:21.397   872  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 13:05:21.398   872  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 13:05:21.400   872  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 13:05:21.401   872  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 13:05:21.414   872  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 13:05:21.422   872  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 13:05:21.422   872  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-09 13:05:21.422   872  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-09 13:05:21.422   872  1316 D ConnectivityService:    accepting network in place of null
,09-09 13:05:21.422   872  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 13:05:21.423   872  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:05:21.424   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:05:21.440   872  4225 D NetlinkSocketObserver: NeighborEvent{elapsedMs=173428, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:05:21.488   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:05:21.522   872  4224 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 13:05:21.523   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:05:21.533   872  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 13:05:21.534   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:05:21.545   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:05:21.555   872  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 13:05:21.557  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:21.557  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:21.557  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:21.557  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:21.557  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:21.557  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:21.557  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:21.557  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:05:21.557  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:05:21.557  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:21.557  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:21.560  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:21.560  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:21.560  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:21.560  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:21.560  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:21.560  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:21.560  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:21.560  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:05:21.560  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:05:21.560  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:21.560  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:21.562  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:21.562  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:21.562  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:21.562  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:21.562  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:21.562  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:21.562  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:21.562  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:05:21.562  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:05:21.562  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:21.562  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:21.575  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 13:05:21.582  1743  1743 D SystemUpdateService: onCreate
09-09 13:05:21.585  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-09 13:05:21.590   872  4224 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:05:21 GMT], X-Android-Received-Millis=[1473419121589], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473419121562]}
09-09 13:05:21.591   872  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 13:05:21.591   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-09 13:05:21.591   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:05:21.592   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 13:05:21.613  1743  4236 I SystemUpdateService: active receiver: enabled
09-09 13:05:21.636  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-09 13:05:21.642  1743  2526 I iu.UploadsManager: num queued entries: 0,
,09-09 13:05:21.642  1743  2526 I iu.UploadsManager: num updated entries: 0
09-09 13:05:21.642  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:21.643  1743  2526 I iu.SyncManager: NEXT; no task
,09-09 13:05:21.650  1743  4236 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:05:21.661  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:05:21.666  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 13:05:21.679  4099  4099 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:05:21.684  1743  4240 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 13:05:21.684  1743  4240 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 13:05:21.686  1743  4240 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 13:05:21.687  4099  4099 D SprintDMHelper: simOperator: 
09-09 13:05:21.687  4099  4099 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:05:21.715  1743  4236 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 13:05:21.715  1743  4236 I SystemUpdateService: now status is 0 (complete)
,09-09 13:05:21.717  1743  4236 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 13:05:21.717  1743  4236 I SystemUpdateService: file has been verified
,09-09 13:05:21.738  1743  4236 I SystemUpdateService: OTA package size = 12249756
,09-09 13:05:21.747  1743  4236 I SystemUpdateService: showing system update notification
,09-09 13:05:21.769  1743  1743 D SystemUpdateService: onDestroy
,09-09 13:05:21.813  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:21.814  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:21.844  1514  4249 I VacuumService: Vacuum at: now=1473419121844 tag=VacuumService
,09-09 13:05:21.870  2872  4245 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:05:21.937  1514  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 13:05:21.937  1514  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 13:05:21.938  1514  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:05:21.938  1514  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:05:22.002  1743  4240 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-09 13:05:22.044  1514  4250 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-09 13:05:22.046  1514  4250 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:05:22.450  1514  4250 W Uploader:  no longer exists, so no auth token.
,09-09 13:05:22.532   872  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 13:05:23.368  1514  4250 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 13:05:23.368  1514  4250 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 13:05:23.368  1514  4250 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:05:23.368  1514  4250 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:05:23.382  1514  4250 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 13:05:23.382  1514  4250 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 13:05:23.382  1514  4250 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 13:05:23.677  1514  4250 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 13:05:23.677  1514  4250 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 13:05:23.677  1514  4250 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:05:23.677  1514  4250 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:05:23.696  1514  4250 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 13:05:23.696  1514  4250 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 13:05:23.696  1514  4250 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 13:05:23.901   872  2019 D WifiService: setWifiEnabled: false pid=3956, uid=10000
,09-09 13:05:23.901   872  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:05:23.932  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:05:23.941   872  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:05:23.941   872  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 13:05:23.942   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:05:23.942   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:05:23.978   872  1314 E native  : do suspend true
,09-09 13:05:23.993   872  2094 D DhcpClient: Clearing IP address
,09-09 13:05:23.994   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:05:23.999   371   870 D CommandListener: Setting iface cfg
,09-09 13:05:24.011  1514  4247 V NativeCrypto: Read error: ssl=0x9ab65400: I/O error during system call, Connection timed out
,09-09 13:05:24.014   872  4226 D DhcpClient: Receive thread stopped
,09-09 13:05:24.017   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:05:24.017   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-09 13:05:24.021  1514  4247 V NativeCrypto: SSL shutdown failed: ssl=0x9ab65400: I/O error during system call, Broken pipe
09-09 13:05:24.027   394   394 E Parcel  : Reading a NULL string not supported here.
09-09 13:05:24.030   872  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
09-09 13:05:24.032   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:05:24.032   872  1314 E native  : do suspend true
09-09 13:05:24.034   872  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 13:05:24.067  1514  4250 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/172.217.21.138 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
09-09 13:05:24.069   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:05:24.091   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 13:05:24.092   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:05:24.092   872  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:05:24.092   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:05:24.094   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 13:05:24.094   872   889 D Tethering: MasterInitialState.processMessage what=3
09-09 13:05:24.099  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.100  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:24.100  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:24.100  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:24.100  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:24.100  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:24.100  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:24.100  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:24.100  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:24.101  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.101  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:05:24.102  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.102  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:24.102  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:24.102  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:24.102  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:24.102  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:24.102  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:24.102  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:24.102  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:24.102  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.103  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:05:24.104  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.104  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:24.104  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:24.104  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:24.104  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:24.104  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:24.104  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:24.104  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:24.104  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:24.104  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.104  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:05:24.114   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 13:05:24.117  1903  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:05:24.117  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.117  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:24.117  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:24.117  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:24.117  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:24.117  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:24.117  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:24.117  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:24.117  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:24.117  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.117  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:24.117   872  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:05:24.118  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 13:05:24.118  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.118  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:24.118  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:24.118  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:24.118  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:24.118  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:24.118  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:24.118  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:24.118  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:24.118  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.118  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:24.119  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.120  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:24.120  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:24.120  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:24.120  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:24.120  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:24.120  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:24.120  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:24.120  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:24.120  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:24.120  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:24.123  1743  1743 D SystemUpdateService: onCreate
09-09 13:05:24.125  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-09 13:05:24.140  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-09 13:05:24.142  1743  2526 I iu.UploadsManager: num queued entries: 0
,09-09 13:05:24.142  1743  2526 I iu.UploadsManager: num updated entries: 0
09-09 13:05:24.143  1743  2526 I iu.SyncManager: NEXT; no task
09-09 13:05:24.147  1743  4272 I SystemUpdateService: active receiver: enabled
09-09 13:05:24.149  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-09 13:05:24.150  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 13:05:24.152  4099  4099 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:05:24.156  4099  4099 D SprintDMHelper: simOperator: 
09-09 13:05:24.156  4099  4099 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 13:05:24.167   371   870 E Netd    : netlink response contains error (No such file or directory)
09-09 13:05:24.176  2872  4276 I Babel   : connection state changed from CONNECTED to DISCONNECTED
09-09 13:05:24.177  1743  4272 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-09 13:05:24.179  1743  4272 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-09 13:05:24.179  1743  4272 I SystemUpdateService: now status is 0 (complete)
09-09 13:05:24.179  1743  4272 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 13:05:24.179  1743  4272 I SystemUpdateService: file has been verified
09-09 13:05:24.180  1743  4272 I SystemUpdateService: OTA package size = 12249756
,09-09 13:05:24.197  1743  4272 I SystemUpdateService: showing system update notification
,09-09 13:05:24.204  1743  1743 D SystemUpdateService: onDestroy
,09-09 13:05:28.940   872   889 I ActivityManager: Start proc 4280:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 13:05:29.069  4280  4280 D AdapterServiceConfig: Adding HeadsetService
,09-09 13:05:29.070  4280  4280 D AdapterServiceConfig: Adding A2dpService
09-09 13:05:29.070  4280  4280 D AdapterServiceConfig: Adding HidService
09-09 13:05:29.070  4280  4280 D AdapterServiceConfig: Adding HealthService
,09-09 13:05:29.070  4280  4280 D AdapterServiceConfig: Adding PanService
09-09 13:05:29.070  4280  4280 D AdapterServiceConfig: Adding GattService
09-09 13:05:29.070  4280  4280 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 13:05:29.082   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5528908:true
,09-09 13:05:29.084  4280  4280 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 13:05:29.092  4280  4292 I BluetoothAdapterState: Entering OffState
,09-09 13:05:29.092  4280  4280 I bt_bluedroid: init
,09-09 13:05:29.099  4280  4293 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 13:05:29.099  4280  4293 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 13:05:29.099  4280  4293 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 13:05:29.100  4280  4293 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 13:05:29.102  4280  4280 I bt_bluedroid: get_profile_interface socket
,09-09 13:05:29.104  4280  4296 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 13:05:29.106  4280  4296 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:05:29.107  4280  4280 I bt_bluedroid: get_profile_interface sdp
,09-09 13:05:29.113  4280  4291 I bt_bluedroid: config_hci_snoop_log
,09-09 13:05:29.115   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 13:05:29.122  4280  4292 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 13:05:29.122  4280  4292 D BluetoothAdapterProperties: Setting state to 14
09-09 13:05:29.123  4280  4292 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-09 13:05:29.125  4280  4292 D BluetoothBondStateMachine: make
,09-09 13:05:29.129  4280  4297 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 13:05:29.135  4280  4292 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:05:29.137  4280  4280 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 13:05:29.143  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:29.145  4280  4280 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:05:29.146  4280  4280 D BtGatt.GattService: Received start request. Starting profile...
,09-09 13:05:29.146  4280  4280 D BtGatt.GattService: start()
,09-09 13:05:29.146  4280  4280 I bt_bluedroid: get_profile_interface gatt
09-09 13:05:29.149  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:29.149  4280  4280 D BtGatt.AdvertiseManager: advertise manager created
,09-09 13:05:29.162  4280  4280 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:05:29.162  4280  4280 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:29.163  4280  4280 V BluetoothAdapterState: isBleTurningOn()=true
09-09 13:05:29.163  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:29.164  4280  4292 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 13:05:29.165  4280  4292 I bt_bluedroid: enable
,09-09 13:05:29.166  4280  4293 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 13:05:29.167  4280  4293 I bt_hci  : start_up
,09-09 13:05:29.187  4280  4293 I bt_vendor: alloc value 0xb3a22189
,09-09 13:05:29.187  4280  4293 I bt_vendor: init
09-09 13:05:29.187  4280  4293 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 13:05:29.187  4280  4293 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 13:05:29.297  4280  4293 D bt_hci  : start_up starting async portion
,09-09 13:05:29.297  4280  4300 I bt_hci  : event_finish_startup
,09-09 13:05:29.297  4280  4300 I bt_hci_h4: hal_open
09-09 13:05:29.298  4280  4300 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 13:05:29.306  4280  4300 I bt_userial_vendor: device fd = 51 open
,09-09 13:05:29.339  4280  4300 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:05:29.373  4280  4300 D bt_hwcfg: Chipset BCM4354A2
,09-09 13:05:29.373  4280  4300 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 13:05:29.375  4280  4300 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 13:05:29.427   872  1316 D ConnectivityService: handlePromptUnvalidated 101
,09-09 13:05:30.034  4280  4300 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-09 13:05:30.035  4280  4300 D bt_hwcfg: Settlement delay -- 100 ms
09-09 13:05:30.035  4280  4300 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 13:05:30.152  4280  4300 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:05:30.153  4280  4300 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 13:05:30.183  4280  4300 I bt_hwcfg: vendor lib fwcfg completed
09-09 13:05:30.184  4280  4300 I bt_vendor: firmware callback
09-09 13:05:30.184  4280  4300 I bt_hci  : firmware_config_callback
,09-09 13:05:30.195  4280  4302 I bt_btu  : btu_task pending for preload complete event
09-09 13:05:30.196  4280  4302 I bt_btu_task: Bluetooth chip preload is complete
,09-09 13:05:30.196  4280  4302 I bt_btu  : btu_task received preload complete event
,09-09 13:05:30.206  4280  4302 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 13:05:30.207  4280  4302 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 13:05:30.207  4280  4302 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 13:05:30.207  4280  4302 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 13:05:30.207  4280  4302 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 13:05:30.208  4280  4302 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 13:05:30.208  4280  4302 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 13:05:30.208  4280  4302 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 13:05:30.209  4280  4302 I         : BTE_InitTraceLevels -- TRC_GAP
,09-09 13:05:30.209  4280  4302 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 13:05:30.209  4280  4302 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 13:05:30.209  4280  4302 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 13:05:30.210  4280  4302 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 13:05:30.211  4280  4302 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-09 13:05:30.211  4280  4302 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 13:05:30.341  4280  4302 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399fd9d
,09-09 13:05:30.341  4280  4302 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399fd9d 
,09-09 13:05:30.365  4280  4296 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 13:05:30.367  4280  4296 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 13:05:30.369  4280  4296 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 13:05:30.377  4280  4296 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:05:30.382  4280  4296 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:05:30.382  4280  4296 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:05:30.383  4280  4296 D bt_hci  : do_postload posting postload work item
,09-09 13:05:30.384  4280  4300 I bt_hci  : event_postload
09-09 13:05:30.384  4280  4300 I bt_vendor: sco_config_cb
,09-09 13:05:30.384  4280  4300 I bt_hci  : sco_config_callback postload finished.
09-09 13:05:30.386  4280  4300 I bt_vendor: low_power_mode_cb
,09-09 13:05:30.387  4280  4296 D bt_bte_conf: Device ID record 1 : primary
09-09 13:05:30.387  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:30.387  4280  4296 D bt_bte_conf:   vendorId            = 000f
,09-09 13:05:30.387  4280  4296 D bt_bte_conf:   vendorIdSource      = 0001
09-09 13:05:30.388  4280  4296 D bt_bte_conf:   product             = 1200
09-09 13:05:30.388  4280  4296 D bt_bte_conf:   version             = 1436
09-09 13:05:30.389  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:30.390  4280  4296 D bt_bte_conf:   clientExecutableURL = 
09-09 13:05:30.391  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:30.391  4280  4296 D bt_bte_conf:   serviceDescription  = 
09-09 13:05:30.392  4280  4296 D bt_bte_conf:   documentationURL    = 
09-09 13:05:30.393  4280  4296 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 13:05:30.394  4280  4293 D bt_stack_manager: event_start_up_stack finished
,09-09 13:05:30.395  4280  4292 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 13:05:30.396  4280  4292 D BluetoothAdapterProperties: Setting state to 15
,09-09 13:05:30.396  4280  4292 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 13:05:30.398  4280  4292 I BluetoothAdapterState: Entering BleOnState
,09-09 13:05:30.400  4280  4292 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 13:05:30.400  4280  4292 D BluetoothAdapterProperties: Setting state to 11
09-09 13:05:30.401  4280  4292 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 13:05:30.409  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:30.410  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:30.410  4280  4280 D HeadsetService: Received start request. Starting profile...
09-09 13:05:30.411  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:30.414  4280  4280 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 13:05:30.414  4280  4280 D HeadsetStateMachine: make
09-09 13:05:30.415  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:30.424  4280  4292 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:05:30.425  4280  4280 D HeadsetStateMachine: max_hf_connections = 1
09-09 13:05:30.425  4280  4280 I bt_bluedroid: get_profile_interface handsfree
09-09 13:05:30.425  4280  4296 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 13:05:30.426  4280  4296 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 13:05:30.432  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:30.432  4280  4280 D A2dpService: Received start request. Starting profile...
,09-09 13:05:30.433  4280  4280 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 13:05:30.434  4280  4280 I bt_bluedroid: get_profile_interface avrcp
,09-09 13:05:30.442  4280  4280 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 13:05:30.443  4280  4280 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:05:30.443  4280  4280 D A2dpStateMachine: make
,09-09 13:05:30.445  4280  4280 I bt_bluedroid: get_profile_interface a2dp
,09-09 13:05:30.446  4280  4296 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-09 13:05:30.448  4280  4280 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 13:05:30.448  4280  4311 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:05:30.449  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:30.451  4043  4043 D BluetoothInputDevice: Proxy object connected
,09-09 13:05:30.451  4280  4280 D HidService: Received start request. Starting profile...
09-09 13:05:30.452  4043  4043 D HidProfile: Bluetooth service connected
09-09 13:05:30.452  4280  4280 I bt_bluedroid: get_profile_interface hidhost
09-09 13:05:30.452  4280  4296 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39813e5
09-09 13:05:30.452  4280  4280 D HidService: setHidService(): set to: null
09-09 13:05:30.452  4280  4296 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-09 13:05:30.455  4280  4280 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 13:05:30.456  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:05:30.457  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:30.458  4280  4280 D HealthService: Received start request. Starting profile...
,09-09 13:05:30.460  4280  4280 I bt_bluedroid: get_profile_interface health
,09-09 13:05:30.464  4280  4280 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 13:05:30.465  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:30.467  4043  4043 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 13:05:30.468  4043  4043 D PanProfile: Bluetooth service connected
09-09 13:05:30.468  4280  4280 D PanService: Received start request. Starting profile...
09-09 13:05:30.472  4280  4280 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:05:30.472  4280  4280 I bt_bluedroid: get_profile_interface pan
,09-09 13:05:30.472  4280  4296 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:05:30.477  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:30.479  4043  4043 D BluetoothMap: Proxy object connected
09-09 13:05:30.479  4043  4043 D MapProfile: Bluetooth service connected
,09-09 13:05:30.480  4043  4043 D BluetoothMap: getConnectedDevices()
09-09 13:05:30.480  4280  4280 D BluetoothMapService: Received start request. Starting profile...
09-09 13:05:30.481  4043  4043 D BluetoothMap: Bluetooth is Not enabled
09-09 13:05:30.481  4280  4280 D BluetoothMapService: start()
,09-09 13:05:30.483  4280  4280 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 13:05:30.484  4280  4280 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 13:05:30.484  4280  4280 D BluetoothMapAppObserver: createReceiver()
,09-09 13:05:30.486  4280  4280 D BluetoothMapAppObserver: initObservers()
09-09 13:05:30.486  4280  4280 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 13:05:30.492  4280  4280 V BluetoothAdapterState: isTurningOff()=false
09-09 13:05:30.492  4280  4280 V BluetoothAdapterState: isTurningOn()=true
09-09 13:05:30.492  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:30.492  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:30.494  4280  4280 V BluetoothAdapterState: isTurningOff()=false
09-09 13:05:30.494  4280  4280 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:05:30.494  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:30.494  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:30.494  4280  4309 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:05:30.494  4280  4280 V BluetoothAdapterState: isTurningOff()=false
09-09 13:05:30.495  4280  4280 V BluetoothAdapterState: isTurningOn()=true
09-09 13:05:30.495  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:30.495  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:30.495  4280  4280 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:05:30.496  4280  4280 V BluetoothAdapterState: isTurningOn()=true
09-09 13:05:30.496  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:30.496  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:30.496  4280  4280 V BluetoothAdapterState: isTurningOff()=false
09-09 13:05:30.496  4280  4280 V BluetoothAdapterState: isTurningOn()=true
09-09 13:05:30.496  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:30.496  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:30.496  4280  4280 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:05:30.497  4280  4280 V BluetoothAdapterState: isTurningOn()=true
09-09 13:05:30.497  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:30.497  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:30.497  4280  4292 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-09 13:05:30.497  4280  4292 D BluetoothAdapterProperties: ScanMode =  20
,09-09 13:05:30.497  4280  4292 D BluetoothAdapterProperties: State =  11
09-09 13:05:30.498  4280  4292 D BluetoothAdapterProperties: Setting state to 12
,09-09 13:05:30.498  4280  4292 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 13:05:30.498   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:05:30.499  1361  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:05:30.499  4280  4296 D BluetoothAdapterProperties: Scan Mode:21
09-09 13:05:30.500  4280  4296 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:05:30.500   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:05:30.500  4280  4292 I BluetoothAdapterState: Entering OnState
,09-09 13:05:30.501  4043  4053 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 13:05:30.502  1361  1361 D BluetoothA2dp: Proxy object connected
09-09 13:05:30.502  4043  4054 D BluetoothPan: onBluetoothStateChange on: true
,09-09 13:05:30.503   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:05:30.503   872   872 D BluetoothA2dp: Proxy object connected,
09-09 13:05:30.503  1361  1373 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:05:30.506  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:05:30.506  1361  1361 D PanProfile: Bluetooth service connected
09-09 13:05:30.507  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:30.507  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:30.507  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:30.507  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:30.507  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:30.507  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:30.507  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:30.507  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:05:30.508  1361  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:05:30.510  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:30.513  4280  4280 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 13:05:30.514  1361  1361 D BluetoothInputDevice: Proxy object connected
,09-09 13:05:30.514  1361  1361 D HidProfile: Bluetooth service connected
09-09 13:05:30.514  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:30.514  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:30.514  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:30.514  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:30.514  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:30.514  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:30.514  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:30.514  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:30.514  4280  4280 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 13:05:30.514   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:05:30.515  1361  1373 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:05:30.517  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:30.517  1956  2084 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:05:30.517  4280  4280 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:05:30.518  1361  1696 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 13:05:30.520  4280  4280 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:05:30.521  1361  1361 D BluetoothMap: Proxy object connected
,09-09 13:05:30.521  1361  1361 D MapProfile: Bluetooth service connected
,09-09 13:05:30.521  1361  1361 D BluetoothMap: getConnectedDevices()
,09-09 13:05:30.522  4043  4053 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:05:30.522  1361  1373 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:05:30.523  4043  4054 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:05:30.523  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:30.523  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:30.523  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:30.523  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:30.523  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:30.523  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:30.523  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:30.523  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:30.524  4280  4280 D ObexServerSockets: Succeed to create listening sockets 
,09-09 13:05:30.524  4280  4280 D ObexServerSockets0: startAccept()
09-09 13:05:30.524  4280  4280 D ObexServerSockets0: prepareForNewConnect()
09-09 13:05:30.526  4280  4280 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-09 13:05:30.526  4280  4280 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-09 13:05:30.526  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:30.526   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 13:05:30.527  4280  4318 D ObexServerSockets0: Accepting socket connection...
09-09 13:05:30.527  4280  4319 D ObexServerSockets0: Accepting socket connection...
09-09 13:05:30.528  4280  4280 D BluetoothMapService: onReceive
09-09 13:05:30.528  4280  4280 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:05:30.528  4280  4280 D BluetoothMapService: STATE_ON
09-09 13:05:30.528  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:30.530  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:30.530  4043  4043 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 13:05:30.534  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:30.537  4043  4043 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 13:05:30.543  4043  4043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:05:30.546  4043  4043 D BluetoothA2dp: Proxy object connected
09-09 13:05:30.550  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:05:30.558  1361  1361 D BluetoothPbap: Proxy object connected
09-09 13:05:30.559  1361  1361 D PbapServerProfile: Bluetooth service connected
09-09 13:05:30.559  4280  4280 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 13:05:30.559  4280  4280 D ObexServerSockets0: prepareForNewConnect()
09-09 13:05:30.559  4043  4043 D DockEventReceiver: finishStartingService: stopping service
09-09 13:05:30.560  4043  4043 D BluetoothPbap: Proxy object connected
09-09 13:05:30.560  4043  4043 D PbapServerProfile: Bluetooth service connected
09-09 13:05:30.566  4280  4323 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:05:30.581  4280  4327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:05:30.583  4280  4327 I BtOppRfcommListener: Accept thread started.
,09-09 13:05:30.599  1361  1373 D BluetoothHeadset: Proxy object connected
,09-09 13:05:30.599  1361  1361 D HeadsetProfile: Bluetooth service connected
09-09 13:05:30.600  1956  1967 D BluetoothHeadset: Proxy object connected
09-09 13:05:30.600   872   872 D BluetoothHeadset: Proxy object connected
09-09 13:05:30.600   872   872 D BluetoothHeadset: Proxy object connected
09-09 13:05:30.600   872   872 D BluetoothHeadset: Proxy object connected
,09-09 13:05:30.604   872   889 D BluetoothHeadset: Proxy object connected
,09-09 13:05:30.615   872   889 D BluetoothHeadset: Proxy object connected
,09-09 13:05:30.618  1956  1973 D BluetoothHeadset: Proxy object connected
,09-09 13:05:30.623  1361  1696 D BluetoothHeadset: Proxy object connected
,09-09 13:05:30.623  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-09 13:05:30.641  4043  4054 D BluetoothHeadset: Proxy object connected
,09-09 13:05:30.641  4043  4043 D HeadsetProfile: Bluetooth service connected
,09-09 13:05:33.854  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:33.871  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:33.877  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:33.923  4280  4292 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 13:05:33.924  4280  4292 D BluetoothAdapterProperties: Setting state to 13
09-09 13:05:33.924  4280  4292 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 13:05:33.926  4280  4292 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 13:05:33.929  4280  4292 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:05:33.934  4280  4280 D BluetoothMapService: onReceive
09-09 13:05:33.935  4280  4280 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:05:33.935  4280  4280 D BluetoothMapService: STATE_TURNING_OFF
09-09 13:05:33.935  4280  4280 D BluetoothMapService: MAP Service closeService in
09-09 13:05:33.935  4280  4280 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 13:05:33.935  4280  4280 D ObexServerSockets0: shutdown(block = true)
09-09 13:05:33.936  4280  4280 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:05:33.936  4280  4280 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 13:05:33.936  4280  4318 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 13:05:33.937  4280  4305 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 13:05:33.937  4280  4319 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-09 13:05:33.938  4280  4280 I BtOppRfcommListener: stopping Accept Thread
09-09 13:05:33.939  4280  4327 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:05:33.939  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:33.939  4280  4327 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 13:05:33.939  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:33.939  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:33.939  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:33.939  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:33.939  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:33.939  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:33.939  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:33.939  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:33.941  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:33.941  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:05:33.947  4280  4296 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:05:33.948  4280  4292 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 13:05:33.948  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:33.949  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:33.949  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:33.949  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:33.949  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:33.949  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:33.949  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:33.949  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:33.949  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:33.951  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:33.951  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:05:33.955  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:05:33.955  4280  4280 D HeadsetService: Received stop request...Stopping profile...
09-09 13:05:33.955  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:33.955  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:33.955  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:33.955  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:33.955  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:05:33.955  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:33.955  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:33.955  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:33.956  3956  3956 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:05:33.956  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:33.957  1361  1373 D BluetoothHeadset: Proxy object disconnected
09-09 13:05:33.957  4043  4053 D BluetoothHeadset: Proxy object disconnected
,09-09 13:05:33.958  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 13:05:33.958  1956  2254 D BluetoothHeadset: Proxy object disconnected
09-09 13:05:33.958  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 13:05:33.958   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 13:05:33.958   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 13:05:33.958   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 13:05:33.959  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:33.959  4280  4280 D A2dpService: Received stop request...Stopping profile...
09-09 13:05:33.960  4280  4311 D A2dpStateMachine: Exit Disconnected: -1
09-09 13:05:33.960  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:33.960  1361  1361 D HeadsetProfile: Bluetooth service disconnected
09-09 13:05:33.960  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:05:33.961  4043  4043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 13:05:33.961  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 13:05:33.962   872   872 D BluetoothA2dp: Proxy object disconnected
,09-09 13:05:33.962  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:33.962  1361  1361 D BluetoothA2dp: Proxy object disconnected
09-09 13:05:33.964  4280  4280 D HidService: Received stop request...Stopping profile...
09-09 13:05:33.964  4280  4280 D HidService: Stopping Bluetooth HidService
09-09 13:05:33.965  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-09 13:05:33.965  1361  1361 D HidProfile: Bluetooth service disconnected
,09-09 13:05:33.966  4280  4280 D HealthService: Received stop request...Stopping profile...
09-09 13:05:33.970  4043  4043 D HeadsetProfile: Bluetooth service disconnected
09-09 13:05:33.970  4043  4043 D BluetoothA2dp: Proxy object disconnected
09-09 13:05:33.970  4043  4043 D BluetoothInputDevice: Proxy object disconnected
,09-09 13:05:33.972  4280  4280 D PanService: Received stop request...Stopping profile...
,09-09 13:05:33.970  4043  4043 D HidProfile: Bluetooth service disconnected
,09-09 13:05:33.973  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:05:33.973  4280  4280 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:33.973  1361  1361 D PanProfile: Bluetooth service disconnected
09-09 13:05:33.973  4280  4280 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:33.973  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:33.973  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:33.974  4280  4280 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:05:33.974  4280  4280 D BluetoothMapService: stop()
09-09 13:05:33.974  4280  4280 D BluetoothMapAppObserver: deinitObservers()
09-09 13:05:33.974  4280  4280 D BluetoothMapAppObserver: removeReceiver()
,09-09 13:05:33.975  1361  1361 D BluetoothMap: Proxy object disconnected
09-09 13:05:33.976  4043  4043 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:05:33.975  1361  1361 D MapProfile: Bluetooth service disconnected
,09-09 13:05:33.976  4280  4280 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:05:33.976  4280  4296 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 13:05:33.977  4280  4302 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:05:33.977  4280  4302 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:05:33.977  4280  4302 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:05:33.977  4280  4296 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 13:05:33.977  4043  4043 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:05:33.977  4043  4043 D PanProfile: Bluetooth service disconnected
09-09 13:05:33.977  4043  4043 D BluetoothMap: Proxy object disconnected
09-09 13:05:33.977  4043  4043 D MapProfile: Bluetooth service disconnected
09-09 13:05:33.976  4280  4280 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:05:33.978  4280  4280 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:33.978  4280  4280 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:33.978  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:33.978  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:33.979  4280  4296 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 13:05:33.979  4280  4302 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:05:33.979  4280  4302 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:05:33.979  4280  4302 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:05:33.980  4280  4280 V BluetoothAdapterState: isTurningOff()=true
,09-09 13:05:33.980  4280  4302 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:05:33.980  4280  4280 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:33.980  4280  4302 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:05:33.980  4280  4302 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 13:05:33.980  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:33.980  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:33.980  4280  4280 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 13:05:33.980  4280  4296 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 13:05:33.980  4280  4280 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:05:33.980  4280  4280 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:33.981  4280  4280 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:33.981  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:33.981  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:33.981  4280  4280 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:05:33.981  4280  4296 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 13:05:33.981  4280  4280 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 13:05:33.982  4280  4280 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:33.982  4280  4280 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:33.982  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:33.982  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:33.984  4280  4280 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:05:33.984  4280  4280 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:05:33.985  4280  4280 D BluetoothMapService: MAP Service closeService in
09-09 13:05:33.985  4280  4280 V BluetoothAdapterState: isTurningOff()=true
09-09 13:05:33.987  4280  4280 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:05:33.987  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:33.987  3705  3705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 13:05:33.987  4280  4280 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:33.987  3705  3705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 13:05:33.987  4280  4292 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 13:05:33.987  4280  4280 D BluetoothMapService: cleanup()
09-09 13:05:33.987  4280  4292 D BluetoothAdapterProperties: Setting state to 15
09-09 13:05:33.988  4280  4292 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 13:05:33.988  4280  4280 D BluetoothMapService: MAP Service closeService in
09-09 13:05:33.988   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:33.988  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:05:33.989  4280  4292 I BluetoothAdapterState: Entering BleOnState
09-09 13:05:33.989  1361  1373 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:05:33.990   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:05:33.989  3705  3705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
09-09 13:05:33.990  4043  4054 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:05:33.991  4043  4053 D BluetoothPan: onBluetoothStateChange on: false
,09-09 13:05:33.991  1361  1361 D BluetoothPbap: Proxy object disconnected
09-09 13:05:33.991  1361  1361 D PbapServerProfile: Bluetooth service disconnected
09-09 13:05:33.991   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:33.992  1361  1373 D BluetoothPan: onBluetoothStateChange on: false
09-09 13:05:33.992  4043  4043 D BluetoothPbap: Proxy object disconnected
09-09 13:05:33.992  4043  4043 D PbapServerProfile: Bluetooth service disconnected
09-09 13:05:33.994  1361  1372 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:05:33.996   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:33.996  4043  4053 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:33.997  1361  1696 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:05:33.997  1956  2084 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:33.997  1361  1373 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:05:33.998  4043  4054 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:05:33.998  4043  4334 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:05:33.998  1361  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:05:33.999  4043  4053 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:05:33.999  4280  4292 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-09 13:05:33.999  4280  4292 D BluetoothAdapterProperties: Setting state to 16
09-09 13:05:33.999  4280  4292 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 13:05:34.000  4280  4292 D BluetoothAdapterProperties: onBleDisable
09-09 13:05:34.000  4280  4292 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:05:34.000  4280  4293 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 13:05:34.002  4280  4296 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:05:34.002  4280  4302 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 13:05:34.002  4280  4302 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:05:34.006  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:34.006  4043  4043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 13:05:34.007  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:34.008  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:34.009  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:34.010  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:34.011  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:34.013  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:05:34.020  4043  4043 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:05:34.203  4280  4296 I bt_hci  : shut_down
,09-09 13:05:34.221  4280  4300 D bt_hwcfg: hw_epilog_process
,09-09 13:05:34.221  4280  4300 I bt_vendor: low_power_mode_cb
,09-09 13:05:34.239  4280  4300 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 13:05:34.239  4280  4300 I bt_vendor: epilog_cb
09-09 13:05:34.239  4280  4300 I bt_hci  : epilog_finished_callback
,09-09 13:05:34.246  4280  4296 I bt_hci_h4: hal_close
,09-09 13:05:34.247  4280  4296 I bt_userial_vendor: device fd = 51 close
,09-09 13:05:34.372  4280  4293 D bt_stack_manager: event_shut_down_stack finished.
,09-09 13:05:34.372  4280  4292 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 13:05:34.381  4280  4280 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:05:34.384  4280  4280 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 13:05:34.384  4280  4280 D BtGatt.GattService: stop()
,09-09 13:05:34.385  4280  4280 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 13:05:34.384  4280  4292 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-09 13:05:34.391  4280  4280 V BluetoothAdapterState: isTurningOff()=false
09-09 13:05:34.392  4280  4280 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:05:34.392  4280  4280 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:34.392  4280  4280 V BluetoothAdapterState: isBleTurningOff()=true
09-09 13:05:34.393  4280  4292 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 13:05:34.394  4280  4292 D BluetoothAdapterProperties: Setting state to 10
09-09 13:05:34.394  4280  4292 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 13:05:34.396  4280  4292 I BluetoothAdapterState: Entering OffState
09-09 13:05:34.397   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 13:05:34.424  4280  4280 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-09 13:05:34.424  4280  4280 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 13:05:34.425  4280  4293 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 13:05:34.432  4280  4293 D bt_stack_manager: event_clean_up_stack finished.
,09-09 13:05:34.433  4280  4280 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 13:05:34.437  4280  4280 I art     : System.exit called, status: 0
09-09 13:05:34.438  4280  4280 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 13:05:34.479   872  2015 I ActivityManager: Process com.android.bluetooth (pid 4280) has died
,09-09 13:05:38.920  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:05:38.921  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:38.925  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:38.926  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6952356 removed from the list
09-09 13:05:38.926  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:38.926  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:38.926  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:38.929  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:05:38.930  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6b550c4 added. We now have 4 listener(s)
,09-09 13:05:38.930  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:05:38.932  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:05:38.932  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6b550c4 removed from the list
09-09 13:05:38.933  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:05:38.933  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:38.933  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:05:38.935  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:05:38.936  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5674bad added. We now have 4 listener(s)
09-09 13:05:38.936  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:05:43.947  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:43.997   872   889 I ActivityManager: Start proc 4339:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 13:05:44.141  4339  4339 D AdapterServiceConfig: Adding HeadsetService
09-09 13:05:44.141  4339  4339 D AdapterServiceConfig: Adding A2dpService
09-09 13:05:44.141  4339  4339 D AdapterServiceConfig: Adding HidService
09-09 13:05:44.142  4339  4339 D AdapterServiceConfig: Adding HealthService
09-09 13:05:44.142  4339  4339 D AdapterServiceConfig: Adding PanService
09-09 13:05:44.142  4339  4339 D AdapterServiceConfig: Adding GattService
09-09 13:05:44.142  4339  4339 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 13:05:44.153   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e3f673f:true
,09-09 13:05:44.154  4339  4339 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 13:05:44.159  4339  4339 I bt_bluedroid: init
,09-09 13:05:44.159  4339  4351 I BluetoothAdapterState: Entering OffState
,09-09 13:05:44.165  4339  4352 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 13:05:44.165  4339  4352 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 13:05:44.165  4339  4352 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 13:05:44.166  4339  4352 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 13:05:44.168  4339  4339 I bt_bluedroid: get_profile_interface socket
,09-09 13:05:44.170  4339  4339 I bt_bluedroid: get_profile_interface sdp
,09-09 13:05:44.174  4339  4350 I bt_bluedroid: config_hci_snoop_log
09-09 13:05:44.176   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 13:05:44.177  4339  4355 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-09 13:05:44.179  4339  4355 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:05:44.181  4339  4351 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 13:05:44.182  4339  4351 D BluetoothAdapterProperties: Setting state to 14
,09-09 13:05:44.187  4339  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-09 13:05:44.189  4339  4351 D BluetoothBondStateMachine: make
,09-09 13:05:44.193  4339  4356 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 13:05:44.195  4339  4339 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 13:05:44.197  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:44.197  4339  4339 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:05:44.198  4339  4351 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:05:44.199  4339  4339 D BtGatt.GattService: Received start request. Starting profile...
09-09 13:05:44.199  4339  4339 D BtGatt.GattService: start()
09-09 13:05:44.199  4339  4339 I bt_bluedroid: get_profile_interface gatt
09-09 13:05:44.199  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
09-09 13:05:44.200  4339  4339 D BtGatt.AdvertiseManager: advertise manager created
,09-09 13:05:44.208  4339  4339 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:05:44.208  4339  4339 V BluetoothAdapterState: isTurningOn()=false
09-09 13:05:44.208  4339  4339 V BluetoothAdapterState: isBleTurningOn()=true
09-09 13:05:44.208  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:44.208  4339  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 13:05:44.208  4339  4351 I bt_bluedroid: enable
09-09 13:05:44.209  4339  4352 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 13:05:44.210  4339  4352 I bt_hci  : start_up
,09-09 13:05:44.219  4339  4352 I bt_vendor: alloc value 0xb3a22189
09-09 13:05:44.219  4339  4352 I bt_vendor: init
,09-09 13:05:44.219  4339  4352 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 13:05:44.219  4339  4352 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 13:05:44.328  4339  4352 D bt_hci  : start_up starting async portion
,09-09 13:05:44.329  4339  4359 I bt_hci  : event_finish_startup
09-09 13:05:44.329  4339  4359 I bt_hci_h4: hal_open
09-09 13:05:44.329  4339  4359 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 13:05:44.338  4339  4359 I bt_userial_vendor: device fd = 51 open
,09-09 13:05:44.371  4339  4359 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:05:44.403  4339  4359 D bt_hwcfg: Chipset BCM4354A2
,09-09 13:05:44.403  4339  4359 D bt_hwcfg: Target name = [BCM4354A2]
09-09 13:05:44.404  4339  4359 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 13:05:45.246  4339  4359 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 13:05:45.248  4339  4359 D bt_hwcfg: Settlement delay -- 100 ms
,09-09 13:05:45.249  4339  4359 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 13:05:45.366  4339  4359 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:05:45.368  4339  4359 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 13:05:45.396  4339  4359 I bt_hwcfg: vendor lib fwcfg completed
,09-09 13:05:45.397  4339  4359 I bt_vendor: firmware callback
09-09 13:05:45.397  4339  4359 I bt_hci  : firmware_config_callback
,09-09 13:05:45.411  4339  4361 I bt_btu  : btu_task pending for preload complete event
,09-09 13:05:45.411  4339  4361 I bt_btu_task: Bluetooth chip preload is complete
09-09 13:05:45.412  4339  4361 I bt_btu  : btu_task received preload complete event
,09-09 13:05:45.421  4339  4361 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 13:05:45.421  4339  4361 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 13:05:45.422  4339  4361 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 13:05:45.422  4339  4361 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 13:05:45.422  4339  4361 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 13:05:45.422  4339  4361 I         : BTE_InitTraceLevels -- TRC_A2D
,09-09 13:05:45.423  4339  4361 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 13:05:45.423  4339  4361 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 13:05:45.423  4339  4361 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 13:05:45.423  4339  4361 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 13:05:45.424  4339  4361 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 13:05:45.424  4339  4361 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 13:05:45.424  4339  4361 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 13:05:45.424  4339  4361 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 13:05:45.425  4339  4361 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 13:05:45.572  4339  4361 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399fd9d
,09-09 13:05:45.573  4339  4361 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399fd9d 
,09-09 13:05:45.585  4339  4355 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 13:05:45.588  4339  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 13:05:45.589  4339  4355 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 13:05:45.595  4339  4355 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:05:45.599  4339  4355 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:05:45.600  4339  4355 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:05:45.600  4339  4355 D bt_hci  : do_postload posting postload work item
,09-09 13:05:45.600  4339  4359 I bt_hci  : event_postload
09-09 13:05:45.601  4339  4359 I bt_vendor: sco_config_cb
09-09 13:05:45.601  4339  4359 I bt_hci  : sco_config_callback postload finished.
09-09 13:05:45.606  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:45.606  4339  4355 D bt_bte_conf: Device ID record 1 : primary
09-09 13:05:45.606  4339  4355 D bt_bte_conf:   vendorId            = 000f
09-09 13:05:45.606  4339  4355 D bt_bte_conf:   vendorIdSource      = 0001
09-09 13:05:45.606  4339  4355 D bt_bte_conf:   product             = 1200
09-09 13:05:45.606  4339  4355 D bt_bte_conf:   version             = 1436
,09-09 13:05:45.606  4339  4355 D bt_bte_conf:   clientExecutableURL = 
09-09 13:05:45.606  4339  4355 D bt_bte_conf:   serviceDescription  = 
09-09 13:05:45.607  4339  4355 D bt_bte_conf:   documentationURL    = 
09-09 13:05:45.607  4339  4355 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 13:05:45.607  4339  4352 D bt_stack_manager: event_start_up_stack finished
09-09 13:05:45.607  4339  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 13:05:45.607  4339  4351 D BluetoothAdapterProperties: Setting state to 15
09-09 13:05:45.607  4339  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 13:05:45.608  4339  4351 I BluetoothAdapterState: Entering BleOnState
,09-09 13:05:45.609  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:45.615  4339  4351 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 13:05:45.615  4339  4351 D BluetoothAdapterProperties: Setting state to 11
09-09 13:05:45.615  4339  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 13:05:45.616  4339  4359 I bt_vendor: low_power_mode_cb
,09-09 13:05:45.627  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:45.629  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:45.632  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:45.635  4339  4339 D HeadsetService: Received start request. Starting profile...
,09-09 13:05:45.638  4339  4339 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 13:05:45.639  4339  4339 D HeadsetStateMachine: make
,09-09 13:05:45.641  4339  4351 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:05:45.650  4339  4339 D HeadsetStateMachine: max_hf_connections = 1
,09-09 13:05:45.650  4339  4339 I bt_bluedroid: get_profile_interface handsfree
,09-09 13:05:45.650  4339  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 13:05:45.651  4339  4355 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-09 13:05:45.656  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:45.657  4339  4339 D A2dpService: Received start request. Starting profile...
,09-09 13:05:45.657  4339  4339 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 13:05:45.658  4339  4339 I bt_bluedroid: get_profile_interface avrcp
,09-09 13:05:45.665  4339  4339 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 13:05:45.665  4339  4339 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:05:45.665  4339  4339 D A2dpStateMachine: make
,09-09 13:05:45.666  4339  4339 I bt_bluedroid: get_profile_interface a2dp
,09-09 13:05:45.667  4339  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 13:05:45.669  4339  4370 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:05:45.669  4339  4339 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 13:05:45.670  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:45.671  4339  4339 D HidService: Received start request. Starting profile...
09-09 13:05:45.671  4339  4339 I bt_bluedroid: get_profile_interface hidhost
09-09 13:05:45.671  4339  4339 D HidService: setHidService(): set to: null
,09-09 13:05:45.671  4339  4355 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39813e5
09-09 13:05:45.672  4339  4355 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 13:05:45.672  4339  4339 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 13:05:45.673  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:45.674  4339  4339 D HealthService: Received start request. Starting profile...
,09-09 13:05:45.675  4339  4339 I bt_bluedroid: get_profile_interface health
,09-09 13:05:45.678  4339  4339 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 13:05:45.679  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:05:45.679  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
09-09 13:05:45.679  4339  4339 D PanService: Received start request. Starting profile...
09-09 13:05:45.680  4339  4339 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:05:45.680  4339  4339 I bt_bluedroid: get_profile_interface pan
09-09 13:05:45.680  4339  4355 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:05:45.682  4339  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
,09-09 13:05:45.683  4339  4339 D BluetoothMapService: Received start request. Starting profile...
09-09 13:05:45.683  4339  4339 D BluetoothMapService: start()
,09-09 13:05:45.686  4339  4339 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 13:05:45.686  4339  4339 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 13:05:45.687  4339  4339 D BluetoothMapAppObserver: createReceiver()
,09-09 13:05:45.688  4339  4339 D BluetoothMapAppObserver: initObservers()
09-09 13:05:45.688  4339  4339 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 13:05:45.696  4339  4339 V BluetoothAdapterState: isTurningOff()=false
09-09 13:05:45.696  4339  4339 V BluetoothAdapterState: isTurningOn()=true
09-09 13:05:45.696  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:45.696  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:45.698  4339  4339 V BluetoothAdapterState: isTurningOff()=false
09-09 13:05:45.698  4339  4339 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:05:45.698  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:45.698  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:05:45.698  4339  4339 V BluetoothAdapterState: isTurningOff()=false
09-09 13:05:45.698  4339  4339 V BluetoothAdapterState: isTurningOn()=true
09-09 13:05:45.698  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:05:45.698  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:45.698  4339  4339 V BluetoothAdapterState: isTurningOff()=false
09-09 13:05:45.699  4339  4339 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:05:45.699  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:45.699  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:45.699  4339  4368 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 13:05:45.699  4339  4339 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:05:45.699  4339  4339 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:05:45.699  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:45.699  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:45.699  4339  4339 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:05:45.699  4339  4339 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:05:45.700  4339  4339 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:05:45.700  4339  4339 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:05:45.700  4339  4351 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 13:05:45.700  4339  4351 D BluetoothAdapterProperties: ScanMode =  20
,09-09 13:05:45.700  4339  4351 D BluetoothAdapterProperties: State =  11
09-09 13:05:45.700  4339  4351 D BluetoothAdapterProperties: Setting state to 12,
,09-09 13:05:45.700  4339  4351 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 13:05:45.700  4339  4351 I BluetoothAdapterState: Entering OnState
,09-09 13:05:45.701   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:05:45.701  1361  1696 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:05:45.703  4339  4355 D BluetoothAdapterProperties: Scan Mode:21
09-09 13:05:45.703  4339  4355 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:05:45.704   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:05:45.704  1361  1361 D BluetoothA2dp: Proxy object connected
09-09 13:05:45.705   872   872 D BluetoothA2dp: Proxy object connected
09-09 13:05:45.706  4043  4053 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:05:45.707  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:45.707  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:45.707  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:45.707  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:45.707  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:45.707  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:45.707  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:45.707  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:45.709  4043  4334 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:05:45.709  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:45.710   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:05:45.711  1361  1372 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:05:45.712  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:05:45.712  1361  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:05:45.712  1361  1361 D PanProfile: Bluetooth service connected
,09-09 13:05:45.713  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:45.713  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:45.713  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:45.713  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:45.713  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:45.713  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:45.713  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:45.713  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:05:45.713   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:05:45.714  1361  1361 D BluetoothInputDevice: Proxy object connected
09-09 13:05:45.714  1361  1361 D HidProfile: Bluetooth service connected
09-09 13:05:45.714  4043  4054 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:05:45.714  4339  4339 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 13:05:45.714  1361  1696 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:05:45.714  4339  4339 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 13:05:45.715  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:05:45.716  4043  4043 D BluetoothInputDevice: Proxy object connected
09-09 13:05:45.716  4339  4339 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:05:45.716  4043  4043 D HidProfile: Bluetooth service connected
09-09 13:05:45.716  1956  2084 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:05:45.717  1361  1373 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:05:45.718  4043  4334 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:05:45.718  4339  4339 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:05:45.720  4339  4339 D ObexServerSockets: Succeed to create listening sockets 
09-09 13:05:45.720  4339  4339 D ObexServerSockets0: startAccept()
09-09 13:05:45.720  4043  4054 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 13:05:45.720  4339  4339 D ObexServerSockets0: prepareForNewConnect()
09-09 13:05:45.721  1361  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:05:45.721  4339  4339 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 13:05:45.721  4339  4339 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 13:05:45.722  4043  4053 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:05:45.722  1361  1361 D BluetoothMap: Proxy object connected
09-09 13:05:45.722  1361  1361 D MapProfile: Bluetooth service connected
09-09 13:05:45.722  1361  1361 D BluetoothMap: getConnectedDevices()
09-09 13:05:45.724  4339  4376 D ObexServerSockets0: Accepting socket connection...
09-09 13:05:45.724   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 13:05:45.725  4339  4339 D BluetoothMapService: onReceive
09-09 13:05:45.725  4339  4339 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:05:45.725  4339  4339 D BluetoothMapService: STATE_ON
09-09 13:05:45.726  4339  4377 D ObexServerSockets0: Accepting socket connection...
09-09 13:05:45.726  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:45.727  4043  4043 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:05:45.727  4043  4043 D PanProfile: Bluetooth service connected
09-09 13:05:45.727  4043  4043 D BluetoothA2dp: Proxy object connected
09-09 13:05:45.728  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:05:45.729  4043  4043 D BluetoothMap: Proxy object connected
,09-09 13:05:45.730  4043  4043 D MapProfile: Bluetooth service connected
09-09 13:05:45.730  4043  4043 D BluetoothMap: getConnectedDevices()
09-09 13:05:45.736  4043  4043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 13:05:45.742  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:05:45.744  4043  4043 D DockEventReceiver: finishStartingService: stopping service
09-09 13:05:45.752  1361  1361 D BluetoothPbap: Proxy object connected
09-09 13:05:45.752  4043  4043 D BluetoothPbap: Proxy object connected
09-09 13:05:45.752  1361  1361 D PbapServerProfile: Bluetooth service connected
09-09 13:05:45.752  4043  4043 D PbapServerProfile: Bluetooth service connected
09-09 13:05:45.752  4339  4339 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 13:05:45.752  4339  4339 D ObexServerSockets0: prepareForNewConnect()
,09-09 13:05:45.760  4339  4382 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:05:45.776  4339  4386 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:05:45.777  4339  4386 I BtOppRfcommListener: Accept thread started.
,09-09 13:05:45.802  1361  1373 D BluetoothHeadset: Proxy object connected
,09-09 13:05:45.803  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-09 13:05:45.803  4043  4054 D BluetoothHeadset: Proxy object connected
09-09 13:05:45.803  4043  4043 D HeadsetProfile: Bluetooth service connected
09-09 13:05:45.803  1956  1967 D BluetoothHeadset: Proxy object connected
09-09 13:05:45.803   872   872 D BluetoothHeadset: Proxy object connected
09-09 13:05:45.804   872   872 D BluetoothHeadset: Proxy object connected
09-09 13:05:45.804   872   872 D BluetoothHeadset: Proxy object connected
,09-09 13:05:45.811   872   889 D BluetoothHeadset: Proxy object connected
,09-09 13:05:45.814   872   889 D BluetoothHeadset: Proxy object connected
,09-09 13:05:45.814  4043  4334 D BluetoothHeadset: Proxy object connected
09-09 13:05:45.814  4043  4043 D HeadsetProfile: Bluetooth service connected
,09-09 13:05:45.817  1956  1973 D BluetoothHeadset: Proxy object connected
,09-09 13:05:45.822  1361  1372 D BluetoothHeadset: Proxy object connected
09-09 13:05:45.822  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-09 13:05:48.968  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:48.968  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:48.968  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:48.968  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:05:48.968  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:48.968  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:48.968  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:48.968  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:05:48.975  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:05:48.976  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:05:48.976  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5674bad removed from the list
,09-09 13:05:48.977  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:05:48.977  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:05:48.977  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:48.980  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:05:48.980  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad81ee2 added. We now have 4 listener(s)
,09-09 13:05:48.981  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:05:48.985   872  1391 D WifiService: setWifiEnabled: false pid=3956, uid=10000
,09-09 13:05:48.985   872  1391 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:05:54.000  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:05:54.003   872   883 D WifiService: setWifiEnabled: true pid=3956, uid=10000
,09-09 13:05:54.003   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:05:54.030   872  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:05:54.048   872  1314 D WifiConfigStore: loaded 0 passpoint configs
,09-09 13:05:54.069   872  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 13:05:54.073   872  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 13:05:54.080   872  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:05:54.081   872  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 13:05:54.081   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 13:05:54.081   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-09 13:05:54.082  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:54.082  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:54.082  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:54.082  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:54.082  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:54.082  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:54.082  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:54.082  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:05:54.087  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:05:54.095  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:54.095  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:54.095  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:54.095  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:54.095  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:54.095  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:05:54.095  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:05:54.095  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:05:54.099  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:05:54.108   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 13:05:54.108   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 13:05:54.110   371   870 D CommandListener: Setting iface cfg
,09-09 13:05:54.162   872  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-09 13:05:54.162   872  1314 E native  : do suspend true
,09-09 13:05:54.162   872  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:05:54.178   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:05:54.200   872  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 13:05:54.204   872  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 13:05:54.293  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:54.301  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:05:54.302  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-09 13:05:54.322  1514  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 13:05:54.322  1514  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 13:05:54.323  1514  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:05:54.323  1514  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:05:54.359  3705  3705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 13:05:54.359  3705  3705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 13:05:54.360  3705  3705 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-09 13:05:55.461   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 13:05:55.592   872  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.50 rxSuccessRate=9.69 delta 1000 -> 994
,09-09 13:05:55.594   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 13:05:55.594   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:05:55.611   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 13:05:55.658   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 13:05:55.661  1475  1475 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 13:05:56.108  1475  1475 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 13:05:56.159  1475  1475 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:05:56.160  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 13:05:56.168   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:05:56.187   872  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:05:56.188   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:05:56.189   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:05:56.215   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:05:56.235   371   870 D CommandListener: Setting iface cfg
,09-09 13:05:56.238   872  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 13:05:56.252   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 13:05:56.279   872  4396 D DhcpClient: Receive thread started
,09-09 13:05:56.366   872  1314 E native  : do suspend false
,09-09 13:05:56.389   872  2094 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 13:05:56.413   872  4396 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-09 13:05:56.414   872  2094 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-09 13:05:56.417   872  2094 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 13:05:56.430   872  4396 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 13:05:56.432   872  2094 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 13:05:56.436   371   870 D CommandListener: Setting iface cfg
,09-09 13:05:56.447   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 13:05:56.448   872  2094 D DhcpClient: Scheduling renewal in 86399s
09-09 13:05:56.452   872  1314 E native  : do suspend true
,09-09 13:05:56.471   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 13:05:56.474   872  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 13:05:56.475   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 13:05:56.478   872  1316 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 13:05:56.489   872  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:05:56.560   872  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 13:05:56.561   872  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 13:05:56.565   872  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 13:05:56.569   872  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 13:05:56.572   872  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 13:05:56.588   872  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 13:05:56.595   872  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-09 13:05:56.595   872  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 13:05:56.595   872  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 13:05:56.595   872  1316 D ConnectivityService:    accepting network in place of null
09-09 13:05:56.596   872  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 13:05:56.596   872  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:05:56.599   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:05:56.630   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:05:56.645   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=208633, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:05:56.666   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:05:56.673   872  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 13:05:56.673   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:05:56.676   872  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-09 13:05:56.679   872   889 D Tethering: MasterInitialState.processMessage what=3
09-09 13:05:56.704  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:56.704  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:56.704  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:56.704  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:56.704  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:56.704  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:56.704  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:05:56.704  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:05:56.706  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:05:56.712  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:56.712  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:56.712  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:56.712  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:56.712  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:56.712  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:56.712  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:05:56.712  3956  3956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:05:56.713  3956  3956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:05:56.717  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 13:05:56.720  1743  1743 D SystemUpdateService: onCreate
,09-09 13:05:56.723  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 13:05:56.730   872  4394 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 13:05:56.743  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:05:56.745  1743  2526 I iu.UploadsManager: num queued entries: 0
,09-09 13:05:56.747  1743  4405 I SystemUpdateService: active receiver: enabled
,09-09 13:05:56.751  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:05:56.752  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 13:05:56.754  4099  4099 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:05:56.758  1743  4407 I MDM     : [187] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 13:05:56.758  1743  4407 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 13:05:56.760  1743  4407 V GoogleAuthProtoRequest: [187] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 13:05:56.761  4099  4099 D SprintDMHelper: simOperator: 
,09-09 13:05:56.761  4099  4099 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:05:56.770  1743  2526 I iu.UploadsManager: num updated entries: 0
,09-09 13:05:56.777  1743  2526 I iu.SyncManager: NEXT; no task
,09-09 13:05:56.777  1743  4405 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:05:56.783  1743  4405 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 13:05:56.784  1743  4405 I SystemUpdateService: now status is 0 (complete)
09-09 13:05:56.784  1743  4405 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 13:05:56.784  1743  4405 I SystemUpdateService: file has been verified
09-09 13:05:56.784  1743  4405 I SystemUpdateService: OTA package size = 12249756
,09-09 13:05:56.810  3181  3190 W art     : Suspending all threads took: 15.650ms
,09-09 13:05:56.826   872  4394 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:05:56 GMT], X-Android-Received-Millis=[1473419156825], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473419156781]}
,09-09 13:05:56.828   872  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 13:05:56.828   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 13:05:56.828   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 13:05:56.829   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:05:56.835  1743  4405 I SystemUpdateService: showing system update notification
,09-09 13:05:56.856  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 13:05:56.856  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 13:05:56.856  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:05:56.856  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:05:56.869  1743  1743 D SystemUpdateService: onDestroy
,09-09 13:05:56.881  1743  4407 E MDM     : [187] SitrepService.a: Error sending sitrep.
,09-09 13:05:56.921  2872  4410 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:05:57.674   872  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 13:05:57.924  1887  1928 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-09 13:05:57.924  1887  1928 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-09 13:05:57.957  1514  1514 I ConfigService: onCreate
,09-09 13:05:59.034  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:05:59.034  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:05:59.034  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:05:59.034  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:05:59.034  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:05:59.034  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:05:59.034  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:05:59.034  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:05:59.041  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:05:59.043  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:05:59.043  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad81ee2 removed from the list
,09-09 13:05:59.044  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:05:59.044  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:05:59.044  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:05:59.056  3956  4420 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-09 13:05:59.057  3956  4420 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:06:02.063  3956  4421 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-09 13:06:02.064  3956  4420 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-09 13:06:02.065  3956  4420 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:06:02.065  3956  4421 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:06:02.066  3956  4420 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:06:02.066  3956  4421 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:06:02.068  3956  4420 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:06:02.068  3956  4421 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:06:02.073  3956  4423 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: OutgoingSocketThread/Sender)
,09-09 13:06:02.077  3956  4420 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:06:02.077  3956  4421 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 13:06:02.083  3956  4424 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: IncomingSocketThread/Sender)
,09-09 13:06:02.086  3956  4426 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: OutgoingSocketThread/Receiver)
,09-09 13:06:02.088  3956  4426 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: OutgoingSocketThread/Receiver)
09-09 13:06:02.089  3956  4426 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:06:02.089  3956  4426 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:06:02.089  3956  4425 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: IncomingSocketThread/Receiver)
,09-09 13:06:02.091  3956  4425 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: IncomingSocketThread/Receiver)
09-09 13:06:02.092  3956  4425 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:06:02.092  3956  4425 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:06:03.020  1514  1514 I ConfigService: onDestroy
,09-09 13:06:04.601   872  1316 D ConnectivityService: handlePromptUnvalidated 102
,09-09 13:06:05.063  3956  4005 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 13:06:05.066  3956  4005 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 13:06:05.074  3956  4005 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8c54dde Bundle[{}]
,09-09 13:06:05.074  3956  4005 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:06:05.074  3956  4005 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 13:06:05.075  3956  4005 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:06:05.075  3956  4005 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:06:05.076  3956  4005 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:06:05.076  3956  4005 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:06:05.080  3956  4005 I System.out: Running OutgoingSocketThread
,09-09 13:06:05.084  3956  4428 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-09 13:06:05.084  3956  4428 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:06:08.093  3956  4429 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-09 13:06:08.094  3956  4429 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:06:08.094  3956  4428 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 13:06:08.094  3956  4429 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:06:08.094  3956  4428 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:06:08.095  3956  4428 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:06:08.095  3956  4429 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:06:08.097  3956  4429 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:06:08.097  3956  4428 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:06:08.102  3956  4431 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 469, name: IncomingSocketThread/Sender)
,09-09 13:06:08.105  3956  4432 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 470, name: OutgoingSocketThread/Sender)
,09-09 13:06:08.106  3956  4428 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:06:08.109  3956  4433 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 471, name: IncomingSocketThread/Receiver)
,09-09 13:06:08.112  3956  4433 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 471, thread name: IncomingSocketThread/Receiver)
,09-09 13:06:08.112  3956  4433 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:06:08.112  3956  4434 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 472, name: OutgoingSocketThread/Receiver)
,09-09 13:06:08.112  3956  4433 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 471, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:06:08.114  3956  4434 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 472, thread name: OutgoingSocketThread/Receiver)
09-09 13:06:08.115  3956  4434 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:06:08.115  3956  4434 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 472, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:06:11.096  3956  4005 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 481)
,09-09 13:06:11.098  3956  4005 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 13:06:11.098  3956  4005 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 482)
,09-09 13:06:11.104  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:06:11.104  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3a3273 added. We now have 3 listener(s)
,09-09 13:06:11.106  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:06:11.106  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:06:11.106  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:06:11.107  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:06:11.107  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@818b530 added. We now have 4 listener(s)
,09-09 13:06:11.107  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:06:11.107  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:06:11.118  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:06:11.129  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:06:11.129  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:06:11.129  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:06:11.129  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:06:11.129  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:06:11.129  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:06:11.129  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:06:11.129  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:06:11.136  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:06:11.136  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:06:11.138  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:06:11.139  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:06:11.139  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:06:11.139  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:06:11.139  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:11.140  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:06:11.140  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:06:11.140  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3a3273 removed from the list
09-09 13:06:11.140  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:11.141  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@818b530 removed from the list
,09-09 13:06:11.143  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:06:11.143  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:06:11.144  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:11.145  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:06:11.145  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:11.159  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:06:11.159  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:06:11.160  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:06:11.160  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:11.160  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@818b530 not in the list
09-09 13:06:11.161  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:11.162  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:11.165  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:06:11.165  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:06:11.165  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:11.166  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@818b530 not in the list
09-09 13:06:11.166  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:06:11.166  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:06:11.166  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:11.167  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3a3273 not in the list
,09-09 13:06:11.169  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:06:11.169  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5d472e added. We now have 3 listener(s)
,09-09 13:06:11.175  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:06:11.175  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:06:11.176  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:06:11.176  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:06:11.176  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfb82cf added. We now have 4 listener(s)
09-09 13:06:11.177  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:06:11.178  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:06:11.182  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:06:11.190  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:06:11.190  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:06:11.190  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:06:11.190  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:06:11.190  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:06:11.190  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:06:11.190  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:06:11.190  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:06:11.194  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:06:11.194  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:06:11.195  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:06:11.196  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:06:11.196  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:06:11.196  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:06:11.197  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:06:11.197  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:06:11.201  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:06:11.206  3956  4005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 13:06:11.206  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:06:11.217  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:06:11.219  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:06:11.219  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:06:11.229  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-09 13:06:11.229  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 13:06:11.230  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:06:11.232  3956  4005 D BluetoothAdapter: STATE_ON
,09-09 13:06:11.239  4339  4375 D BtGatt.GattService: registerClient() - UUID=fba95e0e-c3ae-4593-abc8-5446acb28b01
,09-09 13:06:11.242  4339  4355 D BtGatt.GattService: onClientRegistered() - UUID=fba95e0e-c3ae-4593-abc8-5446acb28b01, clientIf=5
,09-09 13:06:11.244  3956  4020 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 13:06:11.247  4339  4349 D BtGatt.GattService: start scan with filters
,09-09 13:06:11.257  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 13:06:11.258  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:06:11.258  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 13:06:11.258  4339  4358 D BtGatt.ScanManager: handling starting scan
09-09 13:06:11.258  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 13:06:11.263  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:06:11.263  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:06:11.263  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 13:06:11.264  4339  4358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5841a92
09-09 13:06:11.264  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:06:11.269  3956  4005 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 13:06:11.270  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:06:11.270  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:06:11.270  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:11.270  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:06:11.270  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:06:11.270  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:06:11.270  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:06:11.270  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:06:11.271  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:06:11.271  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 13:06:11.273  3956  4005 D BluetoothAdapter: STATE_ON
,09-09 13:06:11.275  4339  4378 D BtGatt.GattService: stopScan() - queue size =1
,09-09 13:06:11.278  4339  4375 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:06:11.279  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:06:11.279  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 13:06:11.279  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 13:06:11.280  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 13:06:11.280  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 13:06:11.280  4339  4355 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 13:06:11.280  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:11.282  4339  4358 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 13:06:11.282  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:06:11.283  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:06:11.285  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:06:11.286  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:06:11.287  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:06:11.290  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:06:11.290  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:06:11.290  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:06:11.300  4339  4355 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 13:06:11.300  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:11.302  4339  4358 D BtGatt.ScanManager: Starting BLE batch scan
09-09 13:06:11.302  4339  4358 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 13:06:11.334  4339  4355 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 13:06:11.335  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:06:11.352  4339  4355 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 13:06:11.352  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:06:11.382  4339  4355 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 13:06:11.383  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:11.384  4339  4358 D BtGatt.ScanManager: stopping BLe Batch
,09-09 13:06:11.407  4339  4355 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 13:06:11.407  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:11.408  4339  4358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:06:11.430  4339  4355 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 13:06:11.430  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:06:11.791  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:06:11.792  3956  3956 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:06:11.792  3956  3956 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:06:14.291  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:06:14.292  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:06:14.292  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:06:14.293  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:06:14.293  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:06:14.294  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:06:14.294  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:06:14.295  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5d472e removed from the list
09-09 13:06:14.295  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:14.295  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfb82cf removed from the list
09-09 13:06:14.295  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:06:14.296  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:14.297  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:14.298  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:06:14.302  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:06:14.303  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:06:14.303  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:06:14.304  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfb82cf not in the list
09-09 13:06:14.304  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:14.305  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:06:14.309  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:06:14.309  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 13:06:14.309  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:14.309  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfb82cf not in the list
09-09 13:06:14.309  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:06:14.310  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:14.310  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:14.310  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5d472e not in the list
09-09 13:06:14.311  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:06:14.311  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@891fa48 added. We now have 3 listener(s)
,09-09 13:06:14.313  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:06:14.313  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:06:14.313  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:06:14.313  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:06:14.313  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c19b0e1 added. We now have 4 listener(s)
09-09 13:06:14.314  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:06:14.314  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:06:14.317  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:06:14.322  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:06:14.322  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:06:14.322  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:06:14.322  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:06:14.322  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:06:14.322  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:06:14.322  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:06:14.322  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:06:14.325  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:06:14.325  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:06:14.326  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:06:14.328  3956  4005 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-09 13:06:14.328  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:06:14.329  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:06:14.331  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:06:14.331  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:06:14.331  3956  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:06:14.331  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:06:14.333  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:06:14.334  3956  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:06:14.334  3956  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:06:14.334  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:06:14.334  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:06:14.335  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-09 13:06:14.335  3956  3956 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:06:14.335  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:06:14.335  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:06:14.338  3956  4435 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:06:14.342  3956  4435 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:06:14.343  3956  4005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 13:06:14.343  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:06:14.353  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:06:14.354  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:06:14.354  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:06:14.358  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:06:14.359  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:06:14.359  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-09 13:06:14.360  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:06:14.360  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:06:14.361  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:06:14.362  3956  4005 D BluetoothAdapter: STATE_ON
,09-09 13:06:14.367  4339  4350 D BtGatt.GattService: registerClient() - UUID=8b255fb5-fc48-4b28-ba52-8d3de87dbc7c
,09-09 13:06:14.368  4339  4355 D BtGatt.GattService: onClientRegistered() - UUID=8b255fb5-fc48-4b28-ba52-8d3de87dbc7c, clientIf=5
,09-09 13:06:14.369  3956  4020 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:06:14.374  4339  4357 D BtGatt.AdvertiseManager: message : 0
,09-09 13:06:14.378  4339  4357 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:06:14.403  4339  4355 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:06:14.421  4339  4355 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:06:14.423  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:06:14.424  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:06:14.427  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:06:14.430  3956  3956 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:06:14.431  3956  3956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:06:14.431  3956  3956 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:06:14.431  3956  3956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:06:14.432  3956  3956 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:06:14.432  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:06:14.436  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:06:14.442  3956  3956 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:06:14.442  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:06:14.944  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:06:14.944  3956  3956 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:06:14.945  3956  3956 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:06:17.437  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:06:17.437  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-09 13:06:17.438  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:06:17.438  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:06:17.438  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:06:17.439  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:06:17.439  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:06:17.440  3956  4435 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:06:17.440  3956  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:06:17.440  3956  4435 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:06:17.440  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:06:17.440  3956  4435 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:06:17.440  3956  3956 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:06:17.441  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:06:17.441  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:06:17.441  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:06:17.442  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:06:17.444  3956  4005 D BluetoothAdapter: STATE_ON
09-09 13:06:17.445  3956  4005 D BluetoothLeScanner: could not find callback wrapper
09-09 13:06:17.445  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:06:17.445  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:06:17.448  4339  4357 D BtGatt.AdvertiseManager: message : 1
09-09 13:06:17.449  4339  4357 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:06:17.459  4339  4355 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:06:17.459  4339  4355 D BtGatt.GattService: Client app is not null!
,09-09 13:06:17.461  4339  4378 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:06:17.462  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:06:17.462  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:06:17.462  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:06:17.463  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:06:17.463  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:06:17.465  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:06:17.465  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:06:17.465  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:06:17.466  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:06:17.468  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:06:17.468  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:17.469  3956  3956 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:06:17.469  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:06:17.469  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:06:17.469  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:06:17.469  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:06:17.469  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@891fa48 removed from the list
09-09 13:06:17.470  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:17.469  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-09 13:06:17.470  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c19b0e1 removed from the list
09-09 13:06:17.470  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:06:17.470  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:17.471  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:17.471  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:06:17.474  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:06:17.474  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:06:17.474  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:17.475  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c19b0e1 not in the list
,09-09 13:06:17.475  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:17.475  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:06:17.478  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:06:17.479  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 13:06:17.479  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:17.479  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c19b0e1 not in the list
09-09 13:06:17.479  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:06:17.479  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:17.480  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-09 13:06:17.480  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@891fa48 not in the list
,09-09 13:06:17.481  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:06:17.482  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a0492 added. We now have 3 listener(s)
,09-09 13:06:17.489  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:06:17.489  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:06:17.489  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:06:17.490  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:06:17.490  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6949e63 added. We now have 4 listener(s)
09-09 13:06:17.490  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:06:17.491  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:06:17.498  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:06:17.507  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:06:17.507  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:06:17.507  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:06:17.507  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:06:17.507  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:06:17.507  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:06:17.507  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:06:17.507  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:06:17.511  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:06:17.511  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:06:17.512  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:06:17.512  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 13:06:17.512  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:06:17.512  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:06:17.513  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:06:17.516  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:06:17.519  3956  4005 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:06:17.519  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:06:17.521  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:06:17.526  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:06:17.528  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:06:17.528  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:06:17.534  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 13:06:17.534  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 13:06:17.535  3956  4005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:06:17.536  3956  4005 D BluetoothAdapter: STATE_ON
,09-09 13:06:17.540  4339  4378 D BtGatt.GattService: registerClient() - UUID=01c98541-b6e9-435d-afb8-049a0d8bd991
,09-09 13:06:17.541  4339  4355 D BtGatt.GattService: onClientRegistered() - UUID=01c98541-b6e9-435d-afb8-049a0d8bd991, clientIf=5
,09-09 13:06:17.542  3956  3967 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 13:06:17.542  4339  4375 D BtGatt.GattService: start scan with filters
,09-09 13:06:17.549  4339  4358 D BtGatt.ScanManager: handling starting scan
,09-09 13:06:17.549  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 13:06:17.549  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:06:17.550  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 13:06:17.550  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 13:06:17.556  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:06:17.557  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:06:17.558  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:06:17.563  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:06:17.567  4339  4355 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 13:06:17.567  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:17.568  4339  4358 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 13:06:17.583  4339  4355 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 13:06:17.583  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:17.584  4339  4358 D BtGatt.ScanManager: Starting BLE batch scan
09-09 13:06:17.584  4339  4358 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 13:06:17.616  4339  4355 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 13:06:17.616  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:06:17.635  4339  4355 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 13:06:17.635  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:06:17.970  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:06:18.059  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 13:06:18.059  3956  3956 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:06:18.059  3956  3956 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:06:19.139  4339  4339 D BtGatt.ScanManager: awakened up at time 231127
,09-09 13:06:19.142  4339  4358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:06:19.192  4339  4355 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-09 13:06:19.192  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:19.193  4339  4355 D BtGatt.GattService: current time is 231181736410
09-09 13:06:19.194  4339  4355 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -94, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 13:06:19.196  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 13:06:19.197  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 13:06:19.197  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 13:06:19.197  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 13:06:19.198  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:06:19.198  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 13:06:19.816   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231803, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:06:20.580  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:06:20.581  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:06:20.581  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:06:20.582  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:06:20.582  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:06:20.583  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:06:20.583  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:06:20.583  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:06:20.583  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:06:20.584  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:06:20.584  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 13:06:20.587  3956  4005 D BluetoothAdapter: STATE_ON
09-09 13:06:20.588  4339  4350 D BtGatt.GattService: stopScan() - queue size =1
09-09 13:06:20.591  4339  4416 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:06:20.593  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:06:20.593  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 13:06:20.593  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 13:06:20.594  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 13:06:20.594  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 13:06:20.601  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:06:20.602  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:06:20.602  3956  4005 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:06:20.601  4339  4339 D BtGatt.ScanManager: awakened up at time 232589
09-09 13:06:20.602  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:06:20.604  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:06:20.607  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:06:20.607  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:06:20.607  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:20.607  3956  3956 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:06:20.607  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:06:20.608  3956  3956 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:06:20.608  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-09 13:06:20.608  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a0492 removed from the list
09-09 13:06:20.608  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:20.609  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6949e63 removed from the list,
09-09 13:06:20.609  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:06:20.609  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:20.610  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:06:20.611  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:20.611  4339  4355 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 13:06:20.611  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:20.612  4339  4358 D BtGatt.ScanManager: stopping BLe Batch
,09-09 13:06:20.613  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:06:20.613  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:06:20.614  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:20.614  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6949e63 not in the list,
09-09 13:06:20.614  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:20.614  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:06:20.617  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:06:20.617  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 13:06:20.617  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:20.617  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6949e63 not in the list
09-09 13:06:20.617  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:06:20.617  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:20.617  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:20.617  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a0492 not in the list
,09-09 13:06:20.618  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:06:20.619  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e32c8c added. We now have 3 listener(s)
09-09 13:06:20.621  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:06:20.621  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:06:20.621  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:06:20.621  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:06:20.621  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94cfd5 added. We now have 4 listener(s)
09-09 13:06:20.622  3956  4005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:06:20.622  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:06:20.627  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:06:20.629  4339  4355 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 13:06:20.629  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:20.629  4339  4358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:06:20.637  3956  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:06:20.637  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:06:20.637  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:06:20.637  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:06:20.637  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:06:20.637  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:06:20.637  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:06:20.637  3956  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:06:20.641  3956  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:06:20.642  3956  4005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:06:20.644  3956  4005 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:06:20.644  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:06:20.644  3956  4005 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:06:20.644  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:06:20.644  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:20.644  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:06:20.644  3956  4005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:06:20.644  3956  4005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e32c8c removed from the list
09-09 13:06:20.645  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:20.645  3956  4005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94cfd5 removed from the list
,09-09 13:06:20.645  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:06:20.650  4339  4355 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
09-09 13:06:20.650  4339  4355 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:06:20.650  3956  3956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:06:20.650  3956  4005 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:06:20.651  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:20.651  4339  4355 D BtGatt.GattService: current time is 232639874693
09-09 13:06:20.651  4339  4355 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -88, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 13:06:20.652  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:20.652  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 13:06:20.652  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:06:20.652  4339  4355 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 13:06:20.654  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:06:20.654  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:06:20.654  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:06:20.655  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94cfd5 not in the list
09-09 13:06:20.655  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:20.655  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:06:20.657  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:06:20.657  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:06:20.657  3956  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:06:20.658  3956  4005 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94cfd5 not in the list
,09-09 13:06:20.658  3956  4005 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:06:20.658  3956  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:06:20.658  3956  4005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:06:20.658  3956  4005 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e32c8c not in the list
,09-09 13:06:20.660  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-09 13:06:20.661  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:06:20.661  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:06:20.661  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:06:20.661  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:06:20.662  3956  4005 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:06:21.109  3956  3956 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:06:22.681  3956  4437 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 491, name: My test thread name)
,09-09 13:06:24.679  3956  4005 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 491
,09-09 13:06:24.679  3956  4005 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 491, name: My test thread name)
,09-09 13:06:24.686  3956  4438 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 492, name: My test thread name)
,09-09 13:06:24.687  3956  4438 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 492, thread name: My test thread name)
09-09 13:06:24.687  3956  4438 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 492, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 13:06:24.691  3956  4005 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:06:24.700  3956  4439 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 496, name: My test thread name)
,09-09 13:06:24.700  3956  4439 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 496, thread name: My test thread name): Test exception.
09-09 13:06:24.701  3956  4439 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 496, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:06:24.708  3956  4005 I jxcore-log: Total number of executed tests:  82
09-09 13:06:24.708  3956  4005 I jxcore-log: 
,09-09 13:06:24.709  3956  4005 I jxcore-log: Number of passed tests:  82
09-09 13:06:24.709  3956  4005 I jxcore-log: 
09-09 13:06:24.710  3956  4005 I jxcore-log: Number of failed tests:  0
09-09 13:06:24.710  3956  4005 I jxcore-log: 
,09-09 13:06:24.711  3956  4005 I jxcore-log: Number of ignored tests:  0
09-09 13:06:24.711  3956  4005 I jxcore-log: 
09-09 13:06:24.711  3956  4005 I jxcore-log: Total duration:  101459
09-09 13:06:24.711  3956  4005 I jxcore-log: 
,09-09 13:06:24.721  3956  4005 I jxcore-log: Unit Test app is loaded
09-09 13:06:24.721  3956  4005 I jxcore-log: 
,09-09 13:06:24.730  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.730  3956  4005 I jxcore-log: 
,09-09 13:06:24.736  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.736  3956  4005 I jxcore-log: 
,09-09 13:06:24.737  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.737  3956  4005 I jxcore-log: 
,09-09 13:06:24.739  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.739  3956  4005 I jxcore-log: 
09-09 13:06:24.740  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 13:06:24.740  3956  4005 I jxcore-log: 
,09-09 13:06:24.742  3956  3956 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 13:06:24.742  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:06:24.742  3956  4005 I jxcore-log: 
,09-09 13:06:24.745  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.745  3956  4005 I jxcore-log: 
,09-09 13:06:24.747  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.747  3956  4005 I jxcore-log: 
,09-09 13:06:24.748  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 13:06:24.748  3956  4005 I jxcore-log: 
09-09 13:06:24.749  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:06:24.749  3956  4005 I jxcore-log: 
,09-09 13:06:24.750  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:06:24.750  3956  4005 I jxcore-log: 
09-09 13:06:24.751  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.751  3956  4005 I jxcore-log: 
,09-09 13:06:24.752  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.752  3956  4005 I jxcore-log: 
09-09 13:06:24.753  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.753  3956  4005 I jxcore-log: 
,09-09 13:06:24.753  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.753  3956  4005 I jxcore-log: 
09-09 13:06:24.755  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.755  3956  4005 I jxcore-log: 
,09-09 13:06:24.756  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.756  3956  4005 I jxcore-log: 
09-09 13:06:24.756  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.756  3956  4005 I jxcore-log: 
,09-09 13:06:24.757  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.757  3956  4005 I jxcore-log: 
09-09 13:06:24.758  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.758  3956  4005 I jxcore-log: 
,09-09 13:06:24.759  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.759  3956  4005 I jxcore-log: 
09-09 13:06:24.760  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.760  3956  4005 I jxcore-log: 
,09-09 13:06:24.760  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.760  3956  4005 I jxcore-log: 
,09-09 13:06:24.762  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.762  3956  4005 I jxcore-log: 
,09-09 13:06:24.763  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.763  3956  4005 I jxcore-log: 
,09-09 13:06:24.763  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.763  3956  4005 I jxcore-log: 
09-09 13:06:24.764  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.764  3956  4005 I jxcore-log: 
09-09 13:06:24.764  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.764  3956  4005 I jxcore-log: 
09-09 13:06:24.765  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.765  3956  4005 I jxcore-log: 
09-09 13:06:24.765  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.765  3956  4005 I jxcore-log: 
,09-09 13:06:24.766  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.766  3956  4005 I jxcore-log: 
09-09 13:06:24.766  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.766  3956  4005 I jxcore-log: 
09-09 13:06:24.767  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.767  3956  4005 I jxcore-log: 
,09-09 13:06:24.767  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.767  3956  4005 I jxcore-log: 
09-09 13:06:24.768  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.768  3956  4005 I jxcore-log: 
09-09 13:06:24.768  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.768  3956  4005 I jxcore-log: 
,09-09 13:06:24.769  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.769  3956  4005 I jxcore-log: 
09-09 13:06:24.769  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.769  3956  4005 I jxcore-log: 
09-09 13:06:24.770  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.770  3956  4005 I jxcore-log: 
09-09 13:06:24.770  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.770  3956  4005 I jxcore-log: 
,09-09 13:06:24.771  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:06:24.771  3956  4005 I jxcore-log: 
09-09 13:06:24.771  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.771  3956  4005 I jxcore-log: 
09-09 13:06:24.772  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:06:24.772  3956  4005 I jxcore-log: 
,09-09 13:06:24.772  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.772  3956  4005 I jxcore-log: 
09-09 13:06:24.773  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.773  3956  4005 I jxcore-log: 
09-09 13:06:24.773  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.773  3956  4005 I jxcore-log: 
09-09 13:06:24.774  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.774  3956  4005 I jxcore-log: 
,09-09 13:06:24.774  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.774  3956  4005 I jxcore-log: 
09-09 13:06:24.775  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:06:24.775  3956  4005 I jxcore-log: 
09-09 13:06:24.775  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.775  3956  4005 I jxcore-log: 
,09-09 13:06:24.776  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:06:24.776  3956  4005 I jxcore-log: 
09-09 13:06:24.776  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.776  3956  4005 I jxcore-log: 
09-09 13:06:24.777  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:06:24.777  3956  4005 I jxcore-log: 
09-09 13:06:24.777  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 13:06:24.777  3956  4005 I jxcore-log: 
,09-09 13:06:24.778  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:06:24.778  3956  4005 I jxcore-log: 
09-09 13:06:24.778  3956  4005 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:06:24.778  3956  4005 I jxcore-log: 
,09-09 13:06:24.783  3956  4005 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-09 13:06:24.783  3956  4005 I jxcore-log:   bluetooth: 'on',
09-09 13:06:24.783  3956  4005 I jxcore-log:   wifi: 'on',
09-09 13:06:24.783  3956  4005 I jxcore-log:   cellular: 'doNotCare',
09-09 13:06:24.783  3956  4005 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 13:06:24.783  3956  4005 I jxcore-log: 
,09-09 13:06:24.787  3956  4005 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-09 13:06:24.787  3956  4005 I jxcore-log:   bluetooth: 'on',
09-09 13:06:24.787  3956  4005 I jxcore-log:   wifi: 'on',
09-09 13:06:24.787  3956  4005 I jxcore-log:   cellular: 'doNotCare',
09-09 13:06:24.787  3956  4005 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 13:06:24.787  3956  4005 I jxcore-log: 
,09-09 13:06:24.788  3956  4005 I jxcore-log: My device name is: motorola-Nexus 6
09-09 13:06:24.788  3956  4005 I jxcore-log: 
09-09 13:06:24.789  3956  4005 I jxcore-log: Running for WIFI network type
09-09 13:06:24.789  3956  4005 I jxcore-log: 
,09-09 13:06:24.846  3956  4437 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 491, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-09 13:06:27.291  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-09 13:06:27.291  3956  4005 I jxcore-log: 
,09-09 13:06:27.753  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-09 13:06:27.753  3956  4005 I jxcore-log: 
,09-09 13:06:27.786  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-09 13:06:27.786  3956  4005 I jxcore-log: 
,09-09 13:06:29.183  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-09 13:06:29.183  3956  4005 I jxcore-log: 
,09-09 13:06:29.424  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-09 13:06:29.424  3956  4005 I jxcore-log: 
,09-09 13:06:29.429  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-09 13:06:29.429  3956  4005 I jxcore-log: 
,09-09 13:06:29.436  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-09 13:06:29.436  3956  4005 I jxcore-log: 
,09-09 13:06:29.515  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-09 13:06:29.515  3956  4005 I jxcore-log: 
,09-09 13:06:29.534  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-09 13:06:29.534  3956  4005 I jxcore-log: 
,09-09 13:06:29.539  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-09 13:06:29.539  3956  4005 I jxcore-log: 
,09-09 13:06:30.490  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-09 13:06:30.490  3956  4005 I jxcore-log: 
,09-09 13:06:30.662  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-09 13:06:30.662  3956  4005 I jxcore-log: 
,09-09 13:06:31.003  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-09 13:06:31.003  3956  4005 I jxcore-log: 
,09-09 13:06:31.013  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-09 13:06:31.013  3956  4005 I jxcore-log: 
,09-09 13:06:31.021  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-09 13:06:31.021  3956  4005 I jxcore-log: 
,09-09 13:06:31.028  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-09 13:06:31.028  3956  4005 I jxcore-log: 
,09-09 13:06:31.069  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-09 13:06:31.069  3956  4005 I jxcore-log: 
,09-09 13:06:31.119  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-09 13:06:31.119  3956  4005 I jxcore-log: 
,09-09 13:06:31.126  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-09 13:06:31.126  3956  4005 I jxcore-log: 
,09-09 13:06:31.134  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-09 13:06:31.134  3956  4005 I jxcore-log: 
,09-09 13:06:31.155  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-09 13:06:31.155  3956  4005 I jxcore-log: 
,09-09 13:06:31.160  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-09 13:06:31.160  3956  4005 I jxcore-log: 
,09-09 13:06:31.166  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-09 13:06:31.166  3956  4005 I jxcore-log: 
,09-09 13:06:31.183  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-09 13:06:31.183  3956  4005 I jxcore-log: 
,09-09 13:06:31.210  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-09 13:06:31.210  3956  4005 I jxcore-log: 
,09-09 13:06:31.222  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-09 13:06:31.222  3956  4005 I jxcore-log: 
,09-09 13:06:31.235  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-09 13:06:31.235  3956  4005 I jxcore-log: 
,09-09 13:06:31.247  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-09 13:06:31.247  3956  4005 I jxcore-log: 
,09-09 13:06:31.264  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-09 13:06:31.264  3956  4005 I jxcore-log: 
,09-09 13:06:31.275  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-09 13:06:31.275  3956  4005 I jxcore-log: 
,09-09 13:06:31.281  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-09 13:06:31.281  3956  4005 I jxcore-log: 
,09-09 13:06:31.312  3956  4005 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-09 13:06:31.312  3956  4005 I jxcore-log: 
,09-09 13:06:31.323  3956  4005 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-09 13:06:31.324  3956  4005 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-09 13:06:31.324  3956  4005 I jxcore-log: 
,09-09 13:06:31.327  3956  4005 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-09 13:06:31.327  3956  4005 I jxcore-log: 
,09-09 13:06:31.327  3956  4005 I jxcore-log: ThaliTape :: Started ThaliTape
09-09 13:06:31.327  3956  4005 I jxcore-log: 
,09-09 13:06:31.333  3956  4005 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-09 13:06:31.333  3956  4005 I jxcore-log: 
,09-09 13:06:31.404  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:06:31.404  3956  4005 I jxcore-log: 
,09-09 13:06:31.404  3956  4005 I jxcore-log: websocket error
09-09 13:06:31.404  3956  4005 I jxcore-log: 
,09-09 13:06:31.404  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:06:31.404  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:06:31.404  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:06:31.404  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:31.404  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:06:31.404  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:31.404  3956  4005 I jxcore-log: 
,09-09 13:06:32.785  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:06:32.785  3956  4005 I jxcore-log: 
,09-09 13:06:32.788  3956  4005 I jxcore-log: websocket error
09-09 13:06:32.788  3956  4005 I jxcore-log: 
,09-09 13:06:32.790  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:06:32.790  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:06:32.790  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:06:32.790  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:32.790  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:06:32.790  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:32.790  3956  4005 I jxcore-log: 
,09-09 13:06:35.855  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:06:35.855  3956  4005 I jxcore-log: 
,09-09 13:06:35.857  3956  4005 I jxcore-log: websocket error
09-09 13:06:35.857  3956  4005 I jxcore-log: 
09-09 13:06:35.857  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:06:35.857  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:06:35.857  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:06:35.857  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:35.857  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:06:35.857  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:35.857  3956  4005 I jxcore-log: 
,09-09 13:06:36.382   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=248370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 13:06:40.466  3348  4441 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:06:40.519  3348  4442 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:06:40.551  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:06:40.554  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:06:40.614  1514  3150 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:06:40.614  1514  3150 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:06:40.614  1514  3150 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:06:40.614  1514  3150 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:06:40.652  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:06:40.659  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:06:40.698  1514  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:06:40.699  1514  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:06:40.699  1514  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:06:40.699  1514  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:06:40.728  3348  4442 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:06:40.730  3348  4441 E BooksSync: Soft error
09-09 13:06:40.730  3348  4441 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:06:40.730  3348  4441 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:06:40.730  3348  4441 E BooksSync: Sync error
09-09 13:06:40.730  3348  4441 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:06:40.730  3348  4441 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:06:40.732  3348  4441 I BooksSync: Finished books sync
,09-09 13:06:40.744   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 252307, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:06:40.923  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:06:40.923  3956  4005 I jxcore-log: 
09-09 13:06:40.924  3956  4005 I jxcore-log: websocket error
09-09 13:06:40.924  3956  4005 I jxcore-log: 
09-09 13:06:40.924  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:06:40.924  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:06:40.924  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:06:40.924  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:40.924  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:06:40.924  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:40.924  3956  4005 I jxcore-log: 
,09-09 13:06:45.989  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:06:45.989  3956  4005 I jxcore-log: 
,09-09 13:06:45.990  3956  4005 I jxcore-log: websocket error
09-09 13:06:45.990  3956  4005 I jxcore-log: 
09-09 13:06:45.990  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:06:45.990  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:06:45.990  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:06:45.990  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:45.990  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:06:45.990  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:45.990  3956  4005 I jxcore-log: 
,09-09 13:06:51.059  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:06:51.059  3956  4005 I jxcore-log: 
,09-09 13:06:51.060  3956  4005 I jxcore-log: websocket error
09-09 13:06:51.060  3956  4005 I jxcore-log: 
09-09 13:06:51.060  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:06:51.060  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:06:51.060  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:06:51.060  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:51.060  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:06:51.060  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:51.060  3956  4005 I jxcore-log: 
,09-09 13:06:56.118  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:06:56.118  3956  4005 I jxcore-log: 
09-09 13:06:56.119  3956  4005 I jxcore-log: websocket error
09-09 13:06:56.119  3956  4005 I jxcore-log: 
,09-09 13:06:56.119  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:06:56.119  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:06:56.119  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:06:56.119  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:56.119  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:06:56.119  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:06:56.119  3956  4005 I jxcore-log: 
,09-09 13:06:59.102   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:07:01.177  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:07:01.177  3956  4005 I jxcore-log: 
09-09 13:07:01.177  3956  4005 I jxcore-log: websocket error
09-09 13:07:01.177  3956  4005 I jxcore-log: 
,09-09 13:07:01.178  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:07:01.178  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:07:01.178  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:07:01.178  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:01.178  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:07:01.178  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:01.178  3956  4005 I jxcore-log: 
,09-09 13:07:06.156   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=278144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 13:07:06.236  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:07:06.236  3956  4005 I jxcore-log: 
09-09 13:07:06.236  3956  4005 I jxcore-log: websocket error
09-09 13:07:06.236  3956  4005 I jxcore-log: 
,09-09 13:07:06.237  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:07:06.237  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:07:06.237  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:07:06.237  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:06.237  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:07:06.237  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:06.237  3956  4005 I jxcore-log: 
,09-09 13:07:10.957  3348  4444 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:07:10.989  3348  4445 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:07:11.004  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:07:11.007  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:07:11.044  1514  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:07:11.044  1514  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:07:11.044  1514  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:07:11.044  1514  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:07:11.088  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:07:11.092  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:07:11.136  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 13:07:11.136  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 13:07:11.136  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:07:11.136  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:07:11.165  3348  4445 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:07:11.166  3348  4444 E BooksSync: Soft error
09-09 13:07:11.166  3348  4444 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:07:11.166  3348  4444 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:07:11.166  3348  4444 E BooksSync: Sync error
09-09 13:07:11.166  3348  4444 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:07:11.166  3348  4444 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:07:11.167  3348  4444 I BooksSync: Finished books sync
,09-09 13:07:11.183   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 282830, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:07:11.302  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:07:11.302  3956  4005 I jxcore-log: 
,09-09 13:07:11.302  3956  4005 I jxcore-log: websocket error,
09-09 13:07:11.302  3956  4005 I jxcore-log: 
09-09 13:07:11.303  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:07:11.303  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:07:11.303  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:07:11.303  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:11.303  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:07:11.303  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:11.303  3956  4005 I jxcore-log: 
,09-09 13:07:16.418  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:07:16.418  3956  4005 I jxcore-log: 
,09-09 13:07:16.418  3956  4005 I jxcore-log: websocket error
09-09 13:07:16.418  3956  4005 I jxcore-log: 
,09-09 13:07:16.418  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:07:16.418  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:07:16.418  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:07:16.418  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:16.418  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:07:16.418  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:16.418  3956  4005 I jxcore-log: 
,09-09 13:07:21.478  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:07:21.478  3956  4005 I jxcore-log: 
,09-09 13:07:21.478  3956  4005 I jxcore-log: websocket error
09-09 13:07:21.478  3956  4005 I jxcore-log: 
,09-09 13:07:21.478  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:07:21.478  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:07:21.478  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:07:21.478  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:21.478  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:07:21.478  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:21.478  3956  4005 I jxcore-log: 
,09-09 13:07:26.549  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:07:26.549  3956  4005 I jxcore-log: 
,09-09 13:07:26.550  3956  4005 I jxcore-log: websocket error
09-09 13:07:26.550  3956  4005 I jxcore-log: 
,09-09 13:07:26.550  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:07:26.550  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:07:26.550  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:07:26.550  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:26.550  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:07:26.550  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:26.550  3956  4005 I jxcore-log: 
,09-09 13:07:28.862   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=300850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:07:31.621  3956  4005 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:07:31.621  3956  4005 I jxcore-log: 
,09-09 13:07:31.622  3956  4005 I jxcore-log: websocket error
09-09 13:07:31.622  3956  4005 I jxcore-log: 
,09-09 13:07:31.622  3956  4005 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:07:31.622  3956  4005 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:07:31.622  3956  4005 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:07:31.622  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:31.622  3956  4005 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:07:31.622  3956  4005 I jxcore-log: emit@events.js:82:1
09-09 13:07:31.622  3956  4005 I jxcore-log: 
,09-09 13:07:36.596   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 13:07:36.945  3956  4005 I jxcore-log: ThaliTape :: Reconnected to the test server
09-09 13:07:36.945  3956  4005 I jxcore-log: 
,09-09 13:07:36.960  3956  4005 I jxcore-log: ThaliTape :: Connected to the test server
09-09 13:07:36.960  3956  4005 I jxcore-log: 
,09-09 13:07:41.611  3765  4459 V KeepSync: Connecting to GoogleApiClient
,09-09 13:07:41.612   872  1404 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:07:41.640  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:07:41.643  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:07:41.664  1514  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:07:41.665  1514  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 13:07:41.665  1514  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:07:41.665  1514  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:07:41.685  3181  4461 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:07:41.685  3181  4461 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:07:41.685  3181  4461 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	... 12 more
09-09 13:07:41.685  3181  4461 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at fal.a(PG:38)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:07:41.685  3181  4461 E HttpOperation: 	... 14 more
,09-09 13:07:41.768  1514  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 13:07:41.769  1514  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 13:07:41.769  1514  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:07:41.769  1514  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:07:41.778  1514  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 13:07:41.778  1514  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 13:07:41.778  1514  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:07:41.778  1514  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:07:41.790  3181  4461 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:07:41.790  3181  4461 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at hec.a(PG:42)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at hee.a(PG:102)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at czr.a(PG:65)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at kka.a(PG:108)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:07:41.790  3181  4461 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	... 15 more
09-09 13:07:41.790  3181  4461 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at fal.a(PG:38)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:07:41.790  3181  4461 E HttpOperation: 	... 17 more
,09-09 13:07:41.791  3181  4461 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:07:41.791  3181  4461 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	... 15 more
09-09 13:07:41.791  3181  4461 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:07:41.791  3181  4461 E ExperimentLoader: 	... 17 more
,09-09 13:07:41.798  1743  4462 V BaseAuthAsyncOperation: access token request failed
,09-09 13:07:41.800  3765  4459 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:07:41.881  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 13:07:41.881  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 13:07:41.881  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:07:41.881  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:07:41.912   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 284944, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:07:41.918  3765  4459 E KeepSync: IOException
09-09 13:07:41.918  3765  4459 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:07:41.918  3765  4459 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:07:41.918  3765  4459 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:07:41.918  3765  4459 E KeepSync: 	... 10 more
09-09 13:07:41.918  3765  4459 W KeepSync: Sync result 2
,09-09 13:07:41.949   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 284453, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:08:00.726   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=332714, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:08:06.969   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=338957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:08:12.087  3348  4466 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:08:12.171  3348  4469 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:08:12.187  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:08:12.188  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:08:12.222  1514  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 13:08:12.222  1514  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:08:12.223  1514  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:08:12.223  1514  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:08:12.252  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:08:12.255  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:08:12.288  1514  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 13:08:12.288  1514  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 13:08:12.288  1514  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:08:12.288  1514  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:08:12.314  3348  4469 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:08:12.315  3348  4466 E BooksSync: Soft error
09-09 13:08:12.315  3348  4466 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:08:12.315  3348  4466 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:08:12.315  3348  4466 E BooksSync: Sync error
09-09 13:08:12.315  3348  4466 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:08:12.315  3348  4466 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:08:12.315  3348  4466 I BooksSync: Finished books sync
,09-09 13:08:12.325  1514  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:08:12.325  1514  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 13:08:12.325  1514  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:08:12.325  1514  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:08:12.334   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 343366, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:08:12.353  3181  4468 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:08:12.353  3181  4468 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:08:12.353  3181  4468 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	... 12 more
09-09 13:08:12.353  3181  4468 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at fal.a(PG:38)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:08:12.353  3181  4468 E HttpOperation: 	... 14 more
,09-09 13:08:12.390  1514  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:08:12.390  1514  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 13:08:12.390  1514  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:08:12.390  1514  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-09 13:08:12.406  3181  4468 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:08:12.406  3181  4468 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at hec.a(PG:42)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at hee.a(PG:102)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at czr.a(PG:65)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at kka.a(PG:108)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:08:12.406  3181  4468 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	... 15 more
09-09 13:08:12.406  3181  4468 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at fal.a(PG:38)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:08:12.406  3181  4468 E HttpOperation: 	... 17 more
,09-09 13:08:12.406  3181  4468 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:08:12.406  3181  4468 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	... 15 more
09-09 13:08:12.406  3181  4468 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:08:12.406  3181  4468 E ExperimentLoader: 	... 17 more
,09-09 13:08:12.558   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 343907, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:08:13.523  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:08:13.571  1514  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 13:08:13.571  1514  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 13:08:13.571  1514  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:08:13.571  1514  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:08:13.611  1514  2017 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 13:08:13.611  1514  2017 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 13:08:13.611  1514  2017 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 13:08:13.611  1514  2017 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-09 13:08:13.611  1514  2017 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-09 13:08:13.611  1514  2017 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-09 13:08:13.611  1514  2017 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 13:08:13.621  3705  3736 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 13:08:13.621  3705  3736 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-09 13:08:13.621  3705  3736 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-09 13:08:13.621  3705  3736 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-09 13:08:13.621  3705  3736 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-09 13:08:13.621  3705  3736 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-09 13:08:13.621  3705  3736 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 13:08:42.718  3765  4476 V KeepSync: Connecting to GoogleApiClient
,09-09 13:08:42.718   872  2016 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:08:42.761  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:08:42.763  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:08:42.787  1514  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 13:08:42.787  1514  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 13:08:42.787  1514  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:08:42.788  1514  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:08:42.802  1743  4477 V BaseAuthAsyncOperation: access token request failed
,09-09 13:08:42.803  3765  4476 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:08:42.843  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 13:08:42.843  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 13:08:42.843  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:08:42.844  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:08:42.863  3765  4476 E KeepSync: IOException
09-09 13:08:42.863  3765  4476 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:08:42.863  3765  4476 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:08:42.863  3765  4476 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:08:42.863  3765  4476 E KeepSync: 	... 10 more
09-09 13:08:42.864  3765  4476 W KeepSync: Sync result 2
,09-09 13:08:42.877   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 346569, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:08:49.769   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:08:57.142   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=389130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:09:13.317  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:09:13.318  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:09:13.371  1514  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 13:09:13.372  1514  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:09:13.372  1514  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:09:13.372  1514  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:09:13.400  3181  4480 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:09:13.400  3181  4480 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:09:13.400  3181  4480 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	... 12 more
09-09 13:09:13.400  3181  4480 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at fal.a(PG:38)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:09:13.400  3181  4480 E HttpOperation: 	... 14 more
,09-09 13:09:13.479  1514  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 13:09:13.479  1514  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 13:09:13.479  1514  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:09:13.479  1514  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:09:13.505  3181  4480 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:09:13.505  3181  4480 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at hec.a(PG:42)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at hee.a(PG:102)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at czr.a(PG:65)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at kka.a(PG:108)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:09:13.505  3181  4480 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	... 15 more
09-09 13:09:13.505  3181  4480 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at fal.a(PG:38)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:09:13.505  3181  4480 E HttpOperation: 	... 17 more
,09-09 13:09:13.505  3181  4480 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:09:13.505  3181  4480 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	... 15 more
09-09 13:09:13.505  3181  4480 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:09:13.505  3181  4480 E ExperimentLoader: 	... 17 more
,09-09 13:09:13.626   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 404559, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:09:14.836   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=406824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:09:22.222   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=414210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:09:39.956   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=431944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:09:47.289   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=439277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:09:48.250  3765  4483 V KeepSync: Connecting to GoogleApiClient
,09-09 13:09:48.251   872  1980 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:09:48.315  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:09:48.317  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:09:48.367  1514  3150 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 13:09:48.367  1514  3150 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 13:09:48.367  1514  3150 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:09:48.367  1514  3150 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:09:48.397  1743  4484 V BaseAuthAsyncOperation: access token request failed
,09-09 13:09:48.399  3765  4483 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:09:48.467  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 13:09:48.467  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 13:09:48.467  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:09:48.467  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:09:48.485  3765  4483 E KeepSync: IOException
09-09 13:09:48.485  3765  4483 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:09:48.485  3765  4483 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:09:48.485  3765  4483 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:09:48.485  3765  4483 E KeepSync: 	... 10 more
,09-09 13:09:48.485  3765  4483 W KeepSync: Sync result 2
,09-09 13:09:48.498   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 440127, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:10:05.022   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=457010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:10:12.369   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=464357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:10:18.690  3348  4487 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:10:18.732  3348  4488 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:10:18.762  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:10:18.765  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:10:18.804  1514  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:10:18.804  1514  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:10:18.804  1514  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:10:18.804  1514  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:10:18.851  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:10:18.853  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:10:18.890  1514  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 13:10:18.891  1514  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 13:10:18.891  1514  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:10:18.891  1514  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:10:18.927  3348  4488 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:10:18.929  3348  4487 E BooksSync: Soft error
09-09 13:10:18.929  3348  4487 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:10:18.929  3348  4487 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:10:18.929  3348  4487 E BooksSync: Sync error
09-09 13:10:18.929  3348  4487 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:10:18.929  3348  4487 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:10:18.929  3348  4487 I BooksSync: Finished books sync
,09-09 13:10:18.940   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 464710, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:10:30.089   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=482077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:10:37.422   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=489410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:10:55.156   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=507144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:11:01.835   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=513823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:11:13.916  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:11:13.917  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:11:13.949  1514  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:11:13.949  1514  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:11:13.949  1514  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:11:13.949  1514  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:11:13.971  3181  4493 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:11:13.971  3181  4493 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:11:13.971  3181  4493 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	... 12 more
09-09 13:11:13.971  3181  4493 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at fal.a(PG:38)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:11:13.971  3181  4493 E HttpOperation: 	... 14 more
,09-09 13:11:14.040  1514  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:11:14.040  1514  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:11:14.040  1514  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:11:14.040  1514  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:11:14.060  3181  4493 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:11:14.060  3181  4493 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at hec.a(PG:42)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at hee.a(PG:102)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at czr.a(PG:65)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at kka.a(PG:108)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:11:14.060  3181  4493 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	... 15 more
09-09 13:11:14.060  3181  4493 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at fal.a(PG:38)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:11:14.060  3181  4493 E HttpOperation: 	... 17 more
,09-09 13:11:14.061  3181  4493 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:11:14.061  3181  4493 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: ,	at jdm.a(PG:77)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	... 15 more
09-09 13:11:14.061  3181  4493 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:11:14.061  3181  4493 E ExperimentLoader: 	... 17 more
,09-09 13:11:14.200   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 525639, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:11:20.222   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=532210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:11:27.569   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=539557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:11:45.289   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=557277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:11:52.676   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=564664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:11:59.129  3765  4497 V KeepSync: Connecting to GoogleApiClient
,09-09 13:11:59.129   872   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:11:59.203  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:11:59.209  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:11:59.260  1514  2017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 13:11:59.261  1514  2017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 13:11:59.261  1514  2017 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:11:59.261  1514  2017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:11:59.298  1743  4498 V BaseAuthAsyncOperation: access token request failed
,09-09 13:11:59.300  3765  4497 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:11:59.364  1514  3150 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 13:11:59.365  1514  3150 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 13:11:59.365  1514  3150 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:11:59.365  1514  3150 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:11:59.387  3765  4497 E KeepSync: IOException
09-09 13:11:59.387  3765  4497 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:11:59.387  3765  4497 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:11:59.387  3765  4497 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:11:59.387  3765  4497 E KeepSync: 	... 10 more
,09-09 13:11:59.387  3765  4497 W KeepSync: Sync result 2
,09-09 13:11:59.402   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 571011, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:12:10.409   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=582397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:12:17.756   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=589744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:12:35.476   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=607464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:12:42.822   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=614810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:13:00.595   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=632583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:13:07.955   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=639943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:13:25.663   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=657650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:13:33.009   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=664997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:13:50.729   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=682717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:13:58.076   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=690063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:14:15.796   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=707784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:14:23.129   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=715117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:14:40.862   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=732850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:14:48.196   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=740184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:15:06.569   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=758557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:15:13.902   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=765890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:15:31.636   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=783624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:15:38.969   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=790957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:15:56.703   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=808691, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:16:04.036   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=816024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:16:21.769   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=833757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:16:29.089   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=841077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:16:46.782   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=858770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:16:54.142   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=866130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:17:11.849   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=883837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:17:19.209   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=891197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:17:28.889   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=900877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:17:44.956   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=916944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:17:53.955   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=925943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:18:10.022   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=942010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:18:18.996   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=950984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:18:35.076   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=967064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:18:44.062   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=976050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:19:00.142   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=992130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:19:09.129   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1001117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:19:25.196   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1017184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:19:34.196   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1026184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:19:50.262   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1042250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:19:59.262   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1051250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:20:15.343   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1067331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:20:24.382   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1076370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:20:40.449   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1092437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:20:45.654   872  3305 I ActivityManager: Start proc 4527:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-09 13:20:45.730  4527  4527 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-09 13:20:45.760  4527  4527 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-09 13:20:45.760  4527  4527 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:20:45.760  4527  4527 I GAv4    :   adb logcat -s GAv4
,09-09 13:20:45.777  4527  4527 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:20:45.784  4527  4527 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:20:45.796  4527  4542 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:20:45.897   872  2015 I ActivityManager: Killing 3877:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 13:20:49.449   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1101437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:20:57.220  1743  4545 I EventLogService: Opted in for usage reporting
,09-09 13:20:57.220  1743  4545 I EventLogService: Aggregate from 1473417786208 (log), 1473417786047 (data)
,09-09 13:20:57.284  1743  4545 W EventLogAggregator: Unknown tag: snet_gcore
,09-09 13:20:57.285  1743  4545 W EventLogAggregator: Unknown tag: snet_launch_service
,09-09 13:20:57.351  1743  4545 I ServiceDumpSys: dumping service [account]
,09-09 13:21:02.196   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1114184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:21:14.516   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1126504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:21:30.569   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1142557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:21:39.582   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1151570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:21:55.635   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1167623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:22:04.622   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1176610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:22:20.702   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1192690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:22:36.862   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1208850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:22:45.769   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1217757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:22:46.657   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,09-09 13:23:01.929   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1233917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:23:10.835   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1242823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:23:26.996   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1258984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:23:35.903   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1267891, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:23:52.062   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1284050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:24:00.996   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1292984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:24:17.129   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1309117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:24:26.062   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1318050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:24:42.196   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1334184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:24:51.116   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1343104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:25:07.262   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1359250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:25:16.182   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1368170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:25:32.329   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1384317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:25:41.235   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1393223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:25:57.396   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1409384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:26:06.303   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1418291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:26:22.462   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1434450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:26:31.369   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1443357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:26:47.529   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1459517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:26:56.422   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1468410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:27:12.596   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1484584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:27:21.502   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1493490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:27:37.769   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1509757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:27:46.569   872  4395 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1518557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms),09-09 13:27:56.980  4566  4566 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 13:27:56.985  4566  4566 D AndroidRuntime: CheckJNI is OFF
09-09 13:27:57.023  4566  4566 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 13:27:57.064  4566  4566 I Radio-JNI: register_android_hardware_Radio DONE
09-09 13:27:57.086  4566  4566 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 13:27:57.097   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 13:27:57.098   872   885 I ActivityManager: Killing 3956:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-09 13:27:57.208   872   895 W PackageSettings: Skipping PackageSetting{fe50857 com.example.hello/10273} due to missing metadata
09-09 13:27:57.233   872   883 D GraphicsStats: Buffer count: 2
09-09 13:27:57.233   872  1391 I WindowState: WIN DEATH: Window{50bed06 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 13:27:57.234   872  1315 D WifiService: Client connection lost with reason: 4
09-09 13:27:57.239   872   895 I art     : Starting a blocking GC Explicit
09-09 13:27:57.301   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-09 13:27:57.301   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-09 13:27:57.302   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-09 13:27:57.302   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 13:27:57.302   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.302   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.302   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:27:57.302   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 13:27:57.302   872   885 I ActivityManager:   Force finishing activity ActivityRecord{4d6f3ef u0 com.test.thalitest/.MainActivity t4}
09-09 13:27:57.321   872   895 I art     : Explicit concurrent mark sweep GC freed 54443(4MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 1.037ms total 77.335ms
09-09 13:27:57.324   872  1679 W ActivityManager: Spurious death for ProcessRecord{108d995 0:com.test.thalitest/u0a0}, curProc for 3956: null
09-09 13:27:57.349   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-09 13:27:57.352  4566  4566 I art     : System.exit called, status: 0
09-09 13:27:57.352  4566  4566 I AndroidRuntime: VM exiting with result code 0.
09-09 13:27:57.354   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-09 13:27:57.362   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-09 13:27:57.368   872  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 13:27:57.369  4339  4339 D BluetoothMapAppObserver: onReceive
09-09 13:27:57.369  4339  4339 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 13:27:57.376  1903  2278 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 13:27:57.376  1887  1887 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 13:27:57.377  3825  3825 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 13:27:57.385  1887  4578 I Keyboard.Facilitator.DecoderInitializer: run()
09-09 13:27:57.398  1887  4578 I Decoder : createOrResetDecoder
09-09 13:27:57.409  1956  1956 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-09 13:27:57.429   872  2013 I ActivityManager: Start proc 4581:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-09 13:27:57.433  1514  1514 I ConfigService: onCreate
09-09 13:27:57.460  4581  4581 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-09 13:27:57.474  1887  4578 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-09 13:27:57.482   872  1678 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3956 uid 10000
09-09 13:27:57.484  1887  1887 I Keyboard.Facilitator: onFinishInput()
09-09 13:27:57.485   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 13:27:57.496  1970  2064 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 13:27:57.496   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-09 13:27:57.497   872   884 E PackageManager: Failed to write settings, restoring backup
09-09 13:27:57.497   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 13:27:57.497   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 13:27:57.497   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 13:27:57.497   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 13:27:57.497   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 13:27:57.497   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.497   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.497   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:27:57.505   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-09 13:27:57.505   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 13:27:57.505   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:27:57.505   872   885 E DropBoxManagerService: 	... 13 more
09-09 13:27:57.508   872   882 I ActivityManager: Start proc 4595:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-09 13:27:57.509  1970  2064 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 13:27:57.509  1970  2064 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1970
09-09 13:27:57.509  1970  2064 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.509  1970  2064 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:27:57.511   872  1980 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 13:27:57.512   872  4604 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:27:57.512   872  4604 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:27:57.512   872  4604 E DropBoxManagerService: 	... 5 more
09-09 13:27:57.514  1970  2064 I Process : Sending signal. PID: 1970 SIG: 9
09-09 13:27:57.527  1887  4578 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-09 13:27:57.529  1887  4578 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 13:27:57.529  1887  4578 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-09 13:27:57.531  1887  4578 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 13:27:57.531  1887  4578 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 13:27:57.532  1887  4578 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 13:27:57.532  1887  4578 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-09 13:27:57.535  1887  4578 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-09 13:27:57.535  1887  4578 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 13:27:57.535  1887  4578 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 13:27:57.536  1887  4578 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 13:27:57.537  1887  4578 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 13:27:57.537  1887  4578 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-09 13:27:57.553  4581  4581 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-09 13:27:57.561  4581  4612 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 13:27:57.569   872   883 I ActivityManager: Start proc 4613:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-09 13:27:57.592   872  3305 D GraphicsStats: Buffer count: 1
09-09 13:27:57.592   872  1980 I WindowState: WIN DEATH: Window{fb1cf8f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-09 13:27:57.609   872  2019 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1970) has died
09-09 13:27:57.609   872  2019 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 13:27:57.611   872  2019 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 13:27:57.623  4613  4613 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-09 13:27:57.629   872   885 I ActivityManager: Start proc 4626:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 13:27:57.657  1514  1514 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 13:27:57.659  1514  1514 D AndroidRuntime: Shutting down VM
09-09 13:27:57.659  1514  1514 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:27:57.659  1514  1514 E AndroidRuntime: Process: com.google.process.gapps, PID: 1514
09-09 13:27:57.659  1514  1514 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 13:27:57.659  1514  1514 E AndroidRuntime: 	... 8 more
09-09 13:27:57.662   872  4641 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:27:57.662   872  4641 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:27:57.662   872  4641 E DropBoxManagerService: 	... 5 more
09-09 13:27:57.663  1514  1514 I Process : Sending signal. PID: 1514 SIG: 9
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.674  4581  4603 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.674  4581  4603 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:27:57.680  4626  4626 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:27:57.681  4626  4626 D AndroidRuntime: Shutting down VM
09-09 13:27:57.685  4626  4626 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:27:57.685  4626  4626 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4626
09-09 13:27:57.685  4626  4626 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:27:57.685  4626  4626 E AndroidRuntime: 	... 10 more
09-09 13:27:57.687   872  1404 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 13:27:57.687  4626  4626 I Process : Sending signal. PID: 4626 SIG: 9
09-09 13:27:57.688   872  4643 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:27:57.688   872  4643 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:27:57.688   872  4643 E DropBoxManagerService: 	... 5 more
09-09 13:27:57.708   872  1315 D WifiService: Client connection lost with reason: 4
09-09 13:27:57.725   872  1921 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4626) has died
09-09 13:27:57.727   872  1921 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 13:27:57.736  1743  1743 W RocketImpressions: ClearcutLogger connection suspended: 1
09-09 13:27:57.742  4581  4603 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-09 13:27:57.742   872   885 I ActivityManager: Start proc 4645:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 13:27:57.742   872  2013 I ActivityManager: Process com.google.process.gapps (pid 1514) has died
09-09 13:27:57.743   872  2013 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-09 13:27:57.743   872  2013 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-09 13:27:57.743   872  2013 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-09 13:27:57.757   872  3305 I ActivityManager: Start proc 4657:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
09-09 13:27:57.769   872  1980 I ActivityManager: Killing 2034:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.789  4581  4612 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 13:27:57.789  4581  4612 E AndroidRuntime: Process: android.process.acore, PID: 4581
09-09 13:27:57.789  4581  4612 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.789  4581  4612 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:27:57.791  4581  4603 I Process : Sending signal. PID: 4581 SIG: 9
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:27:57.797  4645  4645 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:27:57.797  4645  4645 D AndroidRuntime: Shutting down VM
09-09 13:27:57.811   872  1315 D WifiService: Client connection lost with reason: 4
09-09 13:27:57.825  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-09 13:27:57.825  1743  1743 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-09 13:27:57.829   872  1679 I ActivityManager: Process android.process.acore (pid 4581) has died
09-09 13:27:57.829   872  1679 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-09 13:27:57.831   872  4671 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:27:57.831   872  4671 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:27:57.831   872  4671 E DropBoxManagerService: 	... 5 more
09-09 13:27:57.834  4657  4657 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-09 13:27:57.833  4645  4645 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:27:57.833  4645  4645 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4645
09-09 13:27:57.833  4645  4645 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:27:57.833  4645  4645 E AndroidRuntime: 	... 10 more
09-09 13:27:57.838   872  2019 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 13:27:57.839  4645  4645 I Process : Sending signal. PID: 4645 SIG: 9
09-09 13:27:57.840   872  4672 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:27:57.840   872  4672 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:27:57.840   872  4672 E DropBoxManagerService: 	... 5 more
09-09 13:27:57.849  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-09 13:27:57.849  1743  1743 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-09 13:27:57.850   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
