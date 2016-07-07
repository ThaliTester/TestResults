#### Test 7578926821ef376_thali04_htc-Nexus 9 Logs


```
--------- beginning of system
,07-07 20:27:32.978   454   483 I ActivityManager: Start proc 2782:com.google.android.apps.books/u0a28 for service com.google.android.apps.books/.service.SyncService
--------- beginning of main
07-07 20:27:33.017  2782  2782 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm64
07-07 20:27:33.084  2782  2782 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-07 20:27:33.091  2782  2782 I BooksApp: Created application version: 3.6.9 (30609)
07-07 20:27:33.162  2782  2801 I BooksSync: Starting books sync for 61035162, extras: ade
07-07 20:27:33.255  2782  2807 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
07-07 20:27:33.287  1103  1163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-07 20:27:33.287  1103  1163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:27:33.287  1103  1163 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:27:33.287  1103  1163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-07 20:27:33.307  1103  1122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-07 20:27:33.307  1103  1122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:27:33.307  1103  1122 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:27:33.308  1103  1122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-07 20:27:33.315  2782  2807 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:27:33.316  2782  2801 E BooksSync: Soft error
07-07 20:27:33.316  2782  2801 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:27:33.316  2782  2801 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:27:33.316  2782  2801 E BooksSync: Sync error
07-07 20:27:33.316  2782  2801 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:27:33.316  2782  2801 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:27:33.316  2782  2801 I BooksSync: Finished books sync
07-07 20:27:33.321   454  1160 I ActivityManager: Killing 2179:com.google.android.music:main/u0a61 (adj 15): empty #17
07-07 20:27:33.324   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 89590, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
07-07 20:27:33.408  2795  2795 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-07 20:27:33.411  2795  2795 D AndroidRuntime: CheckJNI is OFF
07-07 20:27:33.444  2795  2795 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-07 20:27:33.480  2795  2795 I Radio-JNI: register_android_hardware_Radio DONE
07-07 20:27:33.504  2795  2795 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-07 20:27:33.510   454   470 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-07 20:27:33.526  2795  2795 D AndroidRuntime: Shutting down VM
07-07 20:27:33.534  1079  1094 W SearchService: Abort, client detached.
07-07 20:27:33.546   454   471 I ActivityManager: Start proc 2815:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-07 20:27:33.549  1079  1079 I HotwordDetector: Closing mic
07-07 20:27:33.549  1079  1327 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@42cd61c
07-07 20:27:33.550  1079  1346 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-07 20:27:33.567   222   666 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-07 20:27:33.568  1079  1336 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-07 20:27:33.569  1079  1345 I MicroRecognitionRnrImpl: Detection finished
07-07 20:27:33.673  2815  2815 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-07 20:27:33.798  2815  2815 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-07 20:27:33.821  2815  2815 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 8790-8804)
,07-07 20:27:33.821  2815  2815 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 20:27:33.861  2815  2815 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {88cf2a8}
,07-07 20:27:33.862  2815  2815 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:27:33.862  2815  2815 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-07 20:27:33.866  2815  2815 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-07 20:27:33.868  2815  2815 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 20:27:33.902  2815  2815 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-07 20:27:33.917  2815  2815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-07 20:27:33.917  2815  2815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-07 20:27:34.138   454   496 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b59d8ad:true
,07-07 20:27:34.217  2815  2815 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-07 20:27:34.235  2815  2815 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
,07-07 20:27:34.289  2815  2856 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-07 20:27:34.317  2815  2843 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-07 20:27:34.345  2815  2856 I OpenGLRenderer: Initialized EGL, version 1.4
,07-07 20:27:34.436   454   497 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +900ms
,07-07 20:27:34.439   995   995 I Keyboard.Facilitator: onFinishInput()
,07-07 20:27:34.496  2815  2815 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2815
,07-07 20:27:34.500   454  1044 I ActivityManager: Killing 2549:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,07-07 20:27:34.533   454  1044 I ActivityManager: Killing 2434:com.google.android.apps.photos/u0a66 (adj 15): empty #18
,07-07 20:27:34.568  1103  1103 I ConfigService: onDestroy
,07-07 20:27:34.613  2815  2815 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 20:27:34.788  2815  2857 D jxcore_app_log: JniHelper::setJavaVM(0xab44e7b8), pthread_self() = -559425232
,07-07 20:27:34.796  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-07 20:27:34.796  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 20:27:34.796  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 20:27:34.796  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 20:27:34.796  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-07 20:27:34.796  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a00595f added. We now have 1 listener(s)
,07-07 20:27:34.826  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
,07-07 20:27:34.827  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:27:34.828  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:34.828  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-07 20:27:34.833  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e481c0a added. We now have 1 listener(s)
,07-07 20:27:34.834  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:34.838   454   670 D WifiService: New client listening to asynchronous messages
,07-07 20:27:34.840  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-07 20:27:34.843  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:27:34.843  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-07 20:27:34.844  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-07 20:27:34.844  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-07 20:27:34.846  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:34.847  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
,07-07 20:27:34.854  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:34.854  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:34.854  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:34.854  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:34.854  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:34.854  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:34.854  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:27:34.854  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:27:34.854  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-07 20:27:34.854  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:34.854  2815  2857 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 20:27:34.857  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:34.862  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:34.895  2815  2815 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 20:27:35.420  2815  2865 W jxcore-log: Initializing JXcore engine
,07-07 20:27:35.420  2815  2865 W jxcore-log: JXcore engine is ready
,07-07 20:27:35.461  2865  2865 W Thread-61: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=9922 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-07 20:27:35.461  2865  2865 W Thread-61: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10538]" dev="sockfs" ino=10538 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-07 20:27:35.461  2865  2865 W Thread-61: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1032 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-07 20:27:35.461  2865  2865 W Thread-61: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20766]" dev="sockfs" ino=20766 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-07 20:27:35.476  2815  2865 W jxcore-log: Starting JXcore engine
,07-07 20:27:37.556  2815  2865 W jxcore-log: Platform android
07-07 20:27:37.556  2815  2865 W jxcore-log: 
07-07 20:27:37.556  2815  2865 W jxcore-log: Process ARCH arm
07-07 20:27:37.556  2815  2865 W jxcore-log: 
,07-07 20:27:37.684  2815  2865 I jxcore-log: JXcore Cordova bridge is ready!
07-07 20:27:37.684  2815  2865 I jxcore-log: 
07-07 20:27:37.685  2815  2865 W jxcore-log: JXcore engine is started
,07-07 20:27:37.687  2815  2857 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 20:27:37.689  2815  2815 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 20:27:38.094  2782  2799 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-07 20:27:43.049  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-07 20:27:43.049  2815  2865 I jxcore-log: 
,07-07 20:27:43.050  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-07 20:27:43.050  2815  2865 I jxcore-log: 
,07-07 20:27:43.053  2815  2865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:43.053  2815  2865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:43.053  2815  2865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:43.053  2815  2865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:43.053  2815  2865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:43.053  2815  2865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:43.053  2815  2865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:27:43.053  2815  2865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:27:43.055  2815  2865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-07 20:27:43.056  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-07 20:27:43.056  2815  2865 I jxcore-log: 
,07-07 20:27:43.058  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-07 20:27:43.058  2815  2865 I jxcore-log: 
,07-07 20:27:43.145  2516  2527 D Finsky  : [221] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,07-07 20:27:43.151  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:27:43.155  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:27:43.156  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:27:43.170  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-07 20:27:43.170  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-07 20:27:43.170  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:27:43.170  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:27:43.187  2516  2527 D Finsky  : [221] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-07 20:27:44.462  2815  2865 I jxcore-log: Unit Test app is loaded
07-07 20:27:44.462  2815  2865 I jxcore-log: 
,07-07 20:27:44.465  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:27:44.465  2815  2865 I jxcore-log: 
,07-07 20:27:44.469  2815  2865 I jxcore-log: My device name is: htc-Nexus 9
07-07 20:27:44.469  2815  2865 I jxcore-log: 
,07-07 20:27:44.470  2815  2815 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-07 20:27:44.470  2815  2857 D JX-Cordova: Running tests
,07-07 20:27:44.471  2815  2865 I jxcore-log: WARN testUtils: myNameCallback not set!
07-07 20:27:44.471  2815  2865 I jxcore-log: 
,07-07 20:27:44.561  2815  2857 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-07 20:27:44.562  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-07 20:27:44.563  2815  2857 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,07-07 20:27:44.563  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-07 20:27:44.563  2815  2857 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-07 20:27:44.563  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-07 20:27:44.565  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-07 20:27:44.565  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-07 20:27:44.565  2815  2857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-07 20:27:44.565  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-07 20:27:44.565  2815  2857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-07 20:27:44.565  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-07 20:27:44.565  2815  2857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,07-07 20:27:44.565  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:27:44.566  2815  2857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-07 20:27:44.566  2815  2857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-07 20:27:44.566  2815  2857 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-07 20:27:44.566  2815  2857 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-07 20:27:44.566  2815  2857 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,07-07 20:27:44.566  2815  2857 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-07 20:27:44.566  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:44.566  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6b0d421 added. We now have 2 listener(s)
07-07 20:27:44.566  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:44.568  2815  2857 D BluetoothAdapter: enable(): BT is already enabled..!
,07-07 20:27:44.572   454  2001 D WifiService: setWifiEnabled: true pid=2815, uid=10000
,07-07 20:27:44.572   454  2001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:27:44.573  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:44.573  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c729046 added. We now have 3 listener(s)
07-07 20:27:44.573  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:44.577  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:27:44.577  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e0f207 added. We now have 4 listener(s)
07-07 20:27:44.577  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:44.578  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:27:44.578  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ef5f34 added. We now have 5 listener(s)
07-07 20:27:44.578  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:44.579   454   470 D WifiService: setWifiEnabled: false pid=2815, uid=10000
07-07 20:27:44.579   454   470 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:27:44.589   454   669 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-07 20:27:44.589   454   669 D IpReachabilityMonitor: clear: iface{wlan0/6}, v{4}, ntable=[]
07-07 20:27:44.589   454   669 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:27:44.589   454   669 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-07 20:27:44.593  1629  1675 D BluetoothAdapterState: Current state: ON, message: 23
,07-07 20:27:44.593  1629  1675 D BluetoothAdapterProperties: Setting state to 13
,07-07 20:27:44.593  1629  1675 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-07 20:27:44.593  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:27:44.594  1629  1675 D BluetoothAdapterProperties: onBluetoothDisable()
07-07 20:27:44.594  1629  1675 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:44.596  1629  1679 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:27:44.596  1629  1675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-07 20:27:44.597  1629  1629 D HeadsetService: Received stop request...Stopping profile...
07-07 20:27:44.608  1629  1629 D A2dpService: Received stop request...Stopping profile...
07-07 20:27:44.609  1629  1816 D A2dpStateMachine: Exit Disconnected: -1
07-07 20:27:44.633   454   454 D BluetoothHeadset: Proxy object disconnected
,07-07 20:27:44.634   727   891 D BluetoothHeadset: Proxy object disconnected
,07-07 20:27:44.634   727   727 D BluetoothA2dp: Proxy object disconnected
07-07 20:27:44.634   727   727 D HeadsetProfile: Bluetooth service disconnected
07-07 20:27:44.635  1629  1629 D HidService: Received stop request...Stopping profile...
07-07 20:27:44.635  1629  1629 D HidService: Stopping Bluetooth HidService
07-07 20:27:44.635   727   727 D BluetoothInputDevice: Proxy object disconnected
07-07 20:27:44.635   727   727 D HidProfile: Bluetooth service disconnected
,07-07 20:27:44.636  1629  1629 D HealthService: Received stop request...Stopping profile...
07-07 20:27:44.636   454   454 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:44.636   454   454 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:44.637  1020  1046 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:44.637  1629  1629 D PanService: Received stop request...Stopping profile...
07-07 20:27:44.638   454   454 D BluetoothA2dp: Proxy object disconnected
07-07 20:27:44.638  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:44.638  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:44.638  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:44.638  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:44.638  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:44.638  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:44.638  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:27:44.638  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:27:44.638   727   727 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-07 20:27:44.638   727   727 D PanProfile: Bluetooth service disconnected
,07-07 20:27:44.638  1629  1629 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:44.638  1629  1629 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:44.639  1629  1629 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:44.639  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:44.639  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:27:44.639  1629  1629 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:44.640  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:44.641  1629  1629 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-07 20:27:44.641  1629  1679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
,07-07 20:27:44.641  1629  1629 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-07 20:27:44.643  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:44.645  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:44.645  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:44.645  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:44.645  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:44.645  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:44.645  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:44.645  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:27:44.645  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:27:44.646  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-07 20:27:44.647  1629  1629 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:44.647  1629  1629 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:44.647  1629  1629 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:44.647  1629  1629 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:44.651  1629  1679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100020
07-07 20:27:44.651  1629  1782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:44.651  1629  1782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-07 20:27:44.652  1629  1782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-07 20:27:44.652  1629  1782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-07 20:27:44.653  1629  1782 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-07 20:27:44.653  1629  1782 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-07 20:27:44.653  1629  1782 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-07 20:27:44.653  1629  1782 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-07 20:27:44.653  1629  1679 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-07 20:27:44.654  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:44.655   454  2278 D DhcpClient: Clearing IP address
,07-07 20:27:44.656   218   538 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:27:44.665   218   538 D CommandListener: Setting iface cfg
07-07 20:27:44.668  1103  2342 V NativeCrypto: Read error: ssl=0x559bf2b3c0: I/O error during system call, Connection timed out
07-07 20:27:44.669  1629  1629 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:44.669  1629  1629 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:44.669  1629  1629 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:44.669  1629  1629 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:44.670  1103  2342 V NativeCrypto: SSL shutdown failed: ssl=0x559bf2b3c0: I/O error during system call, Broken pipe
07-07 20:27:44.671  1629  1629 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-07 20:27:44.671  1629  1679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-07 20:27:44.674   454  1152 D ConnectivityService: reportNetworkConnectivity(100, false) by 10007
,07-07 20:27:44.674   454  2275 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10007
07-07 20:27:44.671  1629  1629 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-07 20:27:44.675  1629  1629 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:44.675  1629  1629 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:44.677  1629  1629 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:44.679  1629  1629 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:44.680  1629  1629 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-07 20:27:44.680  1629  1679 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-07 20:27:44.680  1629  1629 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-07 20:27:44.681   454   485 I ActivityManager: Start proc 2898:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-07 20:27:44.682   454  2275 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-07 20:27:44.682   454   671 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-07 20:27:44.682   454   671 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
07-07 20:27:44.682   454   671 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-07 20:27:44.683   454   671 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-07 20:27:44.683   454   671 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-07 20:27:44.684   454   454 D RttService: SCAN_AVAILABLE : 1
07-07 20:27:44.687   454   685 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-07 20:27:44.690  1629  1629 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:44.690  1629  1629 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:44.691  1629  1629 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:27:44.691  1629  1629 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:44.691  1629  1675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-07 20:27:44.691  1629  1675 D BluetoothAdapterProperties: Setting state to 15
07-07 20:27:44.691  1629  1675 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-07 20:27:44.692  1629  1675 I BluetoothAdapterState: Entering BleOnState
07-07 20:27:44.692  1020  1136 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:44.692   454   496 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:44.692   454   496 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-07 20:27:44.692   727   753 D BluetoothPan: onBluetoothStateChange on: false
07-07 20:27:44.699   454   669 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-07 20:27:44.702   727   751 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:44.704   454  2279 D DhcpClient: Receive thread stopped
07-07 20:27:44.705   727   891 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:27:44.705   454   669 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-07 20:27:44.706   727   753 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:27:44.708  1629  1629 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-07 20:27:44.708  1629  1629 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-07 20:27:44.710   218   538 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:27:44.712  1629  1629 I BtOppRfcommListener: stopping Accept Thread
07-07 20:27:44.712  1629  2229 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-07 20:27:44.713   454   669 D DhcpClient: doQuit
,07-07 20:27:44.714   727   753 E BluetoothMap: 
07-07 20:27:44.714   727   753 E BluetoothMap: java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@64551aa
07-07 20:27:44.714   727   753 E BluetoothMap: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-07 20:27:44.714   727   753 E BluetoothMap: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-07 20:27:44.714   727   753 E BluetoothMap: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-07 20:27:44.714   727   753 E BluetoothMap: 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
07-07 20:27:44.714   727   753 E BluetoothMap: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
07-07 20:27:44.714   727   753 E BluetoothMap: 	at android.os.Binder.execTransact(Binder.java:453)
,07-07 20:27:44.714   727   891 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:27:44.714   454   496 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:44.715   454   671 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-07 20:27:44.716   727   753 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:27:44.719   454   496 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:27:44.719  1629  1675 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-07 20:27:44.719  1629  1675 D BluetoothAdapterProperties: Setting state to 16
07-07 20:27:44.719  1629  1675 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-07 20:27:44.720   454  2278 D DhcpClient: onQuitting
07-07 20:27:44.720  1629  2229 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-07 20:27:44.720   454   669 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-07 20:27:44.723  1629  1675 D BluetoothAdapterProperties: onBleDisable
07-07 20:27:44.725  1629  1679 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:27:44.726  1629  1676 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-07 20:27:44.726  1629  1675 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:44.728  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:44.728  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:44.728  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:44.728  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:44.728  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:44.728  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:44.728  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:44.728  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:44.728  1629  1782 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-07 20:27:44.728  1629  1782 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:44.729  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:44.732  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:44.732  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:44.732  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:44.732  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:44.732  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:44.732  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:44.732  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:44.732  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:44.732  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:44.797   218   538 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-07 20:27:44.820  1086  1086 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
07-07 20:27:44.825  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:44.825  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:44.825  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:44.825  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:44.825  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:44.825  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:44.825  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:44.825  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:44.826  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:44.826  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:44.826  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:44.826  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:44.826  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:44.826  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:44.826  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:44.826  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:44.826  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:44.827  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:44.843  1086  1086 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
07-07 20:27:44.847  1086  1086 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-07 20:27:44.868   218   538 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-07 20:27:44.869   454   671 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-07 20:27:44.869   454   671 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-07 20:27:44.870   454   496 D Tethering: MasterInitialState.processMessage what=3
07-07 20:27:44.874  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:44.875  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:44.875  1086  1086 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
07-07 20:27:44.886  1079  1079 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-07 20:27:44.890  1086  1086 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-07 20:27:44.934  1629  1782 W bt_btif : ag scb idx 1 not allocated
07-07 20:27:44.935  1629  1782 E bt_btif : BTA AG is already disabled, ignoring ...
07-07 20:27:44.939  1629  1679 I bt_hci  : shut_down
07-07 20:27:44.940  1629  1696 I bt_vendor: low_power_mode_cb
07-07 20:27:44.943  1629  1696 D bt_hwcfg: hw_epilog_process
07-07 20:27:44.944   218   538 E Netd    : netlink response contains error (No such file or directory)
07-07 20:27:44.959  2898  2898 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
07-07 20:27:44.962   454   671 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-07 20:27:44.962  1629  1696 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-07 20:27:44.962  1629  1696 I bt_vendor: epilog_cb
07-07 20:27:44.962  1629  1696 I bt_hci  : epilog_finished_callback
07-07 20:27:44.964  1629  1679 I bt_hci_h4: hal_close
07-07 20:27:44.965  1629  1679 I bt_userial_vendor: device fd = 49 close
07-07 20:27:45.000   454   669 D wifi    : In wifi stop Hal
07-07 20:27:45.000   454   669 D wifi    : halHandle = 0x559beed1c0, mVM = 0x559bb57c30, mCls = 0x100b16
07-07 20:27:45.001   454  1085 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-07 20:27:45.001   454  1085 D WifiHAL : Got a signal to exit!!!
07-07 20:27:45.001   454  1085 I WifiHAL : Exit wifi_event_loop
07-07 20:27:45.002   454   669 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 9
07-07 20:27:45.002   454   669 E WifiHAL : Event processing terminated
07-07 20:27:45.002   454   669 D wifi    : In wifi cleaned up handler
07-07 20:27:45.002   454   669 I WifiHAL : Internal cleanup completed
07-07 20:27:45.003  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:45.003  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:45.077  1962  1962 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-07 20:27:45.114   454  1085 D wifi    : set interface wlan0 flags (DOWN)
07-07 20:27:45.114   454   669 D WifiNative-HAL: HAL event thread stopped successfully
07-07 20:27:45.186  1629  1676 D bt_stack_manager: event_shut_down_stack finished.
07-07 20:27:45.186  1629  1675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-07 20:27:45.187  1629  1675 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-07 20:27:45.188  1629  1629 D BtGatt.DebugUtils: handleDebugAction() action=null
07-07 20:27:45.188  1629  1629 D BtGatt.GattService: Received stop request...Stopping profile...
07-07 20:27:45.188  1629  1629 D BtGatt.GattService: stop()
07-07 20:27:45.188  1629  1629 D BtGatt.AdvertiseManager: advertise clients cleared
07-07 20:27:45.189  1629  1629 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:45.189  1629  1629 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:45.189  1629  1629 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:45.189  1629  1629 V BluetoothAdapterState: isBleTurningOff()=true
07-07 20:27:45.190  1629  1675 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-07 20:27:45.190  1629  1675 D BluetoothAdapterProperties: Setting state to 10
07-07 20:27:45.190  1629  1675 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-07 20:27:45.191  1629  1675 I BluetoothAdapterState: Entering OffState
07-07 20:27:45.191   454   496 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-07 20:27:45.203  1059  1284 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-07 20:27:45.205  1629  1629 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-07 20:27:45.205  1629  1629 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-07 20:27:45.205  1629  1629 I BluetoothServiceJni: cleanupNative: return from cleanup
07-07 20:27:45.208  1629  1676 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-07 20:27:45.210  1629  1676 D bt_stack_manager: event_clean_up_stack finished.
07-07 20:27:45.217  1629  1629 I art     : System.exit called, status: 0
07-07 20:27:45.218  1629  1629 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-07 20:27:45.256   454  1160 I ActivityManager: Process com.android.bluetooth (pid 1629) has died
07-07 20:27:45.257   454  1160 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,07-07 20:27:45.290  2898  2898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:27:45.298   454   496 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@398b3bb:true
07-07 20:27:45.305   454   471 I ActivityManager: Start proc 2920:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,07-07 20:27:45.323  2898  2898 D LocalBluetoothProfileManager: Adding local MAP profile
,07-07 20:27:45.325  2898  2898 D BluetoothMap: Create BluetoothMap proxy object
,07-07 20:27:45.337  2898  2898 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,07-07 20:27:45.340  2898  2898 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-07 20:27:45.362  2898  2898 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:27:45.370   454   470 I ActivityManager: Killing 2567:com.google.process.gapps/u0a85 (adj 15): empty #17,
,07-07 20:27:45.415  2920  2920 D AdapterServiceConfig: Adding HeadsetService
,07-07 20:27:45.415  2920  2920 D AdapterServiceConfig: Adding A2dpService
07-07 20:27:45.415  2920  2920 D AdapterServiceConfig: Adding HidService
07-07 20:27:45.416  2920  2920 D AdapterServiceConfig: Adding HealthService
07-07 20:27:45.416  2920  2920 D AdapterServiceConfig: Adding PanService
07-07 20:27:45.416  2920  2920 D AdapterServiceConfig: Adding GattService
,07-07 20:27:45.422  1103  1103 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:27:45.436   454   496 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1970008:true
,07-07 20:27:45.438  2898  2898 D BluetoothPbap: Proxy object connected
,07-07 20:27:45.438  2898  2898 D PbapServerProfile: Bluetooth service connected
,07-07 20:27:45.442  2898  2898 D BluetoothPbap: Proxy object disconnected
07-07 20:27:45.442  2898  2898 D PbapServerProfile: Bluetooth service disconnected
,07-07 20:27:45.454   454  1160 I ActivityManager: Start proc 2935:com.google.android.apps.maps/u0a60 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-07 20:27:45.455   454  1160 I ActivityManager: Killing 1962:com.google.android.talk/u0a56 (adj 15): empty #17
,07-07 20:27:45.532  2935  2935 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,07-07 20:27:45.636  2935  2935 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.File.exists(File.java:361)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-07 20:27:45.636  2935  2935 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:27:45.636  2935  2935 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:27:45.636  2935  2935 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.e.b(PG:170)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:27:45.636  2935  2935 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.k.d(PG:583)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.e.b(PG:170)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:27:45.636  2935  2935 D StrictMode: StrictMode policy violation; ~duration=37 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.io.File.exists(File.java:361)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:27:45.636  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:27:45.637  2935  2935 D StrictMode: StrictMode policy violation; ~duration=37 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:27:45.637  2935  2935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at java.io.File.exists(File.java:361)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:27:45.637  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:27:45.640  2935  2935 D StrictMode: StrictMode policy violation; ~duration=36 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:27:45.640  2935  2935 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:27:45.640  2935  2935 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:27:45.653   454  1160 I ActivityManager: Start proc 2958:com.google.android.talk/u0a56 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
07-07 20:27:45.654   454  1160 I ActivityManager: Killing 1646:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-07 20:27:45.721  2958  2958 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-07 20:27:45.867  2958  2976 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-07 20:27:45.867  2958  2976 I Babel_SMS: MmsConfig.loadMmsSettings
07-07 20:27:45.868  2958  2976 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=, mUaProfUrl=
07-07 20:27:45.868  2958  2976 I Babel_SMS: MmsConfig.loadFromDatabase
,07-07 20:27:45.906  2958  2958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:27:45.920  2958  2958 I Babel_Crash: startup - clean
,07-07 20:27:45.923  2958  2976 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-07 20:27:45.924  2958  2976 I Babel_SMS: MmsConfig.loadFromResources
,07-07 20:27:45.927  2958  2976 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-07 20:27:45.933  2958  2976 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Hangouts/4.1.102314611, mUaProfUrl=https://ssl.gstatic.com/android/hangouts/hangouts_mms_ua_profile.xml
,07-07 20:27:45.949  2898  2898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:27:45.955  1103  1103 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:27:45.977  2898  2898 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:27:46.075  2958  2958 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-07 20:27:46.096  2958  2958 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-07 20:27:46.103  2958  2958 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-07 20:27:46.108  2958  2958 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-07 20:27:46.110  2958  2958 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-07 20:27:46.136  1224  1224 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-07 20:27:46.141  1224  2300 I iu.UploadsManager: num queued entries: 0
,07-07 20:27:46.141  1224  2300 I iu.UploadsManager: num updated entries: 0
07-07 20:27:46.142  1224  2300 I iu.SyncManager: NEXT; no task
,07-07 20:27:46.146  1224  1224 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-07 20:27:46.147  1224  1224 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-07 20:27:46.158   454  1076 I ActivityManager: Start proc 2982:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-07 20:27:46.167  2958  2958 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-07 20:27:46.210  2958  2958 I vclib   : onServiceConnected
,07-07 20:27:46.352   454   471 I ActivityManager: Start proc 2998:com.google.android.apps.magazines/u0a62 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-07 20:27:46.388  2958  3003 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,07-07 20:27:46.432  2998  2998 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm64
,07-07 20:27:46.468   454  1152 I ActivityManager: Killing 2495:android.process.acore/u0a3 (adj 15): empty #17
,07-07 20:27:46.483  2935  2954 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-07 20:27:46.503   454   496 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cfdad6f:true
,07-07 20:27:46.564  2998  2998 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-07 20:27:46.564  2998  2998 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-07 20:27:46.564  2998  2998 I GAv4    :   adb logcat -s GAv4
,07-07 20:27:46.576  2998  2998 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:27:46.584  2998  2998 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:27:46.602  2998  3016 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:27:46.700  2998  2998 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-07 20:27:46.737  2998  2998 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm64
,07-07 20:27:46.744  2998  2998 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1723-1726)
,07-07 20:27:46.744  2998  2998 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 20:27:46.755  2998  2998 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {57cd9c8}
,07-07 20:27:46.757  2998  2998 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 20:27:46.758  2998  2998 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-07 20:27:46.761  2998  2998 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-07 20:27:46.773  2998  2998 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 20:27:46.823  2998  2998 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-07 20:27:46.828  2998  2998 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-07 20:27:46.829  2998  2998 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-07 20:27:46.927  2998  3045 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-07 20:27:46.941  2998  2998 I NSApplication: Starting up...
,07-07 20:27:46.954   454  1152 I ActivityManager: Start proc 3050:com.google.android.apps.photos/u0a66 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-07 20:27:46.955   454  1152 I ActivityManager: Killing 2622:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-07 20:27:47.002  3050  3050 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-07 20:27:47.093   454  1044 I ActivityManager: Killing 2674:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-07 20:27:47.640   454   471 D WifiService: setWifiEnabled: true pid=2815, uid=10000
07-07 20:27:47.640   454   471 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:27:47.642   218   538 D SoftapController: Softap fwReload - Ok
07-07 20:27:47.642   218   538 D CommandListener: Setting iface cfg
07-07 20:27:47.642   218   538 D CommandListener: Trying to bring down wlan0
07-07 20:27:47.643   218   538 D CommandListener: Clearing all IP addresses on wlan0
07-07 20:27:47.644   454   669 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-07 20:27:48.238   454   669 D wifi    : set interface wlan0 flags (UP)
07-07 20:27:48.239   454   669 I WifiHAL : Initializing wifi
07-07 20:27:48.239   454   669 I WifiHAL : Creating socket
07-07 20:27:48.242   454   669 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-07 20:27:48.242   454   669 D wifi    : Did set static halHandle = 0x559bfac720
07-07 20:27:48.243   454   669 D wifi    : halHandle = 0x559bfac720, mVM = 0x559bb57c30, mCls = 0x2012b2
07-07 20:27:48.243   454   669 D wifi    : array field set
07-07 20:27:48.243   454   669 I WifiNative-HAL: interface[0] = wlan0
07-07 20:27:48.247   454   669 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-07 20:27:48.247  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:48.247  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:48.248   454   669 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-07 20:27:48.249   454  3068 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=367689123616
07-07 20:27:48.249   454  3068 D wifi    : waitForHalEvents called, vm = 0x559bb57c30, obj = 0x2012b2, env = 0x559c046480
07-07 20:27:48.295  3069  3069 I wpa_supplicant: Successfully initialized wpa_supplicant
07-07 20:27:48.337  3069  3069 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-07 20:27:48.379  3069  3069 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-07 20:27:48.379  3069  3069 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,07-07 20:27:48.725  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:27:48.728  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:27:48.729  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-07 20:27:48.739  1103  1122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-07 20:27:48.739  1103  1122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-07 20:27:48.739  1103  1122 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:27:48.739  1103  1122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:27:48.785  2516  2516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-07 20:27:48.785  2516  2516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-07 20:27:48.785  2516  2516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-07 20:27:49.252  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:49.252  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:49.252  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:49.252  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:49.252  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:49.252  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:49.252  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:49.252  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:49.252  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:49.253  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:49.253  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:49.253  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:49.253  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:49.253  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:49.253  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:49.253  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:49.253  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:49.253  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:49.253   454   669 D WifiConfigStore: Loading config and enabling all networks 
07-07 20:27:49.259   454   669 D WifiConfigStore: loaded 0 passpoint configs
07-07 20:27:49.261   454   669 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-07 20:27:49.261   454   669 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-07 20:27:49.262   454   669 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-07 20:27:49.262   454   669 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-07 20:27:49.262   454   669 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-07 20:27:49.262   454   669 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-07 20:27:49.264   454   669 D WifiNative-HAL: Setting external_sim to 1
07-07 20:27:49.265   454   669 D wifi    : setting dfs flag to true, 0x559be38400
07-07 20:27:49.265   454   669 D WifiStateMachine: Setting OUI to DA-A1-19
,07-07 20:27:49.265   454   669 D wifi    : setting scan oui 0x559be38400
,07-07 20:27:49.265   454   669 D WifiHAL : Sending mac address OUI
07-07 20:27:49.267  2958  2958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:27:49.274   454   669 E native  : do suspend false
,07-07 20:27:49.283   218   538 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
07-07 20:27:49.283   454   454 D RttService: SCAN_AVAILABLE : 3
07-07 20:27:49.283   454   685 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-07 20:27:49.285   454   669 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-07 20:27:49.286   218   538 D CommandListener: Setting iface cfg
07-07 20:27:49.286   454   668 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '60 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 60 Failed to set address (No such device)'
07-07 20:27:49.286   454   668 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-07 20:27:49.290   454   668 D WifiNative-HAL: p2pGetDeviceAddress
,07-07 20:27:49.290   454   668 D WifiNative-HAL: p2pGetDeviceAddress returning 52:2e:5c:e5:0c:a7
,07-07 20:27:49.294   454   669 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:27:49.323   454   487 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=134306 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=28 mControllerEnergyUsed=106 }
,07-07 20:27:49.676  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-07 20:27:49.676  2815  2865 I jxcore-log: 
,07-07 20:27:49.871  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-07 20:27:49.871  2815  2865 I jxcore-log: 
,07-07 20:27:49.974  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-07 20:27:49.974  2815  2865 I jxcore-log: 
,07-07 20:27:49.977  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-07 20:27:49.977  2815  2865 I jxcore-log: 
,07-07 20:27:49.985  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-07 20:27:49.985  2815  2865 I jxcore-log: 
,07-07 20:27:49.988  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-07 20:27:49.988  2815  2865 I jxcore-log: 
,07-07 20:27:50.641   454  1162 D WifiService: setWifiEnabled: false pid=2815, uid=10000
,07-07 20:27:50.642   454  1162 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:27:50.644   454   669 D WifiConfigStore: Retrieve network priorities after PNO.
07-07 20:27:50.645   454   454 D RttService: SCAN_AVAILABLE : 1
07-07 20:27:50.645   454   685 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-07 20:27:50.656   454   669 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-07 20:27:50.656   218   538 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:27:50.661   454   669 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-07 20:27:50.661  3069  3069 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:50.664  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:50.664  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:50.664  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:50.679  3069  3069 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,07-07 20:27:50.707  3069  3069 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-07 20:27:50.720  3069  3069 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-07 20:27:50.724   454   669 D wifi    : In wifi stop Hal
,07-07 20:27:50.724   454   669 D wifi    : halHandle = 0x559bfac720, mVM = 0x559bb57c30, mCls = 0x2012b2
,07-07 20:27:50.725   454  3068 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,07-07 20:27:50.725   454  3068 D WifiHAL : Got a signal to exit!!!
,07-07 20:27:50.725   454  3068 I WifiHAL : Exit wifi_event_loop
,07-07 20:27:50.726  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:50.727  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:50.729   454   669 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 9
07-07 20:27:50.729   454   669 E WifiHAL : Event processing terminated
07-07 20:27:50.730   454   669 D wifi    : In wifi cleaned up handler
07-07 20:27:50.730   454   669 I WifiHAL : Internal cleanup completed
,07-07 20:27:50.739  1059  1284 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:27:50.805  2958  2958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:27:50.806  2958  2958 I art     : Waiting for a blocking GC DisableMovingGc
,07-07 20:27:50.807  2958  2958 I art     : Starting a blocking GC DisableMovingGc
,07-07 20:27:50.837   454  3068 D wifi    : set interface wlan0 flags (DOWN)
,07-07 20:27:50.837   454   669 D WifiNative-HAL: HAL event thread stopped successfully
,07-07 20:27:51.495   454  1160 I ActivityManager: Killing 2692:com.android.musicfx/u0a14 (adj 15): empty #17
,07-07 20:27:52.098  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-07 20:27:52.098  2815  2865 I jxcore-log: 
,07-07 20:27:52.105  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-07 20:27:52.105  2815  2865 I jxcore-log: 
,07-07 20:27:52.111  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-07 20:27:52.111  2815  2865 I jxcore-log: 
,07-07 20:27:52.191  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-07 20:27:52.191  2815  2865 I jxcore-log: 
,07-07 20:27:52.231  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-07 20:27:52.231  2815  2865 I jxcore-log: 
,07-07 20:27:52.259  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-07 20:27:52.259  2815  2865 I jxcore-log: 
,07-07 20:27:52.265  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-07 20:27:52.265  2815  2865 I jxcore-log: 
,07-07 20:27:52.361  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-07 20:27:52.361  2815  2865 I jxcore-log: 
,07-07 20:27:52.374  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-07 20:27:52.374  2815  2865 I jxcore-log: 
,07-07 20:27:52.378  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-07 20:27:52.378  2815  2865 I jxcore-log: 
,07-07 20:27:52.382  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-07 20:27:52.382  2815  2865 I jxcore-log: 
,07-07 20:27:52.391  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-07 20:27:52.391  2815  2865 I jxcore-log: 
,07-07 20:27:52.402  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-07 20:27:52.402  2815  2865 I jxcore-log: 
,07-07 20:27:52.446  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-07 20:27:52.446  2815  2865 I jxcore-log: 
,07-07 20:27:52.450  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-07 20:27:52.450  2815  2865 I jxcore-log: 
,07-07 20:27:52.555  2815  2865 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-07 20:27:52.555  2815  2865 I jxcore-log: 
,07-07 20:27:52.561  2815  2865 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-07 20:27:52.562  2815  2865 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-07 20:27:52.562  2815  2865 I jxcore-log: 
,07-07 20:27:52.601  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:27:52.601  2815  2865 I jxcore-log: 
,07-07 20:27:52.601  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:27:52.601  2815  2865 I jxcore-log: 
07-07 20:27:52.602  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:27:52.602  2815  2865 I jxcore-log: 
07-07 20:27:52.603  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:27:52.603  2815  2865 I jxcore-log: 
,07-07 20:27:52.604  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:52.604  2815  2865 I jxcore-log: 
,07-07 20:27:52.604  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:52.604  2815  2865 I jxcore-log: 
07-07 20:27:52.605  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:27:52.605  2815  2865 I jxcore-log: 
07-07 20:27:52.605  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:27:52.605  2815  2865 I jxcore-log: 
07-07 20:27:52.605  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:52.605  2815  2865 I jxcore-log: 
07-07 20:27:52.606  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:52.606  2815  2865 I jxcore-log: 
,07-07 20:27:53.691  2920  2920 D BluetoothAdapterState: make() - Creating AdapterState
,07-07 20:27:53.698  2920  2920 I bt_bluedroid: init
,07-07 20:27:53.698  2920  3082 I BluetoothAdapterState: Entering OffState
,07-07 20:27:53.703  2920  3083 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-07 20:27:53.703  2920  3083 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-07 20:27:53.704  2920  3083 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-07 20:27:53.704  2920  3083 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-07 20:27:53.708  2920  2920 I bt_bluedroid: get_profile_interface socket
07-07 20:27:53.712  2920  2920 I bt_bluedroid: get_profile_interface sdp
,07-07 20:27:53.713  2920  3086 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
07-07 20:27:53.715  2920  3086 D BluetoothAdapterProperties: Name is: Nexus 9
07-07 20:27:53.717  2920  2930 I bt_bluedroid: config_hci_snoop_log
07-07 20:27:53.719   454   496 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
07-07 20:27:53.723  2920  3082 D BluetoothAdapterState: Current state: OFF, message: 0
07-07 20:27:53.724  2920  3082 D BluetoothAdapterProperties: Setting state to 14
07-07 20:27:53.724  2920  3082 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-07 20:27:53.726  2920  3082 D BluetoothBondStateMachine: make
,07-07 20:27:53.730  2920  3087 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-07 20:27:53.736  2920  2920 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-07 20:27:53.738  2920  2920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b16ec0
,07-07 20:27:53.740  2920  3082 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:53.740  2920  2920 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-07 20:27:53.742  2920  2920 D BtGatt.GattService: Received start request. Starting profile...
,07-07 20:27:53.742  2920  2920 D BtGatt.GattService: start()
07-07 20:27:53.742  2920  2920 I bt_bluedroid: get_profile_interface gatt
07-07 20:27:53.744  2920  2920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b16ec0
,07-07 20:27:53.744  2920  2920 D BtGatt.AdvertiseManager: advertise manager created
,07-07 20:27:53.754  2920  2920 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:27:53.754  2920  2920 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:53.754  2920  2920 V BluetoothAdapterState: isBleTurningOn()=true
07-07 20:27:53.754  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:53.755  2920  3082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-07 20:27:53.755  2920  3082 I bt_bluedroid: enable
,07-07 20:27:53.755  2920  3083 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-07 20:27:53.756  2920  3083 I bt_hci  : start_up
,07-07 20:27:53.765  2920  3083 I bt_vendor: alloc value 0xf3da0889
07-07 20:27:53.765  2920  3083 I bt_vendor: init
07-07 20:27:53.765  2920  3083 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-07 20:27:53.967  2920  3083 D bt_hci  : start_up starting async portion
,07-07 20:27:53.967  2920  3090 I bt_hci  : event_finish_startup
07-07 20:27:53.967  2920  3090 I bt_hci_h4: hal_open
07-07 20:27:53.967  2920  3090 I bt_userial_vendor: userial vendor open: opening /dev/ttyTHS2
07-07 20:27:53.968  2920  3090 I bt_userial_vendor: device fd = 49 open
,07-07 20:27:53.978  2920  3090 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-07 20:27:54.014  2920  3090 D bt_hwcfg: Chipset BCM4350C0
,07-07 20:27:54.014  2920  3090 D bt_hwcfg: Target name = [BCM4350C0]
07-07 20:27:54.014  2920  3090 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4350c0.hcd
,07-07 20:27:54.605  2920  3090 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-07 20:27:54.606  2920  3090 D bt_hwcfg: Settlement delay -- 100 ms
07-07 20:27:54.606  2920  3090 I bt_hwcfg: Setting fw settlement delay to 100 
,07-07 20:27:54.714  2920  3090 I bt_hwcfg: bt vendor lib: set UART baud 3000000
07-07 20:27:54.714  2920  3090 I bt_hwcfg: Setting local bd addr to B4:CE:F6:34:3D:CC
,07-07 20:27:54.750  2920  3090 I bt_hwcfg: vendor lib fwcfg completed
,07-07 20:27:54.751  2920  3090 I bt_vendor: firmware callback
,07-07 20:27:54.751  2920  3090 I bt_hci  : firmware_config_callback
,07-07 20:27:54.761  2920  3092 I bt_btu  : btu_task pending for preload complete event
,07-07 20:27:54.761  2920  3092 I bt_btu_task: Bluetooth chip preload is complete
07-07 20:27:54.761  2920  3092 I bt_btu  : btu_task received preload complete event
,07-07 20:27:54.772  2920  3092 I         : BTE_InitTraceLevels -- TRC_HCI
,07-07 20:27:54.773  2920  3092 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-07 20:27:54.773  2920  3092 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-07 20:27:54.773  2920  3092 I         : BTE_InitTraceLevels -- TRC_AVDT
07-07 20:27:54.773  2920  3092 I         : BTE_InitTraceLevels -- TRC_AVRC
07-07 20:27:54.773  2920  3092 I         : BTE_InitTraceLevels -- TRC_A2D
07-07 20:27:54.774  2920  3092 I         : BTE_InitTraceLevels -- TRC_BNEP
07-07 20:27:54.774  2920  3092 I         : BTE_InitTraceLevels -- TRC_BTM
07-07 20:27:54.774  2920  3092 I         : BTE_InitTraceLevels -- TRC_GAP
07-07 20:27:54.774  2920  3092 I         : BTE_InitTraceLevels -- TRC_PAN
07-07 20:27:54.774  2920  3092 I         : BTE_InitTraceLevels -- TRC_SDP
,07-07 20:27:54.774  2920  3092 I         : BTE_InitTraceLevels -- TRC_GATT
,07-07 20:27:54.775  2920  3092 I         : BTE_InitTraceLevels -- TRC_SMP
,07-07 20:27:54.775  2920  3092 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-07 20:27:54.784  2920  3092 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-07 20:27:55.006  2920  3092 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d1ea31
,07-07 20:27:55.006  2920  3092 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d1ea31 
,07-07 20:27:55.016  2920  3086 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false
,07-07 20:27:55.020  2920  3086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-07 20:27:55.021  2920  3086 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
07-07 20:27:55.026  2920  3086 D BluetoothAdapterProperties: Name is: Nexus 9
,07-07 20:27:55.033  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:55.037  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:55.037  2920  3086 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:27:55.038  2920  3086 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:27:55.038  2920  3086 D bt_hci  : do_postload posting postload work item
07-07 20:27:55.039  2920  3090 I bt_hci  : event_postload
07-07 20:27:55.039  2920  3090 I bt_vendor: sco_config_cb
07-07 20:27:55.039  2920  3090 I bt_hci  : sco_config_callback postload finished.
07-07 20:27:55.043  2920  3086 D bt_bte_conf: Device ID record 1 : primary
07-07 20:27:55.044  2920  3086 D bt_bte_conf:   vendorId            = 000f
07-07 20:27:55.044  2920  3086 D bt_bte_conf:   vendorIdSource      = 0001
,07-07 20:27:55.044  2920  3086 D bt_bte_conf:   product             = 1200
,07-07 20:27:55.044  2920  3086 D bt_bte_conf:   version             = 1436
07-07 20:27:55.044  2920  3086 D bt_bte_conf:   clientExecutableURL = 
07-07 20:27:55.044  2920  3086 D bt_bte_conf:   serviceDescription  = 
,07-07 20:27:55.044  2920  3086 D bt_bte_conf:   documentationURL    = 
07-07 20:27:55.044  2920  3086 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-07 20:27:55.045  2920  3083 D bt_stack_manager: event_start_up_stack finished
07-07 20:27:55.046  2920  3082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-07 20:27:55.046  2920  3082 D BluetoothAdapterProperties: Setting state to 15
07-07 20:27:55.047  2920  3082 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-07 20:27:55.051  2920  3090 I bt_vendor: low_power_mode_cb
07-07 20:27:55.051  2920  3082 I BluetoothAdapterState: Entering BleOnState
,07-07 20:27:55.058  2920  3082 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-07 20:27:55.058  2920  3082 D BluetoothAdapterProperties: Setting state to 11
07-07 20:27:55.059  2920  3082 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-07 20:27:55.075  2920  2920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b16ec0
07-07 20:27:55.079  2920  2920 D HeadsetService: Received start request. Starting profile...
07-07 20:27:55.086  2920  2920 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-07 20:27:55.087  2920  2920 D HeadsetStateMachine: make
07-07 20:27:55.095  2920  3082 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:55.116  2920  2920 D HeadsetStateMachine: max_hf_connections = 1
07-07 20:27:55.118  2920  2920 I bt_bluedroid: get_profile_interface handsfree
07-07 20:27:55.118  2920  3086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-07 20:27:55.119  2920  3086 E bt_btif : btif_hf_upstreams_evt: Invalid index 9316
,07-07 20:27:55.124  2920  2920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b16ec0
,07-07 20:27:55.125  2920  2920 D A2dpService: Received start request. Starting profile...
07-07 20:27:55.125  2920  2920 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-07 20:27:55.125  2920  2920 I bt_bluedroid: get_profile_interface avrcp
,07-07 20:27:55.133  2920  2920 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-07 20:27:55.133  2920  2920 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-07 20:27:55.134  2920  2920 D A2dpStateMachine: make
,07-07 20:27:55.135  2920  2920 I bt_bluedroid: get_profile_interface a2dp
,07-07 20:27:55.140  2920  3086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000028
,07-07 20:27:55.141  2920  3101 D A2dpStateMachine: Enter Disconnected: -2
07-07 20:27:55.141  2920  2920 I BluetoothHidServiceJni: classInitNative: succeeds
,07-07 20:27:55.142  2920  2920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b16ec0
07-07 20:27:55.144  2920  2920 D HidService: Received start request. Starting profile...
07-07 20:27:55.144  2920  2920 I bt_bluedroid: get_profile_interface hidhost
,07-07 20:27:55.145  2920  2920 D HidService: setHidService(): set to: null
07-07 20:27:55.145  2920  2920 I BluetoothHealthServiceJni: classInitNative: succeeds
07-07 20:27:55.146  2920  2920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b16ec0
,07-07 20:27:55.146  2920  3086 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d00099
07-07 20:27:55.147  2920  3086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
07-07 20:27:55.147  2920  2920 D HealthService: Received start request. Starting profile...
,07-07 20:27:55.144  2898  2898 D BluetoothInputDevice: Proxy object connected
,07-07 20:27:55.149  2920  2920 I bt_bluedroid: get_profile_interface health
,07-07 20:27:55.149  2898  2898 D HidProfile: Bluetooth service connected
07-07 20:27:55.150  2920  2920 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-07 20:27:55.150  2920  2920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b16ec0
,07-07 20:27:55.152  2898  2898 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:27:55.152  2920  2920 D PanService: Received start request. Starting profile...
07-07 20:27:55.153  2920  2920 D BluetoothPanServiceJni: initializeNative(L110): pan
07-07 20:27:55.153  2920  2920 I bt_bluedroid: get_profile_interface pan
07-07 20:27:55.153  2920  3086 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-07 20:27:55.160  1103  1103 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-07 20:27:55.161  2920  2920 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:55.161  2920  2920 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:55.161  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:55.161  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:55.164  2920  3098 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-07 20:27:55.163  2920  2920 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:55.164  2920  2920 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:55.164  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:55.164  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:55.164  2920  2920 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:55.164  2920  2920 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:55.164  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:55.164  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:55.165  2920  2920 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:55.165  2920  2920 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:55.165  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:55.165  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:55.165  2920  2920 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:55.165  2920  2920 V BluetoothAdapterState: isTurningOn()=true
07-07 20:27:55.165  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:55.165  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:55.165  2920  3082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-07 20:27:55.165  2920  3082 D BluetoothAdapterProperties: ScanMode =  20
07-07 20:27:55.165  2920  3082 D BluetoothAdapterProperties: State =  11
07-07 20:27:55.166  2920  3082 D BluetoothAdapterProperties: Setting state to 12
07-07 20:27:55.166  2920  3082 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-07 20:27:55.166  1020  1046 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:55.171  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:55.171  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:55.171  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:55.171  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:55.171  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:55.171  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:55.171  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:55.171  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:55.172   454   496 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:55.172  2898  2914 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:27:55.173  2815  2815 D io.jxcore.node.JXcoreExtension: notify,NetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:55.175  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:27:55.175  2815  2865 I jxcore-log: 
07-07 20:27:55.178  2920  3086 D BluetoothAdapterProperties: Scan Mode:21
07-07 20:27:55.178  2920  3086 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:27:55.179  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:55.179  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:55.179  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:55.179  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:55.179  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:55.179  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:55.179  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:55.179  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:55.179  2898  2913 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:27:55.180  2898  2913 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-07 20:27:55.180  2920  3082 I BluetoothAdapterState: Entering OnState
07-07 20:27:55.180   454   496 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:55.180  2898  2914 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:27:55.180   727   891 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:27:55.181  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:55.182   727   727 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:27:55.182   727   727 D PanProfile: Bluetooth service connected
07-07 20:27:55.183  2898  2898 D PanProfile: Bluetooth service connected
07-07 20:27:55.184  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:27:55.184  2815  2865 I jxcore-log: 
07-07 20:27:55.185  2898  2913 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:27:55.185   727   753 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:55.186   727   751 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:27:55.188   727   891 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:27:55.189   727   891 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-07 20:27:55.189   727   753 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:27:55.190   454   496 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:27:55.190   727   751 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:27:55.190   727   727 D BluetoothA2dp: Proxy object connected
07-07 20:27:55.192   454   496 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:27:55.192   727   727 D BluetoothInputDevice: Proxy object connected
07-07 20:27:55.192   727   727 D HidProfile: Bluetooth service connected
07-07 20:27:55.192   454   454 D BluetoothA2dp: Proxy object connected
07-07 20:27:55.194   454   454 I Telecom : BluetoothPhoneService: queryPhoneState
07-07 20:27:55.196  2898  2898 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-07 20:27:55.201  2898  2898 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-07 20:27:55.206  2898  2898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:27:55.217  2898  2898 D BluetoothA2dp: Proxy object connected
,07-07 20:27:55.218  1103  1103 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-07 20:27:55.219   727   727 D BluetoothPbap: Proxy object connected
,07-07 20:27:55.219   727   727 D PbapServerProfile: Bluetooth service connected
,07-07 20:27:55.228  2920  3106 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:27:55.251  2920  3113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:27:55.252  2920  3113 I BtOppRfcommListener: Accept thread started.
07-07 20:27:55.252  2898  2898 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:27:55.253  2898  2898 D BluetoothPbap: Proxy object connected
,07-07 20:27:55.253  2898  2898 D PbapServerProfile: Bluetooth service connected
,07-07 20:27:55.269   454   454 D BluetoothHeadset: Proxy object connected
,07-07 20:27:55.269   727   751 D BluetoothHeadset: Proxy object connected
07-07 20:27:55.269   727   727 D HeadsetProfile: Bluetooth service connected
07-07 20:27:55.269   454   454 D BluetoothHeadset: Proxy object connected
,07-07 20:27:55.269   454   454 D BluetoothHeadset: Proxy object connected
07-07 20:27:55.269  1020  1136 D BluetoothHeadset: Proxy object connected
,07-07 20:27:55.272   454   496 D BluetoothHeadset: Proxy object connected
,07-07 20:27:55.280   454   496 D BluetoothHeadset: Proxy object connected
,07-07 20:27:55.287   727   891 D BluetoothHeadset: Proxy object connected
07-07 20:27:55.287   727   727 D HeadsetProfile: Bluetooth service connected
,07-07 20:27:55.290   454   496 D BluetoothHeadset: Proxy object connected
,07-07 20:27:55.303  2898  2914 D BluetoothHeadset: Proxy object connected
07-07 20:27:55.304  2898  2898 D HeadsetProfile: Bluetooth service connected
,07-07 20:27:56.649  2920  3082 D BluetoothAdapterState: Current state: ON, message: 23
,07-07 20:27:56.649  2920  3082 D BluetoothAdapterProperties: Setting state to 13
07-07 20:27:56.649  2920  3082 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-07 20:27:56.650  2920  3082 D BluetoothAdapterProperties: onBluetoothDisable()
07-07 20:27:56.651  2920  3082 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:56.655  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:56.655  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:56.655  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:56.655  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:56.655  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:56.655  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:56.655  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:56.655  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:27:56.655  2920  3086 D BluetoothAdapterProperties: Scan Mode:20
,07-07 20:27:56.656  2920  2920 I BtOppRfcommListener: stopping Accept Thread
,07-07 20:27:56.656  2920  3113 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-07 20:27:56.656  2920  3113 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-07 20:27:56.657  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:27:56.658  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:56.658  2815  2865 I jxcore-log: 
,07-07 20:27:56.660  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:27:56.660  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:56.660  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:56.660  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:27:56.660  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:27:56.660  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:27:56.660  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:27:56.660  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:27:56.661  2920  3082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-07 20:27:56.661  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:27:56.662  2920  2920 D HeadsetService: Received stop request...Stopping profile...
07-07 20:27:56.662  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:27:56.662  2815  2865 I jxcore-log: 
07-07 20:27:56.664  2898  2914 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:56.664   454   454 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:56.665   727   751 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:56.665  2920  2920 D A2dpService: Received stop request...Stopping profile...
,07-07 20:27:56.666  2920  3101 D A2dpStateMachine: Exit Disconnected: -1
07-07 20:27:56.667  2920  2920 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:56.668  2920  2920 V BluetoothAdapterState: isTurningOn()=false
,07-07 20:27:56.668  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:56.668  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:56.668  2920  2920 D HidService: Received stop request...Stopping profile...
07-07 20:27:56.668  2920  2920 D HidService: Stopping Bluetooth HidService
07-07 20:27:56.672  2898  2898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:27:56.672  2920  2920 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-07 20:27:56.672  2920  2920 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-07 20:27:56.672  2920  3092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:56.673  2920  3092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:56.673  2920  3086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
,07-07 20:27:56.674  2920  3086 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-07 20:27:56.674  2920  2920 D HealthService: Received stop request...Stopping profile...
,07-07 20:27:56.675  2920  2920 V BluetoothAdapterState: isTurningOff()=true
,07-07 20:27:56.675  2920  2920 V BluetoothAdapterState: isTurningOn()=false
,07-07 20:27:56.675  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:56.675  2898  2898 D HeadsetProfile: Bluetooth service disconnected
07-07 20:27:56.676  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:56.676  2898  2898 D BluetoothA2dp: Proxy object disconnected
,07-07 20:27:56.677  2898  2898 D BluetoothInputDevice: Proxy object disconnected
,07-07 20:27:56.677  2898  2898 D HidProfile: Bluetooth service disconnected
07-07 20:27:56.678   454   454 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:56.678   454   454 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:56.679  1020  1055 D BluetoothHeadset: Proxy object disconnected
07-07 20:27:56.679   454   454 D BluetoothA2dp: Proxy object disconnected
,07-07 20:27:56.679  2920  3086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100020
07-07 20:27:56.680  2920  3092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:56.680  2920  3092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:56.680  2920  3092 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:27:56.680  2920  3092 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-07 20:27:56.680  2920  3092 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:27:56.680  2920  3092 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-07 20:27:56.685   727   727 D HeadsetProfile: Bluetooth service disconnected
07-07 20:27:56.686   727   727 D BluetoothA2dp: Proxy object disconnected
07-07 20:27:56.686   727   727 D BluetoothInputDevice: Proxy object disconnected
07-07 20:27:56.686   727   727 D HidProfile: Bluetooth service disconnected
07-07 20:27:56.687  2920  2920 D PanService: Received stop request...Stopping profile...
07-07 20:27:56.688  2920  2920 V BluetoothAdapterState: isTurningOff()=true
,07-07 20:27:56.688  2920  2920 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:56.688  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:56.688  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:56.688  2920  2920 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-07 20:27:56.688  2920  2920 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-07 20:27:56.688  2920  2920 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:56.688  2920  2920 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:56.688  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:27:56.689  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:56.689  2920  2920 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-07 20:27:56.688  2920  3086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-07 20:27:56.689  2920  3086 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,07-07 20:27:56.689  2920  2920 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-07 20:27:56.691  2920  2920 V BluetoothAdapterState: isTurningOff()=true
07-07 20:27:56.691  2920  2920 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:56.691  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:56.691  2920  2920 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:56.691  2920  2920 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-07 20:27:56.691  2920  2920 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-07 20:27:56.697  2920  3082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,07-07 20:27:56.697  2920  3082 D BluetoothAdapterProperties: Setting state to 15
07-07 20:27:56.697  2920  3082 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-07 20:27:56.698  2920  3082 I BluetoothAdapterState: Entering BleOnState
07-07 20:27:56.700  1103  1103 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-07 20:27:56.701  2898  2913 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:27:56.702  1020  1046 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-07 20:27:56.702   454   496 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-07 20:27:56.702  2898  2914 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:27:56.704  2898  2913 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:27:56.704  2898  2913 E BluetoothMap: 
07-07 20:27:56.704  2898  2913 E BluetoothMap: java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@19eb6ec
07-07 20:27:56.704  2898  2913 E BluetoothMap: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-07 20:27:56.704  2898  2913 E BluetoothMap: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-07 20:27:56.704  2898  2913 E BluetoothMap: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-07 20:27:56.704  2898  2913 E BluetoothMap: 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
07-07 20:27:56.704  2898  2913 E BluetoothMap: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
07-07 20:27:56.704  2898  2913 E BluetoothMap: 	at android.os.Binder.execTransact(Binder.java:453)
07-07 20:27:56.705   454   496 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:56.705  2898  2914 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:27:56.706   727   753 D BluetoothPan: onBluetoothStateChange on: false
07-07 20:27:56.706  2898  2913 D BluetoothPan: onBluetoothStateChange on: false
07-07 20:27:56.707   727   751 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:56.707   727  3117 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:27:56.707  2898  2914 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-07 20:27:56.707   727   891 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:27:56.708   727   891 E BluetoothMap: 
07-07 20:27:56.708   727   891 E BluetoothMap: java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@64551aa
07-07 20:27:56.708   727   891 E BluetoothMap: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-07 20:27:56.708   727   891 E BluetoothMap: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-07 20:27:56.708   727   891 E BluetoothMap: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-07 20:27:56.708   727   891 E BluetoothMap: 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
07-07 20:27:56.708   727   891 E BluetoothMap: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
07-07 20:27:56.708   727   891 E BluetoothMap: 	at android.os.Binder.execTransact(Binder.java:453)
07-07 20:27:56.709   727   751 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:27:56.709   454   496 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:27:56.709   727  3117 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:27:56.709   454   496 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:27:56.710  2920  3082 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-07 20:27:56.710  2920  3082 D BluetoothAdapterProperties: Setting state to 16
07-07 20:27:56.710  2920  3082 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-07 20:27:56.711  2920  3082 D BluetoothAdapterProperties: onBleDisable
07-07 20:27:56.711  2920  3082 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:56.711  2920  3083 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-07 20:27:56.714  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:56.714  2920  3086 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:27:56.715  2920  3092 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,07-07 20:27:56.715  2920  3092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:27:56.715  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:56.724  2898  2898 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:27:56.728  2898  2898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:27:56.734  1103  1103 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:27:56.735  2898  2898 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:27:56.915  2920  3092 W bt_btif : ag scb idx 1 not allocated
,07-07 20:27:56.915  2920  3092 E bt_btif : BTA AG is already disabled, ignoring ...
07-07 20:27:56.915  2920  3086 I bt_hci  : shut_down
,07-07 20:27:56.922  2920  3090 I bt_vendor: low_power_mode_cb
,07-07 20:27:56.924  2920  3090 D bt_hwcfg: hw_epilog_process
,07-07 20:27:56.940  2920  3090 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-07 20:27:56.940  2920  3090 I bt_vendor: epilog_cb
07-07 20:27:56.940  2920  3090 I bt_hci  : epilog_finished_callback
,07-07 20:27:56.942  2920  3086 I bt_hci_h4: hal_close
07-07 20:27:56.942  2920  3086 I bt_userial_vendor: device fd = 49 close
,07-07 20:27:57.145  2920  3083 D bt_stack_manager: event_shut_down_stack finished.
,07-07 20:27:57.145  2920  3082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-07 20:27:57.146  2920  3082 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-07 20:27:57.146  2920  2920 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-07 20:27:57.147  2920  2920 D BtGatt.GattService: Received stop request...Stopping profile...
07-07 20:27:57.147  2920  2920 D BtGatt.GattService: stop()
07-07 20:27:57.147  2920  2920 D BtGatt.AdvertiseManager: advertise clients cleared
,07-07 20:27:57.148  2920  2920 V BluetoothAdapterState: isTurningOff()=false
07-07 20:27:57.148  2920  2920 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:57.148  2920  2920 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:27:57.148  2920  2920 V BluetoothAdapterState: isBleTurningOff()=true
07-07 20:27:57.148  2920  3082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-07 20:27:57.148  2920  3082 D BluetoothAdapterProperties: Setting state to 10
07-07 20:27:57.148  2920  3082 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-07 20:27:57.148   454   496 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
07-07 20:27:57.149  2920  3082 I BluetoothAdapterState: Entering OffState
,07-07 20:27:57.152  2920  2920 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-07 20:27:57.152  2920  2920 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-07 20:27:57.152  2920  2920 I BluetoothServiceJni: cleanupNative: return from cleanup
07-07 20:27:57.153  2920  3083 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-07 20:27:57.154  2920  3083 D bt_stack_manager: event_clean_up_stack finished.
,07-07 20:27:57.155  2920  2920 I art     : System.exit called, status: 0
07-07 20:27:57.155  2920  2920 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-07 20:27:57.183   454   471 I ActivityManager: Process com.android.bluetooth (pid 2920) has died
,07-07 20:27:59.649  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:27:59.649  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:27:59.659  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:27:59.659  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5376ad2 added. We now have 6 listener(s)
,07-07 20:27:59.659  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:59.662  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:27:59.662  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b90a7a3 added. We now have 7 listener(s)
,07-07 20:27:59.662  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:59.663  2815  2857 I System.out: IsBluetoothEnabled
,07-07 20:27:59.673  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:59.700   454   496 I ActivityManager: Start proc 3123:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-07 20:27:59.799  3123  3123 D AdapterServiceConfig: Adding HeadsetService
,07-07 20:27:59.799  3123  3123 D AdapterServiceConfig: Adding A2dpService
07-07 20:27:59.799  3123  3123 D AdapterServiceConfig: Adding HidService
07-07 20:27:59.799  3123  3123 D AdapterServiceConfig: Adding HealthService
07-07 20:27:59.799  3123  3123 D AdapterServiceConfig: Adding PanService
07-07 20:27:59.799  3123  3123 D AdapterServiceConfig: Adding GattService
,07-07 20:27:59.812   454   496 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42084b8:true
,07-07 20:27:59.812  3123  3123 D BluetoothAdapterState: make() - Creating AdapterState
,07-07 20:27:59.816  3123  3123 I bt_bluedroid: init
,07-07 20:27:59.816  3123  3135 I BluetoothAdapterState: Entering OffState
,07-07 20:27:59.818  3123  3136 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-07 20:27:59.818  3123  3136 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-07 20:27:59.818  3123  3136 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-07 20:27:59.819  3123  3136 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-07 20:27:59.819  3123  3123 I bt_bluedroid: get_profile_interface socket
,07-07 20:27:59.821  3123  3123 I bt_bluedroid: get_profile_interface sdp
,07-07 20:27:59.825  3123  3134 I bt_bluedroid: config_hci_snoop_log
,07-07 20:27:59.826  3123  3139 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
,07-07 20:27:59.826   454   496 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-07 20:27:59.828  3123  3139 D BluetoothAdapterProperties: Name is: Nexus 9
07-07 20:27:59.830  3123  3135 D BluetoothAdapterState: Current state: OFF, message: 0
07-07 20:27:59.831  3123  3135 D BluetoothAdapterProperties: Setting state to 14
07-07 20:27:59.831  3123  3135 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-07 20:27:59.831  3123  3135 D BluetoothBondStateMachine: make
07-07 20:27:59.834  3123  3140 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-07 20:27:59.835  3123  3135 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:27:59.835  3123  3123 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-07 20:27:59.836  3123  3123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0e39f2
,07-07 20:27:59.837  3123  3123 D BtGatt.DebugUtils: handleDebugAction() action=null
07-07 20:27:59.837  3123  3123 D BtGatt.GattService: Received start request. Starting profile...
,07-07 20:27:59.837  3123  3123 D BtGatt.GattService: start()
07-07 20:27:59.838  3123  3123 I bt_bluedroid: get_profile_interface gatt
,07-07 20:27:59.838  3123  3123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0e39f2
07-07 20:27:59.838  3123  3123 D BtGatt.AdvertiseManager: advertise manager created
,07-07 20:27:59.843  3123  3123 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:27:59.843  3123  3123 V BluetoothAdapterState: isTurningOn()=false
07-07 20:27:59.843  3123  3123 V BluetoothAdapterState: isBleTurningOn()=true
07-07 20:27:59.843  3123  3123 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:27:59.843  3123  3135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-07 20:27:59.844  3123  3135 I bt_bluedroid: enable
07-07 20:27:59.844  3123  3136 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-07 20:27:59.844  3123  3136 I bt_hci  : start_up
07-07 20:27:59.849  3123  3136 I bt_vendor: alloc value 0xf3dac889
07-07 20:27:59.849  3123  3136 I bt_vendor: init
07-07 20:27:59.849  3123  3136 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-07 20:28:00.053  3123  3136 D bt_hci  : start_up starting async portion
,07-07 20:28:00.053  3123  3143 I bt_hci  : event_finish_startup
07-07 20:28:00.053  3123  3143 I bt_hci_h4: hal_open
07-07 20:28:00.053  3123  3143 I bt_userial_vendor: userial vendor open: opening /dev/ttyTHS2
07-07 20:28:00.054  3123  3143 I bt_userial_vendor: device fd = 49 open
,07-07 20:28:00.065  3123  3143 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-07 20:28:00.098  3123  3143 D bt_hwcfg: Chipset BCM4350C0
,07-07 20:28:00.098  3123  3143 D bt_hwcfg: Target name = [BCM4350C0]
07-07 20:28:00.098  3123  3143 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4350c0.hcd
,07-07 20:28:00.712  3123  3143 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-07 20:28:00.713  3123  3143 D bt_hwcfg: Settlement delay -- 100 ms
,07-07 20:28:00.713  3123  3143 I bt_hwcfg: Setting fw settlement delay to 100 
,07-07 20:28:00.821  3123  3143 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-07 20:28:00.822  3123  3143 I bt_hwcfg: Setting local bd addr to B4:CE:F6:34:3D:CC
,07-07 20:28:00.858  3123  3143 I bt_hwcfg: vendor lib fwcfg completed
,07-07 20:28:00.858  3123  3143 I bt_vendor: firmware callback
07-07 20:28:00.858  3123  3143 I bt_hci  : firmware_config_callback
,07-07 20:28:00.869  3123  3145 I bt_btu  : btu_task pending for preload complete event
,07-07 20:28:00.870  3123  3145 I bt_btu_task: Bluetooth chip preload is complete
07-07 20:28:00.870  3123  3145 I bt_btu  : btu_task received preload complete event
,07-07 20:28:00.879  3123  3145 I         : BTE_InitTraceLevels -- TRC_HCI
,07-07 20:28:00.879  3123  3145 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-07 20:28:00.879  3123  3145 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-07 20:28:00.880  3123  3145 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-07 20:28:00.880  3123  3145 I         : BTE_InitTraceLevels -- TRC_AVRC
07-07 20:28:00.880  3123  3145 I         : BTE_InitTraceLevels -- TRC_A2D
07-07 20:28:00.880  3123  3145 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-07 20:28:00.880  3123  3145 I         : BTE_InitTraceLevels -- TRC_BTM
07-07 20:28:00.881  3123  3145 I         : BTE_InitTraceLevels -- TRC_GAP
07-07 20:28:00.881  3123  3145 I         : BTE_InitTraceLevels -- TRC_PAN
07-07 20:28:00.881  3123  3145 I         : BTE_InitTraceLevels -- TRC_SDP
07-07 20:28:00.881  3123  3145 I         : BTE_InitTraceLevels -- TRC_GATT
,07-07 20:28:00.881  3123  3145 I         : BTE_InitTraceLevels -- TRC_SMP
07-07 20:28:00.881  3123  3145 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-07 20:28:00.881  3123  3145 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-07 20:28:01.107  3123  3145 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d2aa31
,07-07 20:28:01.107  3123  3145 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d2aa31 
,07-07 20:28:01.131  3123  3139 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false
,07-07 20:28:01.134  3123  3139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-07 20:28:01.135  3123  3139 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
07-07 20:28:01.138  3123  3139 D BluetoothAdapterProperties: Name is: Nexus 9
07-07 20:28:01.144  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:01.145  3123  3139 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:28:01.146  3123  3139 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:28:01.147  3123  3139 D bt_hci  : do_postload posting postload work item
07-07 20:28:01.147  3123  3143 I bt_hci  : event_postload
,07-07 20:28:01.148  3123  3143 I bt_vendor: sco_config_cb
07-07 20:28:01.148  3123  3143 I bt_hci  : sco_config_callback postload finished.
,07-07 20:28:01.151  3123  3139 D bt_bte_conf: Device ID record 1 : primary
07-07 20:28:01.151  3123  3139 D bt_bte_conf:   vendorId            = 000f
07-07 20:28:01.151  3123  3139 D bt_bte_conf:   vendorIdSource      = 0001
07-07 20:28:01.151  3123  3139 D bt_bte_conf:   product             = 1200
07-07 20:28:01.151  3123  3139 D bt_bte_conf:   version             = 1436
,07-07 20:28:01.151  3123  3139 D bt_bte_conf:   clientExecutableURL = 
07-07 20:28:01.151  3123  3139 D bt_bte_conf:   serviceDescription  = 
07-07 20:28:01.151  3123  3139 D bt_bte_conf:   documentationURL    = 
07-07 20:28:01.152  3123  3139 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-07 20:28:01.152  3123  3136 D bt_stack_manager: event_start_up_stack finished
07-07 20:28:01.153  3123  3135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-07 20:28:01.153  3123  3135 D BluetoothAdapterProperties: Setting state to 15
07-07 20:28:01.153  3123  3135 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-07 20:28:01.155  3123  3143 I bt_vendor: low_power_mode_cb
07-07 20:28:01.157  3123  3135 I BluetoothAdapterState: Entering BleOnState
07-07 20:28:01.158  3123  3135 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-07 20:28:01.158  3123  3135 D BluetoothAdapterProperties: Setting state to 11
07-07 20:28:01.158  3123  3135 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-07 20:28:01.180  3123  3123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0e39f2
,07-07 20:28:01.183  3123  3123 D HeadsetService: Received start request. Starting profile...
07-07 20:28:01.185  3123  3135 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:28:01.187  3123  3123 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-07 20:28:01.187  3123  3123 D HeadsetStateMachine: make
,07-07 20:28:01.200  3123  3123 D HeadsetStateMachine: max_hf_connections = 1
,07-07 20:28:01.200  3123  3123 I bt_bluedroid: get_profile_interface handsfree
07-07 20:28:01.201  3123  3139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-07 20:28:01.201  3123  3139 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,07-07 20:28:01.207  3123  3123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0e39f2
,07-07 20:28:01.208  3123  3123 D A2dpService: Received start request. Starting profile...
,07-07 20:28:01.209  3123  3123 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-07 20:28:01.209  3123  3123 I bt_bluedroid: get_profile_interface avrcp
,07-07 20:28:01.220  3123  3123 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-07 20:28:01.220  3123  3123 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-07 20:28:01.221  3123  3123 D A2dpStateMachine: make
,07-07 20:28:01.223  3123  3123 I bt_bluedroid: get_profile_interface a2dp
,07-07 20:28:01.224  3123  3139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000028
,07-07 20:28:01.234  3123  3153 D A2dpStateMachine: Enter Disconnected: -2
,07-07 20:28:01.234  3123  3123 I BluetoothHidServiceJni: classInitNative: succeeds
,07-07 20:28:01.238  3123  3123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0e39f2
,07-07 20:28:01.241  3123  3123 D HidService: Received start request. Starting profile...
,07-07 20:28:01.241  3123  3123 I bt_bluedroid: get_profile_interface hidhost
07-07 20:28:01.242  3123  3123 D HidService: setHidService(): set to: null
07-07 20:28:01.243  3123  3139 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d0c099
07-07 20:28:01.244  3123  3139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
,07-07 20:28:01.245  3123  3123 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-07 20:28:01.246  3123  3123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0e39f2
,07-07 20:28:01.246  3123  3123 D HealthService: Received start request. Starting profile...
,07-07 20:28:01.247  1103  1103 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:01.249  3123  3123 I bt_bluedroid: get_profile_interface health
,07-07 20:28:01.250  3123  3123 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-07 20:28:01.251  3123  3123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0e39f2
,07-07 20:28:01.251  3123  3123 D PanService: Received start request. Starting profile...
07-07 20:28:01.252  3123  3123 D BluetoothPanServiceJni: initializeNative(L110): pan
07-07 20:28:01.252  3123  3123 I bt_bluedroid: get_profile_interface pan
07-07 20:28:01.252  3123  3139 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-07 20:28:01.256  3123  3151 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-07 20:28:01.256  3123  3123 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:01.256  3123  3123 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:01.256  3123  3123 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:28:01.256  3123  3123 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:28:01.258  3123  3123 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:28:01.258  3123  3123 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:01.258  3123  3123 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:01.258  3123  3123 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:01.258  3123  3123 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:28:01.258  3123  3123 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:01.258  3123  3123 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:01.258  3123  3123 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:01.262  3123  3123 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:01.262  3123  3123 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:01.262  3123  3123 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:01.262  3123  3123 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:28:01.262  3123  3123 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:01.262  3123  3123 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:01.262  3123  3123 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:01.262  3123  3123 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:01.263  3123  3135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-07 20:28:01.263  3123  3135 D BluetoothAdapterProperties: ScanMode =  20
07-07 20:28:01.263  3123  3135 D BluetoothAdapterProperties: State =  11
07-07 20:28:01.263  3123  3135 D BluetoothAdapterProperties: Setting state to 12,
07-07 20:28:01.263  3123  3135 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-07 20:28:01.264  2898  2914 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:28:01.267  3123  3139 D BluetoothAdapterProperties: Scan Mode:21
,07-07 20:28:01.267  3123  3139 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-07 20:28:01.269  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:01.269  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:01.269  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:01.269  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:01.269  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:01.269  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:01.269  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:01.269  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:01.270  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:01.270  3123  3135 I BluetoothAdapterState: Entering OnState
07-07 20:28:01.272  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:28:01.272  2815  2865 I jxcore-log: 
07-07 20:28:01.272  1020  1136 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:01.272   454   496 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:01.272  2898  2914 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:28:01.273  2898  2898 D BluetoothA2dp: Proxy object connected
,07-07 20:28:01.274  2898  2913 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:28:01.275  2898  2913 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-07 20:28:01.275   454   496 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:01.275  2898  2914 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:28:01.276   727   753 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:28:01.277  2898  2914 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:28:01.277   727   727 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:28:01.277   727   727 D PanProfile: Bluetooth service connected
,07-07 20:28:01.278   727   751 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:28:01.278   727   891 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:28:01.279  2898  2914 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:01.279   727   753 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:28:01.280   727   753 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-07 20:28:01.280   727  3117 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:28:01.280  2898  2898 D BluetoothInputDevice: Proxy object connected
07-07 20:28:01.280  2898  2898 D HidProfile: Bluetooth service connected
07-07 20:28:01.281   727   727 D BluetoothA2dp: Proxy object connected
07-07 20:28:01.281   454   496 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:28:01.281  2898  2898 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:28:01.281  2898  2898 D PanProfile: Bluetooth service connected
07-07 20:28:01.281   727   891 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-07 20:28:01.283   454   496 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:28:01.283   727   727 D BluetoothInputDevice: Proxy object connected
07-07 20:28:01.283   727   727 D HidProfile: Bluetooth service connected
07-07 20:28:01.284   454   454 D BluetoothA2dp: Proxy object connected
07-07 20:28:01.286   454   454 I Telecom : BluetoothPhoneService: queryPhoneState
07-07 20:28:01.288  2898  2898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:28:01.293  1103  1103 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:01.306  2898  2898 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:28:01.308  2898  2898 D BluetoothPbap: Proxy object connected
07-07 20:28:01.308  2898  2898 D PbapServerProfile: Bluetooth service connected
,07-07 20:28:01.310  3123  3164 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:28:01.315   727   727 D BluetoothPbap: Proxy object connected
07-07 20:28:01.315   727   727 D PbapServerProfile: Bluetooth service connected
,07-07 20:28:01.328  3123  3168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:28:01.330  3123  3168 I BtOppRfcommListener: Accept thread started.
,07-07 20:28:01.373  2898  2913 D BluetoothHeadset: Proxy object connected
,07-07 20:28:01.373   454   454 D BluetoothHeadset: Proxy object connected
07-07 20:28:01.373   727  3117 D BluetoothHeadset: Proxy object connected
,07-07 20:28:01.373   454   454 D BluetoothHeadset: Proxy object connected
07-07 20:28:01.373   727   727 D HeadsetProfile: Bluetooth service connected
07-07 20:28:01.373   454   454 D BluetoothHeadset: Proxy object connected
07-07 20:28:01.374  1020  1055 D BluetoothHeadset: Proxy object connected
,07-07 20:28:01.375  2898  2898 D HeadsetProfile: Bluetooth service connected
,07-07 20:28:01.375   454   496 D BluetoothHeadset: Proxy object connected
,07-07 20:28:01.379   727   753 D BluetoothHeadset: Proxy object connected
,07-07 20:28:01.379   727   727 D HeadsetProfile: Bluetooth service connected
07-07 20:28:01.379  2898  2914 D BluetoothHeadset: Proxy object connected
07-07 20:28:01.379  2898  2898 D HeadsetProfile: Bluetooth service connected
,07-07 20:28:01.381   454   496 D BluetoothHeadset: Proxy object connected
,07-07 20:28:01.691  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:01.691  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:01.691  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:01.691  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:01.691  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:01.691  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:01.691  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:01.691  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:01.695  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:01.697  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:28:01.699  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:28:01.699  2815  2865 I jxcore-log: 
,07-07 20:28:01.699  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@abd3aa0 added. We now have 8 listener(s)
,07-07 20:28:01.699  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:01.703   454   750 D WifiService: setWifiEnabled: false pid=2815, uid=10000
07-07 20:28:01.703   454   750 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:28:01.714  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:01.715   454   470 D WifiService: setWifiEnabled: true pid=2815, uid=10000
,07-07 20:28:01.715   454   470 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:28:01.724   218   538 D SoftapController: Softap fwReload - Ok
,07-07 20:28:01.730   218   538 D CommandListener: Setting iface cfg
,07-07 20:28:01.730   218   538 D CommandListener: Trying to bring down wlan0
07-07 20:28:01.732   218   538 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:28:01.736   454   669 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-07 20:28:02.398   454   669 D wifi    : set interface wlan0 flags (UP)
,07-07 20:28:02.398   454   669 I WifiHAL : Initializing wifi
07-07 20:28:02.398   454   669 I WifiHAL : Creating socket
07-07 20:28:02.401   454   669 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-07 20:28:02.401   454   669 D wifi    : Did set static halHandle = 0x559bdecdf0
07-07 20:28:02.401   454   669 D wifi    : halHandle = 0x559bdecdf0, mVM = 0x559bb57c30, mCls = 0x1362
07-07 20:28:02.401   454   669 D wifi    : array field set
,07-07 20:28:02.401   454   669 I WifiNative-HAL: interface[0] = wlan0
,07-07 20:28:02.408   454  3173 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=367687290352
,07-07 20:28:02.408   454  3173 D wifi    : waitForHalEvents called, vm = 0x559bb57c30, obj = 0x1362, env = 0x559c14cd10
,07-07 20:28:02.454  3174  3174 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-07 20:28:02.490  3174  3174 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:28:02.503   454   669 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-07 20:28:02.507  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:02.525  3174  3174 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:28:02.525  3174  3174 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,07-07 20:28:02.537   454   669 D WifiConfigStore: Loading config and enabling all networks 
07-07 20:28:02.538  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:02.538  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:02.538  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:02.538  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:02.538  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:02.538  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:02.538  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:02.538  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:02.539  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:02.540  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:02.540  2815  2865 I jxcore-log: 
07-07 20:28:02.546   454   669 D WifiConfigStore: loaded 0 passpoint configs
07-07 20:28:02.548   454   669 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-07 20:28:02.549   454   669 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-07 20:28:02.550   454   669 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-07 20:28:02.550   454   669 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-07 20:28:02.550   454   669 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-07 20:28:02.550   454   669 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-07 20:28:02.555  2958  2958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:28:02.555   454   669 D WifiNative-HAL: Setting external_sim to 1
07-07 20:28:02.555   454   669 D wifi    : setting dfs flag to true, 0x559c2dd730
07-07 20:28:02.555   454   669 D WifiStateMachine: Setting OUI to DA-A1-19
07-07 20:28:02.556   454   669 D wifi    : setting scan oui 0x559c2dd730
07-07 20:28:02.556   454   669 D WifiHAL : Sending mac address OUI
07-07 20:28:02.560   454   669 E native  : do suspend false
,07-07 20:28:02.568   454   669 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-07 20:28:02.571   454   454 D RttService: SCAN_AVAILABLE : 3
,07-07 20:28:02.571   454   685 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-07 20:28:02.575   454   669 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:28:02.575   218   538 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-07 20:28:02.577   218   538 D CommandListener: Setting iface cfg
07-07 20:28:02.578   454   668 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '70 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 70 Failed to set address (No such device)'
07-07 20:28:02.578   454   668 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-07 20:28:02.584   454   668 D WifiNative-HAL: p2pGetDeviceAddress
07-07 20:28:02.585   454   668 D WifiNative-HAL: p2pGetDeviceAddress returning 52:2e:5c:e5:0c:a7
,07-07 20:28:02.611   454   487 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=147594 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=35 mControllerEnergyUsed=133 }
,07-07 20:28:02.739  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:02.739  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:02.739  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:02.739  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:02.739  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:02.739  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:02.739  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:02.739  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:02.744  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:02.749  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:02.749  2815  2865 I jxcore-log: 
,07-07 20:28:02.753  2815  2857 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-07 20:28:02.755  2815  2857 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-07 20:28:02.764  2815  2857 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7c2033e Bundle[{}]
,07-07 20:28:02.765  2815  2857 I io.jxcore.node.LifeCycleMonitor: start: OK
07-07 20:28:02.766  2815  2857 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-07 20:28:02.767  2815  2857 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-07 20:28:02.769  2815  2857 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-07 20:28:02.770  2815  2857 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-07 20:28:02.771  2815  2857 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-07 20:28:02.775  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-07 20:28:02.775  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-07 20:28:02.775  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-07 20:28:02.775  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-07 20:28:02.775  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-07 20:28:02.776  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:28:02.780  2815  2857 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 88)
,07-07 20:28:02.780  2815  2857 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 88)
07-07 20:28:02.780  2815  2857 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 88)
07-07 20:28:02.780  2815  2857 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 88)
,07-07 20:28:02.783  2815  2857 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 94)
,07-07 20:28:02.783  2815  2857 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 94)
07-07 20:28:02.783  2815  2857 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 94)
07-07 20:28:02.783  2815  2857 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 95)
,07-07 20:28:02.784  2815  2857 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 97)
,07-07 20:28:02.785  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.785  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22ee659 added. We now have 2 listener(s)
,07-07 20:28:02.786  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.786  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.787  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:02.787  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.787  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fd621e added. We now have 9 listener(s)
07-07 20:28:02.787  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:02.789  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-07 20:28:02.791  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:28:02.793  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:02.793  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:02.793  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:02.793  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:02.793  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:02.793  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:02.793  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:02.793  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:02.794  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:02.794  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:02.795  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.795  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ccb60cc added. We now have 3 listener(s)
,07-07 20:28:02.795  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:02.796  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.796  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.796  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:28:02.796  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.796  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3de8f15 added. We now have 10 listener(s)
07-07 20:28:02.796  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:02.796  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:02.797  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:02.797  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:02.797  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:02.798  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:02.798  2815  2865 I jxcore-log: 
07-07 20:28:02.798  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:02.798  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.798  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-07 20:28:02.798  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.798  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22ee659 removed from the list
07-07 20:28:02.798  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.798  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fd621e removed from the list
07-07 20:28:02.798  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:02.798  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:02.799  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.799  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:28:02.799  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.799  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fd621e not in the list
07-07 20:28:02.799  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.799  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:28:02.799  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.799  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3de8f15 removed from the list
07-07 20:28:02.799  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:02.799  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.799  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:02.799  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.799  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ccb60cc removed from the list
07-07 20:28:02.800  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.800  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@499822a added. We now have 2 listener(s)
07-07 20:28:02.801  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.801  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.801  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:02.801  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.801  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@181681b added. We now have 9 listener(s)
,07-07 20:28:02.802  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:02.803  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:28:02.806  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:28:02.808  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:02.808  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:02.808  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:02.808  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:02.808  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:02.808  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:02.808  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:02.808  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:02.809  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:02.810  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:02.810  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.810  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a60791 added. We now have 3 listener(s)
07-07 20:28:02.810  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:02.811  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.811  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.811  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:02.811  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.811  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:02.811  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52596f6 added. We now have 10 listener(s)
07-07 20:28:02.811  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:02.811  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:02.811  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:02.811  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:02.811  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:02.812  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:02.812  2815  2865 I jxcore-log: 
,07-07 20:28:02.818  2815  2857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-07 20:28:02.818  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-07 20:28:02.825  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-07 20:28:02.828  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-07 20:28:02.828  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:02.828  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-07 20:28:02.828  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:28:02.828  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-07 20:28:02.829  2815  2857 D BluetoothAdapter: STATE_ON
,07-07 20:28:02.838  3123  3134 D BtGatt.GattService: registerClient() - UUID=e7cb9181-63d2-4de2-8a3e-5ab578b6e005
,07-07 20:28:02.839  3123  3139 D BtGatt.GattService: onClientRegistered() - UUID=e7cb9181-63d2-4de2-8a3e-5ab578b6e005, clientIf=5
,07-07 20:28:02.839  2815  2827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:28:02.840  3123  3133 D BtGatt.GattService: start scan with filters
,07-07 20:28:02.845  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-07 20:28:02.845  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:28:02.845  3123  3142 D BtGatt.ScanManager: handling starting scan
07-07 20:28:02.845  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:28:02.845  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-07 20:28:02.845  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-07 20:28:02.846  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:28:02.846  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-07 20:28:02.846  3123  3142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0e39f2
,07-07 20:28:02.848  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:28:02.848  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:02.848  2815  2865 I jxcore-log: 
07-07 20:28:02.848  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-07 20:28:02.848  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-07 20:28:02.849  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:02.849  2815  2865 I jxcore-log: 
,07-07 20:28:02.850  3123  3139 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:28:02.850  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.850  3123  3142 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-07 20:28:02.851  2815  2857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-07 20:28:02.851  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:02.851  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:02.851  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:28:02.851  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:28:02.852  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:28:02.852  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:28:02.852  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:28:02.852  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-07 20:28:02.853  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-07 20:28:02.853  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.853  3123  3142 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:28:02.853  2815  2857 D BluetoothAdapter: STATE_ON
,07-07 20:28:02.853  3123  3142 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-07 20:28:02.854  3123  3158 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:28:02.854  3123  3139 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:28:02.854  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.854  3123  3134 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:28:02.855  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-07 20:28:02.855  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:28:02.855  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:28:02.855  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:28:02.855  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:28:02.855  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:02.856  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:28:02.856  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:28:02.856  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:28:02.856  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:02.856  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.856  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:02.857  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:02.857  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:02.857  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:28:02.857  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:28:02.859  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:02.859  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:02.859  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:02.859  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:02.859  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.859  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:28:02.859  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:02.860  2815  2815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:28:02.861  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.861  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@499822a removed from the list
07-07 20:28:02.861  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.861  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@181681b removed from the list
07-07 20:28:02.861  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-07 20:28:02.861  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:28:02.861  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.861  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:02.862  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.862  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,07-07 20:28:02.862  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.862  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:02.862  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:28:02.862  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@181681b not in the list
,07-07 20:28:02.862  3123  3142 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:28:02.863  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:28:02.863  2815  2815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:28:02.863  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:02.864  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:02.865  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:28:02.865  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:28:02.865  3123  3142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-07 20:28:02.866  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:02.866  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:02.866  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-07 20:28:02.866  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:02.866  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:02.867  3123  3139 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:28:02.867  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.867  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:02.867  2815  2857 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:28:02.867  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:02.867  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:28:02.867  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.867  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52596f6 removed from the list
07-07 20:28:02.867  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:28:02.867  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.867  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:02.867  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.867  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a60791 removed from the list
07-07 20:28:02.868  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:02.868  2815  2865 I jxcore-log: 
07-07 20:28:02.868  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.868  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4917c9 added. We now have 2 listener(s)
,07-07 20:28:02.868  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:02.868  2815  2865 I jxcore-log: 
07-07 20:28:02.870  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.870  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.870  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:02.870  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.870  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d48ece added. We now have 9 listener(s)
,07-07 20:28:02.870  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:02.871  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:28:02.873  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:02.875  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:02.875  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:02.875  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:02.875  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:02.875  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:02.875  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:02.875  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:02.875  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:02.876  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:02.876  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 20:28:02.877  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:02.878  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:02.878  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.878  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4e94fc added. We now have 3 listener(s)
,07-07 20:28:02.879  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:02.879  2815  2865 I jxcore-log: 
07-07 20:28:02.880  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.880  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.880  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:28:02.880  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.880  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c26785 added. We now have 10 listener(s)
07-07 20:28:02.880  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:02.880  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-07 20:28:02.880  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:02.880  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:02.880  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:02.880  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:02.883  2815  2857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-07 20:28:02.883  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:28:02.885  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:28:02.885  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:28:02.885  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:02.885  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-07 20:28:02.885  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:28:02.885  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-07 20:28:02.886  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:02.887  3123  3160 D BtGatt.GattService: registerClient() - UUID=46ad37cd-9603-4d15-b9fe-47690fab2dc7
,07-07 20:28:02.888  3123  3139 D BtGatt.GattService: onClientRegistered() - UUID=46ad37cd-9603-4d15-b9fe-47690fab2dc7, clientIf=5
07-07 20:28:02.888  2815  2827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:28:02.888  3123  3133 D BtGatt.GattService: start scan with filters
07-07 20:28:02.889  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-07 20:28:02.889  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:28:02.889  3123  3142 D BtGatt.ScanManager: handling starting scan
,07-07 20:28:02.889  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:28:02.889  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-07 20:28:02.889  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-07 20:28:02.890  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-07 20:28:02.890  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-07 20:28:02.891  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:02.891  2815  2865 I jxcore-log: 
,07-07 20:28:02.896  3123  3139 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:28:02.896  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.896  3123  3142 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-07 20:28:02.901  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-07 20:28:02.901  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:28:02.901  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:28:02.901  3123  3142 D BtGatt.ScanManager: Starting BLE batch scan
,07-07 20:28:02.901  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-07 20:28:02.901  3123  3142 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-07 20:28:02.902  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:28:02.903  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:02.903  2815  2865 I jxcore-log: 
07-07 20:28:02.904  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:02.904  2815  2857 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-07 20:28:02.905  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:02.905  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:02.905  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:02.905  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:02.905  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.905  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:02.905  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.905  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4917c9 removed from the list
07-07 20:28:02.905  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.905  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d48ece removed from the list
,07-07 20:28:02.905  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:02.905  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:02.906  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.906  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-07 20:28:02.906  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.906  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:02.906  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.906  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d48ece not in the list
,07-07 20:28:02.906  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:28:02.906  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:28:02.906  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:28:02.906  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:28:02.906  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-07 20:28:02.907  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:02.907  3123  3134 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:28:02.908  3123  3160 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:28:02.908  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:02.908  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:28:02.908  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-07 20:28:02.908  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:28:02.908  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:28:02.908  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:02.908  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:02.908  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:28:02.909  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:02.909  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:02.910  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:02.910  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:02.910  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:02.910  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:28:02.911  3123  3139 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:28:02.911  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.913  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:02.913  2815  2815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:28:02.915  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:28:02.916  2815  2815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:28:02.916  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:02.916  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:02.916  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:28:02.916  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.918  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:02.918  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-07 20:28:02.918  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:02.918  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:02.918  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:02.918  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:02.918  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:02.918  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.918  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c26785 removed from the list
07-07 20:28:02.918  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:02.919  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:02.919  2815  2865 I jxcore-log: 
07-07 20:28:02.919  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:02.919  2815  2865 I jxcore-log: 
07-07 20:28:02.918  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.920  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-07 20:28:02.920  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.920  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4e94fc removed from the list
07-07 20:28:02.920  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.920  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8928794 added. We now have 2 listener(s)
07-07 20:28:02.921  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.921  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.921  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:02.922  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.922  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2b023d added. We now have 9 listener(s)
07-07 20:28:02.922  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-07 20:28:02.922  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:28:02.922  3123  3142 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:28:02.922  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:02.923  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:28:02.925  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:02.930  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:28:02.930  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.930  3123  3142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:28:02.932  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:02.932  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:02.932  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:02.932  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:02.932  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:02.932  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:02.932  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:02.932  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:02.933  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:02.933  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:02.934  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:02.935  3123  3139 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:28:02.935  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.936  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:02.936  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.937  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@572b383 added. We now have 3 listener(s)
,07-07 20:28:02.937  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:02.937  2815  2865 I jxcore-log: 
07-07 20:28:02.939  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.940  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.940  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:02.940  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.940  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eda8900 added. We now have 10 listener(s)
07-07 20:28:02.940  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:02.940  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:02.940  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:02.940  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:02.940  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:28:02.943  2815  2857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:02.943  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-07 20:28:02.945  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-07 20:28:02.945  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-07 20:28:02.945  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:02.945  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-07 20:28:02.945  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:28:02.945  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-07 20:28:02.945  2815  2857 D BluetoothAdapter: STATE_ON
,07-07 20:28:02.946  3123  3133 D BtGatt.GattService: registerClient() - UUID=0b0a7ffa-0aa3-49c7-9229-19b6842a0155
07-07 20:28:02.946  3123  3139 D BtGatt.GattService: onClientRegistered() - UUID=0b0a7ffa-0aa3-49c7-9229-19b6842a0155, clientIf=5
07-07 20:28:02.947  2815  2826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-07 20:28:02.947  3123  3160 D BtGatt.GattService: start scan with filters
,07-07 20:28:02.948  3123  3142 D BtGatt.ScanManager: handling starting scan
07-07 20:28:02.948  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-07 20:28:02.948  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:28:02.948  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:28:02.948  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-07 20:28:02.948  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:28:02.948  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-07 20:28:02.949  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-07 20:28:02.949  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-07 20:28:02.949  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:28:02.949  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:28:02.950  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:02.950  2815  2865 I jxcore-log: 
,07-07 20:28:02.951  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:02.951  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:02.951  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:02.951  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:02.951  2815  2865 I jxcore-log: 
07-07 20:28:02.952  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:02.952  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.952  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:28:02.952  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.952  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8928794 removed from the list
07-07 20:28:02.952  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.952  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2b023d removed from the list
,07-07 20:28:02.952  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:02.952  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:02.953  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.953  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:02.953  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:02.953  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:02.953  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:28:02.953  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2b023d not in the list
,07-07 20:28:02.953  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-07 20:28:02.953  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-07 20:28:02.953  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-07 20:28:02.953  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-07 20:28:02.953  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-07 20:28:02.953  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:02.954  3123  3134 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:28:02.954  3123  3158 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:28:02.955  3123  3139 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:28:02.955  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.955  3123  3142 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-07 20:28:02.955  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:02.955  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:28:02.955  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:28:02.955  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:28:02.955  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:28:02.955  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:02.955  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:02.955  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:28:02.955  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,07-07 20:28:02.955  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:02.955  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:02.955  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:02.955  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:02.955  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:02.956  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:02.956  2815  2815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:28:02.958  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:28:02.959  2815  2815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:28:02.959  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:02.959  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:02.960  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:28:02.960  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.960  3123  3142 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:28:02.960  3123  3142 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-07 20:28:02.961  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:02.961  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:02.961  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:02.962  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:02.962  2815  2857 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:28:02.962  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-07 20:28:02.962  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:28:02.962  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.962  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eda8900 removed from the list
,07-07 20:28:02.962  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:02.962  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.962  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:02.962  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-07 20:28:02.962  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@572b383 removed from the list
,07-07 20:28:02.963  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.963  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7453bf5 added. We now have 2 listener(s)
07-07 20:28:02.964  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.964  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.964  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:02.964  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.964  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53d5d8a added. We now have 9 listener(s)
07-07 20:28:02.964  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:02.965  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:02.965  2815  2865 I jxcore-log: 
07-07 20:28:02.965  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:02.965  2815  2865 I jxcore-log: 
07-07 20:28:02.967  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:28:02.969  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:02.971  3123  3139 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:28:02.971  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.972  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:02.972  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:02.972  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:02.972  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:02.972  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:02.972  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:02.972  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:02.972  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:02.973  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:02.973  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:02.974  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:02.975  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:02.975  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:02.975  2815  2865 I jxcore-log: 
07-07 20:28:02.976  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.976  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a07818 added. We now have 3 listener(s)
07-07 20:28:02.976  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:28:02.976  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.979  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-07 20:28:02.979  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.979  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:02.980  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:02.980  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87aa271 added. We now have 10 listener(s)
07-07 20:28:02.980  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:02.980  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:02.980  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:02.980  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-07 20:28:02.981  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-07 20:28:02.981  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.981  3123  3142 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:28:02.980  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:02.982  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.982  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-07 20:28:02.982  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.982  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7453bf5 removed from the list
,07-07 20:28:02.982  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.982  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53d5d8a removed from the list
07-07 20:28:02.982  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:02.982  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:02.982  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.982  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:02.982  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.983  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:28:02.983  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.983  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53d5d8a not in the list
07-07 20:28:02.983  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.983  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:02.983  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.983  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:28:02.983  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.983  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87aa271 removed from the list
07-07 20:28:02.983  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:28:02.983  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.983  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:02.983  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.983  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a07818 removed from the list
07-07 20:28:02.985  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:02.985  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 added. We now have 2 listener(s)
,07-07 20:28:02.986  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:28:02.986  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.986  3123  3142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:28:02.987  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-07 20:28:02.987  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:02.987  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:02.988  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:28:02.988  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 added. We now have 9 listener(s)
07-07 20:28:02.988  2815  2857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:02.990  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:28:02.991  3123  3139 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:28:02.991  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:02.992  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:02.995  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:02.995  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:02.995  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:02.995  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:02.995  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:02.995  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:02.995  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:02.995  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:02.996  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:02.996  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:02.996  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-07 20:28:02.996  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-07 20:28:02.997  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:28:02.998  2815  2857 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-07 20:28:02.998  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:02.999  2815  2857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-07 20:28:02.999  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-07 20:28:02.999  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:28:02.999  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:28:02.999  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:02.999  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:02.999  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:02.999  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:02.999  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:02.999  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:02.999  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-07 20:28:02.999  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:02.999  2815  2857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 removed from the list
07-07 20:28:02.999  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:02.999  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 removed from the list
07-07 20:28:02.999  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:02.999  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.000  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:03.000  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.000  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.000  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:28:03.000  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.000  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.000  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:03.000  2815  2865 I jxcore-log: 
07-07 20:28:03.000  2815  2857 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-07 20:28:03.001  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.001  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.001  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.001  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.001  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:03.001  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.001  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.001  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.001  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.001  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.001  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.001  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.001  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.001  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-07 20:28:03.001  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.002  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.002  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:28:03.002  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.003  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-07 20:28:03.003  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,07-07 20:28:03.005  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-07 20:28:03.005  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-07 20:28:03.005  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-07 20:28:03.005  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-07 20:28:03.005  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-07 20:28:03.005  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-07 20:28:03.005  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-07 20:28:03.005  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-07 20:28:03.005  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:28:03.005  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.005  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.005  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.006  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.006  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
,07-07 20:28:03.006  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.006  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.006  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.006  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.006  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.006  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.006  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.006  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.006  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:28:03.006  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.006  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.007  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.007  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:28:03.007  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.007  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.007  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.007  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.007  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.007  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.007  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.007  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.007  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:03.007  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.007  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.007  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.007  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.007  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.007  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:28:03.008  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.008  2815  2857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:28:03.010  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:03.012  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:03.012  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:03.012  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:03.012  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:03.012  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:03.012  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:03.012  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:03.012  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:03.012  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:03.012  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:03.013  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:03.013  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:03.013  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:03.013  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:03.014  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:03.014  2815  2857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.014  2815  2857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:28:03.017  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-07 20:28:03.017  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:03.018  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:03.018  2815  2865 I jxcore-log: 
07-07 20:28:03.019  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:28:03.019  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:03.019  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-07 20:28:03.019  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:28:03.019  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-07 20:28:03.019  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.020  3123  3134 D BtGatt.GattService: registerClient() - UUID=f38296a9-1a4c-4125-8813-94ef8969e0b1
07-07 20:28:03.020  3123  3139 D BtGatt.GattService: onClientRegistered() - UUID=f38296a9-1a4c-4125-8813-94ef8969e0b1, clientIf=5
07-07 20:28:03.021  2815  2826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-07 20:28:03.021  3123  3158 D BtGatt.GattService: start scan with filters
07-07 20:28:03.023  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-07 20:28:03.023  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:28:03.023  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:28:03.023  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-07 20:28:03.023  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:28:03.024  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-07 20:28:03.024  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-07 20:28:03.024  3123  3142 D BtGatt.ScanManager: handling starting scan
07-07 20:28:03.025  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:28:03.025  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-07 20:28:03.025  2815  2857 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:28:03.025  2815  2815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:03.025  2815  2815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-07 20:28:03.025  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:28:03.026  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:03.026  2815  2865 I jxcore-log: 
07-07 20:28:03.026  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:03.026  2815  2865 I jxcore-log: 
07-07 20:28:03.033  3123  3139 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:28:03.033  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.033  3123  3142 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-07 20:28:03.035  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.038  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.038  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.038  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-07 20:28:03.038  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:28:03.038  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:28:03.038  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:28:03.038  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:28:03.038  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-07 20:28:03.039  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:28:03.039  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.039  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.039  3123  3133 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:28:03.039  3123  3142 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:28:03.039  3123  3142 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-07 20:28:03.045   454   463 I art     : Background partial concurrent mark sweep GC freed 33884(1850KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/26MB, paused 1.786ms total 112.840ms
,07-07 20:28:03.049  3123  3139 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:28:03.049  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.049  3123  3160 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:28:03.049  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.049  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-07 20:28:03.049  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:28:03.049  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:28:03.049  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:28:03.049  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:03.049  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.049  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:28:03.050  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.055  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:28:03.055  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:28:03.055  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.055  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-07 20:28:03.055  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:03.055  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:03.055  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:03.057  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-07 20:28:03.057  2815  2815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:28:03.059  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:28:03.059  2815  2815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:28:03.059  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:03.059  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:03.061  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.061  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.061  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-07 20:28:03.062  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.062  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.062  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.062  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.062  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:03.062  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-07 20:28:03.062  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.062  3123  3142 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:28:03.067  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:03.068  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:03.068  2815  2865 I jxcore-log: 
07-07 20:28:03.070  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:28:03.070  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:28:03.070  3123  3142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:28:03.074  3123  3139 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:28:03.074  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.075  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:03.075  2815  2865 I jxcore-log: 
07-07 20:28:03.062  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:28:03.075  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:28:03.076  2815  2857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:28:03.076  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:03.078  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:03.078  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:03.078  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:03.078  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:03.078  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:03.078  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:03.078  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:03.078  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:03.079  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:03.079  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:03.080  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:03.081  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:03.082  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:03.082  2815  2865 I jxcore-log: 
07-07 20:28:03.082  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-07 20:28:03.082  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:03.084  2815  2857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.084  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-07 20:28:03.084  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:28:03.084  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-07 20:28:03.084  2815  2857 D BluetoothAdapter: STATE_ON
,07-07 20:28:03.085  3123  3133 D BtGatt.GattService: registerClient() - UUID=d60ad858-c1b1-4a0c-8ada-3054a4ed27a5
,07-07 20:28:03.086  3123  3139 D BtGatt.GattService: onClientRegistered() - UUID=d60ad858-c1b1-4a0c-8ada-3054a4ed27a5, clientIf=5
07-07 20:28:03.086  2815  2826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:28:03.086  3123  3134 D BtGatt.GattService: start scan with filters
07-07 20:28:03.088  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-07 20:28:03.088  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:28:03.088  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-07 20:28:03.088  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-07 20:28:03.088  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:28:03.088  3123  3142 D BtGatt.ScanManager: handling starting scan
,07-07 20:28:03.088  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-07 20:28:03.088  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-07 20:28:03.091  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-07 20:28:03.091  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-07 20:28:03.092  2815  2815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-07 20:28:03.092  2815  2815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-07 20:28:03.092  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-07 20:28:03.093  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:03.093  2815  2865 I jxcore-log: 
07-07 20:28:03.093  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:03.093  2815  2865 I jxcore-log: 
07-07 20:28:03.093  2815  2857 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:28:03.094  3123  3139 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:28:03.094  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.094  3123  3142 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-07 20:28:03.095  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.095  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:28:03.095  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:03.095  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-07 20:28:03.095  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:28:03.095  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:28:03.095  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-07 20:28:03.095  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:28:03.095  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-07 20:28:03.096  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.096  3123  3158 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:28:03.097  3123  3160 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:28:03.097  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.097  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:28:03.097  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:28:03.097  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:28:03.097  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:28:03.097  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:03.098  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.098  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:28:03.098  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.098  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:28:03.098  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:03.098  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:03.098  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:28:03.098  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:28:03.099  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:28:03.099  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.099  3123  3142 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:28:03.099  3123  3142 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-07 20:28:03.099  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.099  2815  2815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:28:03.102  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:28:03.102  2815  2815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-07 20:28:03.102  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:03.102  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:03.103  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.103  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:03.103  2815  2815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.104  2815  2815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-07 20:28:03.104  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:03.104  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.104  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.104  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-07 20:28:03.104  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.104  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.104  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.104  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.104  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:28:03.104  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-07 20:28:03.104  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.104  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.105  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:03.105  2815  2865 I jxcore-log: 
,07-07 20:28:03.106  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:03.106  2815  2865 I jxcore-log: 
07-07 20:28:03.106  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.106  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.106  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.106  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.106  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.107  2815  2857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:28:03.108  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:28:03.110  3123  3139 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:28:03.110  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.110  2815  2857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:03.110  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:03.110  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:03.110  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:03.110  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:03.110  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:03.110  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:03.110  2815  2857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:03.113  2815  2857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:03.113  2815  2857 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:03.113  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:03.114  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:03.114  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:03.114  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-07 20:28:03.114  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:03.114  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:03.116  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:03.116  2815  2865 I jxcore-log: 
07-07 20:28:03.116  2815  2857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.116  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-07 20:28:03.116  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:28:03.116  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-07 20:28:03.117  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:28:03.117  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.117  2815  2857 D BluetoothAdapter: STATE_ON
,07-07 20:28:03.118  3123  3160 D BtGatt.GattService: registerClient() - UUID=508c695a-33d9-4738-bacb-34bd9473cbb1
07-07 20:28:03.118  3123  3139 D BtGatt.GattService: onClientRegistered() - UUID=508c695a-33d9-4738-bacb-34bd9473cbb1, clientIf=5
07-07 20:28:03.119  2815  2826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:28:03.119  3123  3133 D BtGatt.GattService: start scan with filters
07-07 20:28:03.120  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-07 20:28:03.120  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:28:03.120  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-07 20:28:03.120  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-07 20:28:03.120  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:28:03.120  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-07 20:28:03.121  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-07 20:28:03.122  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-07 20:28:03.122  2815  2857 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:28:03.122  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.122  2815  2857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-07 20:28:03.122  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.122  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.122  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-07 20:28:03.122  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:28:03.122  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:28:03.122  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-07 20:28:03.122  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:28:03.122  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-07 20:28:03.122  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:28:03.123  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.123  3123  3158 D BtGatt.GattService: stopScan() - queue size =0
,07-07 20:28:03.123  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-07 20:28:03.123  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.123  3123  3142 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:28:03.123  3123  3133 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-07 20:28:03.124  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.124  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:28:03.124  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:28:03.124  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:28:03.124  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:28:03.124  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:28:03.124  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.124  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-07 20:28:03.124  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.124  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:28:03.124  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:03.124  2815  2815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.124  2815  2815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-07 20:28:03.124  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-07 20:28:03.124  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-07 20:28:03.124  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:03.124  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:03.125  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:03.125  2815  2865 I jxcore-log: 
07-07 20:28:03.125  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:28:03.125  2815  2865 I jxcore-log: 
07-07 20:28:03.126  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.126  2815  2815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-07 20:28:03.128  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:28:03.129  2815  2815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:28:03.129  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:03.129  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:03.130  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:28:03.131  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.131  3123  3142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:28:03.131  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.131  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-07 20:28:03.131  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:03.132  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:03.132  2815  2865 I jxcore-log: 
07-07 20:28:03.132  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:03.132  2815  2865 I jxcore-log: 
07-07 20:28:03.135  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.136  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.136  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.136  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.136  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.136  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-07 20:28:03.136  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.136  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.136  3123  3139 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:28:03.136  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.136  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.137  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.137  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:28:03.137  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.137  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.137  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:28:03.138  3123  3142 D BtGatt.ScanManager: handling starting scan
07-07 20:28:03.142  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.142  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.142  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.142  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.142  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
,07-07 20:28:03.147  3123  3139 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:28:03.147  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.147  3123  3142 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-07 20:28:03.152  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:28:03.152  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.152  3123  3142 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:28:03.152  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:28:03.152  3123  3142 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-07 20:28:03.152  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.152  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.152  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:28:03.152  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:03.154  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.154  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.154  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.154  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.154  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.154  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.154  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.154  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.154  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.154  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.155  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.155  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:28:03.155  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.155  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.156  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.156  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.156  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.156  2815  2857 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-07 20:28:03.156  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.156  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.156  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.156  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.156  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.157  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.157  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
,07-07 20:28:03.157  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:28:03.157  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.157  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.158  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.158  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.158  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.158  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-07 20:28:03.158  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:03.158  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.158  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.158  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.158  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.158  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.158  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.158  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
,07-07 20:28:03.159  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-07 20:28:03.159  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.159  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.159  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-07 20:28:03.159  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:28:03.159  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.159  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.159  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
,07-07 20:28:03.159  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.159  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.159  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.159  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.160  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.160  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.160  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.160  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:03.160  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:28:03.160  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:28:03.160  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.160  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.160  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.160  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.160  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.161  2815  2857 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-07 20:28:03.161  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.161  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.161  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.161  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.161  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.161  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.161  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.161  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.161  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.161  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.161  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.161  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.161  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.161  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.161  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.161  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.161  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.162  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.162  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.162  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-07 20:28:03.162  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.162  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.163  2815  2857 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.163  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.163  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.163  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.163  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.163  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.163  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.163  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.163  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.163  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.163  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.163  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.163  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.163  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.163  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.163  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:28:03.163  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.163  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.164  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.164  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.164  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.164  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:28:03.164  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.164  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-07 20:28:03.165  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:28:03.165  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-07 20:28:03.165  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-07 20:28:03.165  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-07 20:28:03.165  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-07 20:28:03.166  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.166  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.166  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.166  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.166  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.166  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.166  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.166  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.166  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.166  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.166  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.166  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.167  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.167  3123  3139 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:28:03.167  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.167  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.167  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.167  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.167  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:28:03.167  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.167  2815  2857 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:28:03.167  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-07 20:28:03.167  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.168  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.168  2815  2857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:28:03.168  2815  2857 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-07 20:28:03.168  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-07 20:28:03.169  2815  2857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-07 20:28:03.169  2815  2857 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-07 20:28:03.169  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-07 20:28:03.170  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,07-07 20:28:03.170  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-07 20:28:03.170  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-07 20:28:03.170  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-07 20:28:03.170  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-07 20:28:03.170  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-07 20:28:03.170  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-07 20:28:03.170  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-07 20:28:03.171  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-07 20:28:03.171  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-07 20:28:03.173  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-07 20:28:03.173  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:28:03.173  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.174  2815  2857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-07 20:28:03.175  2815  2857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-07 20:28:03.175  2815  2857 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-07 20:28:03.175  2815  2857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:28:03.175  2815  2857 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-07 20:28:03.176  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.176  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.176  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.176  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.176  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.177  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:28:03.177  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.177  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.177  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.177  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.177  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.177  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.177  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.177  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.177  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.177  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.177  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.178  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.178  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.178  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.179  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.179  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.181  2815  2857 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,07-07 20:28:03.181  3123  3139 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-07 20:28:03.181  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.181  3123  3142 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:28:03.181  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.181  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.181  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.182  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.182  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.182  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.182  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.182  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.182  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.182  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.182  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.182  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.182  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.182  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-07 20:28:03.183  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.183  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.183  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.183  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.183  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.183  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.183  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.183  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.184  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.184  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.184  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.184  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.184  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.184  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.184  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.184  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.184  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.184  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.184  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.184  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.184  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.184  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.184  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.184  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.184  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.185  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.185  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.185  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.185  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.185  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listene,r org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.185  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.185  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.185  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.185  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.185  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.185  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.186  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.186  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:28:03.186  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.186  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.186  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.186  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.186  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.186  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.186  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.186  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.186  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:28:03.186  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.187  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.187  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.187  3123  3139 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:28:03.187  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.187  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.187  3123  3142 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:28:03.187  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.188  2815  2857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-07 20:28:03.189  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-07 20:28:03.189  2815  2865 I jxcore-log: 
07-07 20:28:03.189  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.190  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.190  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.190  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.190  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.190  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.190  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.190  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.190  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
,07-07 20:28:03.190  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:28:03.190  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.190  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.190  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.190  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.191  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.191  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.191  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.191  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.191  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.191  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.191  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.191  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.192  2815  2857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-07 20:28:03.192  2815  2857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-07 20:28:03.192  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-07 20:28:03.192  2815  2857 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-07 20:28:03.192  2815  2857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-07 20:28:03.192  2815  2857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-07 20:28:03.192  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:28:03.192  2815  2857 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-07 20:28:03.192  2815  2857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-07 20:28:03.192  2815  2857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-07 20:28:03.192  2815  2857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:28:03.192  2815  2857 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-07 20:28:03.192  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.192  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.192  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of ,this operation, skipping...
07-07 20:28:03.192  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.192  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.192  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.192  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.192  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.192  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.193  3123  3139 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:28:03.193  3123  3139 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:28:03.192  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.193  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.193  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.193  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.193  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.193  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.193  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.193  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.194  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.194  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.194  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.194  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.194  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
,07-07 20:28:03.194  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.194  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.194  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.194  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.194  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.194  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.194  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.194  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.195  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.195  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.195  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.195  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.195  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.195  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.195  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.195  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.195  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.195  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.195  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.195  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.195  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:28:03.195  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.196  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.196  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.196  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.196  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.196  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.196  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.196  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.196  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.196  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.196  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.196  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.196  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.196  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.196  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.196  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.197  2815  2857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-07 20:28:03.197  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:03.198  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-07 20:28:03.199  2815  2857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-07 20:28:03.199  2815  2857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-07 20:28:03.199  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-07 20:28:03.199  2815  2815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-07 20:28:03.199  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.199  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:28:03.199  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-07 20:28:03.199  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-07 20:28:03.199  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-07 20:28:03.199  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.199  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.199  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.199  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:28:03.199  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:28:03.199  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:28:03.199  2815  2857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:28:03.200  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.200  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.200  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.200  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.200  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:28:03.200  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.200  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.200  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.200  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.200  2815  2857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-07 20:28:03.200  2815  3178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,07-07 20:28:03.201  2815  3178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-07 20:28:03.201  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:03.201  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:03.201  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:03.202  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.202  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.202  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.202  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:28:03.202  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.202  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:28:03.203  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.203  2815  2815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:28:03.205  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:28:03.205  2815  2815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:28:03.205  2815  2815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:28:03.205  2815  2815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:03.207  2815  2815 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:28:03.207  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-07 20:28:03.207  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.208  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.208  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:28:03.208  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.208  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.208  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.208  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.208  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.208  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.208  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.208  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.208  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.208  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.208  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.208  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.208  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.207  2815  2815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:03.208  2815  2815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-07 20:28:03.208  2815  2815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-07 20:28:03.208  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.209  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.209  2815  2815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-07 20:28:03.209  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.209  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.209  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.209  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:03.209  2815  2865 I jxcore-log: 
07-07 20:28:03.209  2815  2857 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-07 20:28:03.209  2815  2857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-07 20:28:03.210  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortN,umber: Will use port -1 when trying to connect
07-07 20:28:03.210  2815  2857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:28:03.210  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.210  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.210  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.210  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.210  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.210  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.210  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.210  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.210  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.210  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.210  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.210  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.210  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.210  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.210  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.210  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.210  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.211  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.211  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.211  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.211  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.211  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.215  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.215  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.215  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.215  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.215  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.215  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.215  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.215  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.215  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.215  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.215  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.215  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.215  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.215  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.215  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.215  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.215  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.217  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.217  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.217  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.217  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.217  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.217  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.217  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.217  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.217  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.218  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.218  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.218  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.218  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.218  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.218  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.218  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.218  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.218  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.218  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.218  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.218  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.218  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.218  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.218  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.218  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.218  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.218  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.219  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.219  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.219  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.219  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.219  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.219  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.219  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.219  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.219  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.219  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.219  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.219  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.219  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.219  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.219  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.219  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.220  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.221  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.221  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.221  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.222  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.222  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.222  2815  2857 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-07 20:28:03.222  2815  2857 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-07 20:28:03.222  2815  2815 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-07 20:28:03.223  2815  2857 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-07 20:28:03.224  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-07 20:28:03.224  2815  2865 I jxcore-log: 
07-07 20:28:03.225  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.225  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.225  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.225  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.225  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.225  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.225  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.225  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.225  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.225  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.225  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.225  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.225  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.225  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.225  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.225  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.225  2815  2857 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-07 20:28:03.225  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.226  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.226  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.226  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.226  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.226  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.226  2815  2857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:03.226  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:03.226  2815  2857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:03.227  2815  2857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:03.227  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.227  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.227  2815  2857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bc856 not in the list
07-07 20:28:03.227  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.227  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.227  2815  2857 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:03.227  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.227  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.227  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.227  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:28:03.227  2815  2857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:03.227  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:03.227  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:28:03.228  2815  2857 D BluetoothAdapter: STATE_ON
07-07 20:28:03.228  2815  2857 D BluetoothLeScanner: could not find callback wrapper
07-07 20:28:03.228  2815  2857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:28:03.228  2815  2857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:03.229  2815  2857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@162b0d7 not in the list
07-07 20:28:03.229  2815  2857 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-07 20:28:03.229  2815  2857 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-07 20:28:03.229  2815  2857 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-07 20:28:03.229  2815  2857 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-07 20:28:03.229  2815  2857 E com.test.thalitest.ThaliTestRunner: Total duration: 18676 ms
07-07 20:28:03.229  2815  2857 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 18759ms. Plugin should use CordovaInterface.getThreadPool().
,07-07 20:28:04.321   454   669 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 8, 9 -> obsolete
,07-07 20:28:04.990   454   669 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-07 20:28:04.992   454   669 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-07 20:28:04.992   454   669 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:28:05.000   454   669 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-07 20:28:05.027   454   669 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-07 20:28:05.028  3174  3174 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-07 20:28:05.446  3174  3174 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-07 20:28:05.472  3174  3174 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-07 20:28:05.473  3174  3174 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-07 20:28:05.480   454   669 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:28:05.495   454   669 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-07 20:28:05.495   454   669 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-07 20:28:05.495   454   671 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-07 20:28:05.509   454   669 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:28:05.522   218   538 D CommandListener: Setting iface cfg
,07-07 20:28:05.528   454   669 D WifiStateMachine: Start Dhcp Watchdog 2
,07-07 20:28:05.542   454  3186 D DhcpClient: Receive thread started
,07-07 20:28:05.543   454   671 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-07 20:28:05.544   454   671 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,07-07 20:28:05.546   454   669 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{1}, ntable=[]
,07-07 20:28:05.630   454   669 E native  : do suspend false
,07-07 20:28:05.639   454  3185 D DhcpClient: Broadcasting DHCPDISCOVER
,07-07 20:28:05.860  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:05.860  2815  2857 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,07-07 20:28:05.949  2815  2857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-07 20:28:05.949  2815  2857 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,07-07 20:28:06.095   454  3186 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 OFFER, ip /192.168.1.110, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172706, domain null
,07-07 20:28:06.096   454  3185 D DhcpClient: Got pending lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172706 seconds
07-07 20:28:06.099   454  3185 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.110 serverid=192.168.1.1
,07-07 20:28:06.153   454  3186 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 ACK: your new IP /192.168.1.110, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-07 20:28:06.154   454  3185 D DhcpClient: Confirmed lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-07 20:28:06.157   218   538 D CommandListener: Setting iface cfg
,07-07 20:28:06.165   454   669 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{2}, ntable=[]
07-07 20:28:06.168   454  3185 D DhcpClient: Scheduling renewal in 86399s
,07-07 20:28:06.177   454   669 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-07 20:28:06.179   454   669 D WifiConfigStore: No blacklist allowed without epno enabled
,07-07 20:28:06.180   454   671 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-07 20:28:06.183   454   671 D ConnectivityService: Adding iface wlan0 to network 101
,07-07 20:28:06.196   454   669 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-07 20:28:06.256   454   671 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-07 20:28:06.257   454   671 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-07 20:28:06.260   454   671 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-07 20:28:06.264   454   671 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-07 20:28:06.268   454   671 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-07 20:28:06.280   454   671 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-07 20:28:06.286   454   671 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-07 20:28:06.287   454   671 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-07 20:28:06.287   454   669 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-07 20:28:06.288   454   669 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:28:06.288   454   671 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-07 20:28:06.288   454   671 D ConnectivityService:    accepting network in place of null
,07-07 20:28:06.290   454   671 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::522e:5cff:fee5:ca7/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-07 20:28:06.321   218   538 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:28:06.346   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=151328, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:28:06.350   218   538 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:28:06.352   454   671 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-07 20:28:06.352   454   671 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-07 20:28:06.353   454   671 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,07-07 20:28:06.355   454   496 D Tethering: MasterInitialState.processMessage what=3
07-07 20:28:06.362  2815  2815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:06.362  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:06.362  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:28:06.362  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:06.362  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:06.362  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:28:06.362  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:28:06.362  2815  2815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:28:06.363  2815  2815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-07 20:28:06.364  2815  2865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:28:06.364  2815  2865 I jxcore-log: 
,07-07 20:28:06.366  1079  1079 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-07 20:28:06.383  1224  1224 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-07 20:28:06.384  1224  2300 I iu.UploadsManager: num queued entries: 0
,07-07 20:28:06.385  1224  2300 I iu.UploadsManager: num updated entries: 0
07-07 20:28:06.385  1224  2300 I iu.SyncManager: NEXT; no task
,07-07 20:28:06.390  1224  1224 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-07 20:28:06.391  1224  1224 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-07 20:28:06.395  1224  3197 I MDM     : [200] SitrepService.onHandleIntent: sending sitrep: [0, 2, [Dm42Sezn61r6yJxW_kdgWJ-UM6U], null]
,07-07 20:28:06.395  1224  3197 W BaseAppContext: Using Auth Proxy for data requests.
,07-07 20:28:06.398  1224  3197 V GoogleAuthProtoRequest: [200] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:28:06.405  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:06.407  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:06.434  1103  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-07 20:28:06.434  1103  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-07 20:28:06.434  1103  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:28:06.434  1103  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:28:06.442  2077  3203 V KeepSync: Connecting to GoogleApiClient
,07-07 20:28:06.442   454  1076 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-07 20:28:06.449  1224  3197 E MDM     : [200] SitrepService.a: Error sending sitrep.
,07-07 20:28:06.457   454  3183 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:80b::200e
,07-07 20:28:06.469  1103  1163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-07 20:28:06.469  1103  1163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-07 20:28:06.469  1103  1163 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:28:06.469  1103  1163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:28:06.477  1224  3204 V BaseAuthAsyncOperation: access token request failed
,07-07 20:28:06.478  2077  3203 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:28:06.505  1103  1122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-07 20:28:06.505  1103  1122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-07 20:28:06.505  1103  1122 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:28:06.505  1103  1122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:28:06.514  2077  3203 E KeepSync: IOException
07-07 20:28:06.514  2077  3203 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:28:06.514  2077  3203 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:28:06.514  2077  3203 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:28:06.514  2077  3203 E KeepSync: 	... 10 more
,07-07 20:28:06.514  2077  3203 W KeepSync: Sync result 2
,07-07 20:28:06.517   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 148256, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:28:06.557   454  3183 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 07 Jul 2016 18:28:06 GMT], X-Android-Received-Millis=[1467916086556], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467916086507]}
,07-07 20:28:06.557   454   671 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-07 20:28:06.557   454   671 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-07 20:28:06.557   454   671 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-07 20:28:06.558   454   671 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-07 20:28:06.569  2958  3199 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-07 20:28:06.574  2635  3208 V GoogleAuthProtoRequest: [252] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:28:06.586  1103  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-07 20:28:06.586  1103  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-07 20:28:06.586  1103  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:28:06.586  1103  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:28:06.594  2635  3208 W ExperimentUpdateService: [252] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: [252] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-07 20:28:06.595  2635  3208 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-07 20:28:07.354   454   671 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-07 20:28:08.562   454   671 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-07 20:28:08.944  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:08.977  1103  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-07 20:28:08.977  1103  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-07 20:28:08.977  1103  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:28:08.977  1103  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:28:08.999  2516  2516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-07 20:28:09.000  2516  2516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-07 20:28:09.000  2516  2516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-07 20:28:10.080  3123  3151 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-07 20:28:14.293   454   671 D ConnectivityService: handlePromptUnvalidated 101
,07-07 20:28:17.622   454   669 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,07-07 20:28:23.550   454   500 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-07 20:28:23.557   454   500 I PowerManagerService: Sleeping (uid 1000)...
07-07 20:28:23.573   995   995 I Keyboard.Facilitator: onFinishInput()
,07-07 20:28:23.583   170   446 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (578 us)
,07-07 20:28:23.748  2815  2815 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-07 20:28:23.749  2815  2815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-07 20:28:23.772  2815  2815 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7c2033e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@75b7dc7, 16908290=android.view.AbsSavedState$1@75b7dc7}, android:focusedViewId=100}]}]
,07-07 20:28:23.772  2815  2815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-07 20:28:23.772  2815  2815 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-07 20:28:23.772  2815  2815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-07 20:28:23.795   454   463 I art     : Background partial concurrent mark sweep GC freed 45255(2MB) AllocSpace objects, 7(156KB) LOS objects, 33% free, 17MB/26MB, paused 1.884ms total 110.050ms
,07-07 20:28:24.346   454   500 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-07 20:28:24.356   454   500 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-07 20:28:24.360   454   497 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-07 20:28:24.373   170   170 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x559bd7e430
07-07 20:28:24.374   170   170 D hwcomposer: hwc_blank: display 0: blank
07-07 20:28:24.374   170   170 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,07-07 20:28:24.684   454   688 D SurfaceControl: Excessive delay in setPowerMode(): 310ms
,07-07 20:28:24.742   454   669 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:28:24.764   454   669 E native  : do suspend false
,07-07 20:28:24.776   454   669 D WifiConfigStore: No blacklist allowed without epno enabled
,07-07 20:28:24.786   454   669 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:28:24.794   454   669 E native  : do suspend true
,07-07 20:28:25.253   454   669 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,07-07 20:28:26.258   454   669 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,07-07 20:28:27.329  1059  1551 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:28:29.110  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:29.116  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:29.118  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:29.142  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-07 20:28:29.142  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-07 20:28:29.142  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:28:29.142  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:28:29.162  2516  2516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-07 20:28:29.163  2516  2516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-07 20:28:29.163  2516  2516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-07 20:28:30.931   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175913, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:28:37.459  2782  3212 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:28:37.481  2782  3213 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-07 20:28:37.491  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:37.493  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:37.516  1103  1163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:28:37.516  1103  1163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:28:37.516  1103  1163 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:28:37.516  1103  1163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:28:37.537  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:37.539  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:37.557  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:28:37.558  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:28:37.558  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:28:37.558  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:28:37.572  2782  3213 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-07 20:28:37.575  2782  3212 E BooksSync: Soft error
07-07 20:28:37.575  2782  3212 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:28:37.575  2782  3212 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:28:37.575  2782  3212 E BooksSync: Sync error
07-07 20:28:37.575  2782  3212 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:28:37.575  2782  3212 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:28:37.575  2782  3212 I BooksSync: Finished books sync
,07-07 20:28:37.583   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 182129, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:28:54.974  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:54.981  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:54.982  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:28:55.002  1103  1122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-07 20:28:55.003  1103  1122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-07 20:28:55.003  1103  1122 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:28:55.003  1103  1122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:28:55.020  2516  2516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-07 20:28:55.020  2516  2516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-07 20:28:55.021  2516  2516 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-07 20:28:59.887   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=204869, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:29:02.891  1103  1300 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:29:06.665  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:29:06.668  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:29:06.680  2635  3214 V GoogleAuthProtoRequest: [253] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:29:06.703  1103  1163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-07 20:29:06.703  1103  1163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-07 20:29:06.704  1103  1163 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:29:06.704  1103  1163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:29:06.719  2635  3214 W ExperimentUpdateService: [253] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: [253] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-07 20:29:06.720  2635  3214 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-07 20:29:07.742  2077  3215 V KeepSync: Connecting to GoogleApiClient
,07-07 20:29:07.742   454  1152 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-07 20:29:07.791  1103  1163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-07 20:29:07.791  1103  1163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-07 20:29:07.791  1103  1163 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:29:07.791  1103  1163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:29:07.805  1224  3216 V BaseAuthAsyncOperation: access token request failed
,07-07 20:29:07.807  2077  3215 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:29:07.859  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-07 20:29:07.859  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-07 20:29:07.860  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:29:07.860  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:29:07.901  2077  3215 E KeepSync: IOException
07-07 20:29:07.901  2077  3215 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:29:07.901  2077  3215 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:29:07.901  2077  3215 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:29:07.901  2077  3215 E KeepSync: 	... 10 more
,07-07 20:29:07.910  2077  3215 W KeepSync: Sync result 2
,07-07 20:29:07.917   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 183708, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:29:23.616   995  1102 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-07 20:29:23.617   995  1102 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-07 20:29:23.664  1103  1103 I ConfigService: onCreate
,07-07 20:29:24.405   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229387, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:29:28.767  1103  1103 I ConfigService: onDestroy
,07-07 20:29:38.130  2782  3218 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:29:38.151  2782  3219 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-07 20:29:38.163  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:29:38.164  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:29:38.186  1103  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:29:38.186  1103  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:29:38.186  1103  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:29:38.186  1103  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:29:38.208  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:29:38.210  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:29:38.228  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:29:38.229  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:29:38.229  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:29:38.229  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:29:38.244  2782  3219 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-07 20:29:38.244  2782  3218 E BooksSync: Soft error
07-07 20:29:38.244  2782  3218 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:29:38.244  2782  3218 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:29:38.245  2782  3218 E BooksSync: Sync error
07-07 20:29:38.245  2782  3218 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:29:38.245  2782  3218 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:29:38.245  2782  3218 I BooksSync: Finished books sync
,07-07 20:29:38.251   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 213691, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:30:12.394   454   454 I ActivityManager: Start proc 3220:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-07 20:30:12.498  3220  3220 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,07-07 20:30:12.536  3220  3220 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-07 20:30:12.536  3220  3220 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-07 20:30:12.536  3220  3220 I GAv4    :   adb logcat -s GAv4
,07-07 20:30:12.557  3220  3220 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:30:12.565  3220  3220 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:30:12.579  3220  3235 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:30:12.697  2077  3236 V KeepSync: Connecting to GoogleApiClient
,07-07 20:30:12.698   454  1152 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-07 20:30:12.747  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:30:12.750  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:30:12.778  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-07 20:30:12.778  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-07 20:30:12.778  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:30:12.778  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:30:12.799  1224  3237 V BaseAuthAsyncOperation: access token request failed
,07-07 20:30:12.800  2077  3236 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:30:12.852  1103  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-07 20:30:12.852  1103  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-07 20:30:12.852  1103  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:30:12.852  1103  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:30:12.868  2077  3236 E KeepSync: IOException
07-07 20:30:12.868  2077  3236 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:30:12.868  2077  3236 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:30:12.868  2077  3236 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:30:12.868  2077  3236 E KeepSync: 	... 10 more
,07-07 20:30:12.868  2077  3236 W KeepSync: Sync result 2
,07-07 20:30:12.875   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 277319, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:30:36.672   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=301654, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:30:43.060  2782  3238 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:30:43.110  2782  3239 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-07 20:30:43.137  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:30:43.144  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:30:43.164  1103  1122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:30:43.164  1103  1122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:30:43.164  1103  1122 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:30:43.164  1103  1122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:30:43.186  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:30:43.188  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:30:43.207  1103  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:30:43.207  1103  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:30:43.207  1103  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:30:43.207  1103  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:30:43.221  2782  3239 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-07 20:30:43.222  2782  3238 E BooksSync: Soft error
07-07 20:30:43.222  2782  3238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:30:43.222  2782  3238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:30:43.222  2782  3238 E BooksSync: Sync error
07-07 20:30:43.222  2782  3238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:30:43.222  2782  3238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:30:43.222  2782  3238 I BooksSync: Finished books sync
,07-07 20:30:43.229   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 305484, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:31:00.832   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325814, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:31:06.782  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:06.784  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:06.796  2635  3240 V GoogleAuthProtoRequest: [254] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:31:06.817  1103  1163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-07 20:31:06.817  1103  1163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-07 20:31:06.817  1103  1163 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:31:06.817  1103  1163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: [254] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: [254] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-07 20:31:06.832  2635  3240 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-07 20:31:26.845   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=351827, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:31:35.374  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:35.394  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:35.399  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:35.454  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-07 20:31:35.454  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-07 20:31:35.454  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:31:35.455  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:31:35.503  1103  1308 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-07 20:31:35.503  1103  1308 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-07 20:31:35.503  1103  1308 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-07 20:31:35.503  1103  1308 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-07 20:31:35.503  1103  1308 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-07 20:31:35.503  1103  1308 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-07 20:31:35.503  1103  1308 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-07 20:31:35.510  2516  2545 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-07 20:31:35.510  2516  2545 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-07 20:31:35.510  2516  2545 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-07 20:31:35.510  2516  2545 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-07 20:31:35.510  2516  2545 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-07 20:31:35.510  2516  2545 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-07 20:31:35.510  2516  2545 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-07 20:31:59.952   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=384934, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:32:11.752   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=396734, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:32:21.816  2077  3244 V KeepSync: Connecting to GoogleApiClient
,07-07 20:32:21.816   454  1152 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-07 20:32:21.857  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:21.859  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:21.881  1103  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-07 20:32:21.881  1103  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-07 20:32:21.881  1103  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:32:21.881  1103  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:32:21.895  1224  3245 V BaseAuthAsyncOperation: access token request failed
07-07 20:32:21.896  2077  3244 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:32:21.947  1103  1122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-07 20:32:21.947  1103  1122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-07 20:32:21.948  1103  1122 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:32:21.948  1103  1122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:32:21.963  2077  3244 E KeepSync: IOException
07-07 20:32:21.963  2077  3244 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:32:21.963  2077  3244 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:32:21.963  2077  3244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:32:21.963  2077  3244 E KeepSync: 	... 10 more
,07-07 20:32:21.963  2077  3244 W KeepSync: Sync result 2
,07-07 20:32:21.968   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 406690, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:32:35.872   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=420854, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:32:52.077  2782  3246 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:32:52.128  2782  3247 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-07 20:32:52.154  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:52.159  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:52.209  1103  1118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:32:52.210  1103  1118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:32:52.210  1103  1118 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:32:52.211  1103  1118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:32:52.241  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:52.243  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:52.262  1103  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:32:52.262  1103  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:32:52.262  1103  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:32:52.262  1103  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:32:52.277  2782  3247 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:32:52.278  2782  3246 E BooksSync: Soft error
07-07 20:32:52.278  2782  3246 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:32:52.278  2782  3246 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:32:52.278  2782  3246 E BooksSync: Sync error
07-07 20:32:52.278  2782  3246 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:32:52.278  2782  3246 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:32:52.278  2782  3246 I BooksSync: Finished books sync
,07-07 20:32:52.286   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 432712, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:33:11.565   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=456547, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:33:35.712   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=480694, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:33:43.232   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=488214, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:34:07.392   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=512374, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:34:14.859   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=519841, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:34:39.232   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=544214, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:35:06.946  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:06.952  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:06.974  2635  3249 V GoogleAuthProtoRequest: [255] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:35:06.997  1103  1163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-07 20:35:06.997  1103  1163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-07 20:35:06.997  1103  1163 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:06.997  1103  1163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:07.011  2635  3249 W ExperimentUpdateService: [255] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: [255] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-07 20:35:07.012  2635  3249 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-07 20:35:41.045   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=606027, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:36:05.152   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=630134, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:36:39.739  2077  3254 V KeepSync: Connecting to GoogleApiClient
07-07 20:36:39.739   454   470 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-07 20:36:39.837  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:36:39.839  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:36:39.866  1103  1163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-07 20:36:39.866  1103  1163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-07 20:36:39.866  1103  1163 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:36:39.866  1103  1163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:36:39.889   454   463 I art     : Background partial concurrent mark sweep GC freed 35830(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 17MB/26MB, paused 1.788ms total 126.258ms
,07-07 20:36:39.895  1224  3256 V BaseAuthAsyncOperation: access token request failed
,07-07 20:36:39.896  2077  3254 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:36:39.946  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-07 20:36:39.946  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-07 20:36:39.946  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:36:39.946  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:36:39.960  2077  3254 E KeepSync: IOException
07-07 20:36:39.960  2077  3254 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:36:39.960  2077  3254 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:36:39.960  2077  3254 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:36:39.960  2077  3254 E KeepSync: 	... 10 more
,07-07 20:36:39.960  2077  3254 W KeepSync: Sync result 2
,07-07 20:36:39.966   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 664615, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:36:40.872   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=665854, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:37:05.152   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=690133, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:37:10.115  2782  3259 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:37:10.132  2782  3261 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-07 20:37:10.140  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:10.143  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:10.163  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:37:10.163  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:37:10.163  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:37:10.163  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:37:10.185  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:10.187  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:10.205  1103  1122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:37:10.206  1103  1122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:37:10.206  1103  1122 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:37:10.206  1103  1122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:37:10.221  2782  3261 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-07 20:37:10.223  2782  3259 E BooksSync: Soft error
07-07 20:37:10.223  2782  3259 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:37:10.223  2782  3259 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:37:10.223  2782  3259 E BooksSync: Sync error
07-07 20:37:10.223  2782  3259 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:37:10.223  2782  3259 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:37:10.223  2782  3259 I BooksSync: Finished books sync
,07-07 20:37:10.229   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 686269, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:38:39.883  1103  1300 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:43:07.085  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:43:07.088  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:43:07.097  2635  3263 V GoogleAuthProtoRequest: [256] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:43:07.120  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-07 20:43:07.120  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-07 20:43:07.121  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:43:07.121  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: [256] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: [256] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-07 20:43:07.136  2635  3263 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-07 20:43:12.045   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1057027, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:43:23.231   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1068214, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:45:15.677  2077  3265 V KeepSync: Connecting to GoogleApiClient
07-07 20:45:15.678   454  1076 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-07 20:45:15.717  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:45:15.719  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:45:15.740  1103  1122 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-07 20:45:15.740  1103  1122 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-07 20:45:15.741  1103  1122 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:45:15.741  1103  1122 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:45:15.755  1224  3266 V BaseAuthAsyncOperation: access token request failed
,07-07 20:45:15.756  2077  3265 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:45:15.806  1103  1308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-07 20:45:15.807  1103  1308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-07 20:45:15.807  1103  1308 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:45:15.807  1103  1308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:45:15.822  2077  3265 E KeepSync: IOException
07-07 20:45:15.822  2077  3265 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:45:15.822  2077  3265 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:45:15.822  2077  3265 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:45:15.822  2077  3265 E KeepSync: 	... 10 more
,07-07 20:45:15.822  2077  3265 W KeepSync: Sync result 2
,07-07 20:45:15.828   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1180277, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:45:45.947  2782  3267 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:45:46.006  2782  3268 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-07 20:45:46.033  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:45:46.040  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:45:46.098  1103  1118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:45:46.098  1103  1118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:45:46.098  1103  1118 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:45:46.099  1103  1118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:45:46.155  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:45:46.160  1103  1103 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:45:46.206  1103  1163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:45:46.206  1103  1163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:45:46.207  1103  1163 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:45:46.207  1103  1163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:45:46.234  2782  3268 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:45:46.234  2782  3267 E BooksSync: Soft error
07-07 20:45:46.234  2782  3267 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:45:46.234  2782  3267 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:45:46.235  2782  3267 E BooksSync: Sync error
07-07 20:45:46.235  2782  3267 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:45:46.235  2782  3267 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:45:46.235  2782  3267 I BooksSync: Finished books sync
,07-07 20:45:46.241   454   483 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1193212, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:46:10.377   454   483 I UsageStatsService: User[0] Flushing usage stats to disk
,07-07 20:47:19.205   454  1044 I ActivityManager: Start proc 3271:com.google.android.youtube/u0a81 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-07 20:47:19.281   454   463 I art     : Background partial concurrent mark sweep GC freed 28027(1782KB) AllocSpace objects, 9(180KB) LOS objects, 33% free, 17MB/26MB, paused 1.948ms total 110.983ms
,07-07 20:47:19.309  3271  3271 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,07-07 20:47:19.597  3271  3283 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-07 20:47:19.784  3271  3283 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-07 20:47:19.843  3271  3283 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-07 20:47:19.947  3271  3271 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-07 20:47:20.065  3296  3296 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1387998668.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1387998668.dex
,07-07 20:47:20.186  3271  3271 W InstanceID/Rpc: Found 10007
,07-07 20:47:20.328  3296  3296 I dex2oat : dex2oat took 264.505ms (threads: 2) arena alloc=187KB java alloc=33KB native alloc=758KB free=65KB
,07-07 20:47:20.356   454  1152 I ActivityManager: Killing 2240:com.google.android.gms.wearable/u0a7 (adj 15): empty #17
,07-07 20:47:25.364   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1310347, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:47:30.445   454  3184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1315427, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:47:46.272  1103  1300 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,TIME-OUT KILL (timeout was 1400000ms)
```
