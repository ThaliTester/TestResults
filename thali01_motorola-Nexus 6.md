#### Test 84648740f6d448c_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 17:17:45.111  1513  1513 I ConfigService: onDestroy
,09-09 17:17:46.443  3804  3804 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 17:17:46.449  3804  3804 D AndroidRuntime: CheckJNI is OFF
09-09 17:17:46.493  3804  3804 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 17:17:46.544  3804  3804 I Radio-JNI: register_android_hardware_Radio DONE
09-09 17:17:46.567  3804  3804 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 17:17:46.572   872  1944 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 17:17:46.601  2071  2085 W SearchService: Abort, client detached.
09-09 17:17:46.608  3804  3804 D AndroidRuntime: Shutting down VM
09-09 17:17:46.613  2071  2071 I HotwordDetector: Closing mic
09-09 17:17:46.613  2071  2340 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@63729ed
09-09 17:17:46.613  2071  2355 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 17:17:46.634   872  1948 I ActivityManager: Start proc 3814:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 17:17:46.678   376  2357 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 17:17:46.681   376  2357 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 17:17:46.691   376  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 17:17:46.693  2071  2354 I MicroRecognitionRnrImpl: Detection finished
09-09 17:17:46.694  2071  2344 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 17:17:46.717  3814  3814 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 17:17:46.746  3814  3814 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 17:17:46.754  3814  3814 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8206-8210)
09-09 17:17:46.754  3814  3814 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:17:46.777  3814  3814 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5cd4028}
09-09 17:17:46.780  3814  3814 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:17:46.780  3814  3814 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 17:17:46.789  3814  3814 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 17:17:46.790  3814  3814 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 17:17:46.810  3814  3814 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 17:17:46.831  3814  3814 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 17:17:46.831  3814  3814 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 17:17:46.831  3814  3814 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 17:17:46.831  3814  3814 I Adreno  : Build Date                       : 10/20/15
09-09 17:17:46.831  3814  3814 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 17:17:46.831  3814  3814 I Adreno  : Local Branch                     : M14
09-09 17:17:46.831  3814  3814 I Adreno  : Remote Branch                    : 
09-09 17:17:46.831  3814  3814 I Adreno  : Remote Branch                    : 
09-09 17:17:46.831  3814  3814 I Adreno  : Reconstruct Branch               : 
,09-09 17:17:46.902   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c1cd3f1:true
,09-09 17:17:46.962  3814  3814 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 17:17:46.978  3814  3814 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 17:17:47.041  3814  3851 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 17:17:47.051  3814  3838 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 17:17:47.116  3814  3851 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 17:17:47.183   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +567ms
,09-09 17:17:47.187  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-09 17:17:47.254  3814  3814 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3814
,09-09 17:17:47.355  3814  3814 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 17:17:47.443   872  2037 I ActivityManager: Killing 3227:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 17:17:47.486   872  2037 I ActivityManager: Killing 3010:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-09 17:17:47.584  3814  3855 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1684014800
,09-09 17:17:47.589  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 17:17:47.589  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 17:17:47.589  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 17:17:47.589  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 17:17:47.589  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 17:17:47.589  3814  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c3852c added. We now have 1 listener(s)
,09-09 17:17:47.594  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 17:17:47.594  3814  3855 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:17:47.595  3814  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:17:47.595  3814  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 17:17:47.598  3814  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2899ffb added. We now have 1 listener(s)
09-09 17:17:47.598  3814  3855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:17:47.601   872  1314 D WifiService: New client listening to asynchronous messages
09-09 17:17:47.602  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:17:47.602  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 17:17:47.602  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 17:17:47.602  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 17:17:47.602  3814  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 17:17:47.604  3814  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:47.605  3814  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-09 17:17:47.608  3814  3855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-09 17:17:47.609  3814  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:47.609  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:47.609  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:47.609  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:47.609  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:47.609  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:47.609  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:47.609  3814  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:47.609  3814  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 17:17:47.609  3814  3855 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:47.609  3814  3855 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 17:17:47.740  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:47.742  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:47.745  3814  3814 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 17:17:48.454  3814  3864 W jxcore-log: Initializing JXcore engine
,09-09 17:17:48.455  3814  3864 W jxcore-log: JXcore engine is ready
,09-09 17:17:48.496  3864  3864 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 17:17:48.496  3864  3864 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10933]" dev="sockfs" ino=10933 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 17:17:48.496  3864  3864 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 17:17:48.496  3864  3864 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26688]" dev="sockfs" ino=26688 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 17:17:48.511  3814  3864 W jxcore-log: Starting JXcore engine
,09-09 17:17:48.593  3814  3864 W jxcore-log: Platform android
09-09 17:17:48.593  3814  3864 W jxcore-log: 
,09-09 17:17:48.593  3814  3864 W jxcore-log: Process ARCH arm
09-09 17:17:48.593  3814  3864 W jxcore-log: 
,09-09 17:17:48.860  3814  3864 I jxcore-log: JXcore Cordova bridge is ready!
09-09 17:17:48.860  3814  3864 I jxcore-log: 
,09-09 17:17:48.860  3814  3864 W jxcore-log: JXcore engine is started
,09-09 17:17:48.869  3814  3855 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 17:17:48.880  3814  3814 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 17:17:52.232   872  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 17:17:52.467  1701  1711 W art     : Suspending all threads took: 9.396ms
,09-09 17:17:54.199   872   885 I ActivityManager: Waited long enough for: ServiceRecord{f9997a8 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,09-09 17:17:56.818  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:17:56.827  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:17:56.830  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:17:56.872  1513  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 17:17:56.872  1513  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 17:17:56.872  1513  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 17:17:56.872  1513  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:17:56.900  3544  3544 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 17:17:56.901  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 17:17:56.901  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-09 17:17:58.015  3623  3874 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 17:17:58.060  3623  3875 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 17:17:58.098  1513  2989 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 17:17:58.098  1513  2989 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 17:17:58.098  1513  2989 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:17:58.098  1513  2989 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:17:58.176  1513  2407 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 17:17:58.176  1513  2407 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 17:17:58.177  1513  2407 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:17:58.177  1513  2407 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:17:58.210  3623  3875 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 17:17:58.211  3623  3874 E BooksSync: Soft error
09-09 17:17:58.211  3623  3874 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 17:17:58.211  3623  3874 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 17:17:58.211  3623  3874 E BooksSync: Sync error
09-09 17:17:58.211  3623  3874 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 17:17:58.211  3623  3874 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 17:17:58.212  3623  3874 I BooksSync: Finished books sync
,09-09 17:17:58.224   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129428, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 17:17:58.963  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 17:17:58.963  3814  3864 I jxcore-log: 
,09-09 17:17:58.966  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 17:17:58.966  3814  3864 I jxcore-log: 
,09-09 17:17:58.974  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:58.974  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:58.974  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:58.974  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:58.974  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:58.974  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:58.974  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:58.974  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:58.981  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:58.987  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 17:17:58.987  3814  3864 I jxcore-log: 
,09-09 17:17:58.994  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 17:17:58.994  3814  3864 I jxcore-log: 
,09-09 17:17:59.517  3814  3864 D executeNativeTests: Running unit tests
,09-09 17:17:59.575  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:17:59.575  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b added. We now have 2 listener(s)
,09-09 17:17:59.576  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:17:59.576  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:17:59.576  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:17:59.576  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:17:59.576  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 added. We now have 2 listener(s)
09-09 17:17:59.576  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:17:59.577  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:17:59.581  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:59.593  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:59.593  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:59.593  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:59.593  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:59.593  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:59.593  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:59.593  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:59.593  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:59.599  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:59.600  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:59.606  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:59.608  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 17:17:59.609  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:59.611  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:59.611  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 17:17:59.615  3814  3864 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 17:17:59.616  3814  3864 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 17:17:59.616  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 17:17:59.617  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 17:17:59.617  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:59.619  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:59.620  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.620  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.621  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.621  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.622  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:59.622  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:17:59.622  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b removed from the list
09-09 17:17:59.623  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.623  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 removed from the list
09-09 17:17:59.623  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.623  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.625  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.625  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:59.628  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.628  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.628  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:59.629  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
,09-09 17:17:59.634  3814  3864 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 17:17:59.636  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:59.636  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.636  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.637  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.637  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.637  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.638  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.638  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.638  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
,09-09 17:17:59.638  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.638  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.639  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.639  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.639  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:59.642  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.642  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:17:59.642  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.643  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
,09-09 17:17:59.649  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 17:17:59.649  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-09 17:17:59.649  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:17:59.649  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:17:59.649  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:17:59.650  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:17:59.651  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:17:59.651  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.651  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.651  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.652  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.652  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.652  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.652  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.652  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:59.652  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.652  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.652  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.652  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.652  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.652  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.653  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.654  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.654  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.654  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.654  3814  3864 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 17:17:59.656  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:59.663  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:59.663  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:59.663  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:59.663  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:59.663  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:59.663  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:59.663  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:59.663  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:59.666  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:59.667  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:59.667  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:59.667  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:59.667  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:59.667  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:59.667  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:17:59.669  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:59.671  3814  3864 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 17:17:59.671  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:17:59.672  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:59.678  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:17:59.680  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:17:59.681  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:17:59.684  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 17:17:59.687  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 17:17:59.687  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:17:59.688  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 17:17:59.690  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 17:17:59.691  3814  3864 D BluetoothAdapter: STATE_ON
,09-09 17:17:59.697  2704  2886 D BtGatt.GattService: registerClient() - UUID=d1a5400c-3b87-479f-8e7e-7e46e49f8467
,09-09 17:17:59.698  2704  2724 D BtGatt.GattService: onClientRegistered() - UUID=d1a5400c-3b87-479f-8e7e-7e46e49f8467, clientIf=5
,09-09 17:17:59.699  3814  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 17:17:59.700  2704  2716 D BtGatt.GattService: start scan with filters
,09-09 17:17:59.707  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:17:59.708  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 17:17:59.708  2704  2727 D BtGatt.ScanManager: handling starting scan
09-09 17:17:59.708  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:17:59.708  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:17:59.709  2704  2727 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:17:59.712  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:59.712  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:17:59.713  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:59.716  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:17:59.717  2704  2724 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 17:17:59.717  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.717  2704  2727 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 17:17:59.722  2704  2724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 17:17:59.722  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:17:59.723  2704  2727 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 17:17:59.723  2704  2727 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 17:17:59.724  3814  3864 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:17:59.729  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:59.730  3814  3864 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:17:59.730  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:59.730  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 17:17:59.731  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.731  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 17:17:59.732  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 17:17:59.732  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:59.733  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:59.733  2704  2724 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 17:17:59.734  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.733  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:59.735  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 17:17:59.736  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 17:17:59.738  3814  3864 D BluetoothAdapter: STATE_ON
,09-09 17:17:59.740  2704  2716 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:17:59.740  2704  2724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 17:17:59.740  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.741  2704  2853 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 17:17:59.741  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:59.741  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:17:59.741  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 17:17:59.741  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:17:59.742  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 17:17:59.742  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:59.743  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 17:17:59.743  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 17:17:59.743  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:17:59.743  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:17:59.744  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:59.744  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.744  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:17:59.744  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
,09-09 17:17:59.744  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:59.744  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
,09-09 17:17:59.744  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:59.744  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:59.744  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,09-09 17:17:59.745  3814  3864 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 17:17:59.745  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:17:59.745  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:59.746  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:59.749  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:59.749  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:59.749  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:59.749  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:59.749  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:59.749  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:59.749  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:59.749  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:59.750  2704  2724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 17:17:59.750  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.750  2704  2727 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:17:59.751  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:59.751  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:59.751  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:59.752  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:59.752  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:59.752  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:59.752  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:17:59.755  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:59.755  3814  3864 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 17:17:59.755  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:17:59.760  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:59.761  2704  2724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:17:59.761  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:17:59.762  2704  2727 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 17:17:59.763  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:17:59.764  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:17:59.764  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:17:59.768  2704  2724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:17:59.768  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.769  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:17:59.770  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:17:59.770  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:17:59.771  3814  3864 D BluetoothAdapter: STATE_ON
,09-09 17:17:59.775  2704  2886 D BtGatt.GattService: registerClient() - UUID=5737bfc5-423f-4ccc-9fbd-4d671ee5456c
,09-09 17:17:59.775  2704  2724 D BtGatt.GattService: onClientRegistered() - UUID=5737bfc5-423f-4ccc-9fbd-4d671ee5456c, clientIf=5
09-09 17:17:59.775  3814  3824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 17:17:59.776  2704  2716 D BtGatt.GattService: start scan with filters
,09-09 17:17:59.781  2704  2727 D BtGatt.ScanManager: handling starting scan
09-09 17:17:59.781  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:17:59.781  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 17:17:59.781  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:17:59.781  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:17:59.785  2704  2724 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:17:59.785  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.785  2704  2727 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 17:17:59.786  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:17:59.786  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:17:59.786  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:17:59.789  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 17:17:59.789  2704  2724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 17:17:59.789  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.789  2704  2727 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:17:59.790  2704  2727 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 17:17:59.794  3814  3864 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:17:59.797  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:59.797  3814  3864 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 17:17:59.797  2704  2724 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 17:17:59.797  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.797  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.797  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:17:59.798  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.798  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:17:59.798  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:59.798  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:59.798  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:59.798  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:59.798  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:17:59.799  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 17:17:59.800  3814  3864 D BluetoothAdapter: STATE_ON
09-09 17:17:59.800  2704  2886 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:17:59.801  2704  2715 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:17:59.802  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:59.802  2704  2724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 17:17:59.802  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.803  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:17:59.803  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:17:59.803  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:17:59.803  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:17:59.805  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:59.806  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:17:59.806  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:17:59.806  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:17:59.806  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:59.808  2704  2724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 17:17:59.808  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.808  2704  2727 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:17:59.808  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:59.808  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:59.808  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:59.809  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.809  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.809  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:59.809  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.809  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.809  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.809  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.810  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.810  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.811  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.812  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.812  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.812  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.813  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.813  2704  2724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:17:59.813  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.813  2704  2727 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 17:17:59.814  3814  3864 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:17:59.816  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:59.820  2704  2724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:17:59.820  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.822  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:59.822  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:59.822  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:59.822  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:59.822  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:59.822  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:59.822  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:59.822  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:59.825  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:59.825  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:59.826  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:59.826  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:59.826  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:59.826  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:59.826  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:17:59.828  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:59.829  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:59.831  3814  3864 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 17:17:59.832  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:17:59.836  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:17:59.838  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:17:59.838  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:17:59.843  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:17:59.843  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:17:59.843  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 17:17:59.844  3814  3864 D BluetoothAdapter: STATE_ON
09-09 17:17:59.847  2704  2853 D BtGatt.GattService: registerClient() - UUID=e8a98e65-7654-4ce6-bab2-d7491b092914
09-09 17:17:59.848  2704  2724 D BtGatt.GattService: onClientRegistered() - UUID=e8a98e65-7654-4ce6-bab2-d7491b092914, clientIf=5
09-09 17:17:59.849  3814  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 17:17:59.850  2704  2886 D BtGatt.GattService: start scan with filters
09-09 17:17:59.855  2704  2727 D BtGatt.ScanManager: handling starting scan
09-09 17:17:59.855  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:17:59.856  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:17:59.857  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:17:59.857  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:17:59.861  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:17:59.861  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:17:59.861  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:17:59.862  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 17:17:59.862  2704  2724 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:17:59.863  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.863  2704  2727 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 17:17:59.866  3814  3864 I io.jxcore.node.ConnectionHelper: start: OK
09-09 17:17:59.866  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.866  3814  3864 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:17:59.866  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.866  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:17:59.866  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.866  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:17:59.866  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:59.867  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:59.867  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:59.867  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:59.867  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:17:59.867  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 17:17:59.868  2704  2724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 17:17:59.868  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.868  2704  2727 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:17:59.868  2704  2727 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 17:17:59.868  3814  3864 D BluetoothAdapter: STATE_ON
09-09 17:17:59.869  2704  2715 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:17:59.869  2704  2716 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:17:59.870  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:59.870  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:17:59.870  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 17:17:59.870  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:17:59.870  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 17:17:59.871  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:59.871  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:17:59.871  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:17:59.872  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:17:59.872  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:59.873  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.874  3814  3864 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:17:59.874  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.874  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:59.874  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.874  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.874  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:59.874  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.875  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.875  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list,
09-09 17:17:59.875  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.875  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.875  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:17:59.875  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:59.875  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:59.876  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.876  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.877  2704  2724 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 17:17:59.877  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.877  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.877  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.878  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.878  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.878  3814  3864 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 17:17:59.879  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.879  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.879  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.879  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:59.879  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.879  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.879  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
,09-09 17:17:59.880  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.880  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.880  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.880  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.880  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.880  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:17:59.880  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.882  2704  2724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 17:17:59.882  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.883  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.883  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.883  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.883  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.884  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:17:59.884  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.885  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.885  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.885  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.885  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:17:59.885  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.885  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
,09-09 17:17:59.885  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.885  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.885  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.885  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.885  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.885  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.885  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.887  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.887  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.887  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.887  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.888  3814  3864 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 17:17:59.888  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.888  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.888  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.888  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.888  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.888  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.888  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.888  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.889  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.889  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.889  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.889  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.889  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.889  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.889  2704  2724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 17:17:59.889  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.890  2704  2727 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:17:59.890  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.890  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.890  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.891  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.891  3814  3864 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 17:17:59.891  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.891  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.892  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.892  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.892  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.892  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.892  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.892  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.892  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.892  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.892  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.892  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.892  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.892  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.893  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.893  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.893  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.893  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.894  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:17:59.894  2704  2724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:17:59.895  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.895  2704  2727 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 17:17:59.896  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:59.896  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:17:59.896  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:59.897  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:17:59.898  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:59.898  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.898  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.898  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.899  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.901  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.901  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.901  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.901  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.901  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.901  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.901  2704  2724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:17:59.901  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.902  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.902  2704  2724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:17:59.902  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.902  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.904  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.904  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.904  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.904  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.905  3814  3864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:59.905  3814  3864 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:17:59.905  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 17:17:59.908  3814  3864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:59.908  3814  3864 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 17:17:59.908  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:17:59.908  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:17:59.908  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:17:59.908  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:17:59.909  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:17:59.910  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:17:59.910  3814  3864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 17:17:59.911  3814  3864 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:17:59.911  3814  3864 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 17:17:59.911  3814  3864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:59.911  3814  3864 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:17:59.911  3814  3864 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 17:17:59.911  3814  3864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:59.911  3814  3864 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:17:59.911  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 17:17:59.915  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 17:17:59.915  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 17:17:59.916  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 17:17:59.916  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 17:17:59.916  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 17:17:59.916  3814  3864 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 17:17:59.916  3814  3864 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:59.916  3814  3864 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 17:17:59.917  3814  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
09-09 17:17:59.917  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.917  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.917  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.918  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.918  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.918  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.918  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 17:17:59.918  3814  3876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:59.919  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.919  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.919  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.919  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.919  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.919  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.920  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.920  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.921  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.921  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.921  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.921  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.922  3814  3864 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 17:17:59.923  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.923  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.923  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.924  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.924  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.924  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.924  3814  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
09-09 17:17:59.924  3814  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
09-09 17:17:59.924  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.924  2704  2850 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-09 17:17:59.924  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.925  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.925  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.925  3814  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
09-09 17:17:59.925  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.925  3814  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
09-09 17:17:59.925  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.925  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.925  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.926  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.926  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.926  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.926  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.926  3814  3864 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 17:17:59.927  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.927  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.927  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.927  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.927  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.927  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.927  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.927  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.927  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.927  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.928  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.928  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.928  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.928  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.929  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.929  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.929  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.929  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.930  3814  3864 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 17:17:59.930  3814  3864 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 17:17:59.930  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:59.930  3814  3864 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 17:17:59.930  3814  3864 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:17:59.930  3814  3864 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 17:17:59.930  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:59.930  3814  3864 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 17:17:59.930  3814  3864 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:17:59.930  3814  3864 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:17:59.930  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:59.931  3814  3864 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 17:17:59.931  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.931  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.931  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.931  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.931  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.931  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.931  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.931  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.931  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.931  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.931  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.931  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.932  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.932  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:59.933  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.933  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.933  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.933  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.933  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.934  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.934  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.934  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.934  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.934  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.934  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:59.934  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.934  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.934  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.934  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.934  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.934  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.934  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.934  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.935  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.935  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:59.935  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.936  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.936  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.936  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.936  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.936  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.936  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.936  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.936  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.936  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.936  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.936  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.937  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.937  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.937  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.937  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.939  3814  3864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 17:17:59.939  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:59.939  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 17:17:59.940  3814  3864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 17:17:59.940  3814  3864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 17:17:59.940  3814  3814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 17:17:59.941  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 17:17:59.941  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:59.941  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.941  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 17:17:59.941  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 17:17:59.941  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 17:17:59.941  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.941  3814  3864 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 17:17:59.941  3814  3878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:59.941  3814  3814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 17:17:59.942  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.942  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.942  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:59.942  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:59.942  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:59.942  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.942  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.943  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:59.943  3814  3878 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 17:17:59.943  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:59.943  3814  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 17:17:59.943  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:59.943  3814  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 17:17:59.943  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:59.944  3814  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 17:17:59.944  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.944  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.944  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:59.944  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:59.944  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.944  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.944  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.944  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.944  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.944  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
,09-09 17:17:59.944  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.944  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.945  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:59.945  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:59.945  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:59.945  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.945  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.946  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.946  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
,09-09 17:17:59.947  3814  3864 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 17:17:59.947  3814  3864 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 17:17:59.947  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:17:59.947  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:59.947  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-09 17:17:59.947  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:59.947  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.947  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.947  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.947  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:59.948  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.948  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.948  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.948  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:59.948  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.948  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.948  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.948  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:59.949  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.949  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.949  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:59.949  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.953  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.953  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:59.953  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:59.953  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:59.953  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.953  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.953  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
,09-09 17:17:59.953  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:59.953  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
09-09 17:17:59.953  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.953  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.953  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.953  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.953  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.954  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:59.954  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:17:59.954  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:59.954  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
,09-09 17:17:59.955  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:59.955  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:59.955  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:59.955  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:59.955  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.955  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.955  3814  3864 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4020b not in the list
09-09 17:17:59.955  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:59.956  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
,09-09 17:17:59.956  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:59.956  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.956  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.956  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:59.956  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:59.957  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:59.957  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:59.957  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:59.957  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af668e8 not in the list
,09-09 17:17:59.958  3814  3864 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 17:17:59.958  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:59.958  3814  3864 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-09 17:17:59.958  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:59.958  3814  3864 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-09 17:17:59.958  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:59.960  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 17:17:59.960  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 17:17:59.961  3814  3864 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-09 17:17:59.961  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-09 17:17:59.961  3814  3864 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-09 17:17:59.961  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:17:59.961  3814  3864 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-09 17:17:59.961  3814  3864 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-09 17:17:59.961  3814  3864 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-09 17:17:59.962  3814  3864 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 17:17:59.962  3814  3864 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 17:17:59.962  3814  3864 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-09 17:17:59.962  3814  3864 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-09 17:17:59.962  3814  3864 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-09 17:17:59.963  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,09-09 17:17:59.963  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc7218a added. We now have 2 listener(s)
,09-09 17:17:59.963  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:59.965  3814  3864 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 17:17:59.965   872  1944 D WifiService: setWifiEnabled: true pid=3814, uid=10000
,09-09 17:17:59.965   872  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 17:17:59.966  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:59.966  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@abd83fb added. We now have 3 listener(s)
,09-09 17:17:59.966  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:17:59.971  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:17:59.971  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9dc18 added. We now have 4 listener(s)
,09-09 17:17:59.971  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:59.973  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:17:59.973  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d23671 added. We now have 5 listener(s)
09-09 17:17:59.973  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:17:59.975   872  1747 D WifiService: setWifiEnabled: false pid=3814, uid=10000,
09-09 17:17:59.975   872  1747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 17:17:59.980  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:59.981  2704  2720 D BluetoothAdapterState: Current state: ON, message: 23
09-09 17:17:59.981  2704  2720 D BluetoothAdapterProperties: Setting state to 13
09-09 17:17:59.981  2704  2720 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 17:17:59.982  2704  2720 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 17:17:59.982  2704  2720 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:17:59.982  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:17:59.983  2704  2724 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:17:59.983  2704  2720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 17:17:59.983  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:59.983  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:59.983  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:59.983  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:59.983  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:59.983  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:59.983  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:59.983  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:59.984  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:59.984  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:59.984  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:59.985  2704  2704 D HeadsetService: Received stop request...Stopping profile...
09-09 17:17:59.987   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:59.987   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:59.987   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:59.987  1370  1387 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:59.988  1370  1370 D HeadsetProfile: Bluetooth service disconnected
09-09 17:17:59.988  1997  2168 D BluetoothHeadset: Proxy object disconnected
,09-09 17:17:59.989  2704  2704 D A2dpService: Received stop request...Stopping profile...
,09-09 17:17:59.989  2704  2858 D A2dpStateMachine: Exit Disconnected: -1
,09-09 17:17:59.991   872   872 D BluetoothA2dp: Proxy object disconnected
,09-09 17:17:59.991  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:59.991  1370  1370 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:59.992  2704  2704 D HidService: Received stop request...Stopping profile...
09-09 17:17:59.992  2704  2704 D HidService: Stopping Bluetooth HidService
09-09 17:17:59.993  1370  1370 D BluetoothInputDevice: Proxy object disconnected
09-09 17:17:59.993  1370  1370 D HidProfile: Bluetooth service disconnected
,09-09 17:17:59.993  2704  2704 V BluetoothAdapterState: isTurningOff()=true
09-09 17:17:59.993  2704  2704 V BluetoothAdapterState: isTurningOn()=false
09-09 17:17:59.993  2704  2704 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:17:59.993  2704  2704 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:17:59.996  2704  2704 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:17:59.996  2704  2704 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:17:59.997  2704  2821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 17:17:59.997  2704  2821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:17:59.997  2704  2821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:17:59.997  2704  2704 V BluetoothAdapterState: isTurningOff()=true
09-09 17:17:59.997  2704  2704 V BluetoothAdapterState: isTurningOn()=false
09-09 17:17:59.997  2704  2704 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:17:59.997  2704  2704 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:17:59.997  2704  2724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 17:17:59.997  2704  2724 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 17:17:59.998  2704  2704 D HealthService: Received stop request...Stopping profile...
09-09 17:17:59.998  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:00.002  2704  2724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-09 17:18:00.002  2704  2821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:18:00.002  2704  2821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:18:00.002  2704  2821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:18:00.002  2704  2821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 17:18:00.002  2704  2821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:18:00.002  2704  2821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 17:18:00.002  2704  2704 V BluetoothAdapterState: isTurningOff()=true
09-09 17:18:00.003  2704  2704 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:00.003  2704  2704 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:00.003  2704  2704 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:00.003  2704  2704 D PanService: Received stop request...Stopping profile...
,09-09 17:18:00.004  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:00.004  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:00.004  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:00.004  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:00.004  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:00.004  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:00.004  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:00.004  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:00.004  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:18:00.004  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:18:00.005  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:00.005  2704  2704 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 17:18:00.005  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 17:18:00.005  1370  1370 D PanProfile: Bluetooth service disconnected
09-09 17:18:00.006  2704  2724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 17:18:00.006  2704  2704 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 17:18:00.007  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:00.007  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:18:00.008  2704  2704 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 17:18:00.008  2704  2704 D BluetoothMapService: stop()
09-09 17:18:00.008  2704  2704 D BluetoothMapAppObserver: deinitObservers()
09-09 17:18:00.009  2704  2704 D BluetoothMapAppObserver: removeReceiver()
09-09 17:18:00.009   872  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 17:18:00.009   872  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 17:18:00.009   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 17:18:00.009   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:18:00.010  2704  2704 V BluetoothAdapterState: isTurningOff()=true
09-09 17:18:00.010  2704  2704 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:00.010  2704  2704 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:00.010  2704  2704 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:00.010  2704  2704 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-09 17:18:00.010  2704  2724 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 17:18:00.011  2704  2704 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:18:00.011  2704  2704 V BluetoothAdapterState: isTurningOff()=true
09-09 17:18:00.011  2704  2704 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:00.011  2704  2704 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:00.012  2704  2704 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:00.012  2704  2704 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:18:00.012  2704  2704 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 17:18:00.013  2704  2704 D BluetoothMapService: MAP Service closeService in
,09-09 17:18:00.013  2704  2704 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 17:18:00.013  2704  2704 D ObexServerSockets0: shutdown(block = true)
09-09 17:18:00.014  2704  2887 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 17:18:00.014  2704  2704 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 17:18:00.014  2704  2888 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 17:18:00.016  2704  2850 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 17:18:00.016  1370  1370 D BluetoothMap: Proxy object disconnected
09-09 17:18:00.016  1370  1370 D MapProfile: Bluetooth service disconnected
09-09 17:18:00.017  2704  2704 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 17:18:00.017  2704  2704 V BluetoothAdapterState: isTurningOff()=true
09-09 17:18:00.017  2704  2704 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:00.017  2704  2704 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:00.017  2704  2704 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:00.018  2704  2720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 17:18:00.018  2704  2720 D BluetoothAdapterProperties: Setting state to 15
09-09 17:18:00.018  2704  2720 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 17:18:00.018  2704  2720 I BluetoothAdapterState: Entering BleOnState
09-09 17:18:00.019   872  2165 D DhcpClient: Clearing IP address
09-09 17:18:00.019   372   870 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:18:00.019  2704  2704 D BluetoothMapService: cleanup()
09-09 17:18:00.020  2704  2704 D BluetoothMapService: MAP Service closeService in
09-09 17:18:00.022   372   870 D CommandListener: Setting iface cfg
09-09 17:18:00.024  1513  3485 V NativeCrypto: Read error: ssl=0xaecf2200: I/O error during system call, Connection timed out
09-09 17:18:00.025  1513  3485 V NativeCrypto: SSL shutdown failed: ssl=0xaecf2200: I/O error during system call, Broken pipe
09-09 17:18:00.029   872  2243 D DhcpClient: Receive thread stopped
09-09 17:18:00.029   872  1945 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-09 17:18:00.029   872  2107 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-09 17:18:00.033   872  2107 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-09 17:18:00.034   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,09-09 17:18:00.034   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 17:18:00.035   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 17:18:00.036  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:00.037  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:00.038  2704  2704 I BtOppRfcommListener: stopping Accept Thread
09-09 17:18:00.038  2704  3467 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 17:18:00.038  2704  3467 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 17:18:00.051   872   885 I ActivityManager: Start proc 3882:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-09 17:18:00.051  1370  1381 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 17:18:00.052  1370  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 17:18:00.052   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 17:18:00.052   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:18:00.052   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 17:18:00.053   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 17:18:00.053   872  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-09 17:18:00.054   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 17:18:00.056   372   870 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:18:00.056  1370  2172 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:18:00.058   872  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-09 17:18:00.059   396   396 E Parcel  : Reading a NULL string not supported here.
09-09 17:18:00.061  1370  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:18:00.061  1370  2170 D BluetoothMap: onBluetoothStateChange: up=false
09-09 17:18:00.061   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 17:18:00.062   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 17:18:00.062  1997  2096 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:18:00.062   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:18:00.062  1370  2118 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:18:00.063  2704  2720 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 17:18:00.063  2704  2720 D BluetoothAdapterProperties: Setting state to 16
09-09 17:18:00.063  2704  2720 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-09 17:18:00.063  2704  2720 D BluetoothAdapterProperties: onBleDisable
09-09 17:18:00.063  2704  2720 I BluetoothAdapterState: Entering PendingCommandState
09-09 17:18:00.064  2704  2721 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 17:18:00.064  2704  2821 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 17:18:00.065  2704  2821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 17:18:00.069  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:18:00.069  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:00.069  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:00.069  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:00.069  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:00.069  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:00.069  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:00.069  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:00.069  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:00.069  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:18:00.069  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:00.071  2704  2724 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:18:00.073   872  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:18:00.074  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:00.074  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:00.074  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:00.074  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:00.074  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:00.074  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:00.074  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:00.074  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:00.074  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:00.075  1863  2198 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:18:00.076  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:00.076  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:00.077  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:00.078  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:00.079  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:00.080  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:00.093   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:18:00.103  3882  3882 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 17:18:00.111   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:18:00.112   872  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-09 17:18:00.112   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:18:00.114   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-09 17:18:00.117  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:00.122  3404  3404 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1c3852c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-09 17:18:00.124  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:18:00.126  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:00.131   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@51e5d1b:true
,09-09 17:18:00.132  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:00.145   872  1943 I ActivityManager: Start proc 3900:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 17:18:00.163  3882  3882 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 17:18:00.167   372   870 E Netd    : netlink response contains error (No such file or directory)
,09-09 17:18:00.168   872  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 17:18:00.168   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 17:18:00.172  3882  3882 D BluetoothMap: Create BluetoothMap proxy object
,09-09 17:18:00.178  3900  3900 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 17:18:00.187  3882  3882 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 17:18:00.201  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:18:00.207   872  1948 I ActivityManager: Killing 3404:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 17:18:00.275  2704  2724 I bt_hci  : shut_down
,09-09 17:18:00.276  2704  2728 D bt_hwcfg: hw_epilog_process
,09-09 17:18:00.293  2704  2728 I bt_vendor: low_power_mode_cb
,09-09 17:18:00.321  2704  2728 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-09 17:18:00.321  2704  2728 I bt_vendor: epilog_cb
,09-09 17:18:00.321  2704  2728 I bt_hci  : epilog_finished_callback
,09-09 17:18:00.325  2704  2724 I bt_hci_h4: hal_close
,09-09 17:18:00.325  2704  2724 I bt_userial_vendor: device fd = 51 close
,09-09 17:18:00.388  3900  3900 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:00.388  3900  3900 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:00.388  3900  3900 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
,09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:00.388  3900  3900 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:00.388  3900  3900 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:00.388  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:00.389  3900  3900 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:00.389  3900  3900 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:00.389  3900  3900 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:00.389  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:00.431   872  1526 I ActivityManager: Start proc 3932:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 17:18:00.432   872  1526 I ActivityManager: Killing 3593:com.google.process.gapps/u0a99 (adj 15): empty #17
09-09 17:18:00.444  3814  3814 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:18:00.517  2704  2721 D bt_stack_manager: event_shut_down_stack finished.
09-09 17:18:00.518  2704  2720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 17:18:00.525  2704  2704 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:18:00.525  3932  3932 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 17:18:00.525  2704  2720 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 17:18:00.525  2704  2704 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 17:18:00.525  2704  2704 D BtGatt.GattService: stop()
,09-09 17:18:00.525  2704  2704 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 17:18:00.527  2704  2704 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:18:00.527  2704  2704 V BluetoothAdapterState: isTurningOn()=false
,09-09 17:18:00.527  2704  2704 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:18:00.527  2704  2704 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 17:18:00.527  2704  2720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 17:18:00.527  2704  2720 D BluetoothAdapterProperties: Setting state to 10
,09-09 17:18:00.528  2704  2720 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 17:18:00.530  2704  2720 I BluetoothAdapterState: Entering OffState
,09-09 17:18:00.532   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 17:18:00.566  2704  2704 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 17:18:00.567  2704  2704 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 17:18:00.567  2704  2704 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 17:18:00.567  2704  2721 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 17:18:00.570  2704  2721 D bt_stack_manager: event_clean_up_stack finished.
,09-09 17:18:00.580  2704  2704 I art     : System.exit called, status: 0
,09-09 17:18:00.580  2704  2704 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 17:18:00.633   872  1368 I ActivityManager: Process com.android.bluetooth (pid 2704) has died
,09-09 17:18:00.646  3932  3932 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 17:18:00.685  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:18:00.705   872  2037 I ActivityManager: Start proc 3960:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-09 17:18:00.707  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:18:00.712  3900  3924 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 17:18:00.725   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c468f5:true
,09-09 17:18:00.783  3960  3960 D AdapterServiceConfig: Adding HeadsetService
,09-09 17:18:00.783  3960  3960 D AdapterServiceConfig: Adding A2dpService
,09-09 17:18:00.784  3960  3960 D AdapterServiceConfig: Adding HidService
,09-09 17:18:00.784  3960  3960 D AdapterServiceConfig: Adding HealthService
,09-09 17:18:00.785  3960  3960 D AdapterServiceConfig: Adding PanService
09-09 17:18:00.785  3960  3960 D AdapterServiceConfig: Adding GattService
,09-09 17:18:00.785  3960  3960 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 17:18:00.787   872  1945 I ActivityManager: Killing 2794:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 17:18:00.821  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:00.839  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 17:18:00.843  1701  1701 D SystemUpdateService: onCreate
,09-09 17:18:00.850  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 17:18:00.856  1701  3972 I SystemUpdateService: active receiver: enabled
,09-09 17:18:00.860  1701  3972 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 17:18:00.864  1701  3972 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 17:18:00.864  1701  3972 I SystemUpdateService: now status is 0 (complete)
09-09 17:18:00.864  1701  3972 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 17:18:00.865  1701  3972 I SystemUpdateService: file has been verified
,09-09 17:18:00.865  1701  3972 I SystemUpdateService: OTA package size = 12249756
,09-09 17:18:00.866  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 17:18:00.868  1701  2546 I iu.UploadsManager: num queued entries: 0
09-09 17:18:00.868  1701  2546 I iu.UploadsManager: num updated entries: 0
,09-09 17:18:00.873  1701  3972 I SystemUpdateService: showing system update notification
,09-09 17:18:00.874  1701  2546 I iu.SyncManager: NEXT; no task
,09-09 17:18:00.896  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 17:18:00.898  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 17:18:00.915   872  1368 I ActivityManager: Start proc 3974:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 17:18:00.917  1701  1701 D SystemUpdateService: onDestroy
,09-09 17:18:00.948  3974  3974 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 17:18:00.950  3974  3974 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:18:00.960  3974  3974 D SprintDMHelper: simOperator: 
,09-09 17:18:00.960  3974  3974 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 17:18:00.975   872  1949 I ActivityManager: Start proc 3986:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 17:18:00.976   872  1949 I ActivityManager: Killing 3526:android.process.acore/u0a5 (adj 15): empty #17
,09-09 17:18:01.120   872  1949 I ActivityManager: Start proc 4001:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 17:18:01.128   872  1949 I ActivityManager: Killing 3703:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 17:18:01.206  4001  4001 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 17:18:01.270  4001  4001 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 17:18:01.270  4001  4001 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 17:18:01.270  4001  4001 I GAv4    :   adb logcat -s GAv4
,09-09 17:18:01.286  4001  4001 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 17:18:01.293  4001  4001 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 17:18:01.322  4001  4018 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 17:18:01.437  4001  4001 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 17:18:01.497  4001  4001 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 17:18:01.505  4001  4001 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2958-2961)
,09-09 17:18:01.506  4001  4001 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 17:18:01.519  4001  4001 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d48915c}
,09-09 17:18:01.519  4001  4001 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 17:18:01.520  4001  4001 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 17:18:01.530  4001  4001 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 17:18:01.532  4001  4001 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 17:18:01.547  4001  4001 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 17:18:01.563  4001  4001 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 17:18:01.563  4001  4001 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 17:18:01.563  4001  4001 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 17:18:01.563  4001  4001 I Adreno  : Build Date                       : 10/20/15
09-09 17:18:01.563  4001  4001 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 17:18:01.563  4001  4001 I Adreno  : Local Branch                     : M14
09-09 17:18:01.563  4001  4001 I Adreno  : Remote Branch                    : 
09-09 17:18:01.563  4001  4001 I Adreno  : Remote Branch                    : 
09-09 17:18:01.563  4001  4001 I Adreno  : Reconstruct Branch               : 
,09-09 17:18:01.631  4001  4047 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 17:18:01.633  4001  4001 I NSApplication: Starting up...
,09-09 17:18:01.683   872  1944 I ActivityManager: Start proc 4052:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 17:18:01.684   872  1944 I ActivityManager: Killing 3717:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 17:18:01.759  4052  4052 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 17:18:01.933   872  1949 I ActivityManager: Killing 3430:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 17:18:01.950  3025  3034 W art     : Suspending all threads took: 8.120ms
,09-09 17:18:02.986   872  1943 D WifiService: setWifiEnabled: true pid=3814, uid=10000
,09-09 17:18:02.987   872  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:18:03.001   872  1313 D WifiConfigStore: Loading config and enabling all networks 
,09-09 17:18:03.010  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:18:03.010  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:03.010  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:03.010  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:03.010  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:03.010  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:03.010  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:03.010  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:03.010  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:03.010  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:18:03.011  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:03.014  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:03.014  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:03.014  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:03.014  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:03.014  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:03.014  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:03.014  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:03.014  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:03.014  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:03.015  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:03.015  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:03.049   872  1313 D WifiConfigStore: loaded 0 passpoint configs
,09-09 17:18:03.051   872  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 17:18:03.053   872  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 17:18:03.056   872  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 17:18:03.057   872  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 17:18:03.057   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 17:18:03.057   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 17:18:03.079   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 17:18:03.081   872  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.38 rxSuccessRate=16.00 delta 1000 -> 994
09-09 17:18:03.082   372   870 D CommandListener: Setting iface cfg
,09-09 17:18:03.083   872  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-09 17:18:03.084   872  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 17:18:03.091   872  1312 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 17:18:03.097   872  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 17:18:03.097   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3,
09-09 17:18:03.097   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-09 17:18:03.111   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 17:18:03.229   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 17:18:03.231  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 17:18:03.653  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 17:18:03.688  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 17:18:03.688  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 17:18:03.693   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 17:18:03.704   872  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 17:18:03.705   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:18:03.705   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 17:18:03.731   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:18:03.743   372   870 D CommandListener: Setting iface cfg
09-09 17:18:03.744   872  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 17:18:03.758   872  1315 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-09 17:18:03.760   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 17:18:03.809   872  4075 D DhcpClient: Receive thread started
,09-09 17:18:03.892   872  1313 E native  : do suspend false
,09-09 17:18:03.911   872  2165 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 17:18:03.927   872  4075 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,09-09 17:18:03.928   872  2165 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,09-09 17:18:03.932   872  2165 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 17:18:03.946   872  4075 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 17:18:03.947   872  2165 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 17:18:03.952   372   870 D CommandListener: Setting iface cfg
,09-09 17:18:03.964   872  2165 D DhcpClient: Scheduling renewal in 86399s
,09-09 17:18:03.965   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 17:18:03.981   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 17:18:03.983   872  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 17:18:03.983   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 17:18:03.984   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 17:18:03.986   872  1315 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 17:18:04.002   872  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 17:18:04.058   872  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 17:18:04.059   872  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 17:18:04.063   872  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 17:18:04.067   872  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 17:18:04.069   872  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 17:18:04.079   872  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 17:18:04.084   872  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 17:18:04.084   872  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-09 17:18:04.084   872  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-09 17:18:04.084   872  1315 D ConnectivityService:    accepting network in place of null
,09-09 17:18:04.084   872  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 17:18:04.086   872  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 17:18:04.087   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 17:18:04.105   872  4074 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135561, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 17:18:04.129   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:18:04.180   872  4073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-09 17:18:04.180   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:18:04.192   872  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 17:18:04.192   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:18:04.194   872  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 17:18:04.196   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-09 17:18:04.220  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:18:04.220  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:04.220  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:04.220  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:04.220  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:04.220  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:04.220  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:04.220  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:04.220  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:18:04.220  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:04.221  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:04.226  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:04.226  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:04.226  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:04.226  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:04.226  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:04.226  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:04.226  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:04.226  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:04.226  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:18:04.226  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:04.227  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:18:04.233  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 17:18:04.236  1701  1701 D SystemUpdateService: onCreate
,09-09 17:18:04.239  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 17:18:04.242  1701  4086 I SystemUpdateService: active receiver: enabled
,09-09 17:18:04.247  1701  4086 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 17:18:04.248   872  4073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 15:18:04 GMT], X-Android-Received-Millis=[1473434284248], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473434284224]}
,09-09 17:18:04.249   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 17:18:04.249   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-09 17:18:04.249   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 17:18:04.250  1701  4086 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-09 17:18:04.251  1701  4086 I SystemUpdateService: now status is 0 (complete)
09-09 17:18:04.251   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 17:18:04.252  1701  4086 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 17:18:04.252  1701  4086 I SystemUpdateService: file has been verified
09-09 17:18:04.253  1701  4086 I SystemUpdateService: OTA package size = 12249756
,09-09 17:18:04.258  1701  4086 I SystemUpdateService: showing system update notification
,09-09 17:18:04.263  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 17:18:04.264  1701  2546 I iu.UploadsManager: num queued entries: 0
,09-09 17:18:04.265  1701  2546 I iu.UploadsManager: num updated entries: 0
,09-09 17:18:04.267  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 17:18:04.269  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 17:18:04.270  3974  3974 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:18:04.270  1701  2546 I iu.SyncManager: NEXT; no task
,09-09 17:18:04.272  1701  4091 I MDM     : [173] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 17:18:04.272  1701  4091 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 17:18:04.273  1701  4091 V GoogleAuthProtoRequest: [173] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 17:18:04.274  3974  3974 D SprintDMHelper: simOperator: 
09-09 17:18:04.274  3974  3974 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 17:18:04.279  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 17:18:04.281  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:18:04.287  1701  1701 D SystemUpdateService: onDestroy
,09-09 17:18:04.316  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 17:18:04.317  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 17:18:04.317  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 17:18:04.318  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:18:04.332  1701  4091 E MDM     : [173] SitrepService.a: Error sending sitrep.
,09-09 17:18:04.359  3049  4099 V KeepSync: Connecting to GoogleApiClient
,09-09 17:18:04.360   872  1947 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 17:18:04.393  1513  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 17:18:04.393  1513  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 17:18:04.394  1513  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:18:04.394  1513  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:18:04.405  1701  4100 V BaseAuthAsyncOperation: access token request failed
,09-09 17:18:04.406  3049  4099 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 17:18:04.419  2161  4093 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 17:18:04.439  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 17:18:04.440  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 17:18:04.440  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:18:04.440  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:18:04.457  3025  4098 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 17:18:04.457  3025  4098 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at jdm.a(PG:82)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at jcs.o(PG:406)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at jcn.a(PG:1379)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at jcs.i(PG:143)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at blb.a(PG:3937)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at czp.a(PG:18188)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at czp.a(PG:9081)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at czq.run(PG:1686)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:18:04.457  3025  4098 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at jdj.a(PG:4091)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at jdj.a(PG:1125)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at jdm.a(PG:77)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	... 12 more
09-09 17:18:04.457  3025  4098 E HttpOperation: Caused by: faj: BadAuthentication
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at fal.a(PG:38)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	at jdj.a(PG:4089)
09-09 17:18:04.457  3025  4098 E HttpOperation: 	... 14 more
,09-09 17:18:04.473  1513  2989 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 17:18:04.473  1513  2989 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 17:18:04.474  1513  2989 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:18:04.474  1513  2989 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:18:04.492  3049  4099 E KeepSync: IOException
09-09 17:18:04.492  3049  4099 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 17:18:04.492  3049  4099 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 17:18:04.492  3049  4099 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 17:18:04.492  3049  4099 E KeepSync: 	... 10 more
,09-09 17:18:04.492  3049  4099 W KeepSync: Sync result 2
09-09 17:18:04.493  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 17:18:04.493  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 17:18:04.493  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 17:18:04.493  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:18:04.505   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 132986, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 17:18:04.514  3025  4098 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 17:18:04.514  3025  4098 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at jdm.a(PG:82)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at jcs.o(PG:406)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at jcn.a(PG:1379)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at jcs.i(PG:143)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at hec.a(PG:42)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at hee.a(PG:102)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at czr.a(PG:65)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at kka.a(PG:108)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at czp.a(PG:19176)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at czp.a(PG:9081)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at czq.run(PG:1686)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:18:04.514  3025  4098 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at jdj.a(PG:4091)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at jdj.a(PG:1125)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at jdm.a(PG:77)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	... 15 more
09-09 17:18:04.514  3025  4098 E HttpOperation: Caused by: faj: BadAuthentication
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at fal.a(PG:38)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	at jdj.a(PG:4089)
09-09 17:18:04.514  3025  4098 E HttpOperation: 	... 17 more
09-09 17:18:04.514  3025  4098 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 17:18:04.514  3025  4098 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at hec.a(PG:42)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at hee.a(PG:102)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at czr.a(PG:65)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at kka.a(PG:108)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	... 15 more
09-09 17:18:04.514  3025  4098 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at fal.a(PG:38)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 17:18:04.514  3025  4098 E ExperimentLoader: 	... 17 more
,09-09 17:18:04.604   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130603, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 17:18:05.193   872  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 17:18:05.715   872  1949 I ActivityManager: Killing 3741:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 17:18:05.995   872  1944 D WifiService: setWifiEnabled: false pid=3814, uid=10000
,09-09 17:18:05.996   872  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:18:06.030  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 17:18:06.035   872  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 17:18:06.036   872  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 17:18:06.036   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 17:18:06.036   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:18:06.051   872  2165 D DhcpClient: Clearing IP address
,09-09 17:18:06.052   372   870 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:18:06.056   372   870 D CommandListener: Setting iface cfg
,09-09 17:18:06.064  1513  4102 V NativeCrypto: Read error: ssl=0x9b4a0200: I/O error during system call, Connection timed out
,09-09 17:18:06.068  1513  4102 V NativeCrypto: SSL shutdown failed: ssl=0x9b4a0200: I/O error during system call, Broken pipe
,09-09 17:18:06.069   872  4075 D DhcpClient: Receive thread stopped
09-09 17:18:06.073   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 17:18:06.073   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-09 17:18:06.085   396   396 E Parcel  : Reading a NULL string not supported here.
,09-09 17:18:06.086   872  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 17:18:06.090   872  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-09 17:18:06.094   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 17:18:06.121   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:18:06.146   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:18:06.147   872  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 17:18:06.147   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:18:06.147   372   870 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:18:06.148   872   889 D Tethering: MasterInitialState.processMessage what=3
09-09 17:18:06.153  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:06.153  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:06.153  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:06.153  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:06.153  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:06.153  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:06.153  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:06.153  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:06.153  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:06.153  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:06.154  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:06.154  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:06.155  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:06.155  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:06.155  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:06.155  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:06.155  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:06.155  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:06.155  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:06.155  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:06.155  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:06.155  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:06.159   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 17:18:06.162  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:06.162  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:06.162  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:06.162  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:06.162  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:06.162  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:06.162  3814 , 3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:06.162  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:06.162  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:06.162  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:06.162  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:06.163  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:06.163  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:06.163  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:06.163  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:06.163  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:06.163  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:06.163  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:06.163  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:06.163  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:06.163  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:06.163  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:06.163   872  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:18:06.168  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 17:18:06.172  1863  2198 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:18:06.172  1701  1701 D SystemUpdateService: onCreate
,09-09 17:18:06.177  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 17:18:06.186  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 17:18:06.188  1701  2546 I iu.UploadsManager: num queued entries: 0
09-09 17:18:06.190  1701  4114 I SystemUpdateService: active receiver: enabled
,09-09 17:18:06.193  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 17:18:06.194  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 17:18:06.196  3974  3974 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:18:06.192  1701  2546 I iu.UploadsManager: num updated entries: 0
,09-09 17:18:06.200  3974  3974 D SprintDMHelper: simOperator: 
,09-09 17:18:06.200  3974  3974 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 17:18:06.212  1701  4114 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 17:18:06.216   372   870 E Netd    : netlink response contains error (No such file or directory)
,09-09 17:18:06.217   872  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 17:18:06.230  1701  2546 I iu.SyncManager: NEXT; no task
,09-09 17:18:06.238  2161  4118 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 17:18:06.242  1701  4114 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-09 17:18:06.242  1701  4114 I SystemUpdateService: now status is 0 (complete)
09-09 17:18:06.242  1701  4114 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 17:18:06.242  1701  4114 I SystemUpdateService: file has been verified
09-09 17:18:06.243  1701  4114 I SystemUpdateService: OTA package size = 12249756
,09-09 17:18:06.271  1701  4114 I SystemUpdateService: showing system update notification
,09-09 17:18:06.286  1701  1701 D SystemUpdateService: onDestroy
,09-09 17:18:09.035   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e453ba:true
,09-09 17:18:09.036  3960  3960 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 17:18:09.043  3960  3960 I bt_bluedroid: init
09-09 17:18:09.044  3960  4122 I BluetoothAdapterState: Entering OffState
,09-09 17:18:09.054  3960  4123 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 17:18:09.054  3960  4123 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 17:18:09.054  3960  4123 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 17:18:09.055  3960  4123 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 17:18:09.057  3960  3960 I bt_bluedroid: get_profile_interface socket
,09-09 17:18:09.060  3960  3960 I bt_bluedroid: get_profile_interface sdp
,09-09 17:18:09.070  3960  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 17:18:09.071  3960  3970 I bt_bluedroid: config_hci_snoop_log
09-09 17:18:09.072  3960  4126 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 17:18:09.073   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 17:18:09.081  3960  4122 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 17:18:09.082  3960  4122 D BluetoothAdapterProperties: Setting state to 14
,09-09 17:18:09.082  3960  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-09 17:18:09.083  3960  4122 D BluetoothBondStateMachine: make
,09-09 17:18:09.086  3960  4127 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 17:18:09.089  3960  4122 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:18:09.091  3960  3960 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 17:18:09.095  3960  3960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:09.096  3960  3960 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:18:09.097  3960  3960 D BtGatt.GattService: Received start request. Starting profile...
,09-09 17:18:09.097  3960  3960 D BtGatt.GattService: start()
09-09 17:18:09.097  3960  3960 I bt_bluedroid: get_profile_interface gatt
,09-09 17:18:09.099  3960  3960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:09.099  3960  3960 D BtGatt.AdvertiseManager: advertise manager created
,09-09 17:18:09.106  3960  3960 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:18:09.106  3960  3960 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:09.106  3960  3960 V BluetoothAdapterState: isBleTurningOn()=true
,09-09 17:18:09.106  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:09.107  3960  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 17:18:09.108  3960  4122 I bt_bluedroid: enable
,09-09 17:18:09.108  3960  4123 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 17:18:09.108  3960  4123 I bt_hci  : start_up
,09-09 17:18:09.117  3960  4123 I bt_vendor: alloc value 0xb3939189
09-09 17:18:09.118  3960  4123 I bt_vendor: init
,09-09 17:18:09.118  3960  4123 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 17:18:09.118  3960  4123 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 17:18:09.225  3960  4123 D bt_hci  : start_up starting async portion
,09-09 17:18:09.226  3960  4130 I bt_hci  : event_finish_startup
,09-09 17:18:09.226  3960  4130 I bt_hci_h4: hal_open
,09-09 17:18:09.226  3960  4130 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-09 17:18:09.232  3960  4130 I bt_userial_vendor: device fd = 51 open
,09-09 17:18:09.268  3960  4130 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 17:18:09.300  3960  4130 D bt_hwcfg: Chipset BCM4354A2
,09-09 17:18:09.300  3960  4130 D bt_hwcfg: Target name = [BCM4354A2]
09-09 17:18:09.301  3960  4130 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 17:18:09.955  3960  4130 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 17:18:09.957  3960  4130 D bt_hwcfg: Settlement delay -- 100 ms
09-09 17:18:09.957  3960  4130 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 17:18:10.074  3960  4130 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 17:18:10.075  3960  4130 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 17:18:10.105  3960  4130 I bt_hwcfg: vendor lib fwcfg completed
,09-09 17:18:10.105  3960  4130 I bt_vendor: firmware callback
,09-09 17:18:10.105  3960  4130 I bt_hci  : firmware_config_callback
,09-09 17:18:10.116  3960  4132 I bt_btu  : btu_task pending for preload complete event
09-09 17:18:10.116  3960  4132 I bt_btu_task: Bluetooth chip preload is complete
09-09 17:18:10.117  3960  4132 I bt_btu  : btu_task received preload complete event
,09-09 17:18:10.127  3960  4132 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 17:18:10.128  3960  4132 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 17:18:10.128  3960  4132 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 17:18:10.128  3960  4132 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 17:18:10.128  3960  4132 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:18:10.129  3960  4132 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 17:18:10.129  3960  4132 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 17:18:10.129  3960  4132 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 17:18:10.129  3960  4132 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 17:18:10.130  3960  4132 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 17:18:10.130  3960  4132 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 17:18:10.130  3960  4132 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 17:18:10.131  3960  4132 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 17:18:10.131  3960  4132 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 17:18:10.131  3960  4132 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 17:18:10.267  3960  4132 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,09-09 17:18:10.267  3960  4132 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,09-09 17:18:10.278  3960  4126 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 17:18:10.280  3960  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 17:18:10.281  3960  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 17:18:10.286  3960  4126 D BluetoothAdapterProperties: Name is: Nexus 6
09-09 17:18:10.289  3960  4126 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:18:10.289  3960  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:18:10.290  3960  4126 D bt_hci  : do_postload posting postload work item
09-09 17:18:10.290  3960  4130 I bt_hci  : event_postload
09-09 17:18:10.290  3960  4130 I bt_vendor: sco_config_cb
09-09 17:18:10.291  3960  4130 I bt_hci  : sco_config_callback postload finished.
09-09 17:18:10.292  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:10.294  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:10.294  3960  4126 D bt_bte_conf: Device ID record 1 : primary
09-09 17:18:10.294  3960  4126 D bt_bte_conf:   vendorId            = 000f
09-09 17:18:10.294  3960  4126 D bt_bte_conf:   vendorIdSource      = 0001
09-09 17:18:10.294  3960  4126 D bt_bte_conf:   product             = 1200
09-09 17:18:10.295  3960  4126 D bt_bte_conf:   version             = 1436
09-09 17:18:10.295  3960  4126 D bt_bte_conf:   clientExecutableURL = 
09-09 17:18:10.295  3960  4126 D bt_bte_conf:   serviceDescription  = 
09-09 17:18:10.295  3960  4126 D bt_bte_conf:   documentationURL    = 
09-09 17:18:10.296  3960  4126 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 17:18:10.296  3960  4123 D bt_stack_manager: event_start_up_stack finished
,09-09 17:18:10.299  3960  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 17:18:10.299  3960  4122 D BluetoothAdapterProperties: Setting state to 15
09-09 17:18:10.299  3960  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 17:18:10.300  3960  4122 I BluetoothAdapterState: Entering BleOnState
,09-09 17:18:10.301  3960  4130 I bt_vendor: low_power_mode_cb
,09-09 17:18:10.305  3960  4122 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 17:18:10.305  3960  4122 D BluetoothAdapterProperties: Setting state to 11
,09-09 17:18:10.305  3960  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 17:18:10.311  3960  3960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
09-09 17:18:10.312  3960  3960 D HeadsetService: Received start request. Starting profile...
09-09 17:18:10.315  3960  3960 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:18:10.322  3960  3960 D HeadsetStateMachine: make
,09-09 17:18:10.327  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:10.329  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:10.331  3960  4122 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:18:10.335  3960  3960 D HeadsetStateMachine: max_hf_connections = 1
,09-09 17:18:10.335  3960  3960 I bt_bluedroid: get_profile_interface handsfree,
09-09 17:18:10.337  3960  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-09 17:18:10.337  3960  4126 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-09 17:18:10.340  3960  3960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:10.341  3960  3960 D A2dpService: Received start request. Starting profile...
,09-09 17:18:10.342  3960  3960 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 17:18:10.342  3960  3960 I bt_bluedroid: get_profile_interface avrcp
,09-09 17:18:10.349  3960  3960 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 17:18:10.349  3960  3960 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:18:10.350  3960  3960 D A2dpStateMachine: make
,09-09 17:18:10.351  3960  3960 I bt_bluedroid: get_profile_interface a2dp
,09-09 17:18:10.352  3960  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 17:18:10.354  3960  4142 D A2dpStateMachine: Enter Disconnected: -2
,09-09 17:18:10.355  3960  3960 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 17:18:10.357  3960  3960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:10.358  3882  3882 D BluetoothInputDevice: Proxy object connected
09-09 17:18:10.358  3960  3960 D HidService: Received start request. Starting profile...
09-09 17:18:10.358  3960  3960 I bt_bluedroid: get_profile_interface hidhost
09-09 17:18:10.358  3882  3882 D HidProfile: Bluetooth service connected
09-09 17:18:10.358  3960  3960 D HidService: setHidService(): set to: null
09-09 17:18:10.358  3960  4126 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
09-09 17:18:10.363  3960  3960 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 17:18:10.363  3960  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 17:18:10.364  3960  3960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:10.365  3960  3960 D HealthService: Received start request. Starting profile...
,09-09 17:18:10.369  3960  3960 I bt_bluedroid: get_profile_interface health
09-09 17:18:10.369  3960  3960 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 17:18:10.370  3960  3960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:10.372  3882  3882 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 17:18:10.372  3960  3960 D PanService: Received start request. Starting profile...
,09-09 17:18:10.372  3882  3882 D PanProfile: Bluetooth service connected
,09-09 17:18:10.372  3960  3960 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 17:18:10.372  3960  3960 I bt_bluedroid: get_profile_interface pan
,09-09 17:18:10.373  3960  4126 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 17:18:10.376  3960  3960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:10.378  3882  3882 D BluetoothMap: Proxy object connected
,09-09 17:18:10.378  3882  3882 D MapProfile: Bluetooth service connected
09-09 17:18:10.379  3882  3882 D BluetoothMap: getConnectedDevices()
,09-09 17:18:10.380  3960  3960 D BluetoothMapService: Received start request. Starting profile...
,09-09 17:18:10.380  3960  3960 D BluetoothMapService: start()
09-09 17:18:10.380  3882  3882 D BluetoothMap: Bluetooth is Not enabled
,09-09 17:18:10.383  3960  3960 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 17:18:10.385  3960  3960 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 17:18:10.385  3960  3960 D BluetoothMapAppObserver: createReceiver()
,09-09 17:18:10.389  3960  3960 D BluetoothMapAppObserver: initObservers()
,09-09 17:18:10.389  3960  3960 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 17:18:10.412  3960  3960 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:18:10.412  3960  3960 V BluetoothAdapterState: isTurningOn()=true
09-09 17:18:10.412  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:10.412  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:10.412  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:18:10.413  3960  4138 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isTurningOff()=false
09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isTurningOff()=false
09-09 17:18:10.415  3960  3960 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isTurningOff()=false
09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isTurningOn()=true
,09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isTurningOff()=false
09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isTurningOn()=true
09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:18:10.416  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:10.417  3960  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 17:18:10.417  3960  4122 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:18:10.417  3960  4122 D BluetoothAdapterProperties: State =  11
,09-09 17:18:10.418  3960  4122 D BluetoothAdapterProperties: Setting state to 12
09-09 17:18:10.419  3960  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 17:18:10.420  3960  4122 I BluetoothAdapterState: Entering OnState
,09-09 17:18:10.420  3960  4126 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:18:10.420  3882  3894 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:18:10.420  3960  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:18:10.421  1370  2118 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 17:18:10.423  1370  2170 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 17:18:10.424   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:10.425  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:10.425  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:10.425  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:10.425  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:10.425  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:10.425  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:10.425  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:10.425  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:10.425  3882  3893 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 17:18:10.425   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:18:10.425  1370  1370 D BluetoothInputDevice: Proxy object connected
09-09 17:18:10.425  1370  1370 D HidProfile: Bluetooth service connected
09-09 17:18:10.426  3882  3894 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:18:10.427   872   872 D BluetoothA2dp: Proxy object connected
09-09 17:18:10.427  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:10.428  1370  1381 D BluetoothPan: onBluetoothStateChange on: true
,09-09 17:18:10.430  1370  2118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:18:10.431  3960  3960 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 17:18:10.431  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:18:10.431  1370  1370 D PanProfile: Bluetooth service connected
09-09 17:18:10.431  3960  3960 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 17:18:10.432  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:10.432  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:10.432  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:10.432  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:10.432  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:10.432  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:10.432  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:10.432  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:10.432  1370  1370 D BluetoothA2dp: Proxy object connected
09-09 17:18:10.433  1370  2172 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:18:10.435  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:10.436  1370  1370 D BluetoothMap: Proxy object connected
09-09 17:18:10.436  1370  1370 D MapProfile: Bluetooth service connected
09-09 17:18:10.436   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:10.436  1370  1370 D BluetoothMap: getConnectedDevices()
,09-09 17:18:10.437  1997  2014 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:10.437  3960  3960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:18:10.437   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:10.437  3882  3893 D BluetoothPan: onBluetoothStateChange on: true
09-09 17:18:10.438  1370  1381 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:10.440   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 17:18:10.443  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:10.444  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:10.445  3960  3960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:18:10.446  3882  3882 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-09 17:18:10.446  3960  3960 D ObexServerSockets: Succeed to create listening sockets 
09-09 17:18:10.446  3960  3960 D ObexServerSockets0: startAccept()
09-09 17:18:10.446  3960  3960 D ObexServerSockets0: prepareForNewConnect()
09-09 17:18:10.449  3960  3960 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 17:18:10.449  3960  3960 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 17:18:10.450  3960  3960 D BluetoothMapService: onReceive
09-09 17:18:10.450  3960  3960 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:10.450  3960  3960 D BluetoothMapService: STATE_ON
09-09 17:18:10.454  3960  4149 D ObexServerSockets0: Accepting socket connection...
09-09 17:18:10.453  3960  4150 D ObexServerSockets0: Accepting socket connection...
,09-09 17:18:10.460  3882  3882 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 17:18:10.468  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:18:10.470  3882  3882 D BluetoothA2dp: Proxy object connected
09-09 17:18:10.471  3960  3960 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 17:18:10.471  3960  3960 D ObexServerSockets0: prepareForNewConnect()
,09-09 17:18:10.474  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:10.477  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:18:10.483  3882  3882 D BluetoothPbap: Proxy object connected
,09-09 17:18:10.483  1370  1370 D BluetoothPbap: Proxy object connected
09-09 17:18:10.483  1370  1370 D PbapServerProfile: Bluetooth service connected
09-09 17:18:10.483  3882  3882 D PbapServerProfile: Bluetooth service connected
,09-09 17:18:10.493  3960  4154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:10.503  3960  4158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:10.505  3960  4158 I BtOppRfcommListener: Accept thread started.
,09-09 17:18:10.527   872   872 D BluetoothHeadset: Proxy object connected
,09-09 17:18:10.527   872   872 D BluetoothHeadset: Proxy object connected
,09-09 17:18:10.527   872   872 D BluetoothHeadset: Proxy object connected
09-09 17:18:10.527  1370  1381 D BluetoothHeadset: Proxy object connected
,09-09 17:18:10.527  1370  1370 D HeadsetProfile: Bluetooth service connected
,09-09 17:18:10.528  1997  2096 D BluetoothHeadset: Proxy object connected
,09-09 17:18:10.536   872   889 D BluetoothHeadset: Proxy object connected
,09-09 17:18:10.537  1997  2008 D BluetoothHeadset: Proxy object connected
,09-09 17:18:10.538   872   889 D BluetoothHeadset: Proxy object connected
09-09 17:18:10.538  1370  2170 D BluetoothHeadset: Proxy object connected
09-09 17:18:10.539  1370  1370 D HeadsetProfile: Bluetooth service connected
,09-09 17:18:10.564  3882  3894 D BluetoothHeadset: Proxy object connected
,09-09 17:18:10.564  3882  3882 D HeadsetProfile: Bluetooth service connected
,09-09 17:18:12.015  3960  4122 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 17:18:12.015  3960  4122 D BluetoothAdapterProperties: Setting state to 13
,09-09 17:18:12.015  3960  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 17:18:12.017  3960  4122 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 17:18:12.025  3960  3960 D BluetoothMapService: onReceive
,09-09 17:18:12.026  3960  3960 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:12.026  3960  3960 D BluetoothMapService: STATE_TURNING_OFF
,09-09 17:18:12.027  3960  3960 D BluetoothMapService: MAP Service closeService in
,09-09 17:18:12.028  3960  3960 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 17:18:12.028  3960  3960 D ObexServerSockets0: shutdown(block = true)
09-09 17:18:12.029  3960  4149 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-09 17:18:12.030  3960  4122 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:18:12.033  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:18:12.033  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:12.033  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:12.033  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:12.033  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:12.033  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:12.033  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:12.033  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:12.033  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:12.036  3960  3960 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 17:18:12.036  3960  4135 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 17:18:12.036  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:18:12.039  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:12.036  3960  4150 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 17:18:12.041  3960  4126 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:18:12.041  3960  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 17:18:12.039  3960  3960 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 17:18:12.044  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 17:18:12.044  3960  3960 I BtOppRfcommListener: stopping Accept Thread
09-09 17:18:12.044  3960  4158 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:18:12.045  3960  4158 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 17:18:12.045  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:18:12.045  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:12.045  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:12.045  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:12.045  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:12.045  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:18:12.045  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:12.045  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:12.045  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:12.046  3814  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:18:12.046  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:12.048  3960  3960 D HeadsetService: Received stop request...Stopping profile...
09-09 17:18:12.049  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:12.049   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 17:18:12.049   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 17:18:12.051  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:12.050  3882  3893 D BluetoothHeadset: Proxy object disconnected
09-09 17:18:12.051  3960  3960 D A2dpService: Received stop request...Stopping profile...
09-09 17:18:12.051   872   872 D BluetoothHeadset: Proxy object disconnected
09-09 17:18:12.052  1370  1381 D BluetoothHeadset: Proxy object disconnected
09-09 17:18:12.052  3960  4142 D A2dpStateMachine: Exit Disconnected: -1
,09-09 17:18:12.053  1997  2168 D BluetoothHeadset: Proxy object disconnected
09-09 17:18:12.054   872   872 D BluetoothA2dp: Proxy object disconnected
09-09 17:18:12.054  3960  3960 D HidService: Received stop request...Stopping profile...
09-09 17:18:12.054  3960  3960 D HidService: Stopping Bluetooth HidService
09-09 17:18:12.057  1370  1370 D HeadsetProfile: Bluetooth service disconnected
09-09 17:18:12.057  3960  3960 D HealthService: Received stop request...Stopping profile...
,09-09 17:18:12.058  1370  1370 D BluetoothA2dp: Proxy object disconnected
09-09 17:18:12.058  1370  1370 D BluetoothInputDevice: Proxy object disconnected
09-09 17:18:12.058  1370  1370 D HidProfile: Bluetooth service disconnected
09-09 17:18:12.060  3960  3960 D PanService: Received stop request...Stopping profile...
09-09 17:18:12.061  3960  3960 V BluetoothAdapterState: isTurningOff()=true
,09-09 17:18:12.061  3960  3960 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:12.061  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:12.061  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:12.062  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 17:18:12.062  1370  1370 D PanProfile: Bluetooth service disconnected
09-09 17:18:12.062  3960  3960 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:18:12.063  3960  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 17:18:12.063  3960  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:18:12.063  3960  3960 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:18:12.063  3960  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 17:18:12.063  3960  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:18:12.063  3960  4126 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
09-09 17:18:12.063  3882  3882 D DockEventReceiver: finishStartingService: stopping service
09-09 17:18:12.065  3882  3882 D HeadsetProfile: Bluetooth service disconnected
09-09 17:18:12.065  3882  3882 D BluetoothA2dp: Proxy object disconnected
09-09 17:18:12.065  3882  3882 D BluetoothInputDevice: Proxy object disconnected
09-09 17:18:12.065  3882  3882 D HidProfile: Bluetooth service disconnected
,09-09 17:18:12.066  3960  3960 V BluetoothAdapterState: isTurningOff()=true
09-09 17:18:12.067  3960  3960 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:12.067  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:12.067  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:18:12.067  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:18:12.068  3960  3960 D BluetoothMapService: Received stop request...Stopping profile...
09-09 17:18:12.068  3960  3960 D BluetoothMapService: stop()
09-09 17:18:12.068  3882  3882 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 17:18:12.068  3882  3882 D PanProfile: Bluetooth service disconnected
09-09 17:18:12.069  3960  3960 D BluetoothMapAppObserver: deinitObservers()
09-09 17:18:12.069  3960  3960 D BluetoothMapAppObserver: removeReceiver()
09-09 17:18:12.072  1370  1370 D BluetoothMap: Proxy object disconnected
09-09 17:18:12.071  3882  3882 D BluetoothMap: Proxy object disconnected
,09-09 17:18:12.072  1370  1370 D MapProfile: Bluetooth service disconnected
09-09 17:18:12.072  3882  3882 D MapProfile: Bluetooth service disconnected
09-09 17:18:12.073  3960  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-09 17:18:12.073  3960  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:18:12.073  3960  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 17:18:12.073  3960  4132 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:18:12.073  3960  4132 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:18:12.073  3960  4132 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 17:18:12.073  3960  4132 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:18:12.073  3960  3960 V BluetoothAdapterState: isTurningOff()=true
09-09 17:18:12.073  3960  3960 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:12.073  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:12.074  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:12.074  3960  3960 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 17:18:12.074  3960  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 17:18:12.074  3960  3960 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 17:18:12.075  3960  3960 V BluetoothAdapterState: isTurningOff()=true
09-09 17:18:12.075  3960  3960 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:12.075  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:18:12.075  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:12.075  3960  3960 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:18:12.075  3960  4126 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 17:18:12.075  3960  3960 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:18:12.076  3960  3960 V BluetoothAdapterState: isTurningOff()=true
09-09 17:18:12.076  3960  3960 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:12.076  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:12.076  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:12.076  3960  3960 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:18:12.076  3960  3960 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 17:18:12.079  1370  1370 D BluetoothPbap: Proxy object disconnected
09-09 17:18:12.079  1370  1370 D PbapServerProfile: Bluetooth service disconnected
09-09 17:18:12.079  3882  3882 D BluetoothPbap: Proxy object disconnected
09-09 17:18:12.079  3882  3882 D PbapServerProfile: Bluetooth service disconnected
,09-09 17:18:12.081  3960  3960 D BluetoothMapService: MAP Service closeService in
09-09 17:18:12.082  3960  3960 V BluetoothAdapterState: isTurningOff()=true
,09-09 17:18:12.082  3960  3960 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:12.082  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:12.082  3960  3960 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:12.082  3960  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 17:18:12.082  3960  4122 D BluetoothAdapterProperties: Setting state to 15
09-09 17:18:12.082  3960  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 17:18:12.083  3960  4122 I BluetoothAdapterState: Entering BleOnState
09-09 17:18:12.083  3960  3960 D BluetoothMapService: cleanup()
09-09 17:18:12.084  3960  3960 D BluetoothMapService: MAP Service closeService in
09-09 17:18:12.083  3882  3894 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 17:18:12.086  1370  2118 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 17:18:12.087  1370  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 17:18:12.089  3882  3893 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:18:12.090   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:18:12.090  3882  3894 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 17:18:12.090   872  1315 D ConnectivityService: handlePromptUnvalidated 101
,09-09 17:18:12.090   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:18:12.091  3882  3893 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 17:18:12.091  1370  2172 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:18:12.092  1370  1381 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:18:12.092  1370  2170 D BluetoothMap: onBluetoothStateChange: up=false
09-09 17:18:12.092   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 17:18:12.093  3882  3894 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:18:12.093  1997  2014 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:18:12.093   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 17:18:12.093  3882  3893 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:18:12.094  1370  2118 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 17:18:12.095  3960  4122 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 17:18:12.095  3960  4122 D BluetoothAdapterProperties: Setting state to 16
09-09 17:18:12.095  3960  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-09 17:18:12.095  3960  4122 D BluetoothAdapterProperties: onBleDisable
,09-09 17:18:12.096  3960  4126 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:18:12.096  3960  4122 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:18:12.096  3960  4123 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 17:18:12.097  3960  4132 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 17:18:12.097  3960  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
09-09 17:18:12.098  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:12.100  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:12.101  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:12.102  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:12.103  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:18:12.107  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:18:12.107  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:12.297  3960  4126 I bt_hci  : shut_down
,09-09 17:18:12.298  3960  4130 D bt_hwcfg: hw_epilog_process
,09-09 17:18:12.299  3960  4130 I bt_vendor: low_power_mode_cb,
,09-09 17:18:12.323  3960  4130 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 17:18:12.323  3960  4130 I bt_vendor: epilog_cb
,09-09 17:18:12.324  3960  4130 I bt_hci  : epilog_finished_callback
,09-09 17:18:12.334  3960  4126 I bt_hci_h4: hal_close
,09-09 17:18:12.335  3960  4126 I bt_userial_vendor: device fd = 51 close
,09-09 17:18:12.458  3960  4123 D bt_stack_manager: event_shut_down_stack finished.
,09-09 17:18:12.459  3960  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 17:18:12.465  3960  3960 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 17:18:12.465  3960  4122 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 17:18:12.466  3960  3960 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 17:18:12.467  3960  3960 D BtGatt.GattService: stop()
09-09 17:18:12.467  3960  3960 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 17:18:12.473  3960  3960 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:18:12.473  3960  3960 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:12.473  3960  3960 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:12.474  3960  3960 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 17:18:12.475  3960  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 17:18:12.475  3960  4122 D BluetoothAdapterProperties: Setting state to 10
09-09 17:18:12.476  3960  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 17:18:12.477  3960  4122 I BluetoothAdapterState: Entering OffState
,09-09 17:18:12.479   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 17:18:12.510  3960  3960 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-09 17:18:12.510  3960  3960 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 17:18:12.510  3960  4123 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 17:18:12.514  3960  4123 D bt_stack_manager: event_clean_up_stack finished.
09-09 17:18:12.514  3960  3960 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 17:18:12.516  3960  3960 I art     : System.exit called, status: 0
,09-09 17:18:12.516  3960  3960 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 17:18:12.589   872  1949 I ActivityManager: Process com.android.bluetooth (pid 3960) has died
,09-09 17:18:15.015  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:18:15.015  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:18.023  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:18.023  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35664d7 added. We now have 6 listener(s)
,09-09 17:18:18.024  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:18.028  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:18.029  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cca1c4 added. We now have 7 listener(s)
09-09 17:18:18.029  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:18.031  3814  3864 I System.out: IsBluetoothEnabled
,09-09 17:18:18.043  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:18.087   872   889 I ActivityManager: Start proc 4169:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 17:18:18.219  4169  4169 D AdapterServiceConfig: Adding HeadsetService
,09-09 17:18:18.219  4169  4169 D AdapterServiceConfig: Adding A2dpService
09-09 17:18:18.220  4169  4169 D AdapterServiceConfig: Adding HidService
,09-09 17:18:18.220  4169  4169 D AdapterServiceConfig: Adding HealthService
09-09 17:18:18.220  4169  4169 D AdapterServiceConfig: Adding PanService
,09-09 17:18:18.220  4169  4169 D AdapterServiceConfig: Adding GattService
09-09 17:18:18.220  4169  4169 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 17:18:18.235   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@993440f:true
,09-09 17:18:18.237  4169  4169 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 17:18:18.246  4169  4169 I bt_bluedroid: init
,09-09 17:18:18.246  4169  4181 I BluetoothAdapterState: Entering OffState
,09-09 17:18:18.252  4169  4182 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 17:18:18.253  4169  4182 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 17:18:18.253  4169  4182 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 17:18:18.253  4169  4182 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 17:18:18.259  4169  4169 I bt_bluedroid: get_profile_interface socket
,09-09 17:18:18.264  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 17:18:18.265  4169  4169 I bt_bluedroid: get_profile_interface sdp
,09-09 17:18:18.266  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 17:18:18.270  4169  4180 I bt_bluedroid: config_hci_snoop_log
,09-09 17:18:18.272   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 17:18:18.279  4169  4181 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 17:18:18.280  4169  4181 D BluetoothAdapterProperties: Setting state to 14
,09-09 17:18:18.280  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 17:18:18.284  4169  4181 D BluetoothBondStateMachine: make
,09-09 17:18:18.289  4169  4186 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 17:18:18.301  4169  4181 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:18:18.302  4169  4169 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 17:18:18.311  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:18.313  4169  4169 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:18:18.314  4169  4169 D BtGatt.GattService: Received start request. Starting profile...
,09-09 17:18:18.315  4169  4169 D BtGatt.GattService: start()
09-09 17:18:18.315  4169  4169 I bt_bluedroid: get_profile_interface gatt
,09-09 17:18:18.317  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:18.317  4169  4169 D BtGatt.AdvertiseManager: advertise manager created
,09-09 17:18:18.331  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:18:18.331  4169  4169 V BluetoothAdapterState: isTurningOn()=false
09-09 17:18:18.332  4169  4169 V BluetoothAdapterState: isBleTurningOn()=true
09-09 17:18:18.332  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:18:18.335  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 17:18:18.335  4169  4181 I bt_bluedroid: enable
,09-09 17:18:18.336  4169  4182 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 17:18:18.337  4169  4182 I bt_hci  : start_up
,09-09 17:18:18.360  4169  4182 I bt_vendor: alloc value 0xb39aa189
,09-09 17:18:18.361  4169  4182 I bt_vendor: init
09-09 17:18:18.362  4169  4182 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 17:18:18.362  4169  4182 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 17:18:18.469  4169  4182 D bt_hci  : start_up starting async portion
,09-09 17:18:18.469  4169  4189 I bt_hci  : event_finish_startup
09-09 17:18:18.470  4169  4189 I bt_hci_h4: hal_open
09-09 17:18:18.470  4169  4189 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 17:18:18.480  4169  4189 I bt_userial_vendor: device fd = 51 open
,09-09 17:18:18.511  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 17:18:18.543  4169  4189 D bt_hwcfg: Chipset BCM4354A2
,09-09 17:18:18.543  4169  4189 D bt_hwcfg: Target name = [BCM4354A2]
09-09 17:18:18.544  4169  4189 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 17:18:18.833   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 17:18:18.844  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-09 17:18:18.860   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 17:18:18.860   872   892 I Adreno  : Build Date                       : 10/20/15
09-09 17:18:18.860   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 17:18:18.860   872   892 I Adreno  : Local Branch                     : M14
09-09 17:18:18.860   872   892 I Adreno  : Remote Branch                    : 
09-09 17:18:18.860   872   892 I Adreno  : Remote Branch                    : 
09-09 17:18:18.860   872   892 I Adreno  : Reconstruct Branch               : 
,09-09 17:18:18.895   282   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (194 us)
,09-09 17:18:19.204  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 17:18:19.207  4169  4189 D bt_hwcfg: Settlement delay -- 100 ms
,09-09 17:18:19.208  4169  4189 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 17:18:19.326  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 17:18:19.329  4169  4189 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 17:18:19.354  4169  4189 I bt_hwcfg: vendor lib fwcfg completed
,09-09 17:18:19.358  4169  4189 I bt_vendor: firmware callback
,09-09 17:18:19.360  4169  4189 I bt_hci  : firmware_config_callback
,09-09 17:18:19.372  4169  4193 I bt_btu  : btu_task pending for preload complete event
,09-09 17:18:19.372  4169  4193 I bt_btu_task: Bluetooth chip preload is complete
,09-09 17:18:19.372  4169  4193 I bt_btu  : btu_task received preload complete event
,09-09 17:18:19.383  4169  4193 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 17:18:19.385  4169  4193 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 17:18:19.385  4169  4193 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 17:18:19.386  4169  4193 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 17:18:19.386  4169  4193 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:18:19.386  4169  4193 I         : BTE_InitTraceLevels -- TRC_A2D
,09-09 17:18:19.387  4169  4193 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 17:18:19.387  4169  4193 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 17:18:19.387  4169  4193 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 17:18:19.387  4169  4193 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 17:18:19.387  4169  4193 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 17:18:19.388  4169  4193 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 17:18:19.388  4169  4193 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 17:18:19.388  4169  4193 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 17:18:19.388  4169  4193 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 17:18:19.521  4169  4193 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3927d9d
,09-09 17:18:19.523  4169  4193 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3927d9d 
,09-09 17:18:19.534  4169  4185 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 17:18:19.536  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 17:18:19.536  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 17:18:19.537  3814  3814 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 17:18:19.538  3814  3814 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 17:18:19.572  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 17:18:19.574  4169  4185 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:18:19.574  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:18:19.573   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
09-09 17:18:19.574  4169  4185 D bt_hci  : do_postload posting postload work item
09-09 17:18:19.574  4169  4189 I bt_hci  : event_postload
09-09 17:18:19.574  4169  4189 I bt_vendor: sco_config_cb
09-09 17:18:19.574  4169  4189 I bt_hci  : sco_config_callback postload finished.
,09-09 17:18:19.575  3814  3814 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5a07cbe Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@902c8ad, 16908290=android.view.AbsSavedState$1@902c8ad}, android:focusedViewId=100}]}]
,09-09 17:18:19.575  3814  3814 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-09 17:18:19.576  3814  3814 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 17:18:19.576  3814  3814 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 17:18:19.576  4169  4185 D bt_bte_conf: Device ID record 1 : primary
09-09 17:18:19.576  4169  4185 D bt_bte_conf:   vendorId            = 000f
09-09 17:18:19.576  4169  4185 D bt_bte_conf:   vendorIdSource      = 0001
09-09 17:18:19.576  4169  4185 D bt_bte_conf:   product             = 1200
09-09 17:18:19.576  4169  4185 D bt_bte_conf:   version             = 1436
09-09 17:18:19.576  4169  4185 D bt_bte_conf:   clientExecutableURL = 
09-09 17:18:19.576  4169  4185 D bt_bte_conf:   serviceDescription  = 
09-09 17:18:19.576  4169  4189 I bt_vendor: low_power_mode_cb
,09-09 17:18:19.576  4169  4185 D bt_bte_conf:   documentationURL    = 
09-09 17:18:19.576  4169  4185 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 17:18:19.577  4169  4182 D bt_stack_manager: event_start_up_stack finished
09-09 17:18:19.577  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 17:18:19.577  4169  4181 D BluetoothAdapterProperties: Setting state to 15
,09-09 17:18:19.577  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 17:18:19.578  4169  4181 I BluetoothAdapterState: Entering BleOnState
,09-09 17:18:19.580  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:19.581  4169  4181 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 17:18:19.581  4169  4181 D BluetoothAdapterProperties: Setting state to 11
,09-09 17:18:19.581  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 17:18:19.583   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-09 17:18:19.591  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:19.591  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:19.594  4169  4169 D HeadsetService: Received start request. Starting profile...
09-09 17:18:19.594   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-09 17:18:19.594   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,09-09 17:18:19.594   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-09 17:18:19.596  4169  4169 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:18:19.596  4169  4169 D HeadsetStateMachine: make
,09-09 17:18:19.611  4169  4169 D HeadsetStateMachine: max_hf_connections = 1
09-09 17:18:19.612  4169  4169 I bt_bluedroid: get_profile_interface handsfree
09-09 17:18:19.612  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 17:18:19.612  4169  4185 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 17:18:19.616   872   881 I art     : Background partial concurrent mark sweep GC freed 14198(1196KB) AllocSpace objects, 10(392KB) LOS objects, 33% free, 29MB/43MB, paused 5.735ms total 114.202ms
,09-09 17:18:19.617  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
09-09 17:18:19.618  4169  4181 I BluetoothAdapterState: Entering PendingCommandState
,09-09 17:18:19.618  4169  4169 D A2dpService: Received start request. Starting profile...
,09-09 17:18:19.619  4169  4169 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 17:18:19.619  4169  4169 I bt_bluedroid: get_profile_interface avrcp
,09-09 17:18:19.624  4169  4169 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 17:18:19.624  4169  4169 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:18:19.624  4169  4169 D A2dpStateMachine: make
,09-09 17:18:19.625  4169  4169 I bt_bluedroid: get_profile_interface a2dp
,09-09 17:18:19.626  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 17:18:19.627  4169  4202 D A2dpStateMachine: Enter Disconnected: -2
,09-09 17:18:19.629  4169  4169 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 17:18:19.629  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
09-09 17:18:19.630  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:19.630  4169  4169 D HidService: Received start request. Starting profile...
,09-09 17:18:19.631  4169  4169 I bt_bluedroid: get_profile_interface hidhost
09-09 17:18:19.631  4169  4185 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39093e5
09-09 17:18:19.631  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 17:18:19.631  4169  4169 D HidService: setHidService(): set to: null
,09-09 17:18:19.632  4169  4169 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 17:18:19.632  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:19.633  4169  4169 D HealthService: Received start request. Starting profile...
,09-09 17:18:19.634  4169  4169 I bt_bluedroid: get_profile_interface health
,09-09 17:18:19.634  4169  4169 V BluetoothAdapterState: isTurningOff()=false
09-09 17:18:19.634  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-09 17:18:19.635  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:19.635  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:18:19.636  4169  4169 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 17:18:19.637  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:19.637  4169  4169 D PanService: Received start request. Starting profile...
09-09 17:18:19.638  4169  4169 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 17:18:19.638  4169  4169 I bt_bluedroid: get_profile_interface pan
,09-09 17:18:19.638  4169  4185 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 17:18:19.640  4169  4200 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 17:18:19.642  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
,09-09 17:18:19.642  4169  4169 D BluetoothMapService: Received start request. Starting profile...
09-09 17:18:19.642  4169  4169 D BluetoothMapService: start()
,09-09 17:18:19.644  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 17:18:19.645  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 17:18:19.645  4169  4169 D BluetoothMapAppObserver: createReceiver()
,09-09 17:18:19.645  4169  4169 D BluetoothMapAppObserver: initObservers()
09-09 17:18:19.645  4169  4169 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 17:18:19.651  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:18:19.651  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-09 17:18:19.652  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:19.652  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 17:18:19.654  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:18:19.654  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-09 17:18:19.654  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:19.654  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:19.654  4169  4169 V BluetoothAdapterState: isTurningOff()=false
09-09 17:18:19.654  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-09 17:18:19.654  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 17:18:19.654  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:19.655  4169  4169 V BluetoothAdapterState: isTurningOff()=false
09-09 17:18:19.655  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-09 17:18:19.655  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:19.655  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:19.655  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,09-09 17:18:19.655  4169  4169 V BluetoothAdapterState: isTurningOn()=true
09-09 17:18:19.655  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
09-09 17:18:19.655  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
09-09 17:18:19.656  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 17:18:19.656  4169  4181 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:18:19.656  4169  4181 D BluetoothAdapterProperties: State =  11
09-09 17:18:19.656  4169  4181 D BluetoothAdapterProperties: Setting state to 12
09-09 17:18:19.656  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 17:18:19.656  4169  4181 I BluetoothAdapterState: Entering OnState
,09-09 17:18:19.656  3882  3893 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:18:19.657  4169  4185 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:18:19.657  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 17:18:19.660  1370  2170 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:18:19.661  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:19.661  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:19.661  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:19.661  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:19.661  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:19.661  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:19.661  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:19.661  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:19.662  1370  1387 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 17:18:19.662  3882  3882 D BluetoothMap: Proxy object connected
09-09 17:18:19.662  3882  3882 D MapProfile: Bluetooth service connected
09-09 17:18:19.662  3882  3882 D BluetoothMap: getConnectedDevices()
09-09 17:18:19.663  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:19.663  3882  3894 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:18:19.664  1370  1370 D BluetoothInputDevice: Proxy object connected
09-09 17:18:19.664  1370  1370 D HidProfile: Bluetooth service connected
,09-09 17:18:19.665   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:19.665  3882  3893 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 17:18:19.667   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:18:19.667   872   872 D BluetoothA2dp: Proxy object connected
09-09 17:18:19.667  3882  3893 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 17:18:19.668  1370  2172 D BluetoothPan: onBluetoothStateChange on: true
,09-09 17:18:19.669  3882  3882 D BluetoothA2dp: Proxy object connected
09-09 17:18:19.669  1370  2118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:18:19.670  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:18:19.670  3882  3882 D BluetoothInputDevice: Proxy object connected
09-09 17:18:19.670  1370  1370 D PanProfile: Bluetooth service connected
09-09 17:18:19.670  3882  3882 D HidProfile: Bluetooth service connected
09-09 17:18:19.671  1370  1370 D BluetoothA2dp: Proxy object connected
,09-09 17:18:19.671  1370  1381 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:18:19.672   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:19.672  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 17:18:19.672  3882  4207 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:19.672  4169  4169 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 17:18:19.673  1997  2168 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:19.673   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:19.673  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:18:19.673  3882  3894 D BluetoothPan: onBluetoothStateChange on: true
09-09 17:18:19.674  1370  1370 D BluetoothMap: Proxy object connected
,09-09 17:18:19.674  1370  1370 D MapProfile: Bluetooth service connected
09-09 17:18:19.674  1370  1370 D BluetoothMap: getConnectedDevices()
,09-09 17:18:19.676  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:19.676  1370  2118 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 17:18:19.676  3882  3882 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 17:18:19.676  3882  3882 D PanProfile: Bluetooth service connected
09-09 17:18:19.677  4169  4169 D ObexServerSockets: Succeed to create listening sockets 
,09-09 17:18:19.677   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 17:18:19.677  4169  4169 D ObexServerSockets0: startAccept()
,09-09 17:18:19.677  4169  4169 D ObexServerSockets0: prepareForNewConnect()
,09-09 17:18:19.679  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:19.680  4169  4169 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-09 17:18:19.680  4169  4169 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-09 17:18:19.681  4169  4169 D BluetoothMapService: onReceive
,09-09 17:18:19.681  4169  4169 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:19.681  4169  4169 D BluetoothMapService: STATE_ON
09-09 17:18:19.683  4169  4209 D ObexServerSockets0: Accepting socket connection...
09-09 17:18:19.683  4169  4210 D ObexServerSockets0: Accepting socket connection...,
,09-09 17:18:19.687  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:18:19.692  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:18:19.694  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:19.702  3882  3882 D BluetoothPbap: Proxy object connected
,09-09 17:18:19.702  3882  3882 D PbapServerProfile: Bluetooth service connected
,09-09 17:18:19.704  1370  1370 D BluetoothPbap: Proxy object connected
,09-09 17:18:19.704  1370  1370 D PbapServerProfile: Bluetooth service connected
,09-09 17:18:19.709  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 17:18:19.709  4169  4169 D ObexServerSockets0: prepareForNewConnect()
,09-09 17:18:19.713  4169  4214 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:19.729  4169  4218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:19.731  4169  4218 I BtOppRfcommListener: Accept thread started.
,09-09 17:18:19.766   872   872 D BluetoothHeadset: Proxy object connected
09-09 17:18:19.767   872   872 D BluetoothHeadset: Proxy object connected
09-09 17:18:19.767  3882  3893 D BluetoothHeadset: Proxy object connected
,09-09 17:18:19.768   872   872 D BluetoothHeadset: Proxy object connected
09-09 17:18:19.767  3882  3882 D HeadsetProfile: Bluetooth service connected
09-09 17:18:19.768  1370  2118 D BluetoothHeadset: Proxy object connected
09-09 17:18:19.768  1370  1370 D HeadsetProfile: Bluetooth service connected
09-09 17:18:19.769  1997  2014 D BluetoothHeadset: Proxy object connected
,09-09 17:18:19.772   872   889 D BluetoothHeadset: Proxy object connected
,09-09 17:18:19.773  3882  3894 D BluetoothHeadset: Proxy object connected
09-09 17:18:19.773  1997  2096 D BluetoothHeadset: Proxy object connected
09-09 17:18:19.773  3882  3882 D HeadsetProfile: Bluetooth service connected
09-09 17:18:19.773   872   889 D BluetoothHeadset: Proxy object connected
,09-09 17:18:19.777  1370  2170 D BluetoothHeadset: Proxy object connected
,09-09 17:18:19.777  1370  1370 D HeadsetProfile: Bluetooth service connected
,09-09 17:18:19.817   282   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 17:18:19.820   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 17:18:19.826   872  1337 D SurfaceControl: Excessive delay in setPowerMode(): 232ms
,09-09 17:18:19.832   872   892 I DreamManagerService: Entering dreamland.
,09-09 17:18:19.835   872   892 I PowerManagerService: Dozing...
,09-09 17:18:19.835   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 17:18:19.877   376  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 17:18:19.877   376  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 17:18:19.881   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 17:18:19.884   872  1313 E native  : do suspend false
,09-09 17:18:19.893  1985  4220 D NfcService: Discovery configuration equal, not updating.
,09-09 17:18:19.912   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 17:18:19.917   872  1313 E native  : do suspend true
,09-09 17:18:20.018   376  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 17:18:20.019   376  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 17:18:20.066  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:20.066  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:20.066  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-09 17:18:20.066  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:20.066  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:20.066  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:20.066  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:20.066  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:20.074  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:20.077  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:20.077  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22257e2 added. We now have 8 listener(s)
,09-09 17:18:20.078  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:20.081   872  1947 D WifiService: setWifiEnabled: false pid=3814, uid=10000
,09-09 17:18:20.082   872  1947 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:18:20.091  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:20.091   872  2037 D WifiService: setWifiEnabled: true pid=3814, uid=10000
,09-09 17:18:20.092   872  2037 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:18:20.101   872  1313 D WifiConfigStore: Loading config and enabling all networks 
,09-09 17:18:20.107  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:20.107  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:20.107  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:20.107  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:20.107  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:20.107  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:20.107  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:20.107  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:20.115  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:20.117  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:20.117  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:20.117  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:20.117  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:20.117  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:20.117  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:20.117  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:20.117  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:20.119  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:20.124  3814  3864 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 17:18:20.125  3814  3864 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 17:18:20.127  3814  3864 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5a07cbe Bundle[{}]
,09-09 17:18:20.128  3814  3864 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 17:18:20.128  3814  3864 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 17:18:20.128  3814  3864 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 17:18:20.129  3814  3864 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 17:18:20.129  3814  3864 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 17:18:20.130  3814  3864 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 17:18:20.134  3814  3864 I System.out: Running OutgoingSocketThread
,09-09 17:18:20.135  3814  4228 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
,09-09 17:18:20.136  3814  4228 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43953
09-09 17:18:20.136  3814  4228 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 17:18:20.138   872  1313 D WifiConfigStore: loaded 0 passpoint configs
,09-09 17:18:20.139   872  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 17:18:20.139   872  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 17:18:20.140   872  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 17:18:20.140   872  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 17:18:20.141   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 17:18:20.141   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 17:18:20.153   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 17:18:20.154   372   870 D CommandListener: Setting iface cfg
,09-09 17:18:20.155   872  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-09 17:18:20.155   872  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 17:18:20.155   872  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.08 delta 1000 -> 1000
09-09 17:18:20.155   872  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 17:18:20.158   872  1312 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 17:18:20.158   872  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 17:18:20.169   872  1313 E native  : do suspend true
,09-09 17:18:20.183   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-09 17:18:20.184   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:18:20.199   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 17:18:20.266   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 17:18:20.268  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 17:18:20.745  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 17:18:20.777  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 17:18:20.777  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 17:18:20.783   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 17:18:20.796   872  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 17:18:20.797   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:18:20.797   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 17:18:20.820   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:18:20.835   372   870 D CommandListener: Setting iface cfg
,09-09 17:18:20.836   872  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 17:18:20.845   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 17:18:20.878   872  4232 D DhcpClient: Receive thread started
,09-09 17:18:20.961   872  1313 E native  : do suspend false
,09-09 17:18:20.982   872  2165 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 17:18:20.998   872  4232 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-09 17:18:20.999   872  2165 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-09 17:18:21.002   872  2165 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 17:18:21.017   872  4232 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 17:18:21.018   872  2165 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 17:18:21.023   372   870 D CommandListener: Setting iface cfg
,09-09 17:18:21.034   872  2165 D DhcpClient: Scheduling renewal in 86399s
,09-09 17:18:21.040   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 17:18:21.043   872  1313 E native  : do suspend true
,09-09 17:18:21.059   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 17:18:21.062   872  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 17:18:21.063   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 17:18:21.065   872  1315 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 17:18:21.072   872  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 17:18:21.136  3814  3864 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,09-09 17:18:21.137  3814  3864 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
09-09 17:18:21.138   872  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 17:18:21.138   872  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 17:18:21.141   872  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 17:18:21.143   872  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 17:18:21.145  3814  3864 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,09-09 17:18:21.145  3814  3864 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 17:18:21.145  3814  3864 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
09-09 17:18:21.148   872  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 17:18:21.149  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:21.150  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a327773 added. We now have 2 listener(s)
09-09 17:18:21.153  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:18:21.153  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:21.153  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:21.153  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:21.154  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd41630 added. We now have 9 listener(s)
09-09 17:18:21.154  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:21.155  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:21.161   872  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 17:18:21.166  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:21.167   872  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-09 17:18:21.167   872  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 17:18:21.167   872  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 17:18:21.167   872  1315 D ConnectivityService:    accepting network in place of null
09-09 17:18:21.167   872  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 17:18:21.168   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 17:18:21.169   872  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 17:18:21.171  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:21.171  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:21.171  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:21.171  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:21.171  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:21.171  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:21.171  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:21.171  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:21.174  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:21.175  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:21.175  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:21.175  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92102e added. We now have 3 listener(s)
,09-09 17:18:21.177  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:18:21.177  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:18:21.177  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:21.177  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:21.177  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b317cf added. We now have 10 listener(s)
09-09 17:18:21.177  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:21.177  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:21.178  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:21.178  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:21.178  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:18:21.178  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.178  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:21.178  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:21.178  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a327773 removed from the list
,09-09 17:18:21.178  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.178  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd41630 removed from the list
09-09 17:18:21.181  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:21.181  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:21.181  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:21.181  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:21.181  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:21.181  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:21.181  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:21.181  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:18:21.184  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:18:21.187  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:21.187  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:21.187  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.188  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.188  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.189  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:21.189  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:21.189  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.189  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd41630 not in the list
09-09 17:18:21.190  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:21.190  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.191  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:21.191  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:21.191  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.192  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b317cf removed from the list
09-09 17:18:21.192  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:21.192  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.192  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.192  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:21.192  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f92102e removed from the list
,09-09 17:18:21.193  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:21.193  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c655c added. We now have 2 listener(s)
,09-09 17:18:21.196  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:18:21.196  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:21.197  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:21.197  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:21.197  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a16065 added. We now have 9 listener(s)
09-09 17:18:21.197  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:21.198  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:21.201  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:21.206  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:21.206  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:21.206  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:21.206  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:21.206  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:21.206  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:21.206  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:21.206  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:18:21.209  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:21.209   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:18:21.209  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:18:21.209  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:21.209  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef361eb added. We now have 3 listener(s)
09-09 17:18:21.211  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:21.213  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:21.213  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:18:21.215  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:18:21.215  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:18:21.216  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:21.217  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c387b48 added. We now have 10 listener(s)
,09-09 17:18:21.218  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:21.219  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 17:18:21.219  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 17:18:21.219  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:21.219  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:21.219  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:18:21.223  3814  3864 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 17:18:21.224  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:18:21.229  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-09 17:18:21.230  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:18:21.230  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:18:21.234  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:18:21.234  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:18:21.234  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:18:21.235  3814  3864 D BluetoothAdapter: STATE_ON
,09-09 17:18:21.237   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 17:18:21.240   872  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 17:18:21.240   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:18:21.240  4169  4180 D BtGatt.GattService: registerClient() - UUID=335f04df-80d9-4251-bd6c-1e1306183ba1
09-09 17:18:21.241  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=335f04df-80d9-4251-bd6c-1e1306183ba1, clientIf=5
,09-09 17:18:21.242  3814  3824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 17:18:21.243  4169  4198 D BtGatt.GattService: start scan with filters
09-09 17:18:21.244   872  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 17:18:21.251  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:21.251  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:21.251  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:21.251  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:21.251  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:21.251  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:21.251  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:21.251  3814  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:18:21.252   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-09 17:18:21.252  3814  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:18:21.255  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:21.256  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:18:21.256  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:18:21.256  4169  4188 D BtGatt.ScanManager: handling starting scan
09-09 17:18:21.256  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 17:18:21.256  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:18:21.258  4169  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f01b72
09-09 17:18:21.259  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:18:21.259  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:18:21.259  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:18:21.260  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:18:21.260  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:18:21.261  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.261  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 17:18:21.262  3814  3864 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:18:21.262  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:18:21.262  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:18:21.262  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.262  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:18:21.262  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:18:21.262  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:18:21.263  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 17:18:21.263  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:18:21.263  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 17:18:21.263  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.263  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:18:21.263  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:18:21.263  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:18:21.264  3814  3864 D BluetoothAdapter: STATE_ON
09-09 17:18:21.263  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 17:18:21.265  4169  4198 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:18:21.265  4169  4208 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:18:21.265  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:21.265  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:18:21.266  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:18:21.266  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:18:21.266  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:18:21.266  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 17:18:21.266  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.266  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:18:21.266  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:18:21.267  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:18:21.267  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:18:21.267  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 17:18:21.267  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.269  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:21.270  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:21.270  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:21.270  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:18:21.271  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 17:18:21.271  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.271  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:18:21.272  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:21.272  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:21.272  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:18:21.272  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:21.272  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.272  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:21.272  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:21.272  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c655c removed from the list
09-09 17:18:21.272  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.272  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a16065 removed from the list
09-09 17:18:21.272  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:21.272  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:21.273  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.273  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.273  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:21.273  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:21.273  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:18:21.273  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a16065 not in the list
09-09 17:18:21.274  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.274  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.274  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 17:18:21.274  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.274  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:21.274  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:21.274  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.274  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c387b48 removed from the list
,09-09 17:18:21.274  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:21.274  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 17:18:21.274  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.275  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.275  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:21.275  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef361eb removed from the list
09-09 17:18:21.275  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:21.275  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efe03f4 added. We now have 2 listener(s)
,09-09 17:18:21.276  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:18:21.276  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.276  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 17:18:21.276  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:18:21.276  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:21.277  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:21.277  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:21.277  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a14371d added. We now have 9 listener(s)
,09-09 17:18:21.277  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:21.277  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:18:21.278  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:21.281  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:21.281  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:21.281  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:21.281  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:21.281  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:21.281  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:21.281  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:21.281  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:18:21.283  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:18:21.283  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:18:21.284  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:21.284  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a82363 added. We now have 3 listener(s)
09-09 17:18:21.285  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:21.285  1701  1701 D SystemUpdateService: onCreate
,09-09 17:18:21.286  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:18:21.286  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:21.286  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:21.286  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:21.286  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f16b60 added. We now have 10 listener(s)
09-09 17:18:21.286  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:21.287  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:21.287  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:21.287  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:21.287  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:21.287  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:21.287  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:18:21.287  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:21.288  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 17:18:21.289  3814  3864 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 17:18:21.290  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:18:21.292  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:18:21.292  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 17:18:21.292  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:18:21.295  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:18:21.296  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:18:21.296  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 17:18:21.296  3814  3864 D BluetoothAdapter: STATE_ON
09-09 17:18:21.298  4169  4208 D BtGatt.GattService: registerClient() - UUID=882c62e5-53f2-479d-aed4-6f4b754cd22f
09-09 17:18:21.298  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=882c62e5-53f2-479d-aed4-6f4b754cd22f, clientIf=5
09-09 17:18:21.298  3814  3824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 17:18:21.298  4169  4179 D BtGatt.GattService: start scan with filters
09-09 17:18:21.301  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:18:21.301  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:18:21.301  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:18:21.301  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:18:21.301  4169  4188 D BtGatt.ScanManager: handling starting scan
09-09 17:18:21.303  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:18:21.303  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:18:21.303  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:18:21.304  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:18:21.304  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 17:18:21.304  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.304  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 17:18:21.305  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 17:18:21.305  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.306  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:21.306  3814  3864 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 17:18:21.306  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:21.306  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:21.306  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:18:21.306  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:21.306  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:21.306  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.306  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 17:18:21.306  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:21.306  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efe03f4 removed from the list
09-09 17:18:21.306  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:18:21.306  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a14371d removed from the list
09-09 17:18:21.306  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:21.306  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:21.306  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 17:18:21.307  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.307  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 17:18:21.307  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:21.307  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:21.308  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:21.308  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:21.308  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.308  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 17:18:21.308  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a14371d not in the list
,09-09 17:18:21.308  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.308  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:18:21.308  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:18:21.308  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:18:21.308  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-09 17:18:21.308  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:18:21.308  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 17:18:21.309  3814  3864 D BluetoothAdapter: STATE_ON
,09-09 17:18:21.309  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 17:18:21.309  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:18:21.310  4169  4180 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:18:21.310  4169  4198 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:18:21.310  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:21.310  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:18:21.310  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 17:18:21.310  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:18:21.310  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 17:18:21.311  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-09 17:18:21.311  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:18:21.311  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:18:21.311  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:18:21.312  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.312  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:21.312  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:18:21.312  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.312  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f16b60 removed from the list
09-09 17:18:21.312  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:18:21.312  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:21.313  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.313  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.313  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 17:18:21.313  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:21.313  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a82363 removed from the list
09-09 17:18:21.313  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:18:21.313  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:18:21.313  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1dd8c added. We now have 2 listener(s)
09-09 17:18:21.314  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 17:18:21.314  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:18:21.314  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:18:21.315  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:21.315  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:21.315  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:18:21.315  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:21.315  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc42cd5 added. We now have 9 listener(s)
,09-09 17:18:21.315  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:21.315  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:18:21.316  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:18:21.317  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:18:21.318  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 17:18:21.319  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:18:21.319  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.319  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:21.321  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-09 17:18:21.322  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 17:18:21.322  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:21.322  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:21.322  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:21.322  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:21.322  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:21.322  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:21.322  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:21.322  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:18:21.324  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:21.324  3974  3974 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-09 17:18:21.324  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:21.324  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:18:21.324  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c149bdb added. We now have 3 listener(s)
09-09 17:18:21.326  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 17:18:21.326  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:18:21.326  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:21.326  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:21.326  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a54678 added. We now have 10 listener(s)
,09-09 17:18:21.326  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:21.326  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:21.326  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 17:18:21.326  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:21.326  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:21.326  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:18:21.327  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:21.328  3974  3974 D SprintDMHelper: simOperator: 
,09-09 17:18:21.328  3974  3974 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 17:18:21.329  3814  3864 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 17:18:21.329  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:18:21.330  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:21.331  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:18:21.332  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 17:18:21.332  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:18:21.335  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:18:21.335  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:18:21.336  3814  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
09-09 17:18:21.336  3814  3864 D BluetoothAdapter: STATE_ON
,09-09 17:18:21.339  1701  4245 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 17:18:21.339  1701  4245 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 17:18:21.341  1701  4245 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 17:18:21.341  4169  4180 D BtGatt.GattService: registerClient() - UUID=81994953-c338-42a9-a714-127ab686c3cc
09-09 17:18:21.342  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=81994953-c338-42a9-a714-127ab686c3cc, clientIf=5
,09-09 17:18:21.342  3814  3824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 17:18:21.343  4169  4198 D BtGatt.GattService: start scan with filters
09-09 17:18:21.320  1701  4242 I SystemUpdateService: active receiver: enabled
,09-09 17:18:21.346  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:18:21.346  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:18:21.346  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:18:21.346  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 17:18:21.346  4169  4188 D BtGatt.ScanManager: handling starting scan
,09-09 17:18:21.348  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 17:18:21.348  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.348  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:18:21.348  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:18:21.348  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:18:21.349  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 17:18:21.350  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 17:18:21.352  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 17:18:21.352  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.352  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:18:21.352  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 17:18:21.354  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 17:18:21.354  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:18:21.355  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 17:18:21.355  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.355  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:21.355  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:18:21.355  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:21.355  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:18:21.355  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.355  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:18:21.355  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:21.355  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1dd8c removed from the list
09-09 17:18:21.356  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:18:21.356  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc42cd5 removed from the list
09-09 17:18:21.356  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:21.356  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:21.356  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.356  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 17:18:21.356  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.356  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:21.360  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:18:21.360  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:21.360  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.360  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc42cd5 not in the list
,09-09 17:18:21.360  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:18:21.360  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:18:21.361  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:18:21.361  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:18:21.361  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 17:18:21.361  3814  3864 D BluetoothAdapter: STATE_ON
,09-09 17:18:21.361  4169  4198 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:18:21.362  4169  4208 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 17:18:21.362  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 17:18:21.362  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:18:21.362  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 17:18:21.362  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:18:21.362  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 17:18:21.363  1701  2546 I iu.UploadsManager: num queued entries: 0
09-09 17:18:21.363  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 17:18:21.363  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.363  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:18:21.363  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:18:21.363  3814  3864 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:18:21.363  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:18:21.363  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:18:21.364  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:21.364  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:21.365  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:21.365  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.365  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a54678 removed from the list
,09-09 17:18:21.365  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:18:21.365  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:21.365  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.365  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.365  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:21.365  3814  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:21.365  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c149bdb removed from the list
,09-09 17:18:21.365  3814  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:18:21.365  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:21.365  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8245224 added. We now have 2 listener(s)
09-09 17:18:21.367  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 17:18:21.367  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:18:21.367  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:21.367  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 17:18:21.367  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:21.367  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:21.367  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@456218d added. We now have 9 listener(s)
,09-09 17:18:21.367  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 17:18:21.367  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:21.367  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:21.368  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 17:18:21.368  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 17:18:21.370  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:21.372  3814  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:21.372  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:21.372  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:21.372  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:21.372  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:21.372  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:21.372  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:21.372  3814  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:18:21.374  1701  2546 I iu.UploadsManager: num updated entries: 0
,09-09 17:18:21.374  3814  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:21.374  3814  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:21.374  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:21.374  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98ab53 added. We now have 3 listener(s)
,09-09 17:18:21.376  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 17:18:21.376  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:18:21.376  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:21.376  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:21.376  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a666c90 added. We now have 10 listener(s)
09-09 17:18:21.376  3814  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:21.377  3814  3864 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:18:21.377  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:21.377  3814  3864 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:21.377  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:21.377  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.377  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:21.377  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:21.377  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:21.377  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8245224 removed from the list
09-09 17:18:21.377  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.377  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@456218d removed from the list
,09-09 17:18:21.377  1701  4242 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 17:18:21.379  3814  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:21.379  3814  3864 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:21.379  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.379  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.379  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:21.380  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:21.380  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:21.380  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:18:21.380  3814  3864 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@456218d not in the list
09-09 17:18:21.380  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.380  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.381  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:21.381  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:18:21.381  3814  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:21.381  3814  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a666c90 removed from the list
09-09 17:18:21.381  3814  3864 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:21.382  3814  3864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:21.382  3814  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:21.382  3814  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 17:18:21.382  3814  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98ab53 removed from the list
09-09 17:18:21.383  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 17:18:21.383  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 17:18:21.383  1701  2546 I iu.SyncManager: NEXT; no task
09-09 17:18:21.383  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 17:18:21.384  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:21.384  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-09 17:18:21.384  3814  3864 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:21.384  1701  4242 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-09 17:18:21.384  1701  4242 I SystemUpdateService: now status is 0 (complete)
09-09 17:18:21.384  1701  4242 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 17:18:21.384  1701  4242 I SystemUpdateService: file has been verified
09-09 17:18:21.385  1701  4242 I SystemUpdateService: OTA package size = 12249756
,09-09 17:18:21.389  1701  4242 I SystemUpdateService: showing system update notification
,09-09 17:18:21.395  3814  4251 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
09-09 17:18:21.395  3814  4251 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
09-09 17:18:21.395  3814  4251 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 17:18:21.398  1701  1701 D SystemUpdateService: onDestroy
,09-09 17:18:21.399  3814  4252 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
09-09 17:18:21.399  3814  4252 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
09-09 17:18:21.399  3814  4252 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 17:18:21.402  3814  3864 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 17:18:21.402  3814  3864 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 17:18:21.402  3814  3864 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-09 17:18:21.402  3814  3864 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 17:18:21.402  3814  3864 D com.test.thalitest.ThaliTestRunner: Total duration: 21828 ms
09-09 17:18:21.402  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 17:18:21.403  3814  3864 I jxcore-log: *Native tests were executed*
09-09 17:18:21.403  3814  3864 I jxcore-log: 
09-09 17:18:21.404  3814  3864 I jxcore-log: Total number of executed tests:  80
09-09 17:18:21.404  3814  3864 I jxcore-log: 
09-09 17:18:21.404  3814  3864 I jxcore-log: Number of passed tests:  80
09-09 17:18:21.404  3814  3864 I jxcore-log: 
09-09 17:18:21.404  3814  3864 I jxcore-log: Number of failed tests:  0
09-09 17:18:21.404  3814  3864 I jxcore-log: 
09-09 17:18:21.404  3814  3864 I jxcore-log: Number of ignored tests:  0
09-09 17:18:21.404  3814  3864 I jxcore-log: 
09-09 17:18:21.404  3814  3864 I jxcore-log: Total duration:  21828
09-09 17:18:21.404  3814  3864 I jxcore-log: 
09-09 17:18:21.405  3814  3864 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 17:18:21.405  3814  3864 I jxcore-log: 
,09-09 17:18:21.405  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 17:18:21.408  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.408  3814  3864 I jxcore-log: 
09-09 17:18:21.410  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.410  3814  3864 I jxcore-log: 
09-09 17:18:21.411  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.411  3814  3864 I jxcore-log: 
09-09 17:18:21.412  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.412  3814  3864 I jxcore-log: 
09-09 17:18:21.412  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.412  3814  3864 I jxcore-log: 
09-09 17:18:21.414  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.414  3814  3864 I jxcore-log: 
09-09 17:18:21.414  3814  3814 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 17:18:21.416  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.416  3814  3864 I jxcore-log: 
09-09 17:18:21.417  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.417  3814  3864 I jxcore-log: 
09-09 17:18:21.418  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.418  3814  3864 I jxcore-log: 
09-09 17:18:21.418  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:21.418  3814  3864 I jxcore-log: 
,09-09 17:18:21.419  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:21.419  3814  3864 I jxcore-log: 
09-09 17:18:21.420  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:21.420  3814  3864 I jxcore-log: 
09-09 17:18:21.421  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.421  3814  3864 I jxcore-log: 
09-09 17:18:21.422  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.422  3814  3864 I jxcore-log: 
,09-09 17:18:21.423  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:21.423  3814  3864 I jxcore-log: 
,09-09 17:18:21.424  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:21.424  3814  3864 I jxcore-log: 
09-09 17:18:21.424  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.424  3814  3864 I jxcore-log: 
09-09 17:18:21.425  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.425  3814  3864 I jxcore-log: 
,09-09 17:18:21.425  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.425  3814  3864 I jxcore-log: 
09-09 17:18:21.426  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.426  3814  3864 I jxcore-log: 
,09-09 17:18:21.426  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.426  3814  3864 I jxcore-log: 
09-09 17:18:21.427  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.427  3814  3864 I jxcore-log: 
,09-09 17:18:21.427  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.427  3814  3864 I jxcore-log: 
,09-09 17:18:21.428  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:21.428  3814  3864 I jxcore-log: 
09-09 17:18:21.428  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:21.428  3814  3864 I jxcore-log: 
09-09 17:18:21.429  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:21.429  3814  3864 I jxcore-log: 
09-09 17:18:21.429  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.429  3814  3864 I jxcore-log: 
,09-09 17:18:21.430  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:21.430  3814  3864 I jxcore-log: 
09-09 17:18:21.430  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.430  3814  3864 I jxcore-log: 
,09-09 17:18:21.431  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.431  3814  3864 I jxcore-log: 
09-09 17:18:21.431  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.431  3814  3864 I jxcore-log: 
,09-09 17:18:21.432  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.432  3814  3864 I jxcore-log: 
,09-09 17:18:21.432  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:21.432  3814  3864 I jxcore-log: 
,09-09 17:18:21.434  1513  2989 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 17:18:21.434  1513  2989 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 17:18:21.434  1513  2989 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 17:18:21.434  1513  2989 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 17:18:21.446  1701  4245 E MDM     : [179] SitrepService.a: Error sending sitrep.
,09-09 17:18:21.771  3814  3814 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:18:21.774  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:21.774  3814  3864 I jxcore-log: 
,09-09 17:18:21.814  3814  3814 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:18:21.816  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:21.816  3814  3864 I jxcore-log: 
,09-09 17:18:21.866  3814  3814 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:18:21.869  3814  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:21.869  3814  3864 I jxcore-log: 
,09-09 17:18:22.015  4253  4253 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-09 17:18:22.020  4253  4253 D AndroidRuntime: CheckJNI is OFF
,09-09 17:18:22.062  4253  4253 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-09 17:18:22.108  4253  4253 I Radio-JNI: register_android_hardware_Radio DONE
,09-09 17:18:22.131  4253  4253 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 17:18:22.144   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 17:18:22.144   872   885 I ActivityManager: Killing 3814:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-09 17:18:22.237   872  1948 I WindowState: WIN DEATH: Window{4399b61 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 17:18:22.237   872  1944 D GraphicsStats: Buffer count: 2
,09-09 17:18:22.239   872  1314 D WifiService: Client connection lost with reason: 4
,09-09 17:18:22.240   872  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 17:18:22.302   872   895 W PackageSettings: Skipping PackageSetting{db599b7 com.example.hello/10273} due to missing metadata
,09-09 17:18:22.324   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-09 17:18:22.324   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-09 17:18:22.325   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-09 17:18:22.325   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 17:18:22.325   872   885 E ActivityManager: 	,at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 17:18:22.325   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.325   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.325   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:22.325   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 17:18:22.325   872   885 I ActivityManager:   Force finishing activity ActivityRecord{90fd24e u0 com.test.thalitest/.MainActivity t4}
09-09 17:18:22.326   872   895 I art     : Starting a blocking GC Explicit
,09-09 17:18:22.342   872  2037 W ActivityManager: Spurious death for ProcessRecord{56a9aee 0:com.test.thalitest/u0a0}, curProc for 3814: null
,09-09 17:18:22.379   872   895 I art     : Explicit concurrent mark sweep GC freed 52246(3MB) AllocSpace objects, 10(372KB) LOS objects, 33% free, 29MB/43MB, paused 856us total 52.431ms
,09-09 17:18:22.400   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-09 17:18:22.402  4253  4253 I art     : System.exit called, status: 0
09-09 17:18:22.402  4253  4253 I AndroidRuntime: VM exiting with result code 0.
,09-09 17:18:22.410   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-09 17:18:22.426   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-09 17:18:22.429  4169  4169 D BluetoothMapAppObserver: onReceive
,09-09 17:18:22.430  4169  4169 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 17:18:22.431  1902  1902 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 17:18:22.432  1863  2114 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 17:18:22.433   872  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 17:18:22.436  3689  3689 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) },
,09-09 17:18:22.440  1902  4264 I Keyboard.Facilitator.DecoderInitializer: run()
,09-09 17:18:22.442  1902  4264 I Decoder : createOrResetDecoder
,09-09 17:18:22.450   872   882 I ActivityManager: Start proc 4265:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-09 17:18:22.467  1997  1997 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-09 17:18:22.485  1513  1513 I ConfigService: onCreate
,09-09 17:18:22.497  4265  4265 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-09 17:18:22.500  1902  4264 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-09 17:18:22.528   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 17:18:22.528   872  1747 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3814 uid 10000
09-09 17:18:22.529  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-09 17:18:22.530  1902  4264 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-09 17:18:22.532  1902  4264 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 17:18:22.532  1902  4264 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-09 17:18:22.535  1902  4264 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-09 17:18:22.535  1902  4264 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 17:18:22.535  1902  4264 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-09 17:18:22.535  1902  4264 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-09 17:18:22.536  1902  4264 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-09 17:18:22.536  1902  4264 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-09 17:18:22.536  1902  4264 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 17:18:22.536  1902  4264 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 17:18:22.536  1902  4264 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-09 17:18:22.536  1902  4264 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-09 17:18:22.568   872  1338 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,09-09 17:18:22.568   872  1338 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
,09-09 17:18:22.568   872  1338 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,09-09 17:18:22.568   872  1338 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
09-09 17:18:22.568   872  1338 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
09-09 17:18:22.568   872  1338 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
,09-09 17:18:22.568   872  1338 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
09-09 17:18:22.568   872  1338 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
,09-09 17:18:22.568   872  1338 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
09-09 17:18:22.568   872  1338 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-09 17:18:22.568   872  1338 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-09 17:18:22.568   872  1338 W System.err: 	... 4 more
,09-09 17:18:22.568   872  1338 D skia    : ------- write threw an exception
,09-09 17:18:22.578  2009  2125 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 17:18:22.578   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-09 17:18:22.578   872   884 E PackageManager: Failed to write settings, restoring backup
09-09 17:18:22.578   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 17:18:22.578   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 17:18:22.578   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 17:18:22.578   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 17:18:22.578   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 17:18:22.578   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.578   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.578   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:18:22.580  4265  4265 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-09 17:18:22.582   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-09 17:18:22.582   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 17:18:22.582   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	,at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:18:22.582   872   885 E DropBoxManagerService: 	... 13 more
,09-09 17:18:22.587  4265  4282 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.587  4265  4282 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.588  4265  4282 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:18:22.590   872  1526 I ActivityManager: Start proc 4284:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-09 17:18:22.590  2009  2125 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 17:18:22.590  2009  2125 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2009
09-09 17:18:22.590  2009  2125 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: ,	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.590  2009  2125 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:18:22.593   872  2039 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 17:18:22.593   872  4290 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:22.593   872  4290 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:18:22.593   872  4290 E DropBoxManagerService: 	... 5 more
,09-09 17:18:22.596  2009  2125 I Process : Sending signal. PID: 2009 SIG: 9
,09-09 17:18:22.615   872  1368 I ActivityManager: Start proc 4299:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-09 17:18:22.619  4265  4298 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-09 17:18:22.662  4299  4299 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-09 17:18:22.683  1513  1513 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 17:18:22.684  1513  1513 D AndroidRuntime: Shutting down VM
09-09 17:18:22.684  1513  1513 E AndroidRuntime: FATAL EXCEPTION: main
09-09 17:18:22.684  1513  1513 E AndroidRuntime: Process: com.google.process.gapps, PID: 1513
09-09 17:18:22.684  1513  1513 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 17:18:22.684  1513  1513 E AndroidRuntime: 	... 8 more
,09-09 17:18:22.688  1513  1513 I Process : Sending signal. PID: 1513 SIG: 9
09-09 17:18:22.688   872  4315 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:22.688   872  4315 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:18:22.688   872  4315 E DropBoxManagerService: 	... 5 more
,09-09 17:18:22.715   872  1314 D WifiService: Client connection lost with reason: 4
,09-09 17:18:22.720   872  1943 I ActivityManager: Process com.google.process.gapps (pid 1513) has died
,09-09 17:18:22.721   872  1943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,09-09 17:18:22.721   872  1943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
09-09 17:18:22.721   872  1943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
09-09 17:18:22.721   872  1943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
09-09 17:18:22.722   872  1945 D GraphicsStats: Buffer count: 1
09-09 17:18:22.722   872  2037 I WindowState: WIN DEATH: Window{124f3de u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-09 17:18:22.733   872  1747 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2009) has died
,09-09 17:18:22.733   872  1747 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40988ms
,09-09 17:18:22.734  1701  1701 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-09 17:18:22.734   872  1747 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 17:18:22.751   872  2171 I ActivityManager: Start proc 4318:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-09 17:18:22.768   872   885 I ActivityManager: Start proc 4329:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 17:18:22.786  4318  4318 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-09 17:18:22.794  4318  4318 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,09-09 17:18:22.797  4318  4318 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:22.797  4318  4318 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:22.797  4318  4318 D AndroidRuntime: Shutting down VM
,09-09 17:18:22.798  4318  4318 E AndroidRuntime: FATAL EXCEPTION: main
09-09 17:18:22.798  4318  4318 E AndroidRuntime: Process: com.google.process.gapps, PID: 4318
09-09 17:18:22.798  4318  4318 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	,at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 17:18:22.798  4318  4318 E AndroidRuntime: 	... 10 more
,09-09 17:18:22.802  4318  4318 I Process : Sending signal. PID: 4318 SIG: 9
,09-09 17:18:22.803   872  4343 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:22.803   872  4343 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:18:22.803   872  4343 E DropBoxManagerService: 	... 5 more
,09-09 17:18:22.817  4265  4282 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-09 17:18:22.817  4329  4329 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:22.817  4329  4329 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 17:18:22.817  4329  4329 D AndroidRuntime: Shutting down VM
,09-09 17:18:22.824  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-09 17:18:22.824  1701  1701 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-09 17:18:22.825  4329  4329 E AndroidRuntime: FATAL EXCEPTION: main
09-09 17:18:22.825  4329  4329 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4329
09-09 17:18:22.825  4329  4329 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvide,r.java:89)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 17:18:22.825  4329  4329 E AndroidRuntime: 	... 10 more
,09-09 17:18:22.830   872  1368 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 17:18:22.831   872  4345 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:22.831   872  4345 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:18:22.831   872  4345 E DropBoxManagerService: 	... 5 more
,09-09 17:18:22.832  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-09 17:18:22.832  1701  1701 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-09 17:18:22.834  4329  4329 I Process : Sending signal. PID: 4329 SIG: 9
,09-09 17:18:22.841   872  1945 I ActivityManager: Process com.google.process.gapps (pid 4318) has died
,09-09 17:18:22.837  1701  4346 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-09 17:18:22.842   872  1945 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{8d2610a u0 com.google.android.gms/.gcm.GcmService}
09-09 17:18:22.842   872  1945 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{6232950 u0 com.google.android.gms/.config.ConfigService}
09-09 17:18:22.842   872  1945 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{5e84097 u0 com.google.android.gms/.auth.GetToken}
,09-09 17:18:22.842   872  1945 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{4f4196 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,09-09 17:18:22.854   872  1945 I ActivityManager: Start proc 4348:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,09-09 17:18:22.858   872  2037 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
,09-09 17:18:22.859   872  2037 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
09-09 17:18:22.859   872  2037 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-09 17:18:22.859   872  2037 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 17:18:22.859   872  2037 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-09 17:18:22.859   872  2037 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-09 17:18:22.859   872  2037 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-09 17:18:22.859   872  2037 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-09 17:18:22.859   872  2037 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-09 17:18:22.859   872  2037 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-09 17:18:22.859   872  2037 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-09 17:18:22.859   872  2037 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 17:18:22.865  1701  4346 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-09 17:18:22.865  1701  4346 E AndroidRuntime: Process: com.google.android.gms, PID: 1701
09-09 17:18:22.865  1701  4346 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 17:18:22.865  1701  4346 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,09-09 17:18:22.867  4265  4298 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.867  4265  4298 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:18:22.868  4265  4298 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 17:18:22.868  4265  4298 E AndroidRuntime: Process: android.process.acore, PID: 4265
09-09 17:18:22.868  4265  4298 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 17:18:22.868  4265  4298 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:18:22.869  4265  4282 I Process : Sending signal. PID: 4265 SIG: 9
,09-09 17:18:22.883   872  2037 I ActivityManager: Start proc 4361:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,09-09 17:18:22.884   872   882 W ActivityManager: Spurious death for ProcessRecord{9802b7d 4361:com.google.android.googlequicksearchbox/u0a28}, curProc for 4329: null
,09-09 17:18:22.886   280   280 E lowmemorykiller: Error writing /proc/4265/oom_score_adj; errno=22
,09-09 17:18:22.888   872  4371 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:22.888   872  4371 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:18:22.888   872  4371 E DropBoxManagerService: 	... 5 more
,09-09 17:18:22.889   872  4372 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:22.889   872  4372 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 17:18:22.889   872  4372 E DropBoxManagerService: 	... 5 more
,09-09 17:18:22.890  1701  4346 I Process : Sending signal. PID: 1701 SIG: 9
09-09 17:18:22.893  2071  4347 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-09 17:18:22.911   282   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
