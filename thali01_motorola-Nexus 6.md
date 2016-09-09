#### Test 83627337ab51778_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 13:35:29.804  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:35:29.814  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 13:35:29.818  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 13:35:29.868  1511  2441 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 13:35:29.869  1511  2441 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 13:35:29.869  1511  2441 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:35:29.870  1511  2441 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 13:35:29.913  3514  3514 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 13:35:29.915  3514  3514 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 13:35:29.916  3514  3514 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-09 13:35:30.440  3817  3817 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 13:35:30.445  3817  3817 D AndroidRuntime: CheckJNI is OFF
09-09 13:35:30.488  3817  3817 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 13:35:30.539  3817  3817 I Radio-JNI: register_android_hardware_Radio DONE
09-09 13:35:30.561  3817  3817 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 13:35:30.566   870  2292 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 13:35:30.600  2046  2059 W SearchService: Abort, client detached.
09-09 13:35:30.614  2046  2358 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7a17953
09-09 13:35:30.614  2046  2367 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 13:35:30.614  2046  2046 I HotwordDetector: Closing mic
09-09 13:35:30.632  3817  3817 D AndroidRuntime: Shutting down VM
09-09 13:35:30.663   870  2237 I ActivityManager: Start proc 3827:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 13:35:30.684   374  2369 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 13:35:30.686   374  2369 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 13:35:30.691   374  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 13:35:30.693  2046  2366 I MicroRecognitionRnrImpl: Detection finished
09-09 13:35:30.694  2046  2362 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 13:35:30.752  3827  3827 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 13:35:30.786  3827  3827 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 13:35:30.795  3827  3827 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8861-8864)
09-09 13:35:30.795  3827  3827 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:35:30.815  3827  3827 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d7c3e43}
09-09 13:35:30.816  3827  3827 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:35:30.816  3827  3827 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:35:30.822  3827  3827 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 13:35:30.828  3827  3827 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:35:30.848  3827  3827 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 13:35:30.860  3827  3827 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:35:30.860  3827  3827 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:35:30.860  3827  3827 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:35:30.860  3827  3827 I Adreno  : Build Date                       : 10/20/15
09-09 13:35:30.860  3827  3827 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:35:30.860  3827  3827 I Adreno  : Local Branch                     : M14
09-09 13:35:30.860  3827  3827 I Adreno  : Remote Branch                    : 
09-09 13:35:30.860  3827  3827 I Adreno  : Remote Branch                    : 
09-09 13:35:30.860  3827  3827 I Adreno  : Reconstruct Branch               : 
,09-09 13:35:30.932   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c3370ea:true
,09-09 13:35:30.967  3827  3827 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 13:35:30.978  3827  3827 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 13:35:31.043  3827  3866 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 13:35:31.053  3827  3853 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 13:35:31.080  3827  3866 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 13:35:31.154   870   888 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +518ms
,09-09 13:35:31.162  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-09 13:35:31.261  3827  3827 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3827
,09-09 13:35:31.461   870  1400 I ActivityManager: Killing 3573:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-09 13:35:31.511  3827  3827 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:35:31.520   870  1400 I ActivityManager: Killing 3238:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,09-09 13:35:31.616  3827  3868 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1698498256
,09-09 13:35:31.621  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:35:31.621  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:35:31.621  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:35:31.621  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:35:31.621  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 13:35:31.621  3827  3868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4db57 added. We now have 1 listener(s)
,09-09 13:35:31.625  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 13:35:31.627  3827  3868 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:35:31.628  3827  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:31.628  3827  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 13:35:31.632  3827  3868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc22062 added. We now have 1 listener(s)
09-09 13:35:31.632  3827  3868 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:31.635   870  1313 D WifiService: New client listening to asynchronous messages
,09-09 13:35:31.636  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:31.636  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413,
09-09 13:35:31.636  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 13:35:31.636  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
09-09 13:35:31.636  3827  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 13:35:31.639  3827  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:31.640  3827  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 13:35:31.645  3827  3868 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 13:35:31.646  3827  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:31.646  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:31.646  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:31.646  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:31.646  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:31.646  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:31.646  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:31.646  3827  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:31.646  3827  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-09 13:35:31.646  3827  3868 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:31.647  3827  3868 I io.jxcore.node.LifeCycleMonitor: start: OK,
,09-09 13:35:31.703  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:31.705  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:31.707  3827  3827 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:35:32.456  3827  3875 W jxcore-log: Initializing JXcore engine
,09-09 13:35:32.456  3827  3875 W jxcore-log: JXcore engine is ready
,09-09 13:35:32.493  3875  3875 W Thread-336: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 13:35:32.496  3875  3875 W Thread-336: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12957]" dev="sockfs" ino=12957 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 13:35:32.496  3875  3875 W Thread-336: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 13:35:32.496  3875  3875 W Thread-336: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25910]" dev="sockfs" ino=25910 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 13:35:32.511  3827  3875 W jxcore-log: Starting JXcore engine
,09-09 13:35:32.590  3827  3875 W jxcore-log: Platform android
09-09 13:35:32.590  3827  3875 W jxcore-log: 
,09-09 13:35:32.590  3827  3875 W jxcore-log: Process ARCH arm
09-09 13:35:32.590  3827  3875 W jxcore-log: 
,09-09 13:35:32.837  3827  3875 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:35:32.837  3827  3875 I jxcore-log: 
,09-09 13:35:32.837  3827  3875 W jxcore-log: JXcore engine is started
,09-09 13:35:32.847  3827  3868 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 13:35:32.851  3827  3827 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:35:34.161   870  1312 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 13:35:39.624  3603  3883 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:35:39.660  3603  3884 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:35:39.673  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:35:39.675  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:35:39.703  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:35:39.703  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:35:39.703  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:35:39.703  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:35:39.734  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:35:39.737  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:35:39.768  1511  2997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:35:39.769  1511  2997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 13:35:39.769  1511  2997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:35:39.769  1511  2997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-09 13:35:39.793  3603  3884 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:35:39.796  3603  3883 E BooksSync: Soft error
09-09 13:35:39.796  3603  3883 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:35:39.796  3603  3883 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:35:39.796  3603  3883 E BooksSync: Sync error
09-09 13:35:39.796  3603  3883 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:35:39.796  3603  3883 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:35:39.796  3603  3883 I BooksSync: Finished books sync
,09-09 13:35:39.805   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127567, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:35:42.353  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:35:42.353  3827  3875 I jxcore-log: 
,09-09 13:35:42.356  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:35:42.356  3827  3875 I jxcore-log: 
,09-09 13:35:42.368  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:42.368  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:42.368  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:42.368  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:42.368  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:42.368  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:42.368  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:42.368  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:42.371  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:42.373  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:35:42.373  3827  3875 I jxcore-log: 
,09-09 13:35:42.375  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:35:42.375  3827  3875 I jxcore-log: 
,09-09 13:35:42.862  3827  3875 I jxcore-log: Unit Test app is loaded
09-09 13:35:42.862  3827  3875 I jxcore-log: 
,09-09 13:35:42.867  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:35:42.867  3827  3875 I jxcore-log: 
,09-09 13:35:42.873  3827  3875 D executeNativeTests: Running unit tests
,09-09 13:35:42.874  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:35:42.874  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e37977 added. We now have 2 listener(s)
,09-09 13:35:42.875  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:35:42.875  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:42.875  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:42.875  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:42.875  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe729e4 added. We now have 2 listener(s)
,09-09 13:35:42.875  3827  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:42.876  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:42.878  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:42.887  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:42.887  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:42.887  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:42.887  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:42.887  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:42.887  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:42.887  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:42.887  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:42.889  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:42.889  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:42.892  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:42.895  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:42.895  3827  3827 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 13:35:42.936   870  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 13:35:45.974   870  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 13:35:50.255  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:35:50.271  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:35:50.276  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:35:50.342  1511  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 13:35:50.343  1511  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 13:35:50.343  1511  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:35:50.343  1511  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:35:50.388  3514  3514 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 13:35:50.388  3514  3514 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 13:35:50.389  3514  3514 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 13:35:52.983  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:52.983  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 added. We now have 3 listener(s)
,09-09 13:35:52.984  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:35:52.985  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:52.985  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:52.985  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:52.985  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 added. We now have 3 listener(s)
09-09 13:35:52.985  3827  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:52.986  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:52.993  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:53.006  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:53.006  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:53.006  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:53.006  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:53.006  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:53.006  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:53.006  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:53.006  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:53.011  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:53.012  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:53.021  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:53.029  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:53.031  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:35:53.031  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:35:53.031  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:35:53.032  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:53.033  3827  3875 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 13:35:53.033  3827  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 13:35:53.033  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:53.034  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:35:53.034  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:53.034  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:53.034  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:53.035  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:53.035  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:53.035  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:53.035  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 removed from the list
,09-09 13:35:53.035  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:53.035  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 removed from the list
09-09 13:35:53.035  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:53.035  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:53.037  3827  3875 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 13:35:53.038  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:53.038  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:53.038  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:53.038  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:53.038  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:53.038  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:53.039  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:53.039  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:53.039  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:35:53.044  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:35:53.045  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:35:53.046  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
09-09 13:35:53.046  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:35:53.046  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:35:53.046  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:35:53.046  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:53.046  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:53.046  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:53.046  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:53.046  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:53.046  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:53.046  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:53.046  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:53.046  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:53.047  3827  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true,
09-09 13:35:53.049  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:53.052  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 13:35:53.052  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:53.052  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:53.052  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:53.052  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-09 13:35:53.052  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:53.052  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:53.052  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:53.054  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:53.054  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:53.055  3827  3875 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:35:53.055  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:35:53.055  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:53.055  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-09 13:35:53.055  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:53.056  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:53.056  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:53.057  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:35:53.059  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:53.059  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:53.059  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:35:53.059  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:53.059  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:53.059  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:53.059  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:53.059  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:53.063  3827  3889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:53.063  3827  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:35:53.063  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:35:53.064  3827  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:35:53.068  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:35:53.069  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:35:53.070  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:53.072  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:35:53.072  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:35:53.073  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61,
09-09 13:35:53.074  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:53.074  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:53.074  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:35:53.075  3827  3875 D BluetoothAdapter: STATE_ON
,09-09 13:35:53.081  2695  2707 D BtGatt.GattService: registerClient() - UUID=67e8c64b-6d99-44fd-bf0a-ddff758deb58
,09-09 13:35:53.082  2695  2719 D BtGatt.GattService: onClientRegistered() - UUID=67e8c64b-6d99-44fd-bf0a-ddff758deb58, clientIf=5
09-09 13:35:53.083  3827  3839 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:35:53.085  2695  2722 D BtGatt.AdvertiseManager: message : 0
,09-09 13:35:53.087  2695  2722 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:53.102  2695  2719 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:35:53.108  2695  2719 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:35:53.110  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:35:53.111  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:53.115  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:53.117  3827  3875 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:53.117  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:53.117  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:35:53.117  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:35:53.117  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:35:53.118  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:35:53.118  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:53.120  3827  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:53.121  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:53.622  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:35:53.622  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:35:53.623  3827  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:35:53.624  3827  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:35:53.625  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:35:53.625  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:35:53.625  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:35:53.626  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:35:53.626  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:53.628  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:35:53.628  3827  3889 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:53.628  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:53.628  3827  3889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:53.629  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:35:53.629  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:53.629  3827  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:35:53.629  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:35:53.629  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:53.629  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:53.631  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:35:53.634  3827  3875 D BluetoothAdapter: STATE_ON
09-09 13:35:53.636  3827  3875 D BluetoothLeScanner: could not find callback wrapper
09-09 13:35:53.636  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:35:53.636  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:35:53.639  2695  2722 D BtGatt.AdvertiseManager: message : 1
09-09 13:35:53.641  2695  2722 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:35:53.665  2695  2719 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-09 13:35:53.666  2695  2719 D BtGatt.GattService: Client app is not null!
,09-09 13:35:53.669  2695  2706 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:35:53.671  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:35:53.671  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:35:53.672  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:35:53.672  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:35:53.672  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:53.675  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:53.676  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:35:53.676  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:35:53.680  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:53.684  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:35:53.685  3827  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:35:53.685  3827  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:35:53.685  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:53.686  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:53.686  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:53.688  3827  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:35:53.688  3827  3875 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-09 13:35:53.688  3827  3875 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-09 13:35:53.689  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-09 13:35:53.689  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:53.689  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:35:53.690  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:53.690  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:53.691  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:35:53.691  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:35:53.691  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:53.692  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:53.692  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-09 13:35:53.692  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:53.692  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:53.692  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:35:53.696  3827  3892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:53.697  3827  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:35:53.697  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:35:53.698  3827  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:35:53.702  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:35:53.703  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:35:53.703  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:53.705  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:35:53.705  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:35:53.705  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
09-09 13:35:53.705  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:53.706  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:35:53.706  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:35:53.706  3827  3875 D BluetoothAdapter: STATE_ON
,09-09 13:35:53.709  2695  2849 D BtGatt.GattService: registerClient() - UUID=9603de9e-8f1f-4e58-8585-c26d9177bb5a
,09-09 13:35:53.709  2695  2719 D BtGatt.GattService: onClientRegistered() - UUID=9603de9e-8f1f-4e58-8585-c26d9177bb5a, clientIf=5
09-09 13:35:53.710  3827  3838 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:35:53.710  2695  2722 D BtGatt.AdvertiseManager: message : 0
09-09 13:35:53.713  2695  2722 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:53.725  2695  2719 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:35:53.732  2695  2719 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:35:53.732  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:35:53.732  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:53.734  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:53.736  3827  3875 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:53.736  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:53.736  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:35:53.736  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:35:53.736  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:35:53.736  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:35:53.737  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:53.741  3827  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:53.742  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:54.239  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:54.239  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:54.240  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:35:54.240  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:54.242  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:35:54.242  3827  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:54.242  3827  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:54.242  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:54.243  3827  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:35:54.243  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:35:54.243  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:54.243  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.244  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:54.244  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:54.244  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:54.244  3827  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:54.244  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:54.245  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:35:54.248  3827  3875 D BluetoothAdapter: STATE_ON
,09-09 13:35:54.248  3827  3875 D BluetoothLeScanner: could not find callback wrapper
09-09 13:35:54.248  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:35:54.248  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:35:54.255  2695  2722 D BtGatt.AdvertiseManager: message : 1
,09-09 13:35:54.257  2695  2722 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:35:54.278  2695  2719 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:35:54.278  2695  2719 D BtGatt.GattService: Client app is not null!
09-09 13:35:54.281  2695  2818 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:35:54.282  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:35:54.283  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:35:54.283  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:35:54.283  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:35:54.284  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:54.287  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:54.287  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:35:54.288  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:35:54.289  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:54.292  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
,09-09 13:35:54.293  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:54.293  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.293  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:54.293  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.294  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:54.296  3827  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:35:54.301  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:54.314  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:54.314  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:54.314  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:54.314  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:54.314  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:54.314  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.314  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:54.314  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:54.319  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:54.320  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:54.321  3827  3875 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-09 13:35:54.321  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-09 13:35:54.322  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:54.322  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:35:54.322  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:54.322  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:54.324  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:35:54.325  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:54.326  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.326  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:54.326  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:54.328  3827  3894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:35:54.329  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:54.330  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.330  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:54.333  3827  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:35:54.333  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.334  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:35:54.342  3827  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:35:54.342  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:35:54.346  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:35:54.347  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:35:54.348  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:54.350  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:35:54.350  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:35:54.350  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
,09-09 13:35:54.351  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:35:54.354  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:54.354  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:35:54.356  3827  3875 D BluetoothAdapter: STATE_ON
,09-09 13:35:54.359  2695  2706 D BtGatt.GattService: registerClient() - UUID=2db1ced5-a3e0-4e17-a19a-b0190eedbefa
,09-09 13:35:54.360  2695  2719 D BtGatt.GattService: onClientRegistered() - UUID=2db1ced5-a3e0-4e17-a19a-b0190eedbefa, clientIf=5
09-09 13:35:54.360  3827  3839 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:35:54.361  2695  2722 D BtGatt.AdvertiseManager: message : 0
,09-09 13:35:54.365  2695  2722 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:54.389  2695  2719 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:35:54.406  2695  2719 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:35:54.407  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:35:54.408  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:54.413  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:54.416  3827  3875 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:35:54.416  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:35:54.416  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:35:54.416  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:35:54.417  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:35:54.417  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:35:54.417  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:54.425  3827  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:54.425  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:54.920  3827  3875 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:35:54.921  3827  3875 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:35:54.921  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-09 13:35:54.923  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:35:54.925  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:35:54.925  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:35:54.926  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:35:54.926  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:35:54.931  3827  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-09 13:35:54.932  3827  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:35:54.931  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:35:54.932  3827  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:35:54.933  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 13:35:54.933  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:35:54.933  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:54.934  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:54.935  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:54.935  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:35:54.938  3827  3875 D BluetoothAdapter: STATE_ON
09-09 13:35:54.938  3827  3875 D BluetoothLeScanner: could not find callback wrapper
09-09 13:35:54.938  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:35:54.938  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:35:54.939  2695  2722 D BtGatt.AdvertiseManager: message : 1
09-09 13:35:54.941  2695  2722 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:35:54.957  2695  2719 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:35:54.957  2695  2719 D BtGatt.GattService: Client app is not null!
,09-09 13:35:54.959  2695  2847 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:35:54.959  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:35:54.959  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:35:54.960  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:35:54.960  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:35:54.960  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:54.962  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:54.962  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:35:54.962  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:54.963  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:54.964  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:35:54.964  3827  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 13:35:54.965  3827  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:35:54.965  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:54.965  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:54.965  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:54.965  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:54.968  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:54.968  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.968  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:54.968  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:54.969  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:54.969  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:54.969  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:54.969  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:54.971  3827  3875 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 13:35:54.973  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.973  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.973  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.974  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:54.974  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.974  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:54.974  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:54.974  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.974  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.978  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 13:35:54.978  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.978  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.979  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:54.979  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:54.979  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.979  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
,09-09 13:35:54.979  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.980  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.980  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:54.982  3827  3875 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:35:54.983  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:54.983  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:54.983  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.983  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:54.984  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.984  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
,09-09 13:35:54.984  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.984  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.984  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.986  3827  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-09 13:35:54.986  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.986  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.986  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.986  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:54.987  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:54.987  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:54.987  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:54.987  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:54.987  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.989  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:35:54.990  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.990  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.990  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 13:35:54.990  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:54.991  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:35:54.991  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:35:54.991  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.991  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.991  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:54.992  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.992  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.992  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
,09-09 13:35:54.992  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.992  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
,09-09 13:35:54.993  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.993  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:54.993  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.995  3827  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:54.995  3827  3875 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:35:54.995  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 13:35:55.001  3827  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 13:35:55.002  3827  3875 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-09 13:35:55.002  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:35:55.002  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:35:55.002  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:35:55.002  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:35:55.003  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:35:55.004  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:35:55.005  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:35:55.005  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:35:55.005  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:35:55.006  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:35:55.006  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:35:55.006  3827  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:35:55.006  3827  3875 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:55.006  3827  3875 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:35:55.007  3827  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:55.007  3827  3875 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:55.007  3827  3875 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:35:55.007  3827  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:55.007  3827  3875 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:55.008  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:35:55.017  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:35:55.017  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:35:55.018  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:35:55.018  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:35:55.019  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:35:55.019  3827  3875 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:35:55.019  3827  3875 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:55.019  3827  3875 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:35:55.020  3827  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 436)
09-09 13:35:55.020  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.020  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.020  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.021  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:35:55.021  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:55.022  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.022  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:55.022  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.022  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.022  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.022  3827  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:55.023  3827  3875 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:35:55.023  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.024  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.023  3827  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 436
09-09 13:35:55.024  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.024  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:55.024  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.024  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:55.024  3827  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 436)
09-09 13:35:55.025  3827  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 436)
09-09 13:35:55.024  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.025  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.026  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.026  3827  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 436)
09-09 13:35:55.028  3827  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:35:55.029  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.029  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.029  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.029  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:55.030  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.030  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:55.030  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.030  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.031  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.032  3827  3875 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:35:55.033  3827  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:35:55.033  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:55.036  3827  3875 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:35:55.036  3827  3875 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:35:55.037  3827  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:35:55.037  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:55.037  3827  3875 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:35:55.038  3827  3875 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:35:55.038  3827  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:35:55.038  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:55.038  3827  3875 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:35:55.039  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.039  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.039  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.039  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:55.040  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.040  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:55.040  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.041  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.041  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.042  3827  3875 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:35:55.046  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:55.053  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:55.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:55.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:55.055  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.055  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:55.055  3827  3875 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-09 13:35:55.055  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-09 13:35:55.055  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:55.056  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:35:55.056  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:55.056  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:55.056  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:35:55.057  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:55.057  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:55.057  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:55.057  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:35:55.057  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:55.057  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:55.057  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.059  3827  3899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:55.060  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.060  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:55.061  3827  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:35:55.061  3827  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:35:55.061  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:35:55.065  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:35:55.066  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:35:55.066  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:35:55.068  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:35:55.068  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:35:55.069  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-09 13:35:55.069  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:55.069  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:35:55.069  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:35:55.070  3827  3875 D BluetoothAdapter: STATE_ON
09-09 13:35:55.072  2695  2818 D BtGatt.GattService: registerClient() - UUID=5fa4b95f-74f2-406b-8591-1aa9ca1ab6cc
09-09 13:35:55.073  2695  2719 D BtGatt.GattService: onClientRegistered() - UUID=5fa4b95f-74f2-406b-8591-1aa9ca1ab6cc, clientIf=5
09-09 13:35:55.073  3827  3839 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-09 13:35:55.074  2695  2722 D BtGatt.AdvertiseManager: message : 0
09-09 13:35:55.076  2695  2722 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:35:55.091  2695  2719 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:35:55.102  2695  2719 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:35:55.103  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:35:55.103  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:35:55.106  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:35:55.108  3827  3875 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:35:55.108  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:35:55.109  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:35:55.109  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:35:55.109  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:35:55.109  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:35:55.109  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:35:55.118  3827  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:55.119  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:35:55.613  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:55.614  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:35:55.614  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:35:55.614  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:35:55.615  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:35:55.615  3827  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-09 13:35:55.615  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:55.616  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:55.616  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:55.615  3827  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:55.616  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:35:55.616  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:55.617  3827  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:35:55.617  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:35:55.617  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:55.617  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:35:55.618  3827  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:55.621  3827  3875 D BluetoothAdapter: STATE_ON
09-09 13:35:55.622  3827  3875 D BluetoothLeScanner: could not find callback wrapper
,09-09 13:35:55.622  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:35:55.623  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:35:55.627  2695  2722 D BtGatt.AdvertiseManager: message : 1
,09-09 13:35:55.630  2695  2722 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:35:55.650  2695  2719 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:35:55.650  2695  2719 D BtGatt.GattService: Client app is not null!
09-09 13:35:55.652  2695  2706 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:35:55.654  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:35:55.654  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:35:55.654  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:35:55.654  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:35:55.655  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:35:55.659  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:55.659  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:35:55.660  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:55.661  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:55.663  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:55.663  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:55.663  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:35:55.663  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:35:55.664  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:55.664  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.664  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:55.675  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:55.675  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:55.675  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:55.675  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:55.675  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:55.675  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:55.675  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.676  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:55.676  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:55.678  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:55.678  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:55.679  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:35:55.679  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:35:55.680  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:35:55.680  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:55.680  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:55.680  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:35:55.681  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:55.681  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:35:55.681  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:35:55.681  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:35:55.681  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.681  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:55.681  3827  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:55.681  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:35:55.682  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
,09-09 13:35:55.682  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:55.682  3827  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:35:55.682  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:55.682  3827  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:55.682  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:55.682  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:35:55.683  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.683  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.684  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:55.685  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:35:55.685  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:55.685  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:55.685  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:55.685  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:55.685  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.686  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.687  3827  3875 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:35:55.688  3827  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 13:35:55.688  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:55.688  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:55.688  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:55.689  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:55.689  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.689  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.689  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:55.689  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:55.689  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:55.689  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:55.689  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.689  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.697  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.697  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:55.697  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.698  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
09-09 13:35:55.698  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.698  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
,09-09 13:35:55.698  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.699  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.699  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:55.701  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.701  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.702  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.702  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a591ab2 not in the list
,09-09 13:35:55.702  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.702  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5beca03 not in the list
09-09 13:35:55.703  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.703  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:35:55.703  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.706  3827  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:35:55.706  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:55.707  3827  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-09 13:35:55.707  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:55.707  3827  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:35:55.707  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 13:35:55.714  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 13:35:55.715  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 13:35:55.716  3827  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-09 13:35:55.717  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-09 13:35:55.717  3827  3875 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:35:55.717  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:35:55.717  3827  3875 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:35:55.717  3827  3875 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-09 13:35:55.718  3827  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 13:35:55.718  3827  3875 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-09 13:35:55.719  3827  3875 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-09 13:35:55.719  3827  3875 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-09 13:35:55.719  3827  3875 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-09 13:35:55.719  3827  3875 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-09 13:35:55.722  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:35:55.722  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0e6b0 added. We now have 3 listener(s)
,09-09 13:35:55.724  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:35:55.724  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:55.724  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:55.724  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:35:55.724  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffc0929 added. We now have 3 listener(s),
,09-09 13:35:55.724  3827  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:55.725  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:55.727  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:55.731  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:55.731  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.731  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.731  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.731  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.731  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.731  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:55.731  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:55.733  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-09 13:35:55.733  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:55.735  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:35:55.736  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.736  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:55.736  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:35:55.736  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f0e6b0 removed from the list
,09-09 13:35:55.736  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.736  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffc0929 removed from the list
09-09 13:35:55.736  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.736  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:35:55.736  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:55.738  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:55.738  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db0824f added. We now have 3 listener(s)
,09-09 13:35:55.739  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:35:55.739  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.740  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:55.740  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:55.740  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:55.740  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f5bddc added. We now have 3 listener(s)
09-09 13:35:55.740  3827  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:55.740  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:55.742  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:55.746  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:55.746  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.746  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.746  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.746  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.746  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.746  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:55.746  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:55.748  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:55.748  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:55.749  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:55.749  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:55.749  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:55.749  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:35:55.749  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db0824f removed from the list
09-09 13:35:55.749  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:55.749  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f5bddc removed from the list
,09-09 13:35:55.751  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.751  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:55.751  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:55.752  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:35:55.752  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5154dba added. We now have 3 listener(s)
,09-09 13:35:55.754  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:35:55.754  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.754  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:55.754  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:35:55.754  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:55.754  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f9cf46b added. We now have 3 listener(s)
,09-09 13:35:55.755  3827  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:55.755  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:35:55.757  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:55.761  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:55.761  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.761  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.761  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.761  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.761  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:55.761  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:55.761  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:55.763  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:55.763  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:55.765   870  1528 D WifiService: setWifiEnabled: false pid=3827, uid=10000
,09-09 13:35:55.765   870  1528 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:35:55.766  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.768  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.781  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:35:55.784   870  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:35:55.784   870  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 13:35:55.784   870  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:35:55.784   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:35:55.796   870  1868 D DhcpClient: Clearing IP address
,09-09 13:35:55.796   370   868 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:55.799   370   868 D CommandListener: Setting iface cfg
,09-09 13:35:55.800  1511  2461 V NativeCrypto: Read error: ssl=0x9af7a400: I/O error during system call, Connection timed out
,09-09 13:35:55.804  1511  2461 V NativeCrypto: SSL shutdown failed: ssl=0x9af7a400: I/O error during system call, Broken pipe
,09-09 13:35:55.806   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 13:35:55.807   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-09 13:35:55.813   396   396 E Parcel  : Reading a NULL string not supported here.
09-09 13:35:55.814   870  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 13:35:55.817   870  1877 D DhcpClient: Receive thread stopped
09-09 13:35:55.821   870  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 13:35:55.822   870  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:35:55.840   870   883 I ActivityManager: Start proc 3906:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-09 13:35:55.855   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0,
,09-09 13:35:55.887   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:35:55.887   370   868 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:35:55.888   870  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-09 13:35:55.888   870  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:55.892   870   887 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:35:55.895   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:35:55.901  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.901  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.901  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.901  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:55.901  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.901  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.901  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.901  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.903  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:55.905   870  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 13:35:55.907  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.907  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.907  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.907  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:55.907  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.907  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.907  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.907  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.910  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:55.914  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.914  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.914  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.914  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:55.914  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.914  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.914  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.914  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.916  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:55.917  1904  2337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:55.921  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.921  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.921  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:55.921  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:55.921  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.921  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.921  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.921  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.923  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:55.924  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 13:35:55.925  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.929  3906  3906 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-09 13:35:55.965   370   868 E Netd    : netlink response contains error (No such file or directory)
,09-09 13:35:55.967   870  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 13:35:56.060  3906  3930 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-09 13:35:56.060  3906  3930 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 13:35:56.061  3906  3930 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 13:35:56.061  3906  3930 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 13:35:56.102  3906  3930 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-09 13:35:56.102  3906  3930 I Babel_SMS: MmsConfig.loadFromResources
,09-09 13:35:56.103  3906  3930 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 13:35:56.104  3906  3930 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 13:35:56.132  3906  3906 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:56.134  3906  3906 I Babel_Crash: startup - clean
,09-09 13:35:56.158  3906  3906 I Babel_telephony: TeleModule.launchCompleted
,09-09 13:35:56.170   870  1704 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 13:35:56.181  3906  3906 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-09 13:35:56.186  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:35:56.188  3906  3906 W Babel   : BAM#gBA: invalid account id: -1
,09-09 13:35:56.189  3906  3906 W Babel   : BAM#gBA: invalid account id: -1
,09-09 13:35:56.189  3906  3906 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-09 13:35:56.191  3906  3935 I Babel   : deleted: false for 0
,09-09 13:35:56.206   870  2292 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 13:35:56.229  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 13:35:56.236  1727  1727 D SystemUpdateService: onCreate
,09-09 13:35:56.239  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 13:35:56.252  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:35:56.273  1727  2422 I iu.UploadsManager: num queued entries: 0
,09-09 13:35:56.273  1727  2422 I iu.UploadsManager: num updated entries: 0
,09-09 13:35:56.275   870  2000 D WifiService: setWifiEnabled: true pid=3827, uid=10000
,09-09 13:35:56.275   870  2000 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:35:56.276  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:35:56.277  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 13:35:56.294  1727  3937 I SystemUpdateService: active receiver: enabled
,09-09 13:35:56.301   870   881 I ActivityManager: Start proc 3941:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 13:35:56.305   870  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:35:56.324   870  1312 D WifiConfigStore: loaded 0 passpoint configs
,09-09 13:35:56.325   870  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 13:35:56.326   870  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 13:35:56.326   870  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:35:56.326   870  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 13:35:56.326   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 13:35:56.327   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 13:35:56.329  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.329  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.329  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.329  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.329  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.329  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.329  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.329  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:56.331  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:56.334  3906  3906 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 13:35:56.334  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.334  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.334  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.334  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.334  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.334  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.334  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.334  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:56.336  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:56.340  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.340  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.340  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:35:56.340  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.340  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.340  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.340  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.340  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:35:56.341   370   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 13:35:56.341   370   868 D CommandListener: Setting iface cfg
09-09 13:35:56.343   870  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=14.00 rxSuccessRate=35.75 delta 1000 -> 994
09-09 13:35:56.344   870  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-09 13:35:56.344   870  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:35:56.345  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:56.350   870  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 13:35:56.351   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-09 13:35:56.352   870  1311 D WifiNative-HAL: p2pGetDeviceAddress,
,09-09 13:35:56.357   870  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 13:35:56.357   870  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 13:35:56.367  3941  3941 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 13:35:56.368  1727  3937 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:35:56.377  3941  3941 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:56.378  1727  2422 I iu.SyncManager: NEXT; no task
,09-09 13:35:56.395  1727  3937 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 13:35:56.395  1727  3937 I SystemUpdateService: now status is 0 (complete)
,09-09 13:35:56.395  1727  3937 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 13:35:56.402  3941  3941 D SprintDMHelper: simOperator: 
,09-09 13:35:56.402  3941  3941 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:35:56.395  1727  3937 I SystemUpdateService: file has been verified
,09-09 13:35:56.405  1727  3937 I SystemUpdateService: OTA package size = 12249756
,09-09 13:35:56.416   870  2143 I ActivityManager: Start proc 3953:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 13:35:56.426   870  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 13:35:56.460  3906  3906 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:35:56.470  3906  3906 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:35:56.471  1727  3937 I SystemUpdateService: showing system update notification
,09-09 13:35:56.482  3906  3906 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:35:56.495  3906  3906 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:35:56.516  3906  3906 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:35:56.520   870  1528 I ActivityManager: Killing 3498:android.process.acore/u0a5 (adj 15): empty #17
,09-09 13:35:56.564  3906  3906 I vclib   : onServiceConnected
,09-09 13:35:56.609   870  2000 I ActivityManager: Start proc 3969:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 13:35:56.614  3906  3968 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 13:35:56.618   870  2051 I ActivityManager: Killing 3678:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 13:35:56.665  1727  1727 D SystemUpdateService: onDestroy
,09-09 13:35:56.667   870  2292 I ActivityManager: Killing 3695:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 13:35:56.689  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 13:35:56.762  3969  3969 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:35:56.762  3969  3969 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:35:56.762  3969  3969 I GAv4    :   adb logcat -s GAv4
,09-09 13:35:56.778  3969  3969 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:35:56.785  3969  3969 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:35:56.789  3827  3875 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 13:35:56.814  3969  3986 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:35:56.927  3969  3969 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 13:35:56.972  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 13:35:56.988  3969  3969 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5054-5057)
,09-09 13:35:56.988  3969  3969 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:35:57.002  3969  3969 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {add4847}
,09-09 13:35:57.003  3969  3969 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:35:57.003  3969  3969 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:35:57.012  3969  3969 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:35:57.013  3969  3969 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 13:35:57.030  3969  3969 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 13:35:57.043  3969  3969 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:35:57.043  3969  3969 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:35:57.043  3969  3969 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:35:57.043  3969  3969 I Adreno  : Build Date                       : 10/20/15
09-09 13:35:57.043  3969  3969 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:35:57.043  3969  3969 I Adreno  : Local Branch                     : M14
09-09 13:35:57.043  3969  3969 I Adreno  : Remote Branch                    : 
09-09 13:35:57.043  3969  3969 I Adreno  : Remote Branch                    : 
09-09 13:35:57.043  3969  3969 I Adreno  : Reconstruct Branch               : 
,09-09 13:35:57.107  3969  3969 I NSApplication: Starting up...
,09-09 13:35:57.132  3969  4016 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 13:35:57.137   870  1937 I ActivityManager: Start proc 4021:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 13:35:57.141   870  1937 I ActivityManager: Killing 2086:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 13:35:57.226  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 13:35:57.300  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 13:35:57.449   870  2143 I ActivityManager: Killing 3721:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 13:35:57.560   870  2237 I ActivityManager: Start proc 4035:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 13:35:57.629  4035  4035 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 13:35:57.682  4035  4035 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 13:35:57.694   870  1400 I ActivityManager: Killing 3639:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-09 13:36:00.155  2695  2813 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-09 13:36:00.159  2695  2815 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,09-09 13:36:01.574  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 13:36:01.617  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:36:01.618  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 13:36:01.629   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:36:01.646   870  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:36:01.646   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:01.647   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 13:36:01.662   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:36:01.674   370   868 D CommandListener: Setting iface cfg
,09-09 13:36:01.677   870  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 13:36:01.690   870  1314 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-09 13:36:01.692   870  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 13:36:01.717   870  4072 D DhcpClient: Receive thread started
,09-09 13:36:01.795   870  1312 E native  : do suspend false
,09-09 13:36:01.804   870  1868 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 13:36:01.816  3827  3987 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
,09-09 13:36:01.824  2695  2713 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 13:36:01.825  2695  2713 D BluetoothAdapterProperties: Setting state to 13
,09-09 13:36:01.825  2695  2713 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 13:36:01.826  2695  2713 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 13:36:01.827  2695  2713 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:36:01.829   870  4072 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172672, domain null
,09-09 13:36:01.830   870  1868 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172672 seconds
09-09 13:36:01.831  2695  2719 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:36:01.832  2695  2713 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 13:36:01.832   870  1868 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 13:36:01.837  2695  2695 D BluetoothMapService: onReceive
,09-09 13:36:01.837  2695  2695 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:01.837  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:01.837  2695  2695 D BluetoothMapService: STATE_TURNING_OFF
09-09 13:36:01.838  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:01.838  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.838  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:01.838  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:01.838  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:01.838  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:01.838  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:01.838  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:01.838  2695  2695 D BluetoothMapService: MAP Service closeService in
,09-09 13:36:01.838  2695  2695 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 13:36:01.839  2695  2695 D ObexServerSockets0: shutdown(block = true)
09-09 13:36:01.840  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:01.840  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:01.845  2695  2853 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-09 13:36:01.846   870  4072 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-09 13:36:01.846  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:01.846  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:01.846  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.846  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:01.846  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:01.846  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:01.846  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:01.846  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:01.846  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:01.847  2695  2695 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:36:01.847  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:36:01.847  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:01.847  2695  2854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 13:36:01.849  2695  2815 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 13:36:01.850  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:01.850  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:01.850  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:01.850  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:01.850  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:01.850  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:01.850  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:01.850  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:01.850  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:01.851  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:01.851  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:01.853  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.850  2695  2695 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:36:01.854  2695  2695 I BtOppRfcommListener: stopping Accept Thread
09-09 13:36:01.854  2695  3432 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 13:36:01.854  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.855  2695  3432 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 13:36:01.856  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:01.865   870   883 I ActivityManager: Start proc 4075:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-09 13:36:01.866   870  1868 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-09 13:36:01.868  2695  2695 D HeadsetService: Received stop request...Stopping profile...
09-09 13:36:01.870   370   868 D CommandListener: Setting iface cfg
09-09 13:36:01.872   870   870 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:01.873   870   870 D BluetoothHeadset: Proxy object disconnected
,09-09 13:36:01.873   870   870 D BluetoothHeadset: Proxy object disconnected
,09-09 13:36:01.873  1983  2154 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:01.873   870  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 13:36:01.873  1369  1393 D BluetoothHeadset: Proxy object disconnected
,09-09 13:36:01.874  1369  1369 D HeadsetProfile: Bluetooth service disconnected
,09-09 13:36:01.876   870  1868 D DhcpClient: Scheduling renewal in 86399s
09-09 13:36:01.879  2695  2695 D A2dpService: Received stop request...Stopping profile...
,09-09 13:36:01.880  2695  2823 D A2dpStateMachine: Exit Disconnected: -1
,09-09 13:36:01.881  1369  1369 D BluetoothA2dp: Proxy object disconnected
09-09 13:36:01.881   870   870 D BluetoothA2dp: Proxy object disconnected
,09-09 13:36:01.882  2695  2695 D HidService: Received stop request...Stopping profile...
,09-09 13:36:01.882  2695  2695 D HidService: Stopping Bluetooth HidService
,09-09 13:36:01.882  1369  1369 D BluetoothInputDevice: Proxy object disconnected
,09-09 13:36:01.883  1369  1369 D HidProfile: Bluetooth service disconnected
,09-09 13:36:01.884  2695  2695 V BluetoothAdapterState: isTurningOff()=true
,09-09 13:36:01.884  2695  2695 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:36:01.884  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:01.884  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:36:01.887  2695  2695 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:36:01.887  2695  2695 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:36:01.888  2695  2719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008,
09-09 13:36:01.888  2695  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:36:01.888  2695  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:36:01.888  2695  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:36:01.888  2695  2719 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 13:36:01.888  2695  2695 D HealthService: Received stop request...Stopping profile...
09-09 13:36:01.891  2695  2695 D PanService: Received stop request...Stopping profile...
09-09 13:36:01.891   870  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-09 13:36:01.892  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:36:01.892  1369  1369 D PanProfile: Bluetooth service disconnected
09-09 13:36:01.892   870  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 13:36:01.893   870  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:01.893   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 13:36:01.894   870  1314 D ConnectivityService: Adding iface wlan0 to network 101
09-09 13:36:01.896  2695  2695 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:36:01.896  2695  2695 D BluetoothMapService: stop()
09-09 13:36:01.898   870  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:36:01.901  2695  2695 D BluetoothMapAppObserver: deinitObservers()
09-09 13:36:01.901  2695  2695 D BluetoothMapAppObserver: removeReceiver()
,09-09 13:36:01.902  2695  2695 V BluetoothAdapterState: isTurningOff()=true
09-09 13:36:01.902  2695  2695 V BluetoothAdapterState: isTurningOn()=false
09-09 13:36:01.902  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:01.902  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:36:01.903  2695  2719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 13:36:01.903  2695  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:36:01.903  2695  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:36:01.904  2695  2813 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:36:01.904  2695  2813 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:36:01.904  2695  2813 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:36:01.904  2695  2813 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:36:01.904  2695  2695 V BluetoothAdapterState: isTurningOff()=true
09-09 13:36:01.904  2695  2695 V BluetoothAdapterState: isTurningOn()=false
09-09 13:36:01.904  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:01.904  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:36:01.904  2695  2695 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:36:01.905  2695  2719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 13:36:01.905  2695  2695 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:36:01.905  2695  2695 V BluetoothAdapterState: isTurningOff()=true
,09-09 13:36:01.905  2695  2695 V BluetoothAdapterState: isTurningOn()=false
09-09 13:36:01.905  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:01.905  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:36:01.905  2695  2695 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:36:01.906  2695  2719 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 13:36:01.906  2695  2695 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:36:01.906  2695  2695 V BluetoothAdapterState: isTurningOff()=true
09-09 13:36:01.906  2695  2695 V BluetoothAdapterState: isTurningOn()=false
09-09 13:36:01.906  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:36:01.906  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:36:01.907  2695  2695 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:36:01.907  2695  2695 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:36:01.908  2695  2695 D BluetoothMapService: MAP Service closeService in
09-09 13:36:01.908  2695  2695 V BluetoothAdapterState: isTurningOff()=true
09-09 13:36:01.908  2695  2695 V BluetoothAdapterState: isTurningOn()=false
09-09 13:36:01.908  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:01.908  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:36:01.908  2695  2713 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-09 13:36:01.908  2695  2713 D BluetoothAdapterProperties: Setting state to 15
09-09 13:36:01.908  2695  2695 D BluetoothMapService: cleanup()
09-09 13:36:01.908  2695  2713 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 13:36:01.908  2695  2695 D BluetoothMapService: MAP Service closeService in
09-09 13:36:01.909  2695  2713 I BluetoothAdapterState: Entering BleOnState
09-09 13:36:01.909   870   887 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:36:01.909   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:01.909  1983  2179 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:01.910  1369  2116 D BluetoothPan: onBluetoothStateChange on: false
,09-09 13:36:01.911  1369  1369 D BluetoothMap: Proxy object disconnected
09-09 13:36:01.912  1369  1369 D MapProfile: Bluetooth service disconnected
09-09 13:36:01.913  1369  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:36:01.914  1369  1393 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:01.914  1369  1395 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:36:01.915   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:01.915  1369  2116 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:36:01.916  1369  1395 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 13:36:01.917   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:01.917  2695  2713 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 13:36:01.917  2695  2713 D BluetoothAdapterProperties: Setting state to 16
09-09 13:36:01.917  2695  2713 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 13:36:01.918  2695  2713 D BluetoothAdapterProperties: onBleDisable
,09-09 13:36:01.918  2695  2713 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:36:01.918  2695  2715 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 13:36:01.919  2695  2719 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:36:01.919  2695  2813 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 13:36:01.919  2695  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:36:01.920  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.927  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.928  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:01.929  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.930  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.931  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:01.939   870  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:36:01.939   870  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-09 13:36:01.940   870  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 13:36:01.942   870  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 13:36:01.943   870  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-09 13:36:01.952   870  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 13:36:01.957   870  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-09 13:36:01.957   870  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-09 13:36:01.957   870  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 13:36:01.958   870  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:36:01.958   870  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:01.958   870  1314 D ConnectivityService:    accepting network in place of null
09-09 13:36:01.959   870  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:36:01.969   870  4071 D NetlinkSocketObserver: NeighborEvent{elapsedMs=150039, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:36:01.973  4075  4075 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 13:36:01.981   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:36:01.982  4075  4075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:36:01.988   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18cc1a5:true
,09-09 13:36:01.991  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:36:02.004   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:36:02.006   870  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:36:02.006   870  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:02.012   870  2291 I ActivityManager: Start proc 4094:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 13:36:02.014   870  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 13:36:02.014  4075  4075 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 13:36:02.015   870   887 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:02.021  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.022  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.022  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.022  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:02.022  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:02.022  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:02.022  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.022  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:02.022  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:02.023  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.023  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.026  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.026  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.026  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.026  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:02.026  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:02.026  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:02.026  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.026  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:02.026  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:02.027  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.027  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.030  4075  4075 D BluetoothMap: Create BluetoothMap proxy object
09-09 13:36:02.030  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.030  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.030  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.030  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:02.030  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:02.030  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:02.030  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.030  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:02.030  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:02.031  3827  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:36:02.031  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:02.039  4075  4075 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 13:36:02.043   870  4070 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-09 13:36:02.051  4094  4094 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 13:36:02.053  4075  4075 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:36:02.100   870  4117 D GpsLocationProvider: NTP server returned: 1473420836980 (Fri Sep 09 13:33:56 GMT+02:00 2016) reference: 25047 certainty: 10 system time offset: -125120
,09-09 13:36:02.101   870  4117 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,09-09 13:36:02.103   870  4070 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:36:02 GMT], X-Android-Received-Millis=[1473420962102], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473420962080]}
,09-09 13:36:02.104   870  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 13:36:02.104   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-09 13:36:02.104   870  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:02.105   870  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 13:36:02.121  2695  2719 I bt_hci  : shut_down
,09-09 13:36:02.127  2695  2724 I bt_vendor: low_power_mode_cb
09-09 13:36:02.128  2695  2724 D bt_hwcfg: hw_epilog_process
,09-09 13:36:02.151  2695  2724 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-09 13:36:02.151  2695  2724 I bt_vendor: epilog_cb
09-09 13:36:02.151  2695  2724 I bt_hci  : epilog_finished_callback
,09-09 13:36:02.152  2695  2719 I bt_hci_h4: hal_close
,09-09 13:36:02.153  2695  2719 I bt_userial_vendor: device fd = 51 close
,09-09 13:36:02.155  3023  4111 V KeepSync: Connecting to GoogleApiClient
,09-09 13:36:02.155   870  2292 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:36:02.190  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:36:02.197  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:36:02.215   870   890 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 13:36:02.219  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-09 13:36:02.223  1511  2441 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 13:36:02.223  1511  2441 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 13:36:02.223  1511  2441 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:36:02.223  1511  2441 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:36:02.234   870   890 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:36:02.234   870   890 I Adreno  : Build Date                       : 10/20/15
09-09 13:36:02.234   870   890 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:36:02.234   870   890 I Adreno  : Local Branch                     : M14
09-09 13:36:02.234   870   890 I Adreno  : Remote Branch                    : 
09-09 13:36:02.234   870   890 I Adreno  : Remote Branch                    : 
09-09 13:36:02.234   870   890 I Adreno  : Reconstruct Branch               : 
,09-09 13:36:02.234  1511  2997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 13:36:02.235  1511  2997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:36:02.235  1511  2997 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:36:02.235  1511  2997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:36:02.238  1727  4120 V BaseAuthAsyncOperation: access token request failed
,09-09 13:36:02.241  3023  4111 V KeepSync: GoogleApiClient failed to connect with error code: 4
09-09 13:36:02.251   280   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (109 us)
09-09 13:36:02.252  3553  4118 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:36:02.252  3553  4118 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:36:02.252  3553  4118 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	... 12 more
09-09 13:36:02.252  3553  4118 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at fal.a(PG:38)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:36:02.252  3553  4118 E HttpOperation: 	... 14 more
,09-09 13:36:02.260  2695  2715 D bt_stack_manager: event_shut_down_stack finished.
,09-09 13:36:02.262  2695  2713 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-09 13:36:02.264  2695  2695 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:36:02.264  2695  2713 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 13:36:02.265  2695  2695 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 13:36:02.265  2695  2695 D BtGatt.GattService: stop()
09-09 13:36:02.265  2695  2695 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 13:36:02.267  2695  2695 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:36:02.267  2695  2695 V BluetoothAdapterState: isTurningOn()=false
09-09 13:36:02.267  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:36:02.267  2695  2695 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 13:36:02.267  2695  2713 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 13:36:02.268  2695  2713 D BluetoothAdapterProperties: Setting state to 10
09-09 13:36:02.268  2695  2713 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 13:36:02.269  2695  2713 I BluetoothAdapterState: Entering OffState
09-09 13:36:02.271   870   887 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 13:36:02.284  2695  2695 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-09 13:36:02.284  2695  2695 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 13:36:02.284  2695  2695 I BluetoothServiceJni: cleanupNative: return from cleanup,
09-09 13:36:02.284  2695  2715 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 13:36:02.286  2695  2715 D bt_stack_manager: event_clean_up_stack finished.
,09-09 13:36:02.287  1511  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:36:02.287  1511  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:36:02.288  1511  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:36:02.288  1511  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:36:02.309  3553  4118 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:36:02.309  3553  4118 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at hec.a(PG:42)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at hee.a(PG:102)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at czr.a(PG:65)
,09-09 13:36:02.309  3553  4118 E HttpOperation: 	at kka.a(PG:108)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:36:02.309  3553  4118 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	... 15 more
09-09 13:36:02.309  3553  4118 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at fal.a(PG:38)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:36:02.309  3553  4118 E HttpOperation: 	... 17 more
,09-09 13:36:02.310  3553  4118 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:36:02.310  3553  4118 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	... 15 more
09-09 13:36:02.310  3553  4118 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:36:02.310  3553  4118 E ExperimentLoader: 	... 17 more
,09-09 13:36:02.330  2695  2695 I art     : System.exit called, status: 0
09-09 13:36:02.331  2695  2695 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 13:36:02.409   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129294, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:36:02.442   870  1704 I ActivityManager: Process com.android.bluetooth (pid 2695) has died
,09-09 13:36:02.471  4094  4094 D StrictMode: StrictMode policy violation; ~duration=352 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 13:36:02.471  4094  4094 D StrictMode: 	,at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:02.471  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:02.472  4094  4094 D StrictMode: StrictMode policy violation; ~duration=351 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:02.472  4094  4094 D StrictMod,e: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:02.472  4094  4094 D StrictMode: StrictMode policy violation; ~duration=350 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:02.472  4094  4094 D StrictMode: StrictMode policy violation; ~duration=349 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.j,ava:177)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:02.472  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:02.473  4094  4094 D StrictMode: StrictMode policy violation; ~duration=344 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:02.473  4094  4094 D StrictMode: StrictMode policy violation; ~duration=277 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:02.473  4094  4094 D StrictMode: StrictMode policy violation; ~duration=276 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:02.473  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:02.474  4094  4094 D StrictMode: StrictMode policy violation; ~duration=276 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:36:02.474  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:02.474  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:02.481  4075  4075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:36:02.527   870  2051 I ActivityManager: Start proc 4136:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-09 13:36:02.529  4075  4075 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:36:02.593  1511  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 13:36:02.595  1511  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 13:36:02.595  1511  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:36:02.595  1511  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:36:02.618  3023  4111 E KeepSync: IOException
09-09 13:36:02.618  3023  4111 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:36:02.618  3023  4111 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:36:02.618  3023  4111 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:36:02.618  3023  4111 E KeepSync: 	... 10 more
,09-09 13:36:02.620  3023  4111 W KeepSync: Sync result 2
,09-09 13:36:02.629  4136  4136 D AdapterServiceConfig: Adding HeadsetService
,09-09 13:36:02.631   870  2051 I ActivityManager: Killing 2981:com.google.android.calendar/u0a37 (adj 15): empty #17
09-09 13:36:02.631   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128415, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:36:02.640  4136  4136 D AdapterServiceConfig: Adding A2dpService
,09-09 13:36:02.640  4136  4136 D AdapterServiceConfig: Adding HidService
,09-09 13:36:02.642  4136  4136 D AdapterServiceConfig: Adding HealthService
09-09 13:36:02.644  4136  4136 D AdapterServiceConfig: Adding PanService
09-09 13:36:02.645  4136  4136 D AdapterServiceConfig: Adding GattService
09-09 13:36:02.645  4136  4136 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 13:36:02.711   870  2051 I ActivityManager: Killing 3778:com.google.android.deskclock/u0a44 (adj 15): empty #17
,09-09 13:36:02.757  4094  4113 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 13:36:02.770  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:36:02.783   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d90d5bf:true
,09-09 13:36:02.805  3827  3827 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:36:02.805  3827  3827 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 13:36:02.829   870   890 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 13:36:02.838   870   890 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 13:36:02.858   870   888 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-09 13:36:02.858   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
09-09 13:36:02.858   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-09 13:36:02.862  3827  3827 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3886331 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7fab461, 16908290=android.view.AbsSavedState$1@7fab461}, android:focusedViewId=100}]}]
09-09 13:36:02.862  3827  3827 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-09 13:36:02.863  3827  3827 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:36:02.863  3827  3827 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 13:36:02.865   870  1703 I ActivityManager: Killing 3796:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-09 13:36:02.953  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 13:36:02.956  1727  1727 D SystemUpdateService: onCreate
,09-09 13:36:02.962  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 13:36:02.964  1727  4152 I SystemUpdateService: active receiver: enabled
,09-09 13:36:02.967  1727  4152 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:36:02.969  1727  4152 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 13:36:02.969  1727  4152 I SystemUpdateService: now status is 0 (complete)
09-09 13:36:02.969  1727  4152 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 13:36:02.969  1727  4152 I SystemUpdateService: file has been verified
,09-09 13:36:02.970  1727  4152 I SystemUpdateService: OTA package size = 12249756
,09-09 13:36:02.972  1727  4152 I SystemUpdateService: showing system update notification
,09-09 13:36:02.980  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:36:02.981  1727  2422 I iu.UploadsManager: num queued entries: 0
,09-09 13:36:02.982  1727  2422 I iu.UploadsManager: num updated entries: 0
09-09 13:36:02.982  1727  2422 I iu.SyncManager: NEXT; no task
,09-09 13:36:02.985  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:36:02.987  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 13:36:02.990  3941  3941 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:02.990  1727  4155 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 13:36:02.990  1727  4155 W BaseAppContext: Using Auth Proxy for data requests.
09-09 13:36:02.992  1727  4155 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 13:36:02.996  3941  3941 D SprintDMHelper: simOperator: 
09-09 13:36:02.996  3941  3941 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:36:03.001  1727  1727 D SystemUpdateService: onDestroy
,09-09 13:36:03.007   870  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 13:36:03.028  1511  2997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-09 13:36:03.028  1511  2997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 13:36:03.028  1511  2997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:36:03.028  1511  2997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:36:03.041  1727  4155 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-09 13:36:03.102   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 13:36:03.104   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 13:36:03.104   870  1338 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
,09-09 13:36:03.111   870   890 I DreamManagerService: Entering dreamland.
,09-09 13:36:03.113   870   890 I PowerManagerService: Dozing...
,09-09 13:36:03.114   870   885 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 13:36:03.116  3906  4158 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:36:03.142   374  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-09 13:36:03.142   374  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 13:36:03.145   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:36:03.150   870  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 13:36:03.153  1967  4166 D NfcService: Discovery configuration equal, not updating.
,09-09 13:36:03.155   870  1312 E native  : do suspend false
,09-09 13:36:03.162   870  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 13:36:03.177   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:36:03.181   870  1312 E native  : do suspend true
,09-09 13:36:03.283   374  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 13:36:03.284   374  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 13:36:06.831  3827  4073 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
,09-09 13:36:06.835  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:36:06.835  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.840  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:06.840  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:06.840  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.841  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:36:06.841  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5154dba removed from the list
,09-09 13:36:06.841  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:36:06.842  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f9cf46b removed from the list
09-09 13:36:06.842  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:36:06.842  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:06.842  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.845  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:06.845  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cba8b86 added. We now have 3 listener(s)
,09-09 13:36:06.853  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:36:06.853  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:06.853  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:06.853  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:06.853  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1946c47 added. We now have 3 listener(s)
,09-09 13:36:06.853  3827  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:06.854  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:36:06.860  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:06.862  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:36:06.862  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:06.862  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:06.862  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:06.862  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:06.862  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:06.862  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:06.862  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:06.862  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:06.862  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:06.863  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:06.863  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:36:06.863  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:06.863  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:06.863  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:06.863  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:06.863  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cba8b86 removed from the list
,09-09 13:36:06.864  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:06.864  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1946c47 removed from the list
,09-09 13:36:06.866  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:06.869  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:06.869  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:06.869  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:06.871  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:36:06.872  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5cd359d added. We now have 3 listener(s)
09-09 13:36:06.873  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:36:06.873  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:06.874  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:36:06.874  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:06.874  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323da12 added. We now have 3 listener(s)
,09-09 13:36:06.874  3827  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:36:06.876  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:36:06.879  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:06.881  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:36:06.882  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:06.882  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:06.882  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:06.882  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:06.882  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:06.882  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:06.882  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:06.882  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:06.882  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:36:06.882  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:06.882  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:36:06.886  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:06.888  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:06.892  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:06.915  4136  4136 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 13:36:06.914   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@da13525:true
,09-09 13:36:06.920  4136  4136 I bt_bluedroid: init
,09-09 13:36:06.921  4136  4173 I BluetoothAdapterState: Entering OffState
,09-09 13:36:06.926  4136  4174 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 13:36:06.926  4136  4174 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 13:36:06.926  4136  4174 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 13:36:06.927  4136  4174 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 13:36:06.929  4136  4136 I bt_bluedroid: get_profile_interface socket
,09-09 13:36:06.931  4136  4177 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 13:36:06.933  4136  4177 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:36:06.934  4136  4136 I bt_bluedroid: get_profile_interface sdp
,09-09 13:36:06.939  4136  4147 I bt_bluedroid: config_hci_snoop_log
,09-09 13:36:06.941   870   887 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 13:36:06.949  4136  4173 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 13:36:06.950  4136  4173 D BluetoothAdapterProperties: Setting state to 14
09-09 13:36:06.951  4136  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 13:36:06.955  4136  4173 D BluetoothBondStateMachine: make
,09-09 13:36:06.960  4136  4178 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 13:36:06.968  4136  4173 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:36:06.971  4136  4136 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 13:36:06.977  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b470b5
,09-09 13:36:06.979  4136  4136 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:36:06.980  4136  4136 D BtGatt.GattService: Received start request. Starting profile...
09-09 13:36:06.980  4136  4136 D BtGatt.GattService: start()
,09-09 13:36:06.980  4136  4136 I bt_bluedroid: get_profile_interface gatt
,09-09 13:36:06.982  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b470b5
,09-09 13:36:06.983  4136  4136 D BtGatt.AdvertiseManager: advertise manager created
,09-09 13:36:06.997  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:36:06.997  4136  4136 V BluetoothAdapterState: isTurningOn()=false
09-09 13:36:06.997  4136  4136 V BluetoothAdapterState: isBleTurningOn()=true
09-09 13:36:06.997  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:36:06.998  4136  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 13:36:06.998  4136  4173 I bt_bluedroid: enable
09-09 13:36:06.998  4136  4174 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 13:36:06.999  4136  4174 I bt_hci  : start_up
,09-09 13:36:07.021  4136  4174 I bt_vendor: alloc value 0xb399e189
,09-09 13:36:07.021  4136  4174 I bt_vendor: init
,09-09 13:36:07.021  4136  4174 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 13:36:07.022  4136  4174 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 13:36:07.129  4136  4174 D bt_hci  : start_up starting async portion
,09-09 13:36:07.129  4136  4181 I bt_hci  : event_finish_startup
,09-09 13:36:07.130  4136  4181 I bt_hci_h4: hal_open
,09-09 13:36:07.130  4136  4181 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 13:36:07.136  4136  4181 I bt_userial_vendor: device fd = 51 open
,09-09 13:36:07.170  4136  4181 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:36:07.202  4136  4181 D bt_hwcfg: Chipset BCM4354A2
,09-09 13:36:07.203  4136  4181 D bt_hwcfg: Target name = [BCM4354A2]
09-09 13:36:07.204  4136  4181 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 13:36:07.892  4136  4181 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 13:36:07.894  4136  4181 D bt_hwcfg: Settlement delay -- 100 ms
09-09 13:36:07.894  4136  4181 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 13:36:08.011  4136  4181 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:36:08.012  4136  4181 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 13:36:08.042  4136  4181 I bt_hwcfg: vendor lib fwcfg completed
,09-09 13:36:08.042  4136  4181 I bt_vendor: firmware callback
09-09 13:36:08.042  4136  4181 I bt_hci  : firmware_config_callback
,09-09 13:36:08.056  4136  4184 I bt_btu  : btu_task pending for preload complete event
,09-09 13:36:08.057  4136  4184 I bt_btu_task: Bluetooth chip preload is complete
09-09 13:36:08.057  4136  4184 I bt_btu  : btu_task received preload complete event
,09-09 13:36:08.065  4136  4184 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 13:36:08.065  4136  4184 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_A2D
,09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 13:36:08.066  4136  4184 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 13:36:08.152  1904  2660 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 13:36:08.197  4136  4184 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391bd9d
09-09 13:36:08.197  4136  4184 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391bd9d 
,09-09 13:36:08.208  4136  4177 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 13:36:08.211  4136  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 13:36:08.212  4136  4177 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 13:36:08.215  4136  4177 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:36:08.219  4136  4177 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:36:08.220  4136  4177 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:36:08.220  4136  4177 D bt_hci  : do_postload posting postload work item
09-09 13:36:08.221  4136  4181 I bt_hci  : event_postload
09-09 13:36:08.221  4136  4181 I bt_vendor: sco_config_cb
09-09 13:36:08.222  4136  4181 I bt_hci  : sco_config_callback postload finished.
09-09 13:36:08.225  4136  4177 D bt_bte_conf: Device ID record 1 : primary
09-09 13:36:08.225  4136  4177 D bt_bte_conf:   vendorId            = 000f
09-09 13:36:08.225  4136  4177 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 13:36:08.226  4136  4177 D bt_bte_conf:   product             = 1200
09-09 13:36:08.226  4136  4177 D bt_bte_conf:   version             = 1436
,09-09 13:36:08.226  4136  4177 D bt_bte_conf:   clientExecutableURL = 
09-09 13:36:08.226  4136  4177 D bt_bte_conf:   serviceDescription  = 
,09-09 13:36:08.226  4136  4177 D bt_bte_conf:   documentationURL    = 
,09-09 13:36:08.227  4136  4177 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 13:36:08.227  4136  4174 D bt_stack_manager: event_start_up_stack finished
09-09 13:36:08.228  4136  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 13:36:08.228  4136  4173 D BluetoothAdapterProperties: Setting state to 15
,09-09 13:36:08.228  4136  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 13:36:08.230  4136  4173 I BluetoothAdapterState: Entering BleOnState
,09-09 13:36:08.232  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.235  4136  4173 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 13:36:08.235  4136  4173 D BluetoothAdapterProperties: Setting state to 11
09-09 13:36:08.235  4136  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 13:36:08.235  4136  4181 I bt_vendor: low_power_mode_cb
09-09 13:36:08.239  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:08.243  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.248  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b470b5
09-09 13:36:08.250  4136  4136 D HeadsetService: Received start request. Starting profile...
09-09 13:36:08.254  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.257  4136  4173 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:36:08.257  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:08.259  4136  4136 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 13:36:08.260  4136  4136 D HeadsetStateMachine: make
09-09 13:36:08.261  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:08.267  4136  4136 D HeadsetStateMachine: max_hf_connections = 1
09-09 13:36:08.267  4136  4136 I bt_bluedroid: get_profile_interface handsfree
,09-09 13:36:08.267  4136  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 13:36:08.268  4136  4177 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-09 13:36:08.271  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b470b5
,09-09 13:36:08.271  4136  4136 D A2dpService: Received start request. Starting profile...
,09-09 13:36:08.272  4136  4136 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 13:36:08.272  4136  4136 I bt_bluedroid: get_profile_interface avrcp
,09-09 13:36:08.278  4136  4136 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 13:36:08.279  4136  4136 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:36:08.279  4136  4136 D A2dpStateMachine: make
,09-09 13:36:08.280  4136  4136 I bt_bluedroid: get_profile_interface a2dp
,09-09 13:36:08.281  4136  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 13:36:08.282  4136  4194 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:36:08.282  4136  4136 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 13:36:08.283  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b470b5
,09-09 13:36:08.284  4075  4075 D BluetoothInputDevice: Proxy object connected
09-09 13:36:08.285  4136  4136 D HidService: Received start request. Starting profile...
,09-09 13:36:08.285  4136  4136 I bt_bluedroid: get_profile_interface hidhost
09-09 13:36:08.285  4136  4177 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fd3e5
,09-09 13:36:08.285  4136  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 13:36:08.285  4136  4136 D HidService: setHidService(): set to: null
09-09 13:36:08.285  4075  4075 D HidProfile: Bluetooth service connected
09-09 13:36:08.286  4136  4136 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 13:36:08.287  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b470b5
09-09 13:36:08.287  4136  4136 D HealthService: Received start request. Starting profile...
09-09 13:36:08.287  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:36:08.291  4136  4136 I bt_bluedroid: get_profile_interface health
,09-09 13:36:08.291  4136  4136 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 13:36:08.292  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b470b5
,09-09 13:36:08.294  4075  4075 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 13:36:08.294  4136  4136 D PanService: Received start request. Starting profile...
09-09 13:36:08.294  4075  4075 D PanProfile: Bluetooth service connected
09-09 13:36:08.294  4136  4136 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 13:36:08.294  4136  4136 I bt_bluedroid: get_profile_interface pan
09-09 13:36:08.295  4136  4177 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:36:08.297  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b470b5
,09-09 13:36:08.298  4075  4075 D BluetoothMap: Proxy object connected
,09-09 13:36:08.298  4136  4136 D BluetoothMapService: Received start request. Starting profile...
09-09 13:36:08.298  4136  4136 D BluetoothMapService: start()
09-09 13:36:08.298  4075  4075 D MapProfile: Bluetooth service connected
09-09 13:36:08.298  4075  4075 D BluetoothMap: getConnectedDevices()
,09-09 13:36:08.299  4075  4075 D BluetoothMap: Bluetooth is Not enabled
09-09 13:36:08.300  4136  4136 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 13:36:08.300  4136  4136 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 13:36:08.301  4136  4136 D BluetoothMapAppObserver: createReceiver()
,09-09 13:36:08.301  4136  4136 D BluetoothMapAppObserver: initObservers()
09-09 13:36:08.302  4136  4136 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 13:36:08.308  4136  4136 V BluetoothAdapterState: isTurningOff()=false
09-09 13:36:08.308  4136  4136 V BluetoothAdapterState: isTurningOn()=true
09-09 13:36:08.308  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:36:08.309  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:36:08.310  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:36:08.310  4136  4136 V BluetoothAdapterState: isTurningOn()=true
09-09 13:36:08.310  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:08.310  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:36:08.310  4136  4192 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:36:08.311  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:36:08.311  4136  4136 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:36:08.311  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:08.311  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:36:08.312  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:36:08.312  4136  4136 V BluetoothAdapterState: isTurningOn()=true
09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isTurningOff()=false
09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isTurningOff()=false
09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isTurningOn()=true
09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:36:08.313  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:36:08.314  4136  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-09 13:36:08.314  4136  4173 D BluetoothAdapterProperties: ScanMode =  20
,09-09 13:36:08.314  4136  4173 D BluetoothAdapterProperties: State =  11
,09-09 13:36:08.314  4136  4173 D BluetoothAdapterProperties: Setting state to 12
,09-09 13:36:08.314  4136  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 13:36:08.315  4136  4173 I BluetoothAdapterState: Entering OnState
09-09 13:36:08.315   870   887 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:36:08.318  4075  4085 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:36:08.318  4136  4177 D BluetoothAdapterProperties: Scan Mode:21
,09-09 13:36:08.318   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:36:08.318  4136  4177 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:36:08.318   870   870 D BluetoothA2dp: Proxy object connected
09-09 13:36:08.318  4075  4086 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:36:08.319  1983  2179 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:36:08.319  1369  1395 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:36:08.322  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:36:08.322  1369  1369 D PanProfile: Bluetooth service connected
09-09 13:36:08.322  3827  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 13:36:08.322  1369  2116 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 13:36:08.324  1369  1369 D BluetoothInputDevice: Proxy object connected
09-09 13:36:08.324  1369  1369 D HidProfile: Bluetooth service connected
09-09 13:36:08.324  1369  1381 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:36:08.325  1369  1395 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:36:08.325  3827  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 13:36:08.326  1369  1369 D BluetoothA2dp: Proxy object connected
09-09 13:36:08.327   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:36:08.327  1369  2116 D BluetoothPbap: onBluetoothStateChange: up=true,
09-09 13:36:08.330  4075  4085 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:36:08.331  4136  4136 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 13:36:08.331  4136  4136 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 13:36:08.332  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.332  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
09-09 13:36:08.332  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.332  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.332  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.332  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.332  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.332  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:08.333  1369  1381 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:36:08.334  4136  4136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:08.335  1369  1369 D BluetoothMap: Proxy object connected
09-09 13:36:08.335  1369  1369 D MapProfile: Bluetooth service connected
09-09 13:36:08.335  1369  1369 D BluetoothMap: getConnectedDevices()
09-09 13:36:08.335   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:36:08.335  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:08.336  4075  4086 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:36:08.340   870   870 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 13:36:08.342  4136  4136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:08.343  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.343  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.343  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.343  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.343  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.343  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.343  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.343  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:08.344  4075  4075 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-09 13:36:08.344  4136  4136 D ObexServerSockets: Succeed to create listening sockets 
09-09 13:36:08.344  4136  4136 D ObexServerSockets0: startAccept()
09-09 13:36:08.344  4136  4136 D ObexServerSockets0: prepareForNewConnect()
09-09 13:36:08.346  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.348  4136  4200 D ObexServerSockets0: Accepting socket connection...
09-09 13:36:08.348  4136  4201 D ObexServerSockets0: Accepting socket connection...
09-09 13:36:08.347  4136  4136 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 13:36:08.348  4136  4136 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-09 13:36:08.349  4136  4136 D BluetoothMapService: onReceive
09-09 13:36:08.349  4136  4136 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:08.349  4136  4136 D BluetoothMapService: STATE_ON
09-09 13:36:08.350  4075  4075 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 13:36:08.352  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.352  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.352  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.352  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.352  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.352  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.352  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.352  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:08.354  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.356  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.358  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:08.359  4075  4075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:36:08.361  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.361  4075  4075 D BluetoothA2dp: Proxy object connected
,09-09 13:36:08.366  4075  4075 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:36:08.367  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:36:08.373  4075  4075 D BluetoothPbap: Proxy object connected
09-09 13:36:08.373  4136  4136 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 13:36:08.373  4075  4075 D PbapServerProfile: Bluetooth service connected
09-09 13:36:08.373  4136  4136 D ObexServerSockets0: prepareForNewConnect()
09-09 13:36:08.375  1369  1369 D BluetoothPbap: Proxy object connected
,09-09 13:36:08.375  1369  1369 D PbapServerProfile: Bluetooth service connected
,09-09 13:36:08.380  4136  4205 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:36:08.396  4136  4209 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:36:08.398  4136  4209 I BtOppRfcommListener: Accept thread started.
,09-09 13:36:08.403  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:08.403  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:08.403  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:08.403  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:08.403  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:36:08.404  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5cd359d removed from the list
09-09 13:36:08.404  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:08.404  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323da12 removed from the list
09-09 13:36:08.404  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:08.404  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:08.405  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:36:08.405  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2235be0 added. We now have 3 listener(s)
09-09 13:36:08.406  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:36:08.406  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:36:08.406  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:08.406  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:08.406  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4c8e99 added. We now have 3 listener(s)
09-09 13:36:08.406  3827  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:08.407  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:08.409  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:08.412  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:08.412  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.412  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.412  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.412  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.412  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.412  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.412  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:08.414  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:08.414  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:08.415   870  2237 D WifiService: setWifiEnabled: false pid=3827, uid=10000
,09-09 13:36:08.415   870  2237 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:36:08.416  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.419  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:08.419   870   870 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.419   870   870 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.419   870   870 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.420  1983  2007 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.420  1983  2001 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.420  1369  1393 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.420  1369  1369 D HeadsetProfile: Bluetooth service connected
,09-09 13:36:08.424  1369  1395 D BluetoothHeadset: Proxy object connected
,09-09 13:36:08.425  1369  1369 D HeadsetProfile: Bluetooth service connected
,09-09 13:36:08.425  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:36:08.427   870  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:36:08.428   870  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 13:36:08.428   870  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:36:08.428   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:08.428   870   887 D BluetoothHeadset: Proxy object connected
,09-09 13:36:08.433   870  1312 E native  : do suspend true
,09-09 13:36:08.436   870   887 D BluetoothHeadset: Proxy object connected
,09-09 13:36:08.439   370   868 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:36:08.439   870  1868 D DhcpClient: Clearing IP address
,09-09 13:36:08.441   370   868 D CommandListener: Setting iface cfg
,09-09 13:36:08.446  1511  4165 V NativeCrypto: Read error: ssl=0x9a97e000: I/O error during system call, Connection timed out
,09-09 13:36:08.448   870  4072 D DhcpClient: Receive thread stopped
,09-09 13:36:08.448  1511  4165 V NativeCrypto: SSL shutdown failed: ssl=0x9a97e000: I/O error during system call, Broken pipe
,09-09 13:36:08.450   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 13:36:08.450   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-09 13:36:08.452   870  1312 D WifiStateMachine: Start Disconnecting Watchdog 2
09-09 13:36:08.452   396   396 E Parcel  : Reading a NULL string not supported here.
09-09 13:36:08.453  4075  4085 D BluetoothHeadset: Proxy object connected
,09-09 13:36:08.454  4075  4075 D HeadsetProfile: Bluetooth service connected
09-09 13:36:08.456   870  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:08.457   870  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:36:08.457   870  1312 E native  : do suspend true
,09-09 13:36:08.492   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:36:08.517   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:36:08.517   370   868 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:36:08.518   870  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 13:36:08.519   870  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:08.521   870   887 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:36:08.537   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:36:08.549  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.549  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.549  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.549  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:08.549  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.549  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:08.549  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:08.549  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:08.551  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:08.553  1904  2337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:08.554  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.554  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.554  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.554  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:08.554  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.554  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:08.554  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:08.554  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:08.555   870  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:36:08.556  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:08.558  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 13:36:08.559  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.559  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.559  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.559  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:08.559  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.559  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:08.559  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:08.559  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:08.561  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:08.562  1727  1727 D SystemUpdateService: onCreate
09-09 13:36:08.562  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.564  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.565  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.566  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 13:36:08.571  1727  4218 I SystemUpdateService: active receiver: enabled
,09-09 13:36:08.574  1727  4218 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:36:08.574  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:36:08.578  1727  2422 I iu.UploadsManager: num queued entries: 0
,09-09 13:36:08.579  1727  2422 I iu.UploadsManager: num updated entries: 0
09-09 13:36:08.579  1727  2422 I iu.SyncManager: NEXT; no task
,09-09 13:36:08.581  1727  4218 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 13:36:08.581  1727  4218 I SystemUpdateService: now status is 0 (complete)
09-09 13:36:08.581  1727  4218 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 13:36:08.582  1727  4218 I SystemUpdateService: file has been verified
,09-09 13:36:08.587  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:36:08.588  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 13:36:08.590  3941  3941 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:08.591  1727  4218 I SystemUpdateService: OTA package size = 12249756
,09-09 13:36:08.594  3941  3941 D SprintDMHelper: simOperator: 
09-09 13:36:08.594  3941  3941 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:36:08.606  3906  4221 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 13:36:08.609  1727  4218 I SystemUpdateService: showing system update notification
,09-09 13:36:08.624   370   868 E Netd    : netlink response contains error (No such file or directory)
,09-09 13:36:08.638  1727  1727 D SystemUpdateService: onDestroy
,09-09 13:36:08.928  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.929   870  1704 D WifiService: setWifiEnabled: true pid=3827, uid=10000
09-09 13:36:08.929   870  1704 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:36:08.941   870  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:36:08.961  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.961  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.961  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.961  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.961  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.961  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:08.961  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:08.961  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:08.968  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:08.975   870  1312 D WifiConfigStore: loaded 0 passpoint configs
,09-09 13:36:08.977   870  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 13:36:08.977  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.977  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.977  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.977  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.977  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.977  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:08.977  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:08.977  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:08.978   870  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 13:36:08.979   870  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:36:08.980  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:08.980   870  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 13:36:08.980   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 13:36:08.980   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 13:36:08.984  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.984  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.984  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:08.984  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.984  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.984  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:08.984  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:08.984  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:08.988  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:36:08.997   370   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 13:36:08.998   870  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=21.75 rxSuccessRate=43.00 delta 1000 -> 1
09-09 13:36:08.998   370   868 D CommandListener: Setting iface cfg
,09-09 13:36:08.998   870  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 13:36:09.000   870  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-09 13:36:09.000   870  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:36:09.007   870  1312 E native  : do suspend true
,09-09 13:36:09.011   870  1311 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 13:36:09.012   870  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 13:36:09.015   870  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
,09-09 13:36:09.015   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:36:09.037   870  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 13:36:09.100   870  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 13:36:09.102  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 13:36:09.445  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:09.445  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:09.446  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:09.446  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:09.446  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:09.447  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2235be0 removed from the list
09-09 13:36:09.447  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:09.447  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4c8e99 removed from the list
09-09 13:36:09.448  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:09.448  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:09.464  3827  4229 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-09 13:36:09.464  3827  4229 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:36:09.533  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 13:36:09.569  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:36:09.569  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 13:36:09.577   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:36:09.592   870  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:36:09.593   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:09.593   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 13:36:09.620   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:36:09.632   370   868 D CommandListener: Setting iface cfg
,09-09 13:36:09.632   870  1312 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 13:36:09.640   870  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 13:36:09.661   870  4233 D DhcpClient: Receive thread started
,09-09 13:36:09.744   870  1312 E native  : do suspend false
,09-09 13:36:09.764   870  1868 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 13:36:09.778   870  4233 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
,09-09 13:36:09.780   870  1868 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
,09-09 13:36:09.783   870  1868 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 13:36:09.796   870  4233 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 13:36:09.797   870  1868 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 13:36:09.802   370   868 D CommandListener: Setting iface cfg
,09-09 13:36:09.814   870  1868 D DhcpClient: Scheduling renewal in 86399s
,09-09 13:36:09.814   870  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 13:36:09.822   870  1312 E native  : do suspend true
,09-09 13:36:09.838   870  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 13:36:09.839   870  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 13:36:09.840   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 13:36:09.842   870  1314 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 13:36:09.848   870  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:36:09.892   870  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 13:36:09.893   870  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 13:36:09.895   870  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 13:36:09.898   870  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 13:36:09.901   870  1314 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 13:36:09.916   870  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 13:36:09.920   870  1314 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-09 13:36:09.920   870  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-09 13:36:09.920   870  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:09.920   870  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 13:36:09.920   870  1314 D ConnectivityService:    accepting network in place of null
09-09 13:36:09.921   870  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:36:09.921   870  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:36:09.939   870  4232 D NetlinkSocketObserver: NeighborEvent{elapsedMs=158008, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:36:09.958   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:36:09.973  3827  4240 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-09 13:36:09.973  3827  4240 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:36:09.974  3827  4240 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:09.975  3827  4240 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:09.975  3827  4229 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 13:36:09.975  3827  4229 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:09.975  3827  4229 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:09.978  3827  4240 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:36:09.978  3827  4229 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:09.978  3827  4243 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 498, name: IncomingSocketThread/Sender)
09-09 13:36:09.979  3827  4229 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:36:09.981  3827  4244 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 500, name: OutgoingSocketThread/Sender)
,09-09 13:36:09.984  3827  4245 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 499, name: IncomingSocketThread/Receiver)
,09-09 13:36:09.985  3827  4245 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 499, thread name: IncomingSocketThread/Receiver)
,09-09 13:36:09.986  3827  4245 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:09.986  3827  4245 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 499, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:36:09.989  3827  4247 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 501, name: OutgoingSocketThread/Receiver)
,09-09 13:36:09.991  3827  4247 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 501, thread name: OutgoingSocketThread/Receiver)
,09-09 13:36:09.991  3827  4247 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 13:36:09.991  3827  4247 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 501, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:36:10.001   370   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:36:10.007   870  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 13:36:10.007   870  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:10.016   870  4231 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-09 13:36:10.016   870   887 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:36:10.017   870  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:10.024   870  1314 D ConnectivityService: handlePromptUnvalidated 101
,09-09 13:36:10.032  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:10.032  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:10.032  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:10.032  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:10.032  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:10.032  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:10.032  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:10.032  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:10.035  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:10.042  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:10.042  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:10.042  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:10.042  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:10.042  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:10.042  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:10.042  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:10.042  3827  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:10.043  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 13:36:10.043  3827  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:10.049  1727  1727 D SystemUpdateService: onCreate
,09-09 13:36:10.052  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 13:36:10.059  1727  4249 I SystemUpdateService: active receiver: enabled
,09-09 13:36:10.071  1727  4249 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:36:10.075  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:36:10.078  1727  2422 I iu.UploadsManager: num queued entries: 0
,09-09 13:36:10.083  1727  4249 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 13:36:10.083  1727  4249 I SystemUpdateService: now status is 0 (complete)
09-09 13:36:10.083  1727  4249 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 13:36:10.083  1727  4249 I SystemUpdateService: file has been verified
09-09 13:36:10.083  1727  4249 I SystemUpdateService: OTA package size = 12249756
,09-09 13:36:10.086  1727  2422 I iu.UploadsManager: num updated entries: 0
,09-09 13:36:10.089   870  4231 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:36:10 GMT], X-Android-Received-Millis=[1473420970089], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473420970065]}
,09-09 13:36:10.090   870  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 13:36:10.091   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-09 13:36:10.091   870  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:10.092   870  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 13:36:10.096  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:36:10.097  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 13:36:10.100  3941  3941 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:10.100  1727  2422 I iu.SyncManager: NEXT; no task
,09-09 13:36:10.105  1727  4252 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 13:36:10.105  1727  4252 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 13:36:10.107  1727  4252 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 13:36:10.108  3941  3941 D SprintDMHelper: simOperator: 
09-09 13:36:10.108  3941  3941 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:36:10.111  1727  4249 I SystemUpdateService: showing system update notification
,09-09 13:36:10.122  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:36:10.125  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:36:10.154  1727  1727 D SystemUpdateService: onDestroy
,09-09 13:36:10.181  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 13:36:10.181  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 13:36:10.181  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:36:10.181  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:36:10.221  1727  4252 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-09 13:36:10.232  3906  4255 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:36:10.483  3827  3875 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 13:36:10.484  3827  3875 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 13:36:10.491  3827  3875 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3886331 Bundle[{}]
09-09 13:36:10.494  3827  3875 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:36:10.494  3827  3875 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 13:36:10.496  3827  3875 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 13:36:10.498  3827  3875 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:36:10.498  3827  3875 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:36:10.499  3827  3875 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:36:10.507  3827  4263 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-09 13:36:10.508  3827  4263 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:36:10.518  3827  4265 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-09 13:36:10.518  3827  4263 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-09 13:36:10.518  3827  4265 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:10.518  3827  4265 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:10.518  3827  4263 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:10.519  3827  4263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:10.519  3827  4265 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:10.520  3827  4265 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:36:10.521  3827  4263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:10.523  3827  4267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 512, name: IncomingSocketThread/Sender)
,09-09 13:36:10.525  3827  4269 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 513, name: OutgoingSocketThread/Sender)
,09-09 13:36:10.527  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:36:10.528  3827  4263 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:36:10.528  3827  4268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 514, name: IncomingSocketThread/Receiver)
,09-09 13:36:10.530  3827  4270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 515, name: OutgoingSocketThread/Receiver)
09-09 13:36:10.530  3827  4270 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 515, thread name: OutgoingSocketThread/Receiver)
,09-09 13:36:10.530  3827  4270 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:36:10.530  3827  4270 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 515, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-09 13:36:10.530  3827  4268 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 514, thread name: IncomingSocketThread/Receiver)
09-09 13:36:10.531  3827  4268 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:10.531  3827  4268 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 514, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:36:10.696  1511  4271 I VacuumService: Vacuum at: now=1473420970696 tag=VacuumService
,09-09 13:36:10.696  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:36:10.758  1511  2997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 13:36:10.759  1511  2997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 13:36:10.759  1511  2997 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:36:10.759  1511  2997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:36:10.770  3514  3514 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 13:36:10.770  3514  3514 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 13:36:10.771  3514  3514 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-09 13:36:10.815  1511  4272 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-09 13:36:10.817  1511  4272 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:36:10.842  1511  4272 W Uploader:  no longer exists, so no auth token.
,09-09 13:36:11.009   870  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 13:36:11.027  3827  3875 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 524)
,09-09 13:36:11.029  3827  3875 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 13:36:11.030  3827  3875 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 525)
,09-09 13:36:11.035  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:36:11.035  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddc9d3f added. We now have 3 listener(s)
,09-09 13:36:11.039  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:36:11.039  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:11.039  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:11.039  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:36:11.039  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92560c added. We now have 3 listener(s)
09-09 13:36:11.039  3827  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:36:11.040  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:36:11.044  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:11.053  3827  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:11.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:11.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:36:11.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:11.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:11.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:11.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:11.053  3827  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:11.058  3827  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:11.059  3827  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:36:11.064  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:11.064  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:11.064  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:11.064  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:11.064  3827  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddc9d3f removed from the list
,09-09 13:36:11.064  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:11.064  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92560c removed from the list
09-09 13:36:11.065  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:11.066  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:11.066  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:11.068  3827  3875 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-09 13:36:11.068  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-09 13:36:11.068  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:11.068  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:36:11.068  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:36:11.068  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:11.071  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:36:11.072  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:36:11.072  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:36:11.072  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-09 13:36:11.073  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-09 13:36:11.073  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:11.073  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:11.074  3827  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 13:36:11.075  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:36:11.081  3827  4278 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:36:11.083  3827  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 13:36:11.083  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:36:11.086  3827  4278 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:36:11.090  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:36:11.091  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:36:11.091  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:11.095  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:36:11.095  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:36:11.095  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-09 13:36:11.095  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:36:11.095  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:36:11.096  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:36:11.096  3827  3875 D BluetoothAdapter: STATE_ON
,09-09 13:36:11.099  4136  4146 D BtGatt.GattService: registerClient() - UUID=dbfbb190-bd21-40e5-ae60-64e71ac88cf9
,09-09 13:36:11.100  4136  4177 D BtGatt.GattService: onClientRegistered() - UUID=dbfbb190-bd21-40e5-ae60-64e71ac88cf9, clientIf=5
09-09 13:36:11.101  3827  3966 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:36:11.103  4136  4179 D BtGatt.AdvertiseManager: message : 0
,09-09 13:36:11.105  4136  4179 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:36:11.115  4136  4177 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:36:11.122  4136  4177 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:36:11.122  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:36:11.122  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:36:11.124  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:36:11.125  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:36:11.126  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:36:11.126  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:36:11.126  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:36:11.126  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:36:11.126  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:36:11.129  3827  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:11.130  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:11.433   870  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 15 -> obsolete
,09-09 13:36:11.631  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:36:11.631  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:36:11.631  3827  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:12.053  1511  4272 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 13:36:12.053  1511  4272 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-09 13:36:12.053  1511  4272 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:36:12.054  1511  4272 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:36:12.093  1511  4272 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 13:36:12.093  1511  4272 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 13:36:12.093  1511  4272 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 13:36:12.457  1511  4272 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 13:36:12.458  1511  4272 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 13:36:12.458  1511  4272 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:36:12.458  1511  4272 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:36:12.507  1511  4272 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 13:36:12.507  1511  4272 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 13:36:12.507  1511  4272 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 13:36:14.169   870  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 15 -> obsolete
,09-09 13:36:14.628  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:36:14.628  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:36:14.629  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:36:14.629  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:36:14.629  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:36:14.631  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:36:14.631  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:36:14.632  3827  4278 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:36:14.632  3827  4278 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:36:14.632  3827  4278 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:36:14.633  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:36:14.634  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:36:14.634  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:14.634  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:14.634  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:36:14.635  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:36:14.637  3827  3875 D BluetoothAdapter: STATE_ON
09-09 13:36:14.638  3827  3875 D BluetoothLeScanner: could not find callback wrapper
09-09 13:36:14.638  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:36:14.638  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:36:14.641  4136  4179 D BtGatt.AdvertiseManager: message : 1
09-09 13:36:14.643  4136  4179 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:36:14.652  4136  4177 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:36:14.653  4136  4177 D BtGatt.GattService: Client app is not null!
,09-09 13:36:14.655  4136  4189 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:36:14.657  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:36:14.657  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:36:14.657  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:36:14.658  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:36:14.658  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:36:14.661  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:14.662  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:36:14.662  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:14.664  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:14.668  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:36:14.668  3827  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 13:36:14.668  3827  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:36:14.669  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:14.669  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:14.669  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:14.674  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:14.675  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:14.675  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:14.676  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddc9d3f not in the list
09-09 13:36:14.676  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:36:14.676  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92560c not in the list
,09-09 13:36:14.676  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:36:14.677  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:14.677  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:14.679  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:14.681  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:14.681  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 13:36:14.682  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:14.682  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:14.682  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:36:14.692  3827  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 13:36:14.692  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:36:14.698  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:36:14.698  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:36:14.699  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:14.703  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 13:36:14.704  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 13:36:14.705  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:36:14.706  3827  3875 D BluetoothAdapter: STATE_ON
,09-09 13:36:14.708  4136  4191 D BtGatt.GattService: registerClient() - UUID=e153cf5d-c6f9-4b0c-afdf-b2ea42666565
,09-09 13:36:14.709  4136  4177 D BtGatt.GattService: onClientRegistered() - UUID=e153cf5d-c6f9-4b0c-afdf-b2ea42666565, clientIf=5
09-09 13:36:14.709  3827  3839 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 13:36:14.710  4136  4147 D BtGatt.GattService: start scan with filters
,09-09 13:36:14.714  4136  4180 D BtGatt.ScanManager: handling starting scan
,09-09 13:36:14.714  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 13:36:14.715  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:36:14.715  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 13:36:14.715  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 13:36:14.716  4136  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b470b5
,09-09 13:36:14.719  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:36:14.719  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:36:14.719  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:36:14.721  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:36:14.725  4136  4177 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 13:36:14.725  4136  4177 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:36:14.726  4136  4180 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 13:36:14.733  4136  4177 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 13:36:14.733  4136  4177 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:14.734  4136  4180 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 13:36:14.734  4136  4180 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 13:36:14.750  4136  4177 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 13:36:14.750  4136  4177 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:14.758  4136  4177 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 13:36:14.758  4136  4177 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-09 13:36:15.220  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 13:36:15.221  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:36:15.221  3827  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:16.265  4136  4136 D BtGatt.ScanManager: awakened up at time 164335
,09-09 13:36:16.268  4136  4180 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:16.317  4136  4177 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=11
09-09 13:36:16.317  4136  4177 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:16.317  4136  4177 D BtGatt.GattService: current time is 164387036224
,09-09 13:36:16.318  4136  4177 D BtGatt.GattService: Batch record : [34, -92, -118, -46, -39, 98, 1, -128, -88, 26, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -112, -25, -60, -2, -84, -17, 0, 18, -17, 80, -11, -37, 82, 1, -128, -35, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 52, -118, -96, 0, -126, -22, -96, 83, -39, -56, 1, -128, -70, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -97, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 18, -17, 80, -11, -37, 82, 1, -128, -36, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 52, -118, -96, 0, -126, -22, -96, 83, -39, -56, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65, 0]
09-09 13:36:16.319  4136  4177 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -112, -25, -60, -2, -84, -17]
,09-09 13:36:16.320  4136  4177 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 52, -118, -96]
09-09 13:36:16.320  4136  4177 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65]
,09-09 13:36:16.321  4136  4177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 13:36:16.321  4136  4177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 13:36:16.321  4136  4177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 13:36:16.321  4136  4177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 13:36:16.322  4136  4177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:36:16.322  4136  4177 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 13:36:16.322  4136  4177 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 52, -118, -96]
,09-09 13:36:16.322  4136  4177 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65]
,09-09 13:36:16.326  3827  3827 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 5], added - the peer count is 1
09-09 13:36:16.327  3827  3827 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 6], added - the peer count is 2
09-09 13:36:16.327  3827  3827 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 90:E7:C4:FE:AC:EF 6], added - the peer count is 3
09-09 13:36:16.328  3827  3827 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 08:EC:A9:50:75:41 5] updated - the peer count is 3
09-09 13:36:16.328  3827  3827 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 6] updated - the peer count is 3
09-09 13:36:16.329  3827  3827 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 5], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,09-09 13:36:16.329  3827  3827 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 6], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
09-09 13:36:16.329  3827  3827 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 90:E7:C4:FE:AC:EF 6], Bluetooth address: 90:E7:C4:FE:AC:EF, device name: '', device address: ''
,09-09 13:36:17.724  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:17.724  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:17.725  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:17.725  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddc9d3f not in the list
09-09 13:36:17.725  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:17.726  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:36:17.726  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:17.726  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:36:17.727  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:36:17.727  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 13:36:17.730  3827  3875 D BluetoothAdapter: STATE_ON
,09-09 13:36:17.731  4136  4146 D BtGatt.GattService: stopScan() - queue size =1
,09-09 13:36:17.734  4136  4189 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:36:17.735  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:36:17.736  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:36:17.736  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 13:36:17.736  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 13:36:17.737  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 13:36:17.741  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,09-09 13:36:17.741  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:36:17.742  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:36:17.742  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:17.744  4136  4136 D BtGatt.ScanManager: awakened up at time 165814
09-09 13:36:17.745  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:17.746  3827  3875 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-09 13:36:17.749  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:17.750  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:17.750  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:17.751  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92560c not in the list
09-09 13:36:17.751  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:17.751  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:17.752  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:17.754  3827  3875 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-09 13:36:17.754  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-09 13:36:17.755  4136  4177 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 13:36:17.756  4136  4177 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:36:17.757  4136  4180 D BtGatt.ScanManager: stopping BLe Batch
,09-09 13:36:17.757  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:36:17.760  3827  3875 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:36:17.760  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:36:17.760  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:17.762  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:36:17.763  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:36:17.763  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:36:17.765  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:36:17.765  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:36:17.765  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:36:17.765  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:17.766  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:36:17.769  3827  4289 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:17.770  4136  4177 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 13:36:17.770  4136  4177 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:36:17.770  4136  4180 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:36:17.773  3827  4289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:36:17.777  3827  3875 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:36:17.778  3827  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:36:17.778  4136  4177 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 13:36:17.778  4136  4177 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:36:17.782  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:36:17.783  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:36:17.783  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:17.785  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:36:17.785  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:36:17.785  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
09-09 13:36:17.786  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:36:17.786  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:36:17.786  3827  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:36:17.787  3827  3875 D BluetoothAdapter: STATE_ON
,09-09 13:36:17.789  4136  4191 D BtGatt.GattService: registerClient() - UUID=aa8462ff-dead-4854-8e29-6f14750469a4
09-09 13:36:17.790  4136  4177 D BtGatt.GattService: onClientRegistered() - UUID=aa8462ff-dead-4854-8e29-6f14750469a4, clientIf=5
09-09 13:36:17.790  3827  3966 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:36:17.791  4136  4179 D BtGatt.AdvertiseManager: message : 0
,09-09 13:36:17.794  4136  4179 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:36:17.806  4136  4177 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:36:17.815  4136  4177 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:36:17.816  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:36:17.816  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:36:17.817  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:36:17.819  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:36:17.820  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:36:17.820  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:36:17.820  3827  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:36:17.821  3827  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:36:17.821  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:36:17.824  3827  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:17.824  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:36:17.928   870  1314 D ConnectivityService: handlePromptUnvalidated 102
,09-09 13:36:18.325  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:36:18.325  3827  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:36:18.326  3827  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:36:21.323  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:21.324  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:36:21.324  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:36:21.325  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:36:21.326  3827  4289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:36:21.326  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:36:21.326  3827  4289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:36:21.326  3827  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 13:36:21.327  3827  4289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:36:21.328  3827  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:36:21.328  3827  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:36:21.330  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddc9d3f not in the list
,09-09 13:36:21.330  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:21.331  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:36:21.331  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:36:21.331  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:36:21.332  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:36:21.334  3827  3875 D BluetoothAdapter: STATE_ON
09-09 13:36:21.335  3827  3875 D BluetoothLeScanner: could not find callback wrapper
,09-09 13:36:21.335  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:36:21.336  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:36:21.341  4136  4179 D BtGatt.AdvertiseManager: message : 1
09-09 13:36:21.342  4136  4179 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:36:21.348  4136  4177 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:36:21.348  4136  4177 D BtGatt.GattService: Client app is not null!
,09-09 13:36:21.350  4136  4147 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:36:21.351  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:36:21.352  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:36:21.352  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:36:21.352  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:36:21.352  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 13:36:21.355  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:36:21.355  3827  3875 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:36:21.355  3827  3875 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:36:21.357  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:21.359  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92560c not in the list
,09-09 13:36:21.359  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:21.359  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:21.360  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:21.359  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:36:21.360  3827  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:36:21.360  3827  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:36:21.361  3827  3875 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:21.361  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:21.361  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:21.361  3827  3875 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddc9d3f not in the list
09-09 13:36:21.362  3827  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:21.362  3827  3875 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c92560c not in the list
09-09 13:36:21.362  3827  3875 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:36:21.362  3827  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:21.362  3827  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:21.365  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-09 13:36:21.366  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:36:21.366  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:21.367  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:36:21.367  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:36:21.368  3827  3875 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:36:21.387  3827  4291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 545, name: My test thread name)
,09-09 13:36:21.862  3827  3827 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:36:21.950   870  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,09-09 13:36:23.385  3827  3875 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 545
,09-09 13:36:23.385  3827  3875 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 545, name: My test thread name)
,09-09 13:36:23.392  3827  4292 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 546, name: My test thread name)
,09-09 13:36:23.392  3827  4292 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 546, thread name: My test thread name)
09-09 13:36:23.393  3827  4292 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 546, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 13:36:23.397  3827  3875 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:23.406  3827  4293 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 550, name: My test thread name)
,09-09 13:36:23.407  3827  4293 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 550, thread name: My test thread name): Test exception.
09-09 13:36:23.407  3827  4293 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 550, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:36:23.415  3827  3875 I jxcore-log: Total number of executed tests:  82
09-09 13:36:23.415  3827  3875 I jxcore-log: 
,09-09 13:36:23.416  3827  3875 I jxcore-log: Number of passed tests:  82
09-09 13:36:23.416  3827  3875 I jxcore-log: 
09-09 13:36:23.416  3827  3875 I jxcore-log: Number of failed tests:  0
09-09 13:36:23.416  3827  3875 I jxcore-log: 
,09-09 13:36:23.419  3827  3875 I jxcore-log: Number of ignored tests:  0
09-09 13:36:23.419  3827  3875 I jxcore-log: 
,09-09 13:36:23.420  3827  3875 I jxcore-log: Total duration:  30428
09-09 13:36:23.420  3827  3875 I jxcore-log: 
,09-09 13:36:23.425  3827  3875 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 13:36:23.425  3827  3875 I jxcore-log: 
,09-09 13:36:23.428  3827  3875 I jxcore-log: My device name is: motorola-Nexus 6
09-09 13:36:23.428  3827  3875 I jxcore-log: 
09-09 13:36:23.431  3827  3875 I jxcore-log: WARN testUtils: myNameCallback not set!
09-09 13:36:23.431  3827  3875 I jxcore-log: 
09-09 13:36:23.434  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.434  3827  3875 I jxcore-log: 
09-09 13:36:23.436  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.436  3827  3875 I jxcore-log: 
,09-09 13:36:23.437  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.437  3827  3875 I jxcore-log: 
09-09 13:36:23.440  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:23.440  3827  3875 I jxcore-log: 
09-09 13:36:23.442  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:23.442  3827  3875 I jxcore-log: 
,09-09 13:36:23.444  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.444  3827  3875 I jxcore-log: 
09-09 13:36:23.445  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:23.445  3827  3875 I jxcore-log: 
,09-09 13:36:23.446  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.446  3827  3875 I jxcore-log: 
09-09 13:36:23.447  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:23.447  3827  3875 I jxcore-log: 
09-09 13:36:23.447  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.447  3827  3875 I jxcore-log: 
09-09 13:36:23.448  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.448  3827  3875 I jxcore-log: 
,09-09 13:36:23.449  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.449  3827  3875 I jxcore-log: 
09-09 13:36:23.450  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.450  3827  3875 I jxcore-log: 
,09-09 13:36:23.451  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:23.451  3827  3875 I jxcore-log: 
09-09 13:36:23.452  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:23.452  3827  3875 I jxcore-log: 
,09-09 13:36:23.453  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:23.453  3827  3875 I jxcore-log: 
09-09 13:36:23.453  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:36:23.453  3827  3875 I jxcore-log: 
,09-09 13:36:23.454  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.454  3827  3875 I jxcore-log: 
,09-09 13:36:23.455  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.455  3827  3875 I jxcore-log: 
,09-09 13:36:23.456  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.456  3827  3875 I jxcore-log: 
,09-09 13:36:23.457  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.457  3827  3875 I jxcore-log: 
09-09 13:36:23.458  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.458  3827  3875 I jxcore-log: 
09-09 13:36:23.459  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.459  3827  3875 I jxcore-log: 
,09-09 13:36:23.460  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.460  3827  3875 I jxcore-log: 
,09-09 13:36:23.461  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.461  3827  3875 I jxcore-log: 
09-09 13:36:23.462  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.462  3827  3875 I jxcore-log: 
09-09 13:36:23.463  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.463  3827  3875 I jxcore-log: 
09-09 13:36:23.464  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.464  3827  3875 I jxcore-log: 
,09-09 13:36:23.465  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.465  3827  3875 I jxcore-log: 
09-09 13:36:23.466  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.466  3827  3875 I jxcore-log: 
,09-09 13:36:23.467  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.467  3827  3875 I jxcore-log: 
,09-09 13:36:23.468  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.468  3827  3875 I jxcore-log: 
,09-09 13:36:23.469  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:23.469  3827  3875 I jxcore-log: 
,09-09 13:36:23.469  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:23.469  3827  3875 I jxcore-log: 
09-09 13:36:23.470  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:23.470  3827  3875 I jxcore-log: 
09-09 13:36:23.471  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.471  3827  3875 I jxcore-log: 
09-09 13:36:23.471  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.471  3827  3875 I jxcore-log: 
09-09 13:36:23.472  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:23.472  3827  3875 I jxcore-log: 
,09-09 13:36:23.472  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.472  3827  3875 I jxcore-log: 
09-09 13:36:23.473  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.473  3827  3875 I jxcore-log: 
09-09 13:36:23.473  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:23.473  3827  3875 I jxcore-log: 
09-09 13:36:23.474  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:23.474  3827  3875 I jxcore-log: 
,09-09 13:36:23.474  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 13:36:23.474  3827  3875 I jxcore-log: 
,09-09 13:36:23.475  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 13:36:23.475  3827  3875 I jxcore-log: 
,09-09 13:36:23.476  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 13:36:23.476  3827  3875 I jxcore-log: 
,09-09 13:36:23.477  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 13:36:23.477  3827  3875 I jxcore-log: 
09-09 13:36:23.477  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:36:23.477  3827  3875 I jxcore-log: 
,09-09 13:36:23.481  3827  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:36:23.481  3827  3875 I jxcore-log: 
,09-09 13:36:23.573  3827  4291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 545, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-09 13:36:24.059  4294  4294 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-09 13:36:24.064  4294  4294 D AndroidRuntime: CheckJNI is OFF
,09-09 13:36:24.107  4294  4294 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-09 13:36:24.153  4294  4294 I Radio-JNI: register_android_hardware_Radio DONE
,09-09 13:36:24.175  4294  4294 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 13:36:24.193   870   883 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 13:36:24.194   870   883 I ActivityManager: Killing 3827:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-09 13:36:24.269   870  1703 D GraphicsStats: Buffer count: 2
,09-09 13:36:24.269   870  1313 D WifiService: Client connection lost with reason: 4
,09-09 13:36:24.269   870  1937 I WindowState: WIN DEATH: Window{d81e89a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:36:24.323   870   894 W PackageSettings: Skipping PackageSetting{c0f7d0e com.example.hello/10273} due to missing metadata
,09-09 13:36:24.357   870   883 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-09 13:36:24.358   870   883 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-09 13:36:24.359   870   894 I art     : Starting a blocking GC Explicit
,09-09 13:36:24.363   870   883 E ActivityManager: Failure starting process com.test.thalitest
09-09 13:36:24.363   870   883 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 13:36:24.363   870   883 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:24.363   870   883 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:24.363   870   883 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:36:24.363   870   883 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-09 13:36:24.366   870   883 I ActivityManager:   Force finishing activity ActivityRecord{168eb73 u0 com.test.thalitest/.MainActivity t4}
,09-09 13:36:24.389   870  1704 W ActivityManager: Spurious death for ProcessRecord{e3a47ef 0:com.test.thalitest/u0a0}, curProc for 3827: null
,09-09 13:36:24.404   870   894 I art     : Explicit concurrent mark sweep GC freed 32439(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 853us total 43.726ms
,09-09 13:36:24.433   870   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-09 13:36:24.439  4294  4294 I art     : System.exit called, status: 0
09-09 13:36:24.439  4294  4294 I AndroidRuntime: VM exiting with result code 0.
,09-09 13:36:24.497   870   894 I ActivityManager: Start proc 4304:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-09 13:36:24.498   870   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-09 13:36:24.535   870   883 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-09 13:36:24.539  4136  4136 D BluetoothMapAppObserver: onReceive
,09-09 13:36:24.539  4136  4136 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 13:36:24.541   870  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 13:36:24.542  1904  2297 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 13:36:24.551  3664  3664 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 13:36:24.552  1890  1890 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-09 13:36:24.558  1890  4318 I Keyboard.Facilitator.DecoderInitializer: run()
,09-09 13:36:24.560  1890  4318 I Decoder : createOrResetDecoder
,09-09 13:36:24.580   870  1400 I ActivityManager: Start proc 4320:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-09 13:36:24.581  1983  1983 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-09 13:36:24.595  1511  1511 I ConfigService: onCreate
,09-09 13:36:24.617  1511  4330 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 13:36:24.617  1511  4330 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 13:36:24.617  1511  4330 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-09 13:36:24.619  1511  4330 W SQLiteOpenHelper: Opened config.db in read-only mode
09-09 13:36:24.620   870  2292 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3827 uid 10000
09-09 13:36:24.621  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-09 13:36:24.631   870   870 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 13:36:24.634  4320  4320 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-09 13:36:24.654  1990  2088 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-09 13:36:24.655   870   882 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-09 13:36:24.656   870   882 E PackageManager: Failed to write settings, restoring backup
09-09 13:36:24.656   870   882 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 13:36:24.656   870   882 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 13:36:24.656   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 13:36:24.656   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 13:36:24.656   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 13:36:24.656   870   882 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:24.656   870   882 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:24.656   870   882 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 13:36:24.661   870   883 E DropBoxManagerService: Can't write: system_server_wtf
09-09 13:36:24.661   870   883 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 13:36:24.661   870   883 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:36:24.661   870   883 E DropBoxManagerService: 	... 13 more
,09-09 13:36:24.662  1890  4318 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-09 13:36:24.667   870  2292 I ActivityManager: Start proc 4333:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-09 13:36:24.667  1990  2088 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 13:36:24.667  1990  2088 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1990
09-09 13:36:24.667  1990  2088 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:24.667  1990  2088 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:36:24.669   870  2237 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 13:36:24.671   870  4339 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:36:24.671   870  4339 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:36:24.671   870  4339 E DropBoxManagerService: 	... 5 more
09-09 13:36:24.675  1990  2088 I Process : Sending signal. PID: 1990 SIG: 9
,09-09 13:36:24.708  1890  4318 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-09 13:36:24.710  1890  4318 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 13:36:24.710  1890  4318 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-09 13:36:24.712  1890  4318 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-09 13:36:24.712  1890  4318 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 13:36:24.713  1890  4318 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 13:36:24.713  1890  4318 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-09 13:36:24.713  1890  4318 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-09 13:36:24.714  1890  4318 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 13:36:24.714  1890  4318 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 13:36:24.714  1890  4318 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 13:36:24.714  1890  4318 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 13:36:24.714  1890  4318 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-09 13:36:24.738  4320  4320 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-09 13:36:24.745   278   278 E lowmemorykiller: Error writing /proc/1990/oom_score_adj; errno=22
,09-09 13:36:24.751   870  1704 D GraphicsStats: Buffer count: 1
,09-09 13:36:24.751   870  2291 I WindowState: WIN DEATH: Window{536f76f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-09 13:36:24.760   870  2292 I ActivityManager: Start proc 4354:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-09 13:36:24.761   278   278 E lowmemorykiller: Error opening /proc/1990/oom_score_adj; errno=2
,09-09 13:36:24.761   870  2051 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1990) has died
09-09 13:36:24.762   870  2051 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 13:36:24.763   870  2051 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 13:36:24.785   870   883 I ActivityManager: Start proc 4366:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 13:36:24.813  4354  4354 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-09 13:36:24.817  4320  4353 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-09 13:36:24.829  4366  4366 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:24.829  4366  4366 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:36:24.829  4366  4366 D AndroidRuntime: Shutting down VM
,09-09 13:36:24.838  4366  4366 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:36:24.838  4366  4366 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4366
09-09 13:36:24.838  4366  4366 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:36:24.838  4366  4366 E AndroidRuntime: 	... 10 more
09-09 13:36:24.839   870   880 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 13:36:24.840  4366  4366 I Process : Sending signal. PID: 4366 SIG: 9
09-09 13:36:24.840   870  4379 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:36:24.840   870  4379 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:36:24.840   870  4379 E DropBoxManagerService: 	... 5 more
09-09 13:36:24.856  1727  4378 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-09 13:36:24.856  1727  4378 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-09 13:36:24.861  1727  4378 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-09 13:36:24.862  1727  4378 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-09 13:36:24.868  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-09 13:36:24.869  1511  1511 D AndroidRuntime: Shutting down VM
09-09 13:36:24.870  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:36:24.870  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
09-09 13:36:24.870  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 13:36:24.870  1511  1511 E AndroidRuntime: 	... 8 more
09-09 13:36:24.872   870  4382 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:36:24.872   870  4382 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	at libcore.,io.Posix.open(Native Method)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:36:24.872   870  4382 E DropBoxManagerService: 	... 5 more
09-09 13:36:24.873  1511  1511 I Process : Sending signal. PID: 1511 SIG: 9
,09-09 13:36:24.894   870  2290 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4366) has died
,09-09 13:36:24.896   870  2290 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 13:36:24.912  4320  4349 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:24.912  4320  4349 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:36:24.913  4320  4349 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 13:36:24.919   870   883 I ActivityManager: Start proc 4384:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 13:36:24.921   870  2000 I ActivityManager: Killing 3450:com.android.providers.calendar/u0a3 (adj 15): empty #17

```
