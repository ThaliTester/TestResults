#### Test 84618637daa9683_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 12:08:50.904   872  1876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=114077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 12:08:51.598  3853  3853 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 12:08:51.603  3853  3853 D AndroidRuntime: CheckJNI is OFF
09-12 12:08:51.648  3853  3853 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 12:08:51.701  3853  3853 I Radio-JNI: register_android_hardware_Radio DONE
09-12 12:08:51.723  3853  3853 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 12:08:51.728   872  2167 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 12:08:51.773  2070  2083 W SearchService: Abort, client detached.
09-12 12:08:51.777  3853  3853 D AndroidRuntime: Shutting down VM
09-12 12:08:51.780  2070  2343 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@943ceae
09-12 12:08:51.780  2070  2070 I HotwordDetector: Closing mic
09-12 12:08:51.781  2070  2352 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 12:08:51.799   872  1997 I ActivityManager: Start proc 3862:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 12:08:51.835   377  2354 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 12:08:51.836   377  2354 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 12:08:51.844   377  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 12:08:51.847  2070  2349 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 12:08:51.847  2070  2351 I MicroRecognitionRnrImpl: Detection finished
09-12 12:08:51.881  3862  3862 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 12:08:51.905  3862  3862 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 12:08:51.911  3862  3862 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5082-5084)
09-12 12:08:51.911  3862  3862 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 12:08:51.923  3862  3862 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {da7db14}
09-12 12:08:51.923  3862  3862 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 12:08:51.924  3862  3862 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 12:08:51.929  3862  3862 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 12:08:51.930  3862  3862 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 12:08:51.940  3862  3862 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-12 12:08:51.949  3862  3862 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 12:08:51.949  3862  3862 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 12:08:51.950  3862  3862 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 12:08:51.950  3862  3862 I Adreno  : Build Date                       : 10/20/15
09-12 12:08:51.950  3862  3862 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 12:08:51.950  3862  3862 I Adreno  : Local Branch                     : M14
09-12 12:08:51.950  3862  3862 I Adreno  : Remote Branch                    : 
09-12 12:08:51.950  3862  3862 I Adreno  : Remote Branch                    : 
09-12 12:08:51.950  3862  3862 I Adreno  : Reconstruct Branch               : 
,09-12 12:08:51.995   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6362386:true
09-12 12:08:52.021  3862  3862 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-12 12:08:52.031  3862  3862 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-12 12:08:52.067  3862  3900 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-12 12:08:52.072  3862  3887 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-12 12:08:52.096  3862  3900 I OpenGLRenderer: Initialized EGL, version 1.4
09-12 12:08:52.160   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +384ms
09-12 12:08:52.165  1897  1897 I Keyboard.Facilitator: onFinishInput()
09-12 12:08:52.255  3862  3862 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3862
09-12 12:08:52.363  3862  3862 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-12 12:08:52.547  3862  3903 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1697248976
09-12 12:08:52.557  3862  3903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 12:08:52.557  3862  3903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 12:08:52.557  3862  3903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 12:08:52.557  3862  3903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 12:08:52.557  3862  3903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-12 12:08:52.558  3862  3903 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3e93b added. We now have 1 listener(s)
09-12 12:08:52.561  3862  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-12 12:08:52.563  3862  3903 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 12:08:52.570  3862  3903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:08:52.571  3862  3903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 12:08:52.580   872  1687 I ActivityManager: Killing 3274:com.google.android.gm/u0a78 (adj 15): empty #17
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 12:08:52.580  3862  3903 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe6296 added. We now have 1 listener(s)
09-12 12:08:52.581  3862  3903 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:08:52.586   872  1308 D WifiService: New client listening to asynchronous messages
09-12 12:08:52.589  3862  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 12:08:52.589  3862  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 12:08:52.589  3862  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 12:08:52.589  3862  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 12:08:52.589  3862  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-12 12:08:52.633   872  1687 I ActivityManager: Killing 3174:com.google.android.apps.maps/u0a65 (adj 15): empty #18
09-12 12:08:52.675  3862  3903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:08:52.675  3862  3903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-12 12:08:52.706  3862  3903 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-12 12:08:52.706  3862  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:08:52.706  3862  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:08:52.706  3862  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:08:52.706  3862  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:08:52.706  3862  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:08:52.706  3862  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:08:52.706  3862  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:08:52.706  3862  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:08:52.706  3862  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 12:08:52.706  3862  3903 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:08:52.707  3862  3903 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 12:08:52.747  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:08:52.751  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:08:52.754  3862  3862 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 12:08:53.735  3862  3913 W jxcore-log: Initializing JXcore engine
,09-12 12:08:53.735  3862  3913 W jxcore-log: JXcore engine is ready
,09-12 12:08:53.825  3913  3913 W Thread-331: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8951 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 12:08:53.825  3913  3913 W Thread-331: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9554]" dev="sockfs" ino=9554 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-12 12:08:53.825  3913  3913 W Thread-331: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-12 12:08:53.825  3913  3913 W Thread-331: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25382]" dev="sockfs" ino=25382 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-12 12:08:53.878  3862  3913 W jxcore-log: Starting JXcore engine
,09-12 12:08:54.020  3862  3913 W jxcore-log: Platform android
09-12 12:08:54.020  3862  3913 W jxcore-log: 
,09-12 12:08:54.020  3862  3913 W jxcore-log: Process ARCH arm
09-12 12:08:54.020  3862  3913 W jxcore-log: 
,09-12 12:08:54.272  3862  3913 I jxcore-log: JXcore Cordova bridge is ready!
09-12 12:08:54.272  3862  3913 I jxcore-log: 
09-12 12:08:54.272  3862  3913 W jxcore-log: JXcore engine is started
,09-12 12:08:54.278  3862  3903 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 12:08:54.282  3862  3862 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 12:08:59.742   872  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 12:09:02.041  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:02.046  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:02.053  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:02.078  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 12:09:02.078  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:09:02.078  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:09:02.078  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:02.107  3575  3575 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:09:02.107  3575  3575 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 12:09:02.107  3575  3575 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-12 12:09:06.529  3639  3925 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:09:06.583  3639  3926 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:09:06.663  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:09:06.663  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 12:09:06.664  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:09:06.664  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:06.802  1502  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 12:09:06.802  1502  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:09:06.802  1502  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:09:06.802  1502  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:06.851  3639  3926 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:09:06.852  3639  3925 E BooksSync: Soft error
09-12 12:09:06.852  3639  3925 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:09:06.852  3639  3925 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:09:06.852  3639  3925 E BooksSync: Sync error
09-12 12:09:06.852  3639  3925 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:09:06.852  3639  3925 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:09:06.852  3639  3925 I BooksSync: Finished books sync
,09-12 12:09:06.858   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128060, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:09:08.515  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 12:09:08.515  3862  3913 I jxcore-log: 
,09-12 12:09:08.517  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 12:09:08.517  3862  3913 I jxcore-log: 
,09-12 12:09:08.529  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:09:08.529  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:08.529  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:08.529  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:08.529  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:09:08.529  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:08.529  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:08.529  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:09:08.534  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:09:08.537  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 12:09:08.537  3862  3913 I jxcore-log: 
,09-12 12:09:08.538  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 12:09:08.538  3862  3913 I jxcore-log: 
,09-12 12:09:08.886  3862  3913 I jxcore-log: Running unit tests
09-12 12:09:08.886  3862  3913 I jxcore-log: 
,09-12 12:09:08.887  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 12:09:08.887  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a468d8 added. We now have 2 listener(s)
09-12 12:09:08.888  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 12:09:08.888  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:09:08.888  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 12:09:08.888  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:09:08.889  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@802a431 added. We now have 2 listener(s)
09-12 12:09:08.889  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:09:08.889  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:09:08.893  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:09:08.904  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-12 12:09:08.904  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:08.904  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:08.904  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:08.904  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:09:08.904  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:08.904  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:08.904  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:09:08.910  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:08.910  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:09:08.912  3862  3913 D executeNativeTests: Running unit tests
,09-12 12:09:08.913  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:08.914  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:09.004  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:09:09.004  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 added. We now have 3 listener(s)
,09-12 12:09:09.005  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 12:09:09.005  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:09:09.006  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 12:09:09.006  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:09:09.006  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 added. We now have 3 listener(s)
,09-12 12:09:09.006  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:09:09.006  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:09:09.016  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:09:09.028  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:09:09.028  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:09.028  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:09.028  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:09.028  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:09:09.028  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:09.028  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:09.028  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:09:09.034  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:09:09.035  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:09:09.038  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 12:09:09.038  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:09:09.039  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:09:09.039  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:09:09.040  3862  3913 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 12:09:09.040  3862  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 12:09:09.040  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 12:09:09.040  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 12:09:09.040  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 12:09:09.040  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 12:09:09.041  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:09.041  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:09.041  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:09.042  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:09.042  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:09.042  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:09.042  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:09:09.042  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 12:09:09.042  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 removed from the list
09-12 12:09:09.042  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:09.042  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 removed from the list
,09-12 12:09:09.047  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:09.047  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:09:09.047  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:09.048  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:09.048  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:09.054  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:09:09.056  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:09.057  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:09.057  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
,09-12 12:09:09.061  3862  3913 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 12:09:09.062  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:09:09.062  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:09.062  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:09.062  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:09.062  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:09.062  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:09.062  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:09.063  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:09.063  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:09.063  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:09.063  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:09.063  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:09.063  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:09.063  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:09.065  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:09:09.065  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:09.065  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:09.065  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-12 12:09:09.070  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 12:09:09.071  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 12:09:09.071  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:09:09.071  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:09.071  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:09.071  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:09:09.072  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:09.072  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:09.072  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
,09-12 12:09:09.072  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:09.072  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:09.072  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:09:09.072  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:09.072  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:09.072  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:09.072  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:09.073  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:09.073  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:09.073  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:09.073  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:09.074  3862  3913 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 12:09:09.075  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:09:09.082  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:09:09.082  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:09.082  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:09.082  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:09.082  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:09:09.082  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:09.082  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:09.082  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:09:09.087  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:09:09.088  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:09:09.088  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:09:09.089  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 12:09:09.089  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 12:09:09.089  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:09:09.090  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:09.092  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 12:09:09.100  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:09.110  3862  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 12:09:09.110  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 12:09:09.131  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 12:09:09.133  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 12:09:09.133  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 12:09:09.136  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-12 12:09:09.141  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-12 12:09:09.141  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 12:09:09.141  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 12:09:09.142  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 12:09:09.144  3862  3913 D BluetoothAdapter: STATE_ON
,09-12 12:09:09.150  2712  2907 D BtGatt.GattService: registerClient() - UUID=1596bb74-3770-4c9c-83fb-e58c29f1201c
,09-12 12:09:09.151  2712  2765 D BtGatt.GattService: onClientRegistered() - UUID=1596bb74-3770-4c9c-83fb-e58c29f1201c, clientIf=5
09-12 12:09:09.152  3862  3902 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 12:09:09.153  2712  2726 D BtGatt.GattService: start scan with filters
,09-12 12:09:09.158  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 12:09:09.158  2712  2770 D BtGatt.ScanManager: handling starting scan
09-12 12:09:09.158  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 12:09:09.158  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 12:09:09.159  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 12:09:09.161  2712  2770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:09:09.162  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:09:09.163  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 12:09:09.163  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 12:09:09.165  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 12:09:09.168  3862  3913 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 12:09:09.170  2712  2765 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 12:09:09.171  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:09.171  2712  2770 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 12:09:09.181  2712  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 12:09:09.181  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:09:09.181  2712  2770 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 12:09:09.181  2712  2770 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 12:09:09.207  2712  2765 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 12:09:09.208  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:09.222  2712  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 12:09:09.223  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:09.666  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 12:09:09.667  3862  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:09:09.667  3862  3862 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:09:10.727  2712  2712 D BtGatt.ScanManager: awakened up at time 133900
,09-12 12:09:10.733  2712  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:09:10.775  2712  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-12 12:09:10.775  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:09:10.776  2712  2765 D BtGatt.GattService: current time is 133950102308
09-12 12:09:10.777  2712  2765 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -74, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -98, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 12:09:10.781  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-12 12:09:10.783  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 12:09:10.784  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 12:09:10.785  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 12:09:10.785  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 12:09:11.471   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 12:09:12.278  2712  2712 D BtGatt.ScanManager: awakened up at time 135452
,09-12 12:09:12.282  2712  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:09:12.305  2712  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-12 12:09:12.306  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:09:12.306  2712  2765 D BtGatt.GattService: current time is 135480410472
,09-12 12:09:12.307  2712  2765 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -93, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 12:09:12.309  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 12:09:13.810  2712  2712 D BtGatt.ScanManager: awakened up at time 136984
,09-12 12:09:13.813  2712  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:09:13.824  2712  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 12:09:13.824  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:14.181  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:09:14.181  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:09:14.182  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 12:09:14.182  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:14.182  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 12:09:14.183  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:09:14.183  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 12:09:14.183  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 12:09:14.184  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:09:14.186  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 12:09:14.187  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 12:09:14.190  3862  3913 D BluetoothAdapter: STATE_ON
,09-12 12:09:14.192  2712  2907 D BtGatt.GattService: stopScan() - queue size =1
,09-12 12:09:14.195  2712  2726 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 12:09:14.196  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 12:09:14.197  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 12:09:14.197  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 12:09:14.198  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 12:09:14.198  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 12:09:14.203  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:09:14.204  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 12:09:14.205  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 12:09:14.206  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 12:09:14.208  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:09:14.210  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:09:14.211  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:09:14.211  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:09:14.211  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:09:14.211  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:14.211  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:09:14.211  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:14.211  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:14.212  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:14.212  2712  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 12:09:14.212  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:14.212  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:14.212  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:09:14.213  2712  2770 D BtGatt.ScanManager: stopping BLe Batch
,09-12 12:09:14.222  2712  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 12:09:14.222  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:14.222  2712  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:09:14.231  2712  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 12:09:14.231  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:14.503   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 12:09:14.712  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:09:14.877   872  1876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:09:17.533   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 12:09:19.214  3862  3913 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 12:09:19.221  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:09:19.236  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:09:19.236  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:19.236  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:19.236  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:19.236  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:09:19.236  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:19.236  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:19.236  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:09:19.242  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:09:19.243  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:09:19.244  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 12:09:19.244  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 12:09:19.245  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 12:09:19.245  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:09:19.246  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 12:09:19.252  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:19.257  3862  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 12:09:19.257  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 12:09:19.260  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:19.270  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 12:09:19.272  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 12:09:19.272  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 12:09:19.279  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 12:09:19.279  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 12:09:19.279  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 12:09:19.281  3862  3913 D BluetoothAdapter: STATE_ON
,09-12 12:09:19.286  2712  2898 D BtGatt.GattService: registerClient() - UUID=a6751908-8205-4284-af42-ee451a834173
,09-12 12:09:19.287  2712  2765 D BtGatt.GattService: onClientRegistered() - UUID=a6751908-8205-4284-af42-ee451a834173, clientIf=5
,09-12 12:09:19.288  3862  3873 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 12:09:19.289  2712  2726 D BtGatt.GattService: start scan with filters
,09-12 12:09:19.295  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 12:09:19.295  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 12:09:19.295  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 12:09:19.295  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 12:09:19.295  2712  2770 D BtGatt.ScanManager: handling starting scan,
,09-12 12:09:19.303  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:09:19.304  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 12:09:19.304  2712  2765 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 12:09:19.304  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 12:09:19.304  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:09:19.305  2712  2770 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 12:09:19.310  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 12:09:19.315  3862  3913 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 12:09:19.321  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:19.322  3862  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 12:09:19.322  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:19.323  2712  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 12:09:19.323  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:09:19.324  2712  2770 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 12:09:19.324  2712  2770 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 12:09:19.322  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 12:09:19.325  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:19.325  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 12:09:19.325  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:09:19.325  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 12:09:19.326  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 12:09:19.326  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,09-12 12:09:19.327  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,09-12 12:09:19.327  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 12:09:19.329  3862  3913 D BluetoothAdapter: STATE_ON
09-12 12:09:19.331  2712  2898 D BtGatt.GattService: stopScan() - queue size =1
,09-12 12:09:19.333  2712  2726 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 12:09:19.334  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 12:09:19.334  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 12:09:19.334  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 12:09:19.334  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 12:09:19.335  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 12:09:19.338  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:09:19.339  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 12:09:19.339  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 12:09:19.339  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 12:09:19.341  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:09:19.344  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:09:19.344  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:09:19.344  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:09:19.344  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:19.344  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:09:19.344  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:09:19.344  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
,09-12 12:09:19.344  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:19.345  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
,09-12 12:09:19.345  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:09:19.345  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:19.345  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:09:19.345  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:19.346  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:09:19.346  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:09:19.346  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:19.346  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:19.347  3862  3913 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 12:09:19.349  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:09:19.350  2712  2765 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 12:09:19.351  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:19.357  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:09:19.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:19.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:19.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:19.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:09:19.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:19.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:19.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:09:19.358  2712  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 12:09:19.359  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:19.359  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:09:19.360  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:09:19.361  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 12:09:19.361  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 12:09:19.362  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:19.363  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-12 12:09:19.363  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:09:19.363  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 12:09:19.366  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:19.370  3862  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 12:09:19.371  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 12:09:19.372  2712  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 12:09:19.372  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:09:19.372  2712  2770 D BtGatt.ScanManager: stopping BLe Batch
,09-12 12:09:19.379  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 12:09:19.379  2712  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 12:09:19.379  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:19.380  2712  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 12:09:19.380  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 12:09:19.380  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 12:09:19.385  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 12:09:19.385  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 12:09:19.386  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 12:09:19.386  3862  3913 D BluetoothAdapter: STATE_ON
09-12 12:09:19.387  2712  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 12:09:19.387  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:19.389  2712  2907 D BtGatt.GattService: registerClient() - UUID=753d05da-1883-4034-9052-05634a44451f
,09-12 12:09:19.390  2712  2765 D BtGatt.GattService: onClientRegistered() - UUID=753d05da-1883-4034-9052-05634a44451f, clientIf=5
09-12 12:09:19.390  3862  3874 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 12:09:19.391  2712  2898 D BtGatt.GattService: start scan with filters
,09-12 12:09:19.394  2712  2770 D BtGatt.ScanManager: handling starting scan
,09-12 12:09:19.395  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 12:09:19.395  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 12:09:19.395  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 12:09:19.395  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 12:09:19.399  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:09:19.399  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 12:09:19.399  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:09:19.402  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 12:09:19.402  2712  2765 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 12:09:19.402  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:19.403  2712  2770 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 12:09:19.405  3862  3913 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 12:09:19.415  2712  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 12:09:19.415  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:19.415  2712  2770 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 12:09:19.415  2712  2770 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 12:09:19.433  2712  2765 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 12:09:19.433  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:19.443  2712  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 12:09:19.443  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:19.900  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 12:09:19.901  3862  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:09:19.901  3862  3862 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:09:20.548   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 12:09:20.948  2712  2712 D BtGatt.ScanManager: awakened up at time 144122
,09-12 12:09:20.951  2712  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,09-12 12:09:21.003  2712  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-12 12:09:21.003  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:09:21.004  2712  2765 D BtGatt.GattService: current time is 144177799475
09-12 12:09:21.004  2712  2765 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -92, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -65, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -68, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -94, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-12 12:09:21.005  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 12:09:21.006  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 12:09:21.007  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 12:09:21.008  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 12:09:21.008  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-12 12:09:22.508  2712  2712 D BtGatt.ScanManager: awakened up at time 145681
,09-12 12:09:22.510  2712  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:09:22.582  2712  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
09-12 12:09:22.582  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:22.583  2712  2765 D BtGatt.GattService: current time is 145756989476
,09-12 12:09:22.583  2712  2765 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -93, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 12:09:22.584  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 12:09:22.585  2712  2765 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 12:09:22.763  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:22.781  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:22.787  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:22.858  1502  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:09:22.859  1502  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 12:09:22.859  1502  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:09:22.860  1502  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:22.924  3575  3575 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 12:09:22.926  3575  3575 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 12:09:22.930  3575  3575 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 12:09:24.086  2712  2712 D BtGatt.ScanManager: awakened up at time 147260
,09-12 12:09:24.088  2712  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:09:24.109  2712  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 12:09:24.109  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:24.405  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:09:24.406  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:09:24.406  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 12:09:24.407  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:09:24.407  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 12:09:24.408  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:09:24.408  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 12:09:24.409  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 12:09:24.409  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:09:24.410  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 12:09:24.411  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 12:09:24.415  3862  3913 D BluetoothAdapter: STATE_ON
,09-12 12:09:24.419  2712  2907 D BtGatt.GattService: stopScan() - queue size =1
,09-12 12:09:24.424  2712  2898 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 12:09:24.425  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-12 12:09:24.425  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 12:09:24.425  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 12:09:24.425  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 12:09:24.425  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 12:09:24.427  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:09:24.427  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 12:09:24.427  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 12:09:24.427  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 12:09:24.429  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:09:24.431  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:09:24.432  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:09:24.432  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:09:24.438  2712  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 12:09:24.438  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:09:24.439  2712  2770 D BtGatt.ScanManager: stopping BLe Batch
,09-12 12:09:24.453  2712  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 12:09:24.453  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:24.454  2712  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:09:24.467  2712  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 12:09:24.467  2712  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:09:24.934  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:09:24.934  3862  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:09:24.934  3862  3862 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:09:29.434  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:09:29.434  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:09:29.435  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:29.435  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:09:29.435  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.436  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:09:29.437  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
,09-12 12:09:29.438  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.438  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
,09-12 12:09:29.440  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:29.440  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.444  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.444  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.447  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:29.448  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:09:29.448  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.448  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.451  3862  3913 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 12:09:29.453  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:29.453  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:29.454  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:29.454  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.454  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.455  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.455  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.456  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.456  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.457  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:09:29.457  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.457  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.457  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.458  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.461  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:29.461  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:29.462  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.462  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
,09-12 12:09:29.465  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 12:09:29.465  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:29.466  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:29.466  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:09:29.466  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.466  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.467  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.467  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.467  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.467  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.467  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:09:29.468  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.468  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.468  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.468  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.470  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:09:29.470  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:29.471  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.471  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
,09-12 12:09:29.473  3862  3913 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-12 12:09:29.473  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:29.474  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:09:29.474  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:09:29.475  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.475  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.475  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.475  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.476  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:29.476  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.476  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:09:29.477  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.477  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.477  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.477  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.479  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:09:29.479  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:29.479  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:29.480  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.481  3862  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 12:09:29.481  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:29.481  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:29.481  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:29.481  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.482  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:09:29.482  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.482  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.482  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.482  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.482  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:29.482  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.482  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.482  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.482  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.484  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:29.484  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:29.484  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.485  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.486  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 12:09:29.486  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:09:29.486  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:09:29.486  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 12:09:29.486  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 12:09:29.486  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 12:09:29.486  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 12:09:29.486  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:09:29.487  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 12:09:29.487  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:29.487  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:29.487  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:29.487  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.487  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.487  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.487  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.487  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.488  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.488  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:29.488  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.488  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.488  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.488  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.490  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:29.490  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:29.490  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.491  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
,09-12 12:09:29.492  3862  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 12:09:29.493  3862  3913 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 12:09:29.493  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 12:09:29.498  3862  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 12:09:29.498  3862  3913 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 12:09:29.498  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-12 12:09:29.499  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-12 12:09:29.499  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 12:09:29.499  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-12 12:09:29.499  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 12:09:29.500  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-12 12:09:29.500  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-12 12:09:29.500  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 12:09:29.500  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 12:09:29.500  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 12:09:29.501  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-12 12:09:29.501  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 12:09:29.501  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 12:09:29.501  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 12:09:29.501  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-12 12:09:29.501  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 12:09:29.502  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 12:09:29.502  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 12:09:29.502  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-12 12:09:29.502  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 12:09:29.503  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 12:09:29.503  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 12:09:29.503  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 12:09:29.503  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 12:09:29.503  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 12:09:29.503  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 12:09:29.503  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 12:09:29.504  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 12:09:29.504  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 12:09:29.504  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 12:09:29.504  3862  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 12:09:29.505  3862  3913 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 12:09:29.506  3862  3913 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 12:09:29.506  3862  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 12:09:29.506  3862  3913 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 12:09:29.506  3862  3913 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 12:09:29.507  3862  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 12:09:29.507  3862  3913 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 12:09:29.507  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 12:09:29.513  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 12:09:29.515  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 12:09:29.515  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 12:09:29.517  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 12:09:29.517  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 12:09:29.517  3862  3913 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 12:09:29.517  3862  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 12:09:29.518  3862  3913 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 12:09:29.518  3862  3930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 395)
09-12 12:09:29.520  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:29.520  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:29.520  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:29.520  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.521  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.521  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.521  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 12:09:29.522  3862  3930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 12:09:29.523  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.523  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.524  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.524  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:29.524  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.524  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.524  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.524  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.525  3862  3931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 395
,09-12 12:09:29.526  3862  3931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 395)
09-12 12:09:29.526  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:29.526  3862  3930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 395)
09-12 12:09:29.526  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:29.526  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.526  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.526  3862  3931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 395)
09-12 12:09:29.527  2712  2895 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-12 12:09:29.528  3862  3913 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 12:09:29.529  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:29.529  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:29.529  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:29.530  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.530  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.531  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.531  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.531  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.531  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.531  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:29.531  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.531  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.531  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.531  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.537  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:29.537  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:29.537  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.537  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.538  3862  3913 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 12:09:29.538  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:29.538  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:29.539  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:29.539  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.539  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.539  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.539  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.539  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.539  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.539  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:29.539  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.539  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.539  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.540  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.541  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:29.541  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:29.541  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.541  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.542  3862  3913 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 12:09:29.542  3862  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 12:09:29.542  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 12:09:29.542  3862  3913 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 12:09:29.542  3862  3913 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 12:09:29.542  3862  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 12:09:29.542  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 12:09:29.543  3862  3913 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 12:09:29.543  3862  3913 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 12:09:29.543  3862  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 12:09:29.543  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 12:09:29.543  3862  3913 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 12:09:29.543  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:29.543  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:29.543  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:29.543  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.543  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.543  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.544  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.544  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.544  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.544  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:29.544  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.544  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.544  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.544  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.545  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:29.545  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:29.545  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.545  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.546  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:29.546  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.546  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:29.547  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:29.547  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:29.547  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:29.547  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:29.547  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:29.547  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:29.998   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 12:09:30.008  1897  1897 I Keyboard.Facilitator: onFinishInput()
,09-12 12:09:30.027   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 12:09:30.027   872   892 I Adreno  : Build Date                       : 10/20/15
09-12 12:09:30.027   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 12:09:30.027   872   892 I Adreno  : Local Branch                     : M14
09-12 12:09:30.027   872   892 I Adreno  : Remote Branch                    : 
09-12 12:09:30.027   872   892 I Adreno  : Remote Branch                    : 
09-12 12:09:30.027   872   892 I Adreno  : Reconstruct Branch               : 
,09-12 12:09:30.069   282   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (278 us)
,09-12 12:09:30.702  3862  3862 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 12:09:30.703  3862  3862 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 12:09:30.741   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 12:09:30.742  3862  3862 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4500d0a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d3dc876, 16908290=android.view.AbsSavedState$1@d3dc876}, android:focusedViewId=100}]}]
,09-12 12:09:30.742  3862  3862 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-12 12:09:30.742  3862  3862 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 12:09:30.743  3862  3862 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 12:09:30.756   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 12:09:30.760   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,09-12 12:09:30.760   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-12 12:09:30.761   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-12 12:09:31.015   282   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 12:09:31.017   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 12:09:31.018   872  1333 D SurfaceControl: Excessive delay in setPowerMode(): 258ms
,09-12 12:09:31.025   872   892 I DreamManagerService: Entering dreamland.
,09-12 12:09:31.027   872   892 I PowerManagerService: Dozing...
,09-12 12:09:31.029   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 12:09:31.076   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-12 12:09:31.076   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 12:09:31.090   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:09:31.102   872  1307 E native  : do suspend false
,09-12 12:09:31.102  1950  3935 D NfcService: Discovery configuration equal, not updating.
,09-12 12:09:31.119   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 12:09:31.129   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:09:31.134   872  1307 E native  : do suspend true
,09-12 12:09:31.217   377  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 12:09:31.218   377  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 12:09:31.594   872  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-12 12:09:34.548  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:34.548  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.549  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:09:34.549  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.549  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:34.550  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
,09-12 12:09:34.550  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:09:34.550  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:09:34.551  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:34.551  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:09:34.551  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.552  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.552  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
,09-12 12:09:34.552  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:34.553  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.553  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:09:34.553  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.553  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.554  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.554  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:34.558  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:34.558  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:34.558  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:34.558  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.564  3862  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 12:09:34.565  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:09:34.568  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 12:09:34.569  3862  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 12:09:34.569  3862  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 12:09:34.569  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 12:09:34.569  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 12:09:34.569  3862  3862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 12:09:34.569  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-12 12:09:34.570  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 12:09:34.570  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 12:09:34.570  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-12 12:09:34.570  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:34.570  3862  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 12:09:34.570  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
,09-12 12:09:34.570  3862  3862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 12:09:34.570  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 12:09:34.570  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 12:09:34.570  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 12:09:34.570  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:09:34.571  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:09:34.571  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:34.571  3862  3940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 12:09:34.571  3862  3940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 12:09:34.572  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:09:34.572  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
,09-12 12:09:34.572  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:09:34.572  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:09:34.572  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:34.573  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:09:34.573  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:09:34.573  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:34.573  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.573  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.573  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:09:34.573  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:34.573  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:34.573  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.573  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:34.573  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.573  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.573  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.574  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:34.574  3862  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 12:09:34.574  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:34.575  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:09:34.575  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:34.575  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.576  3862  3913 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 12:09:34.577  3862  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 12:09:34.577  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 12:09:34.577  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 12:09:34.577  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 12:09:34.577  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:34.577  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:34.577  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:34.577  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:34.577  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.578  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:34.578  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:34.578  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:34.578  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.578  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:34.578  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:09:34.578  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.578  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.578  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.579  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:34.579  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:09:34.579  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:34.579  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.583  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:09:34.583  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:34.583  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:09:34.583  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:34.584  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.584  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.584  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
09-12 12:09:34.584  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:34.584  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.584  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:34.584  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.584  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.584  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.584  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:34.585  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:34.585  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:34.585  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:34.585  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.586  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:09:34.587  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:09:34.587  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:09:34.587  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:09:34.587  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.587  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.587  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f2587 not in the list
,09-12 12:09:34.587  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:34.587  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.587  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:34.588  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:34.588  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.588  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:09:34.588  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:34.589  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:09:34.589  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:09:34.589  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:09:34.589  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc4cb4 not in the list
09-12 12:09:34.590  3862  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 12:09:34.590  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-12 12:09:34.590  3862  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 12:09:34.590  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 12:09:34.590  3862  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 12:09:34.591  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 12:09:34.593  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 12:09:34.594  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 12:09:34.594  3862  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-12 12:09:34.594  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 12:09:34.594  3862  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 12:09:34.595  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 12:09:34.595  3862  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 12:09:34.595  3862  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 12:09:34.595  3862  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 12:09:34.595  3862  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-12 12:09:34.596  3862  3913 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 12:09:34.596  3862  3913 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 12:09:34.596  3862  3913 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 12:09:34.596  3862  3913 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 12:09:34.597  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:09:34.597  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a67e77 added. We now have 3 listener(s)
,09-12 12:09:34.598  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:09:34.601  3862  3913 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 12:09:34.601   872  1687 D WifiService: setWifiEnabled: true pid=3862, uid=10000
09-12 12:09:34.601   872  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:09:34.652  2712  2892 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-12 12:09:34.652  2712  2892 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-12 12:09:35.074  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:09:36.326  1864  2648 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 12:09:37.161  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:37.166  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:37.193  1502  2997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:09:37.194  1502  2997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:09:37.194  1502  2997 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:09:37.194  1502  2997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:37.214  3017  3943 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:09:37.214  3017  3943 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:09:37.214  3017  3943 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	... 12 more
09-12 12:09:37.214  3017  3943 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at fal.a(PG:38)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:09:37.214  3017  3943 E HttpOperation: 	... 14 more
,09-12 12:09:37.258  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:09:37.258  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:09:37.258  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:09:37.258  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:37.279  3017  3943 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:09:37.279  3017  3943 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at hec.a(PG:42)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at hee.a(PG:102)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at czr.a(PG:65)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at kka.a(PG:108)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:09:37.279  3017  3943 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	... 15 more
09-12 12:09:37.279  3017  3943 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at fal.a(PG:38)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:09:37.279  3017  3943 E HttpOperation: 	... 17 more
,09-12 12:09:37.279  3017  3943 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 12:09:37.279  3017  3943 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	... 15 more
09-12 12:09:37.279  3017  3943 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:09:37.279  3017  3943 E ExperimentLoader: 	... 17 more
,09-12 12:09:37.376   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 133712, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:09:39.609  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 12:09:39.610  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3764ae4 added. We now have 4 listener(s)
09-12 12:09:39.610  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:09:39.628  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:39.628  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3764ae4 removed from the list
,09-12 12:09:39.628  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:39.629  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:09:39.629  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:09:39.634  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 12:09:39.634  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4878b4d added. We now have 4 listener(s)
09-12 12:09:39.634  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:09:39.638  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:09:39.638  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4878b4d removed from the list
,09-12 12:09:39.639  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:09:39.639  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:09:39.639  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:09:39.642  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:09:39.642  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b5f602 added. We now have 4 listener(s)
09-12 12:09:39.642  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:09:39.650   872  2169 D WifiService: setWifiEnabled: false pid=3862, uid=10000
09-12 12:09:39.650   872  2169 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:09:39.665  2712  2761 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 12:09:39.665  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:09:39.665  2712  2761 D BluetoothAdapterProperties: Setting state to 13
,09-12 12:09:39.666  2712  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 12:09:39.667  2712  2761 D BluetoothAdapterProperties: onBluetoothDisable(),
,09-12 12:09:39.669  2712  2761 I BluetoothAdapterState: Entering PendingCommandState,
09-12 12:09:39.674  2712  2765 D BluetoothAdapterProperties: Scan Mode:20
,09-12 12:09:39.675  2712  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 12:09:39.676  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:39.677  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-12 12:09:39.677  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:39.677  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:39.677  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:39.677  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:39.677  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:39.677  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:39.677  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:09:39.679  2712  2712 D BluetoothMapService: onReceive
,09-12 12:09:39.680  2712  2712 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 12:09:39.680  2712  2712 D BluetoothMapService: STATE_TURNING_OFF
,09-12 12:09:39.680  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.681  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:39.681  2712  2712 D BluetoothMapService: MAP Service closeService in
09-12 12:09:39.681  2712  2712 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 12:09:39.681  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:09:39.681  2712  2712 D ObexServerSockets0: shutdown(block = true)
09-12 12:09:39.683  2712  2908 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 12:09:39.686  2712  2712 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 12:09:39.687  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:39.687  2712  2909 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-12 12:09:39.688  2712  2895 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 12:09:39.688  2712  2712 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 12:09:39.689  2712  2712 I BtOppRfcommListener: stopping Accept Thread
09-12 12:09:39.689  2712  3480 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 12:09:39.689  2712  3480 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 12:09:39.690  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:39.695  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.695  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:39.695  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:39.695  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:39.695  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:39.695  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:39.695  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:39.695  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:39.695  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:09:39.695  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.696  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:39.698  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 12:09:39.699   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 12:09:39.699   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 12:09:39.699   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 12:09:39.699  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.700   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:09:39.700  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:39.700  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:39.700  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:39.700  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:39.700  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:39.700  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:39.700  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:39.700  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:09:39.700  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.700  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:39.703  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:39.706  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:39.708   872   885 I ActivityManager: Start proc 3948:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-12 12:09:39.708  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:39.713   872  1307 E native  : do suspend true
,09-12 12:09:39.714  2712  2712 D HeadsetService: Received stop request...Stopping profile...
09-12 12:09:39.715  1967  2131 D BluetoothHeadset: Proxy object disconnected
09-12 12:09:39.715  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:39.716   872   872 D BluetoothHeadset: Proxy object disconnected
,09-12 12:09:39.716  1361  2091 D BluetoothHeadset: Proxy object disconnected
,09-12 12:09:39.716   872   872 D BluetoothHeadset: Proxy object disconnected
,09-12 12:09:39.716   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 12:09:39.717  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,09-12 12:09:39.717  2712  2712 D A2dpService: Received stop request...Stopping profile...
09-12 12:09:39.717  2712  2901 D A2dpStateMachine: Exit Disconnected: -1
09-12 12:09:39.719   872   872 D BluetoothA2dp: Proxy object disconnected
09-12 12:09:39.719  1361  1361 D BluetoothA2dp: Proxy object disconnected
09-12 12:09:39.720  2712  2712 D HidService: Received stop request...Stopping profile...
09-12 12:09:39.720  2712  2712 D HidService: Stopping Bluetooth HidService
09-12 12:09:39.722  1361  1361 D BluetoothInputDevice: Proxy object disconnected
,09-12 12:09:39.722  1361  1361 D HidProfile: Bluetooth service disconnected
09-12 12:09:39.724  2712  2712 D HealthService: Received stop request...Stopping profile...
09-12 12:09:39.725  2712  2712 V BluetoothAdapterState: isTurningOff()=true
09-12 12:09:39.725  2712  2712 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:39.725  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:39.725  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:39.727   872  1892 D DhcpClient: Clearing IP address
,09-12 12:09:39.727  2712  2712 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 12:09:39.727  2712  2765 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 12:09:39.727   373   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 12:09:39.727  2712  2712 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 12:09:39.727  2712  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:39.728  2712  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:39.728  2712  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:39.728  2712  2765 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-12 12:09:39.729  2712  2712 D PanService: Received stop request...Stopping profile...
09-12 12:09:39.731  2712  2712 D BluetoothMapService: Received stop request...Stopping profile...
09-12 12:09:39.731  2712  2712 D BluetoothMapService: stop()
09-12 12:09:39.731  2712  2712 D BluetoothMapAppObserver: deinitObservers()
09-12 12:09:39.731  2712  2712 D BluetoothMapAppObserver: removeReceiver()
09-12 12:09:39.732  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 12:09:39.732  1361  1361 D PanProfile: Bluetooth service disconnected
09-12 12:09:39.733  1502  2484 V NativeCrypto: Read error: ssl=0x9b1fec00: I/O error during system call, Connection timed out
09-12 12:09:39.734  1502  2484 V NativeCrypto: SSL shutdown failed: ssl=0x9b1fec00: I/O error during system call, Broken pipe
09-12 12:09:39.734   373   871 D CommandListener: Setting iface cfg
09-12 12:09:39.736  2712  2712 V BluetoothAdapterState: isTurningOff()=true
09-12 12:09:39.736  2712  2712 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:39.736  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:39.736  1361  1361 D BluetoothMap: Proxy object disconnected
,09-12 12:09:39.736  1361  1361 D MapProfile: Bluetooth service disconnected
09-12 12:09:39.736   872  1687 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-12 12:09:39.737   872  1869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-12 12:09:39.738   872  1869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-12 12:09:39.739   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-12 12:09:39.739   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-12 12:09:39.740   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 12:09:39.736  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:39.741   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-12 12:09:39.741   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 12:09:39.741   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-12 12:09:39.741   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 12:09:39.742   872  1307 E native  : do suspend true
09-12 12:09:39.744   396   396 E Parcel  : Reading a NULL string not supported here.
09-12 12:09:39.746  2712  2765 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 12:09:39.746  2712  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:39.746  2712  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:39.746  2712  2892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 12:09:39.746  2712  2892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 12:09:39.746  2712  2892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 12:09:39.746  2712  2892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 12:09:39.747  2712  2712 V BluetoothAdapterState: isTurningOff()=true
09-12 12:09:39.747  2712  2712 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:39.747  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:39.747  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:39.748  2712  2712 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 12:09:39.748  2712  2765 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 12:09:39.749  2712  2712 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 12:09:39.749   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 12:09:39.750   872  1895 D DhcpClient: Receive thread stopped
09-12 12:09:39.750  2712  2712 V BluetoothAdapterState: isTurningOff()=true
09-12 12:09:39.750  2712  2712 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:39.750  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:39.750  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:39.750  2712  2712 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 12:09:39.750  2712  2765 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-12 12:09:39.751  2712  2712 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 12:09:39.753  2712  2712 V BluetoothAdapterState: isTurningOff()=true
09-12 12:09:39.754  2712  2712 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:39.754  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:39.754  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:39.755  2712  2712 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 12:09:39.755  2712  2712 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 12:09:39.756  2712  2712 D BluetoothMapService: MAP Service closeService in
09-12 12:09:39.756  2712  2712 V BluetoothAdapterState: isTurningOff()=true
,09-12 12:09:39.756  2712  2712 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:39.756  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:39.756  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:39.756  2712  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 12:09:39.756  2712  2761 D BluetoothAdapterProperties: Setting state to 15
09-12 12:09:39.756  2712  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 12:09:39.757  2712  2761 I BluetoothAdapterState: Entering BleOnState
09-12 12:09:39.757  2712  2712 D BluetoothMapService: cleanup()
09-12 12:09:39.757  2712  2712 D BluetoothMapService: MAP Service closeService in
,09-12 12:09:39.757  1361  1377 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 12:09:39.758  1361  2091 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:09:39.758   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:09:39.758  1361  1376 D BluetoothPan: onBluetoothStateChange on: false
09-12 12:09:39.758   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 12:09:39.758  1967  2310 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:09:39.759  1361  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 12:09:39.759   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 12:09:39.759   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:09:39.759  1361  2091 D BluetoothMap: onBluetoothStateChange: up=false
09-12 12:09:39.759  1361  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 12:09:39.760  2712  2761 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 12:09:39.760  2712  2761 D BluetoothAdapterProperties: Setting state to 16
09-12 12:09:39.760  2712  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 12:09:39.761  2712  2761 D BluetoothAdapterProperties: onBleDisable
09-12 12:09:39.761  2712  2761 I BluetoothAdapterState: Entering PendingCommandState
09-12 12:09:39.761  2712  2762 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 12:09:39.762  2712  2892 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 12:09:39.762  2712  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:39.762  2712  2765 D BluetoothAdapterProperties: Scan Mode:20
,09-12 12:09:39.763  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.763  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:39.763  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:39.763  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:39.763  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:39.763  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:39.763  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:39.763  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:39.763  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:39.763  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.763  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:09:39.765  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.765  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:39.765  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:39.765  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:39.765  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:39.765  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:39.765  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:39.765  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:39.765  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:39.765  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.765  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:39.767  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.767  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:39.767  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:39.767  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:39.767  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:39.767  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:39.767  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:39.767  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:39.767  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:39.767  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.767  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:09:39.768  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:39.769  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:39.769  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:39.779   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:09:39.795  3948  3948 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 12:09:39.798   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:09:39.798   373   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 12:09:39.798   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-12 12:09:39.798   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:09:39.800   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 12:09:39.802   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:09:39.803  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:39.803  3466  3466 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2d2d9be and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-12 12:09:39.804  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:39.805  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:39.813  2070  2070 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-12 12:09:39.820   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:09:39.822  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:39.823  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:39.823  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:39.823  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:39.823  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:39.823  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:39.823  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:39.823  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:39.823  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:39.823  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.823  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:39.824  1864  2309 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 12:09:39.825  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.825  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:39.825  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:39.825  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:39.825  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:39.825  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:39.825  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:39.825  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:39.825  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:39.825  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
09-12 12:09:39.825   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 12:09:39.825  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.825  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:39.827  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.827  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:39.827  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:39.827  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:39.827  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:39.827  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:39.827  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:39.827  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:39.827  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:39.827  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:39.827  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:39.833  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 12:09:39.837   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33ce4b7:true
,09-12 12:09:39.847   872  2167 I ActivityManager: Start proc 3969:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 12:09:39.857   373   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 12:09:39.857   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 12:09:39.872  3948  3948 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 12:09:39.874  3948  3948 D BluetoothMap: Create BluetoothMap proxy object
,09-12 12:09:39.878  3948  3948 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 12:09:39.883  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 12:09:39.893  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,09-12 12:09:39.901   872  1386 I ActivityManager: Killing 2985:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-12 12:09:39.964  2712  2765 I bt_hci  : shut_down
,09-12 12:09:39.964  2712  2771 D bt_hwcfg: hw_epilog_process
,09-12 12:09:39.991  2712  2771 I bt_vendor: low_power_mode_cb
,09-12 12:09:40.018  2712  2771 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 12:09:40.018  2712  2771 I bt_vendor: epilog_cb
,09-12 12:09:40.019  2712  2771 I bt_hci  : epilog_finished_callback
,09-12 12:09:40.024  2712  2765 I bt_hci_h4: hal_close
,09-12 12:09:40.025  2712  2765 I bt_userial_vendor: device fd = 51 close
,09-12 12:09:40.079  3969  3969 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 12:09:40.079  3969  3969 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 12:09:40.079  3969  3969 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:09:40.079  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 12:09:40.085  3969  3969 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 12:09:40.085  3969  3969 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:09:40.085  3969  3969 D StrictMode: 	,at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:09:40.085  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 12:09:40.086  3969  3969 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 12:09:40.086  3969  3969 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
,09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 12:09:40.086  3969  3969 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:09:40.086  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 12:09:40.099  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 12:09:40.108  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 12:09:40.128  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,09-12 12:09:40.131  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 12:09:40.138  1697  1697 D SystemUpdateService: onCreate
,09-12 12:09:40.145  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 12:09:40.158  2712  2762 D bt_stack_manager: event_shut_down_stack finished.
,09-12 12:09:40.160  2712  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 12:09:40.168  1697  4000 I SystemUpdateService: active receiver: enabled
,09-12 12:09:40.173  2712  2712 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 12:09:40.174  2712  2761 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 12:09:40.179  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 12:09:40.184  1697  2460 I iu.UploadsManager: num queued entries: 0
09-12 12:09:40.184  1697  2460 I iu.UploadsManager: num updated entries: 0
,09-12 12:09:40.190  2712  2712 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 12:09:40.190  2712  2712 D BtGatt.GattService: stop()
09-12 12:09:40.190  2712  2712 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 12:09:40.191  2712  2712 V BluetoothAdapterState: isTurningOff()=false
09-12 12:09:40.191  2712  2712 V BluetoothAdapterState: isTurningOn()=false
,09-12 12:09:40.192  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:40.192  2712  2712 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 12:09:40.192  2712  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 12:09:40.192  2712  2761 D BluetoothAdapterProperties: Setting state to 10
09-12 12:09:40.193  2712  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-12 12:09:40.194  2712  2761 I BluetoothAdapterState: Entering OffState
,09-12 12:09:40.195   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 12:09:40.195  1697  4000 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 12:09:40.199  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 12:09:40.201  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 12:09:40.203  1697  4000 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 12:09:40.203  1697  4000 I SystemUpdateService: now status is 0 (complete)
09-12 12:09:40.203  1697  4000 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 12:09:40.203  1697  4000 I SystemUpdateService: file has been verified
09-12 12:09:40.203  1697  4000 I SystemUpdateService: OTA package size = 12249756
,09-12 12:09:40.206  1697  2460 I iu.SyncManager: NEXT; no task
,09-12 12:09:40.218  1697  4000 I SystemUpdateService: showing system update notification
,09-12 12:09:40.237   872   882 I ActivityManager: Start proc 4002:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 12:09:40.252  2712  2712 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 12:09:40.253  2712  2712 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 12:09:40.253  2712  2712 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 12:09:40.254  2712  2762 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-12 12:09:40.255  2712  2762 D bt_stack_manager: event_clean_up_stack finished.
,09-12 12:09:40.272  4002  4002 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 12:09:40.278  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:09:40.283  2712  2712 I art     : System.exit called, status: 0
,09-12 12:09:40.283  2712  2712 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 12:09:40.296  4002  4002 D SprintDMHelper: simOperator: 
09-12 12:09:40.296  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 12:09:40.338   872  2165 I ActivityManager: Start proc 4015:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 12:09:40.341   872  2165 I ActivityManager: Killing 3466:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 12:09:40.388   872  1386 I ActivityManager: Process com.android.bluetooth (pid 2712) has died
,09-12 12:09:40.389  1697  1697 D SystemUpdateService: onDestroy
,09-12 12:09:40.492  3969  3996 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 12:09:40.508   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2488a2:true
,09-12 12:09:40.519   872  2165 I ActivityManager: Start proc 4032:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 12:09:40.523  3114  4031 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 12:09:40.535   872  2169 I ActivityManager: Killing 3529:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 12:09:40.622  4032  4032 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 12:09:40.685  4032  4032 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 12:09:40.685  4032  4032 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 12:09:40.685  4032  4032 I GAv4    :   adb logcat -s GAv4
,09-12 12:09:40.700  4032  4032 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 12:09:40.707  4032  4032 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 12:09:40.735  4032  4049 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 12:09:40.854  4032  4032 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 12:09:40.902  4032  4032 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 12:09:40.917  4032  4032 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4085-4091)
09-12 12:09:40.917  4032  4032 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 12:09:40.927  4032  4032 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {baaa788}
,09-12 12:09:40.927  4032  4032 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 12:09:40.928  4032  4032 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 12:09:40.940  4032  4032 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 12:09:40.942  4032  4032 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 12:09:40.960  4032  4032 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 12:09:40.972  4032  4032 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 12:09:40.972  4032  4032 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 12:09:40.972  4032  4032 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 12:09:40.972  4032  4032 I Adreno  : Build Date                       : 10/20/15
09-12 12:09:40.972  4032  4032 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 12:09:40.972  4032  4032 I Adreno  : Local Branch                     : M14
09-12 12:09:40.972  4032  4032 I Adreno  : Remote Branch                    : 
09-12 12:09:40.972  4032  4032 I Adreno  : Remote Branch                    : 
09-12 12:09:40.972  4032  4032 I Adreno  : Reconstruct Branch               : 
,09-12 12:09:41.042  4032  4032 I NSApplication: Starting up...
,09-12 12:09:41.053  4032  4078 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 12:09:41.088   872  1990 I ActivityManager: Start proc 4083:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 12:09:41.089   872  1990 I ActivityManager: Killing 1711:android.process.acore/u0a5 (adj 15): empty #17
,09-12 12:09:41.165  4083  4083 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 12:09:41.341   872  1999 I ActivityManager: Killing 3718:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 12:09:41.456   872  1990 I ActivityManager: Start proc 4097:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 12:09:41.555  4097  4097 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 12:09:41.612  4097  4097 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 12:09:41.674   872  1687 I ActivityManager: Killing 3732:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 12:09:44.687   872  2165 D WifiService: setWifiEnabled: true pid=3862, uid=10000
,09-12 12:09:44.688   872  2165 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:09:44.701   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-12 12:09:44.708  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:44.709  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:44.709  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:44.709  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:44.709  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:44.709  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:44.709  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:44.709  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:44.709  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:09:44.709  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:44.710  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:44.714  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:44.714  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:44.714  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:44.714  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:44.714  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:44.714  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:44.714  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:44.714  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:44.714  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:09:44.715  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:44.715  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:44.718  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:44.719  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:44.719  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
09-12 12:09:44.719  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:44.719  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:44.719  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:44.719  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:44.719  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:44.719  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:44.719  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:44.720  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:44.753   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-12 12:09:44.755   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 12:09:44.758   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 12:09:44.760   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 12:09:44.761   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-12 12:09:44.761   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 12:09:44.762   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 12:09:44.783   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 12:09:44.783   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=13.38 rxSuccessRate=18.12 delta 1000 -> 994
,09-12 12:09:44.784   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:09:44.784   373   871 D CommandListener: Setting iface cfg
,09-12 12:09:44.785   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-12 12:09:44.785   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 12:09:44.798   872  1307 E native  : do suspend true
,09-12 12:09:44.798   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 12:09:44.807   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 12:09:44.814   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 12:09:44.814   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:09:44.825   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 12:09:44.887   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 12:09:44.888  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 12:09:45.333  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 12:09:45.390  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 12:09:45.390  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 12:09:45.393   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.,
,09-12 12:09:45.402   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 12:09:45.402   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 12:09:45.403   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 12:09:45.425   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:09:45.443   373   871 D CommandListener: Setting iface cfg
,09-12 12:09:45.445   872  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 12:09:45.460   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 12:09:45.478   872  4130 D DhcpClient: Receive thread started
,09-12 12:09:45.564   872  1307 E native  : do suspend false
,09-12 12:09:45.569   872  2164 I ActivityManager: Killing 3512:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 12:09:45.578   872  1892 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 12:09:45.590   872  4130 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172654, domain null
,09-12 12:09:45.624   872  1892 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172654 seconds
,09-12 12:09:45.627   872  1892 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 12:09:45.643   872  4130 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 12:09:45.643   872  1892 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-12 12:09:45.645   373   871 D CommandListener: Setting iface cfg
,09-12 12:09:45.655   872  1892 D DhcpClient: Scheduling renewal in 86399s
,09-12 12:09:45.656   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 12:09:45.659   872  1307 E native  : do suspend true
,09-12 12:09:45.683   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 12:09:45.687   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 12:09:45.689   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 12:09:45.691   872  1309 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 12:09:45.695   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 12:09:45.733   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 12:09:45.734   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 12:09:45.737   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 12:09:45.740   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 12:09:45.745   872  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 12:09:45.760   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 12:09:45.765   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 12:09:45.765   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-12 12:09:45.766   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 12:09:45.766   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-12 12:09:45.766   872  1309 D ConnectivityService:    accepting network in place of null
,09-12 12:09:45.766   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 12:09:45.767   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 12:09:45.777   872  4129 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168950, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:09:45.819   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:09:45.844   872  4128 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-12 12:09:45.854   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:09:45.863   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 12:09:45.864   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:09:45.871   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-12 12:09:45.876   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 12:09:45.889  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:45.889  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:45.889  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:45.889  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:45.889  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:45.889  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:45.889  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:45.889  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:45.889  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:09:45.890  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:45.890  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:09:45.892  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:45.892  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:45.892  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:45.892  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:45.892  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:45.892  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:45.892  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:45.892  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:45.892  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:09:45.892  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:45.892  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:09:45.895  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:45.895  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:45.895  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:45.895  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:45.895  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:09:45.895  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:45.895  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:09:45.895  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:09:45.895  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 12:09:45.895  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:45.896  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:09:45.908  2070  2070 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-12 12:09:45.915   872  4128 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 10:09:45 GMT], X-Android-Received-Millis=[1473674985914], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473674985887]}
09-12 12:09:45.916   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 12:09:45.916   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-12 12:09:45.917   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 12:09:45.918   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 12:09:45.921  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 12:09:45.925  1697  1697 D SystemUpdateService: onCreate
,09-12 12:09:45.929  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 12:09:45.957  1697  4142 I SystemUpdateService: active receiver: enabled
,09-12 12:09:45.967  1697  4142 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 12:09:45.969  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 12:09:45.971  1697  2460 I iu.UploadsManager: num queued entries: 0
,09-12 12:09:45.971  1697  2460 I iu.UploadsManager: num updated entries: 0
,09-12 12:09:45.978  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 12:09:45.979  1697  2460 I iu.SyncManager: NEXT; no task
,09-12 12:09:45.982  1697  4142 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-12 12:09:45.983  1697  4142 I SystemUpdateService: now status is 0 (complete)
09-12 12:09:45.983  1697  4142 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 12:09:45.983  1697  4142 I SystemUpdateService: file has been verified
09-12 12:09:45.983  1697  4142 I SystemUpdateService: OTA package size = 12249756
,09-12 12:09:45.985  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 12:09:45.988  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:09:45.994  1697  4147 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 12:09:45.994  1697  4147 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 12:09:45.996  4002  4002 D SprintDMHelper: simOperator: 
,09-12 12:09:45.996  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 12:09:45.997  1697  4147 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 12:09:46.004  1697  4142 I SystemUpdateService: showing system update notification
,09-12 12:09:46.016  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:46.020  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:46.089  1697  1697 D SystemUpdateService: onDestroy
,09-12 12:09:46.097  1502  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 12:09:46.097  1502  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 12:09:46.097  1502  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:09:46.098  1502  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:46.125  3114  4149 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 12:09:46.133  1697  4147 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-12 12:09:46.139  3819  4140 V KeepSync: Connecting to GoogleApiClient
,09-12 12:09:46.140   872  2166 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:09:46.196  1502  2180 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 12:09:46.196  1502  2180 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 12:09:46.196  1502  2180 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:09:46.196  1502  2180 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:46.215  1697  4157 V BaseAuthAsyncOperation: access token request failed
,09-12 12:09:46.217  3819  4140 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:09:46.306  1697  1697 I GCM     : Message from null null
,09-12 12:09:46.310  1697  1697 E GCM     : Dropping message from null
,09-12 12:09:46.432  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:46.440  1502  4159 I VacuumService: Vacuum at: now=1473674986440 tag=VacuumService
,09-12 12:09:46.509  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 12:09:46.510  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 12:09:46.511  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:09:46.511  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:46.533  3819  4140 E KeepSync: IOException
09-12 12:09:46.533  3819  4140 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:09:46.533  3819  4140 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:09:46.533  3819  4140 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:09:46.533  3819  4140 E KeepSync: 	... 10 more
,09-12 12:09:46.533  3819  4140 W KeepSync: Sync result 2
,09-12 12:09:46.547   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 164454, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:09:46.744  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:09:46.769  1502  4160 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
09-12 12:09:46.771  1502  4160 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 12:09:46.794  1502  2180 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:09:46.794  1502  2180 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:09:46.794  1502  2180 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:09:46.794  1502  2180 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:46.817  1502  4160 W Uploader:  no longer exists, so no auth token.
,09-12 12:09:46.848  3575  3575 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:09:46.848  3575  3575 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 12:09:46.849  3575  3575 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 12:09:46.862   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 12:09:48.446  1502  4160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 12:09:48.446  1502  4160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 12:09:48.447  1502  4160 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:09:48.447  1502  4160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:48.473  1502  4160 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 12:09:48.473  1502  4160 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 12:09:48.473  1502  4160 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 12:09:48.671  1502  4160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 12:09:48.671  1502  4160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 12:09:48.671  1502  4160 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:09:48.671  1502  4160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:48.701  1502  4160 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 12:09:48.701  1502  4160 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 12:09:48.701  1502  4160 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 12:09:49.308  1502  4160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 12:09:49.308  1502  4160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 12:09:49.308  1502  4160 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:09:49.309  1502  4160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:49.332  1502  4160 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 12:09:49.332  1502  4160 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 12:09:49.332  1502  4160 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 12:09:49.510  1502  4160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 12:09:49.511  1502  4160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 12:09:49.511  1502  4160 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:09:49.511  1502  4160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:09:49.533  1502  4160 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 12:09:49.533  1502  4160 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 12:09:49.533  1502  4160 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 12:09:49.694   872  1694 D WifiService: setWifiEnabled: false pid=3862, uid=10000
,09-12 12:09:49.695   872  1694 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:09:49.717  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 12:09:49.720   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 12:09:49.720   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-12 12:09:49.721   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 12:09:49.721   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:09:49.733   872  1307 E native  : do suspend true
,09-12 12:09:49.741   872  1892 D DhcpClient: Clearing IP address
,09-12 12:09:49.741   373   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 12:09:49.744   373   871 D CommandListener: Setting iface cfg
,09-12 12:09:49.746  1502  4154 V NativeCrypto: Read error: ssl=0x9a8a0000: I/O error during system call, Connection timed out
,09-12 12:09:49.748  1502  4154 V NativeCrypto: SSL shutdown failed: ssl=0x9a8a0000: I/O error during system call, Broken pipe
,09-12 12:09:49.752   872   883 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
09-12 12:09:49.753   872  4128 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-12 12:09:49.756   872  4128 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 12:09:49.757   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-12 12:09:49.758   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 12:09:49.769   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 12:09:49.770   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-12 12:09:49.770   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 12:09:49.771   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-12 12:09:49.774   396   396 E Parcel  : Reading a NULL string not supported here.
09-12 12:09:49.772   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 12:09:49.777   872  1307 E native  : do suspend true
09-12 12:09:49.782   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 12:09:49.783   373   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 12:09:49.786   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:09:49.790   872  4130 D DhcpClient: Receive thread stopped
,09-12 12:09:49.801   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:09:49.804  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:49.804  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:49.804  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:49.804  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:49.804  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:49.804  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:49.804  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:49.804  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:49.804  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:09:49.804  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:49.804  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:49.805  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:49.805  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:49.805  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:49.805  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:49.805  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:49.805  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:49.805  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:49.805  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:49.805  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:49.805  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:49.805  1864  2309 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 12:09:49.805  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:49.806  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:49.806  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:49.806  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:49.806  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:49.806  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:49.806  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:49.806  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:49.806  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:49.806  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:49.806  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:49.806  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:09:49.806   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 12:09:49.823   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:09:49.841   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:09:49.844   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 12:09:49.846   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:09:49.848   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 12:09:49.853  2070  2070 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-12 12:09:49.857  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:49.860  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:49.863  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:49.869  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 12:09:49.875  1697  1697 D SystemUpdateService: onCreate
,09-12 12:09:49.878  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 12:09:49.892  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 12:09:49.897  1697  2460 I iu.UploadsManager: num queued entries: 0
,09-12 12:09:49.897  1697  2460 I iu.UploadsManager: num updated entries: 0
,09-12 12:09:49.898  1697  2460 I iu.SyncManager: NEXT; no task
,09-12 12:09:49.899  1697  4179 I SystemUpdateService: active receiver: enabled
,09-12 12:09:49.901  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 12:09:49.903  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 12:09:49.905  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:09:49.909  4002  4002 D SprintDMHelper: simOperator: 
,09-12 12:09:49.909  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 12:09:49.941  1697  4179 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 12:09:49.942  3114  4183 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 12:09:49.950  1697  4179 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 12:09:49.950  1697  4179 I SystemUpdateService: now status is 0 (complete)
09-12 12:09:49.950  1697  4179 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 12:09:49.950  1697  4179 I SystemUpdateService: file has been verified
09-12 12:09:49.950  1697  4179 I SystemUpdateService: OTA package size = 12249756
,09-12 12:09:49.953  1697  4179 I SystemUpdateService: showing system update notification
,09-12 12:09:49.964  1697  1697 D SystemUpdateService: onDestroy
,09-12 12:09:49.965   373   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 12:09:49.966   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 12:09:53.770   872  1309 D ConnectivityService: handlePromptUnvalidated 101
,09-12 12:09:54.752   872   889 I ActivityManager: Start proc 4187:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 12:09:54.871  4187  4187 D AdapterServiceConfig: Adding HeadsetService
,09-12 12:09:54.872  4187  4187 D AdapterServiceConfig: Adding A2dpService
09-12 12:09:54.872  4187  4187 D AdapterServiceConfig: Adding HidService
,09-12 12:09:54.872  4187  4187 D AdapterServiceConfig: Adding HealthService
09-12 12:09:54.872  4187  4187 D AdapterServiceConfig: Adding PanService
09-12 12:09:54.873  4187  4187 D AdapterServiceConfig: Adding GattService
,09-12 12:09:54.873  4187  4187 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 12:09:54.889   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@968b094:true
,09-12 12:09:54.889  4187  4187 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 12:09:54.896  4187  4187 I bt_bluedroid: init
,09-12 12:09:54.896  4187  4199 I BluetoothAdapterState: Entering OffState
,09-12 12:09:54.902  4187  4200 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 12:09:54.902  4187  4200 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 12:09:54.902  4187  4200 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 12:09:54.903  4187  4200 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 12:09:54.905  4187  4187 I bt_bluedroid: get_profile_interface socket
,09-12 12:09:54.907  4187  4187 I bt_bluedroid: get_profile_interface sdp
,09-12 12:09:54.911  4187  4203 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 12:09:54.912  4187  4198 I bt_bluedroid: config_hci_snoop_log
,09-12 12:09:54.914   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 12:09:54.914  4187  4203 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 12:09:54.924  4187  4199 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 12:09:54.924  4187  4199 D BluetoothAdapterProperties: Setting state to 14
09-12 12:09:54.925  4187  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 12:09:54.930  4187  4199 D BluetoothBondStateMachine: make
,09-12 12:09:54.934  4187  4204 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 12:09:54.945  4187  4187 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 12:09:54.945  4187  4199 I BluetoothAdapterState: Entering PendingCommandState
,09-12 12:09:54.951  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:09:54.952  4187  4187 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 12:09:54.953  4187  4187 D BtGatt.GattService: Received start request. Starting profile...
09-12 12:09:54.954  4187  4187 D BtGatt.GattService: start()
,09-12 12:09:54.954  4187  4187 I bt_bluedroid: get_profile_interface gatt
09-12 12:09:54.955  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:09:54.956  4187  4187 D BtGatt.AdvertiseManager: advertise manager created
,09-12 12:09:54.967  4187  4187 V BluetoothAdapterState: isTurningOff()=false
,09-12 12:09:54.968  4187  4187 V BluetoothAdapterState: isTurningOn()=false
,09-12 12:09:54.968  4187  4187 V BluetoothAdapterState: isBleTurningOn()=true
09-12 12:09:54.968  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:09:54.969  4187  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 12:09:54.970  4187  4199 I bt_bluedroid: enable
09-12 12:09:54.970  4187  4200 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 12:09:54.971  4187  4200 I bt_hci  : start_up
,09-12 12:09:54.993  4187  4200 I bt_vendor: alloc value 0xb39b0189
,09-12 12:09:54.994  4187  4200 I bt_vendor: init
09-12 12:09:54.994  4187  4200 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 12:09:54.994  4187  4200 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 12:09:55.100  4187  4200 D bt_hci  : start_up starting async portion,
09-12 12:09:55.101  4187  4207 I bt_hci  : event_finish_startup
09-12 12:09:55.101  4187  4207 I bt_hci_h4: hal_open
09-12 12:09:55.101  4187  4207 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 12:09:55.111  4187  4207 I bt_userial_vendor: device fd = 51 open
,09-12 12:09:55.143  4187  4207 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 12:09:55.176  4187  4207 D bt_hwcfg: Chipset BCM4354A2
,09-12 12:09:55.176  4187  4207 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 12:09:55.178  4187  4207 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 12:09:55.836  4187  4207 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 12:09:55.838  4187  4207 D bt_hwcfg: Settlement delay -- 100 ms
09-12 12:09:55.838  4187  4207 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 12:09:55.955  4187  4207 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 12:09:55.956  4187  4207 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 12:09:55.985  4187  4207 I bt_hwcfg: vendor lib fwcfg completed
09-12 12:09:55.985  4187  4207 I bt_vendor: firmware callback
09-12 12:09:55.986  4187  4207 I bt_hci  : firmware_config_callback
,09-12 12:09:55.997  4187  4209 I bt_btu  : btu_task pending for preload complete event,
09-12 12:09:55.997  4187  4209 I bt_btu_task: Bluetooth chip preload is complete
09-12 12:09:55.998  4187  4209 I bt_btu  : btu_task received preload complete event
,09-12 12:09:56.008  4187  4209 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 12:09:56.008  4187  4209 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 12:09:56.008  4187  4209 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 12:09:56.008  4187  4209 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 12:09:56.009  4187  4209 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 12:09:56.009  4187  4209 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 12:09:56.010  4187  4209 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 12:09:56.010  4187  4209 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 12:09:56.010  4187  4209 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 12:09:56.010  4187  4209 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 12:09:56.011  4187  4209 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 12:09:56.011  4187  4209 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 12:09:56.011  4187  4209 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 12:09:56.011  4187  4209 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 12:09:56.012  4187  4209 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 12:09:56.146  4187  4209 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,09-12 12:09:56.146  4187  4209 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,09-12 12:09:56.158  4187  4203 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-12 12:09:56.160  4187  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 12:09:56.161  4187  4203 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 12:09:56.165  4187  4203 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 12:09:56.169  4187  4203 D BluetoothAdapterProperties: Scan Mode:20
,09-12 12:09:56.170  4187  4203 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 12:09:56.170  4187  4203 D bt_hci  : do_postload posting postload work item
09-12 12:09:56.170  4187  4207 I bt_hci  : event_postload
,09-12 12:09:56.171  4187  4207 I bt_vendor: sco_config_cb
09-12 12:09:56.171  4187  4207 I bt_hci  : sco_config_callback postload finished.
,09-12 12:09:56.173  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:56.176  4187  4203 D bt_bte_conf: Device ID record 1 : primary
09-12 12:09:56.176  4187  4203 D bt_bte_conf:   vendorId            = 000f
,09-12 12:09:56.176  4187  4203 D bt_bte_conf:   vendorIdSource      = 0001
,09-12 12:09:56.176  4187  4203 D bt_bte_conf:   product             = 1200
,09-12 12:09:56.177  4187  4203 D bt_bte_conf:   version             = 1436
,09-12 12:09:56.177  4187  4203 D bt_bte_conf:   clientExecutableURL = 
,09-12 12:09:56.177  4187  4203 D bt_bte_conf:   serviceDescription  = 
,09-12 12:09:56.177  4187  4203 D bt_bte_conf:   documentationURL    = 
09-12 12:09:56.178  4187  4203 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 12:09:56.178  4187  4200 D bt_stack_manager: event_start_up_stack finished
09-12 12:09:56.179  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:56.180  4187  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 12:09:56.181  4187  4199 D BluetoothAdapterProperties: Setting state to 15
09-12 12:09:56.181  4187  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 12:09:56.182  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:56.182  4187  4207 I bt_vendor: low_power_mode_cb
,09-12 12:09:56.182  4187  4199 I BluetoothAdapterState: Entering BleOnState
09-12 12:09:56.185  4187  4199 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 12:09:56.185  4187  4199 D BluetoothAdapterProperties: Setting state to 11
09-12 12:09:56.186  4187  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 12:09:56.192  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:56.195  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:56.196  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
09-12 12:09:56.198  4187  4187 D HeadsetService: Received start request. Starting profile...
09-12 12:09:56.199  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:56.202  4187  4187 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 12:09:56.202  4187  4187 D HeadsetStateMachine: make
09-12 12:09:56.203  4187  4199 I BluetoothAdapterState: Entering PendingCommandState
,09-12 12:09:56.211  4187  4187 D HeadsetStateMachine: max_hf_connections = 1
,09-12 12:09:56.212  4187  4187 I bt_bluedroid: get_profile_interface handsfree
,09-12 12:09:56.212  4187  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 12:09:56.213  4187  4203 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 12:09:56.215  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:09:56.216  4187  4187 D A2dpService: Received start request. Starting profile...
,09-12 12:09:56.216  4187  4187 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 12:09:56.217  4187  4187 I bt_bluedroid: get_profile_interface avrcp
,09-12 12:09:56.224  4187  4187 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 12:09:56.224  4187  4187 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-12 12:09:56.224  4187  4187 D A2dpStateMachine: make
,09-12 12:09:56.226  4187  4187 I bt_bluedroid: get_profile_interface a2dp
,09-12 12:09:56.228  4187  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 12:09:56.228  4187  4219 D A2dpStateMachine: Enter Disconnected: -2
09-12 12:09:56.228  4187  4187 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 12:09:56.229  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:09:56.230  4187  4187 D HidService: Received start request. Starting profile...
,09-12 12:09:56.230  3948  3948 D BluetoothInputDevice: Proxy object connected
09-12 12:09:56.231  4187  4187 I bt_bluedroid: get_profile_interface hidhost
09-12 12:09:56.231  4187  4187 D HidService: setHidService(): set to: null
,09-12 12:09:56.231  4187  4203 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
09-12 12:09:56.231  4187  4187 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 12:09:56.231  4187  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 12:09:56.232  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
09-12 12:09:56.232  3948  3948 D HidProfile: Bluetooth service connected
,09-12 12:09:56.233  4187  4187 D HealthService: Received start request. Starting profile...
09-12 12:09:56.234  4187  4187 I bt_bluedroid: get_profile_interface health
,09-12 12:09:56.235  4187  4187 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-12 12:09:56.236  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:09:56.237  4187  4187 D PanService: Received start request. Starting profile...
,09-12 12:09:56.238  4187  4187 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 12:09:56.238  3948  3948 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 12:09:56.238  4187  4187 I bt_bluedroid: get_profile_interface pan
,09-12 12:09:56.238  3948  3948 D PanProfile: Bluetooth service connected
09-12 12:09:56.238  4187  4203 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 12:09:56.240  4187  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:09:56.242  3948  3948 D BluetoothMap: Proxy object connected
,09-12 12:09:56.243  4187  4187 D BluetoothMapService: Received start request. Starting profile...
,09-12 12:09:56.243  4187  4187 D BluetoothMapService: start()
,09-12 12:09:56.243  3948  3948 D MapProfile: Bluetooth service connected
09-12 12:09:56.243  3948  3948 D BluetoothMap: getConnectedDevices()
,09-12 12:09:56.244  3948  3948 D BluetoothMap: Bluetooth is Not enabled
09-12 12:09:56.245  4187  4187 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 12:09:56.246  4187  4187 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 12:09:56.246  4187  4187 D BluetoothMapAppObserver: createReceiver()
,09-12 12:09:56.247  4187  4187 D BluetoothMapAppObserver: initObservers()
09-12 12:09:56.247  4187  4187 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 12:09:56.256  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 12:09:56.258  4187  4187 V BluetoothAdapterState: isTurningOff()=false
,09-12 12:09:56.258  4187  4187 V BluetoothAdapterState: isTurningOn()=true
09-12 12:09:56.258  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:56.258  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:09:56.261  4187  4187 V BluetoothAdapterState: isTurningOff()=false
,09-12 12:09:56.261  4187  4217 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 12:09:56.261  4187  4187 V BluetoothAdapterState: isTurningOn()=true
09-12 12:09:56.261  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:09:56.261  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:56.261  4187  4187 V BluetoothAdapterState: isTurningOff()=false
09-12 12:09:56.261  4187  4187 V BluetoothAdapterState: isTurningOn()=true
09-12 12:09:56.262  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:09:56.262  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:56.262  4187  4187 V BluetoothAdapterState: isTurningOff()=false
09-12 12:09:56.262  4187  4187 V BluetoothAdapterState: isTurningOn()=true
09-12 12:09:56.262  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:09:56.262  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:56.263  4187  4187 V BluetoothAdapterState: isTurningOff()=false
09-12 12:09:56.263  4187  4187 V BluetoothAdapterState: isTurningOn()=true
09-12 12:09:56.263  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:09:56.263  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:56.263  4187  4187 V BluetoothAdapterState: isTurningOff()=false
09-12 12:09:56.264  4187  4187 V BluetoothAdapterState: isTurningOn()=true
09-12 12:09:56.264  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:09:56.264  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:56.264  4187  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-12 12:09:56.265  4187  4199 D BluetoothAdapterProperties: ScanMode =  20
,09-12 12:09:56.265  4187  4199 D BluetoothAdapterProperties: State =  11
,09-12 12:09:56.265  4187  4199 D BluetoothAdapterProperties: Setting state to 12
09-12 12:09:56.265  4187  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 12:09:56.266  4187  4199 I BluetoothAdapterState: Entering OnState
09-12 12:09:56.266  3948  3958 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 12:09:56.268  1361  1377 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 12:09:56.273  4187  4203 D BluetoothAdapterProperties: Scan Mode:21
,09-12 12:09:56.273  1361  2091 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:09:56.273  4187  4203 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 12:09:56.275   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 12:09:56.276  1361  1376 D BluetoothPan: onBluetoothStateChange on: true
,09-12 12:09:56.277  4187  4187 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 12:09:56.278  4187  4187 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 12:09:56.278  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:56.278  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:56.278  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:56.278  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:56.278  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:09:56.278  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:56.278  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:56.278  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:09:56.279  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 12:09:56.279  1361  1361 D PanProfile: Bluetooth service connected
09-12 12:09:56.279   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 12:09:56.280  1967  1982 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:09:56.280  4187  4187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 12:09:56.280  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:56.281  3948  3959 D BluetoothMap: onBluetoothStateChange: up=true
09-12 12:09:56.281  1361  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 12:09:56.291  4187  4187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:09:56.291  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:56.291  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:56.291  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:56.291  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:56.291  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:09:56.291  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:56.291  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:56.291  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:56.291  1361  1361 D BluetoothInputDevice: Proxy object connected
09-12 12:09:56.291  1361  1361 D HidProfile: Bluetooth service connected
09-12 12:09:56.291   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:09:56.291   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 12:09:56.292  3948  3958 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 12:09:56.293  4187  4187 D ObexServerSockets: Succeed to create listening sockets 
,09-12 12:09:56.293  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:56.293  4187  4187 D ObexServerSockets0: startAccept()
,09-12 12:09:56.294  4187  4187 D ObexServerSockets0: prepareForNewConnect()
,09-12 12:09:56.298  1361  1377 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 12:09:56.299  4187  4187 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 12:09:56.299  4187  4187 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-12 12:09:56.300  4187  4225 D ObexServerSockets0: Accepting socket connection...
,09-12 12:09:56.300  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:56.300  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:56.300  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:56.300  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:56.300  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:09:56.300  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:56.300  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:56.300  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:09:56.301   872   872 D BluetoothA2dp: Proxy object connected
,09-12 12:09:56.301  1361  1361 D BluetoothMap: Proxy object connected
09-12 12:09:56.301  1361  1361 D MapProfile: Bluetooth service connected
09-12 12:09:56.301  1361  1361 D BluetoothMap: getConnectedDevices()
,09-12 12:09:56.302  3948  3959 D BluetoothPan: onBluetoothStateChange on: true
09-12 12:09:56.303  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:09:56.304  1361  2091 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 12:09:56.304  4187  4226 D ObexServerSockets0: Accepting socket connection...
,09-12 12:09:56.306  1361  1361 D BluetoothA2dp: Proxy object connected
09-12 12:09:56.307   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 12:09:56.309  4187  4187 D BluetoothMapService: onReceive
,09-12 12:09:56.309  4187  4187 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 12:09:56.309  4187  4187 D BluetoothMapService: STATE_ON
09-12 12:09:56.310  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:56.311  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:56.312  3948  3948 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 12:09:56.313  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:56.320  3948  3948 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 12:09:56.329  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 12:09:56.330  4187  4187 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 12:09:56.330  4187  4187 D ObexServerSockets0: prepareForNewConnect()
09-12 12:09:56.332  3948  3948 D BluetoothA2dp: Proxy object connected
,09-12 12:09:56.337  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 12:09:56.345  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,09-12 12:09:56.345  1361  1361 D BluetoothPbap: Proxy object connected
09-12 12:09:56.345  1361  1361 D PbapServerProfile: Bluetooth service connected
09-12 12:09:56.346  3948  3948 D BluetoothPbap: Proxy object connected
09-12 12:09:56.347  3948  3948 D PbapServerProfile: Bluetooth service connected
,09-12 12:09:56.355  4187  4230 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:09:56.371  4187  4234 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:09:56.372  4187  4234 I BtOppRfcommListener: Accept thread started.
,09-12 12:09:56.375  1967  2131 D BluetoothHeadset: Proxy object connected
,09-12 12:09:56.375   872   872 D BluetoothHeadset: Proxy object connected
09-12 12:09:56.375   872   889 D BluetoothHeadset: Proxy object connected
,09-12 12:09:56.375  1361  2091 D BluetoothHeadset: Proxy object connected
09-12 12:09:56.376  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-12 12:09:56.376   872   872 D BluetoothHeadset: Proxy object connected
09-12 12:09:56.376   872   872 D BluetoothHeadset: Proxy object connected
,09-12 12:09:56.381  1967  2310 D BluetoothHeadset: Proxy object connected
,09-12 12:09:56.391   872   889 D BluetoothHeadset: Proxy object connected
,09-12 12:09:56.392   872   889 D BluetoothHeadset: Proxy object connected
,09-12 12:09:56.424  3948  3959 D BluetoothHeadset: Proxy object connected
,09-12 12:09:56.425  3948  3948 D HeadsetProfile: Bluetooth service connected
,09-12 12:09:59.711  4187  4199 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 12:09:59.711  4187  4199 D BluetoothAdapterProperties: Setting state to 13
09-12 12:09:59.711  4187  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 12:09:59.713  4187  4199 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 12:09:59.719  4187  4199 I BluetoothAdapterState: Entering PendingCommandState
,09-12 12:09:59.721  4187  4203 D BluetoothAdapterProperties: Scan Mode:20
,09-12 12:09:59.722  4187  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 12:09:59.730  4187  4187 D BluetoothMapService: onReceive
09-12 12:09:59.731  4187  4187 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 12:09:59.731  4187  4187 D BluetoothMapService: STATE_TURNING_OFF
,09-12 12:09:59.732  4187  4187 D BluetoothMapService: MAP Service closeService in
,09-12 12:09:59.732  4187  4187 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 12:09:59.732  4187  4187 D ObexServerSockets0: shutdown(block = true)
09-12 12:09:59.735  4187  4225 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 12:09:59.737  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:59.738  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:59.738  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:59.738  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:59.738  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:59.738  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:59.738  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:59.738  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:59.738  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:59.741  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:59.741  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:09:59.743  4187  4187 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 12:09:59.743  4187  4187 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 12:09:59.743  4187  4211 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 12:09:59.743  4187  4226 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 12:09:59.744  4187  4187 I BtOppRfcommListener: stopping Accept Thread
09-12 12:09:59.744  4187  4234 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 12:09:59.744  4187  4234 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 12:09:59.747  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:59.747  4187  4187 D HeadsetService: Received stop request...Stopping profile...
,09-12 12:09:59.747  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:59.747  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:59.747  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:59.747  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:59.747  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:59.747  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:59.747  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:59.747  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:09:59.748  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:59.748  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:09:59.748  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 12:09:59.749  1967  1982 D BluetoothHeadset: Proxy object disconnected
09-12 12:09:59.749   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 12:09:59.750  4187  4187 D A2dpService: Received stop request...Stopping profile...
09-12 12:09:59.750  4187  4219 D A2dpStateMachine: Exit Disconnected: -1
09-12 12:09:59.750  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 12:09:59.750  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:09:59.750  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:09:59.750  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:09:59.750  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:09:59.750  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 12:09:59.750  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:09:59.750  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:09:59.750  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:09:59.751  3862  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 12:09:59.751  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:09:59.752  3948  3958 D BluetoothHeadset: Proxy object disconnected
09-12 12:09:59.752  1361  2091 D BluetoothHeadset: Proxy object disconnected
,09-12 12:09:59.752   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 12:09:59.752   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 12:09:59.754   872   872 D BluetoothA2dp: Proxy object disconnected
,09-12 12:09:59.755  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:59.755  1361  1361 D HeadsetProfile: Bluetooth service disconnected
09-12 12:09:59.756  1361  1361 D BluetoothA2dp: Proxy object disconnected
09-12 12:09:59.757  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:59.757  4187  4187 D HidService: Received stop request...Stopping profile...
,09-12 12:09:59.757  4187  4187 D HidService: Stopping Bluetooth HidService
09-12 12:09:59.758  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-12 12:09:59.758  1361  1361 D HidProfile: Bluetooth service disconnected
,09-12 12:09:59.759  3948  3948 D DockEventReceiver: finishStartingService: stopping service
09-12 12:09:59.759  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:59.760  4187  4187 V BluetoothAdapterState: isTurningOff()=true
,09-12 12:09:59.760  3948  3948 D HeadsetProfile: Bluetooth service disconnected
,09-12 12:09:59.760  4187  4187 V BluetoothAdapterState: isTurningOn()=false
,09-12 12:09:59.760  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:59.760  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:09:59.760  3948  3948 D BluetoothA2dp: Proxy object disconnected
,09-12 12:09:59.760  4187  4187 D HealthService: Received stop request...Stopping profile...
09-12 12:09:59.764  4187  4187 D PanService: Received stop request...Stopping profile...
,09-12 12:09:59.765  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 12:09:59.765  3948  3948 D BluetoothInputDevice: Proxy object disconnected
09-12 12:09:59.765  1361  1361 D PanProfile: Bluetooth service disconnected
,09-12 12:09:59.765  3948  3948 D HidProfile: Bluetooth service disconnected
,09-12 12:09:59.765  3948  3948 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 12:09:59.765  3948  3948 D PanProfile: Bluetooth service disconnected
09-12 12:09:59.766  4187  4187 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 12:09:59.766  4187  4187 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 12:09:59.766  4187  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 12:09:59.766  4187  4209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:59.766  4187  4209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 12:09:59.767  4187  4209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:59.767  4187  4203 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 12:09:59.768  4187  4187 D BluetoothMapService: Received stop request...Stopping profile...
09-12 12:09:59.768  4187  4187 D BluetoothMapService: stop()
09-12 12:09:59.768  4187  4187 D BluetoothMapAppObserver: deinitObservers()
09-12 12:09:59.768  4187  4187 D BluetoothMapAppObserver: removeReceiver()
,09-12 12:09:59.770  1361  1361 D BluetoothMap: Proxy object disconnected
09-12 12:09:59.770  1361  1361 D MapProfile: Bluetooth service disconnected
09-12 12:09:59.770  4187  4187 V BluetoothAdapterState: isTurningOff()=true
09-12 12:09:59.770  4187  4187 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:59.771  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:09:59.771  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:59.772  3948  3948 D BluetoothMap: Proxy object disconnected
09-12 12:09:59.772  3948  3948 D MapProfile: Bluetooth service disconnected
09-12 12:09:59.773  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 12:09:59.774  4187  4187 V BluetoothAdapterState: isTurningOff()=true
,09-12 12:09:59.774  4187  4187 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:59.774  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:59.774  4187  4209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:59.774  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:09:59.775  4187  4209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:59.775  4187  4187 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 12:09:59.775  4187  4209 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 12:09:59.775  4187  4187 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 12:09:59.775  4187  4209 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 12:09:59.775  4187  4209 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 12:09:59.775  4187  4209 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 12:09:59.775  4187  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 12:09:59.775  4187  4187 V BluetoothAdapterState: isTurningOff()=true
,09-12 12:09:59.775  4187  4187 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:59.775  4187  4203 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 12:09:59.775  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 12:09:59.775  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:09:59.776  4187  4187 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 12:09:59.776  4187  4203 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 12:09:59.776  4187  4187 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 12:09:59.776  4187  4187 V BluetoothAdapterState: isTurningOff()=true
09-12 12:09:59.776  4187  4187 V BluetoothAdapterState: isTurningOn()=false
,09-12 12:09:59.776  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:59.777  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:59.777  4187  4187 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 12:09:59.778  4187  4187 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 12:09:59.778  4187  4187 D BluetoothMapService: MAP Service closeService in
09-12 12:09:59.778  4187  4187 V BluetoothAdapterState: isTurningOff()=true
,09-12 12:09:59.778  4187  4187 V BluetoothAdapterState: isTurningOn()=false
09-12 12:09:59.778  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:09:59.779  4187  4187 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:09:59.779  4187  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 12:09:59.779  4187  4199 D BluetoothAdapterProperties: Setting state to 15
09-12 12:09:59.779  4187  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 12:09:59.780  4187  4199 I BluetoothAdapterState: Entering BleOnState
09-12 12:09:59.780  4187  4187 D BluetoothMapService: cleanup()
,09-12 12:09:59.780  4187  4187 D BluetoothMapService: MAP Service closeService in
09-12 12:09:59.780  3948  3958 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 12:09:59.781  1361  2091 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 12:09:59.781  1361  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:09:59.782   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:09:59.782  1361  1377 D BluetoothPan: onBluetoothStateChange on: false
09-12 12:09:59.782   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 12:09:59.783  1967  2131 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 12:09:59.783  3948  3959 D BluetoothMap: onBluetoothStateChange: up=false
09-12 12:09:59.784  1361  2091 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 12:09:59.785   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:09:59.785  3948  4239 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 12:09:59.785   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:09:59.785  3948  3958 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 12:09:59.786  1361  1376 D BluetoothMap: onBluetoothStateChange: up=false
09-12 12:09:59.786  3948  3959 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 12:09:59.787  3948  4239 D BluetoothPan: onBluetoothStateChange on: false
09-12 12:09:59.787  1361  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 12:09:59.788  4187  4199 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 12:09:59.788  4187  4199 D BluetoothAdapterProperties: Setting state to 16
,09-12 12:09:59.788  4187  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 12:09:59.788  4187  4199 D BluetoothAdapterProperties: onBleDisable
09-12 12:09:59.788  3948  3948 D BluetoothPbap: Proxy object disconnected
09-12 12:09:59.788  3948  3948 D PbapServerProfile: Bluetooth service disconnected
09-12 12:09:59.789  4187  4199 I BluetoothAdapterState: Entering PendingCommandState
09-12 12:09:59.789  4187  4200 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-12 12:09:59.790  4187  4209 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 12:09:59.790  4187  4209 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 12:09:59.791  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:59.792  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:59.792  4187  4203 D BluetoothAdapterProperties: Scan Mode:20
,09-12 12:09:59.793  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:59.793  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 12:09:59.795  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:09:59.797  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:59.798  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:09:59.798  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 12:09:59.817  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,09-12 12:09:59.994  4187  4203 I bt_hci  : shut_down
,09-12 12:09:59.995  4187  4207 D bt_hwcfg: hw_epilog_process
,09-12 12:09:59.997  4187  4207 I bt_vendor: low_power_mode_cb
,09-12 12:10:00.016  4187  4207 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 12:10:00.016  4187  4207 I bt_vendor: epilog_cb
09-12 12:10:00.017  4187  4207 I bt_hci  : epilog_finished_callback
,09-12 12:10:00.024  4187  4203 I bt_hci_h4: hal_close
,09-12 12:10:00.026  4187  4203 I bt_userial_vendor: device fd = 51 close
,09-12 12:10:00.151  4187  4200 D bt_stack_manager: event_shut_down_stack finished.
,09-12 12:10:00.153  4187  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 12:10:00.159  4187  4199 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 12:10:00.159  4187  4187 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 12:10:00.161  4187  4187 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 12:10:00.161  4187  4187 D BtGatt.GattService: stop()
09-12 12:10:00.161  4187  4187 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 12:10:00.166  4187  4187 V BluetoothAdapterState: isTurningOff()=false
,09-12 12:10:00.167  4187  4187 V BluetoothAdapterState: isTurningOn()=false
09-12 12:10:00.167  4187  4187 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:10:00.167  4187  4187 V BluetoothAdapterState: isBleTurningOff()=true
09-12 12:10:00.168  4187  4199 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 12:10:00.169  4187  4199 D BluetoothAdapterProperties: Setting state to 10
,09-12 12:10:00.169  4187  4199 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 12:10:00.170  4187  4199 I BluetoothAdapterState: Entering OffState
,09-12 12:10:00.172   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 12:10:00.196  4187  4187 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 12:10:00.201  4187  4187 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 12:10:00.202  4187  4200 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 12:10:00.208  4187  4187 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 12:10:00.214  4187  4200 D bt_stack_manager: event_clean_up_stack finished.
,09-12 12:10:00.220  4187  4187 I art     : System.exit called, status: 0
09-12 12:10:00.220  4187  4187 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 12:10:00.261   872  1687 I ActivityManager: Process com.android.bluetooth (pid 4187) has died
,09-12 12:10:04.708  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:10:04.709  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:04.715  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:10:04.715  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b5f602 removed from the list
,09-12 12:10:04.716  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:10:04.716  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:04.716  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:04.722  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 12:10:04.723  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9bf3150 added. We now have 4 listener(s)
09-12 12:10:04.723  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:10:04.725  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:04.725  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9bf3150 removed from the list
09-12 12:10:04.725  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:10:04.726  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:04.726  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:04.728  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:10:04.729  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b4e8f49 added. We now have 4 listener(s)
,09-12 12:10:04.729  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:10:09.741  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:09.788   872   889 I ActivityManager: Start proc 4246:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 12:10:09.937  4246  4246 D AdapterServiceConfig: Adding HeadsetService
09-12 12:10:09.937  4246  4246 D AdapterServiceConfig: Adding A2dpService
,09-12 12:10:09.938  4246  4246 D AdapterServiceConfig: Adding HidService
09-12 12:10:09.938  4246  4246 D AdapterServiceConfig: Adding HealthService
09-12 12:10:09.938  4246  4246 D AdapterServiceConfig: Adding PanService
09-12 12:10:09.938  4246  4246 D AdapterServiceConfig: Adding GattService
09-12 12:10:09.938  4246  4246 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 12:10:09.952   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c931c1:true
,09-12 12:10:09.953  4246  4246 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 12:10:09.962  4246  4246 I bt_bluedroid: init,
09-12 12:10:09.963  4246  4258 I BluetoothAdapterState: Entering OffState
,09-12 12:10:09.966  4246  4259 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 12:10:09.966  4246  4259 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 12:10:09.966  4246  4259 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 12:10:09.966  4246  4259 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 12:10:09.967  4246  4246 I bt_bluedroid: get_profile_interface socket
,09-12 12:10:09.970  4246  4246 I bt_bluedroid: get_profile_interface sdp
,09-12 12:10:09.973  4246  4262 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 12:10:09.974  4246  4257 I bt_bluedroid: config_hci_snoop_log
,09-12 12:10:09.978   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-12 12:10:09.978  4246  4262 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 12:10:09.990  4246  4258 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 12:10:09.991  4246  4258 D BluetoothAdapterProperties: Setting state to 14
09-12 12:10:09.991  4246  4258 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 12:10:09.995  4246  4258 D BluetoothBondStateMachine: make
,09-12 12:10:09.999  4246  4263 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 12:10:10.004  4246  4258 I BluetoothAdapterState: Entering PendingCommandState
,09-12 12:10:10.009  4246  4246 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 12:10:10.017  4246  4246 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:10:10.018  4246  4246 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 12:10:10.020  4246  4246 D BtGatt.GattService: Received start request. Starting profile...
,09-12 12:10:10.020  4246  4246 D BtGatt.GattService: start()
09-12 12:10:10.020  4246  4246 I bt_bluedroid: get_profile_interface gatt
,09-12 12:10:10.022  4246  4246 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
09-12 12:10:10.022  4246  4246 D BtGatt.AdvertiseManager: advertise manager created
,09-12 12:10:10.032  4246  4246 V BluetoothAdapterState: isTurningOff()=false
09-12 12:10:10.032  4246  4246 V BluetoothAdapterState: isTurningOn()=false
,09-12 12:10:10.033  4246  4246 V BluetoothAdapterState: isBleTurningOn()=true
09-12 12:10:10.033  4246  4246 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:10:10.034  4246  4258 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-12 12:10:10.034  4246  4258 I bt_bluedroid: enable
09-12 12:10:10.035  4246  4259 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 12:10:10.035  4246  4259 I bt_hci  : start_up
,09-12 12:10:10.044  4246  4259 I bt_vendor: alloc value 0xb39b0189
09-12 12:10:10.044  4246  4259 I bt_vendor: init
09-12 12:10:10.044  4246  4259 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 12:10:10.044  4246  4259 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 12:10:10.153  4246  4259 D bt_hci  : start_up starting async portion
09-12 12:10:10.154  4246  4266 I bt_hci  : event_finish_startup
,09-12 12:10:10.154  4246  4266 I bt_hci_h4: hal_open
09-12 12:10:10.154  4246  4266 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 12:10:10.164  4246  4266 I bt_userial_vendor: device fd = 51 open
,09-12 12:10:10.195  4246  4266 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 12:10:10.226  4246  4266 D bt_hwcfg: Chipset BCM4354A2
,09-12 12:10:10.226  4246  4266 D bt_hwcfg: Target name = [BCM4354A2]
09-12 12:10:10.228  4246  4266 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 12:10:11.083  4246  4266 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 12:10:11.086  4246  4266 D bt_hwcfg: Settlement delay -- 100 ms
09-12 12:10:11.086  4246  4266 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 12:10:11.204  4246  4266 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 12:10:11.206  4246  4266 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 12:10:11.233  4246  4266 I bt_hwcfg: vendor lib fwcfg completed
09-12 12:10:11.234  4246  4266 I bt_vendor: firmware callback
,09-12 12:10:11.234  4246  4266 I bt_hci  : firmware_config_callback
,09-12 12:10:11.246  4246  4268 I bt_btu  : btu_task pending for preload complete event
,09-12 12:10:11.247  4246  4268 I bt_btu_task: Bluetooth chip preload is complete
09-12 12:10:11.247  4246  4268 I bt_btu  : btu_task received preload complete event
,09-12 12:10:11.256  4246  4268 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 12:10:11.257  4246  4268 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 12:10:11.257  4246  4268 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 12:10:11.257  4246  4268 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 12:10:11.258  4246  4268 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 12:10:11.258  4246  4268 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 12:10:11.258  4246  4268 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 12:10:11.258  4246  4268 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 12:10:11.259  4246  4268 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 12:10:11.259  4246  4268 I         : BTE_InitTraceLevels -- TRC_PAN
,09-12 12:10:11.260  4246  4268 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 12:10:11.260  4246  4268 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 12:10:11.261  4246  4268 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 12:10:11.261  4246  4268 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 12:10:11.262  4246  4268 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 12:10:11.413  4246  4268 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,09-12 12:10:11.414  4246  4268 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,09-12 12:10:11.427  4246  4262 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 12:10:11.430  4246  4262 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 12:10:11.430  4246  4262 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 12:10:11.433  4246  4262 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 12:10:11.440  4246  4262 D BluetoothAdapterProperties: Scan Mode:20
,09-12 12:10:11.441  4246  4262 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 12:10:11.443  4246  4262 D bt_hci  : do_postload posting postload work item
,09-12 12:10:11.443  4246  4266 I bt_hci  : event_postload
09-12 12:10:11.444  4246  4266 I bt_vendor: sco_config_cb
09-12 12:10:11.444  4246  4266 I bt_hci  : sco_config_callback postload finished.
09-12 12:10:11.444  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:10:11.448  4246  4262 D bt_bte_conf: Device ID record 1 : primary
09-12 12:10:11.448  4246  4262 D bt_bte_conf:   vendorId            = 000f
09-12 12:10:11.448  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:10:11.449  4246  4262 D bt_bte_conf:   vendorIdSource      = 0001
09-12 12:10:11.449  4246  4262 D bt_bte_conf:   product             = 1200
09-12 12:10:11.449  4246  4262 D bt_bte_conf:   version             = 1436
09-12 12:10:11.449  4246  4262 D bt_bte_conf:   clientExecutableURL = 
09-12 12:10:11.449  4246  4262 D bt_bte_conf:   serviceDescription  = 
09-12 12:10:11.450  4246  4262 D bt_bte_conf:   documentationURL    = 
09-12 12:10:11.450  4246  4262 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 12:10:11.450  4246  4259 D bt_stack_manager: event_start_up_stack finished
09-12 12:10:11.451  4246  4258 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 12:10:11.452  4246  4258 D BluetoothAdapterProperties: Setting state to 15
09-12 12:10:11.452  4246  4258 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 12:10:11.454  4246  4266 I bt_vendor: low_power_mode_cb
09-12 12:10:11.454  4246  4258 I BluetoothAdapterState: Entering BleOnState
,09-12 12:10:11.460  4246  4258 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 12:10:11.460  4246  4258 D BluetoothAdapterProperties: Setting state to 11
09-12 12:10:11.460  4246  4258 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 12:10:11.465  4246  4246 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:10:11.466  4246  4246 D HeadsetService: Received start request. Starting profile...
,09-12 12:10:11.469  4246  4246 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 12:10:11.469  4246  4246 D HeadsetStateMachine: make
,09-12 12:10:11.477  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:11.480  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:11.483  4246  4246 D HeadsetStateMachine: max_hf_connections = 1
,09-12 12:10:11.483  4246  4246 I bt_bluedroid: get_profile_interface handsfree
09-12 12:10:11.487  4246  4262 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 12:10:11.487  4246  4262 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 12:10:11.491  4246  4246 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
09-12 12:10:11.491  4246  4246 D A2dpService: Received start request. Starting profile...
09-12 12:10:11.492  4246  4246 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 12:10:11.493  4246  4246 I bt_bluedroid: get_profile_interface avrcp
09-12 12:10:11.494  4246  4258 I BluetoothAdapterState: Entering PendingCommandState
,09-12 12:10:11.500  4246  4246 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 12:10:11.500  4246  4246 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 12:10:11.501  4246  4246 D A2dpStateMachine: make
,09-12 12:10:11.502  4246  4246 I bt_bluedroid: get_profile_interface a2dp
,09-12 12:10:11.504  4246  4262 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 12:10:11.506  4246  4277 D A2dpStateMachine: Enter Disconnected: -2
,09-12 12:10:11.508  4246  4246 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 12:10:11.510  4246  4246 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:10:11.510  4246  4246 D HidService: Received start request. Starting profile...
09-12 12:10:11.511  4246  4246 I bt_bluedroid: get_profile_interface hidhost
09-12 12:10:11.511  4246  4246 D HidService: setHidService(): set to: null
09-12 12:10:11.511  4246  4262 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
09-12 12:10:11.511  4246  4262 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 12:10:11.515  4246  4246 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 12:10:11.516  4246  4246 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
09-12 12:10:11.517  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 12:10:11.517  4246  4246 D HealthService: Received start request. Starting profile...
,09-12 12:10:11.519  4246  4246 I bt_bluedroid: get_profile_interface health
09-12 12:10:11.520  4246  4246 V BluetoothAdapterState: isTurningOff()=false
09-12 12:10:11.520  4246  4246 V BluetoothAdapterState: isTurningOn()=true
09-12 12:10:11.520  4246  4246 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:10:11.520  4246  4246 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:10:11.521  4246  4274 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 12:10:11.523  4246  4246 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 12:10:11.524  4246  4246 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
09-12 12:10:11.524  4246  4246 D PanService: Received start request. Starting profile...
09-12 12:10:11.524  4246  4246 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 12:10:11.524  4246  4246 I bt_bluedroid: get_profile_interface pan
09-12 12:10:11.525  4246  4262 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 12:10:11.531  4246  4246 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:10:11.533  4246  4246 D BluetoothMapService: Received start request. Starting profile...
09-12 12:10:11.533  4246  4246 D BluetoothMapService: start()
,09-12 12:10:11.535  4246  4246 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 12:10:11.536  4246  4246 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 12:10:11.536  4246  4246 D BluetoothMapAppObserver: createReceiver()
09-12 12:10:11.537  4246  4246 D BluetoothMapAppObserver: initObservers()
09-12 12:10:11.537  4246  4246 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 12:10:11.542  4246  4246 V BluetoothAdapterState: isTurningOff()=false
09-12 12:10:11.542  4246  4246 V BluetoothAdapterState: isTurningOn()=true
09-12 12:10:11.542  4246  4246 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:10:11.543  4246  4246 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:10:11.543  4246  4246 V BluetoothAdapterState: isTurningOff()=false
09-12 12:10:11.543  4246  4246 V BluetoothAdapterState: isTurningOn()=true
09-12 12:10:11.543  4246  4246 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:10:11.543  4246  4246 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:10:11.543  4246  4246 V BluetoothAdapterState: isTurningOff()=false
09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isTurningOn()=true
09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isTurningOff()=false
09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isTurningOn()=true
,09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isTurningOff()=false
09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isTurningOn()=true
,09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isBleTurningOn()=false
09-12 12:10:11.544  4246  4246 V BluetoothAdapterState: isBleTurningOff()=false
09-12 12:10:11.545  4246  4258 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 12:10:11.545  4246  4258 D BluetoothAdapterProperties: ScanMode =  20
09-12 12:10:11.545  4246  4258 D BluetoothAdapterProperties: State =  11
,09-12 12:10:11.545  4246  4258 D BluetoothAdapterProperties: Setting state to 12
09-12 12:10:11.545  4246  4258 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 12:10:11.546  4246  4262 D BluetoothAdapterProperties: Scan Mode:21
09-12 12:10:11.547  4246  4262 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 12:10:11.547  4246  4258 I BluetoothAdapterState: Entering OnState
09-12 12:10:11.547  3948  3959 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 12:10:11.549  1361  1376 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 12:10:11.550  3948  3948 D BluetoothInputDevice: Proxy object connected
09-12 12:10:11.550  3948  3948 D HidProfile: Bluetooth service connected
09-12 12:10:11.550  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:10:11.550  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:11.550  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:11.550  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:10:11.550  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:11.550  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:10:11.550  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:10:11.550  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:10:11.551  1361  2091 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:10:11.552   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 12:10:11.552  1361  1377 D BluetoothPan: onBluetoothStateChange on: true
09-12 12:10:11.552  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:10:11.555  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 12:10:11.555   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 12:10:11.555  1361  1361 D PanProfile: Bluetooth service connected
09-12 12:10:11.556  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:10:11.556  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:11.556  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:11.556  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:10:11.556  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:11.556  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:10:11.556  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:10:11.556  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 12:10:11.556  1967  1982 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:10:11.557   872   872 D BluetoothA2dp: Proxy object connected
09-12 12:10:11.557  3948  3958 D BluetoothMap: onBluetoothStateChange: up=true
09-12 12:10:11.559  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 12:10:11.559  3948  3948 D BluetoothMap: Proxy object connected
,09-12 12:10:11.559  3948  3948 D MapProfile: Bluetooth service connected
09-12 12:10:11.559  1361  2091 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 12:10:11.559  3948  3948 D BluetoothMap: getConnectedDevices()
09-12 12:10:11.561  1361  1361 D BluetoothInputDevice: Proxy object connected
09-12 12:10:11.561  1361  1361 D HidProfile: Bluetooth service connected
09-12 12:10:11.561   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:10:11.562  3948  3958 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 12:10:11.563  4246  4246 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 12:10:11.563  4246  4246 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 12:10:11.563   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:10:11.564  3948  4239 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 12:10:11.564  4246  4246 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 12:10:11.566  3948  3948 D BluetoothA2dp: Proxy object connected
09-12 12:10:11.566  1361  1376 D BluetoothMap: onBluetoothStateChange: up=true
09-12 12:10:11.566  4246  4246 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 12:10:11.568  4246  4246 D ObexServerSockets: Succeed to create listening sockets 
09-12 12:10:11.568  1361  1361 D BluetoothMap: Proxy object connected
09-12 12:10:11.568  4246  4246 D ObexServerSockets0: startAccept()
,09-12 12:10:11.568  4246  4246 D ObexServerSockets0: prepareForNewConnect()
09-12 12:10:11.568  1361  1361 D MapProfile: Bluetooth service connected
09-12 12:10:11.568  1361  1361 D BluetoothMap: getConnectedDevices()
09-12 12:10:11.568  3948  3959 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 12:10:11.569  3948  3958 D BluetoothPan: onBluetoothStateChange on: true
09-12 12:10:11.569  4246  4246 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 12:10:11.570  4246  4246 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 12:10:11.570  4246  4283 D ObexServerSockets0: Accepting socket connection...
09-12 12:10:11.571  4246  4284 D ObexServerSockets0: Accepting socket connection...
09-12 12:10:11.571  1361  2091 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 12:10:11.573  1361  1361 D BluetoothA2dp: Proxy object connected
,09-12 12:10:11.574   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 12:10:11.574  4246  4246 D BluetoothMapService: onReceive
09-12 12:10:11.574  4246  4246 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 12:10:11.574  4246  4246 D BluetoothMapService: STATE_ON
09-12 12:10:11.573  3948  3948 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 12:10:11.575  3948  3948 D PanProfile: Bluetooth service connected
09-12 12:10:11.576  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:10:11.577  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:11.582  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 12:10:11.588  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 12:10:11.589  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,09-12 12:10:11.594  3948  3948 D BluetoothPbap: Proxy object connected
09-12 12:10:11.594  3948  3948 D PbapServerProfile: Bluetooth service connected
,09-12 12:10:11.599  1361  1361 D BluetoothPbap: Proxy object connected
,09-12 12:10:11.599  1361  1361 D PbapServerProfile: Bluetooth service connected
,09-12 12:10:11.599  4246  4246 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 12:10:11.599  4246  4246 D ObexServerSockets0: prepareForNewConnect()
09-12 12:10:11.601  4246  4290 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:10:11.636  4246  4294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:10:11.637  4246  4294 I BtOppRfcommListener: Accept thread started.
,09-12 12:10:11.654  1967  2131 D BluetoothHeadset: Proxy object connected
,09-12 12:10:11.654   872   872 D BluetoothHeadset: Proxy object connected
,09-12 12:10:11.655  3948  4239 D BluetoothHeadset: Proxy object connected
09-12 12:10:11.656  3948  3948 D HeadsetProfile: Bluetooth service connected
09-12 12:10:11.656  1361  1376 D BluetoothHeadset: Proxy object connected
09-12 12:10:11.656   872   872 D BluetoothHeadset: Proxy object connected
09-12 12:10:11.656   872   872 D BluetoothHeadset: Proxy object connected
09-12 12:10:11.656  1967  2310 D BluetoothHeadset: Proxy object connected
09-12 12:10:11.656  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-12 12:10:11.662   872   889 D BluetoothHeadset: Proxy object connected
,09-12 12:10:11.664   872   889 D BluetoothHeadset: Proxy object connected
,09-12 12:10:11.668  3948  3958 D BluetoothHeadset: Proxy object connected
,09-12 12:10:11.669  3948  3948 D HeadsetProfile: Bluetooth service connected
,09-12 12:10:12.096  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:10:12.108  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:10:12.111  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:10:12.177  1502  2997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 12:10:12.178  1502  2997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 12:10:12.178  1502  2997 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:10:12.178  1502  2997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:10:12.230  3575  3575 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 12:10:12.231  3575  3575 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 12:10:12.233  3575  3575 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 12:10:14.761  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:10:14.761  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:14.761  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:14.761  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 12:10:14.761  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:14.761  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:10:14.761  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:10:14.761  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:10:14.769  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:10:14.770  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:10:14.795  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b4e8f49 removed from the list
,09-12 12:10:14.795  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:10:14.795  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:14.795  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:14.797  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:10:14.798  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b91704e added. We now have 4 listener(s)
09-12 12:10:14.798  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:10:14.801   872  2165 D WifiService: setWifiEnabled: false pid=3862, uid=10000
,09-12 12:10:14.801   872  2165 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:10:19.813  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:19.814   872  1997 D WifiService: setWifiEnabled: true pid=3862, uid=10000
09-12 12:10:19.814   872  1997 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 12:10:19.832   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-12 12:10:19.851  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:10:19.851  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:19.851  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:19.851  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:19.851  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:19.851  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:10:19.851  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:10:19.851  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:10:19.858  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:10:19.870  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:10:19.870  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:19.870  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:19.870  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:19.870  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:19.870  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 12:10:19.870  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 12:10:19.870  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 12:10:19.876  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 12:10:19.883   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-12 12:10:19.885   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 12:10:19.888   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 12:10:19.891   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 12:10:19.892   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 12:10:19.893   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 12:10:19.893   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 12:10:19.907   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 12:10:19.908   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 12:10:19.909   373   871 D CommandListener: Setting iface cfg
,09-12 12:10:19.959   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-12 12:10:19.960   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 12:10:19.966   872  1307 E native  : do suspend true
,09-12 12:10:19.970   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 12:10:19.986   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 12:10:20.008   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:10:21.326   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 12:10:22.904   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.19 rxSuccessRate=5.91 delta 1000 -> 994
,09-12 12:10:22.915   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 12:10:22.915   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:10:22.938   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 12:10:22.993   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 12:10:22.995  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 12:10:23.432  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 12:10:23.471  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 12:10:23.471  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 12:10:23.481   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 12:10:23.495   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 12:10:23.496   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 12:10:23.496   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
,09-12 12:10:23.527   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 12:10:23.548   373   871 D CommandListener: Setting iface cfg
09-12 12:10:23.549   872  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 12:10:23.565   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 12:10:23.599   872  4305 D DhcpClient: Receive thread started
,09-12 12:10:23.698   872  1307 E native  : do suspend false
,09-12 12:10:23.721   872  1892 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 12:10:23.735   872  4305 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172762, domain null
,09-12 12:10:23.737   872  1892 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172762 seconds
,09-12 12:10:23.745   872  1892 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 12:10:23.757   872  4305 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 12:10:23.758   872  1892 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 12:10:23.767   373   871 D CommandListener: Setting iface cfg
,09-12 12:10:23.776   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 12:10:23.778   872  1307 E native  : do suspend true
,09-12 12:10:23.779   872  1892 D DhcpClient: Scheduling renewal in 86399s
,09-12 12:10:23.795   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 12:10:23.797   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled,
,09-12 12:10:23.799   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 12:10:23.801   872  1309 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 12:10:23.808   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 12:10:23.877   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 12:10:23.877   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 12:10:23.881   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 12:10:23.883   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 12:10:23.887   872  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 12:10:23.907   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 12:10:23.920   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-12 12:10:23.921   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 12:10:23.921   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 12:10:23.921   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 12:10:23.921   872  1309 D ConnectivityService:    accepting network in place of null
,09-12 12:10:23.923   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 12:10:23.924   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 12:10:23.937   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=207110, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:10:23.969   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:10:24.010   872  4303 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-12 12:10:24.028   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 12:10:24.035   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-12 12:10:24.035   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:10:24.043   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102],
09-12 12:10:24.044   872   889 D Tethering: MasterInitialState.processMessage what=3
09-12 12:10:24.055  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:10:24.055  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:24.055  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:24.055  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:24.055  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:24.055  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:10:24.055  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:10:24.055  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:10:24.061  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:10:24.068  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:10:24.068  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:24.068  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:24.068  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:24.068  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:24.068  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:10:24.068  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:10:24.068  3862  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:10:24.071  3862  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:10:24.074  2070  2070 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-12 12:10:24.078  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 12:10:24.084  1697  1697 D SystemUpdateService: onCreate
,09-12 12:10:24.087   872  4303 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 10:10:24 GMT], X-Android-Received-Millis=[1473675024087], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473675024054]}
,09-12 12:10:24.089   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 12:10:24.089   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 12:10:24.089   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 12:10:24.091  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-12 12:10:24.092   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 12:10:24.112  1697  4315 I SystemUpdateService: active receiver: enabled
,09-12 12:10:24.115  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 12:10:24.118  1697  2460 I iu.UploadsManager: num queued entries: 0
09-12 12:10:24.118  1697  2460 I iu.UploadsManager: num updated entries: 0
,09-12 12:10:24.118  1697  2460 I iu.SyncManager: NEXT; no task
,09-12 12:10:24.128  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-12 12:10:24.129  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 12:10:24.131  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 12:10:24.140  1697  4317 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 12:10:24.140  1697  4317 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 12:10:24.141  4002  4002 D SprintDMHelper: simOperator: 
,09-12 12:10:24.141  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 12:10:24.156  1697  4317 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 12:10:24.166  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:10:24.167  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:10:24.181  1697  4315 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 12:10:24.218  1697  4315 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 12:10:24.218  1697  4315 I SystemUpdateService: now status is 0 (complete)
09-12 12:10:24.218  1697  4315 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 12:10:24.218  1697  4315 I SystemUpdateService: file has been verified
09-12 12:10:24.218  1697  4315 I SystemUpdateService: OTA package size = 12249756
,09-12 12:10:24.239  1697  4315 I SystemUpdateService: showing system update notification
,09-12 12:10:24.246  3819  4320 V KeepSync: Connecting to GoogleApiClient
,09-12 12:10:24.247   872  2105 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:10:24.282  1502  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 12:10:24.282  1502  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 12:10:24.282  1502  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:10:24.285  1502  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:10:24.288  3114  4321 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 12:10:24.311  1697  1697 D SystemUpdateService: onDestroy
,09-12 12:10:24.321  1502  2180 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 12:10:24.322  1502  2180 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 12:10:24.322  1502  2180 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:10:24.322  1502  2180 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:10:24.332  1697  4326 V BaseAuthAsyncOperation: access token request failed
,09-12 12:10:24.333  3819  4320 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:10:24.335  1697  4317 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-12 12:10:24.389  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 12:10:24.389  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 12:10:24.389  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:10:24.389  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:10:24.407  3819  4320 E KeepSync: IOException
09-12 12:10:24.407  3819  4320 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:10:24.407  3819  4320 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:10:24.407  3819  4320 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:10:24.407  3819  4320 E KeepSync: 	... 10 more
,09-12 12:10:24.407  3819  4320 W KeepSync: Sync result 2
,09-12 12:10:24.423   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 201382, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:10:24.456  1502  4325 I GCM     : Ack for not saved message 149
,09-12 12:10:24.847  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 12:10:24.847  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:24.847  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:24.847  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:24.847  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:24.847  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:10:24.847  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:10:24.847  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:10:24.857  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:10:24.858  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:10:24.858  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b91704e removed from the list
09-12 12:10:24.859  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:10:24.859  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:24.859  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:24.872  3862  4328 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-12 12:10:24.874  3862  4328 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 12:10:25.038   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 12:10:27.879  3862  4330 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-12 12:10:27.880  3862  4328 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-12 12:10:27.880  3862  4328 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 12:10:27.880  3862  4330 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-12 12:10:27.882  3862  4328 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 12:10:27.882  3862  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 12:10:27.883  3862  4328 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 12:10:27.884  3862  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 12:10:27.888  3862  4333 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
09-12 12:10:27.888  3862  4328 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 12:10:27.889  3862  4330 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-12 12:10:27.889  3862  4332 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Sender)
,09-12 12:10:27.893  3862  4335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Receiver)
09-12 12:10:27.894  3862  4334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Receiver)
09-12 12:10:27.894  3862  4334 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: OutgoingSocketThread/Receiver)
09-12 12:10:27.894  3862  4334 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 12:10:27.894  3862  4334 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-12 12:10:27.895  3862  4335 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: IncomingSocketThread/Receiver)
09-12 12:10:27.895  3862  4335 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 12:10:27.895  3862  4335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 12:10:30.061  1897  1937 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-12 12:10:30.061  1897  1937 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 12:10:30.102  1502  1502 I ConfigService: onCreate
,09-12 12:10:30.878  3862  3913 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 12:10:30.880  3862  3913 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 12:10:30.888  3862  3913 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4500d0a Bundle[{}]
,09-12 12:10:30.888  3862  3913 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 12:10:30.888  3862  3913 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 12:10:30.889  3862  3913 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 12:10:30.889  3862  3913 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 12:10:30.890  3862  3913 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 12:10:30.890  3862  3913 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 12:10:30.895  3862  3913 I System.out: Running OutgoingSocketThread
,09-12 12:10:30.900  3862  4337 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-12 12:10:30.900  3862  4337 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 12:10:31.927   872  1309 D ConnectivityService: handlePromptUnvalidated 102
,09-12 12:10:33.908  3862  4339 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-12 12:10:33.909  3862  4339 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 12:10:33.909  3862  4337 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-12 12:10:33.909  3862  4339 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 12:10:33.909  3862  4337 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-12 12:10:33.910  3862  4337 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 12:10:33.911  3862  4339 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 12:10:33.912  3862  4337 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 12:10:33.917  3862  4337 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-12 12:10:33.917  3862  4341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Sender)
,09-12 12:10:33.920  3862  4339 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 12:10:33.926  3862  4342 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Sender)
,09-12 12:10:33.931  3862  4343 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Receiver)
,09-12 12:10:33.932  3862  4343 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: OutgoingSocketThread/Receiver)
,09-12 12:10:33.933  3862  4343 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 12:10:33.933  3862  4343 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-12 12:10:33.933  3862  4344 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Receiver)
,09-12 12:10:33.934  3862  4344 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: IncomingSocketThread/Receiver)
09-12 12:10:33.935  3862  4344 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 12:10:33.935  3862  4344 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-12 12:10:35.193  1502  1502 I ConfigService: onDestroy
,09-12 12:10:36.910  3862  3913 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,09-12 12:10:36.913  3862  3913 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 12:10:36.913  3862  3913 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 451)
,09-12 12:10:36.919  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:10:36.919  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@778c56f added. We now have 3 listener(s)
,09-12 12:10:36.921  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 12:10:36.921  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 12:10:36.921  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 12:10:36.921  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:10:36.921  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e127c added. We now have 4 listener(s)
09-12 12:10:36.921  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:10:36.922  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:10:36.925  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:10:36.944  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:10:36.944  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:36.944  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:36.944  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:36.944  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:36.944  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:10:36.944  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:10:36.944  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:10:36.953  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:10:36.953  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK,
,09-12 12:10:36.954  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:10:36.955  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:10:36.955  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:10:36.955  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:10:36.955  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:36.956  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:10:36.956  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 12:10:36.956  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@778c56f removed from the list
09-12 12:10:36.956  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:36.957  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e127c removed from the list
09-12 12:10:36.959  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:36.966  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 12:10:36.967  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:10:36.967  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:36.968  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:10:36.968  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:36.970  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 12:10:36.971  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:10:36.971  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:36.971  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e127c not in the list
,09-12 12:10:36.971  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:36.971  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:36.974  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:10:36.975  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:10:36.975  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 12:10:36.975  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e127c not in the list
09-12 12:10:36.975  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:10:36.975  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:36.976  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:36.976  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@778c56f not in the list
09-12 12:10:36.978  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:10:36.978  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@798435a added. We now have 3 listener(s)
,09-12 12:10:36.985  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 12:10:36.985  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:10:36.985  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 12:10:36.987  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:10:36.987  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f6498b added. We now have 4 listener(s)
,09-12 12:10:36.987  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:10:36.988  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:10:36.993  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:10:37.002  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:10:37.002  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:37.002  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:37.002  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:37.002  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:37.002  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:10:37.002  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:10:37.002  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:10:37.007  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:10:37.007  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:10:37.007  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:10:37.007  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 12:10:37.007  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 12:10:37.007  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:10:37.007  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 12:10:37.011  3862  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 12:10:37.011  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 12:10:37.013  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:37.018  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:37.018  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 12:10:37.020  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 12:10:37.020  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 12:10:37.027  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 12:10:37.028  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 12:10:37.028  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 12:10:37.030  3862  3913 D BluetoothAdapter: STATE_ON
,09-12 12:10:37.036  4246  4275 D BtGatt.GattService: registerClient() - UUID=fd24777e-b556-4374-94dc-99daa357a258
,09-12 12:10:37.038  4246  4262 D BtGatt.GattService: onClientRegistered() - UUID=fd24777e-b556-4374-94dc-99daa357a258, clientIf=5
,09-12 12:10:37.040  3862  3902 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 12:10:37.042  4246  4282 D BtGatt.GattService: start scan with filters
,09-12 12:10:37.051  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 12:10:37.051  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 12:10:37.052  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 12:10:37.052  4246  4265 D BtGatt.ScanManager: handling starting scan
09-12 12:10:37.052  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 12:10:37.057  4246  4265 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@706fefe
,09-12 12:10:37.060  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:10:37.060  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 12:10:37.061  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 12:10:37.064  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 12:10:37.068  3862  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 12:10:37.069  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 12:10:37.069  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 12:10:37.069  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:10:37.069  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 12:10:37.069  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:10:37.069  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 12:10:37.069  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 12:10:37.070  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 12:10:37.070  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 12:10:37.070  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 12:10:37.070  4246  4262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 12:10:37.071  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:10:37.071  3862  3913 D BluetoothAdapter: STATE_ON
09-12 12:10:37.073  4246  4256 D BtGatt.GattService: stopScan() - queue size =1
09-12 12:10:37.073  4246  4265 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 12:10:37.074  4246  4275 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 12:10:37.075  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 12:10:37.075  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 12:10:37.075  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 12:10:37.075  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 12:10:37.076  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 12:10:37.078  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:10:37.078  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 12:10:37.078  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 12:10:37.079  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 12:10:37.081  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:10:37.084  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:10:37.084  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:10:37.085  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:10:37.092  4246  4262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 12:10:37.092  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:10:37.094  4246  4265 D BtGatt.ScanManager: Starting BLE batch scan
09-12 12:10:37.094  4246  4265 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 12:10:37.122  4246  4262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 12:10:37.122  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:10:37.139  4246  4262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 12:10:37.139  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:10:37.163  4246  4262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 12:10:37.163  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:10:37.164  4246  4265 D BtGatt.ScanManager: stopping BLe Batch
,09-12 12:10:37.184  4246  4262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 12:10:37.184  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:10:37.185  4246  4265 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:10:37.206  4246  4262 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 12:10:37.207  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:10:37.586  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:10:37.587  3862  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:10:37.587  3862  3862 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:10:40.084  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:10:40.085  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:10:40.085  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 12:10:40.086  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:10:40.087  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:10:40.087  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:10:40.087  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 12:10:40.088  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@798435a removed from the list
09-12 12:10:40.088  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:40.088  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f6498b removed from the list
09-12 12:10:40.089  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 12:10:40.089  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:40.090  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:40.091  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:40.094  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:10:40.094  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:10:40.094  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:40.095  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f6498b not in the list
09-12 12:10:40.095  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:40.095  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:40.098  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:10:40.098  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:10:40.099  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:40.099  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f6498b not in the list
,09-12 12:10:40.099  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:10:40.100  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:10:40.100  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:40.100  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@798435a not in the list
09-12 12:10:40.103  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:10:40.103  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3743514 added. We now have 3 listener(s)
09-12 12:10:40.106  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 12:10:40.106  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:10:40.106  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 12:10:40.106  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:10:40.107  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ee1bd added. We now have 4 listener(s)
09-12 12:10:40.107  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:10:40.107  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:10:40.110  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:10:40.117  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:10:40.117  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:40.117  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:40.117  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:40.117  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:40.117  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:10:40.117  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:10:40.117  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:10:40.120  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:10:40.120  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:10:40.121  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 12:10:40.122  3862  3913 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-12 12:10:40.122  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-12 12:10:40.124  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 12:10:40.124  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-12 12:10:40.124  3862  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 12:10:40.124  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:10:40.125  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:10:40.126  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 12:10:40.126  3862  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 12:10:40.126  3862  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 12:10:40.127  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 12:10:40.127  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 12:10:40.127  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:10:40.127  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 12:10:40.130  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:10:40.130  3862  3862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 12:10:40.135  3862  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 12:10:40.135  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 12:10:40.136  3862  4345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 12:10:40.140  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 12:10:40.141  3862  4345 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 12:10:40.141  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 12:10:40.141  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 12:10:40.144  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-12 12:10:40.144  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 12:10:40.145  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-12 12:10:40.147  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 12:10:40.147  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 12:10:40.147  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 12:10:40.148  3862  3913 D BluetoothAdapter: STATE_ON
,09-12 12:10:40.152  4246  4256 D BtGatt.GattService: registerClient() - UUID=711e5cb1-4217-4d09-9057-a85dbf02b624
,09-12 12:10:40.153  4246  4262 D BtGatt.GattService: onClientRegistered() - UUID=711e5cb1-4217-4d09-9057-a85dbf02b624, clientIf=5
09-12 12:10:40.153  3862  3873 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-12 12:10:40.155  4246  4264 D BtGatt.AdvertiseManager: message : 0
,09-12 12:10:40.158  4246  4264 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 12:10:40.170  4246  4262 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 12:10:40.179  4246  4262 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 12:10:40.181  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 12:10:40.182  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 12:10:40.184  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 12:10:40.186  3862  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 12:10:40.187  3862  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 12:10:40.187  3862  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 12:10:40.187  3862  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-12 12:10:40.187  3862  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-12 12:10:40.187  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-12 12:10:40.191  3862  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 12:10:40.191  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 12:10:40.193  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 12:10:40.193  3862  3913 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:10:40.692  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 12:10:43.194  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:10:43.195  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-12 12:10:43.195  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 12:10:43.195  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 12:10:43.196  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 12:10:43.196  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 12:10:43.197  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 12:10:43.197  3862  4345 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 12:10:43.198  3862  4345 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 12:10:43.198  3862  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 12:10:43.198  3862  4345 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 12:10:43.199  3862  3862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-12 12:10:43.199  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:10:43.200  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 12:10:43.200  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 12:10:43.200  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:10:43.200  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 12:10:43.203  3862  3913 D BluetoothAdapter: STATE_ON
,09-12 12:10:43.203  3862  3913 D BluetoothLeScanner: could not find callback wrapper
09-12 12:10:43.204  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 12:10:43.204  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-12 12:10:43.206  4246  4264 D BtGatt.AdvertiseManager: message : 1
09-12 12:10:43.208  4246  4264 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 12:10:43.216  4246  4262 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-12 12:10:43.217  4246  4262 D BtGatt.GattService: Client app is not null!
,09-12 12:10:43.218  4246  4285 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 12:10:43.220  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 12:10:43.220  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 12:10:43.220  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-12 12:10:43.220  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 12:10:43.220  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 12:10:43.223  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:10:43.223  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 12:10:43.223  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 12:10:43.224  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:10:43.226  3862  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:10:43.226  3862  3862 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 12:10:43.226  3862  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 12:10:43.226  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 12:10:43.226  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:43.227  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:10:43.227  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 12:10:43.227  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3743514 removed from the list
09-12 12:10:43.228  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:43.228  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ee1bd removed from the list
09-12 12:10:43.228  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:10:43.228  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-12 12:10:43.228  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:43.228  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:10:43.228  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:10:43.229  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:43.230  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:43.231  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:10:43.231  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:10:43.231  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:43.231  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ee1bd not in the list
09-12 12:10:43.231  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:43.231  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:43.232  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:10:43.232  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:10:43.233  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:43.233  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ee1bd not in the list
09-12 12:10:43.233  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:10:43.233  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:10:43.233  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:43.233  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3743514 not in the list
,09-12 12:10:43.234  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:10:43.234  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56088fe added. We now have 3 listener(s)
09-12 12:10:43.236  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 12:10:43.236  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 12:10:43.236  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 12:10:43.237  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:10:43.237  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64be85f added. We now have 4 listener(s)
,09-12 12:10:43.237  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 12:10:43.238  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 12:10:43.241  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:10:43.248  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:10:43.248  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:43.248  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:43.248  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:43.248  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:43.248  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:10:43.248  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:10:43.248  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:10:43.251  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:10:43.251  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 12:10:43.252  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:10:43.252  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 12:10:43.252  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 12:10:43.253  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 12:10:43.253  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 12:10:43.256  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:43.258  3862  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 12:10:43.258  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 12:10:43.259  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 12:10:43.267  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 12:10:43.268  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 12:10:43.268  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 12:10:43.273  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 12:10:43.273  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 12:10:43.273  3862  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 12:10:43.274  3862  3913 D BluetoothAdapter: STATE_ON
,09-12 12:10:43.276  4246  4257 D BtGatt.GattService: registerClient() - UUID=6994635c-67bc-4d95-918b-1bd7b073664c
,09-12 12:10:43.277  4246  4262 D BtGatt.GattService: onClientRegistered() - UUID=6994635c-67bc-4d95-918b-1bd7b073664c, clientIf=5,
09-12 12:10:43.278  3862  3902 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 12:10:43.279  4246  4285 D BtGatt.GattService: start scan with filters
,09-12 12:10:43.283  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 12:10:43.283  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 12:10:43.283  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 12:10:43.284  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 12:10:43.284  4246  4265 D BtGatt.ScanManager: handling starting scan
,09-12 12:10:43.286  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 12:10:43.287  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 12:10:43.287  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 12:10:43.289  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 12:10:43.301  4246  4262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 12:10:43.301  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:10:43.301  4246  4265 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 12:10:43.313  4246  4262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 12:10:43.313  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:10:43.314  4246  4265 D BtGatt.ScanManager: Starting BLE batch scan
09-12 12:10:43.314  4246  4265 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 12:10:43.331  4246  4262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 12:10:43.331  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:10:43.339  4246  4262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 12:10:43.339  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 12:10:43.729  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:10:43.787  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 12:10:43.787  3862  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:10:43.788  3862  3862 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 12:10:44.845  4246  4246 D BtGatt.ScanManager: awakened up at time 228019
,09-12 12:10:44.848  4246  4265 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:10:44.902  4246  4262 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,09-12 12:10:44.902  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:10:44.903  4246  4262 D BtGatt.GattService: current time is 228076960104
,09-12 12:10:44.904  4246  4262 D BtGatt.GattService: Batch record : [-37, -105, 4, -76, 116, 104, 1, -128, -53, 23, 0, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -93, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -96, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -37, -105, 4, -76, 116, 104, 1, -128, -53, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 116, -43, -111, -91, -20, -29, 1, -128, -98, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -37, -105, 4, -76, 116, 104, 1, -128, -54, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0]
,09-12 12:10:44.908  4246  4262 D BtGatt.GattService: ScanRecord : []
,09-12 12:10:44.910  4246  4262 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 12:10:44.911  4246  4262 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 12:10:44.912  4246  4262 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,09-12 12:10:44.913  4246  4262 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 12:10:44.913  4246  4262 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 12:10:44.914  4246  4262 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 12:10:44.915  4246  4262 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 12:10:44.915  4246  4262 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,09-12 12:10:44.922  3862  3862 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,09-12 12:10:44.923  3862  3862 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 1] updated - the peer count is 1
09-12 12:10:44.923  3862  3862 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-12 12:10:46.300  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 12:10:46.300  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 12:10:46.301  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 12:10:46.301  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 12:10:46.301  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 12:10:46.302  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 12:10:46.302  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 12:10:46.302  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 12:10:46.302  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 12:10:46.304  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 12:10:46.304  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 12:10:46.306  3862  3913 D BluetoothAdapter: STATE_ON
,09-12 12:10:46.308  4246  4275 D BtGatt.GattService: stopScan() - queue size =1
,09-12 12:10:46.311  4246  4282 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 12:10:46.312  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 12:10:46.313  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 12:10:46.313  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 12:10:46.314  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 12:10:46.314  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 12:10:46.318  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 12:10:46.318  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 12:10:46.319  3862  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 12:10:46.319  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 12:10:46.321  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:10:46.322  4246  4246 D BtGatt.ScanManager: awakened up at time 229495
09-12 12:10:46.322  3862  3913 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-12 12:10:46.326  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 12:10:46.327  3862  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 12:10:46.327  3862  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 12:10:46.328  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:10:46.328  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:46.329  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 12:10:46.329  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 12:10:46.330  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56088fe removed from the list
09-12 12:10:46.330  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:46.330  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64be85f removed from the list
09-12 12:10:46.331  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:10:46.331  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:46.332  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:46.332  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:46.333  4246  4262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 12:10:46.333  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:10:46.334  4246  4265 D BtGatt.ScanManager: stopping BLe Batch
,09-12 12:10:46.335  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:10:46.335  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:10:46.335  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:46.336  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64be85f not in the list
,09-12 12:10:46.336  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:46.336  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:46.338  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:10:46.338  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:10:46.338  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:46.338  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64be85f not in the list
09-12 12:10:46.339  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:10:46.339  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:46.339  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:46.339  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56088fe not in the list
,09-12 12:10:46.341  4246  4262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 12:10:46.341  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:10:46.341  4246  4265 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 12:10:46.342  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 12:10:46.342  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2ab9d6 added. We now have 3 listener(s)
,09-12 12:10:46.346  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 12:10:46.347  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 12:10:46.347  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 12:10:46.347  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 12:10:46.348  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7548457 added. We now have 4 listener(s)
09-12 12:10:46.348  3862  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 12:10:46.349  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 12:10:46.353  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 12:10:46.353  4246  4262 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-12 12:10:46.353  4246  4262 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 12:10:46.353  4246  4262 D BtGatt.GattService: current time is 229527581468
09-12 12:10:46.354  4246  4262 D BtGatt.GattService: Batch record : [-37, -105, 4, -76, 116, 104, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0]
,09-12 12:10:46.354  4246  4262 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,09-12 12:10:46.357  3862  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 12:10:46.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 12:10:46.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 12:10:46.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 12:10:46.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 12:10:46.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 12:10:46.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 12:10:46.357  3862  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 12:10:46.358  3862  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 12:10:46.359  3862  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 12:10:46.359  3862  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 12:10:46.359  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 12:10:46.359  3862  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 12:10:46.359  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:10:46.359  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:46.360  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 12:10:46.360  3862  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 12:10:46.360  3862  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2ab9d6 removed from the list
09-12 12:10:46.360  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:46.360  3862  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7548457 removed from the list
,09-12 12:10:46.361  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:10:46.361  3862  3913 D io.jxcore.node.ConnectivityMonitor: stop
09-12 12:10:46.361  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:46.362  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:46.362  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:46.363  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:10:46.363  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 12:10:46.363  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:46.363  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7548457 not in the list
09-12 12:10:46.363  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:46.363  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 12:10:46.364  3862  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 12:10:46.364  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 12:10:46.364  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 12:10:46.365  3862  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 12:10:46.365  3862  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7548457 not in the list
,09-12 12:10:46.365  3862  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 12:10:46.365  3862  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 12:10:46.365  3862  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 12:10:46.365  3862  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2ab9d6 not in the list
09-12 12:10:46.366  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-12 12:10:46.366  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 12:10:46.366  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 12:10:46.366  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 12:10:46.367  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-12 12:10:46.367  3862  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 12:10:46.657   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229830, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:10:46.829  3862  3862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 12:10:48.382  3862  4346 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,09-12 12:10:50.379  3862  3913 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 460
,09-12 12:10:50.380  3862  3913 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 460, name: My test thread name)
,09-12 12:10:50.387  3862  4347 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
,09-12 12:10:50.387  3862  4347 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: My test thread name)
09-12 12:10:50.387  3862  4347 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-12 12:10:50.391  3862  3913 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 12:10:50.400  3862  4348 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: My test thread name)
,09-12 12:10:50.401  3862  4348 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 465, thread name: My test thread name): Test exception.
09-12 12:10:50.401  3862  4348 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 465, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-12 12:10:50.408  3862  3913 I jxcore-log: Total number of executed tests:  82
09-12 12:10:50.408  3862  3913 I jxcore-log: 
,09-12 12:10:50.410  3862  3913 I jxcore-log: Number of passed tests:  82
09-12 12:10:50.410  3862  3913 I jxcore-log: 
,09-12 12:10:50.410  3862  3913 I jxcore-log: Number of failed tests:  0
09-12 12:10:50.410  3862  3913 I jxcore-log: 
09-12 12:10:50.411  3862  3913 I jxcore-log: Number of ignored tests:  0
09-12 12:10:50.411  3862  3913 I jxcore-log: 
,09-12 12:10:50.411  3862  3913 I jxcore-log: Total duration:  101401
09-12 12:10:50.411  3862  3913 I jxcore-log: 
,09-12 12:10:50.421  3862  3913 I jxcore-log: Unit Test app is loaded
09-12 12:10:50.421  3862  3913 I jxcore-log: 
,09-12 12:10:50.440  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.440  3862  3913 I jxcore-log: 
,09-12 12:10:50.445  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.445  3862  3913 I jxcore-log: 
,09-12 12:10:50.446  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.446  3862  3913 I jxcore-log: 
,09-12 12:10:50.447  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.447  3862  3913 I jxcore-log: 
,09-12 12:10:50.448  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 12:10:50.448  3862  3913 I jxcore-log: 
,09-12 12:10:50.450  3862  3862 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 12:10:50.450  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:10:50.450  3862  3913 I jxcore-log: 
,09-12 12:10:50.453  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.453  3862  3913 I jxcore-log: 
,09-12 12:10:50.455  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.455  3862  3913 I jxcore-log: 
,09-12 12:10:50.456  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 12:10:50.456  3862  3913 I jxcore-log: 
,09-12 12:10:50.457  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:10:50.457  3862  3913 I jxcore-log: 
,09-12 12:10:50.458  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:10:50.458  3862  3913 I jxcore-log: 
09-12 12:10:50.459  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.459  3862  3913 I jxcore-log: 
,09-12 12:10:50.460  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.460  3862  3913 I jxcore-log: 
09-12 12:10:50.461  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.461  3862  3913 I jxcore-log: 
,09-12 12:10:50.462  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:10:50.462  3862  3913 I jxcore-log: 
,09-12 12:10:50.463  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:10:50.463  3862  3913 I jxcore-log: 
,09-12 12:10:50.464  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:10:50.464  3862  3913 I jxcore-log: 
,09-12 12:10:50.465  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.465  3862  3913 I jxcore-log: 
09-12 12:10:50.465  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.465  3862  3913 I jxcore-log: 
09-12 12:10:50.466  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.466  3862  3913 I jxcore-log: 
,09-12 12:10:50.467  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:10:50.467  3862  3913 I jxcore-log: 
09-12 12:10:50.468  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:10:50.468  3862  3913 I jxcore-log: 
09-12 12:10:50.469  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 12:10:50.469  3862  3913 I jxcore-log: 
,09-12 12:10:50.469  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.469  3862  3913 I jxcore-log: 
09-12 12:10:50.470  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.470  3862  3913 I jxcore-log: 
09-12 12:10:50.471  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.471  3862  3913 I jxcore-log: 
,09-12 12:10:50.472  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.472  3862  3913 I jxcore-log: 
09-12 12:10:50.473  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.473  3862  3913 I jxcore-log: 
09-12 12:10:50.473  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.473  3862  3913 I jxcore-log: 
,09-12 12:10:50.474  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.474  3862  3913 I jxcore-log: 
09-12 12:10:50.475  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.475  3862  3913 I jxcore-log: 
09-12 12:10:50.476  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.476  3862  3913 I jxcore-log: 
,09-12 12:10:50.477  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.477  3862  3913 I jxcore-log: 
,09-12 12:10:50.478  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.478  3862  3913 I jxcore-log: 
09-12 12:10:50.478  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.478  3862  3913 I jxcore-log: 
09-12 12:10:50.479  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.479  3862  3913 I jxcore-log: 
,09-12 12:10:50.479  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.479  3862  3913 I jxcore-log: 
09-12 12:10:50.480  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 12:10:50.480  3862  3913 I jxcore-log: 
,09-12 12:10:50.480  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 12:10:50.480  3862  3913 I jxcore-log: 
09-12 12:10:50.481  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 12:10:50.481  3862  3913 I jxcore-log: 
09-12 12:10:50.481  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.481  3862  3913 I jxcore-log: 
,09-12 12:10:50.482  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.482  3862  3913 I jxcore-log: 
09-12 12:10:50.482  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.482  3862  3913 I jxcore-log: 
09-12 12:10:50.483  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.483  3862  3913 I jxcore-log: 
,09-12 12:10:50.483  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.483  3862  3913 I jxcore-log: 
09-12 12:10:50.484  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:10:50.484  3862  3913 I jxcore-log: 
09-12 12:10:50.484  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.484  3862  3913 I jxcore-log: 
,09-12 12:10:50.485  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 12:10:50.485  3862  3913 I jxcore-log: 
09-12 12:10:50.485  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.485  3862  3913 I jxcore-log: 
09-12 12:10:50.486  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:10:50.486  3862  3913 I jxcore-log: 
,09-12 12:10:50.487  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 12:10:50.487  3862  3913 I jxcore-log: 
09-12 12:10:50.487  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-12 12:10:50.487  3862  3913 I jxcore-log: 
09-12 12:10:50.488  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 12:10:50.488  3862  3913 I jxcore-log: 
,09-12 12:10:50.489  3862  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 12:10:50.489  3862  3913 I jxcore-log: 
,09-12 12:10:50.493  3862  3913 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-12 12:10:50.493  3862  3913 I jxcore-log:   bluetooth: 'on',
09-12 12:10:50.493  3862  3913 I jxcore-log:   wifi: 'on',
09-12 12:10:50.493  3862  3913 I jxcore-log:   cellular: 'doNotCare',
09-12 12:10:50.493  3862  3913 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 12:10:50.493  3862  3913 I jxcore-log: 
,09-12 12:10:50.498  3862  3913 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-12 12:10:50.498  3862  3913 I jxcore-log:   bluetooth: 'on',
09-12 12:10:50.498  3862  3913 I jxcore-log:   wifi: 'on',
09-12 12:10:50.498  3862  3913 I jxcore-log:   cellular: 'doNotCare',
09-12 12:10:50.498  3862  3913 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 12:10:50.498  3862  3913 I jxcore-log: 
,09-12 12:10:50.499  3862  3913 I jxcore-log: My device name is: motorola-Nexus 6
09-12 12:10:50.499  3862  3913 I jxcore-log: 
09-12 12:10:50.500  3862  3913 I jxcore-log: Running for WIFI network type
09-12 12:10:50.500  3862  3913 I jxcore-log: 
,09-12 12:10:50.539  3862  4346 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-12 12:10:52.945  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-12 12:10:52.945  3862  3913 I jxcore-log: 
,09-12 12:10:53.397  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-12 12:10:53.397  3862  3913 I jxcore-log: 
,09-12 12:10:53.429  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-12 12:10:53.429  3862  3913 I jxcore-log: 
,09-12 12:10:53.543   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=236717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 12:10:54.804  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-12 12:10:54.804  3862  3913 I jxcore-log: 
,09-12 12:10:55.040  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-12 12:10:55.040  3862  3913 I jxcore-log: 
,09-12 12:10:55.045  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-12 12:10:55.045  3862  3913 I jxcore-log: 
,09-12 12:10:55.052  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-12 12:10:55.052  3862  3913 I jxcore-log: 
,09-12 12:10:55.129  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-12 12:10:55.129  3862  3913 I jxcore-log: 
,09-12 12:10:55.149  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-12 12:10:55.149  3862  3913 I jxcore-log: 
,09-12 12:10:55.154  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-12 12:10:55.154  3862  3913 I jxcore-log: 
,09-12 12:10:56.087  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-12 12:10:56.087  3862  3913 I jxcore-log: 
,09-12 12:10:56.255  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-12 12:10:56.255  3862  3913 I jxcore-log: 
,09-12 12:10:56.557  3819  4349 V KeepSync: Connecting to GoogleApiClient
09-12 12:10:56.558   872  1999 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:10:56.601  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:10:56.604  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:10:56.611  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-12 12:10:56.611  3862  3913 I jxcore-log: 
,09-12 12:10:56.621  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-12 12:10:56.621  3862  3913 I jxcore-log: 
,09-12 12:10:56.628  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-12 12:10:56.628  3862  3913 I jxcore-log: 
,09-12 12:10:56.633  1502  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 12:10:56.633  1502  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 12:10:56.633  1502  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:10:56.633  1502  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:10:56.634  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-12 12:10:56.634  3862  3913 I jxcore-log: 
,09-12 12:10:56.652  1697  4350 V BaseAuthAsyncOperation: access token request failed
,09-12 12:10:56.654  3819  4349 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:10:56.677  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-12 12:10:56.677  3862  3913 I jxcore-log: 
,09-12 12:10:56.714  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 12:10:56.714  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 12:10:56.714  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:10:56.714  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:10:56.725  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-12 12:10:56.725  3862  3913 I jxcore-log: 
,09-12 12:10:56.732  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-12 12:10:56.732  3862  3913 I jxcore-log: 
,09-12 12:10:56.737  3819  4349 E KeepSync: IOException
09-12 12:10:56.737  3819  4349 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:10:56.737  3819  4349 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:10:56.737  3819  4349 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:10:56.737  3819  4349 E KeepSync: 	... 10 more
,09-12 12:10:56.737  3819  4349 W KeepSync: Sync result 2
09-12 12:10:56.740  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-12 12:10:56.740  3862  3913 I jxcore-log: 
,09-12 12:10:56.751   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 239591, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:10:56.761  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-12 12:10:56.761  3862  3913 I jxcore-log: 
,09-12 12:10:56.765  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-12 12:10:56.765  3862  3913 I jxcore-log: 
,09-12 12:10:56.771  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-12 12:10:56.771  3862  3913 I jxcore-log: 
,09-12 12:10:56.787  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-12 12:10:56.787  3862  3913 I jxcore-log: 
,09-12 12:10:56.812  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-12 12:10:56.812  3862  3913 I jxcore-log: 
,09-12 12:10:56.822  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-12 12:10:56.822  3862  3913 I jxcore-log: 
,09-12 12:10:56.835  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-12 12:10:56.835  3862  3913 I jxcore-log: 
,09-12 12:10:56.847  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-12 12:10:56.847  3862  3913 I jxcore-log: 
,09-12 12:10:56.864  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-12 12:10:56.864  3862  3913 I jxcore-log: 
,09-12 12:10:56.875  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-12 12:10:56.875  3862  3913 I jxcore-log: 
,09-12 12:10:56.880  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-12 12:10:56.880  3862  3913 I jxcore-log: 
,09-12 12:10:56.911  3862  3913 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-12 12:10:56.911  3862  3913 I jxcore-log: 
,09-12 12:10:56.925  3862  3913 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-12 12:10:56.926  3862  3913 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-12 12:10:56.926  3862  3913 I jxcore-log: 
,09-12 12:10:56.929  3862  3913 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-12 12:10:56.929  3862  3913 I jxcore-log: 
,09-12 12:10:56.929  3862  3913 I jxcore-log: ThaliTape :: Started ThaliTape
09-12 12:10:56.929  3862  3913 I jxcore-log: 
,09-12 12:10:56.935  3862  3913 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-12 12:10:56.935  3862  3913 I jxcore-log: 
,09-12 12:10:57.002  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:10:57.002  3862  3913 I jxcore-log: 
,09-12 12:10:57.002  3862  3913 I jxcore-log: websocket error
09-12 12:10:57.002  3862  3913 I jxcore-log: 
09-12 12:10:57.003  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:10:57.003  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:10:57.003  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:10:57.003  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:10:57.003  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:10:57.003  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:10:57.003  3862  3913 I jxcore-log: 
,09-12 12:10:58.419  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:10:58.419  3862  3913 I jxcore-log: 
,09-12 12:10:58.420  3862  3913 I jxcore-log: websocket error
09-12 12:10:58.420  3862  3913 I jxcore-log: 
09-12 12:10:58.421  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:10:58.421  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:10:58.421  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:10:58.421  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:10:58.421  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:10:58.421  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:10:58.421  3862  3913 I jxcore-log: 
,09-12 12:11:00.408  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:00.408  3862  3913 I jxcore-log: 
09-12 12:11:00.410  3862  3913 I jxcore-log: websocket error
09-12 12:11:00.410  3862  3913 I jxcore-log: 
,09-12 12:11:00.410  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:00.410  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:00.410  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:00.410  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:00.410  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:00.410  3862  3913 I jxcore-log: emit@events.js:82:1,
09-12 12:11:00.410  3862  3913 I jxcore-log: 
,09-12 12:11:04.757  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:04.757  3862  3913 I jxcore-log: 
,09-12 12:11:04.758  3862  3913 I jxcore-log: websocket error
09-12 12:11:04.758  3862  3913 I jxcore-log: 
09-12 12:11:04.758  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:04.758  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:04.758  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:04.758  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:04.758  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:04.758  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:04.758  3862  3913 I jxcore-log: 
,09-12 12:11:09.829  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:09.829  3862  3913 I jxcore-log: 
,09-12 12:11:09.829  3862  3913 I jxcore-log: websocket error
09-12 12:11:09.829  3862  3913 I jxcore-log: 
09-12 12:11:09.829  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:09.829  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:09.829  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:09.829  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:09.829  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:09.829  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:09.829  3862  3913 I jxcore-log: 
,09-12 12:11:14.891  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:14.891  3862  3913 I jxcore-log: 
,09-12 12:11:14.891  3862  3913 I jxcore-log: websocket error
09-12 12:11:14.891  3862  3913 I jxcore-log: 
,09-12 12:11:14.892  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:14.892  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:14.892  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:14.892  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:14.892  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:14.892  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:14.892  3862  3913 I jxcore-log: 
,09-12 12:11:15.757   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=258930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:11:19.954  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:19.954  3862  3913 I jxcore-log: 
09-12 12:11:19.954  3862  3913 I jxcore-log: websocket error
09-12 12:11:19.954  3862  3913 I jxcore-log: 
09-12 12:11:19.955  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:19.955  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:19.955  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:19.955  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:19.955  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:19.955  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:19.955  3862  3913 I jxcore-log: 
,09-12 12:11:24.930   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 12:11:25.020  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:25.020  3862  3913 I jxcore-log: 
09-12 12:11:25.021  3862  3913 I jxcore-log: websocket error
09-12 12:11:25.021  3862  3913 I jxcore-log: 
09-12 12:11:25.021  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:25.021  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:25.021  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:25.021  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:25.021  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:25.021  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:25.021  3862  3913 I jxcore-log: 
,09-12 12:11:26.944  3639  4356 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:11:26.986  3639  4357 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:11:27.012  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:11:27.015  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:11:27.050  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:11:27.051  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:11:27.051  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:11:27.051  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:11:27.090  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:11:27.095  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:11:27.135  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 12:11:27.135  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 12:11:27.136  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:11:27.136  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:11:27.164  3639  4357 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 12:11:27.165  3639  4356 E BooksSync: Soft error
09-12 12:11:27.165  3639  4356 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:11:27.165  3639  4356 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:11:27.166  3639  4356 E BooksSync: Sync error
09-12 12:11:27.166  3639  4356 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:11:27.166  3639  4356 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:11:27.166  3639  4356 I BooksSync: Finished books sync
,09-12 12:11:27.178   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 250052, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:11:30.082  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:30.082  3862  3913 I jxcore-log: 
09-12 12:11:30.082  3862  3913 I jxcore-log: websocket error
09-12 12:11:30.082  3862  3913 I jxcore-log: 
,09-12 12:11:30.083  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:30.083  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:30.083  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:30.083  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:30.083  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:30.083  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:30.083  3862  3913 I jxcore-log: 
,09-12 12:11:35.155  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:35.155  3862  3913 I jxcore-log: 
,09-12 12:11:35.155  3862  3913 I jxcore-log: websocket error
09-12 12:11:35.155  3862  3913 I jxcore-log: 
09-12 12:11:35.156  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:35.156  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:35.156  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:35.156  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:35.156  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:35.156  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:35.156  3862  3913 I jxcore-log: 
,09-12 12:11:40.261  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:40.261  3862  3913 I jxcore-log: 
,09-12 12:11:40.261  3862  3913 I jxcore-log: websocket error
09-12 12:11:40.261  3862  3913 I jxcore-log: 
,09-12 12:11:40.262  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:40.262  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:40.262  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:40.262  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:40.262  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:40.262  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:40.262  3862  3913 I jxcore-log: 
,09-12 12:11:45.323  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:45.323  3862  3913 I jxcore-log: 
,09-12 12:11:45.324  3862  3913 I jxcore-log: websocket error
09-12 12:11:45.324  3862  3913 I jxcore-log: 
,09-12 12:11:45.324  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:45.324  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:45.324  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:45.324  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:45.324  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:45.324  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:45.324  3862  3913 I jxcore-log: 
,09-12 12:11:46.827  1502  2245 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 12:11:47.117   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=290290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:11:50.373  3862  3913 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 12:11:50.373  3862  3913 I jxcore-log: 
,09-12 12:11:50.374  3862  3913 I jxcore-log: websocket error
09-12 12:11:50.374  3862  3913 I jxcore-log: 
09-12 12:11:50.375  3862  3913 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 12:11:50.375  3862  3913 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 12:11:50.375  3862  3913 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 12:11:50.375  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:50.375  3862  3913 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 12:11:50.375  3862  3913 I jxcore-log: emit@events.js:82:1
09-12 12:11:50.375  3862  3913 I jxcore-log: 
,09-12 12:11:55.357   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=298531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 12:11:55.528  3862  3913 I jxcore-log: ThaliTape :: Reconnected to the test server
09-12 12:11:55.528  3862  3913 I jxcore-log: 
,09-12 12:11:55.543  3862  3913 I jxcore-log: ThaliTape :: Connected to the test server
09-12 12:11:55.543  3862  3913 I jxcore-log: 
,09-12 12:11:57.645  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:11:57.652  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:11:57.696  1502  2180 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:11:57.697  1502  2180 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 12:11:57.697  1502  2180 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:11:57.697  1502  2180 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:11:57.723  3017  4372 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:11:57.723  3017  4372 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:11:57.723  3017  4372 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	... 12 more
09-12 12:11:57.723  3017  4372 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at fal.a(PG:38)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:11:57.723  3017  4372 E HttpOperation: 	... 14 more
,09-12 12:11:57.782  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 12:11:57.782  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:11:57.782  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:11:57.782  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:11:57.833  3017  4372 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:11:57.833  3017  4372 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at hec.a(PG:42)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at hee.a(PG:102)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at czr.a(PG:65)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at kka.a(PG:108)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:11:57.833  3017  4372 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	... 15 more
09-12 12:11:57.833  3017  4372 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at fal.a(PG:38)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:11:57.833  3017  4372 E HttpOperation: 	... 17 more
,09-12 12:11:57.833  3017  4372 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 12:11:57.833  3017  4372 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	... 15 more
09-12 12:11:57.833  3017  4372 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:11:57.833  3017  4372 E ExperimentLoader: 	... 17 more
,09-12 12:11:57.947   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 290610, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:12:28.083  3639  4380 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:12:28.126  3639  4382 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:12:28.140  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:12:28.142  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:12:28.170  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:12:28.170  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:12:28.170  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:12:28.170  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:12:28.171  3819  4381 V KeepSync: Connecting to GoogleApiClient
09-12 12:12:28.171   872  2164 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:12:28.220  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:12:28.225  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:12:28.274  1502  4375 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:12:28.274  1502  4375 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:12:28.274  1502  4375 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:12:28.274  1502  4375 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:12:28.300  1502  2997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 12:12:28.300  1502  2997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 12:12:28.300  1502  2997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:12:28.300  1502  2997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 12:12:28.300  3639  4382 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 12:12:28.301  3639  4380 E BooksSync: Soft error
09-12 12:12:28.301  3639  4380 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:12:28.301  3639  4380 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:12:28.301  3639  4380 E BooksSync: Sync error
09-12 12:12:28.301  3639  4380 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:12:28.301  3639  4380 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:12:28.301  3639  4380 I BooksSync: Finished books sync
,09-12 12:12:28.326  1697  4383 V BaseAuthAsyncOperation: access token request failed
,09-12 12:12:28.326   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 302926, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:12:28.327  3819  4381 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:12:28.377  1502  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 12:12:28.377  1502  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 12:12:28.377  1502  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:12:28.377  1502  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:12:28.390  3819  4381 E KeepSync: IOException
09-12 12:12:28.390  3819  4381 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:12:28.390  3819  4381 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:12:28.390  3819  4381 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:12:28.390  3819  4381 E KeepSync: 	... 10 more
,09-12 12:12:28.390  3819  4381 W KeepSync: Sync result 2
,09-12 12:12:28.426   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 303913, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:12:28.542  1502  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:12:28.543  1502  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:12:28.543  1502  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:12:28.543  1502  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:12:28.560  3017  4385 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:12:28.560  3017  4385 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:12:28.560  3017  4385 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	... 12 more
09-12 12:12:28.560  3017  4385 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at fal.a(PG:38)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:12:28.560  3017  4385 E HttpOperation: 	... 14 more
,09-12 12:12:28.605  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:12:28.605  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:12:28.605  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:12:28.605  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:12:28.620  3017  4385 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:12:28.620  3017  4385 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at hec.a(PG:42)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at hee.a(PG:102)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at czr.a(PG:65)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at kka.a(PG:108)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:12:28.620  3017  4385 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	... 15 more
09-12 12:12:28.620  3017  4385 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at fal.a(PG:38)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:12:28.620  3017  4385 E HttpOperation: 	... 17 more
09-12 12:12:28.620  3017  4385 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 12:12:28.620  3017  4385 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	... 15 more
09-12 12:12:28.620  3017  4385 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:12:28.620  3017  4385 E ExperimentLoader: 	... 17 more
,09-12 12:12:28.769   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 331171, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:12:41.442  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:12:41.454  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:12:41.458  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:12:41.517  1502  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 12:12:41.517  1502  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 12:12:41.517  1502  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:12:41.517  1502  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:12:41.550  1502  2046 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 12:12:41.550  1502  2046 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 12:12:41.550  1502  2046 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 12:12:41.550  1502  2046 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-12 12:12:41.550  1502  2046 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-12 12:12:41.550  1502  2046 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-12 12:12:41.550  1502  2046 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 12:12:41.562  3575  3607 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 12:12:41.562  3575  3607 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-12 12:12:41.562  3575  3607 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-12 12:12:41.562  3575  3607 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-12 12:12:41.562  3575  3607 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-12 12:12:41.562  3575  3607 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-12 12:12:41.562  3575  3607 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 12:13:07.877   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=371050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:13:15.743   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=378917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:13:29.126  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:13:29.129  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:13:29.160  1502  2180 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:13:29.160  1502  2180 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:13:29.160  1502  2180 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:13:29.160  1502  2180 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:13:29.177  3017  4396 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:13:29.177  3017  4396 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:13:29.177  3017  4396 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	... 12 more
09-12 12:13:29.177  3017  4396 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at fal.a(PG:38)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:13:29.177  3017  4396 E HttpOperation: 	... 14 more
,09-12 12:13:29.240  1502  4375 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:13:29.240  1502  4375 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:13:29.240  1502  4375 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:13:29.240  1502  4375 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:13:29.268  3017  4396 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:13:29.268  3017  4396 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at hec.a(PG:42)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at hee.a(PG:102)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at czr.a(PG:65)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at kka.a(PG:108)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:13:29.268  3017  4396 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	... 15 more
09-12 12:13:29.268  3017  4396 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at fal.a(PG:38)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:13:29.268  3017  4396 E HttpOperation: 	... 17 more
09-12 12:13:29.269  3017  4396 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 12:13:29.269  3017  4396 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	... 15 more
09-12 12:13:29.269  3017  4396 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:13:29.269  3017  4396 E ExperimentLoader: 	... 17 more
,09-12 12:13:29.438   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 392045, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:13:33.090   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=396264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:13:40.930   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=404104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:13:58.157   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=421331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:13:59.680  3639  4399 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:13:59.723  3639  4400 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:13:59.742  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:13:59.747  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:13:59.797  1502  2180 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:13:59.798  1502  2180 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:13:59.798  1502  2180 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:13:59.798  1502  2180 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:13:59.857  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:13:59.862  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:13:59.919  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:13:59.920  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:13:59.920  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:13:59.920  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:13:59.958  3639  4400 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 12:13:59.960  3639  4399 E BooksSync: Soft error
09-12 12:13:59.960  3639  4399 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:13:59.960  3639  4399 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:13:59.962  3639  4399 E BooksSync: Sync error
09-12 12:13:59.962  3639  4399 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:13:59.962  3639  4399 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:13:59.962  3639  4399 I BooksSync: Finished books sync
,09-12 12:13:59.978   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 396648, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:14:06.010   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=429184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:14:23.224   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=446397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:14:29.264   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=452437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:14:36.542  3819  4404 V KeepSync: Connecting to GoogleApiClient
,09-12 12:14:36.543   872  1386 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 12:14:36.623  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:14:36.626  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:14:36.679  1502  2997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 12:14:36.679  1502  2997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 12:14:36.679  1502  2997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:14:36.680  1502  2997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:14:36.705  1697  4405 V BaseAuthAsyncOperation: access token request failed
,09-12 12:14:36.706  3819  4404 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 12:14:36.761  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 12:14:36.761  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 12:14:36.761  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:14:36.761  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:14:36.785  3819  4404 E KeepSync: IOException
09-12 12:14:36.785  3819  4404 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 12:14:36.785  3819  4404 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 12:14:36.785  3819  4404 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 12:14:36.785  3819  4404 E KeepSync: 	... 10 more
,09-12 12:14:36.785  3819  4404 W KeepSync: Sync result 2
,09-12 12:14:36.792   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 459576, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:14:48.290   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=471463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:14:56.130   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=479304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:15:13.357   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=496530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:15:21.197   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=504370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:15:29.915  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:15:29.920  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:15:29.972  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:15:29.972  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:15:29.972  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:15:29.972  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:15:29.997  3017  4408 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 12:15:29.997  3017  4408 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at jcn.a(PG:1379)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at blb.a(PG:3937)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at czp.a(PG:18188)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:15:29.997  3017  4408 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	... 12 more
09-12 12:15:29.997  3017  4408 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at fal.a(PG:38)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:15:29.997  3017  4408 E HttpOperation: 	... 14 more
,09-12 12:15:30.079  1502  4375 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 12:15:30.079  1502  4375 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 12:15:30.080  1502  4375 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 12:15:30.080  1502  4375 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:15:30.116  3017  4408 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 12:15:30.116  3017  4408 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at jdm.a(PG:82)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at jcs.o(PG:406)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at jcn.a(PG:1379)
,09-12 12:15:30.116  3017  4408 E HttpOperation: 	at jcs.i(PG:143)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at hec.a(PG:42)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at hee.a(PG:102)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at czr.a(PG:65)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at kka.a(PG:108)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at czp.a(PG:19176)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at czp.a(PG:9081)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at czq.run(PG:1686)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:15:30.116  3017  4408 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at jdj.a(PG:4091)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at jdj.a(PG:1125)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at jdm.a(PG:77)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	... 15 more
09-12 12:15:30.116  3017  4408 E HttpOperation: Caused by: faj: BadAuthentication
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at fal.a(PG:38)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	at jdj.a(PG:4089)
09-12 12:15:30.116  3017  4408 E HttpOperation: 	... 17 more
09-12 12:15:30.117  3017  4408 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 12:15:30.117  3017  4408 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at hec.a(PG:42)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at hee.a(PG:102)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at czr.a(PG:65)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at kka.a(PG:108)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	... 15 more
09-12 12:15:30.117  3017  4408 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at fal.a(PG:38)
09-12 12:15:30.117  3017  4408 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 12:15:30.117  3017  4408 E ,ExperimentLoader: 	... 17 more
,09-12 12:15:30.239   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 512816, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:15:38.424   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=521597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:15:44.504   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=527677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:16:03.437   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=546610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:16:10.365  3639  4412 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 12:16:10.398  3639  4413 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 12:16:10.412  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:16:10.415  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:16:10.448  1502  4375 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 12:16:10.448  1502  4375 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:16:10.448  1502  4375 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:16:10.448  1502  4375 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:16:10.483  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:16:10.488  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 12:16:10.522  1502  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 12:16:10.523  1502  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 12:16:10.523  1502  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 12:16:10.523  1502  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 12:16:10.547  3639  4413 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 12:16:10.548  3639  4412 E BooksSync: Soft error
09-12 12:16:10.548  3639  4412 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:16:10.548  3639  4412 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 12:16:10.548  3639  4412 E BooksSync: Sync error
09-12 12:16:10.548  3639  4412 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 12:16:10.548  3639  4412 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 12:16:10.548  3639  4412 I BooksSync: Finished books sync
,09-12 12:16:10.558   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 553448, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 12:16:11.331   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=554504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:16:28.558   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=571731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:16:36.397   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=579570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:16:53.624   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=596797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:17:01.450   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=604623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:17:18.690   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=621863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:17:26.504   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=629677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:17:44.077   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:17:51.918   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=655090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:18:09.144   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=672317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:18:16.984   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=680157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:18:34.211   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=697384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:18:42.051   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=705224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:18:59.277   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=722450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:19:07.091   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=730264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:19:24.344   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=747517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:19:32.157   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=755330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:19:49.357   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=772531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:19:57.224   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=780397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:20:14.478   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=797651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:20:22.317   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=805490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:20:39.544   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=822717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:20:47.384   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=830557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:21:04.611   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=847784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:21:12.437   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=855610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:21:29.677   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=872850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:21:37.504   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=880677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:21:41.850   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=885023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:22:02.957   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=906130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:22:07.797   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=910970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:22:28.904   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=932077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:22:32.864   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=936037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:22:53.970   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=957144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:22:57.930   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=961103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:23:19.037   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=982210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:23:22.983   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=986157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:23:44.103   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1007277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:23:48.064   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1011237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:24:09.171   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1032344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:24:13.130   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1036304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:24:34.237   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1057410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:24:38.850   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1062023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:24:59.957   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1083130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:25:03.904   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1087077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:25:25.010   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1108183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:25:28.970   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1112143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:25:50.091   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1133264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:25:54.037   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1137210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:26:15.144   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1158317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:26:19.103   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1162277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:26:40.211   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1183384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:26:51.811   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1194984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:27:05.304   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1208477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:27:15.868   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,09-12 12:27:16.877   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1220050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:27:30.370   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1233543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:27:41.970   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1245144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:27:55.464   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1258637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:28:07.064   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1270237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:28:20.544   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1283717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:28:32.130   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1295303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:28:45.664   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1308837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:28:57.250   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:28:59.482  1697  4458 I EventLogService: Opted in for usage reporting
,09-12 12:28:59.485  1697  4458 I EventLogService: Aggregate from 1473674339319 (log), 1473674339319 (data)
,09-12 12:28:59.524  1697  4458 W EventLogAggregator: Unknown tag: snet_gcore
,09-12 12:28:59.524  1697  4458 W EventLogAggregator: Unknown tag: snet_launch_service
,09-12 12:28:59.615  1697  4458 I ServiceDumpSys: dumping service [account]
,09-12 12:29:04.423   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1327597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:29:22.424   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1345597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:29:35.917   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1359090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:29:47.490   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1370663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:30:01.011   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1384184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:30:12.610   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1395783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:30:26.104   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1409277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:30:37.677   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1420850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:30:51.157   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1434330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:31:02.717   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1445890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:31:16.211   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1459384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:31:27.757   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1470930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:31:41.277   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1484450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:31:45.437   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1488610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 12:32:06.344   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1509517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 12:32:10.530   872  4304 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1513703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-12 12:32:24.066  4470  4470 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 12:32:24.071  4470  4470 D AndroidRuntime: CheckJNI is OFF
09-12 12:32:24.106  4470  4470 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 12:32:24.147  4470  4470 I Radio-JNI: register_android_hardware_Radio DONE
09-12 12:32:24.167  4470  4470 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-12 12:32:24.179   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-12 12:32:24.180   872   885 I ActivityManager: Killing 3862:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-12 12:32:24.289   872   897 W PackageSettings: Skipping PackageSetting{24ceb93 com.example.hello/10273} due to missing metadata
09-12 12:32:24.315   872   897 I art     : Starting a blocking GC Explicit
09-12 12:32:24.327   872  1378 I WindowState: WIN DEATH: Window{9947a36 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 12:32:24.328   872  1308 D WifiService: Client connection lost with reason: 4
09-12 12:32:24.329   872  1990 D GraphicsStats: Buffer count: 2
09-12 12:32:24.372   872   897 I art     : Explicit concurrent mark sweep GC freed 71402(5MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 29MB/43MB, paused 957us total 55.993ms
09-12 12:32:24.389   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-12 12:32:24.389   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-12 12:32:24.390   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-12 12:32:24.390   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 12:32:24.390   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:32:24.390   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.390   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 12:32:24.390   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 12:32:24.390   872   885 I ActivityManager:   Force finishing activity ActivityRecord{dccbb5f u0 com.test.thalitest/.MainActivity t4}
09-12 12:32:24.396   872  1989 W ActivityManager: Spurious death for ProcessRecord{61f053d 0:com.test.thalitest/u0a0}, curProc for 3862: null
09-12 12:32:24.398   872   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-12 12:32:24.402  4470  4470 I art     : System.exit called, status: 0
09-12 12:32:24.402  4470  4470 I AndroidRuntime: VM exiting with result code 0.
09-12 12:32:24.410   872   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-12 12:32:24.421   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-12 12:32:24.425  4246  4246 D BluetoothMapAppObserver: onReceive
09-12 12:32:24.425  4246  4246 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-12 12:32:24.431  1864  2260 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 12:32:24.432   872  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-12 12:32:24.435  3704  3704 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-12 12:32:24.453  1897  1897 I Keyboard.Facilitator: resetDictionaries() : en_US
09-12 12:32:24.475  1967  1967 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-12 12:32:24.490   872  2166 I ActivityManager: Start proc 4485:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-12 12:32:24.506  1897  4484 I Keyboard.Facilitator.DecoderInitializer: run()
09-12 12:32:24.517  1897  4484 I Decoder : createOrResetDecoder
09-12 12:32:24.525   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 12:32:24.535  4485  4485 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-12 12:32:24.539  1502  1502 I ConfigService: onCreate
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 12:32:24.548  1502  4497 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 12:32:24.548  1502  4497 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-12 12:32:24.551   872  2165 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3862 uid 10000
09-12 12:32:24.552  1897  1897 I Keyboard.Facilitator: onFinishInput()
09-12 12:32:24.551  1502  4497 W SQLiteOpenHelper: Opened config.db in read-only mode
09-12 12:32:24.553  1983  2068 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-12 12:32:24.557   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-12 12:32:24.558   872   884 E PackageManager: Failed to write settings, restoring backup
09-12 12:32:24.558   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 12:32:24.558   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 12:32:24.558   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 12:32:24.558   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 12:32:24.558   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 12:32:24.558   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:32:24.558   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.558   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 12:32:24.563   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-12 12:32:24.563   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 12:32:24.563   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 12:32:24.563   872   885 E DropBoxManagerService: 	... 13 more
09-12 12:32:24.566   872  2167 I ActivityManager: Start proc 4498:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-12 12:32:24.567  1983  2068 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 12:32:24.567  1983  2068 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1983
09-12 12:32:24.567  1983  2068 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.567  1983  2068 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: Can't write: system_app_crash
09-12 12:32:24.571   872  4504 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 12:32:24.571   872  4504 E DropBoxManagerService: 	... 5 more
09-12 12:32:24.572   872   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 12:32:24.577  1983  2068 I Process : Sending signal. PID: 1983 SIG: 9
09-12 12:32:24.578  1897  4484 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-12 12:32:24.654  1897  4484 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-12 12:32:24.662  1897  4484 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-12 12:32:24.662  1897  4484 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-12 12:32:24.665  1897  4484 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-12 12:32:24.665  1897  4484 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 12:32:24.667  1897  4484 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-12 12:32:24.667  4485  4485 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-12 12:32:24.668  1897  4484 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 12:32:24.671   872  1298 W InputDispatcher: channel 'c3d1ce5 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-12 12:32:24.671   872  1386 D GraphicsStats: Buffer count: 1
09-12 12:32:24.671   872  1298 E InputDispatcher: channel 'c3d1ce5 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-12 12:32:24.671   872  1687 I WindowState: WIN DEATH: Window{c3d1ce5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-12 12:32:24.671   872  1687 W InputDispatcher: Attempted to unregister already unregistered input channel 'c3d1ce5 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-12 12:32:24.676   872  2169 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1983) has died
09-12 12:32:24.677   872  2169 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-12 12:32:24.680  1897  4484 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 12:32:24.680  1897  4484 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 12:32:24.680  1897  4484 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-12 12:32:24.680   872  2169 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-12 12:32:24.681  1897  4484 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-12 12:32:24.681  1897  4484 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 12:32:24.681  1897  4484 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-12 12:32:24.701   872   885 I ActivityManager: Start proc 4517:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 12:32:24.719  4485  4530 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 12:32:24.724   872  2167 I ActivityManager: Start proc 4531:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-12 12:32:24.748  1697  4527 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-12 12:32:24.750  1697  4527 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:32:24.758  4517  4517 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:32:24.758  4517  4517 D AndroidRuntime: Shutting down VM
09-12 12:32:24.766  4517  4517 E AndroidRuntime: FATAL EXCEPTION: main
09-12 12:32:24.766  4517  4517 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4517
09-12 12:32:24.766  4517  4517 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 12:32:24.766  4517  4517 E AndroidRuntime: 	... 10 more
09-12 12:32:24.767   872  1999 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 12:32:24.768   872  4544 E DropBoxManagerService: Can't write: system_app_crash
09-12 12:32:24.768   872  4544 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 12:32:24.768   872  4544 E DropBoxManagerService: 	... 5 more
09-12 12:32:24.768  4517  4517 I Process : Sending signal. PID: 4517 SIG: 9
09-12 12:32:24.785  4531  4531 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-12 12:32:24.787  1697  4527 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-12 12:32:24.788  1697  4527 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-12 12:32:24.797   872  2105 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4517) has died
09-12 12:32:24.798   872  2105 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.799  4485  4513 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.800  4485  4513 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 12:32:24.812   872   885 I ActivityManager: Start proc 4547:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 12:32:24.815   872  1990 I ActivityManager: Killing 3756:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-12 12:32:24.826  1502  1502 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-12 12:32:24.827  1502  1502 D AndroidRuntime: Shutting down VM
09-12 12:32:24.829  1502  1502 E AndroidRuntime: FATAL EXCEPTION: main
09-12 12:32:24.829  1502  1502 E AndroidRuntime: Process: com.google.process.gapps, PID: 1502
09-12 12:32:24.829  1502  1502 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 12:32:24.829  1502  1502 E AndroidRuntime: 	... 8 more
09-12 12:32:24.851  4485  4513 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.856  4485  4530 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 12:32:24.856  4485  4530 E AndroidRuntime: Process: android.process.acore, PID: 4485
09-12 12:32:24.856  4485  4530 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 12:32:24.856  4485  4530 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 12:32:24.858  4485  4513 I Process : Sending signal. PID: 4485 SIG: 9
09-12 12:32:24.893   872   883 I ActivityManager: Process android.process.acore (pid 4485) has died
09-12 12:32:24.894   872   883 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms

```
